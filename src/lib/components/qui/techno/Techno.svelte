<script>
  import htmld from '../../../images/SVG/technod/htmld.svg';
  import cssd from '../../../images/SVG/technod/cssd.svg';
  import svelted from '../../../images/SVG/technod/svelted.svg';
  import tailwindd from '../../../images/SVG/technod/tailwindd.svg';
  import jsd from '../../../images/SVG/technod/javascriptd.svg';
  import nextd from '../../../images/SVG/technod/nextd.svg';
  import pythond from '../../../images/SVG/technod/pythond.svg';
  import sqld from '../../../images/SVG/technod/databased.svg';
  import gitd from '../../../images/SVG/technod/gitd.svg';

  import htmlw from '../../../images/SVG/technow/htmlw.svg';
  import cssw from '../../../images/SVG/technow/cssw.svg';
  import sveltew from '../../../images/SVG/technow/sveltew.svg';
  import tailwindw from '../../../images/SVG/technow/tailwindw.svg';
  import jsw from '../../../images/SVG/technow/javascriptw.svg';
  import nextw from '../../../images/SVG/technow/nextw.svg';
  import pythonw from '../../../images/SVG/technow/pythonw.svg';
  import sqlw from '../../../images/SVG/technow/databasew.svg';
  import gitw from '../../../images/SVG/technow/gitw.svg';

  let darkMode = false;
</script>

<div class="flex flex-col items-center justify-center pt-[50px] pb-[50px] bg-[#f4f3fc] dark:bg-[#0C0C12]" id="techno-container">

  <h1 class="font-extrabold pb-4 text-[50px] text-[#ff9900] dark:text-[#FFC000] font-family: 'Outfit', sans-serif" id="technologies">Technologies utilisées :</h1>

  <div class="flex flex-row" id="row">

    <div class="group flex items-center bg-[#d4d5e2] dark:bg-[#14141E] p-5 m-5 rounded-[300px] hover:bg-[#c7c9d8] dark:hover:bg-[#191925] hover:cursor-pointer" id="html-container">
      <a class="flex items-center no-underline" href="https://developer.mozilla.org/fr/docs/Web/HTML" target="_blank">
      <img class="h-[25px] mr-2.5" src={darkMode ? htmld : htmlw} alt={darkMode ? 'HTML Noir' : 'HTML Blanc'}>
      <p class="text-xl text-[#5e5e5e] group-hover:text-black dark:text-[#a2a4b3] dark:group-hover:text-white no-underline font-family: 'Outfit', sans-serif">HTML</p>
      </a>
    </div>

    <div class="group flex items-center bg-[#d4d5e2] dark:bg-[#14141E] p-5 m-5 rounded-[300px] hover:bg-[#c7c9d8] dark:hover:bg-[#191925] hover:cursor-pointer" id="css-container">
      <a class="flex items-center no-underline" href="https://developer.mozilla.org/fr/docs/Web/CSS" target="_blank">
      <img class="h-[25px] mr-2.5" src={darkMode ? cssd : cssw} alt={darkMode ? 'CSS Noir' : 'CSS Blanc'}>
      <p class="text-xl text-[#5e5e5e] group-hover:text-black dark:text-[#a2a4b3] dark:group-hover:text-white no-underline font-family: 'Outfit', sans-serif">CSS</p>
      </a>
    </div>

    <div class="group flex items-center bg-[#d4d5e2] dark:bg-[#14141E] p-5 m-5 rounded-[300px] hover:bg-[#c7c9d8] dark:hover:bg-[#191925] hover:cursor-pointer" id="svelte-container">
      <a class="flex items-center no-underline" href="https://svelte.dev/" target="_blank">
        <img class="h-[25px] mr-2.5" src={darkMode ? svelted : sveltew} alt={darkMode ? 'Svelte Noir' : 'Svelte Blanc'}>
        <p class="text-xl text-[#5e5e5e] group-hover:text-black dark:text-[#a2a4b3] dark:group-hover:text-white no-underline font-family: 'Outfit', sans-serif">Svelte</p>
      </a>
    </div>

    <div class="group flex items-center bg-[#d4d5e2] dark:bg-[#14141E] p-5 m-5 rounded-[300px] hover:bg-[#c7c9d8] dark:hover:bg-[#191925] hover:cursor-pointer" id="tailwind-container">
      <a class="flex items-center no-underline" href="https://tailwindcss.com/" target="_blank">
        <img class="h-[25px] mr-2.5" src={darkMode ? tailwindd : tailwindw} alt={darkMode ? 'TailwindCSS Noir' : 'TailwindCSS Blanc'}>
        <p class="text-xl text-[#5e5e5e] group-hover:text-black dark:text-[#a2a4b3] dark:group-hover:text-white no-underline font-family: 'Outfit', sans-serif">TailwindCSS</p>
      </a>
    </div>

    <div class="group flex items-center bg-[#d4d5e2] dark:bg-[#14141E] p-5 m-5 rounded-[300px] hover:bg-[#c7c9d8] dark:hover:bg-[#191925] hover:cursor-pointer" id="js-container">
      <a class="flex items-center no-underline" href="https://developer.mozilla.org/fr/docs/Web/JavaScript" target="_blank">
        <img class="h-[25px] mr-2.5" src={darkMode ? jsd : jsw} alt={darkMode ? 'JavaScript Noir' : 'JavaScript Blanc'}>
        <p class="text-xl text-[#5e5e5e] group-hover:text-black dark:text-[#a2a4b3] dark:group-hover:text-white no-underline font-family: 'Outfit', sans-serif">JavaScript</p>
      </a>
    </div>

  </div>

  
  <div class="flex flex-row" id="row">

    <div class="group flex items-center bg-[#d4d5e2] dark:bg-[#14141E] p-5 m-5 rounded-[300px] hover:bg-[#c7c9d8] dark:hover:bg-[#191925] hover:cursor-pointer" id="next-container">
      <a class="flex items-center no-underline" href="https://nextjs.org/" target="_blank">
        <img class="h-[25px] mr-2.5" src={darkMode ? nextd : nextw} alt={darkMode ? 'Next.JS Noir' : 'Next.JS Blanc'}>
        <p class="text-xl text-[#5e5e5e] group-hover:text-black dark:text-[#a2a4b3] dark:group-hover:text-white no-underline font-family: 'Outfit', sans-serif">Next.JS</p>
      </a>
    </div>

    <div class="group flex items-center bg-[#d4d5e2] dark:bg-[#14141E] p-5 m-5 rounded-[300px] hover:bg-[#c7c9d8] dark:hover:bg-[#191925] hover:cursor-pointer" id="python-container">
      <a class="flex items-center no-underline" href="https://www.python.org/" target="_blank">
        <img class="h-[25px] mr-2.5" src={darkMode ? pythond : pythonw} alt={darkMode ? 'Python Noir' : 'Python Blanc'}>
        <p class="text-xl text-[#5e5e5e] group-hover:text-black dark:text-[#a2a4b3] dark:group-hover:text-white no-underline font-family: 'Outfit', sans-serif">Python</p>
      </a>
    </div>

    <div class="group flex items-center bg-[#d4d5e2] dark:bg-[#14141E] p-5 m-5 rounded-[300px] hover:bg-[#c7c9d8] dark:hover:bg-[#191925] hover:cursor-pointer" id="sql-container">
      <a class="flex items-center no-underline" href="https://sql.sh/" target="_blank">
        <img class="h-[25px] mr-2.5" src={darkMode ? sqld : sqlw} alt={darkMode ? 'SQL Noir' : 'SQL Blanc'}>
        <p class="text-xl text-[#5e5e5e] group-hover:text-black dark:text-[#a2a4b3] dark:group-hover:text-white no-underline font-family: 'Outfit', sans-serif">SQL</p>
      </a>
    </div>

    <div class="group flex items-center bg-[#d4d5e2] dark:bg-[#14141E] p-5 m-5 rounded-[300px] hover:bg-[#c7c9d8] dark:hover:bg-[#191925] hover:cursor-pointer" id="git-container">
      <a class="flex items-center no-underline" href="https://git-scm.com/" target="_blank">
        <img class="h-[25px] mr-2.5" src={darkMode ? gitd : gitw} alt={darkMode ? 'GIT Noir' : 'GIT Blanc'}>
        <p class="text-xl text-[#5e5e5e] group-hover:text-black dark:text-[#a2a4b3] dark:group-hover:text-white no-underline font-family: 'Outfit', sans-serif">GIT & GitHub</p>
      </a>
    </div>
  </div>

</div>