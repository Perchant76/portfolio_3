<script>
    import "../app.css";
  </script>
  <div class="bg-[url('/white_noise_background.png')] ">
    <div class="flex justify-between py-5 text-2xl text-white font-oswald">
      <img class="ps-5" src="smallLogo.png" alt="logo" style="width: 60px; height: 50px;" />
      <div class="px-5 ">
        <a class="px-2" href="/">Home</a>
        <a class="px-2" href="/contact">Contact</a>
      </div>
    </div>
    <br>
    <slot class=""/>
  </div>

  <style>
    @import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap');
    @import url('https://fonts.googleapis.com/css2?family=Oswald:wght@200..700&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap');
    @import url('https://fonts.googleapis.com/css2?family=Ubuntu:ital,wght@0,300;0,400;0,500;0,700;1,300;1,400;1,500;1,700&display=swap');
  </style>
  