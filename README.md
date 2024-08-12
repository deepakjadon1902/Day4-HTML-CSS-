<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta http-equiv="X-UA-Compatible" content="IE=edge" />
<meta name="viewport" content="width=device-width,
initial-scale=1.0" />
<title>CSS Assignment</title>
<style>
#container {
    height: 600px;
    width: 700px;
    background-color: white;
    border: 2px solid lightseagreen;
    border-radius: 10px;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-evenly;
    align-items: center;
    }
    .box {
    height: 100px;
    width: 100px;
    background-color: grey;
    border: 2px solid black;
    border-radius: 10px;
    font-size: 50px;
    text-align: center;
    }
    #navbar {
        height: 50px;
        width: 900px;
        background-color: pink;
        border: 2px solid lightseagreen;
        border-radius: 10px;
        display: flex;
        justify-content: flex-start;
        align-content: center;
        }
        .option {
        height: 50px;
        width: 80px;
        border-radius: 10px;
        margin-left: 5px;
        font-size: 24px;
        line-height: 50px;
        }
        </style>
</head>
<body>
<div id="container">
<div class="box">A</div>
<div class="box">B</div>
<div class="box">C</div>
<div class="box">D</div>
<div class="box">E</div>
<div class="box">F</div>
<div class="box">G</div>
<div class="box">H</div>
<div class="box">I</div>
<div class="box">J</div>
<div class="box">K</div>
<div class="box">L</div>
<div class="box">M</div>
<div class="box">N</div>
<div class="box">O</div>
<div class="box">P</div>
<div class="box">Q</div>
<div class="box">R</div>
<div class="box">S</div>
<div class="box">T</div>
<div class="box">U</div>
<div class="box">V</div>
<div class="box">W</div>
<div class="box">X</div>
<div class="box">Y</div>
<div class="box">Z</div>
</div>
<br>
<div id="navbar">
<div class="option">logo</div>
<div class="option">Home</div>
<div class="option">About</div>
<div class="option">Contact</div>
</div>
</body>
</html>
