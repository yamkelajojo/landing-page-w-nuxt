<template>
  <div class="header">
    <div class="wrapper">
      <nav>
        <div class="nav-left"><a :href=unotheactivist>UnotheActivist</a></div>
        <div class="nav-right">
          <ul>
            <li><a href="https://www.youtube.com/@UnoTheActivist"><Icon  name="mdi:youtube" size="3rem" color="#b2071d"></Icon></a></li>
            <li><a href="https://soundcloud.com/the-act"><Icon name="mdi:soundcloud" size="3rem" color="#ff7700"></Icon></a></li>
            <li><a href="https://www.instagram.com/unotheactivist/"><Icon name="mdi:instagram" size="3rem" color="#E1306C"></Icon></a></li>
          </ul>
        </div>
      </nav>
      <div class="hero">
        <div class="hero-left">
          <div id="hero-main-text">This is my favourite rapper</div>
          <div id="hero-secondary-text">
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Ut quis sit officia deserunt eveniet! Magni, voluptatibus!
          </div>
          <div>
            <button>Like</button>
          </div>
        </div>
        <div class="hero-right">
          <img
            id="placeholder-img"
            src="../assets/images/unowallpaper.jpg"
            alt=""
          />
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
import { ref } from "vue";

const unotheactivist = ref("https://en.wikipedia.org/wiki/UnoTheActivist")
</script>

<style scoped>
.header {
  background-color: #1f2937;
}

nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1.2rem 0;
}

.hero-left{
  display: flex;
  justify-content: center;
  flex-direction: column;
  gap: 1em;
}

ul {
  display: flex;
  list-style: none;
  gap: 1.6rem;
}

.nav-left {
  color: #f9faf8;
  font-size: 24px;
  font-weight: 600;
}

.hero {
  display: flex;
  padding: 1.6rem 0 5rem 0;
  gap: 10%
}

#placeholder-img {
  height: auto;
  width: 500px;
}

#hero-main-text {
  font-size: 48px;
  color: #f9faf8;
  font-weight: 800;
}
.hero-right{
  margin: auto;
}

a{
  color: #f9faf8;

}

button {
  background-color: #3882f6;
  color: #f9faf8;
  font-size: 12px;
  font-weight: 600;
  border: none;
  padding: 0.5rem 1.5rem;
}
</style>
