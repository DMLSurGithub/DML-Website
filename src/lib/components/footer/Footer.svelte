<script>
  import pp from '../../images/IMG/pdp/pp.png'
  import discord from '../../images/SVG/reseau/discord.svg'
  import github from '../../images/SVG/reseau/github.svg'
</script>

<div class="flex justify-between items-center pt-[50px] pb-[30px] bg-[#f4f3fc] dark:bg-[#0C0C12]" id="footer">

  <div class="ml-[130px]" id="pp-container">
    <img class="w-[120px] rounded-[30px]" src={pp} alt="PP">
  </div>

  <div class="" id="center">
    <div class="description-container">
      <p class="text-center text-xl text-black dark:text-[#ffffff] mb-2.5 font-family: 'Outfit', sans-serif">Je suis un jeune Développeur !<br>Je fais principalement du Frontend en utilisant le Framework Svelte.</p>
    </div>
    <div class="bydml-container">
      <p class="text-center text-lg text-black dark:text-[#ffffff] font-family: 'Outfit', sans-serif">Fais avec ❤️ par <a class="text-dark dark:text-[#ffffff] underline hover:text-[#5865f2] font-family: 'Outfit', sans-serif" href="https://github.com/DMLSurGithub/" target="_blank">DML</a></p>
    </div>
  </div>

  <div class="mr-[130px]" id="reseau-container">
    <h6 class="flex text-xl text-black dark:text-[#ffffff] mb-2.5 font-family: 'Outfit', sans-serif">Réseaux Sociaux :</h6>
    <div class="flex">
    <a href="https://github.com/DMLSurGithub/" target="_blank">
      <img class="w-[30px] ml-[40px] hover:brightness-[-180%] dark:hover:brightness-[180%]" src={discord} alt="Discord Logo">
    </a>
    <a href="https://github.com/DMLSurGithub/" target="_blank">
      <img class="flex w-[30px] ml-[15px] hover:brightness-[-180%] dark:hover:brightness-[180%]" src={github} alt="Github Logo">
    </a>
    </div>
  </div>

</div>