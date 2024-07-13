<template>
  <h1>COMING SOON ( ͡° ͜ʖ ͡°)</h1>
  <div class="social-container">
    <a href="https://github.com/RomanFalzon" target="_blank">
      <img class="github" src="./assets/github.svg" alt="" />
    </a>
    <a href="https://www.linkedin.com/in/roman-f-8b7b61164/" target="_blank">
      <img class="linkedin" src="./assets/linkedin.svg" alt="" />
    </a>
  </div>
</template>

<style lang="scss">
@import url("https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap");
* {
  font-family: "Roboto", sans-serif;
}
body {
  background-color: #f1fffa;
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  position: relative;
}
h1 {
  letter-spacing: 5px;
  font-weight: 300;
  color: #785964;
}
.social-container {
  position: absolute;
  bottom: 15px;
  left: 50%;
  transform: translateX(-50%);
  img {
    width: 32px;
    height: 32px;
    margin: 10px;
  }
  .github {
    filter: brightness(0) saturate(100%) invert(36%) sepia(22%) saturate(459%)
      hue-rotate(287deg) brightness(94%) contrast(87%);
  }
}
</style>
