<script>
  import html from '../../../images/SVG/technod/htmld.svg'
  import css from '../../../images/SVG/technod/cssd.svg'
  import svelte from '../../../images/SVG/technod/svelted.svg'
  import js from '../../../images/SVG/technod/javascriptd.svg'
  import open from '../../../images/SVG/crea/open.svg'
</script>

<div class="flex flex-col items-center justify-center pt-[50px] pb-[50px] bg-[#f4f3fc] dark:bg-[#0C0C12]" id="portfolio">

  <div class="flex flex-row" id="row">

    <div class="bg-[#d4d5e2] dark:bg-[#14141E] flex flex-col justify-between w-[500px] p-5 mr-[25px] rounded-[10px] relative" id="crea-container">
      <a href="https://tplm-mgc.fr" target="_blank">
        <div class="bg-red-700 hover:bg-red-600 text-white px-2 py-1 flex rounded absolute top-5 right-5" id="github-redirection">
          Not Open Source
          <img class="ml-2 mt-1 h-4" src={open} alt="Open">
        </div>
      </a>           
      <div>
        <h1 class="text-[30px] mb-[0px] mt-[-10px] font-family: 'Outfit', sans-serif text-[#4e59d8] dark:text-[#5865f2] font-bold">TPLM Website</h1>
        <p class="text-[12px] mb-[15px] font-family: 'Outfit', sans-serif dark:text-white">26/11/2023 -> Aujourd'hui</p>
        <p class="text-[17px] mb-[10px] font-family: 'Outfit', sans-serif dark:text-white">C'est un site qui présente la cybersécurité et qui explique la différence entre l'informatique et la cybersécurité</p>
      </div>
      <div class="flex justify-start items-end">
        <div class="flex" id="techno-crea">
          <a href="https://svelte.dev/" target="_blank">
            <div class="bg-[#c4c6d6] dark:bg-[#0f0f18] hover:bg-[#aaacbb] dark:hover:bg-[#161624] p-[10px] rounded-full border-[0.5px] border-solid mr-2 border-[#aaacbb] dark:border-[#3a3a5a] hover:border-[#777985] dark:hover:border-[#4f4f79]">
              <img class="h-5" src={svelte} alt="Svelte">
            </div>
          </a>
          <a href="https://developer.mozilla.org/fr/docs/Web/HTML" target="_blank">
            <div class="bg-[#c4c6d6] dark:bg-[#0f0f18] hover:bg-[#aaacbb] dark:hover:bg-[#161624] p-[10px] rounded-full border-[0.5px] border-solid mr-2 border-[#aaacbb] dark:border-[#3a3a5a] hover:border-[#777985] dark:hover:border-[#4f4f79]">
              <img class="h-5" src={html} alt="HTML">
            </div>
          </a>
          <a href="https://developer.mozilla.org/fr/docs/Web/CSS" target="_blank">
            <div class="bg-[#c4c6d6] dark:bg-[#0f0f18] hover:bg-[#aaacbb] dark:hover:bg-[#161624] p-[10px] rounded-full border-[0.5px] border-solid mr-2 border-[#aaacbb] dark:border-[#3a3a5a] hover:border-[#777985] dark:hover:border-[#4f4f79]">
              <img class="h-5" src={css} alt="CSS">
            </div>
          </a>
          <a href="https://developer.mozilla.org/fr/docs/Web/JavaScript" target="_blank">
            <div class="bg-[#c4c6d6] dark:bg-[#0f0f18] hover:bg-[#aaacbb] dark:hover:bg-[#161624] p-[10px] rounded-full border-[0.5px] border-solid border-[#aaacbb] dark:border-[#3a3a5a] hover:border-[#777985] dark:hover:border-[#4f4f79]">
              <img class="h-5" src={js} alt="JavaScript">
            </div>
          </a>
        </div>
      </div>
    </div>

    <div class="bg-[#d4d5e2] dark:bg-[#14141E] flex flex-col justify-between w-[500px] p-5 rounded-[10px] relative" id="crea-container">
      <a href="https://github.com/DMLSurGithub/DML-Website" target="_blank">
        <div class="bg-green-700 hover:bg-green-600 text-white px-2 py-1 flex rounded absolute top-5 right-5" id="github-redirection">
          Open Source
          <img class="ml-2 mt-1 h-4" src={open} alt="Open">
        </div>
      </a>         
      <div>
        <h1 class="text-[30px] mb-[0px] mt-[-10px] font-family: 'Outfit', sans-serif text-[#4e59d8] dark:text-[#5865f2] font-bold">DML Website</h1>
        <p class="text-[12px] mb-[15px] font-family: 'Outfit', sans-serif dark:text-white">18/06/2023 -> Aujourd'hui</p>
        <p class="text-[17px] mb-[10px] font-family: 'Outfit', sans-serif dark:text-white">C'est un site qui présente la cybersécurité et qui explique la différence entre l'informatique et la cybersécurité</p>
      </div>
      <div class="flex justify-start items-end">
        <div class="flex" id="techno-crea">
          <a href="https://svelte.dev/" target="_blank">
            <div class="bg-[#c4c6d6] dark:bg-[#0f0f18] hover:bg-[#aaacbb] dark:hover:bg-[#161624] p-[10px] rounded-full border-[0.5px] border-solid mr-2 border-[#aaacbb] dark:border-[#3a3a5a] hover:border-[#777985] dark:hover:border-[#4f4f79]">
              <img class="h-5" src={svelte} alt="Svelte">
            </div>
          </a>
          <a href="https://developer.mozilla.org/fr/docs/Web/HTML" target="_blank">
            <div class="bg-[#c4c6d6] dark:bg-[#0f0f18] hover:bg-[#aaacbb] dark:hover:bg-[#161624] p-[10px] rounded-full border-[0.5px] border-solid mr-2 border-[#aaacbb] dark:border-[#3a3a5a] hover:border-[#777985] dark:hover:border-[#4f4f79]">
              <img class="h-5" src={html} alt="HTML">
            </div>
          </a>
          <a href="https://developer.mozilla.org/fr/docs/Web/CSS" target="_blank">
            <div class="bg-[#c4c6d6] dark:bg-[#0f0f18] hover:bg-[#aaacbb] dark:hover:bg-[#161624] p-[10px] rounded-full border-[0.5px] border-solid mr-2 border-[#aaacbb] dark:border-[#3a3a5a] hover:border-[#777985] dark:hover:border-[#4f4f79]">
              <img class="h-5" src={css} alt="CSS">
            </div>
          </a>
          <a href="https://developer.mozilla.org/fr/docs/Web/JavaScript" target="_blank">
            <div class="bg-[#c4c6d6] dark:bg-[#0f0f18] hover:bg-[#aaacbb] dark:hover:bg-[#161624] p-[10px] rounded-full border-[0.5px] border-solid border-[#aaacbb] dark:border-[#3a3a5a] hover:border-[#777985] dark:hover:border-[#4f4f79]">
              <img class="h-5" src={js} alt="JavaScript">
            </div>
          </a>
        </div>
      </div>
    </div>

  </div>
  <div class="flex flex-row mt-[25px]" id="row">

    <div class="bg-[#d4d5e2] dark:bg-[#14141E] flex flex-col justify-between w-[500px] mr-[25px] p-5 rounded-[10px] relative" id="crea-container">
      <a href="https://github.com/DMLSurGithub/Discord-Invitation" target="_blank">
        <div class="bg-green-700 hover:bg-green-600 text-white px-2 py-1 flex rounded absolute top-5 right-5" id="github-redirection">
          Open Source
          <img class="ml-2 mt-1 h-4" src={open} alt="Open">
        </div>
      </a>         
      <div>
        <h1 class="text-[30px] mb-[0px] mt-[-10px] font-family: 'Outfit', sans-serif text-[#4e59d8] dark:text-[#5865f2] font-bold">Discord Invitation</h1>
        <p class="text-[12px] mb-[15px] font-family: 'Outfit', sans-serif dark:text-white">13/05/2023</p>
        <p class="text-[17px] mb-[10px] font-family: 'Outfit', sans-serif dark:text-white">C'est un site qui présente la cybersécurité et qui explique la différence entre l'informatique et la cybersécurité</p>
      </div>
      <div class="flex justify-start items-end">
        <div class="flex" id="techno-crea">
          <a href="https://developer.mozilla.org/fr/docs/Web/HTML" target="_blank">
            <div class="bg-[#c4c6d6] dark:bg-[#0f0f18] hover:bg-[#aaacbb] dark:hover:bg-[#161624] p-[10px] rounded-full border-[0.5px] border-solid mr-2 border-[#aaacbb] dark:border-[#3a3a5a] hover:border-[#777985] dark:hover:border-[#4f4f79]">
              <img class="h-5" src={html} alt="HTML">
            </div>
          </a>
          <a href="https://developer.mozilla.org/fr/docs/Web/CSS" target="_blank">
            <div class="bg-[#c4c6d6] dark:bg-[#0f0f18] hover:bg-[#aaacbb] dark:hover:bg-[#161624] p-[10px] rounded-full border-[0.5px] border-solid border-[#aaacbb] dark:border-[#3a3a5a] hover:border-[#777985] dark:hover:border-[#4f4f79]">
              <img class="h-5" src={css} alt="CSS">
            </div>
          </a>
        </div>
      </div>
    </div>

    <div class="bg-[#d4d5e2] dark:bg-[#14141E] flex flex-col justify-between w-[500px] p-5 rounded-[10px] relative" id="crea-container">
      <a href="https://github.com/DMLSurGithub/SecureBits" target="_blank">
        <div class="bg-green-700 hover:bg-green-600 text-white px-2 py-1 flex rounded absolute top-5 right-5" id="github-redirection">
          Open Source
          <img class="ml-2 mt-1 h-4" src={open} alt="Open">
        </div>
      </a>          
      <div>
        <h1 class="text-[30px] mb-[0px] mt-[-10px] font-family: 'Outfit', sans-serif text-[#4e59d8] dark:text-[#5865f2] font-bold">SecureBits</h1>
        <p class="text-[12px] mb-[15px] font-family: 'Outfit', sans-serif dark:text-white">01/04/2023 -> 02/04/2023</p>
        <p class="text-[17px] mb-[10px] font-family: 'Outfit', sans-serif dark:text-white">C'est un site qui présente la cybersécurité et qui explique la différence entre l'informatique et la cybersécurité</p>
      </div>
      <div class="flex justify-start items-end">
        <div class="flex" id="techno-crea">
          <a href="https://developer.mozilla.org/fr/docs/Web/HTML" target="_blank">
            <div class="bg-[#c4c6d6] dark:bg-[#0f0f18] hover:bg-[#aaacbb] dark:hover:bg-[#161624] p-[10px] rounded-full border-[0.5px] border-solid mr-2 border-[#aaacbb] dark:border-[#3a3a5a] hover:border-[#777985] dark:hover:border-[#4f4f79]">
              <img class="h-5" src={html} alt="HTML">
            </div>
          </a>
          <a href="https://developer.mozilla.org/fr/docs/Web/CSS" target="_blank">
            <div class="bg-[#c4c6d6] dark:bg-[#0f0f18] hover:bg-[#aaacbb] dark:hover:bg-[#161624] p-[10px] rounded-full border-[0.5px] border-solid border-[#aaacbb] dark:border-[#3a3a5a] hover:border-[#777985] dark:hover:border-[#4f4f79]">
              <img class="h-5" src={css} alt="CSS">
            </div>
          </a>
        </div>
      </div>
    </div>

  </div>

</div>