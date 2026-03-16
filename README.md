<!DOCTYPE html>
<html lang="ku" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Siroz Luxury</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Amiri:wght@700&family=Noto+Serif+Kurdish:wght@300;700&display=swap');
        
        body { 
            background: #050a12; 
            color: #ffffff; 
            font-family: 'Noto Serif Kurdish', serif; 
            text-align: center; 
            margin: 0; padding: 0; 
            display: flex; justify-content: center;
        }

        .main { 
            background: #050a12; 
            width: 100%; max-width: 400px;
            min-height: 100vh; padding: 60px 20px; 
            border: 1px solid rgba(197, 160, 89, 0.2);
            box-sizing: border-box;
        }

        /* اسم سيروز باللون الذهبي الملكي */
        .brand-name { 
            font-family: 'Amiri', serif; 
            color: #C5A059; 
            font-size: 3.2rem; letter-spacing: 12px; 
            margin: 0; text-transform: uppercase;
            text-shadow: 0 0 10px rgba(197, 160, 89, 0.2);
        }

        .tagline { 
            color: #ffffff; 
            font-size: 1rem; 
            margin-top: 10px; 
            margin-bottom: 50px; 
            opacity: 0.9;
        }

        .card { 
            background: rgba(255, 255, 255, 0.02); 
            border: 1px solid rgba(197, 160, 89, 0.2); 
            border-radius: 15px; padding: 25px; 
            margin-bottom: 30px; display: flex; align-items: center; text-align: right;
        }

        /* تنفيذ خطة الصور مع الكلمة التوضيحية */
        .image-section {
            display: flex;
            flex-direction: column;
            align-items: center;
            margin-left: 20px;
            min-width: 80px;
        }

        .icon-img { 
            width: 65px; 
            height: 65px; 
            margin-bottom: 8px;
            filter: drop-shadow(0 0 5px rgba(197, 160, 89, 0.3));
        }

        .image-label {
            color: #C5A059;
            font-size: 0.65rem;
            letter-spacing: 2px;
            font-family: sans-serif;
            font-weight: bold;
        }

        .card-content { flex: 1; }
        h3 { color: #C5A059; margin: 0 0 8px 0; font-size: 1.3rem; }
        p { color: #ced4da; font-size: 0.95rem; margin: 0 0 15px 0; line-height: 1.7; }

        .link-btn {
            color: #C5A059; 
            text-decoration: none; 
            font-size: 0.85rem; 
            border: 1px solid #C5A059;
            padding: 5px 15px;
            border-radius: 4px;
            transition: 0.3s;
        }

        footer { 
            margin-top: 60px; 
            font-size: 0.8rem; 
            color: #C5A059; 
            border-top: 1px solid rgba(197, 160, 89, 0.1); 
            padding-top: 25px;
        }
    </style>
</head>
<body>

<div class="main">
    <h1 class="brand-name">SIROZ</h1>
    <p class="tagline">جوانیێ شاهانە، یەقینێ ڕاستەقینە</p>

    <div class="card">
        <div class="image-section">
            <img src="https://raw.githubusercontent.com/Sebil-it/Siroz-/main/6914.png" class="icon-img">
            <span class="image-label">SIROZ IMAGE</span>
        </div>
        <div class="card-content">
            <h3>ئارامیا دل</h3>
            <p>ئارامیا دلێ کو ژ عومقێ سوجدێ دەستپێدکەت.</p>
            <a href="#" class="link-btn">کلیک بکە</a>
        </div>
    </div>

    <div class="card">
        <div class="image-section">
            <img src="https://raw.githubusercontent.com/Sebil-it/Siroz-/main/6916.png" class="icon-img">
            <span class="image-label">SIROZ IMAGE</span>
        </div>
        <div class="card-content">
            <h3>جەوهەرێ جوانیێ</h3>
            <p>نهێنیێن خودانکرنا شاهانە بۆ پیستی و دێرمابەنێ.</p>
            <a href="#" class="link-btn">کلیک بکە</a>
        </div>
    </div>

    <div class="card">
        <div class="image-section">
            <img src="https://raw.githubusercontent.com/Sebil-it/Siroz-/main/6915.png" class="icon-img">
            <span class="image-label">SIROZ IMAGE</span>
        </div>
        <div class="card-content">
            <h3>بنەمايێن ڕەوشەنبیریێ</h3>
            <p>ئەناقەتا هێمن و فەلسەفەیا سادەیا بەرز.</p>
            <a href="#" class="link-btn">کلیک بکە</a>
        </div>
    </div>

    <footer>
        ZAKHO 2026 <br>
        "Hasbi Allah wa ni'ma al-wakeel"
    </footer>
</div>

</body>
</html>
            box-sizing: border-box;
        }

        /* الاسم الذهبي الملكي */
        .brand-name { 
            font-family: 'Amiri', serif; 
            color: #C5A059; 
            font-size: 3rem; letter-spacing: 12px; 
            margin: 0; text-transform: uppercase;
        }

        .tagline { color: #ffffff; font-size: 1rem; margin-top: 10px; margin-bottom: 50px; }

        .card { 
            background: rgba(255, 255, 255, 0.02); 
            border: 1px solid rgba(197, 160, 89, 0.2); 
            border-radius: 15px; padding: 25px; 
            margin-bottom: 30px; display: flex; align-items: center; text-align: right;
        }

        /* أيقونات الخطة (Medium) */
        .icon-container {
            display: flex;
            flex-direction: column;
            align-items: center;
            margin-left: 20px;
        }

        .icon-img { 
            width: 65px; height: 65px; 
            margin-bottom: 5px;
        }

        .image-label {
            color: #C5A059;
            font-size: 0.7rem;
            letter-spacing: 1px;
            font-family: sans-serif;
        }

        .card-content { flex: 1; }
        h3 { color: #C5A059; margin: 0 0 8px 0; font-size: 1.3rem; }
        p { color: #ced4da; font-size: 0.95rem; margin: 0 0 15px 0; line-height: 1.7; }

        .click-link {
            color: #C5A059; text-decoration: none; 
            font-size: 0.85rem; border-bottom: 1px solid #C5A059;
            padding-bottom: 2px;
        }

        footer { margin-top: 50px; font-size: 0.8rem; color: #C5A059; opacity: 0.6; }
    </style>
</head>
<body>

<div class="main">
    <h1 class="brand-name">SIROZ</h1>
    <p class="tagline">جوانیێ شاهانە، یەقینێ ڕاستەقینە</p>

    <div class="card">
        <div class="icon-container">
            <img src="https://raw.githubusercontent.com/Sebil-it/Siroz-/main/6914.png" class="icon-img">
            <span class="image-label">SIROZ IMAGE</span>
        </div>
        <div class="card-content">
            <h3>ئارامیا دل</h3>
            <p>ئارامیا دلێ کو ژ عومقێ سوجدێ دەستپێدکەت.</p>
            <a href="#" class="click-link">کلیک بکە</a>
        </div>
    </div>

    <div class="card">
        <div class="icon-container">
            <img src="https://raw.githubusercontent.com/Sebil-it/Siroz-/main/6916.png" class="icon-img">
            <span class="image-label">SIROZ IMAGE</span>
        </div>
        <div class="card-content">
            <h3>جەوهەرێ جوانیێ</h3>
            <p>نهێنیێن خودانکرنا شاهانە بۆ پیستی و دێرمابەنێ.</p>
            <a href="#" class="click-link">کلیک بکە</a>
        </div>
    </div>

    <div class="card">
        <div class="icon-container">
            <img src="https://raw.githubusercontent.com/Sebil-it/Siroz-/main/6915.png" class="icon-img">
            <span class="image-label">SIROZ IMAGE</span>
        </div>
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
