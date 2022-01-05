# NikenBirthday
<html>
    <head>
        <meta charset="utf-8">
        <tittle>HAPPY BIRTHDAY</tittle>
        <link rel="stylesheet"href="project.css">
    </head>
    <div class="header">
        <body>
        <div class="main">
            <div class="copy-container">
            <h1>HAPPY BIRTHDAY NIKEN UTAMI!</h1>
            <h1>20+ Years old</h1>
            <p>Hopefully you will be the best of your version</p>
            <p>And your dreams come true</p>
            <p>Don't forget to pray and believe in yourself. Just go for it</p>
            <p>From your old buddy, Nalda</p> 
            <div class="contents-item">
                <img src="https://image.freepik.com/free-vector/happy-birthday-background_1344-43.jpg">
            </div>
        </div>
        <footer>
                <h2>See you on top</h2>
        </footer>
      </div>
    </body>
</html>
  
html, body,
ul, ol, li,
h1, h2, h3, h4, h5, h6, p,
form, input, div 

body {
  font-family: "Avenir Next";
}

li {
  list-style: none;
  float: right;
  padding: 33px 50px;
  color: hsl(240, 33%, 88%);
  text-align: right;
}

.tittle {
  background-color: black;
  font: white;
}

.header {
  background-color : rgb(24, 22, 21);
  max-height: 10000;
}

.main {
  padding: 200px 40px;
  text-align: center;
  color: hsl(240, 24%, 93%);
}

.copy-container h1 {
  font-size: 40px;
  text-align: center;
}

.copy-container p {
  font-size: 20px;
  text-align: center;
}

.footer {
  background-color: rgb(8, 8, 8);
  height: 50px;
  padding-bottom: 20px;
}

.footer-list li {
  padding-top: 30px;
  list-style: none;
  text-align: center;
  color:black;
}
  
@media all and (max-width: 1000px) {
    
      /* Tambahkan CSS untuk tag <h1> didalam top-wrapper */
      .main h1 {
        font-size: 32px;
      }
    
      /* Tambahkan CSS untuk tag <h2> didalam heading */
      .contents h2 {
        font-size: 20px;
      }
    
      
    }
    /* Untuk Smartphone */
   @media all and (max-width: 670px) {
   
    
    footer {
      text-align: center;
    }
    
    .main {
      text-align: center;
    }
    
    /* Tambahkan CSS untuk header-right */
    .header-list{
      display:none;
    }
    .menu-icon{
      display:block;
    }
    /* Tambahkan CSS untuk menu-icon */
    
    
    .main h1 {
      font-size: 24px;
      line-height: 36px;
    }
    
    .main p {
      font-size: 14px;
      line-height: 20px;
    }
  }
