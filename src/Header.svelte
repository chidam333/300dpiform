<script>
	import Router from 'svelte-hash-router'
</script>
<nav class="navbar navbar-expand-lg navbar-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#lolimg">CHETAN</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNavDropdown">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" style="color: #686822;" href="#/">&nbsp;&nbsp;&nbsp;Home&nbsp;&nbsp;&nbsp;</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" style="color: #686822;" href="#/ftrs">&nbsp;&nbsp;&nbsp;Features&nbsp;&nbsp;&nbsp;</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" style="color: #686822;" href="#/price">&nbsp;&nbsp;&nbsp;Pricing&nbsp;&nbsp;&nbsp;</a>
          </li>
          <li class="nav-item dropdown" >
            <a class="nav-link dropdown-toggle" style="color: #686822;" href="#" id="navbarDropdownMenuLink" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                &nbsp;&nbsp;&nbsp;Dropdown link&nbsp;&nbsp;&nbsp;
            </a>
            <ul class="dropdown-menu"  aria-labelledby="navbarDropdownMenuLink">
              <li><a class="dropdown-item" href="#/inspri">Our Inspiration</a></li>
              <li><a class="dropdown-item" href="https://chidam.pages.dev" target="_blank">Web developer</a></li>
            </ul>
          </li>
        </ul>
      </div>
    </div>
  </nav>
<Router/>
<style>
.navbar{
    background: rgb(134, 234, 241,0.5);
    }
 .navbar-brand{
     font-family: "bsteel";
     color: green;
     font-size: 2rem;
     letter-spacing: 0.5rem;

 }
 .nav-item{
     color: #686822;
     font-size: 1.3rem;
     text-transform: lowercase;
     letter-spacing: 0.1rem;
     font-family: "roboto";
 }
  .dropdown-menu{
    background: rgb(134, 234, 241,0.8);
  }
</style>