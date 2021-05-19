<template>
  <div class="list-movies">
      <h2 class="text-uppercase title">{{data.title}}</h2>
      <hr>
        <div class="container-list">
            <b-card-group deck class="row mx-auto">
                <b-card v-for="movie in data.movies" :key="movie" 
                class="movie"
                :title="movie.name" 
                :img-src="movie.img" 
                img-alt="Image" 
                img-top
                >
                    <b-card-text>{{movie.descr}}</b-card-text>
                    <template #footer>
                        <small class="text-muted">Last updated {{movie.updated}}</small>
                    </template>
                </b-card>
            </b-card-group>
        </div>
  </div>
</template>

<script>
export default {
    props: {
        data: {
            
        }
    },
    data: () => ({
        movies: [1,2,3,4]
    })
}
</script>

<style>

</style>