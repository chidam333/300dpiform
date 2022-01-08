
{indexs}
<div class="grid-video-list">
    {#each videosIndex as index}
    <a href="{videosUrl[index]}"class="card card-list" style="width: 18rem;">
            <h1>{videosTitle[index]}</h1>
            <h5>{videosDesc[index]}</h5>
    </a>
    {/each}

    <div class="card" style="width: 18rem;">
        <div class="card-body">
        <form on:submit={addVideo}>
            <input class="video-title text" placeholder="Video title" bind:value={vtitle} required/>
            <textarea class="video-desc" placeholder="Give a brief description about the video. It is highly enouraged" bind:value={vdesc} required></textarea>
            <input type="text" class="🔗" spellcheck="false" placeholder="paste the url" bind:value={driveurl} required/>
            <button class="video-btn btn-lg btn-dark" type="submit">Post video</button>
        </form>
        </div>
    </div>
</div>

<style>
    .video-title{
        color: rgb(0, 0, 0);
        font-family: "roboto";
        display: inline-block;
        margin-bottom: 1rem;
        width:8rem;
        text-transform: uppercase;
    }
    .video-desc{
        color: rgb(77, 65, 65);
        font-family: "codercoder";
        display: inline-block;
        margin-bottom: 1rem;
        font-size: 0.8rem;
        min-height: 4rem;
        width:15rem;
        text-transform: uppercase;
        
    }
    .🔗{
        color: steelblue;
        font-family: "codercoder";
        letter-spacing: 0.1rem;
        display: inline-block;
        margin-bottom: 1rem;
        font-size: 0.7rem;
        width:15rem;
        text-transform: uppercase;
    }
    .grid-video-list{
        display: grid;
        gap: 1rem;
        grid-template-columns: repeat(auto-fill, minmax(270px, 1fr));
    }
    .card-list{
        text-decoration: none;
        padding-left: 5%;
        background: rgb(36, 36, 36) !important;
    }
    .card-list h1{
        color: wheat;
    }    
</style>
