<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Siroz Luxury</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Amiri:wght@700&family=Noto+Serif+Arabic:wght@300;700&family=Noto+Serif+Kurdish:wght@300;700&display=swap');

        :root {
            --royal-blue: #0a192f;
            --gold-primary: #C5A059;
            --dark-bg: #050a12;
            /* اللون السكري الجديد */
            --off-white: #FDFBF8; 
        }

        body {
            background-color: var(--dark-bg);
            margin: 0;
            padding: 0;
            font-family: 'Noto Serif Arabic', serif;
            color: var(--off-white);
            display: flex;
            justify-content: center;
            min-height: 100vh;
        }

        .phone-container {
            width: 100%;
            max-width: 400px;
            background: linear-gradient(180deg, var(--royal-blue) 0%, var(--dark-bg) 100%);
            min-height: 100vh;
            padding: 40px 20px;
            border: 1px solid rgba(197, 160, 89, 0.2);
            text-align: center;
            position: relative;
        }

        #lang-btn {
            position: absolute;
            top: 20px;
            left: 20px;
            background: rgba(197, 160, 89, 0.1);
            color: var(--gold-primary);
            border: 1px solid var(--gold-primary);
            padding: 5px 15px;
            border-radius: 20px;
            cursor: pointer;
            font-family: 'Noto Serif Kurdish', serif;
            z-index: 10;
        }

        h1 {
            font-family: 'Amiri', serif;
            /* تغيير اللون هنا إلى السكري */
            color: var(--off-white); 
            font-size: 3.5rem;
            letter-spacing: 10px;
            margin: 40px 0 10px;
        }

        .card {
            background: rgba(255, 255, 255, 0.03);
            border: 1px solid rgba(197, 160, 89, 0.1);
            border-radius: 15px;
            padding: 25px;
            margin-bottom: 20px;
            transition: 0.3s;
        }

        .icon-gold {
            font-size: 2.5rem;
            color: var(--gold-primary);
            margin-bottom: 15px;
            display: block;
        }

        .ku-text { display: none; font-family: 'Noto Serif Kurdish', serif; }

        footer {
            margin-top: 40px;
            font-size: 0.8rem;
            color: var(--gold-primary);
            border-top: 1px solid rgba(197, 160, 89, 0.1);
            padding-top: 20px;
        }
    </style>
</head>
<body>

<div class="phone-container">
    <button id="lang-btn" onclick="toggleLang()">کوردی</button>
    
    <h1>SIROZ</h1>
    <p class="ar-text" style="color: #E5C789;">جمالٌ ملكي، يقينٌ راسخ</p>
    <p class="ku-text" style="color: #E5C789;">جوانیێ شاهانە، یەقینێ ڕاستەقینە</p>

    <div class="card">
        <span class="icon-gold">🌙</span>
        <h3 class="ar-text">سكون الروح</h3>
        <h3 class="ku-text">ئارامیا دل</h3>
        <p class="ar-text">طمأنينة القلب التي تبدأ من عمق السجود، لأن ما قُدّر لكِ لن يخطئكِ.</p>
        <p class="ku-text">ئارامیا دلێ کو ژ عومقێ سوجدێ دەستپێدکەت، چونکی یێ بۆ تە هاتیە نڤیسین ژ تە ناچیت.</p>
    </div>

    <div class="card">
        <span class="icon-gold">🪷</span>
        <h3 class="ar-text">جوهر النضارة</h3>
        <h3 class="ku-text">جەوهەرێ جوانیێ</h3>
        <p class="ar-text">أسرار العناية الملكية بالبشرة، دليلكِ للديرمابن وزيت الورد.</p>
        <p class="ku-text">نهێنیێن خودانکرنا شاهانە بۆ پیستی، رێبەرێ تە بۆ دێرمابەنێ و زەیتا گولێ.</p>
    </div>

    <footer>
        بأيدي مهندسة IT - زاخو 2026<br>
        "Hasbi Allah wa ni'ma al-wakeel"
    </footer>
</div>

<script>
    function toggleLang() {
        const arElements = document.querySelectorAll('.ar-text');
        const kuElements = document.querySelectorAll('.ku-text');
        const btn = document.getElementById('lang-btn');

        arElements.forEach(el =>
    left: 20px;
            background: rgba(197, 160, 89, 0.1);
            color: var(--gold-primary);
            border: 1px solid var(--gold-primary);
            padding: 8px 15px;
            border-radius: 20px;
            font-size: 0.8rem;
            cursor: pointer;
            font-family: 'Noto Serif Kurdish', serif;
            transition: 0.3s;
        }

        #lang-toggle:hover {
            background: rgba(197, 160, 89, 0.2);
            box-shadow: 0 0 10px rgba(197, 160, 89, 0.3);
        }

        h1 {
            font-family: 'Amiri', serif;
            font-size: 3.5rem;
            color: var(--gold-primary);
            margin: 20px 0 0 0;
            letter-spacing: 12px;
            text-transform: uppercase;
        }

        .tagline {
            color: #E5C789;
            font-size: 0.9rem;
            margin-bottom: 45px;
            font-weight: 300;
        }

        .card {
            background: rgba(255, 255, 255, 0.03);
            border: 1px solid rgba(197, 160, 89, 0.15);
            border-radius: 12px;
            padding: 30px 20px;
            margin-bottom: 25px;
            transition: 0.3s;
        }

        /* حجم الأيقونات الذهبية (الهلال، اللوتس) */
        .royal-icon {
            width: 45px;
            height: 45px;
            margin-bottom: 15px;
        }

        h3 {
            color: var(--gold-primary);
            margin: 0 0 12px 0;
            font-size: 1.5rem;
            font-weight: 700;
        }

        p {
            font-size: 0.95rem;
            line-height: 1.8;
            color: #b0b8c1;
            margin: 0;
        }

        /* تنسيق النصوص الكوردية */
        .ku-text {
            font-family: 'Noto Serif Kurdish', serif;
            display: none; /* مخفية افتراضياً */
        }

        footer {
            margin-top: 60px;
            font-size: 0.8rem;
            color: var(--gold-primary);
            border-top: 1px solid rgba(197, 160, 89, 0.1);
            padding-top: 25px;
            letter-spacing: 1px;
        }
    </style>
</head>
<body>

<div class="phone-view">
    <button id="lang-toggle" onclick="toggleLanguage()">کوردی</button>
    
    <h1>SIROZ</h1>
    <div class="tagline">جمالٌ ملكي، يقينٌ راسخ، ورُقي لا يغيب</div>

    <div class="card">
        <img src="6914.png" alt="Moon" class="royal-icon">
        <h3>سكون الروح</h3>
        <p class="ar-text">مساحتكِ لأوراد الفجر، أذكار اليقين، وطمأنينة القلب التي تبدأ من عمق السجود.</p>
        <p class="ku-text">فەزایێ تە بۆ وێردێن فەجرێ، ئەزکارێن یەقینێ، و ئار
