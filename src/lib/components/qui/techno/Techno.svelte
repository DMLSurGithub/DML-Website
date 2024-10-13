<script>
  import { darkMode } from '../../../store/dark.js';
  
  import htmld from '../../../images/SVG/technod/htmld.svg';
  import cssd from '../../../images/SVG/technod/cssd.svg';
  import svelted from '../../../images/SVG/technod/svelted.svg';
  import tailwindd from '../../../images/SVG/technod/tailwindd.svg';
  import pythond from '../../../images/SVG/technod/pythond.svg';
  import sqld from '../../../images/SVG/technod/databased.svg';
  import gitd from '../../../images/SVG/technod/gitd.svg';

  import htmlw from '../../../images/SVG/technow/htmlw.svg';
  import cssw from '../../../images/SVG/technow/cssw.svg';
  import sveltew from '../../../images/SVG/technow/sveltew.svg';
  import tailwindw from '../../../images/SVG/technow/tailwindw.svg';
  import pythonw from '../../../images/SVG/technow/pythonw.svg';
  import sqlw from '../../../images/SVG/technow/databasew.svg';
  import gitw from '../../../images/SVG/technow/gitw.svg';

let darkModeValue = false;

darkMode.subscribe(value => {
  darkModeValue = value;
});
</script>

<div class="transition-colors duration-500 flex flex-col items-center justify-center pt-[50px] bg-[#f4f3fc] dark:bg-[#0C0C12]" id="techno-container">

  <h1 class="transition-colors duration-500 font-extrabold pb-7 text-[40px] text-[#ff9900] dark:text-[#FFC000] font-family: 'Outfit', sans-serif" id="technologies">Technologies utilisées :</h1>

  <div class="flex flex-row" id="row">

    <a class="flex items-center no-underline" href="https://developer.mozilla.org/fr/docs/Web/HTML" target="_blank">
      <div class="relative transition-colors duration-500 group flex items-center bg-[#d4d5e2] dark:bg-[#14141E] py-3 px-4 m-3 rounded-[300px] hover:bg-[#c7c9d8] dark:hover:bg-[#191925] hover:cursor-pointer" id="html-container">
        <img src={htmld} alt="HTML Noir" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-[20px]' : 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-[20px]'}>
        <img src={htmlw} alt="HTML Blanc" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-[20px]' : 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-[20px]'}>
        <p class="ml-7 transition-colors duration-500 text-l text-[#5e5e5e] group-hover:text-black dark:text-[#a2a4b3] dark:group-hover:text-white no-underline font-family: 'Outfit', sans-serif">HTML</p>
      </div>
    </a>

    <a class="flex items-center no-underline" href="https://developer.mozilla.org/fr/docs/Web/CSS" target="_blank">
      <div class="relative transition-colors duration-500 group flex items-center bg-[#d4d5e2] dark:bg-[#14141E] py-3 px-4 m-3 rounded-[300px] hover:bg-[#c7c9d8] dark:hover:bg-[#191925] hover:cursor-pointer" id="css-container">
        <img src={cssd} alt="CSS Noir" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-[20px]' : 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-[20px]'}>
        <img src={cssw} alt="CSS Blanc" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-[20px]' : 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-[20px]'}>
        <p class="ml-7 transition-colors duration-500 text-l text-[#5e5e5e] group-hover:text-black dark:text-[#a2a4b3] dark:group-hover:text-white no-underline font-family: 'Outfit', sans-serif">CSS</p>
      </div>
    </a>

    <a class="flex items-center no-underline" href="https://svelte.dev/" target="_blank">
      <div class="relative transition-colors duration-500 group flex items-center bg-[#d4d5e2] dark:bg-[#14141E] py-3 px-4 m-3 rounded-[300px] hover:bg-[#c7c9d8] dark:hover:bg-[#191925] hover:cursor-pointer" id="svelte-container">
        <img src={svelted} alt="Svelte Noir" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-[20px]' : 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-[20px]'}>
        <img src={sveltew} alt="Svelte Blanc" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-[20px]' : 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-[20px]'}>
        <p class="ml-7 transition-colors duration-500 text-l text-[#5e5e5e] group-hover:text-black dark:text-[#a2a4b3] dark:group-hover:text-white no-underline font-family: 'Outfit', sans-serif">Svelte</p>
      </div>
    </a>

    <a class="flex items-center no-underline" href="https://tailwindcss.com/" target="_blank">
      <div class="relative transition-colors duration-500 group flex items-center bg-[#d4d5e2] dark:bg-[#14141E] py-3 px-4 m-3 rounded-[300px] hover:bg-[#c7c9d8] dark:hover:bg-[#191925] hover:cursor-pointer" id="tailwindcss-container">
        <img src={tailwindd} alt="TailwindCSS Noir" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-[20px]' : 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-[20px]'}>
        <img src={tailwindw} alt="TailwindCSS Blanc" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-[20px]' : 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-[20px]'}>
        <p class="ml-7 transition-colors duration-500 text-l text-[#5e5e5e] group-hover:text-black dark:text-[#a2a4b3] dark:group-hover:text-white no-underline font-family: 'Outfit', sans-serif">TailwindCSS</p>
      </div>
    </a>

  </div>

  
  <div class="flex flex-row" id="row">

    <a class="flex items-center no-underline" href="https://python.org/" target="_blank">
      <div class="relative transition-colors duration-500 group flex items-center bg-[#d4d5e2] dark:bg-[#14141E] py-3 px-4 m-3 rounded-[300px] hover:bg-[#c7c9d8] dark:hover:bg-[#191925] hover:cursor-pointer" id="python-container">
        <img src={pythond} alt="Python Noir" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-[20px]' : 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-[20px]'}>
        <img src={pythonw} alt="Python Blanc" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-[20px]' : 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-[20px]'}>
        <p class="ml-7 transition-colors duration-500 text-l text-[#5e5e5e] group-hover:text-black dark:text-[#a2a4b3] dark:group-hover:text-white no-underline font-family: 'Outfit', sans-serif">Python</p>
      </div>
    </a>

    <a class="flex items-center no-underline" href="https://sql.sh/" target="_blank">
      <div class="relative transition-colors duration-500 group flex items-center bg-[#d4d5e2] dark:bg-[#14141E] py-3 px-4 m-3 rounded-[300px] hover:bg-[#c7c9d8] dark:hover:bg-[#191925] hover:cursor-pointer" id="sql-container">
        <img src={sqld} alt="SQL Noir" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-[20px]' : 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-[20px]'}>
        <img src={sqlw} alt="SQL Blanc" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-[20px]' : 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-[20px]'}>
        <p class="ml-7 transition-colors duration-500 text-l text-[#5e5e5e] group-hover:text-black dark:text-[#a2a4b3] dark:group-hover:text-white no-underline font-family: 'Outfit', sans-serif">SQL</p>
      </div>
    </a>

    <a class="flex items-center no-underline" href="https://git-scm.com/" target="_blank">
      <div class="relative transition-colors duration-500 group flex items-center bg-[#d4d5e2] dark:bg-[#14141E] py-3 px-4 m-3 rounded-[300px] hover:bg-[#c7c9d8] dark:hover:bg-[#191925] hover:cursor-pointer" id="git-container">
        <img src={gitd} alt="GIT Noir" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-[20px]' : 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-[20px]'}>
        <img src={gitw} alt="GIT Blanc" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-[20px]' : 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-[20px]'}>
        <p class="ml-7 transition-colors duration-500 text-l text-[#5e5e5e] group-hover:text-black dark:text-[#a2a4b3] dark:group-hover:text-white no-underline font-family: 'Outfit', sans-serif">GIT & GitHub</p>
      </div>
    </a>

  </div>

</div>