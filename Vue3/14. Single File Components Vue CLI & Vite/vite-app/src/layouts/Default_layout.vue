<script>
import Header from '../components/Header.vue'
import Footer from '../components/Footer.vue'
export default {
    components:{Header,Footer}
}
</script>

<template>
    <div id='default_layout'>
        <Header/>
        <slot/>
        <Footer/>
    </div>
</template>

<style scoped>
#default_layout{
    padding-top:60px;padding-bottom:40px;
}

</style>

