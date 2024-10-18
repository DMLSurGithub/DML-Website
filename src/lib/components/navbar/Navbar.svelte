<script>
  import { onMount } from 'svelte';
  import { domCookie } from "cookie-muncher";
  import { darkMode } from '../../store/dark.js';
  import moon from '../../images/SVG/navbar/moon.svg';
  import sun from '../../images/SVG/navbar/sun.svg';
  import tradb from '../../images/SVG/navbar/tradb.svg';
  import tradw from '../../images/SVG/navbar/tradw.svg';

  const toggleTheme = () => {
    darkMode.update(value => !value);
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

  onMount(() => {
    const cookie = domCookie.get("darkMode");
    if (cookie) {
      if (cookie.value === "enabled") {
        darkMode.set(true);
      } else {
        darkMode.set(false);
      }
    } else if (window.matchMedia && window.matchMedia('(prefers-color-scheme: dark)').matches) {
      darkMode.set(true);
    }

    darkMode.subscribe(value => {
      if (value) {
        document.body.classList.add('dark');
      } else {
        document.body.classList.remove('dark');
      }
      saveUserChoice(value);
    });
  });
</script>

<div class="fixed flex items-center justify-center w-full pt-" id="navbar">

  <div class="transition-all duration-500 group bg-[#d4d5e2] dark:bg-[#14141E] flex justify-center items-center cursor-pointer rounded-[20px] w-[53.5px] h-[53.5px] border-2 border-solid border-[#aaabbb] dark:border-[#868796] hover:bg-[#bdbeca] dark:hover:bg-[#23232e] hover:border-2 hover:border-[#9697a5] dark:hover:border-[#b5b6c9]" id="theme" on:click={toggleTheme} role="button" tabindex="0" on:keydown={e => {if (e.key === 'Enter') toggleTheme()}}>
    <div class="mx-[10px] my-[10px]">
      <img class="group-hover:brightness-[-180%] dark:group-hover:brightness-[180%] w-[25px]" src={darkMode ? sun : moon} alt={darkMode ? 'Thème Clair' : 'Thème Sombre'}>
    </div>
  </div>

  <div class="transition-colors duration-500 bg-[#d4d5e2] dark:bg-[#14141E] flex justify-between w-[290px] h-[53.5px] mx-3 px-1 py-1 rounded-[15px] border-2 border-solid border-[#aaabbb] dark:border-[#868796]" id="page">
    <a class="transition-colors duration-500 text-[#5e5e5e] dark:text-[#a2a4b3] text-[15px] m-2.5 hover:text-[#000000] dark:hover:text-[#ffffff] font-family: 'Outfit', sans-serif" href="/">/Qui suis-je</a>
    <a class="transition-colors duration-500 text-[#5e5e5e] dark:text-[#a2a4b3] text-[15px] m-2.5 hover:text-[#000000] dark:hover:text-[#ffffff] font-family: 'Outfit', sans-serif" href="/creations">/Créations</a>
    <a class="transition-colors duration-500 text-[#5e5e5e] dark:text-[#a2a4b3] text-[15px] m-2.5 hover:text-[#000000] dark:hover:text-[#ffffff] font-family: 'Outfit', sans-serif" href="/contact">/Contact</a>
  </div>
 
  <div class="transition-colors duration-500 group bg-[#d4d5e2] dark:bg-[#14141E] flex justify-center items-center cursor-pointer rounded-[20px] w-[53.5px] h-[53.5px] border-2 border-solid border-[#aaabbb] dark:border-[#868796] hover:bg-[#bdbeca] dark:hover:bg-[#23232e] hover:border-2 hover:border-[#9697a5] dark:hover:border-[#b5b6c9]" id="langue">
    <button class="mx-[10px] my-[10px]">
      <img class="group-hover:brightness-[-180%] dark:group-hover:brightness-[180%] w-[25px]" src={darkMode ? tradw : tradb} alt={darkMode ? 'Thème Clair' : 'Thème Sombre'}>
    </button>
  </div>

</div>