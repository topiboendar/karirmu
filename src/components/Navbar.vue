<template> 
<nav class="navbar navbar-dark navbar-expand-lg fixed-top shadow">
  <div class="container-fluid col-md-11 col-lg-10 mx-auto px-3">
    <a class="navbar-brand" href="#">KarirMu</a>
    <button class="navbar-toggler ms-auto" 
        type="button" 
        data-bs-toggle="collapse" 
        data-bs-target="#navbarScroll" 
        aria-controls="navbarScroll" 
        aria-expanded="false" 
        aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarScroll">
      <ul class="navbar-nav ms-auto my-2 my-lg-0 navbar-nav-scroll" style="--bs-scroll-height: 100px;">
        <li class="nav-item"><a href="#" class="nav-link active">Home</a></li>
        <li class="nav-item"><a href="#" class="nav-link">Jobs</a></li>
        <li class="nav-item"><a href="#" class="nav-link">Blog</a></li>
        <li class="nav-item"><a href="#" class="nav-link" data-bs-toggle="modal" data-bs-target="#signInModal" >Sign In</a></li>
      </ul>
    </div>
  </div>
</nav>
</template>