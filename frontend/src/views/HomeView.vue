<template>
  <div class="home">
    <div class="container">
      <h3>Все новости</h3>
      <div class="row">
        <div class="col-md-6 col-lg-4 mb-5">
          <CardVue></CardVue>
        </div>
        <div class="col-md-6 col-lg-4 mb-5">
          <Card2vue></Card2vue>
        </div>
        <div class="col-md-6 col-lg-4 mb-5">
          <Card3vue></Card3vue>
        </div>
      </div>
      <div class="row">
        <div class="col-md-6 col-lg-4 mb-5">
          <Card3vue></Card3vue>
        </div>
        <div class="col-md-6 col-lg-4 mb-5">
          <CardVue></CardVue>
        </div>
        <div class="col-md-6 col-lg-4 mb-5">
          <Card2vue></Card2vue>
        </div>
      </div>
    </div>
    <ButtonVue></ButtonVue>
  </div>
</template>

<script>
// @ is an alias to /src
import CardVue from "@/components/News/CardVue";
import Card2vue from "@/components/News/Card2vue";
import Card3vue from "@/components/News/Card3vue";
import ButtonVue from "@/components/News/ButtonVue";

export default {
  name: 'HomeView',
  components: {
    ButtonVue,
    Card3vue,
    Card2vue,
    CardVue
  }
}
</script>

<style scoped>
  h3 {
    padding-bottom: 25px;
  }
</style>