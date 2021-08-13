<template>
  <section class="section1 p-5">
    <div class="container">
      <div class="row">
        <div class="col-12 pb-5">
          <h1 class="text-center text-white">Dynamic Card Profile</h1>
        </div>
      </div>
      <div class="row" id="example-1">
        <div class="col-4" v-for="item in items" :key="item.id">
          <a href="#">
            <div class="card">
              <h2 class="text-center text-white">{{ item.id }}</h2>
              <h2 class="text-center text-white">{{ item.name }}</h2>
            </div>
          </a>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      items: [
        { id: 1, name: "Deepak" },
        { id: 2, name: "Neeraj" },
        { id: 3, name: "Anish" },
        { id: 4, name: "Shartak" },
      ],
    };
  },
  methods: {},
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
