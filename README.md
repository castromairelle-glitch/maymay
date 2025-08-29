<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Web Portfolio</title>

  <!-- Font Awesome -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  
  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
  
  <!-- Custom CSS -->
  <link rel="stylesheet" href="elle.css">
</head>
<body>
  <!-- Navbar -->
  <header class="bg-dark text-white p-2">
    <nav class="navbar navbar-expand-lg navbar-dark container">
      <a class="navbar-brand" href="mair.html">Web Portfolio</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ml-auto">
          <li class="nav-item"><a class="nav-link" href="mair.html">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="about.html">About</a></li>
          <li class="nav-item"><a class="nav-link" href="education.html">Education</a></li>
          <li class="nav-item"><a class="nav-link" href="other.html">Others</a></li>
        </ul>
      </div>
    </nav>
  </header>

  <!-- Main Content -->
  <main class="container mt-4 text-center">
    <img src="mayie formal.jpeg" alt="Profile Image" class="profile-img">

    <h2 class="font-weight-bold">Mairelle C. Castro</h2>
    <h4 class="text-muted">Front End Developer</h4>
    <p class="mt-3">
      I’m an IT enthusiast who loves exploring tech, coding,
       and building cool stuff online. This portfolio is a simple collection
        of my projects, skills, and little experiments as I grow in the IT field.
         Always learning, always curious, and always up for creating something new.
    </p>

    <!-- Buttons trigger modals -->
    <a href="#" class="btn btn-primary btn-custom" data-toggle="modal" data-target="#resumeModal">Resume</a>
    <a href="#" class="btn btn-secondary btn-custom" data-toggle="modal" data-target="#letterModal">Application Letter</a>
  </main>

  <!-- Resume Modal -->
  <div class="modal fade" id="resumeModal" tabindex="-1" role="dialog" aria-labelledby="resumeModalLabel" aria-hidden="true">
    <div class="modal-dialog modal-xl" role="document">
      <div class="modal-content">
        <div class="modal-header">
          <h5 class="modal-title" id="resumeModalLabel">My Resume</h5>
          <button type="button" class="close" data-dismiss="modal" aria-label="Close">
            <span aria-hidden="true">&times;</span>
          </button>
        </div>
        <div class="modal-body p-0">
          <!-- Embed Resume PDF -->
          <iframe src="resume.pdf" width="100%" height="600px" style="border:none;"></iframe>
        </div>
      </div>
    </div>
  </div>

  <!-- Application Letter Modal -->
  <div class="modal fade" id="letterModal" tabindex="-1" role="dialog" aria-labelledby="letterModalLabel" aria-hidden="true">
    <div class="modal-dialog modal-xl" role="document">
      <div class="modal-content">
        <div class="modal-header">
          <h5 class="modal-title" id="letterModalLabel">Application Letter</h5>
          <button type="button" class="close" data-dismiss="modal" aria-label="Close">
            <span aria-hidden="true">&times;</span>
          </button>
        </div>
        <div class="modal-body p-0">
          <!-- Embed Application Letter PDF -->
          <iframe src="application_letter.pdf" width="100%" height="600px" style="border:none;"></iframe>
        </div>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="text-center py-3">
    <p>
      <i class="fas fa-phone"></i> +63 9945105694 &nbsp; | &nbsp;
      <i class="fas fa-envelope"></i> castromairelle@gmail.com &nbsp; | &nbsp;
      <i class="fab fa-facebook"></i> 
      <a href="https://facebook.com/yourprofile" target="_blank">Mairelle Castro</a>
    </p>
  </footer>

  <!-- Bootstrap JS and dependencies -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
