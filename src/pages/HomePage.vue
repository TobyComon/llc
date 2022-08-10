<template>
  <div class="row my-5 ms-1">
    <h1>The Squad LLC</h1>
    <div class="col-md-6">
      <p class="">
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ut doloremque
        ea, suscipit dolorem maiores dignissimos dolores quos nulla odit
        debitis. Commodi accusantium quo quaerat eum minus autem aperiam
        obcaecati nihil!
      </p>
    </div>
  </div>

  <div class="row">
    <div class="col-md-6">
      <img
        src="src/assets/img/Screen Shot 2022-08-09 at 15.29.27.png"
        alt="Poof Pets preview"
        class="img-fluid p-2 rounded"
      />
      <a class="ms-3 fs-5" href="https://poofpetsboise.com"
        >PoofPetsBoise.com</a
      >
    </div>
  </div>
</template>

<script>
export default {
  name: "Home",
};
</script>

<style scoped lang="scss">
.home {
  display: grid;
  height: 80vh;
  place-content: center;
  text-align: center;
  user-select: none;
  .home-card {
    width: 50vw;
    > img {
      height: 200px;
      max-width: 200px;
      width: 100%;
      object-fit: contain;
      object-position: center;
    }
  }
}
</style>
