<!DOCTYPE html>
<html>
<head>
  <title>About Me</title>
  <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
  <header>
    <h1>About Sibusiso Dwayi</h1>
  </header>
  
  <main>
    <section>
      <div class="profile-picture">
        <img src="IMG.jpg" alt="Profile Picture">
      </div>
      
      <div class="details">
        <h2>Personal Details</h2>
        <p>NAME: Sibusiso Dwayi</p>
        <p>LOCATION: 143 Sir Lowry Road,
		 Woodstock,
		 Cape Town</p>
        <p>EMAIL: sibusisodwayi03@gmail.com</p>
        <p>PHONE: 084 287 4758</p>
		<br>
		<br>
		<br>
		 <h3>To Whom It May Concern</h3>
		<p1>I am a third year student at Cape Penisnula University Of Technology. As I am about to complete my Diploma in information 
technology, I am looking forward to joining your company 
where I will have the opportunity to put my knowledge to 
use, as well as have the necessary opportunities to brush 
up on my natural skills and abSilities.
And gain real time experience by applying the 
fundamentals and concepts I have learned throughout my 
course.</p1>
<br>
<br>
<p2>Click the button to see my resume for further information.</p2>
      </div>
      
      <div class="resume-link">
        <a href="SD DWAYI Resume & Relevant Docs.pdf">View My Resume</a>
      </div>
    </section>
  </main>
</body>
</html>
body {
  font-family: Audiowide, sans-serif;
  background-color: #382c2c;
  margin: 0;
  padding: 0;
}

header {
  background-color: #333;
  color: #FFF;
  text-align: center;
  padding: 20px;
}

h1 {
  margin: 0;
  text-shadow: 2px 2px 5px red;
}

main {
  max-width: 800px;
  margin: 20px auto;
  padding: 20px;
  background-color: #787575;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  border-radius: 20px;
}
p{font-family: cooperplate, fantacy;
}
p1{
	
  padding: 10px;
  width: 100px;
  height: 100px;
  text-align: justify;
  text-justify: auto;
  font-family: cooperplate, fantacy;
  border-radius: 8px;
  padding: 2px;
  background-color: #8c8b8b;
}
p2{
  font-family: cooperplate, fantacy;
  text-align: center-right;
}
h3 {
  margin-top: 0;
  background-color: #555;
    text-align: center;

}
.profile-picture {
  text-align: center;
}

.profile-picture img {
  width: 200px;
  border-radius: 50%;
}

.details h2 {
  margin-top: 0;
  background-color: #555;
    text-align: center;

}

.resume-link {
  text-align: center;
  margin-top: 20px;
  text-shadow: 2px 2px 5px red;
}

.resume-link a {
  display: inline-block;
  padding: 10px 20px;
  background-color: #333;
  color: #FFF;
  text-decoration: none;
  border-radius: 4px;
}

.resume-link a:hover {
  background-color: #555;
}
