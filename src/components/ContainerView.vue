<template>
    <div>
        컨테이너에요.

        <Post :게시물="게시물[i]" v-for="(a, i) in 게시물" :key="i" />
        <!-- <Post :게시물="게시물[0]"/>
        <Post :게시물="게시물[1]"/>
        <Post :게시물="게시물[2]"/> -->
    </div>
</template>

<script>
import Post from './PostView.vue';

export default {
    name : 'ContainerView',
    components : {
        Post,
    },
    props : {
        게시물 : Array,
    }

}
</script>

<style>

</style>