<!DOCTYPE html>
<html lang="kk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Болашақ технологиялары 2026</title>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary: #00f2ff;
            --secondary: #7000ff;
            --bg: #0d1117;
            --card: #161b22;
            --text: #c9d1d9;
        }

        body {
            font-family: 'Montserrat', sans-serif;
            background-color: var(--bg);
            color: var(--text);
            margin: 0;
            display: flex;
            justify-content: center;
            padding: 20px;
        }

        .main-wrapper {
            width: 100%;
            max-width: 900px;
        }

        header {
            text-align: center;
            padding: 40px 0;
        }

        h1 {
            color: var(--primary);
            font-size: 2.5rem;
            text-transform: uppercase;
            letter-spacing: 3px;
            margin-bottom: 10px;
        }

        /* Слайдер */
        .slider-box {
            position: relative;
            background: var(--card);
            border-radius: 20px;
            padding: 50px;
            min-height: 400px;
            box-shadow: 0 20px 50px rgba(0,0,0,0.5);
            border: 1px solid rgba(0, 242, 255, 0.1);
            display: flex;
            flex-direction: column;
            justify-content: center;
        }

        .slide {
            display: none;
            animation: slideIn 0.6s ease-out;
        }

        .slide.active { display: block; }

        @keyframes slideIn {
            from { transform: translateX(20px); opacity: 0; }
            to { transform: translateX(0); opacity: 1; }
        }

        .slide h2 {
            color: var(--primary);
            font-size: 1.8rem;
            margin-bottom: 20px;
        }

        .slide p {
            font-size: 1.1rem;
            line-height: 1.8;
            color: #8b949e;
        }

        .nav-buttons {
            display: flex;
            justify-content: space-between;
            margin-top: 30px;
        }

        .btn {
            background: transparent;
            border: 2px solid var(--primary);
            color: var(--primary);
            padding: 12px 25px;
            border-radius: 30px;
            cursor: pointer;
            font-weight: bold;
            transition: 0.3s;
        }

        .btn:hover {
            background: var(--primary);
            color: #000;
            box-shadow: 0 0 20px var(--primary);
        }

        /* Бот */
        .ai-bot {
            margin-top: 50px;
            background: #1c2128;
            border-radius: 20px;
            padding: 30px;
            border: 1px solid var(--secondary);
        }

        .chat-area {
            height: 250px;
            overflow-y: auto;
            background: rgba(0,0,0,0.2);
            border-radius: 10px;
            padding: 20px;
            margin-bottom: 20px;
        }

        .msg { margin-bottom: 15px; padding: 10px 15px; border-radius: 10px; max-width: 80%; }
        .bot-msg { background: var(--secondary); color: white; align-self: flex-start; }
        .user-msg { background: #30363d; color: white; margin-left: auto; text-align: right; }

        .input-group { display: flex; gap: 10px; }
        input {
            flex: 1;
            padding: 15px;
            border-radius: 10px;
            border: none;
            background: #0d1117;
            color: white;
            border: 1px solid #30363d;
        }

        .send-btn {
            background: var(--secondary);
            border: none;
            color: white;
            padding: 0 25px;
            border-radius: 10px;
            cursor: pointer;
            font-weight: bold;
        }
    </style>
</head>
<body>

<div class="main-wrapper">
    <header>
        <h1>Болашақ Жобасы 2026</h1>
        <p>Жасанды интеллект және адамзаттың келесі қадамы</p>
    </header>

    <div class="slider-box">
        <div class="slide active">
            <h2>01. Нейротехнологиялар</h2>
            <p>2026 жылы нейроинтерфейстер тек медициналық құрал емес, күнделікті өмірдің бөлшегіне айналды. Адамдар ой күшімен хат жазып, үй құрылғыларын басқара алады. Бұл технология мүмкіндігі шектеулі жандарға еркін қозғалуға және қарым-қатынас жасауға толық жағдай жасады.</p>
        </div>
        <div class="slide">
            <h2>02. Жасыл энергия және ЖИ</h2>
            <p>Жасанды интеллект планетаның климатын бақылауға алды. ЖИ алгоритмдері күн және жел энергиясын тиімді бөлу арқылы қалаларды 100% экологиялық таза қуатпен қамтамасыз етуде. Бұл көміртегі қалдығын нөлге дейін төмендетуге мүмкіндік берді.</p>
        </div>
        <div class="slide">
            <h2>03. Білім берудің жаңа форматы</h2>
            <p>Мұғалімдердің орнына ЖИ-тьюторлар келді деп ойласаңыз, қателесесіз. Керісінше, ЖИ техникалық жұмыстарды (тексеру, жоспарлау) өз мойнына алып, мұғалімдерге баланың шығармашылығымен және тәрбиесімен айналысуға көбірек уақыт берді.</p>
        </div>
        <div class="slide">
            <h2>04. Марс пен Ай колониялары</h2>
            <p>2026 жылы Ай бетіндегі алғашқы тұрақты база іске қосылды. Автономды роботтар адамдар келуіне дейін барлық инфрақұрылымды дайындап қойды. Бұл адамзаттың көппланеталы түрге айналуының алғашқы нақты қадамы болды.</p>
        </div>
        <div class="slide">
            <h2>05. Киберқауіпсіздік</h2>
            <p>Цифрлық әлемдегі қауіпсіздікті енді кванттық шифрлау жүйелері қорғайды. Сіздің жеке деректеріңіз бен цифрлық егізіңіз бұзылудан толық қорғалған. ЖИ нақты уақыт режимінде кез келген хакерлік шабуылды анықтап, тойтарыс береді.</p>
        </div>

        <div class="nav-buttons">
            <button class="btn" onclick="go(-1)">⬅ Артқа</button>
            <button class="btn" onclick="go(1)">Алға ➡</button>
        </div>
    </div>

    <div class="ai-bot">
        <h3>🤖 ЖИ Көмекші</h3>
        <p style="font-size: 0.8rem; color: #8b949e;">Сұрақтар: Нейротехнология деген не? / Мұғалімдер не істейді? / Марста не бар? / Энергия туралы айт.</p>
        <div class="chat-area" id="chat">
            <div class="msg bot-msg">Сәлем! Мен осы презентация бойынша көмекшімін. Маған сұрақ қой!</div>
        </div>
        <div class="input-group">
            <input type="text" id="userInp" placeholder="Сұрағыңызды жазыңыз...">
            <button class="send-btn" onclick="chat()">Жіберу</button>
        </div>
    </div>
</div>

<script>
    // Слайдер
    let idx = 0;
    const slides = document.querySelectorAll('.slide');
    function go(n) {
        slides[idx].classList.remove('active');
        idx = (idx + n + slides.length) % slides.length;
        slides[idx].classList.add('active');
    }

    // Бот логикасы
    const data = {
        "нейро": "Нейротехнологиялар ой күшімен құрылғыларды басқаруға және ақпаратты тез қабылдауға мүмкіндік береді.",
        "энергия": "ЖИ арқылы күн және жел энергиясы тиімді басқарылып, қалалар таза қуат алады.",
        "мұғалім": "ЖИ техникалық жұмыстарды істейді, ал мұғалімдер баланың шығармашылығына көңіл бөледі.",
        "марс": "Ай мен Марста адамдар үшін базалар салынып, алғашқы колониялар құрылуда.",
        "қауіпсіз": "Кванттық шифрлау деректеріңізді хакерлерден 100% қорғайды.",
        "сәлем": "Сәлем! Мен дайынмын. Сұрағыңды қоя бер."
    };

    function chat() {
        const inp = document.getElementById('userInp');
        const box = document.getElementById('chat');
        const text = inp.value.toLowerCase();
        if(!text) return;

        box.innerHTML += `<div class="msg user-msg">${inp.value}</div>`;
        
        let ans = "Кешіріңіз, слайдтарда бұл туралы ақпарат жоқ. Нейро, Марс немесе білім туралы сұрап көріңіз.";
        for(let key in data) {
            if(text.includes(key)) { ans = data[key]; break; }
        }

        setTimeout(() => {
            box.innerHTML += `<div class="msg bot-msg">${ans}</div>`;
            box.scrollTop = box.scrollHeight;
        }, 500);
        inp.value = "";
    }
</script>

</body>
</html>
