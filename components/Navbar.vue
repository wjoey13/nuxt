<template>
    <div class="nav">
        <nav class="main-navbar">
            <nuxt-link to ="/Home" class="button">Home</nuxt-link>
            <nuxt-link to ="/About" class="button">About</nuxt-link>
            <nuxt-link to ="/Projects" class="button">Projects</nuxt-link>
            <nuxt-link to ="/Contact" class="button">Contact</nuxt-link>
        </nav>
    </div>
</template>

<script>
export default {
    name:"Navbar",
    data(){
        return{

        }
    }
}
</script>

<style>
.nav{
    display: flex;
    flex-flow: column nowrap;
    align-content: flex-start;
    align-items: center;

}
.button{
    margin: 4px 2px;
    border-radius: 10px;
}
</style>
