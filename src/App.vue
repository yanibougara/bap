<script setup>
import { RouterLink, RouterView } from 'vue-router'

</script>

<template>

  <header>
    <div class="wrapper">
      <nav>
        <RouterLink to="/">Accueil</RouterLink>
        <RouterLink to="/search">association</RouterLink><svg width="31" height="27" viewBox="0 0 31 27" fill="none" xmlns="http://www.w3.org/2000/svg">
<g filter="url(#filter0_d_27_2)">
<rect width="23" height="19" rx="9.5" transform="matrix(1 0 0 -1 4 19)" fill="#FF5D5D"/>
</g>
<path d="M15.5 6V13M12 9.5H19" stroke="white" stroke-linecap="round"/>
<defs>
<filter id="filter0_d_27_2" x="0" y="0" width="31" height="27" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
<feFlood flood-opacity="0" result="BackgroundImageFix"/>
<feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0" result="hardAlpha"/>
<feOffset dy="4"/>
<feGaussianBlur stdDeviation="2"/>
<feComposite in2="hardAlpha" operator="out"/>
<feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/>
<feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_27_2"/>
<feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_27_2" result="shape"/>
</filter>
</defs>
</svg>

      </nav>
    </div>
  </header>

  <RouterView />

</template>

<style scoped>

header{
  padding: 15px ;
  
}

nav{
  display: flex;
}

nav li{
  text-decoration: none;
  
  font-size: 20px;
  margin-right: 20px;
}

nav li:hover{
  color: #f5a623;
}

nav a{
  text-decoration: none;
  color: rgb(3, 2, 2);
  font-size: 20px;
  margin-right: 20px;
}

</style>