<template>
  <div class="container-fluid">
        <header class="row header">
            <b-navbar type="dark" variant="dark" class="col-10 mx-auto navbar">
                <b-navbar-brand class="brand col-4" href="#">Website Brand</b-navbar-brand>
                <Search class="col-4" />  
                <b-navbar-nav class="col">
                    <b-nav-item href="#">Đăng nhập</b-nav-item>
                    <b-nav-item href="#">Đăng ký</b-nav-item>
                </b-navbar-nav>
            </b-navbar>
        </header>
  </div>
</template>

<script>
import Search from '@/components/Section/Search'
export default {
    data: () => ({

    }),
    components: {
        Search,
    },
}
</script>

<style>

</style>