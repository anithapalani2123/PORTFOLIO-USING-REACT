# PORTFOLIO-USING-REACT
# portfolio.js
```
import React from 'react';
import './App.css';
import what from './whatsapp.png';
import git from './git.png';
import link from './linkedin.png';
import side from './crt.png';


function Portfolio() {
  return (
    <div>
      <nav className="navbar">
        <ul>
          <li><a href="#home">HOME</a></li>
          <li><a href="#about">ABOUT ME</a></li>
          <li><a href="#education">EDUCATION</a></li>
          <li><a href="#portfolio">PORTFOLIO</a></li>
          <li><a href="#contact">CONTACT ME</a></li>
        </ul>
      </nav>
      <section id="home">
        
      </section>
      <section className="sec">
        <div className="gal">
          <img src={side} alt="" />
        </div>
        <p className="box">
          I am anitha p studying in saveetha engineering college in the department aiml 2nd year.
          I did my schooling in bharathi matriculation higher secondary school. I scored 90% in my 10th and 12th grade.
          I am anitha p studying in saveetha engineering college in the department aiml 2nd year.
          I did my schooling in bharathi matriculation higher secondary school. I scored 90% in my 10th and 12th grade.
          <br /><br />
          I am anitha p studying in saveetha engineering college in the department aiml 2nd year.
          I am anitha p studying in saveetha engineering college in the department aiml 2nd year.
          I did my schooling in bharathi matriculation higher secondary school. I scored 90% in my 10th and 12th grade.
          I am anitha p studying in saveetha engineering college in the department aiml 2nd year.
          I did my schooling in bharathi matriculation higher secondary school. I scored 90% in my 10th and 12th grade.
        </p>
      </section>
      <section className="sec1">
        <div className="expect">
          <p className="font"><u>EXPERTISE:</u></p>
          <br />
          <ul>
            <li>Product Development (FUSION360)</li><br />
            <li>AR filters (INSTAGRAM / SNAPCHAT)</li><br />
            <li>Web Designer</li><br />
            <li>Modelling</li><br />
            <li>Communication SkillS</li><br />
          </ul>
        </div>
        <div className="lang">
          <p className="font"><u>PROGRAMMING LANGUAGES:</u></p>
          <br />
          <ul>
            <li>PYTHON</li><br />
            <li>C</li><br />
            <li>JAVA</li><br />
            <li>JAVA SCRIPT</li><br />
            <li>HTML & CSS</li><br />
          </ul>
        </div>
        <div className="edu">
          <p className="font"><u>EDUCATION:</u></p>
          <br />
          <ul>
            <li>2019 - 10TH GRADE in Bharathi Vidhya Mandhir</li><br />
            <li>2021 - 12TH GRADE in Bharathi Matriculation higher Secondary School</li><br />
            <li>2025 - B.Tech AIML in Saveetha Engineering College</li><br />
          </ul>
        </div>
      </section>
      <section className="thirdbox">
        <p className="font" style={{ fontSize: '30px' }}><b>Contact me:</b></p><br />
        <div>
          <a href="https://github.com/anithapalani2123"><img src={git} className="git" alt="Photo" width="100" height="100" /></a>
        </div>
        <div className="what">
          <a href="https://wa.me/7305444188"><img src={what} alt="Photo" width="120" height="120" /></a>
        </div>
        <div className="link">
          <a href="https://www.linkedin.com/in/anitha-palani-b79a3a22a/"><img src={link} alt="Photo" width="120" height="120" /></a>
        </div>
      </section>
      <div className="footer">
        <p>copyright &#169;Developed by  ANITHA PALANI</p>
      </div>
    </div>
  );
}

export default Portfolio;


```
# App.css:
```
*
{
    margin: 0;
    padding: 0;
}
html{
    scroll-behavior: smooth;
}

#home{
    display: flex;
    flex-direction: column;
    height: 1000px;
    justify-content: center;
    align-items: center;
    /* background-color: rgba(23, 8, 8, 0.5);
    color: rgb(27, 14, 14); */
    font-size: 25px;
}
#home::before{
    content: "";
    position: absolute;
    top: 0;
    left: 0;
    background: url('PIC.png') no-repeat center center/cover;
    height: 1000px;
    width: 100%;
    z-index: -1;
    /* opacity: 0.5; */
    overflow: hidden;
}
.heading{
    color: rgb(252, 249, 249);
    
    font-family: 'Didact Gothic';font-size: 22px;
    text-align: center;
    transform: scale(1,1.3);
    padding-top: 10px;
    letter-spacing: .2em;

}
.para
{
    color: rgb(204, 177, 177);
    font-style: italic;
    font-size: large;
}
.sec{
    height: 700px;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    font-size: medium;
    color: #011311;
    background-color:  #310d0470;
    padding: 50px;
    
}

.navbar{
    display : flex;
    justify-content: center;
    height: 50px;
    
    align-items: center;
    /* position: sticky; */
    top: 0;
}
.navbar::before{
    content: "";
    position: absolute;
    background-color: #310d0470;
    height: 100%;
    width: 100%;
    z-index: -1;
}
.navbar ul{
    display : flex;
    list-style: none;
}
.navbar ul li{
    font-size: 1.1rem;
}
.navbar ul li a{
    padding: 5px 20px;
    text-decoration: none;
    color: rgb(255, 255, 255);
}
.navbar ul li a:hover{
    border-bottom: 2px solid yellow;

}
.s2
{
    display:flex;
    flex-direction: column;
    height: 1000px;
}
.box
{
    display: block;
    /* top: 0%; */
    height: 450px;
    width: 800px;
    color: blanchedalmond;
    background-color: #010811;
    margin-left: 500px;
    margin-top: -500px;
    border-radius: 30px;
    font-family: 'Alegreya';
    font-size: 22px;
    word-spacing: 9px;
    letter-spacing: 0.45px;
    padding: 15px;
    
    
}
/* .box1::before{
    content: "";
    position: absolute;
    top: 0;
    left: 0;
} */
.box1
{
    display: block;
    top: 50%;
    height: 500px;
    width: 300px;
    color: blanchedalmond;
    background-color: #e3cfcbe2;
    margin-left: 100px;
    margin-top: 130px;
    border-radius: 20px;
    z-index: -1;
    opacity: .8;
}

.h1{
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    color: #ffffff;
}
.gal img{
    
    width: 335px;
    height: 500px;
    /* padding: 10px; */
    margin-left: 100px;
    margin-top: 90px;
    /* opacity: .6; */
    border-radius: 20px;

}
.sec1
{
    height: 550px;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    font-size: medium;
    color: rgba(229, 235, 238, 0.952) ;
    background-color: #b6bdc5;
    padding: 50px;
}
.expect
{
    height:250px;
    width: 250px;
    background-color: rgba(0, 1, 2, 0.982);
    margin-left: 120px;
    margin-top: 100px;
    padding: 50px;
    word-spacing: 5px;
    letter-spacing: 2px;
    border-radius: 60px;
    opacity: .9;
}
.lang
{
    height:250px;
    width: 250px;
    background-color: rgba(0, 1, 2, 0.982);
    margin-left: 600px;
    margin-top: -350px;
    padding: 50px;
    word-spacing: 5px;
    letter-spacing: 2px;
    border-radius: 60px;
    opacity: .9;
}
.edu
{
    height:250px;
    width: 250px;
    background-color: rgba(0, 1, 2, 0.982);
    margin-left: 1100px;
    margin-top: -350px;
    padding: 50px;
    word-spacing: 5px;
    letter-spacing: 2px;
    border-radius: 60px;
    opacity: .9;

}
.font
{
    font-family: 'Aclonica';
    font-size: 22px;
    color: antiquewhite;
}
.thirdbox
{
    height: 200px;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    font-size: medium;
    color: rgba(229, 235, 238, 0.952) ;
    background-color:  #681e0d79;
    padding: 50px;
}
.footer {
    text-align: center;
    padding: 3px;
    background-color: #010811;
    color: white;
  }
.git
{
    margin-left: 500px;
    margin-top: -10px;
    
    
}
.what
{
    margin-left: 300px;
    margin-top: -120px;
}
.link
{
    margin-left: 100px;
    margin-top: -120px;
}
```
# App.js:
```
import React from 'react';
import Portfolio from './Portfolio';

function App() {
  return (
    <div className="App">
      <Portfolio />
    </div>
  );
}

export default App;



```

# OUTPUT:


![p1](https://github.com/anithapalani2123/PORTFOLIO-USING-REACT/assets/94184990/c801643c-12b6-4434-87ae-5dec2ef949d3)
![p5](https://github.com/anithapalani2123/PORTFOLIO-USING-REACT/assets/94184990/83165955-4af7-49d6-bed5-89db4392f791)

![p3](https://github.com/anithapalani2123/PORTFOLIO-USING-REACT/assets/94184990/34e988f2-86bb-405b-ba50-4f40f9051d83)

![p4](https://github.com/anithapalani2123/PORTFOLIO-USING-REACT/assets/94184990/db5eea08-f62c-4929-86ef-9d5d2eafe6ac)


























