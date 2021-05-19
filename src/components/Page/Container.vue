<template>
    <div>
        <component
        v-for="section in sections"
        :key="section"
        :is="'ListMovies'"
        :data="section"
        >

        </component>
    </div>
</template>

<script>
import ListMovies from '@/components/Page/ListMovies'
export default {
    data: () => ({
        sections: {
            1: {
                title: 'Hot Current Movies',
                movies: [
                    {
                        name: 'Name',
                        descr: '',
                        updated: '',
                        img: 'https://picsum.photos/300/300/?image=41'
                    },
                    {
                        name: 'Name',
                        descr: '',
                        updated: '',
                        img: 'https://picsum.photos/300/300/?image=41'
                    },
                    {
                        name: 'Name',
                        descr: '',
                        updated: '',
                        img: 'https://picsum.photos/300/300/?image=41'
                    }
                ]
            },
            2: {
                title: 'Hot Upcoming Movies',
                movies: [
                    {
                        name: 'Name',
                        descr: '',
                        updated: '',
                        img: 'https://picsum.photos/300/300/?image=41'
                    },
                    {
                        name: 'Name',
                        descr: '',
                        updated: '',
                        img: 'https://picsum.photos/300/300/?image=41'
                    },
                    {
                        name: 'Name',
                        descr: '',
                        updated: '',
                        img: 'https://picsum.photos/300/300/?image=41'
                    }
                ]
            }
        }
    }),
    components: {
        ListMovies
    }
}
</script>

<style>

</style>