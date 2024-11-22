/* Reset Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

  html {
    font-size:20px;
  }
  
  body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background: #f4f4f4;
    color: #333;
  }
  
  header {
    text-align: center;
    padding: 20px;
    background: #6c5ce7;
    color: white;
  }
  
  h1 {
    margin-bottom: 10px;
  }
  
  main {
    padding: 20px;
  }
  
  /* Sections */
  .section {
    margin-bottom: 40px;
  }
  
  h2 {
    color: #2d3436;
  }
  
  /* Flexbox Container */
  .flex-container {
    
    border: 2px dashed #ccc;
    padding: 10px;
    margin: 20px 0;
  
  }
  
  /* Flexbox Items */
  .box {
    background: #74b9ff;
    color: white;
    padding: 20px;
    margin: 5px;
    border-radius: 5px;
    text-align: center;
  }
  
  /* Section Specific Styles */
  .display-flex .flex-container {
    /* Students can experiment here */
    
  }
  
  .flex-direction .flex-container {
   }
  
  .justify-content .flex-container {
   }
  
  .align-items .flex-container {
   }
  
  .flex-wrap .flex-container {
   }
  
  /* CSS Units Section */
  .unit-container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 10px;
    margin-top: 20px;
  }
  
  .unit-box {
    padding: 20px;
    color: white;
    border-radius: 5px;
    text-align: center;
  }
  
  .vh-box {
    background-color: #55efc4;
  
  }
  
  .vw-box {
    background-color: #fab1a0;
  
  }
  
  .percent-box {
    background-color: #ffeaa7;
   
  }
  
  .em-box {
    background-color: #81ecec;
   
  }
  
  .rem-box {
    background-color: #74b9ff;
    
  }
  
  .px-box {
    background-color: #d63031;
    
  }
  
</head>
<body>

    <div id="header">
        <h1>Hariksh Mahendra Suryawanshi</h1>
        <p>B.Tech in Computer Science</p>
        <p>Newton School of Technology</p>
    </div>

    <div id="intro">
        <h2>About Me</h2>
        <img src="hariksh.jpeg" width="150px" height="150px"  alt="Hariksh Suryawanshi" class="profile-img">
        <p>I’m Hariksh, a passionate computer science student pursuing a B.Tech at Newton School of Technology. I enjoy solving coding problems and learning new technologies to improve my skills.</p>
    </div>

    <div id="hobbies">
        <h2>Hobbies</h2>
        <p>When I’m not coding, I love watching cricket, listening to music, and tackling coding challenges. These keep me motivated and help me unwind after a busy day.</p>
    </div>

    <div id="contact">
        <h2>Contact</h2>
        <p>If you want to connect with me, feel free to reach out on LinkedIn</p>
    </div>

    <div id="footer">
        <p> Hariksh Mahendra Suryawanshi</p>
    </div>

</body>
</html>
