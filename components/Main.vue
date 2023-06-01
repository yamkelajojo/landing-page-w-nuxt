<template>
  <div class="main-section">
    <section class="random-info-block">
      <h3 id="info-header-text">Best Uno Projects</h3>
      <div class="cards-container">
        <div class="card">
          <img
            src="assets\images\392e8758089593730dcd5ca64f38c62a.999x999x1.jpg"
            alt=""
          />
          <p>Project name</p>
        </div>
        <div class="card">
          <img
            src="assets\images\deaaaddf751e238b3566a430b5b75dbb.1000x1000x1.png"
            alt=""
          />
          <p>Project name</p>
        </div>
        <div class="card">
          <img src="assets\images\Unoverse.jpeg" alt="" />
          <p>Project name</p>
        </div>
        <div class="card">
          <img src="" alt="" />
          <p>Project name</p>
        </div>
      </div>
    </section>
    <section id="quote-block">
      <p>
        "Lorem ipsum dolor, sit amet consectetur adipisicing elit. Natus quasi
        repellat inventore. Quis expedita necessitatibus porro eaque aut magni
        vel praesentium sequi enim aspernatur molestiae, tempore possimus quidem
        et! Rerum!"
      </p>
    </section>
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
</template>

<script setup></script>

<style scoped>
.main-section {
  flex: 1;
}

#info-header-text {
  font-size: 36px;
  font-weight: 800;
  color: #1f2937;
  text-align: center;
  margin-bottom: 1.5rem;
}

.random-info-block {
  padding: 1.5rem 0;
}

img {
  height: 100px;
  width: 100px;
  border: solid 2px #3882f6;
  border-radius: 0.5rem;
  text-align: center;
}

.card {
  text-align: center;
}

.cards-container {
  display: flex;
  justify-content: space-around;
}

#quote-block {
  background-color: #e5e7eb;
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

button {
  background-color: #3882f6;
  border: solid 2px #f9faf8;
  color: #f9faf8;
}
</style>
