<template>
  <div class="main-section">
    <section class="random-info-block">
      <div class="wrapper">
        <h3 id="info-header-text">Best Uno Projects</h3>
      </div>
      <div class="cards-container">
        <div class="card">
          <a :href=showStopper>
            <img
              src="../assets/images/WAYDT.jpg"
              alt=""
            />
            <p>Show Stopper</p>
          </a>
        </div>
        <div class="card">
          <a :href=unoverse>
            <img src="../assets/images/Unoverse.jpeg" alt="" />
            <p>Unoverse</p>
          </a>
        </div>
        <div class="card">
          <a :href=unoverse_two>
            <img
              src="../assets/images/Unoverse2.png"
              alt=""
            />
            <p>Unoverse 2</p>
          </a>
        </div>
        <div class="card">
          <a :href=limbus_3>
            <img src="../assets/images/Limbus_3.jpg" al="" />
            <p>Limbus 3</p>
          </a>
        </div>
      </div>
    </section>
    <section id="quote-block">
      <div class="wrapper">
        <div>
          <p>
            "Lorem ipsum dolor, sit amet consectetur adipisicing elit. Natus quasi
            repellat inventore. Quis expedita necessitatibus porro eaque aut magni
            vel praesentium sequi enim aspernatur molestiae, tempore possimus quidem
            et! Rerum!"
          </p>
        </div>
        <div id="quoter">
          <p>-UnoTheActivist</p>
        </div>
      </div>
    </section>
    <div class="wrapper">
      <section id="sign-up-block">
        <div id="sign-up-banner">
          <div class="left">
            <h5>Yah diiig!</h5>
            <p>Sign Up for more UnoTheActivist content</p>
          </div>
          <div class="right">
            <button>Sign Up</button>
          </div>
        </div>
      </section>
    </div>
  </div>
</template>

<script setup>
import { ref } from "vue";
const showStopper = ref("https://music.youtube.com/playlist?list=OLAK5uy_lePiipMg8WRQQVz5qdTd3rOywRyU8kQ4s&feature=share")
const unoverse = ref("https://music.youtube.com/playlist?list=OLAK5uy_kYuDdvgbN1pLOEGB5QDDKmMfkYX4HGLbE&feature=share")
const unoverse_two = ref("https://music.youtube.com/playlist?list=OLAK5uy_kcx-TN73KY2nOmRKJ7HK9BraaQlbD-58s&feature=share")
const limbus_3 = ref("https://music.youtube.com/playlist?list=OLAK5uy_kAhPGIIjKniGq2jMNgKOoXlPgrydOvc-w&feature=share")
</script>

<style scoped>
.main-section {
  flex: 1;
}

#info-header-text {
  font-size: 36px;
  font-weight: 800;
  color: #1f2937;
  text-align: center;
  /* padding: 0.5rem; */
  margin-bottom: 1.5rem;
}

.random-info-block {
  padding: 3rem 0 4.8rem 0; 
}

img {
  height: 150px;
  width: 150px;
  border: solid 2px #3882f6;
  border-radius: 0.4rem;
  text-align: center;
}

.card , .card > p{
  text-align: center;
  font-size: 16px;
  font-weight: 600;
}

.cards-container {
  display: flex;
  justify-content: center;
  gap: 5rem;
  padding: 1rem 0;
}

#quote-block {
  display: flex;
  flex-direction: column;
  gap: 2rem;
  background-color: #e5e7eb;
  padding: 6rem;
  color: #1f2937;
  font-size: 36px;
  font-weight: lighter;
  font-style: italic;
}

#sign-up-block {
  /* background-color: darkorchid; */
  padding: 5rem 0;
}

#sign-up-banner {
  margin: auto;
  background-color: #3882f6;
  padding: 1.5rem 3rem;
  border-radius: 0.3rem;
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.left > h5 {
  color: #f9faf8;
  font-size: 20px;
  font-weight: 600;
}
.left > p {
  color: #e5e7eb;
  font-size: 10px;
}

a{
    color: #1f2937;
}

#quoter{
  display: flex;
  justify-content: flex-end;
  font-size: 30px;
  font-weight: 700;
}

button {
  background-color: #3882f6;
  border: solid 2px #f9faf8;
  color: #f9faf8;
}
</style>
