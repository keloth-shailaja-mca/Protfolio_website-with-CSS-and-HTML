Your portfolio should have a welcome section with an id of welcome-section
The welcome section should have an h1 element that contains text
Your portfolio should have a projects section with an id of projects
The projects section should contain at least one element with a class of project-tile to hold a project
The projects section should contain at least one link to a project
Your portfolio should have a navbar with an id of navbar
The navbar should contain at least one link that you can click on to navigate to different sections of the page
Your portfolio should have a link with an id of profile-link, which opens your GitHub or freeCodeCamp profile in a new tab
Your portfolio should have at least one media query
The height of the welcome section should be equal to the height of the viewport
The navbar should always be at the top of the viewport
Fulfill the user stories and pass all the tests below to complete this project. Give it your own personal style. Happy Coding!
Note: Be sure to add <link rel="stylesheet" href="styles.css"> in your HTML to link your stylesheet and apply your CSS
1. Your portfolio should have a "Welcome" section with an id of welcome-section.
Waiting:2. Your #welcome-section element should contain an h1 element.
Waiting:3. You should not have any empty h1 elements within #welcome-section element.
Waiting:4. You should have a "Projects" section with an id of projects.
Waiting:5. Your portfolio should contain at least one element with a class of project-tile.
Waiting:6. Your #projects element should contain at least one a element.
Waiting:7. Your portfolio should have a navbar with an id of navbar.
Waiting:8. Your #navbar element should contain at least one a element whose href attribute starts with #.
Waiting:9. Your portfolio should have an a element with an id of profile-link.
Waiting:10. Your #profile-link element should have a target attribute of _blank.
Waiting:11. Your portfolio should use at least one media query.
Waiting:12. Your #navbar element should always be at the top of the viewport.


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio website</title>
     <link href="protfolio.css" rel="stylesheet">
     <link
      rel="stylesheet"
      href="https://use.fontawesome.com/releases/v5.8.2/css/all.css"
integrity="sha384-oS3vJWv+0UjzBfQzYUhtDYW+Pj2yciDJxpsK1OYPAYjqT085Qq/1cq5FLXAZQ7Ay"
  crossorigin="anonymous" />
</head>
<body>
   <header id="about">
    <nav id="navbar" class="nav">
        <ul>
     <li><a href="#welcome-section">About</a></li>
     <li><a href="#projects">Work</a></li>
     <li><a href="#contact">Contact</a></li>
     </ul>
    </nav>
    <div id="welcome-section" class="container">
        <h1 id="title">Hey I am shailaja</h1>
        <p><em>a web developer</em></p>
    </div>
   </header>
  <section id="projects">
    <div class="project-tile" id="project-tile">
        <h2 id="h2">These are some of my projects</h2>
    </div>
    <div class="flex">
      <div>
      <img  id="box" src="TributePage.png" wigth="300px" height="200px">
      <p>TributePage</p>
      </div>

      <div >
        <img id="box" src="Bulding.png" wigth="300px" height="200px">
        <p>BuildingPages</p>
        </div>

        <div >
          <img id="box" src="Survey.png" wigth="300px" height="200px">
          <p>SurveyForm</p>
          </div>

          <div >
            <img id="box" src="LandingPage.png" wigth="300px" height="200px">
            <p>ProductLandingPage</p>
            </div>
    </div>


    <div class="flex">
      <div>
      <img  id="box" src="Portfolio.png" wigth="300px" height="200px">
      <p>Portfolio website</p>
      </div>

      <div >
        <img id="box" src="Bulding.png" wigth="300px" height="200px">
        <p>BuildingPages</p>
        </div>

        <div >
          <img id="box" src="Survey.png" wigth="300px" height="200px">
          <p>SurveyForm</p>
          </div>

          <div >
            <img id="box" src="LandingPage.png" wigth="300px" height="200px">
            <p>ProductLandingPage</p>
            </div>
    </div>
  </section>
   <section id="contact" class="contact-section">
    <div class="contact-section-h3">
      <h3 id="title">Let's work together...</h3>
      <p class="p">How do you take your coffee?</p>
    </div>
    <div class="contact-link">
      <a href="https://facebook.com/freecodecamp"
target="_blank"class="btn contact-details"><i class="fab fa-facebook-square"></i> Facebook</a>
<a id="profile-link"
href="https://github.com/freecodecamp"target="_blank"
          class="btn contact-details"><i class="fab fa-github"></i> GitHub</a>
<a href="https://twitter.com/freecodecamp"
target="_blank" class="btn contact-details"><i class="fab fa-twitter"></i> Twitter</a>
<a href="/cdn-cgi/l/email-protection#e7829f868a978b82a7829f868a978b82c984888a" class="btn contact-details"><i class="fas fa-at"></i> Send a mail</a>
<a href="tel:555-555-5555" class="btn contact-details"
          ><i class="fas fa-mobile-alt"></i> Call me</a> </div>
    </div>
   </section>
   <hr>
   <footer>
    <img  class="img" src="https://images.pexels.com/photos/733872/pexels-photo-733872.jpeg?auto=compress&cs=tinysrgb&w=600" width="250px" height="200px">
    <p id="my">This website designed by shailaja</p>
    <p>&copy; Created for students</p>
   </footer>
</body>
</html>




  *{
    margin: 0px;
    padding: 0px;
    box-sizing: content-box;
  }
  .nav{
    width: 100%;
    height: 100px;
    background-color: rgb(164, 86, 86);
    justify-content: right;
  }

#navbar{
    display: flex;
}
ul{
    display: flex;
    margin: 30px 10px;

}
li{
    list-style: none;
    margin: 10px;
}
a{
    text-decoration: none;
    font-family:sans-serif;
    font-size: 30px;
    text-align: center;
}
a:hover{
    color: azure;
}
h1{
    font-size: 40px;
}
#title{
    padding-top: 250px;

}
#title, p{
    text-align: center;
     font-family: Arial, Helvetica, sans-serif;
     color: azure;

}
.container{
    width: 98.7%;
    height: 80vh;
    background-color:black;
    padding: 10px;
}

.contact-section{
    width: 98.7%;
    height: 80vh;
    background-color: gray;
    padding: 10px;
}

.contact-link{
    padding-top: 40px;
    padding-left: 350px;
}
a{
    margin: 10px;
}



#h2{
 text-align: center;
 font-family: Arial, Helvetica, sans-serif;
     color: azure;
     font-size: 30px;
     text-decoration: underline;
     
}

#projects{
    width: 98.7%;
    height: 100vh;
    background-color: rgb(71, 71, 145);
    padding: 10px;
}


.DD{
    width: 300px;
    height: 300px;
    display: flex;
  
}


@media screen  and (max-width: 600px){
    
    .nav{
        width: 100%;
        height: 40vh;
      }
      
      
}

.flex{
    display: flex;
    flex-direction: row;
    margin: 30px;
}

#box{
    width: 300px;
    height: 220px;
    background-color: gray;
    padding: 10px;
    
}
#Abox{
    width: 350px;
    height: 300px;
    background-color: gray;
    padding: 10px;
    
}

img{
    margin-left: 20px;
}

#title{
    font-size: 4rem;
}
.p{
    font-style: italic;
}

hr{
    border: 3px solid red;;
}
footer{
    width: 98.7%;
    height: 40vh;
    background-color: gray;
    padding: 10px;

}

.img {
    width: 200px;
    height: 200px;
    border-radius: 350px;
    background-color: azure;
    margin-left: 600px;
}
#my{
    font-style: oblique;
    font-size: 30px;
}
