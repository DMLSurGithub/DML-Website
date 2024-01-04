<script>
  import { darkMode } from '../../../store/dark.js';
  
  import htmld from '../../../images/SVG/technod/htmld.svg';
  import cssd from '../../../images/SVG/technod/cssd.svg';
  import svelted from '../../../images/SVG/technod/svelted.svg';
  import tailwindd from '../../../images/SVG/technod/tailwindd.svg';
  import jsd from '../../../images/SVG/technod/javascriptd.svg';
  import nextd from '../../../images/SVG/technod/nextd.svg';
  import pythond from '../../../images/SVG/technod/pythond.svg';
  import sqld from '../../../images/SVG/technod/databased.svg';
  import gitd from '../../../images/SVG/technod/gitd.svg';
  import tsd from '../../../images/SVG/technod/typescriptd.svg';

  import htmlw from '../../../images/SVG/technow/htmlw.svg';
  import cssw from '../../../images/SVG/technow/cssw.svg';
  import sveltew from '../../../images/SVG/technow/sveltew.svg';
  import tailwindw from '../../../images/SVG/technow/tailwindw.svg';
  import jsw from '../../../images/SVG/technow/javascriptw.svg';
  import nextw from '../../../images/SVG/technow/nextw.svg';
  import pythonw from '../../../images/SVG/technow/pythonw.svg';
  import sqlw from '../../../images/SVG/technow/databasew.svg';
  import gitw from '../../../images/SVG/technow/gitw.svg';
  import tsw from '../../../images/SVG/technow/typescriptw.svg';
  import open from '../../../images/SVG/crea/open.svg';

  let darkModeValue = false;

darkMode.subscribe(value => {
  darkModeValue = value;
});
</script>

<div class="transition-colors duration-500 flex flex-col items-center justify-center pt-[50px] pb-[50px] bg-[#f4f3fc] dark:bg-[#0C0C12]" id="portfolio">

  <div class="flex flex-row mt-[25px]" id="row">

    <div class="transition-colors duration-500 bg-[#d4d5e2] dark:bg-[#14141E] flex flex-col justify-between w-[500px] p-5 mr-[25px] rounded-[10px] relative" id="crea-container">
      <a href="https://geodia.vercel.app/" target="_blank">
        <div class="bg-red-700 hover:bg-red-600 text-white px-2 py-1 flex rounded absolute top-5 right-5" id="github-redirection">
          Not Open Source
          <img class="ml-2 mt-1 h-4" src={open} alt="Open">
        </div>
      </a>
      <div>
        <h1 class="transition-colors duration-500 text-[30px] mb-[0px] mt-[-10px] font-family: 'Outfit', sans-serif text-[#4e59d8] dark:text-[#5865f2] font-bold">Geodia Website</h1>
        <p class="transition-colors duration-500 text-[12px] mb-[15px] font-family: 'Outfit', sans-serif text-black dark:text-white">29/11/2023 ➜ Aujourd'hui</p>
        <p class="transition-colors duration-500 text-[17px] mb-[10px] font-family: 'Outfit', sans-serif text-black dark:text-white">C'est un site pour le serveur Minecraft Bedrock Geodia, créé par la communauté Française pour la communauté.</p>
      </div>
      <div class="flex justify-start items-end">
        <div class="flex" id="techno-crea">
          <a href="https://svelte.dev/" target="_blank">
            <div class="relative transition-colors duration-500 bg-[#c4c6d6] dark:bg-[#0f0f18] hover:bg-[#aaacbb] dark:hover:bg-[#161624] p-[10px] rounded-full w-[42px] h-[42px] border-[0.5px] border-solid mr-2 border-[#aaacbb] dark:border-[#3a3a5a] hover:border-[#777985] dark:hover:border-[#4f4f79]">
              <img src={svelted} alt="Svelte Noir" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-5' : 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-5'}>
              <img src={sveltew} alt="Svelte Blanc" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-5' : 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-5'}>
            </div>            
          </a>
          <a href="https://tailwindcss.com/" target="_blank">
            <div class="relative transition-colors duration-500 bg-[#c4c6d6] dark:bg-[#0f0f18] hover:bg-[#aaacbb] dark:hover:bg-[#161624] p-[10px] rounded-full w-[42px] h-[42px] border-[0.5px] border-solid mr-2 border-[#aaacbb] dark:border-[#3a3a5a] hover:border-[#777985] dark:hover:border-[#4f4f79]">
              <img src={tailwindd} alt="TailwindCSS Noir" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-5' : 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-5'}>
              <img src={tailwindw} alt="TailwindCSS Blanc" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-5' : 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-5'}>
            </div>            
          </a>
          <a href="https://developer.mozilla.org/fr/docs/Web/HTML" target="_blank">
            <div class="relative transition-colors duration-500 bg-[#c4c6d6] dark:bg-[#0f0f18] hover:bg-[#aaacbb] dark:hover:bg-[#161624] p-[10px] rounded-full w-[42px] h-[42px] border-[0.5px] border-solid mr-2 border-[#aaacbb] dark:border-[#3a3a5a] hover:border-[#777985] dark:hover:border-[#4f4f79]">
              <img src={htmld} alt="HTML Noir" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-5' : 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-5'}>
              <img src={htmlw} alt="HTML Blanc" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-5' : 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-5'}>
            </div>            
          </a>
          <a href="https://developer.mozilla.org/fr/docs/Web/CSS" target="_blank">
            <div class="relative transition-colors duration-500 bg-[#c4c6d6] dark:bg-[#0f0f18] hover:bg-[#aaacbb] dark:hover:bg-[#161624] p-[10px] rounded-full w-[42px] h-[42px] border-[0.5px] border-solid mr-2 border-[#aaacbb] dark:border-[#3a3a5a] hover:border-[#777985] dark:hover:border-[#4f4f79]">
              <img src={cssd} alt="CSS Noir" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-5' : 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-5'}>
              <img src={cssw} alt="CSS Blanc" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-5' : 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-5'}>
            </div>            
          </a>
          <a href="https://developer.mozilla.org/fr/docs/Web/JavaScript" target="_blank">
            <div class="relative transition-colors duration-500 bg-[#c4c6d6] dark:bg-[#0f0f18] hover:bg-[#aaacbb] dark:hover:bg-[#161624] p-[10px] rounded-full w-[42px] h-[42px] border-[0.5px] border-solid mr-2 border-[#aaacbb] dark:border-[#3a3a5a] hover:border-[#777985] dark:hover:border-[#4f4f79]">
              <img src={jsd} alt="JavaScript Noir" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-5' : 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-5'}>
              <img src={jsw} alt="JavaScript Blanc" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-5' : 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-5'}>
            </div>            
          </a>
          <a href="https://typescriptlang.com/" target="_blank">
            <div class="relative transition-colors duration-500 bg-[#c4c6d6] dark:bg-[#0f0f18] hover:bg-[#aaacbb] dark:hover:bg-[#161624] p-[10px] rounded-full w-[42px] h-[42px] border-[0.5px] border-solid mr-2 border-[#aaacbb] dark:border-[#3a3a5a] hover:border-[#777985] dark:hover:border-[#4f4f79]">
              <img src={tsd} alt="TypeScript Noir" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-5' : 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-5'}>
              <img src={tsw} alt="TypeScript Blanc" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-5' : 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-5'}>
            </div>            
          </a>
        </div>
      </div>
    </div>

  </div>

  <div class="flex flex-row mt-[25px]" id="row">

    <div class="transition-colors duration-500 bg-[#d4d5e2] dark:bg-[#14141E] flex flex-col justify-between w-[500px] p-5 mr-[25px] rounded-[10px] relative" id="crea-container">
      <a href="https://tplm-mgc.fr" target="_blank">
        <div class="bg-red-700 hover:bg-red-600 text-white px-2 py-1 flex rounded absolute top-5 right-5" id="github-redirection">
          Not Open Source
          <img class="ml-2 mt-1 h-4" src={open} alt="Open">
        </div>
      </a>           
      <div>
        <h1 class="transition-colors duration-500 text-[30px] mb-[0px] mt-[-10px] font-family: 'Outfit', sans-serif text-[#4e59d8] dark:text-[#5865f2] font-bold">TPLM Website</h1>
        <p class="transition-colors duration-500 text-[12px] mb-[15px] font-family: 'Outfit', sans-serif text-black dark:text-white">26/11/2023 ➜ Aujourd'hui</p>
        <p class="transition-colors duration-500 text-[17px] mb-[10px] font-family: 'Outfit', sans-serif text-black dark:text-white">C'est un site boutique pour la marque de vêtement TPLM créé par la MGC GVNG.</p>
      </div>
      <div class="flex justify-start items-end">
        <div class="flex" id="techno-crea">
          <a href="https://svelte.dev/" target="_blank">
            <div class="relative transition-colors duration-500 bg-[#c4c6d6] dark:bg-[#0f0f18] hover:bg-[#aaacbb] dark:hover:bg-[#161624] p-[10px] rounded-full w-[42px] h-[42px] border-[0.5px] border-solid mr-2 border-[#aaacbb] dark:border-[#3a3a5a] hover:border-[#777985] dark:hover:border-[#4f4f79]">
              <img src={svelted} alt="Svelte Noir" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-5' : 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-5'}>
              <img src={sveltew} alt="Svelte Blanc" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-5' : 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-5'}>
            </div>            
          </a>
          <a href="https://tailwindcss.com/" target="_blank">
            <div class="relative transition-colors duration-500 bg-[#c4c6d6] dark:bg-[#0f0f18] hover:bg-[#aaacbb] dark:hover:bg-[#161624] p-[10px] rounded-full w-[42px] h-[42px] border-[0.5px] border-solid mr-2 border-[#aaacbb] dark:border-[#3a3a5a] hover:border-[#777985] dark:hover:border-[#4f4f79]">
              <img src={tailwindd} alt="TailwindCSS Noir" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-5' : 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-5'}>
              <img src={tailwindw} alt="TailwindCSS Blanc" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-5' : 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-5'}>
            </div>            
          </a>
          <a href="https://developer.mozilla.org/fr/docs/Web/HTML" target="_blank">
            <div class="relative transition-colors duration-500 bg-[#c4c6d6] dark:bg-[#0f0f18] hover:bg-[#aaacbb] dark:hover:bg-[#161624] p-[10px] rounded-full w-[42px] h-[42px] border-[0.5px] border-solid mr-2 border-[#aaacbb] dark:border-[#3a3a5a] hover:border-[#777985] dark:hover:border-[#4f4f79]">
              <img src={htmld} alt="HTML Noir" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-5' : 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-5'}>
              <img src={htmlw} alt="HTML Blanc" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-5' : 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-5'}>
            </div>            
          </a>
          <a href="https://developer.mozilla.org/fr/docs/Web/CSS" target="_blank">
            <div class="relative transition-colors duration-500 bg-[#c4c6d6] dark:bg-[#0f0f18] hover:bg-[#aaacbb] dark:hover:bg-[#161624] p-[10px] rounded-full w-[42px] h-[42px] border-[0.5px] border-solid mr-2 border-[#aaacbb] dark:border-[#3a3a5a] hover:border-[#777985] dark:hover:border-[#4f4f79]">
              <img src={cssd} alt="CSS Noir" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-5' : 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-5'}>
              <img src={cssw} alt="CSS Blanc" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-5' : 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-5'}>
            </div>            
          </a>
          <a href="https://developer.mozilla.org/fr/docs/Web/JavaScript" target="_blank">
            <div class="relative transition-colors duration-500 bg-[#c4c6d6] dark:bg-[#0f0f18] hover:bg-[#aaacbb] dark:hover:bg-[#161624] p-[10px] rounded-full w-[42px] h-[42px] border-[0.5px] border-solid mr-2 border-[#aaacbb] dark:border-[#3a3a5a] hover:border-[#777985] dark:hover:border-[#4f4f79]">
              <img src={jsd} alt="JavaScript Noir" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-5' : 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-5'}>
              <img src={jsw} alt="JavaScript Blanc" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-5' : 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-5'}>
            </div>            
          </a>
        </div>
      </div>
    </div>

    <div class="transition-colors duration-500 bg-[#d4d5e2] dark:bg-[#14141E] flex flex-col justify-between w-[500px] p-5 rounded-[10px] relative" id="crea-container">
      <a href="https://github.com/DMLSurGithub/DML-Website" target="_blank">
        <div class="bg-green-700 hover:bg-green-600 text-white px-2 py-1 flex rounded absolute top-5 right-5" id="github-redirection">
          Open Source
          <img class="ml-2 mt-1 h-4" src={open} alt="Open">
        </div>
      </a>         
      <div>
        <h1 class="transition-colors duration-500 text-[30px] mb-[0px] mt-[-10px] font-family: 'Outfit', sans-serif text-[#4e59d8] dark:text-[#5865f2] font-bold">DML Website</h1>
        <p class="transition-colors duration-500 text-[12px] mb-[15px] font-family: 'Outfit', sans-serif text-black dark:text-white">18/06/2023 ➜ Aujourd'hui</p>
        <p class="transition-colors duration-500 text-[17px] mb-[10px] font-family: 'Outfit', sans-serif text-black dark:text-white">C'est un site qui présente les créations de DML et qui permet de le contacter.</p>
      </div>
      <div class="flex justify-start items-end">
        <div class="flex" id="techno-crea">
          <a href="https://svelte.dev/" target="_blank">
            <div class="relative transition-colors duration-500 bg-[#c4c6d6] dark:bg-[#0f0f18] hover:bg-[#aaacbb] dark:hover:bg-[#161624] p-[10px] rounded-full w-[42px] h-[42px] border-[0.5px] border-solid mr-2 border-[#aaacbb] dark:border-[#3a3a5a] hover:border-[#777985] dark:hover:border-[#4f4f79]">
              <img src={svelted} alt="Svelte Noir" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-5' : 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-5'}>
              <img src={sveltew} alt="Svelte Blanc" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-5' : 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-5'}>
            </div>            
          </a>
          <a href="https://tailwindcss.com/" target="_blank">
            <div class="relative transition-colors duration-500 bg-[#c4c6d6] dark:bg-[#0f0f18] hover:bg-[#aaacbb] dark:hover:bg-[#161624] p-[10px] rounded-full w-[42px] h-[42px] border-[0.5px] border-solid mr-2 border-[#aaacbb] dark:border-[#3a3a5a] hover:border-[#777985] dark:hover:border-[#4f4f79]">
              <img src={tailwindd} alt="TailwindCSS Noir" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-5' : 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-5'}>
              <img src={tailwindw} alt="TailwindCSS Blanc" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-5' : 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-5'}>
            </div>            
          </a>
          <a href="https://developer.mozilla.org/fr/docs/Web/HTML" target="_blank">
            <div class="relative transition-colors duration-500 bg-[#c4c6d6] dark:bg-[#0f0f18] hover:bg-[#aaacbb] dark:hover:bg-[#161624] p-[10px] rounded-full w-[42px] h-[42px] border-[0.5px] border-solid mr-2 border-[#aaacbb] dark:border-[#3a3a5a] hover:border-[#777985] dark:hover:border-[#4f4f79]">
              <img src={htmld} alt="HTML Noir" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-5' : 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-5'}>
              <img src={htmlw} alt="HTML Blanc" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-5' : 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-5'}>
            </div>            
          </a>
          <a href="https://developer.mozilla.org/fr/docs/Web/CSS" target="_blank">
            <div class="relative transition-colors duration-500 bg-[#c4c6d6] dark:bg-[#0f0f18] hover:bg-[#aaacbb] dark:hover:bg-[#161624] p-[10px] rounded-full w-[42px] h-[42px] border-[0.5px] border-solid mr-2 border-[#aaacbb] dark:border-[#3a3a5a] hover:border-[#777985] dark:hover:border-[#4f4f79]">
              <img src={cssd} alt="CSS Noir" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-5' : 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-5'}>
              <img src={cssw} alt="CSS Blanc" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-5' : 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-5'}>
            </div>            
          </a>
          <a href="https://developer.mozilla.org/fr/docs/Web/JavaScript" target="_blank">
            <div class="relative transition-colors duration-500 bg-[#c4c6d6] dark:bg-[#0f0f18] hover:bg-[#aaacbb] dark:hover:bg-[#161624] p-[10px] rounded-full w-[42px] h-[42px] border-[0.5px] border-solid mr-2 border-[#aaacbb] dark:border-[#3a3a5a] hover:border-[#777985] dark:hover:border-[#4f4f79]">
              <img src={jsd} alt="JavaScript Noir" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-5' : 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-5'}>
              <img src={jsw} alt="JavaScript Blanc" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-5' : 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-5'}>
            </div>            
          </a>
          <a href="https://typescriptlang.com/" target="_blank">
            <div class="relative transition-colors duration-500 bg-[#c4c6d6] dark:bg-[#0f0f18] hover:bg-[#aaacbb] dark:hover:bg-[#161624] p-[10px] rounded-full w-[42px] h-[42px] border-[0.5px] border-solid mr-2 border-[#aaacbb] dark:border-[#3a3a5a] hover:border-[#777985] dark:hover:border-[#4f4f79]">
              <img src={tsd} alt="TypeScript Noir" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-5' : 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-5'}>
              <img src={tsw} alt="TypeScript Blanc" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-5' : 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-5'}>
            </div>            
          </a>
        </div>
      </div>
    </div>

  </div>
  <div class="flex flex-row mt-[25px]" id="row">

    <div class="transition-colors duration-500 bg-[#d4d5e2] dark:bg-[#14141E] flex flex-col justify-between w-[500px] mr-[25px] p-5 rounded-[10px] relative" id="crea-container">
      <a href="https://github.com/DMLSurGithub/Discord-Invitation" target="_blank">
        <div class="bg-green-700 hover:bg-green-600 text-white px-2 py-1 flex rounded absolute top-5 right-5" id="github-redirection">
          Open Source
          <img class="ml-2 mt-1 h-4" src={open} alt="Open">
        </div>
      </a>         
      <div>
        <h1 class="transition-colors duration-500 text-[30px] mb-[0px] mt-[-10px] font-family: 'Outfit', sans-serif text-[#4e59d8] dark:text-[#5865f2] font-bold">Discord Invitation</h1>
        <p class="transition-colors duration-500 text-[12px] mb-[15px] font-family: 'Outfit', sans-serif text-black dark:text-white">13/05/2023</p>
        <p class="transition-colors duration-500 text-[17px] mb-[10px] font-family: 'Outfit', sans-serif text-black dark:text-white">C'est un bout de code qu'on peut rajouter à son site et customiser à sa guise.</p>
      </div>
      <div class="flex justify-start items-end">
        <div class="flex" id="techno-crea">
          <a href="https://developer.mozilla.org/fr/docs/Web/HTML" target="_blank">
            <div class="relative transition-colors duration-500 bg-[#c4c6d6] dark:bg-[#0f0f18] hover:bg-[#aaacbb] dark:hover:bg-[#161624] p-[10px] rounded-full w-[42px] h-[42px] border-[0.5px] border-solid mr-2 border-[#aaacbb] dark:border-[#3a3a5a] hover:border-[#777985] dark:hover:border-[#4f4f79]">
              <img src={htmld} alt="HTML Noir" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-5' : 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-5'}>
              <img src={htmlw} alt="HTML Blanc" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-5' : 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-5'}>
            </div>            
          </a>
          <a href="https://developer.mozilla.org/fr/docs/Web/CSS" target="_blank">
            <div class="relative transition-colors duration-500 bg-[#c4c6d6] dark:bg-[#0f0f18] hover:bg-[#aaacbb] dark:hover:bg-[#161624] p-[10px] rounded-full w-[42px] h-[42px] border-[0.5px] border-solid mr-2 border-[#aaacbb] dark:border-[#3a3a5a] hover:border-[#777985] dark:hover:border-[#4f4f79]">
              <img src={cssd} alt="CSS Noir" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-5' : 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-5'}>
              <img src={cssw} alt="CSS Blanc" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-5' : 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-5'}>
            </div>            
          </a>
        </div>
      </div>
    </div>

    <div class="transition-colors duration-500 bg-[#d4d5e2] dark:bg-[#14141E] flex flex-col justify-between w-[500px] p-5 rounded-[10px] relative" id="crea-container">
      <a href="https://github.com/DMLSurGithub/SecureBits" target="_blank">
        <div class="bg-green-700 hover:bg-green-600 text-white px-2 py-1 flex rounded absolute top-5 right-5" id="github-redirection">
          Open Source
          <img class="ml-2 mt-1 h-4" src={open} alt="Open">
        </div>
      </a>          
      <div>
        <h1 class="transition-colors duration-500 text-[30px] mb-[0px] mt-[-10px] font-family: 'Outfit', sans-serif text-[#4e59d8] dark:text-[#5865f2] font-bold">SecureBits</h1>
        <p class="transition-colors duration-500 text-[12px] mb-[15px] font-family: 'Outfit', sans-serif text-black dark:text-white">01/04/2023 ➜ 02/04/2023</p>
        <p class="transition-colors duration-500 text-[17px] mb-[10px] font-family: 'Outfit', sans-serif text-black dark:text-white">C'est un site qui présente la cybersécurité et qui explique la différence entre l'informatique et la cybersécurité.</p>
      </div>
      <div class="flex justify-start items-end">
        <div class="flex" id="techno-crea">
          <a href="https://developer.mozilla.org/fr/docs/Web/HTML" target="_blank">
            <div class="relative transition-colors duration-500 bg-[#c4c6d6] dark:bg-[#0f0f18] hover:bg-[#aaacbb] dark:hover:bg-[#161624] p-[10px] rounded-full w-[42px] h-[42px] border-[0.5px] border-solid mr-2 border-[#aaacbb] dark:border-[#3a3a5a] hover:border-[#777985] dark:hover:border-[#4f4f79]">
              <img src={htmld} alt="HTML Noir" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-5' : 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-5'}>
              <img src={htmlw} alt="HTML Blanc" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-5' : 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-5'}>
            </div>            
          </a>
          <a href="https://developer.mozilla.org/fr/docs/Web/CSS" target="_blank">
            <div class="relative transition-colors duration-500 bg-[#c4c6d6] dark:bg-[#0f0f18] hover:bg-[#aaacbb] dark:hover:bg-[#161624] p-[10px] rounded-full w-[42px] h-[42px] border-[0.5px] border-solid mr-2 border-[#aaacbb] dark:border-[#3a3a5a] hover:border-[#777985] dark:hover:border-[#4f4f79]">
              <img src={cssd} alt="CSS Noir" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-5' : 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-5'}>
              <img src={cssw} alt="CSS Blanc" class={$darkMode ? 'absolute transition-opacity duration-500 ease-in-out opacity-0 h-5' : 'absolute transition-opacity duration-500 ease-in-out opacity-100 h-5'}>
            </div>            
          </a>
        </div>
      </div>
    </div>

  </div>

</div>