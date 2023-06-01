<template>
  <div class="header">
    <nav>
      <div class="nav-left">UnotheActivist</div>
      <div class="nav-right">
        <ul>
          <li><a href=""></a>Youtube</li>
          <li><a href=""></a>Soundcloud</li>
          <li><a href=""></a>Insta</li>
        </ul>
      </div>
    </nav>
    <div class="hero">
      <div class="hero-left">
        <div id="hero-main-text">This is my favourite rapper</div>
        <div id="hero-secondary-text">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Laboriosam
          minima sed reiciendis. Ab excepturi cumque error possimus cum!
        </div>
        <button>Like</button>
      </div>
      <div class="hero-right">
        <img
          id="placeholder-img"
          src="assets\images\cyber_neon_classic_garage.jpg"
          alt=""
        />
      </div>
    </div>
  </div>
</template>

<script setup></script>

<style scoped>
.header {
  background-color: #1f2937;
}

nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0.5rem 0;
}

ul {
  display: flex;
  list-style: none;
  gap: 1.6rem;
}

.nav-left {
  color: #f9faf8;
  font-size: 24px;
  font-weight: 550;
}

.hero {
  display: flex;
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

button {
  background-color: #3882f6;
  color: #f9faf8;
  font-size: 10px;
  font-weight: 600;
  border: none;
}
</style>
