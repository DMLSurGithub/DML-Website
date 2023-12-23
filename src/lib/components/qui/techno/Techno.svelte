<script>
  import html from '../../../images/SVG/techno/html.svg'
  import css from '../../../images/SVG/techno/css.svg'
  import svelte from '../../../images/SVG/techno/svelte.svg'
  import tailwind from '../../../images/SVG/techno/tailwind.svg'
  import js from '../../../images/SVG/techno/javascript.svg'
  import next from '../../../images/SVG/techno/next.svg'
  import python from '../../../images/SVG/techno/python.svg'
  import sql from '../../../images/SVG/techno/database.svg'
  import git from '../../../images/SVG/techno/git.svg'
</script>

<div class="flex flex-col items-center justify-center pt-[50px] pb-[50px] bg-white dark:bg-[#0C0C12]" id="techno-container">

  <h1 class="font-extrabold pb-4 text-[50px] text-[#ff9900] dark:text-[#FFC000] font-family: 'Outfit', sans-serif" id="technologies">Technologies utilisées :</h1>

  <div class="flex flex-row" id="row">

    <div class="flex items-center bg-[#d4d5e2] dark:bg-[#14141E] p-5 m-5 rounded-[300px] hover:bg-[#c7c9d8] dark:hover:bg-[#191925] hover:cursor-pointer" id="html-container">
      <a class="flex items-center no-underline" href="https://developer.mozilla.org/fr/docs/Web/HTML" target="_blank">
      <img class="h-[25px] mr-2.5" src={html} alt="HTML">
      <p class="text-xl text-black dark:text-white no-underline font-family: 'Outfit', sans-serif">HTML</p>
    </div>

    <div class="flex items-center bg-[#d4d5e2] dark:bg-[#14141E] p-5 m-5 rounded-[300px] hover:bg-[#c7c9d8] dark:hover:bg-[#191925] hover:cursor-pointer" id="css-container">
      <a class="flex items-center no-underline" href="https://developer.mozilla.org/fr/docs/Web/CSS" target="_blank">
      <img class="h-[25px] mr-2.5" src={css} alt="CSS">
      <p class="text-xl text-black dark:text-white no-underline font-family: 'Outfit', sans-serif">CSS</p>
    </div>

    <div class="flex items-center bg-[#d4d5e2] dark:bg-[#14141E] p-5 m-5 rounded-[300px] hover:bg-[#c7c9d8] dark:hover:bg-[#191925] hover:cursor-pointer" id="svelte-container">
      <a class="flex items-center no-underline" href="https://svelte.dev/" target="_blank">
        <img class="h-[25px] mr-2.5" src={svelte} alt="Svelte">
        <p class="text-xl text-black dark:text-white no-underline font-family: 'Outfit', sans-serif">Svelte</p>
      </a>
    </div>

    <div class="flex items-center bg-[#d4d5e2] dark:bg-[#14141E] p-5 m-5 rounded-[300px] hover:bg-[#c7c9d8] dark:hover:bg-[#191925] hover:cursor-pointer" id="tailwind-container">
      <a class="flex items-center no-underline" href="https://tailwindcss.com/" target="_blank">
        <img class="h-[25px] mr-2.5" src={tailwind} alt="TailwindCSS">
        <p class="text-xl text-black dark:text-white no-underline font-family: 'Outfit', sans-serif">TailwindCSS</p>
      </a>
    </div>

    <div class="flex items-center bg-[#d4d5e2] dark:bg-[#14141E] p-5 m-5 rounded-[300px] hover:bg-[#c7c9d8] dark:hover:bg-[#191925] hover:cursor-pointer" id="js-container">
      <a class="flex items-center no-underline" href="https://developer.mozilla.org/fr/docs/Web/JavaScript" target="_blank">
        <img class="h-[25px] mr-2.5" src={js} alt="JavaScript">
        <p class="text-xl text-black dark:text-white no-underline font-family: 'Outfit', sans-serif">JavaScript</p>
      </a>
    </div>

  </div>

  
  <div class="flex flex-row" id="row">

    <div class="flex items-center bg-[#d4d5e2] dark:bg-[#14141E] p-5 m-5 rounded-[300px] hover:bg-[#c7c9d8] dark:hover:bg-[#191925] hover:cursor-pointer" id="next-container">
      <a class="flex items-center no-underline" href="https://nextjs.org/" target="_blank">
        <img class="h-[25px] mr-2.5" src={next} alt="NextJS">
        <p class="text-xl text-black dark:text-white no-underline font-family: 'Outfit', sans-serif">Next.JS</p>
      </a>
    </div>

    <div class="flex items-center bg-[#d4d5e2] dark:bg-[#14141E] p-5 m-5 rounded-[300px] hover:bg-[#c7c9d8] dark:hover:bg-[#191925] hover:cursor-pointer" id="python-container">
      <a class="flex items-center no-underline" href="https://www.python.org/" target="_blank">
        <img class="h-[25px] mr-2.5" src={python} alt="Python">
        <p class="text-xl text-black dark:text-white no-underline font-family: 'Outfit', sans-serif">Python</p>
      </a>
    </div>

    <div class="flex items-center bg-[#d4d5e2] dark:bg-[#14141E] p-5 m-5 rounded-[300px] hover:bg-[#c7c9d8] dark:hover:bg-[#191925] hover:cursor-pointer" id="sql-container">
      <a class="flex items-center no-underline" href="https://sql.sh/" target="_blank">
        <img class="h-[25px] mr-2.5" src={sql} alt="sql">
        <p class="text-xl text-black dark:text-white no-underline font-family: 'Outfit', sans-serif">SQL</p>
      </a>
    </div>

    <div class="flex items-center bg-[#d4d5e2] dark:bg-[#14141E] p-5 m-5 rounded-[300px] hover:bg-[#c7c9d8] dark:hover:bg-[#191925] hover:cursor-pointer" id="git-container">
      <a class="flex items-center no-underline" href="https://git-scm.com/" target="_blank">
        <img class="h-[25px] mr-2.5" src={git} alt="GIT">
        <p class="text-xl text-black dark:text-white no-underline font-family: 'Outfit', sans-serif">GIT & GitHub</p>
      </a>
    </div>
  </div>

</div>