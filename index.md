
<html>
<style>
/*
COLOR PALETTE
https://coolors.co/f7fff7-343434-2f3061-ffe66d-a1c6d7
#F7FFF7 - almost white
#343434 - dark gray - almost black
#2F3061 - blue dark
#FFE66D - yellow
#A1C6D7 - blue light
*/


/* Global styles
------------------------------------*/
html {
  box-sizing: border-box;
}
*, *:before, *:after {
  box-sizing: inherit;
}

body {
  color: #343434;
  margin: 0;
  padding: 0;
  font-family: 'Montserrat', sans-serif;
  font-size: 15px;
  line-height: 1.5;
}
img {
  width: 300px;
}
a {
  color: #FFE66D;
}
a:hover {
  text-decoration: none;
}
h1, h2 {
  font-family: 'Caveat', cursive;
  font-weight: 400;
  margin: 0;
}
h1 {
  font-size: 100px;
  line-height: 1;
}
h2 {
  font-size: 45px;
}

.content-wrap {
  max-width: 800px;
  width: 85%;
  margin: 0 auto;
  padding: 60px 0;
}
.item-details h3 {
  margin-bottom: 0;
}
.item-details h3 + p {
  font-style: italic;
}
.item-details h3 ~ p {
  margin: 0;
}
.divider > section {
  overflow: hidden;
  border-bottom: 1px dashed #343434;
  padding: 25px 0;
}
.divider > section:last-of-type {
  border: none;
}


/* Profile
------------------------------------*/
header {
  background: #2F3061;
  color: #F7FFF7;
}


/* Projects
------------------------------------*/
.projects {
  background: #F7FFF7;
}
.projects a {
  color: #2F3061;
}
.projects .btn {
  background: #2F3061;
  color: #F7FFF7;
  text-decoration: none;
  padding: 8px;
  border-radius: 4px;
  display: inline-block;
}
.projects .btn:hover {
  background: rgba(47,48,97,80%);
}
.project-item h3 {
  margin-top: 0;
}



/* Work Experience
------------------------------------*/
.work-experience {
  background: #A1C6D7;
}



/* Education
------------------------------------*/
.education {
  background-image: url(../images/joanna-kosinska-unsplash.jpg);
  background-position: top right;
  background-size: cover;
  padding-bottom: 100px;
}
.education p {
  width: 60%;
}


/* Contact Info
------------------------------------*/
footer {
  background: #343434;
  color: #F7FFF7;
}
.contact-list {
  list-style-type: none;
  padding: 0;
}
.contact-list a {
  padding: 5px;
  display: inline-block;
}


/* Responsive
------------------------------------*/
@media screen and (min-width: 750px) {

  header, footer {
    text-align: center;
  }

  .project-item img {
    float: left;
    margin-right: 20px;
  }

  .job-item {
    display: grid;
    grid-template-columns: 1fr 2fr;
    column-gap: 20px;
  }

  .contact-list {
    display: flex;
    justify-content: center;
  }
  .contact-list a {
    padding: 15px;
  }
}

@media screen and (max-width: 749px) {
  h1 {
    font-size: 75px;
    line-height: 0.9;
    margin-bottom: 20px;
  }
  h2 {
    line-height: 1;
  }
}
</style>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Polina Zhukovskaya Clements, Student at Queens College + Music Theory Tutor</title>
     <link href="https://fonts.googleapis.com/css?family=Caveat|Montserrat:400,600&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="css/styles.css">
  </head>
  <body>
    <main>
      <!-- ***********************  ABOUT / PROFILE  *********************** -->
      <header>
           <div>
          <h1>Polina Zhukovskaya Clements</h1>
          <h2>Student at Queens College City University of New York + Music Theory Tutor</h2>

          <p>As a student, I am interested in system modeling and computer science applications. As a tutor, I focus on interesting problems, and delivering results.</p>
						 <p>I’m also exploring more creative pursuits designing projects with real life applications.</p>
        </div>
      </header>

     <!-- ********************  PROJECTS / PORTFOLIO  ********************* -->
          <div>
           
          <h2>Featured Projects</h2>
          <!-- Project 2 -->
          <section class="project-item">
						   <span style="font-weight:700;color:rgb(253, 253, 253)">AirEx</span>
    
   

            <h3>Ship What You Can't Ship</h3>
            <p>Worked with the team of students on the system that allows to ship additional items to the destination. Focused on database design and documentation.</p>
            <a class="btn" href ="https://airexp.herokuapp.com/" target="_blank">View live site</a>
<a class="btn" href ="https://github.com/smilank3/airport_ship" target="_blank">GitHub</a>
          </section>

          <!-- Project 3 -->
          <section class="project-item">			
            <h3>Animal Placement System</h3>
            <p>Designed logical structure of database for storing, manipualting, and oraganizing user data. Developed quieries for fetching data based on given parameters.
						<p>	<a class="btn" href ="https://drive.google.com/drive/folders/13jsx_8TfxIL3SIxo4SKfor7kO-x2e4n-" target="_blank">Google Docs</a></p>
						</p>
          </section>
        </div>
  

      <!-- ***********************  WORK EXPERIENCE  *********************** -->
          <div>
          <h2>Work Experience</h2>

          <!-- Job 1 -->
    
              <h3> Research Foundation</h3>
              <p>Student Aid, CUNY</p>
              <p>December 2019 -January 2020</p>
            </div>
            <div>
              <p>Designed and maintained a database of student internships available in Summer 2020. Performed clerical and administrative work related to arrangement of final exams. Answered phone calls and under supervision resolved issues in CUNY EDGE program participating students. 
            </div>
          </section>
          <!-- Job 1 -->
            <div>
              <h3> Central Staff Services</h3>
              <p>Music Theory Tutor</p>
              <p>June 2019 - August 2019</p>
            </div>
            <div>
              <p>Customized tutoring and instructional approaches to meet the needs of diverse client populations. Tutored in Music Theory subject areas and guided students in test taking strategies, prioritising, and studying for the exams. Elevated student performance by at least one letter grade. 
            </div>
          </section>
      <!-- ******************  EDUCATION & CERTIFICATIONS ****************** -->
        <div>
          <h2>Education</h2>

          <section>
            <h3>Queens College City University of New York - New York, NY</h3>
            <p>Corporate Finance, 2021</p>
          </section>

          <section>
            <h3>Queens College City University of New York- New York, NY</h3>
            <p>Computer Science, 2021</p>
          </section>

          <section>
            <h3>NYCT City University of New York - New York, NY</h3>
            <p>Applied Mathematics, 2015</p>
          </section>
        </div>
      </section>
      <!-- *****************  CONTACT INFO / SOCIAL MEDIA  ***************** -->
      <footer>
        <div>
           <h2>Let's Keep in Touch!</h2>

          <!-- Social media and contact links. Add or remove any networks. -->
          <ul class="contact-list">
            <li>pollycle@yahoo.com |</li>
            <li>| (646) 246 - 3097</li>
          </ul>
        </div>
      </footer>
    </main>
  </body>
</html>

