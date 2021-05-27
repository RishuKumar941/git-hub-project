<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
    <title>repl.it</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-+0n0xVW2eSR5OomGNYDnhzAbDsOXxcvSN1TPprVMTNDbiYZCxYbOOl7+AMvyTG2x" crossorigin="anonymous">
    <link href="style.css" rel="stylesheet" type="text/css" />

    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" integrity="sha512-iBBXm8fW90+nuLcSKlbmrPcLa0OT92xO1BIsZ+ywDWZCvqsWgccV3gFoRBv0z+8dLJgyAHIhR35VZc2oM/gI1w==" crossorigin="anonymous" referrerpolicy="no-referrer" />


  </head>
  <body>

    <!-- Navbar -->
    <nav class="navbar sticky-top navbar-expand-lg navbar-dark bg-danger">
  <div class="container-fluid">
    <a class="navbar-brand text" href="#">Rishu </a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link active " aria-current="page" href="#">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#contact">Contact us</a>
        </li>

        <li class="nav-item">
          <a class="nav-link" href="#works">My Works</a>
        </li>
        
        <li class="nav-item">
          <a class="nav-link disabled" href="#" My Skills="-1" aria-disabled="true">Contact us</a>
        </li>

      </ul>
     
    </div>
  </div>
</nav>
<main class="container mt-3">
  <section id="hero" class="d-flex justify-content-sm-center d-flex justify-sm-content-md-evenly align-items-center flex-column-reverse gap-3   flex-md-row">

    <!-- Hero -->
    <div class="d-flex justify-sm-center align-items-center flex-column flex-md-column justify-content-md-start align-items-md-start">
      <h5> Hello! </h5>
      <h1>Im Rishu  </h1>
      <p> I am a Full Stack Web Developer</p>
      <button class="btn btn-danger"> My Resume </button>
      </div>
      <div class="d-none d-md-block w-50 h-50">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQS8UWMhN1Fhp-IawTqFxOUI-K6sgelMTQdXA&usqp=CAU" class="w-50 H-50 rounded-circle align-center" >
     </div>
     <div class="d-none d-md-block w-25 h-25">
    </section>

     <section  id="skills" class=" mt-4  p-4 ">
    <!-- My Skills -->
    <h1 class="text-danger text-center">My Skills </h1>

    <div class="d-flex  d-md-none justify-content-evenly mt-4">
      <i class="fab fa-html5 fa-7x" style="color:#ff4000"></i>
      <i class="fab fa-css3-alt fa-7x" style="color:#0040ff"></i>
      <i class="fab fa-bootstrap fa-7x" style="color:##8000ff"></i>
      </div>
    </section>

    <section id="works" class="mt-5 p-4">

    <!-- My Works -->
    
    <h1 class="text-danger text-center">  My Work</h1>
<div class="d-flex flex-column flex-md-row justify-content-md-evenly">
  <div class="card mt-3 mb-3">
  <img src="https://images.unsplash.com/photo-1531297484001-80022131f5a1?ixid=MnwxMjA3fDB8MHxzZWFyY2h8MTZ8fHRlY2hub2xvZ3l8ZW58MHwwfDB8fA%3D%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" class="card-img-top" alt="...">
  <div class="card-body">
    <h5 class="card-title">Web Development using bootstraps.</h5>
    <p class="card-text">Build an amazing website which would help the people around the world</p>
    <a href="#" class="btn btn-dark">View Source <i class="fab fa-github-square"></i></a>
  </div>
</div>
    </section>

     
<section id="contact" class="mt-4 py-4">

    <!-- Contact us -->

    <h1 class="text-danger text-center">Contact us </h1>
<div class="row">
  <div class="col-sm col-md-8">
    <form>
      <div class="mb-3">
  <label for="exampleFormControlInput1" class="form-label">Email Address</label>
  <input type="email" required class="form-control" id="exampleFormControlInput1" placeholder="enter your message!">
</div>
<div class="mb-3">
  <label for="exampleFormControlTextarea1" class="form-label">Example textarea</label>
  <textarea class="form-control" id="exampleFormControlTextarea1" required rows="3"></textarea>
</div>
<button type="submit" class="btn btn-primary">
  Submit
  </button>

    </form>
  </div>
  <div class=" col-sm col-md-4">
    <div class="mt-3">
<h4> <i class="fas fa-at"></i> rishu20021028@gmail.com </h4>
<button type="button" class="btn btn-link"></button>

<a href="https://github.com/intel/haxm"><i class="fab fa-github-square"></i></a>

      </div>
    </section>
</div>
</main>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/js/bootstrap.bundle.min.js" integrity="sha384-gtEjrD/SeCtmISkJkNUaaKMoLD0//ElJ19smozuHV6z3Iehds+3Ulb9Bn9Plx0x4" crossorigin="anonymous"></script>
    </body>
  
</html>
