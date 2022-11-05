<template>
    <div class="wrapper">
        <div><img class="profilelogo" alt="logo" src="../assets/profile.svg"></div>
        <div><div><b>{{ name }}</b> <small>@{{username}}·{{time}}</small></div>
        <div>{{post}}</div>
        <img class="poster" v-bind:src="postImg"/></div>
    </div>
</template>
    
<script>
export default {
    name: 'PostItem',
    props: ['name','username',"postImg","time",'post']
}
</script>
    
    <!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.wrapper{
    border: 1px solid rgb(239, 243, 244);
    padding: 11px;
    display: flex;
    gap: 1rem;
}
.profilelogo{
    height: 41px;
    border-radius: 50%;
}
.poster{
    border-radius: 11px;
    width: 60%;
    margin-block: 1rem;
}
</style>
    