<!DOCTYPE html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />

    <!-- Bootstrap CSS -->
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC"
      crossorigin="anonymous"
    />

    <title>Bootstrap</title>
  </head>
  <body>
    <nav
      class="navbar navbar-expand-lg navbar-light fixed-top"
      style="background-color: rgb(173, 255, 244)"
    >
      <div class="container">
        <a class="navbar-brand" href="#">
          <img
            src="logo.jpg"
            alt=""
            widht="50"
            height="40"
            class="d-inline-block align-top"
            alt=""
          />
          PEMALANG
        </a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarNav"
          aria-controls="navbarNav"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav ms-auto">
            <li class="nav-item">
              <a class="nav-link" href="home.html">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="buku.html">Buku</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="kontak.html">Kontak</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="login.html">Login</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <br />
    <br />
    <div
      id="carouselExampleControls"
      class="carousel slide"
      data-bs-ride="carousel"
    >
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img
            src="pexels-atanas-milanov-7835812.jpg"
            class="d-block w-100"
            style="height: 460px"
            alt="..."
          />
        </div>
        <div class="carousel-item">
          <img
            src="pexels-johannes-plenio-1423600.jpg"
            class="d-block w-100"
            style="height: 460px"
            alt="..."
          />
        </div>
        <div class="carousel-item">
          <img
            src="px.jpg"
            class="d-block w-100"
            style="height: 460px"
            alt="..."
          />
        </div>
      </div>
      <button
        class="carousel-control-prev"
        type="button"
        data-bs-target="#carouselExampleControls"
        data-bs-slide="prev"
      >
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button
        class="carousel-control-next"
        type="button"
        data-bs-target="#carouselExampleControls"
        data-bs-slide="next"
      >
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>
    <br />
    <br />

    <div class="container mt-3">
      <h2>Perpustakaan Umum Kab.Pemalang</h2>
      <div class="mt-4 p-5 text-dark rounded" style="background-color: #e3f2fd">
        <h1>Info</h1>
        <p>
          Perpustakaan Umum daerah kabupaten pemalang menyediakan buku dengan
          berbagai macam tema/genre. perpustakaan ini juga menyediakan fasilitas
          yang nyaman untuk para pembaca.
        </p>
      </div>
    </div>
    <br />
    <br />

    <section>
      <h2 style="text-align: center">Pilih Topik Yang Anda Minati</h2>
      <div class="row">
        <div class="col-md-3">
          <div class="card m-5" style="width: 10rem">
            <img src="8-books.png" class="card-img-top" alt="..." />
            <div class="card-body">
              <h5 class="card-title text-center">SEJARAH</h5>
            </div>
          </div>
        </div>
        <div class="col-md-3">
          <div class="card m-5" style="width: 10rem">
            <img src="6-blackboard.png" class="card-img-top" alt="..." />
            <div class="card-body">
              <h5 class="card-title text-center">SAINS</h5>
            </div>
          </div>
        </div>
        <div class="col-md-3">
          <div class="card m-5" style="width: 10rem">
            <img src="2-mosque.png" class="card-img-top" alt="..." />
            <div class="card-body">
              <h5 class="card-title text-center">KEAGAMAAN</h5>
            </div>
          </div>
        </div>
        <div class="col-md-3">
          <div class="card m-5" style="width: 10rem">
            <img src="0-chemical.png" class="card-img-top" alt="..." />
            <div class="card-body">
              <h5 class="card-title text-center">TEKNOLOGI</h5>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Optional JavaScript; choose one of the two! -->

    <!-- Option 1: Bootstrap Bundle with Popper -->
    <script
      src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js"
      integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM"
      crossorigin="anonymous"
    ></script>
  </body>
</html>
