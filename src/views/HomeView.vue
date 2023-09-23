<!-- <script setup>
import TheWelcome from '../components/TheWelcome.vue'
</script>

<template>
  <main>
    <TheWelcome />
  </main>
</template> -->

<template>
  <body>
    <section class="hero">
      <p class="small">WE ARE</p>
      <p class="effect">J O R A Z E D H A N</p>
      <p class="big">J O R A Z E D H A N</p>
      <div class="box">
        <p>Meet The Team</p>
        <div class="inside-box">
          <div class="upper-box">
            <div class="left-upper-box">
              <img src="https://via.placeholder.com/300x300" alt="" />
              <p>
                JONATHAN ADITHYA BASWARA <br />
                5027221062 <br />
                TEKNOLOGI INFORMASI <br />
                2022
              </p>
            </div>
            <div class="right-upper-box">
              <img src="https://via.placeholder.com/300x300" alt="" />
              <p>
                RIZKI RAMADHANI <br />
                5027221013 <br />
                TEKNOLOGI INFORMASI <br />
                2022
              </p>
            </div>
          </div>
          <div class="below-box">
            <div class="left-upper-box">
              <img src="https://via.placeholder.com/300x300" alt="" />
              <p>
                JONATHAN ADITHYA BASWARA <br />
                5027221062 <br />
                TEKNOLOGI INFORMASI <br />
                2022
              </p>
            </div>
            <div class="right-upper-box">
              <img src="https://via.placeholder.com/300x300" alt="" />
              <p>
                RIZKI RAMADHANI <br />
                5027221013 <br />
                TEKNOLOGI INFORMASI <br />
                2022
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="cards-collide">
      <div class="card">
        <img src="https://via.placeholder.com/300x300" alt="" />
        <p>
          JONATHAN ADITHYA BASWARA <br />
          5027221062 <br />
        </p>
      </div>
      <div class="card">
        <img src="https://via.placeholder.com/300x300" alt="" />
        <p>
          JONATHAN ADITHYA BASWARA <br />
          5027221062 <br />
        </p>
      </div>
      <div class="card">
        <img src="https://via.placeholder.com/300x300" alt="" />
        <p>
          JONATHAN ADITHYA BASWARA <br />
          5027221062 <br />
        </p>
      </div>
      <div class="card">
        <img src="https://via.placeholder.com/300x300" alt="" />
        <p>
          JONATHAN ADITHYA BASWARA <br />
          5027221062 <br />
        </p>
      </div>
    </section>
    <section class="content">
      <div class="title">
        <p class="content-title">Team's Project</p>
        <p>
          We obtained some of the project results during Basic Media Scholling
          activities and also during the lecture period.
        </p>
      </div>
      <div class="content-card">
        <img src="https://via.placeholder.com/300x300" alt="" />
        <p>
          Journalism is one of our projects that takes place during basic media
          school activities. Here we try to be like camera people and reporters.
        </p>
      </div>
      <div class="content-card-rev">
        <img src="https://via.placeholder.com/300x300" alt="" />
        <p>
          News writing techniques are one of our projects during basic media
          school activities. Here we try to write news starting from angel news,
          lead story, body, paragraphs and tail.
        </p>
      </div>
      <div class="content-card">
        <img src="https://via.placeholder.com/300x300" alt="" />
        <p>
          virtual background screens and posters are one of our projects during
          the lecture period. Here we design a virtual background screen
          starting from color selection, theme, layout, rough design to
          completion.
        </p>
      </div>
    </section>
    <footer>
      <p>all rights reserved © 2023 Jorazedhan</p>
    </footer>
  </body>
</template>

<style>
* {
  margin: 0;
  padding: 0;
}

body {
  background-color: #0a4d68;
  width: 100%;
}

.hero {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.hero .effect {
  position: absolute;
  margin-left: 10px;
  margin-top: 155px;
  text-align: center;
  font-family: Bebas Neue;
  font-size: 103px;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
  color: #ecf9ff;
  z-index: 0;
  color: transparent;
  /* the first value is the width 
  and the second value is the color */
  -webkit-text-stroke: 2px #ecf9ff;
}

.small {
  padding: 100px 0 15px 0;
  color: #ffeeb3;
  text-align: center;
  font-family: "Bebas Neue";
  font-size: 36px;
  font-style: normal;
  font-weight: 400;
  line-height: 1.3;
}

.big {
  color: #ffeeb3;
  font-family: "Bebas Neue";
  font-size: 103px;
  font-style: normal;
  font-weight: 400;
  line-height: 1.3;
  text-align: center;
  z-index: 1;
}

.box {
  margin-top: 70px;
  align-items: center;
  border-radius: 19px;
  background: #ecf9ff;
  box-shadow: 7px 7px 35px 7px rgba(255, 255, 255, 0.55);
}

.box > p {
  text-align: center;
  padding: 50px 0 40px 0;
  color: #0a4d68;
  font-family: "Bebas Neue";
  font-size: 32px;
  font-style: normal;
  font-weight: 400;
  line-height: 20px; /* 62.5% */
}

img {
  width: 80px;
  height: 80px;
  border-radius: 50px;
}

.left-upper-box {
  display: flex;
  flex-direction: row;
}

.right-upper-box {
  display: flex;
  flex-direction: row-reverse;
}

.right-upper-box {
  text-align: right;
}

.upper-box {
  display: flex;
  justify-content: center;
  gap: 10px;
  padding: 10px;
  margin: 30px 80px;
}

.inside-box p {
  color: #0a4d68;
  font-family: "Bebas Neue";
  font-size: 15px;
  font-style: normal;
  font-weight: 800;
  line-height: 20px; /* 105.263% */
  padding: 0px 30px;
}

.below-box {
  display: flex;
  justify-content: center;
  gap: 10px;
  padding: 10px;
  margin: 70px 80px;
}

.cards-collide {
  margin: 200px 0px;
  display: flex;
  justify-content: space-evenly;
}

.card {
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.card p {
  color: #ffeeb3;
  font-family: Bebas Neue;
  text-align: center;
  font-size: 16px;
  font-style: normal;
  font-weight: 400;
  line-height: 30px; /* 103.448% */
}

.card img {
  border-radius: 10px;
  width: 250px;
  height: 250px;
  padding: 20px;
  border-radius: 19px;
  background: #ecf9ff;
  box-shadow: 7px 7px 35px 7px rgba(255, 255, 255, 0.55);
}

.content .content-title {
  color: #ffeeb3;
  text-align: center;
  font-family: Times New Roman;
  font-size: 36px;
  font-style: normal;
  font-weight: 700;
  line-height: 46px; /* 127.778% */
  letter-spacing: -0.2px;
}

.content p {
  color: #ecf9ff;
  text-align: center;
  font-family: Times New Roman;
  font-size: 32px;
  font-style: normal;
  font-weight: 400;
  line-height: 30px; /* 93.75% */
  letter-spacing: -0.1px;
  width: 664px;
}

.content .title {
  margin: 300px 0 200px;
  display: flex;
  align-items: center;
  flex-direction: column;
  gap: 40px;
}

.content-card {
  display: flex;
  gap: 50px;
  flex-direction: row;
  align-items: center;
  margin: 150px 300px;
}

.content-card p {
  text-align: left;
}

.content-card img {
  width: 300px;
  height: 300px;
  border-radius: 19px;
  background: #ecf9ff;
  box-shadow: 7px 7px 35px 7px rgba(255, 255, 255, 0.55);
}

.content-card-rev {
  display: flex;
  gap: 50px;
  flex-direction: row-reverse;
  align-items: center;
  margin: 105px 300px;
}

.content-card-rev p {
  text-align: right;
}

.content-card-rev img {
  width: 300px;
  height: 300px;
  border-radius: 19px;
  background: #ecf9ff;
  box-shadow: 7px 7px 35px 7px rgba(255, 255, 255, 0.55);
}

footer {
  display: flex;
  justify-content: center;
  align-items: center;
  opacity: 0.29;
  background: #088395;
  width: 100%;
  height: 213px;
}

footer p {
  color: #00ffca;
  font-family: Times New Roman;
  font-size: 29px;
  font-style: normal;
  font-weight: 400;
  line-height: 30px; /* 103.448% */
  letter-spacing: -0.1px;
  text-align: center;
}
</style>
