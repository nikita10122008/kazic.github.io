<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Slot Machine</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #ffe600;
            font-family: Arial, sans-serif;
            position: relative;
        }
        .slot-machine {
            display: flex;
            flex-direction: column;
            align-items: center;
            background-color: #ffbc02;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgb(255, 72, 0);
            width: 90%;
            max-width: 600px;
            z-index: 1;
        }
        .reels {
            display: flex;
            justify-content: center;
            width: 100%;
            margin-bottom: 20px;
        }
        .reel {
            width: 30%;
            max-width: 100px;
            height: 100px;
            display: flex;
            justify-content: center;
            align-items: center;
            border: 1px solid #fcad04;
            margin: 0 10px;
            background-color: #ffe600;
        }
        .reel img {
            width: 100%;
            height: 100%;
            object-fit: contain;
        }
        .win-message {
            font-size: 2em;
            margin-bottom: 20px;
            display: none;
        }
        .jackpot-message {
            position: fixed;
            top: 10%;
            left: 0;
            width: 100%;
            text-align: center;
            font-size: 4em;
            color: #fff;
            text-shadow: 0 0 10px #000;
            display: none;
            z-index: 0;
        }
        button {
            padding: 10px 20px;
            font-size: 1em;
            cursor: pointer;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
            transition: background-color 0.3s;
        }
        button:hover {
            background-color: #45a049;
        }
        button:disabled {
            background-color: #cccccc;
            cursor: not-allowed;
        }
    </style>
</head>
<body>
    <div class="slot-machine">
        <div class="reels">
            <div class="reel" id="reel1"><img src="symbol1.png" alt="" class="symbol"></div>
            <div class="reel" id="reel2"><img src="symbol2.png" alt="" class="symbol"></div>
            <div class="reel" id="reel3"><img src="symbol3.png" alt="" class="symbol"></div>
        </div>
        <div class="win-message" id="winMessage"></div>
        <button id="spinButton" onclick="spin()">Крутка</button>
    </div>
    <div class="jackpot-message" id="jackpotMessage">ДЖЕКПОТ</div>

    <script>
        const symbols = ['symbol1.png', 'symbol2.png', 'symbol3.png', 'symbol4.png', 'symbol5.png'];

        function getRandomSymbol() {
            return symbols[Math.floor(Math.random() * symbols.length)];
        }

        function spin() {
            const reel1 = document.getElementById('reel1').querySelector('img');
            const reel2 = document.getElementById('reel2').querySelector('img');
            const reel3 = document.getElementById('reel3').querySelector('img');
            const jackpotMessage = document.getElementById('jackpotMessage');
            const spinButton = document.getElementById('spinButton');

            reel1.src = getRandomSymbol();
            reel2.src = getRandomSymbol();
            reel3.src = getRandomSymbol();

            if (reel1.src === reel2.src && reel2.src === reel3.src) {
                jackpotMessage.style.display = 'block';
                spinButton.disabled = true;
                setTimeout(() => {
                    jackpotMessage.style.display = 'none';
                    spinButton.disabled = false;
                }, 3000);
            } else {
                jackpotMessage.style.display = 'none';
            }
        }
    </script>
</body>
</html>
