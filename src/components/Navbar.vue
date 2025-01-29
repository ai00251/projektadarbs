<template>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#groups">Groups</a></li>
        <li><a href="#crew">Crew</a></li>
        <li><a href="#apparel">Apparel & Gift Cards</a></li>
        <li><a href="#events">Events</a></li>
        <li><a href="#auditions">Auditions</a></li>
      </ul>
    </nav>
  </template>
  
  <script setup>

  </script>
  
  <style scoped>

@font-face {
  font-family: 'NeueHaasDisplay';
  src: url('/fonts/NeueHaasDisplayMedium.ttf') format('truetype');
  font-weight: normal;
  font-style: normal;
}

header {
  position: absolute;
  top: 0;
  left: 15%;
  width: 90%;
}

nav {
  font-family: 'NeueHaasDisplay', sans-serif; 
  color: #fff;
  font-size: 3rem; 
  padding: 20px 0;
}

nav ul {
  display: flex;
  gap: 50px;
  list-style-type: none;
  justify-content: flex-start;
}

</style>
  