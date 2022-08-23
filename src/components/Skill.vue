<template>
  <div class="skill">

    <div class="content">
      <div class="maincontent">
        <p>HTML</p>
        <div class="bar">
          <div class="skills html">90%</div>
        </div>
      </div>
      <div class="maincontent">
        <p>CSS</p>
        <div class="bar">
          <div class="skills css">90%</div>
        </div>
      </div>
      <div class="maincontent">
        <p>JavaScript</p>
        <div class="bar">
          <div class="skills js">55%</div>
        </div>
      </div>
      <div class="maincontent">
        <p>Laravel</p>
        <div class="bar">
          <div class="skills lvl">75%</div>
        </div>
      </div>
      <div class="maincontent">
        <p>MySql</p>
        <div class="bar">
          <div class="skills sql">45%</div>
        </div>
      </div>
      <div class="maincontent">
        <p>WordPress</p>
        <div class="bar">
          <div class="skills wp">85%</div>
        </div>
      </div>
      <div class="maincontent">
        <p>Bootstrap</p>
        <div class="bar">
          <div class="skills bts">90%</div>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
  .content {
    text-align: start;
  }

  .maincontent {
    display: flex;
  }

  .maincontent p{
    margin-top: 15px;
    font-weight: 500;
    color: black;
    width: 100px;
  }

  .bar {
    margin-left: 10px;
    margin: 10px;
    padding: 5px;
    width: 25rem;
    background-color: white;
    color: white;

  }

  .skills{
    background-color: black;
    text-align: center;
    color: white;
  }

  .html {
    width: 90%;
  }

  .css {
    width: 90%;
  }

  .js {
    width: 55%;
  }

  .lvl{
    width: 75%;
  }

  .sql{
    width: 45%;
  }

  .wp{
    width: 85%;
  }

  .bts{
    width: 90%;
  }
</style>