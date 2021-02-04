<template>
<body>
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary sticky-top">
  <a class="navbar-brand" href="#">LOGO</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>

  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav mr-auto">
      <li class="nav-item active">
        <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Services</a>
      </li>
      <li class="nav-item">
        <a class="nav-link " href="#">Careers</a>
      </li>
      <li class="nav-item">
        <a class="nav-link " href="#">FAQ</a>
      </li>
    </ul>
    
  </div>
</nav>
  <div >
  <b-jumbotron id="head" align="center"   text-variant="info" >
    <h1>KuchToh Technologies Pvt. Ltd.</h1><br>
     <p>
      KuchToh Technologies Pvt. Ltd. is an upcoming Startup into Healthcare sector.<br>
      We welcome you to join & be part of the change, along with exciting work ranging from planning to final shaping of the product.
    </p>
  </b-jumbotron>
</div>
<div class="row">
       <b-card
       id="card"
       align="left"  
        
       text-variant="info" 
      >
         <h4>JOB ID: D002<br>
             JOB TYPE: Full time Software Developer<br>
             LOCATION: Bengaluru
         </h4>
        <b-card-text>Looking for enthusiastic software developer, willing to work in a startup setup with work ranging from software maintenance to client interactions.<br>

Required skills: Node.js, Express.js, Vue/Nuxt, Postgresql,<br>
 Progressive Web App, with a minimum of 2 years of relevant experience.<br>

Preferred skills: Google location APIs, location/route based search optimization,<br>
web application security, payment gateway API, notification APIs, cloud hosting.<br>

Salary: 3L to 3.5L per year

To apply, mail your resume to: kuchtohtechnologies@gmail.com.</b-card-text>
      </b-card>
      <b-card
      id="card"
       align="left"  
         
       text-variant="info" 
      >
         <h4>Job ID: D001<br>
             Job type: Full time Senior Software Developer<br>
             Location: Bengaluru
         </h4>
        <b-card-text>Looking for an enthusiastic, full stack developer, willing to work in a startup setup.<br>

Required skills: Node.js, Express.js, Vue/Nuxt, Postgresql,<br>
 Progressive Web App, with a minimum of 2 years of relevant experience.<br>

Preferred skills: Google location APIs, location/route based search optimization,<br>
web application security, payment gateway API, notification APIs, cloud hosting.<br>

Salary: 3L to 3.5L per year

To apply, mail your resume to: kuchtohtechnologies@gmail.com.</b-card-text>
      </b-card>

       <b-card
      id="card"
       align="left"  
         
       text-variant="info" 
      >
         <h4>Job ID: D001<br>
             Job type: Full time Senior Software Developer<br>
             Location: Bengaluru
         </h4>
        <b-card-text>Looking for an enthusiastic, full stack developer, willing to work in a startup setup.<br>

Required skills: Node.js, Express.js, Vue/Nuxt, Postgresql,<br>
 Progressive Web App, with a minimum of 2 years of relevant experience.<br>

Preferred skills: Google location APIs, location/route based search optimization,<br>
web application security, payment gateway API, notification APIs, cloud hosting.<br>

Salary: 3L to 3.5L per year

To apply, mail your resume to: kuchtohtechnologies@gmail.com.</b-card-text>
      </b-card>
    </div>
    </body>
</template>
<style scoped>
h1 {
  font-family: Arial, sans-serif;
  font-size: 80px;
  color:rgb(253, 238, 209) ;

}
h4{
  font-weight: bold;
  font-family: URW Chancery L, cursive;
   background: #2280F7;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
p{
  font-weight: bold;
  color: rgb(253, 238, 209);
  font-family: Optima, sans-serif;
}
div{
  display: flexbox;
  align-content: center;
  justify-content: center;
  opacity: 0.8;
}
body{
 background-color: black;
 
}
#card{
  border: 7px solid rgb(253, 238, 209);
  
  width: 370px;
  padding: 20px;
  margin: 30px;
  background-color:#181616;
  
}
#head{
 background-color: black;
 
  
}

</style>