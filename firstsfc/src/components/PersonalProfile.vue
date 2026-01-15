<template>
  <div class="personal-profile">
    
    <h1>Vue Example</h1>
    <div class="message-box">
      {{ message }}
    </div>

    <h1>Introduction to Geoff Guevarra</h1>
    
    <div class="about-me">
      <h2>About Me</h2>
      <ul>
        <li>BSIT Student of Asia Pacific College</li>
        <li>Basketball Savant</li>
        <li>Halimaw Magmahal</li>
      </ul>
    </div>

    <div class="education-achievements">
      <h2>Education / Achievements</h2>
      <ol>
        <li>Graduated at Treston International School</li>
        <li>2nd Runner up ISAA Basketball HS Tournament</li>
      </ol>
    </div>

    <div class="experience">
      <h2>Course / IT Experience</h2>
      <p>BSIT and grew up in a compute shop</p>
    </div>

    <div class="goals-dreams">
      <h2>Goals / Dreams</h2>
      <p>To give a better life to those around me and every person I can help</p>
    </div>

    <h1>GRID</h1>

    <div class="container">
      <div>Religion: Roman Catholic</div>
      <div>Studies at: Asia Pacific College</div>
      <div>Dogs: 3</div>  
      <div>uepppppa</div>
      <div>to be updated</div>
      <div>to be updated</div>  
      <div>to be updated</div>
      <div>to be updated</div>  
    </div>

    <div class="gallery">
      <img v-for="(x, index) in manyFoods" :key="index" :src="x" alt="Food item" />
    </div>

  </div>
</template>

