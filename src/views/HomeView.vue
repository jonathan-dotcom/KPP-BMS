<!-- <script setup>
import TheWelcome from '../components/TheWelcome.vue'
</script>

<template>
  <main>
    <TheWelcome />
  </main>
</template> -->

<template>
  <div class="container" style="padding-top: 2rem;">
      <div class="atas">
          <p style="font-size: 36px">WE ARE</p>
          <H1 style="font-size: 103px">JORAZEDHAN</H1>
      </div>
      <div class="bawah">
          <h3>MEET THE TEAM</h3>
          <div class="profil">
              <div class="anggota">
                  <img src="https://via.placeholder.com/300x300" alt="">
                  <p>JONATHAN ADITHYA BASWARA <br> 5027221062 <br> TEKNOLOGI INFORMASI <br> 2022</p>
              </div>
              <div class="anggota">
                  <img src="https://via.placeholder.com/300x300" alt="">
                  <p>RIZKI RAMADHANI <br> 5027221013 <br> TEKNOLOGI INFORMASI <br> 2022</p>
              </div>
              <div class="anggota">
                  <img src="https://via.placeholder.com/300x300" alt="">
                  <p>JODY HEZEKIAH T.S <br> 5027221050 <br> TEKNOLOGI INFORMASI <br> 2022</p>
              </div>
              <div class="anggota">
                  <img src="https://via.placeholder.com/300x300" alt="">
                  <p>CLARA VALENTINA <br> 5027221016 <br> TEKNOLOGI INFORMASI <br> 2022</p>
              </div>
          </div>
      </div>
  </div>
</template>

<style scoped>
.container .atas{
  text-align: center;
  font-family: 'Bebas Neue';
  line-height: 1.3;

}

.container .bawah {
  display: flex;
  flex-direction: column;
  background-color: aquamarine;
  align-items: center;
  padding: 2rem;
  border-radius: 50px;
}

.container .bawah .profil{
  display: grid;
  align-items: center;
  align-content: center;
  grid-template-columns: repeat(2,1fr);
}
.container .bawah .profil img{
  border-radius: 50%;
  width: 150px;
}

.container .bawah .profil .anggota{
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  padding-bottom: 1rem;
}
</style>
