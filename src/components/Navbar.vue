<template>
    <header>
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
    </header>
  </template>
  
  <script setup>
  // No special logic for now
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
    top: 3%;
    left: 25%; 
    width: 90%;
    z-index: 10; 
  }

  nav a {
    font-family: 'NeueHaasDisplay', sans-serif;
    color: #ffffff;
    font-size: 2.5rem; /* Simulate zoom */
    padding: 20px 0;
  }
  
  nav ul {
    display: flex;
    gap: 50px;
    list-style-type: none;
    justify-content: flex-start;
  }
  
  nav a:hover {
    color: #ffe08a; 
  }
  </style>
  