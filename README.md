<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Resume - Manasa M S</title>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

<style>
  body{
    background:#000;
    font-family:"Poppins",sans-serif;
    display:flex;
    justify-content:center;
    flex-direction:column;
    align-items:center;
    min-height:100vh;
    padding:20px;
  }

  /* NAV */
  .top-nav{
    position:absolute;
    top:15px;
    right:20px;
    display:flex;
    gap:15px;
  }
  .top-nav a{
    color:white;
    font-size:1.1rem;
    text-decoration:none;
  }
  .top-nav a:hover{color:red;}

  .card{
    background:#fff;
    border:2px solid red;
    border-radius:20px;
    padding:50px;
    max-width:700px;
    width:100%;
    text-align:center;
  }

  h2{
    color:darkblue;
    font-size:2rem;
    border-bottom:2px solid red;
    display:inline-block;
    padding-bottom:8px;
    margin-bottom:25px;
  }

  .resume-btn{
    background:blue;
    color:white;
    padding:15px 25px;
    border-radius:12px;
    text-decoration:none;
    font-weight:bold;
    display:inline-flex;
    gap:10px;
    align-items:center;
  }

  .resume-btn:hover{
    background:lime;
    color:black;
  }

  .nav-buttons{
    display:flex;
    justify-content:center;
    gap:20px;
    margin-top:25px;
  }

  .nav-buttons a{
    background:blue;
    border:2px solid red;
    color:white;
    padding:12px 20px;
    border-radius:10px;
    text-decoration:none;
  }
  .nav-buttons a:hover{
    background:lime;
    color:black;
  }
</style>
</head>

<body>

<!-- NAV -->
<div class="top-nav">
  <a href="manasa.html">Home</a>
  <a href="knowmore.html">Index</a>
  <a href="contact.html">Contact</a>
</div>

<div class="card">
  <h2>My Resume</h2>
  <p>You can download my resume below:</p>

  <!-- PURE HTML DOWNLOAD BUTTON -->
  <a href="RESUMEMANASA.pdf" download="Manasa_Resume.pdf" class="resume-btn">
      <i class="fas fa-file-pdf"></i> Download Resume
  </a>
</div>

<div class="nav-buttons">
  <a href="knowmore.html"><i class="fas fa-arrow-left"></i> Back</a>
  <a href="contact.html">Next <i class="fas fa-arrow-right"></i></a>
</div>

</body>
</html>
