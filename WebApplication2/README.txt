Author : Aditya Patel
Author ID : 0751432
Program: Creating MVC Tutorial

9/22/2022 - Part 1 & 2 - Together
------------------------------------------------------
1000: Created Hello World Controller

1005: Changing Hello Controller file .cs.

1038: Testing Appilication.

1045: ID Error > Wrong Spell

1045: Application Running smoottttttt...

------------------------------------------------------

9/22/2022 - Part 3 

------------------------------------------------------

1100 : Starting Part 3.

1102 : Changed Index Function in Controller .cs.

1108 : Task - Dynamically change the year of copyright.
		Task Completed.

1109: 
--------------------------

<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Bootstrap Final Test</title>
    
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/css/bootstrap.min.css">

    <style>

      body{
        margin: auto;
        padding: auto;
      }

      main{
        vertical-align: middle;
        text-align: center;
        margin: 250px;
      }

      a{
        text-align: center;
        margin: auto;
        padding: auto;
      }

      .custom-tooltip {
        --bs-tooltip-bg: var(--bs-primary);
      }

      .modal{
        --bs-modal-bg: #0d6efd;
      }
      .modal-title{
        color:white;
      }
      .modal-body{
        background-color: cornsilk;
      }
    </style>

    

  </head>
  <body>

    <main>

      <span data-bs-toggle="modal" data-bs-target="#exampleModal">
       <a class="btn btn-primary" data-bs-toggle="tooltip" data-bs-title="Default tooltip" data-bs-placement="top" href="#" role="button">
         Link</a></span>

       <!-- Modal -->
      <div class="modal fade modal-dialog modal-dialog-centered" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
        <div class="modal-dialog">
          <div class="modal-content">
            <div class="modal-header">
              <h1 class="modal-title fs-5" id="exampleModalLabel">Aditya Patel</h1>
              <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
            </div>
            <div class="modal-body">
              <div class="container-fluid text-center p-3 m-0 border-0 bd-example bd-example-row">
                <div class="row">
                  <div class="col px-3">.px-3 </div>
                  <div class="col ms-4">.ms-4</div>
                  <div class="col g-2">g-2</div>

                </div>
            </div>
            <div class="modal-footer">
              <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
            </div>
          </div>
        </div>
      </div>
    </main>

    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-OERcA2EqjJCMA+/3y+gxIOqMEjwtxJY7qPCqsdltbNJuaOe923+mo//f6V8Qbsw3"
    crossorigin="anonymous"></script>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>

    <script>
      const tooltipTriggerList = document.querySelectorAll('[data-bs-toggle="tooltip"]')
      const tooltipList = [...tooltipTriggerList].map(tooltipTriggerEl => new bootstrap.Tooltip(tooltipTriggerEl))
    </script>
  </body>
</html>
