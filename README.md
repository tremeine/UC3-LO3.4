<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <!-- Compiled and minified CSS -->
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/css/materialize.min.css"
    />
    <!--Import Google Icon Font-->
    <link
      href="https://fonts.googleapis.com/icon?family=Material+Icons"
      rel="stylesheet"
    />
    <style>
      .col > div {
        background-color: lightblue;
        height: 120px;
      }
      nav .badge {
        position: relative;
        top: 20px;
        right: 20px;
      }
    </style>
    <title>UC 3 LO 3.4</title>
  </head>
  <body>
    <nav class="nav-wrapper blue lighten-2">
      <div class="container">
        <a href="#" class="brand-logo">Site Title </a>
        <a
          href="#"
          class="sidenav-trigger hide-on-large-only"
          data-target="mobile-links"
        >
          <i class="material-icons">menu</i>
        </a>
        <ul class="right hide-on-med-and-down">
          <li><a href="#">Home</a></li>
          <li><a href="#">About</a></li>
          <li><a href="#">Contact</a></li>
          <li>
            <a href="#" class="btn-floating indigo darken-1 z-depth-0">
              <i class="material-icons">notifications</i>
            </a>
          </li>
          <li><span class="badge white-text red new">5</span></li>
        </ul>
      </div>
    </nav>
    <ul class="sidenav" id="mobile-links">
      <li><a href="#">Home</a></li>
      <li><a href="#">About</a></li>
      <li><a href="#">Contact</a></li>
    </ul>
    <div class="container">
      <h4>Shadows & depth</h4>
      <div class="row">
        <div class="col s2"><div></div></div>
        <div class="col s2">
          <div class="z-depth-1"></div>
        </div>
        <div class="col s2">
          <div class="z-depth-2"></div>
        </div>
        <div class="col s2">
          <div class="z-depth-3"></div>
        </div>
        <div class="col s2">
          <div class="z-depth-4"></div>
        </div>
        <div class="col s2">
          <div class="z-depth-5"></div>
        </div>
      </div>
    </div>

    <!-- Jquery -->
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <!-- Compiled and minified JavaScript -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/js/materialize.min.js"></script>
    <script>
      $(document).ready(function () {
        $(".sidenav").sidenav();
      });
    </script>
  </body>
</html>
