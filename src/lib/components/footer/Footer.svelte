<script lang="ts">
  import pp from '../../images/IMG/pdp/pp.png'
  import ppc from '../../images/IMG/pdp/pdp.png'
  import discord from '../../images/SVG/reseau/discord.svg'
  import github from '../../images/SVG/reseau/github.svg'

  function copyToClipboard(text: string) {
    navigator.clipboard.writeText(text).then(function() {
      alert('Le mot dml130ris a été copié dans votre presse-papier.\nAllez vite le coller sur Discord pour ajouter DML !');
    }, function(err) {
      console.error('Could not copy text: ', err);
    });
  }

  let hover = false;
  function handleMouseOver() {
    hover = true;
  }
  function handleMouseOut() {
    hover = false;
  }
</script>

<div class="transition-colors duration-500 flex justify-between items-center pt-[30px] pb-[10px] bg-[#edebf5] dark:bg-[#0a0a0f]" id="footer">

  <div class="ml-[130px] pb-[120px] pr-[120px] relative" id="pp-container">
    <img 
      class="absolute w-[100px] rounded-[30px] transition-all duration-[350ms] ease-in-out transform {hover ? '-rotate-[25deg]' : ''} {hover ? 'opacity-0' : 'opacity-100'}" 
      src={pp} 
      alt="PP" 
      on:mouseover={handleMouseOver} 
      on:mouseout={handleMouseOut}
      on:focus={handleMouseOver} 
      on:blur={handleMouseOut}
    >
    <img
      class="absolute w-[100px] rounded-[30px] transition-all duration-[350ms] ease-in-out transform {hover ? '-rotate-[25deg]' : ''} {hover ? 'opacity-100' : 'opacity-0'}" 
      src={ppc} 
      alt="PPC" 
      on:mouseover={handleMouseOver} 
      on:mouseout={handleMouseOut}
      on:focus={handleMouseOver} 
      on:blur={handleMouseOut}
    >
</div>

  <div class="" id="center">
    <div class="description-container">
      <p class="transition-colors duration-500 text-center text-l text-black dark:text-[#ffffff] mb-2.5 font-family: 'Outfit', sans-serif">Je suis un jeune Développeur !<br>Je fais principalement du Frontend en utilisant le Framework Svelte.</p>
    </div>
    <div class="bydml-container">
      <p class="transition-colors duration-500 text-center text-l text-black dark:text-[#ffffff] font-family: 'Outfit', sans-serif">Fais avec ❤️ par <a class="transition-colors duration-500 text-black dark:text-[#ffffff] underline hover:text-[#5865f2] font-family: 'Outfit', sans-serif" href="https://github.com/DMLSurGithub/" target="_blank">DML</a></p>
    </div>
  </div>

  <div class="mr-[130px]" id="reseau-container">
    <h6 class="transition-colors duration-500 flex text-l text-black dark:text-[#ffffff] mb-2.5 font-family: 'Outfit', sans-serif">Réseaux Sociaux :</h6>
    <div class="flex">
      <button on:click={() => copyToClipboard('dml130ris')}>
        <img class="transition-colors duration-500 w-[20px] ml-[40px] hover:brightness-[-180%] dark:hover:brightness-[180%]" src={discord} alt="Discord Logo">
      </button>      
    <a href="https://github.com/DMLSurGithub/" target="_blank">
      <img class="transition-colors duration-500 flex w-[20px] ml-[15px] hover:brightness-[-180%] dark:hover:brightness-[180%]" src={github} alt="Github Logo">
    </a>
    </div>
  </div>

</div>