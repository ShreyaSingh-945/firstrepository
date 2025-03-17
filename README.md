<!DOCTYPE html>
<html>
<head>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Creepster&display=swap');

        body {
            background: black url("dark.jpg") no-repeat center center fixed;
            background-size: cover;
            color: red;
            font-family: 'Creepster', cursive;
            text-align: center;
            overflow: hidden;
        }

        h1 {
            font-size: 60px;
            text-shadow: 5px 5px 10px darkred;
            animation: flicker 1.5s infinite alternate;
        }

        h3 {
            font-size: 25px;
            text-shadow: 2px 2px 5px red;
            animation: shake 0.5s infinite alternate;
        }

        @keyframes flicker {
            0% { opacity: 1; }
            50% { opacity: 0.5; }
            100% { opacity: 1; }
        }

        @keyframes shake {
            0% { transform: translateX(-2px); }
            50% { transform: translateX(2px); }
            100% { transform: translateX(-2px); }
        }

        form {
            font-size: 20px;
            color: white;
        }

        input {
            background: black;
            color: red;
            border: 2px solid darkred;
            padding: 5px;
            font-family: 'Creepster', cursive;
        }

        .enter-button {
            display: block;
            background: darkred;
            color: white;
            padding: 15px;
            text-decoration: none;
            font-size: 20px;
            font-weight: bold;
            border-radius: 5px;
            width: 120px;
            margin: auto;
            box-shadow: 0px 0px 10px red;
            transition: 0.5s ease-in-out;
        }

        .enter-button:hover {
            background: black;
            color: red;
            box-shadow: 0px 0px 20px white;
            transform: scale(1.2);
        }

        audio {
            display: none;
        }

    </style>
</head>
<body>
    <h1>𝔻𝔸ℝ𝕂 𝕎𝔼𝔹</h1>
    <h3>Enter Your Sooul... I Mean Details (Confidential)</h3>
    <form>
        Code Name: <input type="text" name="name"><br><br>
        Passcode: <input type="password" name="pwd"><br><br>
        <a href="darkwebsite.htm" class="enter-button">Enter</a>
    </form>

    <audio autoplay loop>
        <source src="dark_audio.m4a" type="audio/mpeg">
    </audio>
</body>
</html>

            
