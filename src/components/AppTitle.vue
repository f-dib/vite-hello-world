<script>
export default {
    name: 'AppTitle',
}
</script>


<template>
    <h1>Quante repositories di Hello World farai?</h1>
    <div>
        <img class="my_width" src="../assets/28fncn.jpg" alt="">
    </div>
</template>


<style>
    h1 {
        text-align: center;
        color: red;
        font-size: 30px;
    }

    .my_width {
        width: 50vw;
    }


    /********** RESPONSIVE *************/
    @media screen and (max-width: 767px){
        h1 {
            font-size: 20px;
        }

        .my_width {
            width: 70vw;
        }
    }
</style>