<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Hachi+Maru+Pop&display=swap" rel="stylesheet">
    <link rel="stylesheet"type=text/css href="melike.css">
</head>
<body>
    <div class="container">
        <header class="text-center">
            <h1 id="title">SampleForm</h1>
            <p id="description"><em>thank you for taking the time</em></p>
        </header>
        <form action="#"id="survey-form">
            <div class="form-group">
<label for="name"id="name-label">Name</label>
<input type="text" name="" id="name" class="form-control"placeholder="Enter your name" required/>
            </div>



<div class="form-group">
    <p>How often do you provide food aid?</p>
    <p>
    <label>
<input type="radio" name="answer" id="definitely"value="Definitely" checked/>Weekly
    </label>
</p>

<p>
<label>
<input type="radio" name="answer" id="maybe" value="Maybe"/>Monthly
</label>
</p>
<p>
    <label>
    <input type="radio" name="answer" id="maybe" value="Maybe"/>Quarterly
    </label>
    </p>
<p>
    <label>
    <input type="radio" name="answer" id="notsure" value="Not Sure"/>Annually
    </label>
    </p>
</div>


 
 <div class="form-group">
     <button type="submit"id="submit">Submit</button>
 </div>
 <div class="form-group">
    <button type="back"id="back">Back</button>
</div>
        </form>
      </div>
</body>
</html>
