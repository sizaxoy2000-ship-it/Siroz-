<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Siroz Luxury</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Amiri:wght@700&family=Noto+Serif+Arabic:wght@300;700&display=swap');

        :root {
            --royal-blue: #0a192f;
            --gold: #C5A059;
            --off-white: #FDFBF8;
            --dark-bg: #050a12;
        }

        body {
            background-color: var(--dark-bg);
            margin: 0;
            font-family: 'Noto Serif Arabic', serif;
            color: var(--off-white);
            display: flex;
            justify-content: center;
        }

        .container {
            width: 100%;
            max-width: 400px;
            background: linear-gradient(180deg, var(--royal-blue) 0%, var(--dark-bg) 100%);
            min-height: 100vh;
            padding: 40px 20px;
            text-align: center;
            border: 1px solid rgba(197, 160, 89, 0.2);
        }

        h1 {
            font-family: 'Amiri', serif;
            color: var(--off-white); /* اللون السكري الملكي */
            font-size: 3.5rem;
            letter-spacing: 8px;
            margin-bottom: 5px;
        }

        .tagline {
            color: var(--gold);
            font-size: 0.9rem;
            margin-bottom: 40px;
            letter-spacing: 1px;
        }

        .card {
            background: rgba(255, 255, 255, 0.03);
            border: 1px solid rgba(197, 160, 89, 0.1);
            border-radius: 15px;
            padding: 25px;
            margin-bottom: 25px;
        }

        /* تنسيق الصور لتظهر بدلاً من الإيموجي */
        .royal-icon {
            width: 60px;
            height: 60px;
            margin-bottom: 15px;
            filter: drop-shadow(0 0 5px rgba(197, 160, 89, 0.5));
        }

        footer {
            margin-top: 50px;
            font-size: 0.8rem;
            color: var(--gold);
            opacity: 0.7;
        }
    </style>
</head>
<body>

<div class="container">
    <h1>SIROZ</h1>
    <p class="tagline">جمالٌ ملكي، يقينٌ راسخ</p>

    <div class="card">
        <img src="https://raw.githubusercontent.com/Sebil-it/Siroz-/main/6914.png" class="royal-icon" alt="Moon">
        <h3 style="color: var(--gold)">سكون الروح</h3>
        <p>طمأنينة القلب التي تبدأ من عمق السجود، لأن ما قُدّر لكِ لن يخطئكِ.</p>
    </div>

    <div class="card">
        <img src="https://raw.githubusercontent.com/Sebil-it/Siroz-/main/6916.png" class="royal-icon" alt="Lotus">
        <h3 style="color: var(--gold)">جوهر النضارة</h3>
        <p>أسرار العناية الملكية بالبشرة، دليلكِ الاحترافي للديرمابن وزيت الورد.</p>
    </div>

    <div class="card">
        <img src="https://raw.githubusercontent.com/Sebil-it/Siroz-/main/6915.png" class="royal-icon" alt="Star">
        <h3 style="color: var(--gold)">قواعد الرّقي</h3>
        <p>الأناقة الهادئة وفلسفة البساطة الراقية.. لتكوني دائماً في كامل فخامتكِ.</p>
    </div>

    <footer>
        تصميم مهندسة IT - زاخو 2026<br>
        "Hasbi Allah wa ni'ma al-wakeel"
    </footer>
</div>

</body>
</html>
            box-sizing: border-box;
        }

        h1 { 
            font-family: 'Amiri', serif; 
            color: #C5A059; 
            font-size: 2.8rem; letter-spacing: 10px; 
            margin: 0 0 10px; text-transform: uppercase;
        }

        .tagline { color: #ffffff; font-size: 1rem; margin-bottom: 50px; }

        .card { 
            background: rgba(255, 255, 255, 0.02); 
            border: 1px solid rgba(197, 160, 89, 0.2); 
            border-radius: 15px; padding: 20px; 
            margin-bottom: 25px; display: flex; align-items: center; text-align: right;
        }

        .icon-img { 
            width: 65px; height: 65px; 
            margin-left: 15px; border-radius: 50%;
        }

        .card-content { flex: 1; }
        h3 { color: #C5A059; margin: 0 0 5px 0; font-size: 1.2rem; }
        p { color: #ced4da; font-size: 0.9rem; margin: 0 0 10px 0; line-height: 1.6; }

        .click-link {
            color: #C5A059; text-decoration: none; 
            font-size: 0.85rem; font-weight: bold;
            border: 1px solid #C5A059; padding: 4px 12px; border-radius: 5px;
        }

        footer { margin-top: 40px; font-size: 0.8rem; color: #C5A059; opacity: 0.7; }
    </style>
</head>
<body>

<div class="main">
    <h1>SIROZ</h1>
    <p class="tagline">جوانیێ شاهانە، یەقینێ ڕاستەقینە</p>

    <div class="card">
        <img src="https://raw.githubusercontent.com/Sebil-it/Siroz-/main/6914.png" class="icon-img">
        <div class="card-content">
            <h3>ئارامیا دل</h3>
            <p>ئارامیا دلێ کو ژ عومقێ سوجدێ دەستپێدکەت.</p>
            <a href="#" class="click-link">کلیک بکە</a>
        </div>
    </div>

    <div class="card">
        <img src="https://raw.githubusercontent.com/Sebil-it/Siroz-/main/6916.png" class="icon-img">
        <div class="card-content">
            <h3>جەوهەرێ جوانیێ</h3>
            <p>نهێنیێن خودانکرنا شاهانە بۆ پیستی و دێرمابەنێ.</p>
            <a href="#" class="click-link">کلیک بکە</a>
        </div>
    </div>

    <div class="card">
        <img src="https://raw.githubusercontent.com/Sebil-it/Siroz-/main/6915.png" class="icon-img">
        <div class="card-content">
            <h3>بنەمايێن ڕەوشەنبیریێ</h3>
            <p>ئەناقەتا هێمن و فەلسەفەیا سادەیا بەرز.</p>
            <a href="#" class="click-link">کلیک بکە</a>
        </div>
    </div>

    <footer>
        ZAKHO 2026 | "Hasbi Allah"
    </footer>
</div>

</body>
</html>
        <h3>قواعد الرّقي</h3>
        <p>الأناقة الهادئة وفلسفة البساطة الراقية.</p>
    </div>

</body>
</html>
