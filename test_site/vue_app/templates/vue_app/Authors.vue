<!-- cd /mnt/c/users/maxwe/OneDrive/Documents/BetterShot-master/frontend -->
<!-- npm run dev -->

<template>
  <div class="Profile Settings">

    <style>
      body {
        background-image: url('https://wallpaper-mania.com/wp-content/uploads/2018/09/High_resolution_wallpaper_background_ID_77700320670.jpg');
        background-attachment: fixed;
      }
      .field-name {
        margin-top: 20px;
        font-size: 20px;
        color: #B5B5BC;
      }
      .field-value {
        margin-bottom: 7px;
        font-size: 20px;
        color: #4A4A4A;
      }
      .inner {
        display: inline-block;
      }
      .tab { 
        margin-bottom: 20px; 
      }
      .box-background {
        background-color: #1f2330 ;
      }
    </style>

    <div class="box">
      <h1 class="title">About Us</h1>
    </div>

    <div class="box">
      <figure class="image is-128x128">
        <img src="https://cdn.discordapp.com/avatars/249997994831773706/9ba2c597ae46aec72c1f810e373597a9.webp?size=128">
      </figure>
      <div class="tab"></div>
      <h1 class = "title"> 
        Maxwell Tang - Software Developer
      </h1>
      <p>
        Maxwell is an RPI junior currently majoring in computer science. He is the captain of the RPI Breakdance Club and juggles.
      </p>
      <p>
        Email: tangm2@rpi.edu
      </p>
    </div>

  </div>

</template>

<script>
export default {
  
}
</script>