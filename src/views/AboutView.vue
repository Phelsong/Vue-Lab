<template>
  <div class="about">
    <h1>This is an about page</h1>
    <img src="../../bluebox-SS2.jpg" alt="BlueBox" class="inline-image"/>
  </div>
</template>

<style>
.inline-image {
  width: 10rem;
  height: 10rem;
}


@media (max-width: 720px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
