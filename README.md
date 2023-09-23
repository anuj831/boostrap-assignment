# boostrap-assignment
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <meta name="description" content="Bootstrap landing page">
    <meta name="author" content="Nav Appaiya">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
    <script src="https://code.jquery.com/ui/1.12.1/jquery-ui.js"></script>

    <title>Example landing page for Bootstrap</title>
    <style>

        html {
            font-size: 14px;
        }
        @media (min-width: 768px) {
            html {
                font-size: 16px;
            }
        }

        .container {
            max-width: 960px;
        }

        .pricing-header {
            max-width: 700px;
        }

        .card-deck .card {
            min-width: 220px;
        }

        .border-top { border-top: 1px solid #e5e5e5; }
        .border-bottom { border-bottom: 1px solid #e5e5e5; }

        .box-shadow { box-shadow: 0 .25rem .75rem rgba(0, 0, 0, .05); }
        #navbarScroll{
        padding-left:64%;
    }
    .nav-link:hover{
        text-decoration: underline;
    }
    .pricing-card.highlighted {
  border: 2px solid #007bff; /* Adjust the highlighting style as needed */
}
    </style>

  </head>

  <body>
    <div class="container-fluid">
        <nav class="navbar  navbar-expand-lg bg-body-tertiary" style="background-color: red;">
            <div class="container-fluid">
              <a class="navbar-brand" href="#">Company Name</a>
              <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarScroll" aria-controls="navbarScroll" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse" id="navbarScroll">
                <ul class="navbar-nav me-auto my-2 my-lg-0 navbar-nav-scroll" style="--bs-scroll-height: 100px;">
                  <li class="nav-item">
                    <a class="nav-link active" aria-current="page" href="#">Features</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link active" aria-current="page" href="#">Enterprise</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link active" aria-current="page" href="#">Support</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link active" aria-current="page" href="#">Pricing</a>
                  </li>
                 <button type="button" class="btn btn-outline-primary">Primary</button>
                 
                </ul>
              
              </div>
            </div>
          </nav>
        </div>


   


    <!--mid part -->
    <div class="pricing-header px-3 py-3 pt-md-5 pb-md-4 mx-auto text-center">
      <h1 class="display-4">Landing here</h1>
      <p class="lead">Quickly build an effective pricing table for your potential customers with this Bootstrap example. It's built with default Bootstrap components and utilities with little customization.</p>
    </div>

    <div class="container">
      <div class="row">
        <div class="col-md-12">
          <label for="user-slider">Number of Users:</label>
          <input type="range" id="user-slider" min="0" max="30" step="10" value="0">
        </div>
      </div>
    </div>

    <div class="container">
      <div class="row">
        <div class="col-md-4">
            <div class="card mb-4 box-shadow pricing-card">
                <div class="card-header">
                  <h4 class="my-0 font-weight-normal">Free</h4>
                </div>
                <div class="card-body">
                  <h1 class="card-title pricing-card-title">$0 <small class="text-muted">/ mo</small></h1>
                  <ul class="list-unstyled mt-3 mb-4">
                    <li>10 users included</li>
                    <li>2 GB of storage</li>
                    <li>Email support</li>
                    <li>Help center access</li>
                  </ul>
                  <button type="button" class="btn btn-lg btn-block btn-outline-primary" class="btn btn-primary" data-toggle="modal" data-target="#myModal">Sign up for free</button>
                  
                </div>
              </div>
        </div>
        <div class="col-md-4">
            <div class="card mb-4 box-shadow pricing-card">
                <div class="card-header">
                  <h4 class="my-0 font-weight-normal">Pro</h4>
                </div>
                <div class="card-body">
                  <h1 class="card-title pricing-card-title">$15 <small class="text-muted">/ mo</small></h1>
                  <ul class="list-unstyled mt-3 mb-4">
                    <li>20 users included</li>
                    <li>10 GB of storage</li>
                    <li>Priority email support</li>
                    <li>Help center access</li>
                  </ul>
                  <button type="button" class="btn btn-lg btn-block btn-primary">Get started</button>
                </div>
              </div>
        </div>
        <div class="col-md-4">
            <div class="card mb-4 box-shadow pricing-card">
                <div class="card-header">
                  <h4 class="my-0 font-weight-normal">Enterprise</h4>
                </div>
                <div class="card-body">
                  <h1 class="card-title pricing-card-title">$29 <small class="text-muted">/ mo</small></h1>
                  <ul class="list-unstyled mt-3 mb-4">
                    <li>30 users included</li>
                    <li>15 GB of storage</li>
                    <li>Phone and email support</li>
                    <li>Help center access</li>
                  </ul>
                  <button type="button" class="btn btn-lg btn-block btn-primary">Contact us</button>
                </div>
              </div>
        </div>
      </div>
    </div>

    <!--endof mid part-->

    <!--footer part-->
    <footer class="pt-4 my-md-5 pt-md-5 border-top">
        <div class="container">
          <div class="row">
            
<div class="col-12 col-md">
    <img class="mb-2" src="https://getbootstrap.com/docs/4.0/assets/brand/bootstrap-solid.svg" alt="" width="24" height="24">
    <small class="d-block mb-3 text-muted">© 2017-2018</small>
  </div>
            <div class="col-6 col-md">
              <h5>Features</h5>
              <ul class="list-unstyled text-small">
                <li><a class="text-muted" href="#">Cool stuff</a></li>
                <li><a class="text-muted" href="#">Random feature</a></li>
                <li><a class="text-muted" href="#">Team feature</a></li>
                <li><a class="text-muted" href="#">Stuff for developers</a></li>
                <li><a class="text-muted" href="#">Another one</a></li>
                <li><a class="text-muted" href="#">Last time</a></li>
              </ul>
            </div>
            <div class="col-6 col-md">
              <h5>Resources</h5>
              <ul class="list-unstyled text-small">
                <li><a class="text-muted" href="#">Resource</a></li>
                <li><a class="text-muted" href="#">Resource name</a></li>
                <li><a class="text-muted" href="#">Another resource</a></li>
                <li><a class="text-muted" href="#">Final resource</a></li>
              </ul>
            </div>
            <div class="col-6 col-md">
              <h5>About</h5>
              <ul class="list-unstyled text-small">
                <li><a class="text-muted" href="#">Team</a></li>
                <li><a class="text-muted" href="#">Locations</a></li>
                <li><a class="text-muted" href="#">Privacy</a></li>
                <li><a class="text-muted" href="#">Terms</a></li>
              </ul>
            </div>
          </div>
        </div>
      </footer>
      
     




 <!--modal-->
 <form action ="{getform-forms.maakeetoo.com/formapi/679}" method="POST">
 <div class="modal fade" id="myModal">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h4 class="modal-title">Fill in the Form</h4>
        <button type="button" class="close" data-dismiss="modal">&times;</button>
      </div>
      <div class="modal-body">
        <form>
          <div class="form-group">
            <label for="name">Name:</label>
            <input type="text" class="form-control" id="name">
          </div>
          <div class="form-group">
            <label for="email">Email:</label>
            <input type="email" class="form-control" id="email">
          </div>
          <div class="form-group">
            <label for="comments">Order Comments:</label>
            <textarea class="form-control" id="comments"></textarea>
          </div>
          <button type="submit" class="btn btn-primary">Submit</button>
        </form>
      </div>
    </div>
  </div>
</div>
</form>
  <!--endof modal-->

    <!--endof footer-->
    <!-- Bootstrap core JavaScript
    ================================================== -->
    <!-- Placed at the end of the document so the pages load faster -->
    
  
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.min.js" integrity="sha384-XE8f4v5tp5T6e9xjOTkDjGYbF5RqeK+I5qLH0R5Pv5Lqj1aYi5Kny2Kd8KCk6f5ab" crossorigin="anonymous"></script>
  </body>


  <script>
    // Function to handle slider change
    function handleSliderChange() {
      var slider = document.getElementById("user-slider");
      var value = slider.value;
      
      // Calculate the plan index based on the slider value
      var planIndex = Math.floor(value / 10);
  
      // Remove the 'highlighted' class from all pricing cards
      var pricingCards = document.querySelectorAll(".pricing-card");
      pricingCards.forEach(function(card) {
        card.classList.remove("highlighted");
      });
  
      // Add the 'highlighted' class to the selected pricing card
      pricingCards[planIndex].classList.add("highlighted");
    }
  
    // Attach the 'input' event listener to the slider
    var slider = document.getElementById("user-slider");
    slider.addEventListener("input", handleSliderChange);
  
    // Initial highlighting of the first plan
    handleSliderChange();
  </script>
  
  <script>
    // Function to handle form submission
    function handleFormSubmit(event) {
      event.preventDefault(); // Prevent the default form submission behavior
  
      // Get the form values
      const name = document.getElementById("name").value;
      const email = document.getElementById("email").value;
      const comments = document.getElementById("comments").value;
  
      // Populate the modal content with the form values
      const modalBody = document.querySelector(".modal-body");
      modalBody.innerHTML = `
        <p><strong>Name:</strong> ${name}</p>
        <p><strong>Email:</strong> ${email}</p>
        <p><strong>Order Comments:</strong> ${comments}</p>
      `;
  
      // Display the modal with the populated content
      $('#myModal').modal('show');
    }
  
    // Attach the 'submit' event listener to the form
    const submissionForm = document.getElementById("submissionForm");
    submissionForm.addEventListener("submit", handleFormSubmit);
  </script>

</html>

