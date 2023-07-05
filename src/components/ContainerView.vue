<template>
    <div>
        컨테이너에요.
        <Post />
        <Post />
        <Post />
    </div>
</template>

<script>
import Post from './PostView.vue';

export default {
    name : 'ContainerView',
    components : {
        Post,
    }

}
</script>

<style>

</style>