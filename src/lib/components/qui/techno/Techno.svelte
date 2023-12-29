<script>
  import { darkMode } from '../../../store/dark.js';
  
  import htmld from '../../../images/SVG/technod/htmld.svg';
  import cssd from '../../../images/SVG/technod/cssd.svg';
  import svelted from '../../../images/SVG/technod/svelted.svg';
  import tailwindd from '../../../images/SVG/technod/tailwindd.svg';
  import jsd from '../../../images/SVG/technod/javascriptd.svg';
  import tsd from '../../../images/SVG/technod/typescriptd.svg';
  import nextd from '../../../images/SVG/technod/nextd.svg';
  import pythond from '../../../images/SVG/technod/pythond.svg';
  import sqld from '../../../images/SVG/technod/databased.svg';
  import gitd from '../../../images/SVG/technod/gitd.svg';

  import htmlw from '../../../images/SVG/technow/htmlw.svg';
  import cssw from '../../../images/SVG/technow/cssw.svg';
  import sveltew from '../../../images/SVG/technow/sveltew.svg';
  import tailwindw from '../../../images/SVG/technow/tailwindw.svg';
  import jsw from '../../../images/SVG/technow/javascriptw.svg';
  import tsw from '../../../images/SVG/technow/typescriptw.svg';
  import nextw from '../../../images/SVG/technow/nextw.svg';
  import pythonw from '../../../images/SVG/technow/pythonw.svg';
  import sqlw from '../../../images/SVG/technow/databasew.svg';
  import gitw from '../../../images/SVG/technow/gitw.svg';

let darkModeValue = false;

darkMode.subscribe(value => {
  darkModeValue = value;
});
</script>

<div class="transition-colors duration-500 flex flex-col items-center justify-center pt-[50px] pb-[50px] bg-[#f4f3fc] dark:bg-[#0C0C12]" id="techno-container">

  <h1 class="transition-colors duration-500 font-extrabold pb-4 text-[50px] text-[#ff9900] dark:text-[#FFC000] font-family: 'Outfit', sans-serif" id="technologies">Technologies utilisées :</h1>

  <div class="flex flex-row" id="row">

    <a class="flex items-center no-underline" href="https://developer.mozilla.org/fr/docs/Web/HTML" target="_blank">
      <div class="relative transition-colors duration-500 group flex items-center bg-[#d4d5e2] dark:bg-[#14141E] p-5 m-5 rounded-[300px] hover:bg-[#c7c9d8] dark:hover:bg-[#191925] hover:cursor-pointer" id="html-container">
        <img src={htmld} alt="HTML Noir" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-[25px]' : 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-[25px]'}>
        <img src={htmlw} alt="HTML Blanc" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-[25px]' : 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-[25px]'}>
        <p class="ml-9 transition-colors duration-500 text-xl text-[#5e5e5e] group-hover:text-black dark:text-[#a2a4b3] dark:group-hover:text-white no-underline font-family: 'Outfit', sans-serif">HTML</p>
      </div>
    </a>

    <a class="flex items-center no-underline" href="https://developer.mozilla.org/fr/docs/Web/CSS" target="_blank">
      <div class="relative transition-colors duration-500 group flex items-center bg-[#d4d5e2] dark:bg-[#14141E] p-5 m-5 rounded-[300px] hover:bg-[#c7c9d8] dark:hover:bg-[#191925] hover:cursor-pointer" id="css-container">
        <img src={cssd} alt="CSS Noir" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-[25px]' : 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-[25px]'}>
        <img src={cssw} alt="CSS Blanc" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-[25px]' : 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-[25px]'}>
        <p class="ml-9 transition-colors duration-500 text-xl text-[#5e5e5e] group-hover:text-black dark:text-[#a2a4b3] dark:group-hover:text-white no-underline font-family: 'Outfit', sans-serif">CSS</p>
      </div>
    </a>

    <a class="flex items-center no-underline" href="https://svelte.dev/" target="_blank">
      <div class="relative transition-colors duration-500 group flex items-center bg-[#d4d5e2] dark:bg-[#14141E] p-5 m-5 rounded-[300px] hover:bg-[#c7c9d8] dark:hover:bg-[#191925] hover:cursor-pointer" id="svelte-container">
        <img src={svelted} alt="Svelte Noir" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-[25px]' : 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-[25px]'}>
        <img src={sveltew} alt="Svelte Blanc" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-[25px]' : 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-[25px]'}>
        <p class="ml-9 transition-colors duration-500 text-xl text-[#5e5e5e] group-hover:text-black dark:text-[#a2a4b3] dark:group-hover:text-white no-underline font-family: 'Outfit', sans-serif">Svelte</p>
      </div>
    </a>

    <a class="flex items-center no-underline" href="https://tailwindcss.com/" target="_blank">
      <div class="relative transition-colors duration-500 group flex items-center bg-[#d4d5e2] dark:bg-[#14141E] p-5 m-5 rounded-[300px] hover:bg-[#c7c9d8] dark:hover:bg-[#191925] hover:cursor-pointer" id="tailwindcss-container">
        <img src={tailwindd} alt="TailwindCSS Noir" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-[25px]' : 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-[25px]'}>
        <img src={tailwindw} alt="TailwindCSS Blanc" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-[25px]' : 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-[25px]'}>
        <p class="ml-9 transition-colors duration-500 text-xl text-[#5e5e5e] group-hover:text-black dark:text-[#a2a4b3] dark:group-hover:text-white no-underline font-family: 'Outfit', sans-serif">TailwindCSS</p>
      </div>
    </a>

    <a class="flex items-center no-underline" href="https://developer.mozilla.org/fr/docs/Web/JavaScript" target="_blank">
      <div class="relative transition-colors duration-500 group flex items-center bg-[#d4d5e2] dark:bg-[#14141E] p-5 m-5 rounded-[300px] hover:bg-[#c7c9d8] dark:hover:bg-[#191925] hover:cursor-pointer" id="js-container">
        <img src={jsd} alt="JavaScript Noir" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-[25px]' : 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-[25px]'}>
        <img src={jsw} alt="JavaScript Blanc" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-[25px]' : 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-[25px]'}>
        <p class="ml-9 transition-colors duration-500 text-xl text-[#5e5e5e] group-hover:text-black dark:text-[#a2a4b3] dark:group-hover:text-white no-underline font-family: 'Outfit', sans-serif">JavaScript</p>
      </div>
    </a>

  </div>

  
  <div class="flex flex-row" id="row">

    <a class="flex items-center no-underline" href="https://www.typescriptlang.org/" target="_blank">
      <div class="relative transition-colors duration-500 group flex items-center bg-[#d4d5e2] dark:bg-[#14141E] p-5 m-5 rounded-[300px] hover:bg-[#c7c9d8] dark:hover:bg-[#191925] hover:cursor-pointer" id="ts-container">
        <img src={tsd} alt="TypeScript Noir" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-[25px]' : 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-[25px]'}>
        <img src={tsw} alt="TypeScript Blanc" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-[25px]' : 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-[25px]'}>
        <p class="ml-9 transition-colors duration-500 text-xl text-[#5e5e5e] group-hover:text-black dark:text-[#a2a4b3] dark:group-hover:text-white no-underline font-family: 'Outfit', sans-serif">TypeScript</p>
      </div>
    </a>

    <a class="flex items-center no-underline" href="https://nextjs.org/" target="_blank">
      <div class="relative transition-colors duration-500 group flex items-center bg-[#d4d5e2] dark:bg-[#14141E] p-5 m-5 rounded-[300px] hover:bg-[#c7c9d8] dark:hover:bg-[#191925] hover:cursor-pointer" id="next-container">
        <img src={nextd} alt="NextJS Noir" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-[25px]' : 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-[25px]'}>
        <img src={nextw} alt="NextJS Blanc" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-[25px]' : 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-[25px]'}>
        <p class="ml-9 transition-colors duration-500 text-xl text-[#5e5e5e] group-hover:text-black dark:text-[#a2a4b3] dark:group-hover:text-white no-underline font-family: 'Outfit', sans-serif">Next.JS</p>
      </div>
    </a>

    <a class="flex items-center no-underline" href="https://python.org/" target="_blank">
      <div class="relative transition-colors duration-500 group flex items-center bg-[#d4d5e2] dark:bg-[#14141E] p-5 m-5 rounded-[300px] hover:bg-[#c7c9d8] dark:hover:bg-[#191925] hover:cursor-pointer" id="python-container">
        <img src={pythond} alt="Python Noir" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-[25px]' : 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-[25px]'}>
        <img src={pythonw} alt="Python Blanc" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-[25px]' : 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-[25px]'}>
        <p class="ml-9 transition-colors duration-500 text-xl text-[#5e5e5e] group-hover:text-black dark:text-[#a2a4b3] dark:group-hover:text-white no-underline font-family: 'Outfit', sans-serif">Python</p>
      </div>
    </a>

    <a class="flex items-center no-underline" href="https://sql.sh/" target="_blank">
      <div class="relative transition-colors duration-500 group flex items-center bg-[#d4d5e2] dark:bg-[#14141E] p-5 m-5 rounded-[300px] hover:bg-[#c7c9d8] dark:hover:bg-[#191925] hover:cursor-pointer" id="sql-container">
        <img src={sqld} alt="SQL Noir" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-[25px]' : 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-[25px]'}>
        <img src={sqlw} alt="SQL Blanc" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-[25px]' : 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-[25px]'}>
        <p class="ml-9 transition-colors duration-500 text-xl text-[#5e5e5e] group-hover:text-black dark:text-[#a2a4b3] dark:group-hover:text-white no-underline font-family: 'Outfit', sans-serif">SQL</p>
      </div>
    </a>

    <a class="flex items-center no-underline" href="https://git-scm.com/" target="_blank">
      <div class="relative transition-colors duration-500 group flex items-center bg-[#d4d5e2] dark:bg-[#14141E] p-5 m-5 rounded-[300px] hover:bg-[#c7c9d8] dark:hover:bg-[#191925] hover:cursor-pointer" id="git-container">
        <img src={gitd} alt="GIT Noir" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-[25px]' : 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-[25px]'}>
        <img src={gitw} alt="GIT Blanc" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-[25px]' : 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-[25px]'}>
        <p class="ml-9 transition-colors duration-500 text-xl text-[#5e5e5e] group-hover:text-black dark:text-[#a2a4b3] dark:group-hover:text-white no-underline font-family: 'Outfit', sans-serif">GIT & GitHub</p>
      </div>
    </a>

  </div>

</div>