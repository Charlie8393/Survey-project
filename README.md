- 👋 Hi, I’m @Charlie8393
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Survey Form</title>
    <link href="index.css" rel="stylesheet">
</head>
<body>
    <div class="introduction">
        <h1 style="text-align: center;">Survey Form</h1>
        <h4 style="text-align: center;">This is a thing to know about this class and school. So take it seriously</h4>
    </div>

    <div class="body">
        <body style="background-color: blue;"></body>
        <h1><lable for="Name">Name</lable></h1>
        <input id="Name" type="text-field" name="Name">
        <h1><lable for="password">Email</lable></h1>
        <input id="Email" type="Email" name="Email">
        <h1><lable for="Age">Age</lable></h1>
        <input id="Age" type="number" name="Age" step="2">
        <h1><lable for="volume">Current role</lable></h1>
        <input type="text" list="Current role" id="role">
        <datalist id="Current role">
            <option value="Teacher"></option>
            <option value="Student"></option>
        </datalist>
    <div>
        <h1>About Web Development class:</h1>
        <div>
        <input id="Good" name="class" type="radio" value="Good">
        <label for="Good">Good</label>
        </div>

        <div>
        <input id="Bad" name="class" type="radio" value="Bad">
        <label for="Bad">Bad</label>
        </div>
        
        <div>
        <input id="So-So" name="class" type="radio" value="So-So">
        <label for="So-So">So-So</label>
        </div>
    </div>
        
    <div>
        <h1>What is the things you want to improve from coding? (Check all that apply)</h1>
        <div>
        <input id="video" name="improve" type="checkbox" value="video">
        <label for="video">Making video.</label>
        </div>
        <div>
        <input id="web-page" name="improve" type="checkbox" value="web-page">
        <label for="web-page">Making a web-page.</label>
        </div>
        <div>
        <input id="challenges" name="improve" type="checkbox" value="challenges">
        <label for="challenges">Better at challenges.</label>
        </div>
        <div>
        <input id="Game" name="improve" type="checkbox" value="Game">
        <label for="Game">Making Game.</label>
        </div>
        <div>
        <input id="community" name="improve" type="checkbox" value="community">
        <label for="community">Open source community.</label>
        </div>
    </div>
    
    <div>
        <label for="comments"><h3>Post Comments</h3></label>
        <textarea id="comments" name="comments" rows="3" cols="50">
            
        </textarea>
    </div>

    
    </div>
</body>
</html>
