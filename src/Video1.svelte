<script></script>
<div class="container-fluid">
    <div class="video-player" id="video-player">
        <iframe class="video-it" src="https://www.youtube.com/embed/a7ylve6TFo8" title="video on dm" frameborder="0" allowfullscreen></iframe>
    </div>
</div> 
<style>
    .video-player{
        display: grid;
        justify-content: center;
        align-content: center;
    }
    .video-it{
        width: 960px;
        height: 540px;
        margin-top: 5%;
        margin-bottom: 3%;
    }
    @media only screen and (max-width: 1000px) {
        .video-it{
            width:800px;
            height: 450px;
        }
    }
    @media only screen and (max-width: 800px) {
        .video-it{
            width:400px;
            height: 225px;
        }
    }
    @media only screen and (max-width: 450px) {
        .video-it{
            width:300px;
            height: 168.75px;
        }
    }
</style>