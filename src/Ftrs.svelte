<script>
      import Router from 'svelte-hash-router';
</script>
<section class="full">
<h1 class="specs">SPECIFICATION</h1>
<br>
<br>
<div id="carouselExampleCaptions" class="carousel slide mx-auto" data-bs-ride="carousel">
    <div class="carousel-indicators">
      <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
      <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
      <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
    </div>
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img src="img/specs.jpg" class="d-block w-100" alt="spec1">

        <div class="carousel-caption my-auto d-none d-md-block">
          <h5>CHETAN IN 1</h5>
               <p>Live Energy Generation</p>
               <p>For city traffic </p>
               <p>The nokia for CARS</p>
               <a role="button" href="#/price" class="btn-sm btn-get">Get it now</a>
        <Router/>
              </div>
      </div>
      <div class="carousel-item">
        <img src="img/spec2.jpg" class="d-block w-100" alt="spec2">

        <div class="carousel-caption my-auto d-none d-md-block">
          <h5>CHETAN NODE</h5>
          <p>Grid Energy Used</p>
          <p>For recursive </p>
          <p>Exclusive for large buyers</p>
          <a role="button" href="#/price" class="btn-sm btn-get">Get it now</a>
        <Router/>
        </div>
      </div>
      <div class="carousel-item">
        <img src="img/spec3.jpg" class="d-block w-100" alt="spec3">

        <div class="carousel-caption my-auto d-none d-md-block">
          <h5>CHETAN SERVER</h5>
          <p>Electric packs used</p>
          <p>For autobans </p>
          <p>The highest level of customisation</p>
          <a role="button" href="#/price" class="btn-sm btn-get">Get it now</a>
        <Router/>
        </div>
      </div>
    </div>
    <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" style="color: white;" data-bs-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Previous</span>
    </button>
    <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Next</span>
    </button>
  </div>
</section>
<section class="small">
  <div class="d-lg-none">
  <div class="accordion" id="accordionExample">
    <div class="accordion-item">
      <h2 class="accordion-header" id="headingOne">
        <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
          CHETAN IN 1
        </button>
      </h2>
      <div id="collapseOne" class="accordion-collapse collapse show" aria-labelledby="headingOne" data-bs-parent="#accordionExample">
        <div class="accordion-body">
            <ul>
                <li>Live Energy Generation</li>
                <li>For city traffic </li>
                <li>The nokia for CARS</li>
            </ul>
        </div>
      </div>
    </div>
    <div class="accordion-item">
      <h2 class="accordion-header" id="headingTwo">
        <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
          CHETAN NODE
        </button>
      </h2>
      <div id="collapseTwo" class="accordion-collapse collapse" aria-labelledby="headingTwo" data-bs-parent="#accordionExample">
        <div class="accordion-body">
            <ul>
                <li>Grid Energy Used</li>
                <li>For recursive </li>
                <li>Exclusive for large buyers</li>
            </ul>

        </div>
      </div>
    </div>
    <div class="accordion-item">
      <h2 class="accordion-header" id="headingThree">
        <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
          CHETAN SERVER
        </button>
      </h2>
      <div id="collapseThree" class="accordion-collapse collapse" aria-labelledby="headingThree" data-bs-parent="#accordionExample">
        <div class="accordion-body">
            <ul>
                <li>Electric packs used</li>
                <li>For autobans </li>
                <li>The highest level of customisation</li>
            </ul>

        </div>
      </div>
    </div>
    </div>
  </div>
</section>

<section class="upcoming">
<br>
<h1>Upcoming Products</h1>
<div class="basic-grid">
    <div class="thimg" style="background-image: url(img/img1.jfif);"><h4>SolarPunk 1</h4></div>
    <div class="thimg" style="background-image: url(img/img2.jfif);"><h4>SolarPunk 2</h4></div>
    <div class="thimg" style="background-image: url(img/img3.jfif);"><h4>SolarPunk 3</h4></div>
    <div class="thimg" style="background-image: url(img/img4.jfif);"><h4>SolarPunk 4</h4></div>
    <div class="thimg" style="background-image: url(img/img5.jfif);"><h4>SolarPunk 5</h4></div>
    <div class="thimg" style="background-image: url(img/img6.jfif);"><h4>SolarPunk 6</h4></div>
</div>
</section>
<style>
    .full{
        background: linear-gradient(180deg,rgb(134, 234, 241,0.5),white);
    }
    .specs{
        font-family: 'ele';
        letter-spacing: 0.3rem;
        padding: 2%;
        text-align: center;
    }
    #carouselExampleCaptions{
        width: 800px;
        height: 450px;
        border: rgb(21, 75, 75) 5px solid;
        margin-bottom: 2%;
    }
    .carousel-item{
        position: relative;
        width: 800px;
        height: 440px;
    }
    @media only screen and (max-width: 800px) {
        #carouselExampleCaptions{
            width: 400px;
            height: 225px;
        }
        .carousel-item{
            width:400px;
            height: 220px;
        }
    }
    @media only screen and (max-width: 400px) {
        #carouselExampleCaptions{
            width: 300px;
            height: 168.75px;
        }
        .carousel-item{
            width:300px;
            height: 165px;
        }
    }
    .carousel-caption{
        color: rgb(179, 245, 229);
        bottom: 25%;
    }
    .carousel-caption h5{
        font-family: "Samarkan";
        font-size: 4rem;
    }
    .carousel-caption p{
        font-family: "ele";
        font-weight: 900;
        text-transform: lowercase;
        color: rgb(219, 213, 123);
        word-spacing: 1rem;
        letter-spacing: 0.3rem;
    }
    .carousel-item::before{
    content:"";
    display: block;
    position: absolute;
    top:0;
    left: 0;
    bottom: 0;
    right: 0;
    background: #000000;
    opacity: 0.8;
    }
    .btn-get{
        background: rgb(255, 255, 120);
        border: rgb(182, 250, 255) solid 2px;
        font-family: "roboto";
        color: rgb(0, 53, 40);
        text-decoration: none;
    }
    .btn-get:hover{
        background: greenyellow;
    }
    .accordion{
        padding:5%;
    }
    .accordion-button{
        background:linear-gradient(to right , rgb(99, 219, 235) ,rgb(228, 228, 150));
        color: rgb(78, 117, 0);
        text-transform: lowercase;
        font-family: "roboto";
    }
    .accordion-item{
        color: rgb(116, 8, 0);
        background: rgba(64, 224, 208,0.4);
        font-family: "Merriweather";
        text-transform: capitalize;
    }
    .small{
        background: linear-gradient(to bottom,white,white);
    }
    .basic-grid{
        position:relative;
        display:grid;
        gap:2rem;
        margin-left: 5%;
        margin-right:5%;
        grid-template-columns: repeat(auto-fill, minmax(320px, 1fr));
        grid-auto-rows: 240px;
        padding-bottom: 5%;

    }
    
    .upcoming h1{
        color: rgb(0, 64, 72);
        font-family: "robo";
        text-align: center;
        margin-bottom: 5%;
    }
    .upcoming{
        background: linear-gradient(to bottom,white,rgb(156, 201, 156));
    }
    .thimg{
        background-size:cover;
        border: black 5px solid;
        transition: transform 0.8s ease;
    }
    .thimg:hover{
        transform: scale(1.1);
    }
    .basic-grid h4{
        height: 100%;
        background: rgba(0, 0, 0,0.5);
        display: grid;
        justify-content: center;
        align-content: center;
        color: cadetblue;
        font-family: "bsteel";
        letter-spacing: 0.3rem;
    }
</style>