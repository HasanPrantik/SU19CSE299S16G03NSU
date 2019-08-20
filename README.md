<p align="center">
  <img width="250" height="280" src="images/nsulogo.png">
</p>                                        









  <h1 align="center">Project Name: Populace</h1>
  <h2 align ="center">Course Number: CSE 299<br>
  Section:16</br>
  Semester: Summer 2019</br><br>
  Faculty Name: Shaikh Shawon Arefin Shimon</h2>
  <h3 align="center">Student Name: Sayeed Md. Shaiban<br>
  Student ID: 1621193042<br>
  Email: sayeed.shaiban@northsouth.edu <br><br>
  Student Name: Monisha Saha<br>
  Student ID: 1631667042<br>
  Email: monisha.saha@northsouth.edu <br><br>
  Date prepared: 11/06/2019</h3><br><br>










<h2> Project Name: Populace </h2><br><br>
<h3 id="table-of-contents">Table of contents</h3>

<ol>
<a href="#projectidea"><li>Project Idea</li><br></a>
<a href="#features"><li>Software Specification</li><br></a>
<a href="#technology"><li>Technology</li><br></a>
<a href="#businessplan"><li>BusinessPlan/Monetization</li></a>
</ol><br><br><br>
 <!-- <p align="left">
  <img width="900" height="400" src="images/populace.png"><br>
</p>  -->
<h2 id="#projectidea">1. Project Idea</h2>
<p>At present times we have various web based tools like google-classroom and piazza to manage resource with a large group of people. These are specially used by educational institutions (e.g. school, college, university) and other organization to communicate with a large number of people, to create workflow etc. But often using different sites simultaneously causes a lot of clutter and becomes cumbersome to keep track of. Hence we offer ‘Populace’ which is a web based application. The reason it stands out from the rest is because it will combine all this separate existing platform into one single platform. By signing in to ‘Populace’ users will be able to see posts made on the other existing web applications and also make their own query. It will therefore be a gathering place especially for students and for people who wants a one-stop solution to keep track of all the accounts in different web platform. Thus creating a better workflow.
Primarily, the two platforms that we will include are ‘Google Classroom’ and ‘Piazza’. In the future we also plan to add other platforms similar to the above mentioned names.</p>

<h2 id="features">2. Software Specification</h2>
This project has the following features -
<h3>2.1 User Registration:</h3>
  To access any platform (e.g.piazza,google classroom) users first have to register. Users must include username, firstname, lastname,email and password. The username will be used as a primary key to identify unique users. And so username will have to be unique. And it must contain 150 characters or fewer characters. Letters, digits and @/./+/-/_ are permitted only.
   <br>
   <br>
   <p align="center">
   <img width="700" height="450" src="images/registration.png">
   Figure 1.0
  </p>
 <h3>2.2 Login to a specific platform :</h3>
  The main feature of ‘Populace’ is that users will be able to view different platforms on one window after logging in once. This section is know as the profile. The users information is shown on the left as seen in figure 2.0.<br>
  <br>


  <p align="center">
  <img width="700" height="400" src="images/piazza.png"><br>
  Figure 2.0
</p>
<br>
<br>
  <p>Currently the following functions are available -
  <p>
    * Users can see all their subject/course in the specific platform.<br>
    * Users can add or delete their subject/courses. To easy view which platform contains what subject<br>
    * Users will also be able to see posts of the specific subject/course sorted by subject and recent to old.</p> <br><br><br>

  <p align="center">
  <img width="750" height="450" src="images/piazzaPost.png"><br>
  figure 3.0
</p>  



 <h2 id="#technology">3. Technology</h2>
 <h5>3.2 Proposed Technology Stack: </h5>
 <p>For UI design we decided to use Bootstrap. Bootstrap is a free and open-source CSS framework directed at responsive front-end web development. It contains CSS and JavaScript-based design templates for typography, forms, buttons, navigation and other interface components. Bootstrap will be used over the usual HTML and CSS. And for the backend we will be using Express.js. It is a web application framework. It is a minimal and flexible Node.js web application framework that provides robust set of features.

 Finally, for the database requirement we have opted to use a NoSQL database. And so we have decided to use MongoDB for the projects database requirement.  The reason for doing so is because we have only three entities:

    * USER: Will keep info about the users signing in the application.<br>
    * PLATFORM: The platform information for the signed in USER entity.
    * COURSE_INFO: The name of the course/subject associated with the specific platform</p><br>

 <h5>3.2 Changed Technology Stack: </h5>
 <p>Due to npm api for piazza being old and unusable we have decided to switch our project from node.js to Django.For which our project specification has changed. Django is a high level python-based free and open-source web framework.

 For the database requirement we have opted to use a NoSQL database. And so we have decided to use MongoDB for the projects database requirement.</p> 





<p>To get the data from the other platforms we will be using the following APIs–

  * [Google Classroom Link](https://developers.google.com/classroom/quickstart/python)
  * [Piazza Link](https://pypi.org/project/piazza-api/) </p>



<h2 id="businessplan">4. BusinessPlan/Monetization</h2>
<p>
Google AdSense is the easiest way to monetize a website. It is designed for website developers to display photos, videos, texts on their website.  There are different types of ads available in Google AdSense. If our website is Google AdSense approved, Google will post ads on our website. Therefore, we can make money if someone clicks and views it. On the other hand, this can be used by universities, schools and colleges as a means for them to communicate with their students, so we can make these organizations use our website as their own personal site. It will help the students in their studies. Because they will find Google classroom and piazza in one platform. It will saves their time and keeps them organized. So we can also approach these educational institutions to adopt our site to their system.</p>
