# project

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width,initial-scale=1.0">
  <title>CodeMaster Academy</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.3.0/css/bootstrap.min.css">
</head>
<body>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <a class="navbar-brand mx-2" href="#">CodeMaster Academy</a>
    <div class="collapse navbar-collapse">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item"><a class="nav-link" href="#courses">Courses</a></li>
        <li class="nav-item"><a class="nav-link" href="#exercises">Exercises</a></li>
        <li class="nav-item"><a class="nav-link" href="#dashboard">Dashboard</a></li>
        <li class="nav-item"><a class="nav-link" href="#login">Login</a></li>
      </ul>
    </div>
  </nav>

  <!-- Hero Banner -->
  <section class="bg-primary text-white p-5 text-center">
    <h1>Master Coding with Interactive Learning</h1>
    <p>Analyze, Debug, Practice, and Progress — All in One Platform</p>
    <a href="#courses" class="btn btn-light btn-lg">Get Started</a>
  </section>

  <!-- Platform Features -->
  <section class="container my-5">
    <div class="row text-center">
      <div class="col-md-3">
        <h3>Code Analysis</h3>
        <p>Automatic error detection, simple explanations, and improvement suggestions.</p>
      </div>
      <div class="col-md-3">
        <h3>Live Debugger</h3>
        <p>Step-by-step debugging guidance and instant feedback within the browser.</p>
      </div>
      <div class="col-md-3">
        <h3>Auto-Exercises</h3>
        <p>Personalized practice problems and tests tailored to your progress.</p>
      </div>
      <div class="col-md-3">
        <h3>Interactive Tutorials</h3>
        <p>Hands-on lessons with in-browser code execution and instant analytics.</p>
      </div>
    </div>
  </section>

  <!-- Interactive IDE -->
  <section id="exercises" class="bg-light py-5">
    <div class="container">
      <h2 class="mb-4 text-center">Try the Interactive Code Editor</h2>
      <div class="row">
        <div class="col-md-8">
          <!-- Placeholder for actual IDE integration -->
          <textarea class="form-control" rows="10" placeholder="Write your code here..."></textarea>
        </div>
        <div class="col-md-4">
          <button class="btn btn-success w-100 mb-3">Run & Analyze</button>
          <div class="alert alert-info" role="alert">
            <!-- Dynamic feedback placeholder -->
            <strong>Feedback:</strong> Syntax correct. Ready to proceed!
          </div>
          <div>
            <h5>Suggestions</h5>
            <ul>
              <li>Try fixing variable naming.</li>
              <li>Optimize loop structure.</li>
              <li>Check for missing semicolons.</li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Course Catalog -->
  <section id="courses" class="container my-5">
    <h2 class="mb-4 text-center">Explore Courses</h2>
    <div class="row">
      <div class="col-md-4"><div class="card"><div class="card-body"><h5 class="card-title">Python Basics</h5><p>Start coding with friendly, in-depth tutorials and immediate feedback.</p></div></div></div>
      <div class="col-md-4"><div class="card"><div class="card-body"><h5 class="card-title">JavaScript Essentials</h5><p>Grasp core web programming and debug code live as you learn.</p></div></div></div>
      <div class="col-md-4"><div class="card"><div class="card-body"><h5 class="card-title">Java & C++ Foundations</h5><p>Master object-oriented concepts and get real-time code suggestions.</p></div></div></div>
    </div>
  </section>

  <!-- Dashboard - Progress Visualization -->
  <section id="dashboard" class="bg-secondary text-white py-5">
    <div class="container text-center">
      <h2>Your Learning Dashboard</h2>
      <p>Track your completed lessons, earned badges, and next steps.</p>
      <div class="progress my-3" style="height:30px;">
        <div class="progress-bar progress-bar-striped" role="progressbar" style="width: 60%;">60% Complete</div>
      </div>
      <p>Keep learning to unlock your next badge!</p>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center p-3 mt-4">
    © 2025 CodeMaster Academy | Learn, Debug, Succeed!
  </footer>
</body>
</html>
