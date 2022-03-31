<template>
    <div>
        <h2>{{title}}</h2>
        <img src="https://vitejs.dev/logo.svg" alt="remote logo">
    </div>
</template>

<script>
export default {
    data(){return{
        title:'vite-vue SFC'
    }}
}
</script>

<style scoped>
div{
   border:2px #DCB0FF dashed;margin:10px;text-align:center;
    color:#845EC2; 
}
div:hover{
    background:#FFD3FF
}
img{
    max-height:80px;max-width:80px;
}
</style>
