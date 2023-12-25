<div class="transition-colors duration-500 pt-[120px] pb-[50px] bg-[#f4f3fc] dark:bg-[#0C0C12] flex justify-center items-center" id="contact">

  <div class="transition-colors duration-500 bg-[#d4d5e2] dark:bg-[#14141E] items-center w-[1000px] p-5 rounded-[10px]" id="contact-container">

    <div class="flex justify-center mb-10" id="contact-titre-container">
      <h1 class="transition-colors duration-500 font-extrabold text-[50px] text-[#ff9900] dark:text-[#FFC000] font-family: 'Outfit', sans-serif" id="contact-titre">Contactez moi :</h1>
    </div>

    <div class="flex flex-col space-y-2.5" id="entete">

      <div class="flex flex-row self-center mb-5" id="row">

        <div class="mr-5" id="prenom-container">
          <h1 class="transition-colors duration-500 mb-2 text-[20px] text-black dark:text-[#c2c4d4] font-family: 'Outfit', sans-serif dark:text-white">Votre prénom :</h1>
          <input class="transition-colors duration-500 bg-[#edeef7] dark:bg-[#1d1d2c] px-2 py-1 w-[470px] rounded-xl border-[1px] border-[#7b7c83] dark:border-[#3d3d57] text-black dark:text-white" type="text" id="prenom" name="prenom" placeholder="Obligatoire" required />
        </div>

        <div class="" id="nom-container">
          <h1 class="transition-colors duration-500 mb-2 text-[20px] text-black dark:text-[#c2c4d4] font-family: 'Outfit', sans-serif dark:text-white">Votre nom :</h1>
          <input class="transition-colors duration-500 bg-[#edeef7] dark:bg-[#1d1d2c] px-2 py-1 w-[470px] rounded-xl border-[1px] border-[#7b7c83] dark:border-[#3d3d57] text-black dark:text-white" type="text" id="nom" name="nom" placeholder="Obligatoire" required />
        </div>
          
      </div>

      <div class="flex flex-row self-center" id="row">

        <div class="mr-5" id="dsc-container">
          <h1 class="transition-colors duration-500 mb-2 text-[20px] text-black dark:text-[#c2c4d4] font-family: 'Outfit', sans-serif dark:text-white">Votre nom d'utilisateur discord :</h1>
          <input class="transition-colors duration-500 bg-[#edeef7] dark:bg-[#1d1d2c] px-2 py-1 w-[470px] rounded-xl border-[1px] border-[#7b7c83] dark:border-[#3d3d57] text-black dark:text-white" type="text" id="discord" name="discord" placeholder="Falcultatif" />
        </div>

        <div class="" id="email-container">
          <h1 class="transition-colors duration-500 mb-2 text-[20px] text-black dark:text-[#c2c4d4] font-family: 'Outfit', sans-serif dark:text-white">Votre e-mail :</h1>
          <input class="transition-colors duration-500 bg-[#edeef7] dark:bg-[#1d1d2c] px-2 py-1 w-[470px] rounded-xl border-[1px] border-[#7b7c83] dark:border-[#3d3d57] text-black dark:text-white" type="email" id="email" name="email" placeholder="Obligatoire" required />
        </div>

      </div>
      
      <div class="pt-5 pb-5" id="objet-container">
        <h1 class="transition-colors duration-500 mb-2 text-[20px] text-black dark:text-[#c2c4d4] font-family: 'Outfit', sans-serif dark:text-white">Objet du mail :</h1>
        <input class="transition-colors duration-500 bg-[#edeef7] dark:bg-[#1d1d2c] px-2 py-1 w-[960px] rounded-xl border-[1px] border-[#7b7c83] dark:border-[#3d3d57] text-black dark:text-white" type="text" id="objet" name="objet" placeholder="Obligatoire" required />
      </div>
      
    </div>

    <div class="" id="message-container">
      <h1 class="transition-colors duration-500 mb-2 text-[20px] text-black dark:text-[#c2c4d4] font-family: 'Outfit', sans-serif dark:text-white">Message :</h1>
      <textarea class="transition-colors duration-500 bg-[#edeef7] dark:bg-[#1d1d2c] px-2 py-1 w-[960px] h-[300px] rounded-xl border-[1px] border-[#7b7c83] dark:border-[#3d3d57] text-black dark:text-white" id="message" name="message" placeholder="Message (obligatoire)" required></textarea>
    </div>

    <div class="transition-colors duration-500 bg-[#e4e4eb] hover:bg-[#ffffff] dark:bg-[#1d1d2c] dark:hover:bg-[#2c2c42] w-[100px] mx-auto rounded-full pl-5 p-3 mt-8" id="button-envoyer">
      <button class="transition-colors duration-500 text-black dark:text-white flex items" type="submit" id="button-envoyer">Envoyer</button>
    </div>

  </div>

</div>