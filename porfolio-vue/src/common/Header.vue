<template>
    <header>
        <Nav/>
        <router-link to='/' tag='h1'>
            <img alt="Vue logo" src="../assets/logo.png">
        </router-link>
    </header>
</template>

<script>
import Nav from './nav'
export default {
    name:'Header',
    components:{
        Nav
    }
}
</script>

<style lang="scss">
    header{
        width: 100%;
        height: 600px;
        background: #d0d0d0;
        h1{
            max-width: 120px;
            text-align: center;
            margin: 0 auto;
            cursor: pointer;
            img{
                width: 100%;
            }
        }
    }
    
</style>