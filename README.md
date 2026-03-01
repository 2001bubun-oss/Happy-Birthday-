# Happy-Birthday-<!DOCTYPE html>
<html lang="en">
<head>
    <title>Happy Birthday Ivana Chakraborty 💖🎂</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body {
            height: 100vh; overflow: hidden;
            background: linear-gradient(-45deg, #ff9a9e, #fecfef, #fad0c4, #ffd1ff);
            background-size: 600% 600%; animation: gradientShift 12s ease infinite;
            font-family: 'Dancing Script', cursive; cursor: none; position: relative;
        }
        @import url('https://fonts.googleapis.com/css2?family=Dancing+Script:wght@700&family=Poppins:wght@400;600&display=swap');
        @keyframes gradientShift {
            0%,100% {background-position:0% 50%}
            50% {background-position:100% 50%}
        }
        .stars { 
            position: absolute; top: 0; left: 0; width: 100%; height: 100%;
            background-image: 
                radial-gradient(2px 2px at 20px 30px, #fff, transparent),
                radial-gradient(2px 2px at 40px 70px, rgba(255,255,255,0.8), transparent),
                radial-gradient(1px 1px at 90px 40px, #fff, transparent),
                radial-gradient(1px 1px at 130px 80px, rgba(255,255,255,0.6), transparent),
                radial-gradient(2px 2px at 200px 120px, #fff, transparent);
            background-repeat: repeat; background-size: 250px 150px;
            animation: sparkle 25s linear infinite; opacity: 0.9; z-index: 1;
        }
        @keyframes sparkle { 100% { transform: translateY(-50px) rotate(0.5deg); } }
        
        .container {
            position: absolute; top: 50%; left: 50%; transform: translate(-50%, -50%);
            text-align: center; color: #fff; z-index: 1000; text-shadow: 0 0 25px rgba(0,0,0,0.6);
            font-family: 'Poppins', sans-serif;
        }
        h1 {
            font-family: 'Dancing Script', cursive; font-size: 4.2em; margin-bottom: 25px;
            background: linear-gradient(45deg, #ff6b9d, #ffd93d, #6bcf7f, #4ecdc4, #feca57);
            -webkit-background-clip: text; -webkit-text-fill-color: transparent; 
            background-size: 400% 400%; animation: rainbow 3s ease-in-out infinite;
            filter: drop-shadow(0 0 45px rgba(255,255,255,0.9));
        }
        @keyframes rainbow { 
            0%,100%{background-position:0% 50%} 
            50%{background-position:100% 50%} 
        }
        #message { 
            font-size: 1.7em; line-height: 1.7; max-width: 850px; margin: 0 auto 50px;
            opacity: 0; animation: fadeInUp 2.5s 0.8s forwards; font-weight: 600;
        }
        @keyframes fadeInUp { 
            0% { opacity: 0; transform: translateY(40px); }
            100% { opacity: 1; transform: translateY(0); }
        }
        
        .btn-party {
            background: linear-gradient(45deg, #ff6b9d, #ffd700, #ff1493, #00ff88);
            background-size: 300% 300%; animation: btnGlow 4s ease infinite;
            border: none; padding: 25px 65px; font-size: 1.9em; border-radius: 60px;
            color: white; cursor: pointer; position: relative; overflow: hidden;
            box-shadow: 0 18px 40px rgba(255,107,157,0.7), 0 0 0 1px rgba(255,255,255,0.3);
            transition: all 0.5s cubic-bezier(0.175, 0.885, 0.32, 1.275);
            font-family: 'Poppins', sans-serif; font-weight: 600; text-transform: uppercase;
            letter-spacing: 3px; text-shadow: 0 2px 10px rgba(0,0,0,0.3);
        }
        @keyframes btnGlow { 0%,100%{background-position:0% 50%} 50%{background-position:100% 50%} }
        .btn-party:hover { 
            transform: translateY(-10px) scale(1.08); 
            box-shadow: 0 30px 60px rgba(255,215,0,0.9), 0 0 30px rgba(255,255,255,0.8);
        }
        .btn-party:active { transform: scale(0.97); }
        
        /* Floating Balloons & Gifts */
        .balloon {
            position: absolute; bottom: -120px; animation: floatUp 10s infinite linear;
            font-size: 35px; pointer-events: none; z-index: 10;
        }
        @keyframes floatUp {
            0% { bottom: -120px; opacity: 0; transform: translateX(0) rotate(0deg) scale(0.8); }
            15% { opacity: 1; transform: scale(1.1); }
            85% { opacity: 1; }
            100% { bottom: 120vh; opacity: 0; transform: translateX(250px) rotate(720deg) scale(1.3); }
        }
        .gift { 
            position: absolute; font-size: 45px; animation: bounce 3.5s infinite ease-in-out;
            z-index: 15; text-shadow: 0 4px 12px rgba(0,0,0,0.4);
        }
        @keyframes bounce {
            0%,20%,50%,80%,100% { transform: translateY(0) rotate(5deg); }
            40% { transform: translateY(-35px) rotate(-5deg); }
            60% { transform: translateY(-20px) rotate(3deg); }
        }
        
        /* Custom Birthday Cursor */
        body::after {
            content: '🎂'; position: fixed; pointer-events: none; z-index: 9999; 
            font-size: 32px; transform: translate(-50%, -50%);
            animation: cursorBounce 1.8s infinite ease-in-out;
        }
        @keyframes cursorBounce { 
            0%,100%{transform:translate(-50%,-50%) scale(1) rotate(0deg)}
            50%{transform:translate(-50%,-50%) scale(1.4) rotate(180deg)}
        }
    </style>
</head>
<body>
    <div class="stars"></div>
    
    <div class="container">
        <h1>Happy Birthday Ivana Chakraborty! 🎉💖</h1>
        <div id="message"></div>
        <button class="btn-party" onclick="celebrateBirthday()">I Love You! 🎈🎁✨</button>
    </div>

    <script>
        // Personalized Messages for Ivana
        const bdayMsgs = [
            "Ivana Chakraborty, my dearest love, your birthday is my favorite day! 🌟💕",
            "You make every moment magical. Wishing you infinite happiness! 🎂✨",
            "My heart beats for you always. Happy Birthday to my forever love! ☀️💖",
            "You're more beautiful than all the stars combined. Love you endlessly! 🌹"
        ];
        
        let msgIdx = 0, charIdx = 0;
        function typeBdayMsg() {
            const msgEl = document.getElementById('message');
            if (charIdx < bdayMsgs[msgIdx].length) {
                msgEl.innerHTML += bdayMsgs[msgIdx].charAt(charIdx);
                charIdx++;
                setTimeout(typeBdayMsg, 60);
            } else {
                setTimeout(() => {
                    charIdx = 0; msgEl.innerHTML = '';
                    msgIdx = (msgIdx + 1) % bdayMsgs.length;
                    typeBdayMsg();
                }, 3500);
            }
        }
        typeBdayMsg();
        
        // Floating Balloons & Gifts
        const balloons = ['🎈','🎊','🎉','🎁','🌹','💝','🎂','🥳','✨'];
        setInterval(() => {
            const bal = document.createElement('div');
            bal.className = 'balloon'; 
            bal.innerHTML = balloons[Math.floor(Math.random()*balloons.length)];
            bal.style.left = Math.random() * 100 + '%';
            bal.style.animationDelay = Math.random() * 3 + 's';
            bal.style.animationDuration = (Math.random()*4 + 7) + 's';
            document.body.appendChild(bal);
            setTimeout(() => bal.remove(), 12000);
        }, 600);
        
        // Bouncing Gifts
        setInterval(() => {
            const gift = document.createElement('div');
            gift.className = 'gift'; 
            gift.innerHTML = ['🎁','💐','🍰','💍','🎀'][Math.floor(Math.random()*5)];
            gift.style.left = (Math.random() * 85) + '%';
            gift.style.top = (Math.random() * 80) + '%';
            gift.style.animationDelay = Math.random() * 3 + 's';
            document.body.appendChild(gift);
            setTimeout(() => gift.remove(), 6000);
        }, 1200);
        
        // Epic Birthday Celebration
        function celebrateBirthday() {
            const btn = document.querySelector('.btn-party');
            btn.innerHTML = 'Happy Birthday My Love! 🎉🥰💕';
            btn.style.background = 'linear-gradient(45deg, #ffd700, #ff6b9d, #00ff88, #4ecdc4)';
            btn.style.transform = 'scale(1.1)';
            
            document.getElementById('message').innerHTML = 
                `<div style="font-size:2em; animation: pulse 1s infinite;">
                🎂 DEAR IVANA CHAKRABORTY 🎂<br><br>
                You are my sunshine, my heartbeat, my everything! 🌟<br>
                Wishing you the most magical year ahead! 🥳💖<br>
                I love you more than words... Forever! 💍✨
                </div>`;
            
            // MASSIVE Celebration Effects
            for(let i = 0; i < 250; i++) {
                setTimeout(() => createConfetti(), i * 15);
            }
        }
        
        // Confetti Rain
        function createConfetti() {
            const confetti = document.createElement('div');
            confetti.style.cssText = `
                position: fixed; top: -10px; left: ${Math.random()*100}%;
                width: 12px; height: 12px; background: hsl(${Math.random()*360}, 100%, 70%);
                border-radius: 50%; z-index: 9999; pointer-events: none;
                animation: confettiFall 4s linear forwards;
            `;
            document.body.appendChild(confetti);
            setTimeout(() => confetti.remove(), 4000);
        }
    </script>
    <style>
        @keyframes confettiFall {
            to { transform: translateY(110vh) rotate(1080deg); opacity: 0; }
        }
        @keyframes pulse {
            0%,100% { transform: scale(1); }
            50% { transform: scale(1.05); }
        }
    </style>
</body>
</html>
