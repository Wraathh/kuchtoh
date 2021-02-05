<template>
<body>
  

  <div>
  <b-jumbotron id="head" align="center"   text-variant="info" >
    <h1>KuchToh Technologies Pvt. Ltd.</h1><br>
    <div ><h4 id="hire">Coming Soon...</h4></div><br>
     <p>
      KuchToh Technologies Pvt. Ltd. is an upcoming Startup into Healthcare sector.<br>
      We welcome you to join & be part of the change, along with exciting work ranging from planning to final shaping of the product.
    </p>
  </b-jumbotron>
 
</div>
<div ><h4 id="hire">We are Hiring...</h4></div>
<div class="row">
       <b-card
       id="card"
       align="left"   
       text-variant="info" 
      >
         <h4>JOB ID: D001<br>
             JOB TYPE: Full time Senior Software Developer<br>
             LOCATION: Bengaluru
         </h4>
        <b-card-text>Looking for an enthusiastic, full stack developer, willing to work in a startup setup.<br><br>

          <b><u>REQUIRED SKILLS:</u></b> Node.js, Express.js, Vue/Nuxt, Postgresql,<br>
          Progressive Web App, with a minimum of 2 years of relevant experience.<br><br>

          <b><u>PREFERRED SKILLS:</u></b> Google location APIs, location/route based search optimization,<br>
          web application security, payment gateway API, notification APIs, cloud hosting.<br><br>

          <b><u>SALARY:</u></b> 3L to 3.5L per year<br><br>

          <b>To apply, mail your resume to: kuchtohtechnologies@gmail.com.</b></b-card-text>
      </b-card>
     
      <b-card
      id="card"
      align="left"   
      text-variant="info" 
      >
         <h4>JOB ID: I002<br>
             JOB TYPE: Intern(Marketing)<br>
             LOCATION: Bengaluru
         </h4>
        <b-card-text>Looking for enthusiastic <b>Marketing post-graduates/graduates,</b> 
          willing to work in a startup setup.<br><br>

          <b><u>REQUIREMENT:</u></b> MBA in Marketing and Sales<br><br>

          <b><u>PREFERRED SKILLS:</u></b> <br>1. Basic knowledge of Google Analytics, Mixpanel and Google AdWords.<br>
          2. Basic understanding of different marketing techniques (e.g Point-of-Purchase Marketing, Internet Marketing, Paid Media Advertising, etc).<br>
          3. Familiar with email marketing techniques.<br>
          4. Excellent researching abilities.
          <br><br>

          <b><u>Perks:</u></b><br>1. Experience Certificate<br>2. Letter of recommendation<br>3. Internship extendable to employement based on performance.<br><br>

         <b> To apply, mail your resume to: kuchtohtechnologies@gmail.com with the subject-line (Job ID/Start Date/Number of Months)</b></b-card-text>
      </b-card>
      <b-card
      id="card"
      align="left"   
      text-variant="info" 
      >
         <h4>JOB ID: I003<br>
             JOB TYPE: Intern(Law)<br>
             LOCATION: Bengaluru
         </h4>
        <b-card-text><b><u>QUALIFICATION AND SKILLS:</u></b><br>
        1. Graduated in Law<br>
        2. Excellent English (oral and written) is a must<br>
        3. Must have good MS Office skills, mainly MS Word, MS Excel or equivalent<br>
        <br>

          <b><u>RESPONSIBILITIES:</u></b><br>
          1. Legal Research - IP Law, Labour Law, Corporate Law, Employment Law, Medical related Legalities<br>
          2. Legal Drafting - Contracts, Policies, Medical policies, insurance, indemnity etc<br>
          3. Legal Writing and Content Creation - Articles, Reports, Interviews.<br>
          4. Business Development related work
          <br><br>

          <b><u>Perks:</u></b><br>1. Experience Certificate<br>2. Letter of recommendation<br>3. Flexible working hours with work from home.<br><br>

         <b> To apply, mail your resume to: kuchtohtechnologies@gmail.com with the subject-line (Job ID/Start Date/Number of Months)</b></b-card-text>
      </b-card>
    </div>
     <div id="div">
    <section>
      <article>
        <details>
          <summary><h4 id="hire">Are you a Doctor??    <span id="plus">&#9660;</span></h4></summary>
          <details>
            <summary id="sum"><h5 id="hire">Watch this area, we have more coming for you! </h5></summary>
            
          </details>
         </details>
      </article>
    </section>
  </div><br><br>
    <div class="footer">
  <p>KuchToh Technologies Pvt. Ltd &#169; 2021 </p>
</div>
    </body>
</template>
<style scoped>
#plus{
  color: #ffffff;
}
 summary::-webkit-details-marker {
display: none;
 
}
summary:focus {
	outline-style: none;
}
article > details > summary {
	font-size: 28px;
	margin-top: 16px;
}
details > p {
	margin-left: 24px;
}
details details {
	margin-left: 36px;
}
details details summary {
	font-size: 16px;
}

#hire{
  padding: 15px;
  color: #2280F7;
  text-align: center;
}
.footer {
   padding-bottom: 10px;
   left: 0;
   bottom: 0;
   width: 100%;
   height: 50px;
   color: white;
   text-align: center;
}
#sum
{
  height: 50px;;
}
h1 {
  font-family: Arial, sans-serif;
  font-size: 60px;
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