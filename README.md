# Demo_Bootstrap
<!doctype html>
<html lang="en">
  <head>
    <title>Bootstrap-Demo</title>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
     <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.1/font/bootstrap-icons.css">
    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
    <link rel="stylesheet" href="projectBS.css" text="text/css">

</head>
  <body>
      
    <div class="container-fluid">
        <div class="row confl">
          <div class="col-md-3 px-5">
            <nav class="navbar navbar-expand navbar-light ">
                <a herf="" class="navbar-brand  text-light"><i class="bi bi-bootstrap"></i></a>
                <ul class="navbar-nav">
                    <li class="nav-item"><a class="nav-link  text-light" href="">Docs</a></li>
                    <li class="nav-item"><a class="nav-link  text-light" href="">Exapmles</a></li>
                    <li class="nav-item"><a class="nav-link  text-light" href="">Icons</a></li>
                    <li class="nav-item"><a class="nav-link  text-light" href="">Themes</a></li>
                    <li class="nav-item"><a class="nav-link  text-light" href="">Blogs</a></li>
                </ul>
            </nav>
          </div>
          
          <div class="col-md-1">
          </div>

          <div class="col-md-3 px-5">
            <nav class="navbar navbar-expand navbar-light ">
                <button class="btn btn-light ml-5 " type="button">
                    <span class="badge badge-light badge-pill mr-3 text-light text-muted"><i class="bi bi-search mr-3"></i>Search</span>
                    <span class="badge text-right ml-2 text-light text-muted" style="background-color: rgb(5, 5, 101);">CTRL+K</span>
                </button>
            </nav>
          </div>
          
          <div class="col-md-1">
          </div>

          <div class="col-md-3 px-5">
            <nav class="navbar navbar-expand navbar-light ">
                <ul class="navbar-nav mr-5">
                    <li class="nav-item"><a href="" class="nav-link text-light"><i class="bi bi-github"></i></a> </li>
                    <li class="nav-item"><a href="" class="nav-link text-light"><i class="bi bi-twitter"></i></a> </li>
                    <li class="nav-item"><a href="" class="nav-link text-light"><i class="bi bi-opencollective"></i></a> </li>
                </ul>
            
              <div class="btn-group ">
                <button class="btn text-light dropdown-toggle border-left" data-toggle="dropdown" type="button">v5.3</button>
                <div class="dropdown-menu bordered-bottom">
                    <span class="text-muted ml-4">v5 release</span>
                    <div class="confl text-light"><span class="ml-4">Latest (5.3.x)<i class="bi bi-check-lg float-right pr-3"></i> </span></div>
                    <ul class="list-group">
                      <li class="list-group-item">
                        <a href="" class="dropdown-item">v5.2.3</a>
                        <a href="" class="dropdown-item">v5.2.3</a>
                        <a href="" class="dropdown-item">v5.1.3</a>
                        <a href="" class="dropdown-item">v5.0.2</a>
                      </li>
                    </ul>
                    <span class="text-muted ml-4">Previous release</span>
                    <ul class="list-group">
                      <li class="list-group-item">
                        <a href="" class="dropdown-item">v4.6.x</a>
                        <a href="" class="dropdown-item">v3.4.3</a>
                        <a href="" class="dropdown-item">v2.3.2</a>
                      </li>
                    </ul>
                    <a class=" text-dark ml-4" href="">All versions</a>   
                </div>
              </div>
            
          

              <div class="btn-group">
                <button class="btn text-light dropdown-toggle text-right border-left" data-toggle="dropdown" type="button" ><i class="bi bi-brightness-high"></i></button>
                <div class="dropdown-menu">
                    <a href="" class="dropdown-item "><span class="bi bi-brightness-high-fill text-muted">Light</span></a>
                    <a href="" class="dropdown-item "><span class="bi bi-moon-stars-fill text-muted">Dark</span></a>
                    <a href="" class="dropdown-item "><span class="bi bi-circle-half text-muted">Auto</span></a>
                </div>
              </div>

            </nav>
        </div>
      </div>

      <div class="row justify-content-center bgpic">
          <div class="col-6 p-1 pl-3">
              <div class="carousel slid" data-ride="carousel" id="carouselid">
                  <div class="carousel-inner" >
                      <!--Image place-->
                      <div class="carousel-item">
                          <img src="carousel1.jpg"  class="d-display h-100 w-100">
                      </div>
                      <div class="carousel-item active">
                          <img src="carousel2.jpg" class="d-display h-100 w-100">
                      </div>
                      <div class="carousel-item">
                          <img src="carousel3.jpg" class="d-display h-100 w-100">
                      </div>
                      <div class="carousel-item">
                          <img src="carousel2.jpg" class="d-display h-100 w-100">
                      </div>
                      <div class="carousel-item">
                          <img src="carousel1.jpg" class="d-display h-100 w-100">
                      </div>
                  </div>
                  <!-- prev and next slider-->
                  <a href="#carouselid" class="carousel-control-prev" data-slide="prev">
                      <span class="carousel-control-prev-icon"></span>
                  </a>
                  <a href="#carouselid" class="carousel-control-next" data-slide="next">
                      <span class="carousel-control-next-icon"></span>
                  </a>

                  <ol class="carousel-indicators">
                      <li data-target="#carouselid" data-slide-to="0"></li>
                      <li class="active" data-target="#carouselid" data-slide-to="1"></li>
                      <li data-target="#carouselid" data-slide-to="2"></li>
                      <li data-target="#carouselid" data-slide-to="3"></li>
                      <li data-target="#carouselid" data-slide-to="4"></li>
                      

                  </ol>
              </div>
          </div>
        
        <div class="col-md-5 offset-md-2 p-0 mt-5">
          <button class="btm btn-warning">New in v5.3</button><span class="ml-2">Color mode support,expanded color palette and more!</span>
        </div>
      </div>
      <!--Row-2 complete-->
      <div class="row bgpic">
        <div class="col-12 text-center pt-4 mb-5 mt-2">
          <img src="Bootstrap_logo.png" class="imgCar" >
        </div>
        <div class="col-12 text-center">
          <h1>Build fast, responsive sites <br> with Bootstrap</h1>
        </div>
        <div class="col-12">
          <p class="text-center lead">Powerful, extensible, and feature-packed frontend toolkit. Build and customize<br> with Sass, utilize prebuilt grid system and components, and bring projects to life<br> with powerful JavaScript plugins.</p>
        </div>
        
        
        <div class="col-md-3 offset-md-4">
          <div class="input-group">
            <div class="input-group-prepend">
              <span class="input-group-text" >$</span>
            </div>
            <input class="form-control" type="text" placeholder="npm i bootstrap@5.3.2" readonly>
            <div class="input-group-append">
              <div class="input-group-text"><i class="bi bi-clipboard"></i></div>
            </div>
          </div>
          </div>
          <div class="col-md-2">
          <button class="btn confl" type="button"><span class="mr-3 pr-3 bi bi-book-half text-light">Read the docs</span></button>
          </div>

        <div class="col-md-6 mt-5 text-right">
          <span> Curently <b>v5.3.2</b></span>
          </div>
          <div class="col-md-6 mt-5">
          <ul class=" list-inline ">
            <li class="list-inline-item"> <a href="" class="text-dark "><u> Download</u></a> </li>
            <li class="list-inline-item"> <a href="" class="text-dark"><u>All release</u></a> </li>
          </ul>
        </div>

        <div class="col-md-4  offset-md-4 mt-5 mb-3">
          <div class="card bgpic">
            <div class="row">
              <div class="col-md-6">
                <img src="/RiverInForest.jpg" class="card-img" alt="">
              </div>
              <div class="col-md-6">
                <div class="card-body">
                  <div class="card-title">Mountain</div>
                  <p class="card-text fonts">
                    Forests are a diverse ecosystem on Earth.</p>
                </div>
              </div>
            </div>
          </div>
        </div>
       

        
        <div class="col-md-6 offset-md-3 pl-5">
          <h1 class="pl-5">Get started any way you want</h1>
        </div>

        <div class="col-md-5 offset-md-3 text-center pl-3">
          <p class="lead pl-5">Jump right into building with Bootstrap—use the CDN, install it via 
            package manager, or download the source code.</p>
        </div>
        <div class="col-12 text-center"><a href="" class="pr-5" ><u class=" text-dark"><b>Read installation docs</b></u><i class="bi bi-arrow-right  ml-2 "></i></a> </div>


        <!-- Row 3 complete-->
      </div>

      <div class="row">
          <div class="col-md-10 mt-3 offset-md-1">
            <div class="card-group">
            <div class="card border-left-0 border-top-0 border-bottom-0 border-right mr-2">
              <h1 class="bi bi-box-seam pl-3 pt-3"></h1>
              <div class="card-body">
                <h2 class="">Install via package manager</h2>
                <p class="card-text">
                  Install Bootstrap’s source Sass and JavaScript files via npm, RubyGems, Composer, or Meteor.
                  Package managed installs don’t include documentation or our full build scripts. You can also
                  <a href="card-link">use any demo from our Examples repo</a> to quickly jumpstart Bootstrap projects
                </p>
              </div>
            </div>
         
          
          
            <div class="card border-left border-0 ml-2">
              <h1 class="bi bi-globe pl-3 pt-3"></h1>
              <div class="card-body">
                <p class="card-text ">
                  When you only need to include Bootstrap’s compiled CSS or JS, you can use <a href="">jsDelivr</a>.
                  See it in action with our simple<a href="">quick start</a>, or<a href="">browse the examples</a> to jumpstart 
                  your next project. You can also choose to include Popper and our JS<a href=""> separately</a>.
                </p>
              
              </div>
            </div>
          </div>
      </div>


      <div class="col-md-5 offset-md-1">
        <div class="input-group mb-4 mt-3">
          <div class="input-group-prepend">
            <span class="input-group-text">$</span>
          </div>
          <input class="form-control" typr="text" placeholder="npm install bootstrap@5.3.2">
          <div class="input-group-append">
            <span class="bi bi-clipboard input-group-text "></span>
          </div>
        </div>

        <div class="input-group">
          <div class="input-group-prepend">
            <span class="input-group-text">$</span>
          </div>
          <input class="form-control" type="text" placeholder="gem install bootstrap -v 5.3.2">
          <div class="input-group-append">
            <span class="bi bi-clipboard input-group-text"></span>
          </div>
        </div>
      </div>

      <div class="col-md-5">
        <div class="input-group mb-4 mt-3">
          <input class="form-control" type="text" placeholder="<link href=https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css rel= stylesheet  integrity= sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN crossorigin= anonymous" readonly>
          <div class="input-group-append">
            <button type="button" class=" btn input-group-text"><span class="bi bi-clipboard"></span></button>
          </div>
        </div>

        <div class="input-group ">
          <input class="form-control" type="text" placeholder="<script src=|https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js|  integrity=|sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL| crossorigin=|anonymous|></script>" readonly>
          <div class="input-group-append">
            <button type="button" class=" btn input-group-text"><span class="bi bi-clipboard"></span></button>
          </div>
        </div>
      </div>


      <div class="col-md-6 offset-md-3 mt-5">
        <div class="">
          <h4 class="text-center">Read our getting started guides</h4>
          <span class="text-center pl-5">Get a jump on including Bootstrap's source files in a new project with our official guides.</span>
        </div>
      </div>

      <div class="col-md-4 offset-md-5 mt-5">
        <figure class="figure">
          <img src="WebPack.png" class="img-fluid figure-img imgCar" alt="">
          <figcaption class="figure-caption text-center">WebPack</figcaption>
        </figure>
        <figure class="figure">
          <img src="parcel.jpeg" class="img-fluid figure-img imgCar ml-3" alt="">
          <figcaption class="figure-caption text-center">Parcel</figcaption>
        </figure>
        <figure class="figure">
          <img src="Vite.jpeg" class="img-fluid figure-img imgCar ml-3" alt="">
          <figcaption class="figure-caption text-center">Vite</figcaption>
        </figure>
      </div>

      <div class="col-md-6 offset-md-1">
        <h1 class="bi bi-boxes"></h1>
        <h1>Customize everything with Sass</h1>
        <p>Bootstrap utilizes Sass for a modular and customizable architecture.
          Import only the components you need, enable global options like gradients and shadows,
          and write your own CSS with our variables, maps, functions, and mixins.
        </p>
        <a href="" class=""><u style="font-size:20px;">Learn more about customizing </u><i class="bi bi-arrow-right"></i></a>
      </div>
      </div>

    </div>

    <!--2nd container-->
    <div class="container-fluid mt-5 bg">
      <div class="row justify-content-around mb-5 border-top pt-5">
        <div class="col-sm-3">
            <h4 class="bi bi-bootstrap-fill">  Bootstrap</h4>
              <p class="footer-text">
                Designed and built with all the love in the world by the Bootstrap team with the help of our contributors.
               <br> <br>Code licensed MIT, docs CC BY 3.0.
               <br> <br>Currently v5.3.2.
              </p>
        </div>


        <div class="col-sm-1"> 
          <ul class="listStyle">
          <li><h4 class=" text-black-50">Link</h4></li>
          <li class=""><a class="text-dark" href="">Home</a> </li>
          <li class=""><a class="text-dark" href="">Docs</a></li>
          <li class=""><a class="text-dark" href="">Examples</a></li>
          <li class=""><a class="text-dark" href="">Icons</a> </li>
          <li class=""><a class="text-dark" href="">Themes</a></li>
          <li class=""><a class="text-dark" href="">Blog</a></li>
          <li class=""><a class="text-dark" href="">Swag store</a></li>
          </ul>
        </div>


        <div class="col-sm-2">
          <ul class="listStyle">
          <li><h4 class=" text-black-50">Guides</h4></li>
          <li class=""><a class="text-dark" href="">Getting started</a> </li>
          <li class=""><a class="text-dark" href="">Starter templet</a></li>
          <li class=""><a class="text-dark" href="">webpack</a></li>
          <li class=""><a class="text-dark" href="">Parcel</a> </li>
          <li class=""><a class="text-dark" href="">Vite</a></li>
          </ul>
        </div>


        <div class="col-sm-2">
          <ul class="listStyle">
          <li><h4 class=" text-black-50">Projects</h4></li>
          <li class=""><a class="text-dark" href="">Bootstrap 5 </a> </li>
          <li class=""><a class="text-dark" href="">Bootstrap 4</a></li>
          <li class=""><a class="text-dark" href="">Icons</a></li>
          <li class=""><a class="text-dark" href="">RFS</a> </li>
          <li class=""><a class="text-dark" href="">Examples repo</a></li>
          </ul>
        </div>


        <div class="col-sm-2">
          <ul class="listStyle">
          <li><h4 class=" text-black-50">Community</h4></li>
          <li class=""><a class="text-dark" href="">Issues </a> </li>
          <li class=""><a class="text-dark" href="">Discussions </a></li>
          <li class=""><a class="text-dark" href="">Corporate sponsors</a></li>
          <li class=""><a class="text-dark" href="">Open Collective</a> </li>
          <li class=""><a class="text-dark" href="">Stack Overflow</a></li>
          </ul>
        </div>

        </div>
      </div>
    </div>
  </body>
</html>
