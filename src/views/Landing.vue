<template>
  <section class="section1 p-5">
    <div class="container">
      <div class="row">
        <div class="col-12 pb-5">
          <h1 class="text-center text-white">Card Profile</h1>
        </div>
      </div>
      <div class="row">
        <div class="col-4">
          <a href="#">
            <div class="card">
              <h2 class="text-center text-white">Card1</h2>
            </div>
          </a>
        </div>
        <div class="col-4">
          <a href="#">
            <div class="card">
              <h2 class="text-center text-white">Card2</h2>
            </div>
          </a>
        </div>
        <div class="col-4">
          <a href="#">
            <div class="card">
              <h2 class="text-center text-white">Card3</h2>
            </div>
          </a>
        </div>
        <div class="col-4">
          <a href="#">
            <div class="card">
              <h2 class="text-center text-white">Card4</h2>
            </div>
          </a>
        </div>
        <div class="col-4">
          <a href="#">
            <div class="card">
              <h2 class="text-center text-white">Card5</h2>
            </div>
          </a>
        </div>
        <div class="col-4">
          <a href="#">
            <div class="card">
              <h2 class="text-center text-white">Card6</h2>
            </div>
          </a>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  data() {},
  methods: {
    const DataArray = [
      {
        id: 1,
        name: "Deepak",
      },
      {
        id: 2,
        name: "Neeraj",
      },
      {
        id: 3,
        name: "Shartak",
      },
    ]
  },
};
</script>

<style>
a,
a:hover {
  text-decoration: none;
}
.card {
  border: 1px solid #fff;
  padding: 20px;
  letter-spacing: 1px;
  margin-bottom: 20px;
}
.card:hover {
  background: rgb(4, 97, 11);
  border-color: rgb(4, 97, 11);
}
</style>
