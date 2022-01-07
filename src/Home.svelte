<script>
    import Router from 'svelte-hash-router';
</script>
<div class="img" id="lolimg">
    <img class="imgdude" src="img/bgimg.jpg" alt="solarpunkbgimg"/>
    <div class="img-overlay">
        <h1 class="img-title">CHETAN</h1>
        <p class="img-pa">a better car for solarpunk future</p>
        <a class="attentionbtn" href="#/price" role="button">Get pricing</a>
        <Router/>
    </div>
</div>
<style>
    .img{
        position: relative;
    }
    .imgdude {
        display: block;
        width: 100%;
        height: 900px;
        object-fit: cover;
        object-position: bottom;
    }
    .img-overlay{
        position: absolute;
        top: 0%;
        left: 0%;
        width: 100%;
        height: 100%;
        background: rgba(79, 82, 35, 0.6);
        display: grid;
        justify-content: center;
        align-content: center;
        grid-auto-flow: row;
    }
    .img-title{
        text-align: center;
        font-family: "bsteel";
        color: rgba(255, 255, 147, 0.7);
        letter-spacing: 1rem;
        font-size: 4rem;
    }
    .img-pa{
        font-family: "ele";
        text-align: center;
        font-size: 4rem;
        font-weight: 900;
        word-spacing: 2rem;
        color: rgb(116, 194, 181);
    }
    .attentionbtn{
        margin: 0% 40%;
        padding: 2% 0%;
        text-transform: lowercase;
        font-family: "roboto";
        text-align: center;
        letter-spacing: 0.2rem;
        color: rgb(105, 105, 15);
        text-decoration: none;
        background: rgb(121, 173, 216);
        border: rgb(233, 233, 160) solid 3px;
        transition: box-shadow ease 0.6s;

    }
    .attentionbtn:hover{
        color: rgb(181, 216, 245);
        background: rgb(199, 136, 54);
        border: black 3px solid;
        box-shadow: 6px 6px 0px rgb(0, 46, 46);
    }
    @media only screen and (max-width: 500px) {
        .img-pa{
            font-size: 2rem;
        }
    }

</style>