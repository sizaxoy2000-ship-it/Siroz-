<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Siroz Luxury Concept</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Amiri:wght@700&family=Noto+Serif+Arabic:wght@300;700&display=swap');

        :root {
            --royal-blue: #0a192f;
            --gold-primary: #C5A059;
            --dark-bg: #050a12;
        }

        body {
            background-color: var(--dark-bg);
            margin: 0;
            padding: 0;
            font-family: 'Noto Serif Arabic', serif;
            display: flex;
            justify-content: center;
            color: #FDFBF8;
        }

        .phone-view {
            width: 100%;
            max-width: 414px;
            background: linear-gradient(180deg, var(--royal-blue) 0%, var(--dark-bg) 100%);
            min-height: 100vh;
            padding: 40px 20px;
            border: 1px solid rgba(197, 160, 89, 0.2);
            box-sizing: border-box;
            text-align: center;
        }

        /* أيقونة الملكة العلوية 6917.png */
        .queen-logo {
            width: 120px;
            height: 120px;
            margin: 0 auto 25px;
            border: 1.5px solid var(--gold-primary);
            border-radius: 50%;
            background-image: url('6917.png'); 
            background-size: cover;
            background-position: center;
        }

        h1 {
            font-family: 'Amiri', serif;
            font-size: 3.5rem;
            color: var(--gold-primary);
            margin: 0;
            letter-spacing: 12px;
            text-transform: uppercase;
        }

        .tagline {
            color: #E5C789;
            font-size: 0.9rem;
            margin-bottom: 45px;
            font-weight: 300;
            letter-spacing: 1px;
        }

        .card {
            background: rgba(255, 255, 255, 0.03);
            border: 1px solid rgba(197, 160, 89, 0.15);
            border-radius: 12px;
            padding: 30px 20px;
            margin-bottom: 25px;
            transition: 0.3s;
        }

        /* حجم الأيقونات الذهبية (الهلال، اللوتس، النجمة) */
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
    <div class="queen-logo"></div>
    
    <h1>SIROZ</h1>
    <div class="tagline">جمالٌ ملكي، يقينٌ راسخ، ورُقي لا يغيب</div>

    <div class="card">
        <img src="6914.png" alt="Moon" class="royal-icon">
        <h3>سكون الروح</h3>
        <p>مساحتكِ لأوراد الفجر، أذكار اليقين، وطمأنينة القلب التي تبدأ من عمق السجود.</p>
    </div>

    <div class="card">
        <img src="6916.png" alt="Lotus" class="royal-icon">
        <h3>جوهر النضارة</h3>
        <p>أسرار العناية الملكية بالبشرة، دليلكِ الاحترافي للديرمابن، وسحر الزيوت الطبيعية.</p>
    </div>

    <div class="card">
        <img src="6915.png" alt="Star" class="royal-icon">
        <h3>قواعد الرُقي</h3>
        <p>الأناقة الهادئة وفلسفة البساطة الراقية.. لتكوني دائماً في كامل فخامتكِ بأبسط التفاصيل.</p>
    </div>

    <footer>
        بأيدي مهندسة IT - زاخو 2026<br>
        "Hasbi Allah wa ni'ma al-wakeel"
    </footer>
</div>

</body>
</html>
