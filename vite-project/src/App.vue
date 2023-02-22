<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div>
    <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
  </div>
  <HelloWorld msg="Vite + Vue" />
</template>

<style>
.card {
  width: 350px;
  text-align: center;
  background: #004c54;

  
  margin-top: 16px;
  margin-bottom: 16px;
  margin-left: 16px;
  margin-right: 16px;
  
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 8px;
  padding-right: 8px;
  
  border: 2px solid black;
  border-radius: 16px;
  box-shadow: 4px 4px;
}


.h1 {
  font: 28px Times New Roman;
  color: white;
  text-shadow: 2px 2px #000000;
  line-height: 0px;
  
}
.h2 {
  font: 20px Times New Roman;
  color: white;
  margin-bottom: 16px;
  text-shadow: 2px 2px #000000;
}

.p1 {
  font: 14px Times New Roman;
  color: white;
  margin-top: 16px;
  margin-left: 16px;
  margin-right: 16px;
  text-shadow: 2px 2px #000000;
}

.l1 {
  font: 14px Times New Roman;
  color: white;
  margin-bottom: 24px;
  margin-left: 16px;
  margin-right: 16px;
  text-shadow: 2px 2px #000000;
  
}

ul {
    text-align: center;
    list-style-position: inside;
}


.b1 {
  font: 12px Comic Sans MS;
  border-radius: 16px;
  box-shadow: 2px 2px;
  margin-bottom: 16px;
  
}

.img {
  border: 3px solid black;
  border-radius: 16px;
  box-shadow: 4px 4px;
  
}

.buttons {
  width: 350px;
  text-align: center;
  background: #004c54;
  
  margin-top: 16px;
  margin-bottom: 16px;
  margin-left: 16px;
  margin-right: 16px;
  
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 8px;
  padding-right: 8px;
  
  border: 2px solid black;
  border-radius: 16px;
  box-shadow: 4px 4px;
}


@media (max-width: 800px) and (min-width: 500px) {
  .b1 {
    display: none;
  }
}

@media (max-width: 500px) {
  * {
    transform: scale(0.9);
  }
}

body{
  background: silver;
}


 .button{
   padding: 4px;
       box-shadow: 2px 2px #000000;
    background-color: white;
     border-radius: 16px;
     border: 2px solid black;
    font: 14px Times New Roman;
  color: #004c54;

}

.button:hover{
  background-color: black;
}

.button:focus {
  background-color: blue; 
}


.tog
{
  background-color: cyan;
}

.tog2
{
  background-color: pink;
}
</style>
