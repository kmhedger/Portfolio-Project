# Portfolio-Project
<style>
  body {
  background-color: #e6f7ff;
  margin: 0;
font-family: "Georgia", serif;
}

#navbar {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  justify-items: center;
  background-color: #002333;
  margin: 0;
  font-size: 16px;
  opacity: 0.7;
  position: fixed;
  width: 100%;
}

ul a {
  text-decoration: none;
  color: #e6f7ff
}

ul a:hover {
  color: #e6f7ff;
  opacity: 0.5;
}

#Kaija  {
  width: 100%;
  height: 100vh;
  object-fit: cover;
  object-position: 0vh;
}

#About {
  display: grid;
  grid-template-column: 1fr;
  text-align: center;
  color: #002333;
  padding-left: 50px;
  font-size: 50px;
  padding-top: 50px;
  object-position: 0vh;
  object-fit: cover;
}

#para {
  display: grid;
  grid-template-columns: 1fr;
  padding-left: 100px;
  padding-right: 100px;
  font-size: 20px;
  text-align: center;
  color: #002333;
  padding-bottom: 150px;
}

#Portfolio {
  display: grid;
  grid-template-column: 50% 50%;
  grid-template-row: 50% 50%;
  justify-items: center;
  background-color: #002333;
  color:#e6f7ff;
  text-align: center;
  object-position: 0vh;
  object-fit: cover;
}

#Portfoliotitle {
  display: grid;
  grid-template-column: 1fr;
  text-align: center;
  color: #e6f7ff;
  padding-left: 50px;
  font-size: 50px;
  padding-top: 20px;
}

.flex-container {
  display: flex;
  flex-flow: wrap;
  justify-conent: center;
  justify-content: space-around;
}

.grid-item {
  padding-top: 30px;
  padding-bottom: 100px;
  padding-left: 20px;
  padding-right: 20px;
}

#tribute img {
  width: 100%;
  height: 79vh;
  width: 80vh;
  object-fit: cover;
  object-position: top;
  max-height: 250px;
  max-width: 250px;
}

.grid-item a{
  text-decoration: none;
  color: #e6f7ff; 
}

.grid-item a:hover {
  color: #e6f7ff; 
  opacity: 0.7;
}

#Contact {
  display: grid;
  grid-template-column: 1fr;
  text-align: center;
  color: #002333;
  padding-left: 50px;
  font-size: 50px;
  padding-top: 20px;
  object-position: 0vh;
  object-fit: cover;
}

#info {
  display: grid;
  grid-template-columns: 1fr;
  grid-template-rows: 1fr 1fr;
  justify-content: center;
  justify-content: space-around
}

#name {
  padding-bottom:
    10px;
}

#email {
  padding-bottom: 10px;
  padding-top: 20px;
}

#emailbox{ 
  margin-bottom: 10px; 
}

 input{
  width: 300px;
  height: 20px;
}

button {
  width: 50px;
}

#contactinfo {
  display: grid;
  grid-template-rows: 1fr;
  justify-content: center;
}

#social {
  display: flex;
  justify-content: center;
  padding-top: 30px;
  transform:scale(3);
}

#fb {
  padding-left: 20px;
  padding-right: 20px;
}

#fb a{
  text-decoration: none;
  color: #3b5998;
}

#link a{
  text-decoration: none;
  color: #0077B5;
}

#git a{
  text-decoration: none;
  color: #333;
}

footer {
  display: flex;
  color: #002333;
  justify-content: center;
  padding-top: 200px;
  padding-bottom: 20px;
}
  </style>

<link rel="stylesheet" href="//maxcdn.bootstrapcdn.com/font-awesome/4.5.0/css/font-awesome.min.css"/>  

<heading> 
    <nav class="navbar navbar-fixed-top" id="navbar">
    <ul><a href="#About">About</a></ul>
    <ul><a href="#Portfolio">Portfolio</a></ul>
    <ul><a href="#Contact">Contact</a></ul>
  </nav>
</heading>


<main>
  
  <section>
  <div class="container">
    <img id="Kaija" src="https://preview.ibb.co/n8B19o/Portfolio2.jpg">
        </div>
      </section>
  
  <section>
    <div class=container>
    <h1 id="About"> About Me </h1>
    <p id="para"> My name is Kaija. I am currently learning to code with the goal of becoming a web developer. Check out the work I have done so far. Feel free to contact me with comments and suggestions to better my learning.</p>
  </div>
    </section>
    
 <div id="Portfolio">
   <h1 id="Portfoliotitle"> Portfolio </h1> 
    
   <div class="flex-container">
 <div id="tribute" class="grid-item">  <img src="https://lh3.googleusercontent.com/A4IHbbW6-pKDVFZnl6NqF9y0BpA6lNQr9nZfrJexwPZpUgxeKOUgK1dL9k14SVNQKWvNBWwpAuR4tuMT8Zn4zBL-X4wGku2n-eFJIQrULGrk7L1S7_KX41Cjjbc23JShs1PDFmxZSiQFcr-2TRZAFgwp_PUtyHaB2apgpOC-6xNDTd7MSS5TiEhgVcURce4BbaXspqr5NnXYZbSV75uVZr22LItpLFa3DmnCdaJCLFHHeFbVGVdtszcL3zVt_aJPule7jv-5gxKxyfgwnh5lELS0DT3OQXQxM5lkJ_VC8NrEg69BOhphAYFygnL-Wesurqt6a_jUctY7-h2BS3fqcTGkTJkXiou-gy4EgmNvWyIy05NYJiFeffONpN6X2UJml1vRKCIhMMxQLfs1gUOqLtjQVRuKyKzJKd2xCE0zFxjGiGtks5kRUN5cHWkssqgPN1CEJC5tQDEqCNRztss98yUakmUY1wuCIrU1ajnFg31r6mzemWJKmTedIu1oQTmn0nyaQVvjTa2_q0fN8ArjjyS5kihp5s06SSY-Z_sNghozVTdrgQPU48VLUp-32U3fU6gZxZhtoh4rywNWd5n1FeBPElZkHJsP-CeOMQ=s670-no" alt="tribute page">
   <h4><a href="https://codepen.io/kaijamh/full/ERGjGW/">Tribute Page<a></h4> 
     </div>
    
    <div id="project2" class="grid-item">
      <img src="https://pbs.twimg.com/profile_images/638786550206230529/fwnBbDZF.png" alt = "google logo">
    <h4><a href="https://codepen.io/kaijamh/full/ERGjGW/">Project 2<a></h4>
    </div>
    
    <div id="project3" class="grid-item">
     <img src="https://pbs.twimg.com/profile_images/638786550206230529/fwnBbDZF.png" alt = "google logo"/>
    <h4><a href="https://codepen.io/kaijamh/full/ERGjGW/">Project 3<a></h4>
    </div>
    
    <div id="project4" class="grid-item">
        <img src="https://pbs.twimg.com/profile_images/638786550206230529/fwnBbDZF.png" alt = "google logo"/>
    <h4><a href="https://codepen.io/kaijamh/full/ERGjGW/">Project 4<a></h4>
    </div>
    
   </div>
  </div>
    
  <section>  
    <div>
  <div class=container>
    <h1 id="Contact"> Contact </h1
  </div>
      <div id="contactinfo">
      <div id="info">
      <label id="name"> Name </label>
        <input id="namebox" type="text" placeholder="Name" required>
      <label id="email"> Email </label>
        <input id="emailbox" type="text" placeholder="Email" required>
        <button> Submit </button>
      </div>
      
      <div id="social">
        <div id="git">
        <a href="https://github.com/jonthemod">
          <i class="fa fa-github-square"></i>
        </a>
        </div>
        
        <div id="fb">
        <a href="https://www.facebook.com/kaija.hed"> <i class="fa fa-facebook-square"></i>
        </a>
        </div>
        
        <div id="link">
        <a href="https://www.linkedin.com/in/kaija-hedger-b0743283/"> <i class="fa fa-linkedin-square"> </i>
        </a>
        </div>
        
      </div>
      </div>
      </div>
    </section>
    
      <footer> Designed and writtent by Kaija Hedger. </footer>
</main>
