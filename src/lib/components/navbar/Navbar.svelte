<script>
  import { onMount } from 'svelte';
  import { domCookie } from "cookie-muncher";
  import moon from '../../images/SVG/navbar/moon.svg';
  import sun from '../../images/SVG/navbar/sun.svg';
  import tradb from '../../images/SVG/navbar/tradb.svg';
  import tradw from '../../images/SVG/navbar/tradw.svg';

  let darkMode = false;
  let searchQuery = '';

  const toggleTheme = () => {
    darkMode = !darkMode;
    if (darkMode) {
      document.body.classList.add('dark');
    } else {
      document.body.classList.remove('dark');
    }
    saveUserChoice(darkMode);
  };

  /**
 * @param {boolean} isDarkModeEnabled
 */
  function saveUserChoice(isDarkModeEnabled) {
    const cookie = {
      name: "darkMode",
      value: isDarkModeEnabled ? "enabled" : "disabled"
    };
    domCookie.set(cookie);
  }

  function loadUserChoice() {
    const cookie = domCookie.get("darkMode");
    if (cookie) {
      if (cookie.value === "enabled") {
        darkMode = true;
        document.body.classList.add('dark');
      } else {
        darkMode = false;
        document.body.classList.remove('dark');
      }
    } else if (window.matchMedia && window.matchMedia('(prefers-color-scheme: dark)').matches) {
      darkMode = true;
      document.body.classList.add('dark');
      saveUserChoice(true);
    }
  }

  onMount(loadUserChoice);
</script>

<div class="fixed top-0 left-0 flex items-center justify-center w-full z-50 pt-5 pb-5" id="navbar">

  <div class="bg-[#d4d5e2] dark:bg-[#14141E] cursor-pointer h-max w-max rounded-[20px] border-2 border-solid border-[#aaabbb] dark:border-[#868796] hover:bg-[#bdbeca] dark:hover:bg-[#23232e] hover:border-2 hover:border-[#9697a5] dark:hover:border-[#b5b6c9]" id="theme" on:click={toggleTheme}>
    <button class="mx-[10px] my-[10px]">
      <img src={darkMode ? sun : moon} alt={darkMode ? 'Thème Clair' : 'Thème Sombre'}>
    </button>
  </div>

  <div class="bg-[#d4d5e2] dark:bg-[#14141E] flex items-center justify-between w-[350px] mx-5 my-0 px-2.5 py-[5px] rounded-[20px] border-2 border-solid border-[#aaabbb] dark:border-[#868796]" id="page">
    <a class="text-[#5e5e5e] dark:text-[#a2a4b3] text-[17px] no-underline m-2.5 hover:text-[#000000] dark:hover:text-[#ffffff] font-family: 'Outfit', sans-serif" href="/">/Qui suis-je</a>
    <a class="text-[#5e5e5e] dark:text-[#a2a4b3] text-[17px] no-underline m-2.5 hover:text-[#000000] dark:hover:text-[#ffffff] font-family: 'Outfit', sans-serif" href="/creations">/Créations</a>
    <a class="text-[#5e5e5e] dark:text-[#a2a4b3] text-[17px] no-underline m-2.5 hover:text-[#000000] dark:hover:text-[#ffffff] font-family: 'Outfit', sans-serif" href="/informations">/Informations</a>
  </div>
 
  <button class="mx-[10px] my-[10px]">
  <div class="bg-[#d4d5e2] dark:bg-[#14141E] cursor-pointer h-max w-max rounded-[20px] border-2 border-solid border-[#aaabbb] dark:border-[#868796] hover:bg-[#bdbeca] dark:hover:bg-[#23232e] hover:border-2 hover:border-[#9697a5] dark:hover:border-[#b5b6c9]" id="langue">
    <button class="mx-[10px] my-[10px]">
      <img src={darkMode ? tradw : tradb} alt={darkMode ? 'Thème Clair' : 'Thème Sombre'}>
    </button>
  </div>

</div>