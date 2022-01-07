<script>
    import Router from 'svelte-hash-router';
    let idl=['a7ylve6TFo8','qRao8xS_nyM','z-Ng5ZvrDm4','dtHOu-aPev4','AP07mio4POc','AdNJ3fydeao','dQw4w9WgXcQ','-tT0O0qybGg']
	let cats = [
		{ id: 0, name: 'What is solar punk',desc:"This video gives an introduction to what solarpunk is and why is it a future we all can hope for" },
		{ id: 1, name: 'The starter !!' ,desc:"I started thinking about solarpunk thanks to this balajis talking about it in his twitter here is a video to get more of his ideas" },
		{ id: 2, name: 'This looks amazing' ,desc:"This is a video which is very nice to watch just watch it" },
		{ id: 3, name: 'Cyberpunk is scary' ,desc:"Cyberpunk might look like an cool place to live in when we see the renders but is it really good or is it scary ?" },
		{ id: 4, name: 'Dharmicism ? whats that' ,desc:"I found this video intresting and hence sharing this with you all ? 🤨 What do you think" },
		{ id: 5, name: 'Why Svelte ?? Its best ??' ,desc:"This is the video which convinced me to ditch all popular frameworks to something like svelte" },
        { id: 6, name: "You know Easter egg?", desc:"This is a very amazing vide something which i have seen multiple times do take a look"},
        { id: 7, name: "Sridhar vembu's podcast", desc:"It was a very thought provocking session something worth listening atleast once"}
	];
    $: urlkaro=''
    function urlboom(a){
        urlkaro=a;
        
    }
</script>

<Router/>

<h1 class="inspiro">Our inspiration</h1>
    <section id="whole-section">
    <div class="grid-list">
	{#each cats as { id, name,desc }}
    <a href="#/inspri/video{id+1}" class="card card-list">
        <h1>{name}</h1>
        <h5>{desc}</h5>
    </a>
  
    <!-- <li><a target="_blank" href="https://www.youtube.com/watch?v={id}">
        {i + 1}: {name}{desc}
    </a></li> -->
	{/each}

    </div>


    <!-- <div class="container-fluid">
        <div class="video-player" id="video-player">
            <iframe class="video-it" src="https://www.youtube.com/embed/{urlkaro}" title="video on dm" frameborder="0" allowfullscreen></iframe>
        </div>
    </div> on:click={urlboom(idl[id])}>-->
    </section>
<style>
    .inspiro{
        color: cadetblue;
        font-family: "robo";
        text-align: center;
        margin: 5% 0%;
    }
    .card-list{
        text-decoration: none;
        padding-left: 5%;
        padding-right: 5%;
        background: rgb(36, 36, 36) !important;
        border: solid wheat 5px;
    }
    .card-list h1{
        color: wheat;
        font-family: "roboto";
        text-transform: uppercase;
    }    
    .card-list h5{
        color: rgb(241, 168, 33);
        font-family: "codercoder";
        text-transform: uppercase;
        padding-bottom: 3rem;
    }
    .grid-list{
        display: grid;
        gap: 1rem;
        grid-template-columns: repeat(auto-fit,minmax(16rem,1fr)) !important;
        justify-content: center;
        align-content: center;
        margin: 0% 5%;
    }
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