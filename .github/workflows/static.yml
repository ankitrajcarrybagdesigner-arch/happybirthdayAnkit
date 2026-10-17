
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy Birthday Ankit Raj</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    overflow: hidden;
    font-family: Arial, sans-serif;
    background: linear-gradient(135deg, #090979, #7b2ff7, #f107a3);
    color: white;
    text-align: center;
}

.card {
    padding: 40px 25px;
    width: 90%;
    max-width: 550px;
    border: 2px solid #ffd700;
    border-radius: 25px;
    background: rgba(0, 0, 0, 0.35);
    box-shadow: 0 0 35px #ff00ff;
    animation: glow 2s infinite alternate;
    z-index: 2;
}

h1 {
    color: #ffd700;
    font-size: clamp(30px, 7vw, 48px);
    text-shadow: 0 0 15px #ff4500;
    animation: pulse 1.5s infinite;
}

.name {
    margin: 20px 0;
    font-size: clamp(32px, 8vw, 52px);
    font-weight: bold;
    color: #00ffff;
    text-shadow: 0 0 20px #00ffff;
}

.cake {
    font-size: 75px;
    margin: 20px 0;
    animation: bounce 1s infinite alternate;
}

p {
    font-size: 18px;
    line-height: 1.7;
}

button {
    margin-top: 25px;
    padding: 13px 25px;
    border: none;
    border-radius: 30px;
    background: #ffd700;
    color: #4b0082;
    font-weight: bold;
    font-size: 16px;
    cursor: pointer;
}

button:hover {
    background: white;
    transform: scale(1.08);
}

.balloon {
    position: absolute;
    bottom: -120px;
    font-size: 45px;
    animation: fly 8s linear infinite;
}

.balloon:nth-child(2) { left: 10%; animation-delay: 1s; }
.balloon:nth-child(3) { left: 80%; animation-delay: 3s; }
.balloon:nth-child(4) { left: 25%; animation-delay: 5s; }
.balloon:nth-child(5) { left: 65%; animation-delay: 2s; }

@keyframes glow {
    from { box-shadow: 0 0 15px #ff00ff; }
    to { box-shadow: 0 0 40px #00ffff; }
}

@keyframes pulse {
    50% { transform: scale(1.06); }
}

@keyframes bounce {
    to { transform: translateY(-12px); }
}

@keyframes fly {
    to { transform: translateY(-120vh) rotate(20deg); }
}
</style>
</head>

<body>

<div class="balloon">🎈</div>
<div class="balloon">🎈</div>
<div class="balloon">🎈</div>
<div class="balloon">🎈</div>

<div class="card">
    <h1>🎉 HAPPY BIRTHDAY 🎉</h1>

    <div class="cake">🎂</div>

    <div class="name">ANKIT RAJ</div>

    <p>
        Wishing You A Day Full Of Happiness! 💖<br>
        May All Your Dreams Come True. ✨<br>
        Stay Blessed, Keep Smiling! 🌟
    </p>

    <button onclick="celebrate()">
        🎊 Click for Surprise 🎊
    </button>

    <p id="message" style="margin-top:20px;"></p>
</div>

<script>
function celebrate() {
    document.getElementById("message").innerHTML =
        "🥳🎁 Many Many Happy Returns of the Day, Ankit Raj! 🎁🥳";
    
    for (let i = 0; i < 25; i++) {
        let confetti = document.createElement("div");
        confetti.innerHTML = ["🎉", "✨", "💖", "🎊"][
            Math.floor(Math.random() * 4)
        ];
        confetti.style.position = "absolute";
        confetti.style.left = Math.random() * 100 + "vw";
        confetti.style.top = Math.random() * 100 + "vh";
        confetti.style.fontSize = "25px";
        confetti.style.pointerEvents = "none";
        document.body.appendChild(confetti);
        setTimeout(() => confetti.remove(), 2500);
    }
}
</script>

</body>
</html>
