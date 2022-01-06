<script>
     import {Link} from "svelte-navigator";
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
            <Link class="nav-link active" aria-current="page" style="color: #686822;" to="/">&nbsp;&nbsp;&nbsp;Home&nbsp;&nbsp;&nbsp;</Link>
          </li>
          <li class="nav-item">
            <Link class="nav-link" style="color: #686822;" to="ftrs">&nbsp;&nbsp;&nbsp;Features&nbsp;&nbsp;&nbsp;</Link>
          </li>
          <li class="nav-item">
            <Link class="nav-link" style="color: #686822;" to="price">&nbsp;&nbsp;&nbsp;Pricing&nbsp;&nbsp;&nbsp;</Link>
          </li>
          <li class="nav-item dropdown" >
            <Link class="nav-link dropdown-toggle" style="color: #686822;" to="inspri" id="navbarDropdownMenuLink" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                &nbsp;&nbsp;&nbsp;Dropdown link&nbsp;&nbsp;&nbsp;
            </Link>
            <ul class="dropdown-menu"  aria-labelledby="navbarDropdownMenuLink">
              <li><Link class="dropdown-item" to="inspri">Our Inspiration</Link></li>
              <li><a class="dropdown-item" href="https://chidam.pages.dev" target="_blank">Web developer</a></li>
            </ul>
          </li>
        </ul>
      </div>
    </div>
  </nav>
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