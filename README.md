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
  
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flexie's Adventure in CSS Land</title>
    <link rel="stylesheet" href="boil.css">
</head>
<body>
    <header>
        <h1>Welcome to Flexie's Adventure</h1>
        <p>Follow along and help Flexie master Flexbox and CSS units!</p>
    </header>

    <main>
        <!-- Section 1: Display Flex -->
        <section class="section display-flex">
            <h2>1. Entering the Land of Flexbox</h2>
            <div class="flex-container">
                <div class="box">Box 1</div>
                <div class="box">Box 2</div>
                <div class="box">Box 3</div>
            </div>
        </section>

        <!-- Section 2: Flex Direction -->
        <section class="section flex-direction">
            <h2>2. Choosing Directions</h2>
            <div class="flex-container">
                <div class="box">Direction 1</div>
                <div class="box">Direction 2</div>
                <div class="box">Direction 3</div>
            </div>
        </section>

        <!-- Section 3: Justify Content -->
        <section class="section justify-content">
            <h2>3. The Six Paths of Justification</h2>
            <div class="flex-container">
                <div class="box">Path 1</div>
                <div class="box">Path 2</div>
                <div class="box">Path 3</div>
            </div>
        </section>

        <!-- Section 4: Align Items -->
        <section class="section align-items">
            <h2>4. Aligning in Style</h2>
            <div class="flex-container">
                <div class="box">Align 1</div>
                <div class="box">Align 2</div>
                <div class="box">Align 3</div>
            </div>
        </section>

        <!-- Section 5: Flex Wrap -->
        <section class="section flex-wrap">
            <h2>5. The Flex-Wrap Festival</h2>
            <div class="flex-container">
                <div class="box">Wrap 1</div>
                <div class="box">Wrap 2</div>
                <div class="box">Wrap 3</div>
                <div class="box">Wrap 4</div>
                <div class="box">Wrap 5</div>
            </div>
        </section>

        <!-- Section 6: CSS Units -->
        <section class="section css-units">
            <h2>6. Exploring Unitopia</h2>
            <div class="unit-container">
                <div class="unit-box vh-box">VH</div>
                <div class="unit-box vw-box">VW</div>
                <div class="unit-box percent-box">%</div>
                <div class="unit-box em-box">EM</div>
                <div class="unit-box rem-box">REM</div>
                <div class="unit-box px-box">PX</div>
            </div>
        </section>
    </main>

    <footer>
        <p>Created with ❤️ by Your Name</p>
    </footer>
</body>
</html>
