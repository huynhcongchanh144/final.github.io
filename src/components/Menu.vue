<template>
  <div class="main-menu row">
        <b-navbar class="navbar">
            <b-navbar-nav align="mx-auto">
                <b-nav-item href="#" class="item-menu text-uppercase" v-for="(item,index) in menu" :key="index">{{item}}</b-nav-item>
            </b-navbar-nav>
        </b-navbar>
  </div>
</template>

<script>
export default {
  data: () => ({
    menu: ['Home','Current Movies','Upcoming Movies','Cinema','Contact Us']
  })
}
</script>

<style>

</style>