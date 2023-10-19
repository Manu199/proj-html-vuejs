<script>
export default {
    name: 'Jumbotron'
}
</script>


<template>
  
<div class="jumbotron">

    <img src="../../public/img/02_Landing-Page.jpg" alt="">
    <div class="content-jumbotron">
        <h1>Professional development for coaches and leaders</h1>
        <button>Learn More</button>
    </div>
</div>


</template>


<style scoped lang="scss">

    .jumbotron  {
        height: 100%;
        width: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
        img{
            top: 75px;
            width: 100%;
        }
        .content-jumbotron{
            width: 100%;
            height: 100%;
            justify-content: center;
            align-items: center;
            display: flex;
            flex-direction: column;
        }
    }

</style>