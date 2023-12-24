<script>
  import { darkMode } from '../../../store/dark.js';
  
  import webd from '../../../images/SVG/service/webd.svg';
  import webw from '../../../images/SVG/service/webw.svg';
  
  let darkModeValue = false;

  darkMode.subscribe(value => {
    darkModeValue = value;
  });
</script>

<div class="pt-[120px] pb-[50px] bg-[#f4f3fc] dark:bg-[#0C0C12] flex justify-center items-center" id="biographie">

  <div class="bg-[#d4d5e2] dark:bg-[#14141E] flex items-center w-[1100px] p-5 px-10 pb-8 rounded-[10px]" id="bio-container">

    <div class="mr-5" id="pdp">
      <img class="w-[1000px]" src={$darkMode ? webw : webd} alt={$darkMode ? 'Web clair' : 'Web sombre'}>
    </div>

    <div class="pl-[25px] flex flex-col" id="bio-text">
      <h1 class="text-[50px] mb-[15px] font-family: 'Outfit', sans-serif dark:text-white font-black"><span class="font-bold text-[#ff9900] dark:text-[#FFC000]">Développement</span> <span class="font-bold text-[#4e59d8] dark:text-[#5865f2]">Web</span></h1>
      <p class="text-xl text-black dark:text-[#868894] font-family: 'Outfit', sans-serif dark:text-white">Je suis spécialisé dans le développement Web, offrant des solutions sur mesure pour répondre à vos besoins spécifiques. J’utilise principalement le framework Svelte, reconnu pour sa rapidité et son efficacité, combiné avec TailwindCSS pour un design moderne et réactif. Mon objectif est de créer des sites Web performants et esthétiquement agréables, tout en garantissant une expérience utilisateur optimale.</p>
    </div>

  </div>
</div>