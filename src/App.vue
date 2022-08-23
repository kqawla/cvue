<script setup>
import { RouterLink, RouterView } from 'vue-router'
import viewPersonal from './views/viewPersonal.vue'
</script>

<template>
<div class="container">  
    <nav class="navbar">    
        <ul>  
          <li>  
            <RouterLink to="/personal">Personal</RouterLink>  
          </li>  
          <li>  
            <RouterLink to="/skill">Skill</RouterLink>  
          </li>
        </ul>
    </nav>
    <center>
      <div class="card">
      <div class="card-box">
        <img src="@/assets/Qawla Khoirunisa.png" alt="">
        <h1>QAWLA KHOIRUNISA</h1>
        <h4>FRONT END DEVELOPER</h4>
        <p>Her name is Qawla Khoirunisa. She is 17 years old. She is currently attending Taruna Bhakti Vocational High School, majoring in Software Engineering. She learned many things in her school, but she mostly likes to create landing pages using HTML, CSS, JS, and Bootstrap. She also likes Laravel.</p>
      </div>
      <div class="card-box-2">
        <RouterView />
      </div>
    </div>
    </center>
    
</div>
</template>

<style>
.navbar {
    height: 60px;
    display: flex;  
    align-items: center;     
    text-decoration: none;
    box-shadow: rgba(60, 64, 67, 0.3) 0px 1px 2px 0px, rgba(60, 64, 67, 0.15) 0px 1px 3px 1px;
    margin-bottom: 100px;
    background-color: #EFEFEF;
}  
  
.navbar ul {  
    display: flex;
    list-style: none;  
}  

.navbar ul li a{
  color: black;
  font-weight: bold;
  margin: 10px;
}

.navbar ul li a:hover{
  background-color: black;
  padding: 5px 15px;
  border-radius: 30px;
  color: white;
  font-weight: bold;
  margin: 10px;
}

.container{
  position: relative;
  left: -5rem;
  width: 85rem;
  height: 42rem;
}

h1{
  font-weight: bolder;
  color: black;
}

.card{
  width: 60rem;
  display: flex;
  box-shadow: rgba(60, 64, 67, 0.3) 0px 1px 2px 0px, rgba(60, 64, 67, 0.15) 0px 1px 3px 1px;
}

.card img{
  width: 200px;
  height: 200px;
  border-radius: 100px;
}

.card-box{
  padding: 30px;
  width: 30rem;
  justify-content: center;
}

.card-box h1{
  font-weight: bold;
}

.card-box p{
  font-size: 12px;
  margin-top: 10px;
}

.card-box-2{
  padding: 30px;
  width: 30rem;
  background-color: #EFEFEF;
}
</style>