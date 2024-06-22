# foronlineexam
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Quiz Wuiz</title>
    <style>

body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
        background-color: #f5f5f5;
    }
    
    .login-container {
        background-color: #fff;
        padding: 20px;
        border-radius: 5px;
        box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
    }
    
    h2 {
        text-align: center;
        margin-bottom: 20px;
    }
    
    form {
        display: flex;
        flex-direction: column;
    }
    
    input[type="text"],
    input[type="password"] {
        margin-bottom: 10px;
        padding: 10px;
        border: 1px solid #ccc;
        border-radius: 3px;
        outline: none;
    }
    
    button {
        padding: 10px;
        background-color: #007bff;
        color: #fff;
        border: none;
        border-radius: 3px;
        cursor: pointer;
    }
    
    button:hover {
        background-color: #0056b3;
    }

        *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}


body {
    font-family: Arial, sans-serif;
  }
  
  .container {
    max-width: 400px;
    margin: 50px auto;
    padding: 20px;
    border: 1px solid #ccc;
    border-radius: 5px;
  }
  
  label {
    display: block;
    margin-bottom: 5px;
  }
  
  input[type="text"],
  input[type="email"],
  input[type="password"],
  button {
    width: 100%;
    padding: 10px;
    margin-bottom: 10px;
  }
  
  button {
    background-color: #007bff;
    color: #fff;
    border: none;
    border-radius: 5px;
    cursor: pointer;
  }
  
  button:hover {
    background-color: #0056b3;
  }

  

  body {
        font-family: Arial, sans-serif;
        line-height: 1.6;
        background-color: #f9f9f9;
        margin: 20px;
    }
    .container {
        max-width: 800px;
        margin: auto;
        padding: 20px;
        border: 1px solid #ccc;
        border-radius: 5px;
        background-color: #fff;
    }
    .question {
        margin-bottom: 20px;
    }
    .question h3 {
        margin-bottom: 10px;
    }
    .question label {
        display: block;
        margin-bottom: 5px;
        font-weight: bold;
    }
    .question input[type="radio"] {
        margin-right: 10px;
    }
    .timer {
        font-size: 20px;
        text-align: center;
        margin-bottom: 20px;
    }
    .form-group {
        text-align: center;
    }
    .form-group input[type="submit"] {
        background-color: #4CAF50;
        color: white;
        padding: 10px 15px;
        border: none;
        border-radius: 4px;
        cursor: pointer;
    }

body{
    font-family: sans-serif;
    background: linear-gradient(115deg, rgba(101,151,209,0.8),rgba(202,102,211,0.5)),url(/quizbg.jpg);
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    height: 100vh;
}
#title{
    text-align: center;
    padding: 0.8rem 0;
    font-size: 3rem;
    color: rgb(49,70,7);
    background: rgba(105,224,90,0.55);
    font-family: Georgia, 'Times New Roman', Times, serif;
}
.questions{
    margin: 3rem auto;
    width: 90vw;
    padding: 2rem;
    background: rgba(0,255,221,0.45);
    cursor: default;
    border-radius: 1rem;
}
#question{
    margin-bottom: 1rem;
}
.option{
    margin-bottom: 0.5rem;
    font-size: 1.2rem;
    border-bottom: solid 0.1rem green;
    width: 15rem;
    background: lightgreen;
    border-radius: 1rem;
}
.option:hover{
    color: white;
}
ol{
    position: relative;
    padding: 0 1.5rem;
    color: rgb(1,73,73);
}
span{
    display: block;
    padding: 0.1rem 0.7rem;
    border-radius: 1rem;
}
#answer{
    margin-top: 2.5rem;
}
#stat{
    margin-top: 1.5rem;
    color: rgb(6,17,168);
}
.buttons{
    text-align: center;
}
button{
    padding: 0.2rem 1.5rem;
    border: none;
    outline: none;
    font-size: 1.5rem;
    border-radius: 1.5rem;
    color: rgba(93,53,156,0.98);
    background: rgba(161,177,19,0.82);
}
button:active{
    background: lavenderblush;
}
#scoreboard,#answerBank{
    width: 20rem;
    background: rgba(230,230,250,0.77);
    padding: 2rem;
    text-align: center;
    margin: auto;
    position: relative;
    top: 5rem;
    display: none;
}
#score-title{
    margin: 1rem 0;
}
#score-btn,#check-answer{
    margin-top: 1rem;
}
#score{
    font-size: 2.5rem;
}
#answerBank li{
    text-align: left;
    margin-bottom: 0.2rem;
    font-size: larger;
}
#answers{
    margin-top: 1rem;
}

body {
  font-family: Arial, sans-serif;
  background-color: #f0f0f0;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  margin: 0;
}

.container {
  text-align: center;
  background-color: #fff;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

button {
  padding: 10px 20px;
  font-size: 16px;
  cursor: pointer;
  background-color: #007bff;
  color: #fff;
  border: none;
  border-radius: 4px;
}

button:hover {
  background-color: #0056b3;
}

    </style>

</head>
<body>

    <div class="login-container">
        <h2>Online Examination Login</h2>
        <form id="login-form">
            <input type="text" id="username" placeholder="Username" required>
            <input type="password" id="password" placeholder="Password" required>
            <button type="submit">Login</button>
        </form>

        <div class="container">
            <h2>User Profile</h2>
            <form id="profileForm">
              <label for="username">Username:</label>
              <input type="text" id="username" name="username" required>
              <label for="email">Email:</label>
              <input type="email" id="email" name="email" required>
              <label for="password">New Password:</label>
              <input type="password" id="password" name="password" required>
              <button type="submit">Update Profile</button>
            </form>
          </div>
          
          
    
    <h1 id="title">Today's Quiz</h1>

    <!-- quiz-container -->
    <div id="quiz-container">
        <!-- question container -->
        <div class="questions">
            <h2 id="question"></h2>
            <ol type="A">
                <li class="option"><span id="option0" onclick="calcScore(this)"></span></li>
                <li class="option"><span id="option1" onclick="calcScore(this)"></span></li>
                <li class="option"><span id="option2" onclick="calcScore(this)"></span></li>
                <li class="option"><span id="option3" onclick="calcScore(this)"></span></li>
            </ol>
            <h4 id="stat"></h4>
        </div>

        <div class="buttons">
            <button type="button" class="next">Next</button>
        </div>

    </div>

    <!-- scoreboard section -->
    <div id="scoreboard">
        <h2 id="score-title">Your Score</h2>
        <h2 id="score"></h2>
        <button type="button" id="score-btn" onclick="backToQuiz()">Back to Quiz</button>
        <button type="button" id="check-answer" onclick="checkAnswer()">Check Answers</button>
    </div>

            <div class="form-group">
        <input type="submit" id="submit-exam" value="Submit Exam">
    </div>
</div>
<div id="timer" class="timer"></div>
    
    <!-- answers section -->
    <div id="answerBank">
        <h2>Answers :</h2>
        <ol type="1" id="answers">

        </ol>
        <button type="button" id="score-btn" onclick="backToQuiz()">Back to Quiz</button>
    </div>

    <div class="container">
        <h1>Welcome to My App</h1>
        <button id="logout-btn">Logout</button>
      </div>

</body>
</html>
<script>

    document.getElementById("login-form").addEventListener("submit", function(event) {
    event.preventDefault();
    
    var username = document.getElementById("username").value;
    var password = document.getElementById("password").value;

    // Here you would validate the username and password, for example, by sending them to a server for authentication.
    // For this example, let's just display an alert.
    alert("Username: " + username + "\nPassword: " + password);
});

document.getElementById("profileForm").addEventListener("submit", function(event) {
    event.preventDefault();
    // Get form values
    var username = document.getElementById("username").value;
    var email = document.getElementById("email").value;
    var password = document.getElementById("password").value;
  
    // Here you can send the form data to the server for processing, e.g., using AJAX
    console.log("Username: " + username);
    console.log("Email: " + email);
    console.log("New Password: " + password);
  
    // Reset form
    document.getElementById("profileForm").reset();
  });

  
    // Set your exam duration in seconds
    const examDuration = 300; // 5 minutes

    let timerInterval;

    // Countdown timer function
    function startTimer(duration, display) {
        let timer = duration, minutes, seconds;
        timerInterval = setInterval(function () {
            minutes = parseInt(timer / 60, 10);
            seconds = parseInt(timer % 60, 10);

            minutes = minutes < 10 ? "0" + minutes : minutes;
            seconds = seconds < 10 ? "0" + seconds : seconds;

            display.textContent = minutes + ":" + seconds;

            if (--timer < 0) {
                clearInterval(timerInterval);
                alert('Time up! Auto-submitting answers.');
                submitExam();
            }
        }, 1000);
    }

    // Start the timer when the page loads
    window.onload = function () {
        const display = document.getElementById('timer');
        startTimer(examDuration, display);
    };

    // Submit exam function
    function submitExam() {
        clearInterval(timerInterval);
        document.getElementById('submit-exam').setAttribute('disabled', 'disabled');

        // Simulate exam submission (replace with actual submission logic)
        let answers = {};
        const questions = document.querySelectorAll('.question');
        questions.forEach((question, index) => {
            const radioButtons = question.querySelectorAll('input[type="radio"]');
            radioButtons.forEach(radio => {
                if (radio.checked) {
                    answers[`q${index + 1}`] = radio.value;
                }
            });
        });

        // Example: Displaying selected answers (replace with your logic)
        let result = '<h2>Exam Results:</h2>';
        Object.keys(answers).forEach(key => {
            result += `<p>Question ${key}: ${answers[key]}</p>`;
        });

        document.getElementById('exam-content').innerHTML = result;
    }

    // Example: Prevent form submission (in case JavaScript is disabled)
    document.getElementById('submit-exam').addEventListener('click', function(event) {
        event.preventDefault();
        submitExam();
    });

//Question bank
var questionBank= [
    {
        question : ' Which animal is known as the Ship of the Desert',


        option : ['camel','dog','donkey','horse'],
        answer : 'camel'
    },
    {
        question : ' How many seconds make one hour',


        
        option : ['23000 seconds','36000 seconds','40000 seconds','33000 seconds'],
        answer : '36000 seconds'
    },
    {
        question :' How many consonants are there in the English alphabet?',


        option : ['20 Consonants ','30 Consonants','21 Consonants','22 Consonants'],
        answer : '21 Consonants'
    },
    {
        question : ' Name the National bird of India?',

        option : ['Pigeons','crow',' The Peacock'

,'puffin'],
        answer : ' The Peacock'


    },
    {
        question : 'First human heart transplant operation conducted by Dr. Christiaan Barnard on Louis Washkansky, was conducted in',
        option : ['1967','1968','1958','1922'],
        answer : '1967'
    }
]

var question= document.getElementById('question');
var quizContainer= document.getElementById('quiz-container');
var scorecard= document.getElementById('scorecard');
var option0= document.getElementById('option0');
var option1= document.getElementById('option1');
var option2= document.getElementById('option2');
var option3= document.getElementById('option3');
var next= document.querySelector('.next');
var points= document.getElementById('score');
var span= document.querySelectorAll('span');
var i=0;
var score= 0;

//function to display questions
function displayQuestion(){
    for(var a=0;a<span.length;a++){
        span[a].style.background='none';
    }
    question.innerHTML= 'Q.'+(i+1)+' '+questionBank[i].question;
    option0.innerHTML= questionBank[i].option[0];
    option1.innerHTML= questionBank[i].option[1];
    option2.innerHTML= questionBank[i].option[2];
    option3.innerHTML= questionBank[i].option[3];
    stat.innerHTML= "Question"+' '+(i+1)+' '+'of'+' '+questionBank.length;
}

//function to calculate scores
function calcScore(e){
    if(e.innerHTML===questionBank[i].answer && score<questionBank.length)
    {
        score= score+1;
        document.getElementById(e.id).style.background= 'blue';
    }
    else{
        document.getElementById(e.id).style.background= 'tomato';
    }
    setTimeout(nextQuestion,300);
}

//function to display next question
function nextQuestion(){
    if(i<questionBank.length-1)
    {
        i=i+1;
        displayQuestion();
    }
    else{
        points.innerHTML= score+ '/'+ questionBank.length;
        quizContainer.style.display= 'none';
        scoreboard.style.display= 'block'
    }
}

//click events to next button
next.addEventListener('click',nextQuestion);

//Back to Quiz button event
function backToQuiz(){
    location.reload();
}

//function to check Answers
function checkAnswer(){
    var answerBank= document.getElementById('answerBank');
    var answers= document.getElementById('answers');
    answerBank.style.display= 'block';
    scoreboard.style.display= 'none';
    for(var a=0;a<questionBank.length;a++)
    {
        var list= document.createElement('li');
        list.innerHTML= questionBank[a].answer;
        answers.appendChild(list);
    }
}


displayQuestion();

document.getElementById('logout-btn').addEventListener('click', function() {
  // Perform logout actions here
  // For demonstration, let's just reload the page
  window.location.href = 'logout.html'; // Redirect to logout page or handle logout logic
});

</script>
