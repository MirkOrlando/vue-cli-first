<template>
    <div class="jumbotron">
        <div class="container">
            <h3>Pronti per iniziare il viaggio?</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Culpa eius temporibus fugiat impedit rem. Dolorem, fuga eius quasi expedita ratione vero atque nemo distinctio facere et veritatis repudiandae deleniti consequuntur?</p>
        </div>
    </div>
</template>

<script>

export default {
    name: 'My-Hero'
}
</script>

<style scoped lang="scss">
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }

    .jumbotron {
        background-image: url('https://wallpapercave.com/wp/wp5252098.jpg');
        background-size: cover;
        background-position-x: center;
        background-position-y: 23%;
        background-repeat: no-repeat;
        color: rgb(247 230 207);
        padding: 6rem;
        display: flex;
        justify-content: flex-end;
        align-items: flex-end;
    }
    
    .container {
        width: calc(100% / 4);
        padding: 1rem;
        background-color: rgb(46 47 42 / 40%);
        border-radius: 1rem;
    }

    .container > h3,
    .container > p {
        margin: 2rem 0;
    }

</style>
