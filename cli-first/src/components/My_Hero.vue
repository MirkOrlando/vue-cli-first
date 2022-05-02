<template>
    <div class="jumbotron">
        <div class="container">
            <div class="jumboText">
            <h3>Pronti per iniziare?</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Culpa eius temporibus fugiat impedit rem. Dolorem, fuga eius quasi expedita ratione vero atque nemo distinctio facere et veritatis repudiandae deleniti consequuntur?</p>
            </div>
        </div>
    </div>
</template>

<script>

export default {
    name: 'My-Hero'
}
</script>

<style scoped lang="scss">

    .jumbotron {
        background-image: url('https://wallpapercave.com/wp/wp5252098.jpg');
        background-size: cover;
        background-position-x: center;
        background-position-y: 23%;
        background-repeat: no-repeat;
        color: rgb(247 230 207);
        padding: 4rem;
    }
    
    .container {
        max-width: 1200px;
        margin: 2rem auto;
        display: flex;
        justify-content: flex-end;
        align-items: flex-end;
    }

    .jumboText {
        width: calc(100% / 4);
        padding: 1rem;
        background-color: rgb(46 47 42 / 40%);
        border-radius: 1rem;
    }

    .jumboText > h3,
    .jumboText > p {
        margin: 2rem 0;
    }

</style>
