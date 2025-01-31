<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Handsome Boi Roleplay System - About Me</title>
    <style>
        /* Dark mode background */
        body {
            font-family: Arial, sans-serif;
            background-color: #121212;
            color: #ffffff;
            margin: 0;
            padding: 0;
            transition: background-color 0.5s ease;
        }

        h1, h2 {
            text-align: center;
            color: #3498db;
            font-family: 'Arial', sans-serif;
        }

        h2 {
            color: #e74c3c;
        }

        .container {
            max-width: 800px;
            margin: auto;
            padding: 20px;
            text-align: center;
            background-color: #2c3e50;
            border-radius: 10px;
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.5);
        }

        p {
            font-size: 1.2em;
            margin-bottom: 20px;
            line-height: 1.6;
        }

        ul {
            list-style-type: none;
            padding: 0;
        }

        li {
            padding: 10px;
            background-color: #34495e;
            margin: 10px 0;
            border-radius: 8px;
        }

        .highlight {
            font-weight: bold;
        }

        .emoji {
            font-size: 1.5em;
        }

        #easter-egg {
            display: none;
            padding: 20px;
            background-color: #e74c3c;
            color: white;
            border-radius: 8px;
            margin-top: 20px;
        }

        .reveal-btn {
            background-color: #3498db;
            color: white;
            border: none;
            padding: 12px;
            cursor: pointer;
            border-radius: 5px;
            font-size: 1.1em;
            transition: background-color 0.3s ease;
        }

        .reveal-btn:hover {
            background-color: #2980b9;
        }

        .input-box {
            margin-top: 20px;
        }

        .input-box input {
            padding: 10px;
            font-size: 1em;
            width: 80%;
            border-radius: 5px;
            border: 1px solid #ddd;
            background-color: #1c2833;
            color: white;
        }

        .input-box button {
            padding: 10px 15px;
            background-color: #2ecc71;
            border: none;
            border-radius: 5px;
            color: white;
            font-size: 1em;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        .input-box button:hover {
            background-color: #27ae60;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Welcome to the Handsome Boi Roleplay System! ✨</h1>

        <p>Embark on an immersive journey where YOU are the star! 🌟 Step into the world of high-class charm, romance, and strategy. The **Handsome Boi RP System** is designed to help you conquer social, romantic, and business landscapes with your charisma, wealth, and confidence. 💼💎</p>

        <h2>Key Features 🗝️</h2>
        <ul>
            <li><span class="emoji">👑</span> **Customizable Settings:** Choose your city, target girl, or specific mission.</li>
            <li><span class="emoji">❤️</span> **Behavior System:** NPC girls react dynamically to your personality and actions.</li>
            <li><span class="emoji">⚡</span> **EXP & Power System:** Earn EXP, unlock special abilities, and dominate interactions.</li>
            <li><span class="emoji">🚗</span> **RevAuto Car System:** Show off your car and watch NPCs react based on your vehicle's features.</li>
            <li><span class="emoji">📍</span> **City & NPC Interactions:** Engage with characters across various settings, from luxury galas to street markets.</li>
        </ul>

        <h2>The Trenx Behavior Pack 🔥</h2>
        <p>This unique pack enhances interactions by adding detailed personality traits to NPC girls. Whether they're cold, clingy, shy, or loving, you’ll need to adjust your approach to win their hearts! 💘</p>

        <h2>RevAuto: The Car System 🚗💨</h2>
        <p>Choose your ride and watch how the world reacts. Whether you drive a sleek sports car or a luxury vehicle, the system generates vivid descriptions and NPC reactions based on your car’s details. From admiration to envy, the road is filled with potential! 🏎️💥</p>

        <h2>The City Experience 🏙️</h2>
        <p>The city is alive, filled with different districts and diverse people. From high society to street markets, you’ll encounter trust issues, love challenges, and intense social dynamics. 🏙️💫</p>

        <h2>Start Your Journey Now! 🚀</h2>
        <p>With your charm, wit, and confidence, there’s no limit to what you can achieve! 🌟</p>

        <div class="input-box">
            <input type="text" id="codeInput" placeholder="Enter code to unlock special info...">
            <button id="submitCodeBtn">Submit</button>
        </div>

        <div id="easter-egg">
            <h3>Special Girls ✨</h3>
            <p>Here’s a sneak peek of the three special girls in your journey! 🌹</p>
            <ul>
                <li><span class="emoji">💋</span> **The Korean Beauty (Ultra Challenge)**: Sweet, elegant, independent. Subtle romantic gestures win her heart. Likes confidence, but dislikes arrogance. 🥰</li>
                <li><span class="emoji">🔥</span> **The Cold, Rude, Alluring Girl**: A stunning, curvy woman with a fierce personality. Will make you work hard for her affections. Trust is hard to build with her, but persistence and charm can break her walls. 💪</li>
                <li><span class="emoji">💎</span> **The Tsundere Queen**: Aloof and tough on the outside, but secretly has feelings for you. Handle with care—she has high expectations! 🥺</li>
            </ul>
        </div>

        <button class="reveal-btn" id="unlockButton">Unlock Special Girl Info 🔒</button>

    </div>

    <script>
        document.getElementById("submitCodeBtn").addEventListener("click", function() {
            var code = document.getElementById("codeInput").value;
            if (code === "handsomeboi2025") {
                document.getElementById("easter-egg").style.display = "block";
                alert("Code correct! Special girl info unlocked! 🔓");
            } else {
                alert("Incorrect code! Try again!");
            }
        });

        // Optional: Make the unlock button more engaging
        document.getElementById("unlockButton").addEventListener("click", function() {
            var code = prompt("Enter the secret code to unlock the special girls!");
            if (code === "KaiYourDevHasABigCock") {
                document.getElementById("easter-egg").style.display = "block";
                alert("You have unlocked the secret girls! 🎉");
            } else {
                alert("Wrong code! Try again!");
            }
        });
    </script>
</body>
</html>
