<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Siroz Concept</title>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Serif+Arabic:wght@300;500;700&display=swap" rel="stylesheet">
    <style>
        /* تعريف الألوان: الكريمي #FDFBF8 والذهبي المطفي #C5A059 */
        body { 
            background-color: #FDFBF8; 
            font-family: 'Noto Serif Arabic', serif; 
            color: #4A4238; /* بني داكن هادئ */
            text-align: center; 
            padding: 0; 
            margin: 0;
            display: flex; justify-content: center; align-items: center; min-height: 100vh;
        }
        .container {
            width: 100%; max-width: 414px; /* عرض مثالي للموبايل */
            padding: 50px 25px;
        }
        header { margin-bottom: 60px; }
        .concept-tag { 
            font-size: 0.75rem; letter-spacing: 4px; color: #9A8C73; text-transform: uppercase; 
            margin-bottom: 10px; font-weight: 300;
        }
        h1 { 
            color: #C5A059; letter-spacing: 12px; text-transform: uppercase; 
            font-size: 3rem; margin: 0; font-weight: 700;
        }
        .tagline { 
            font-size: 0.85rem; color: #8B6B23; margin-top: 5px; font-weight: 300; 
        }
        .section-separator {
            width: 60px; height: 1px; background-color: #E0DCD5; margin: 40px auto;
        }
        .card { 
            background: #ffffff; 
            border-radius: 2px; /* زوايا حادة للفخامة البسيطة */
            padding: 35px 25px; 
            margin: 0 0 30px 0;
            border-left: 4px solid #C5A059; 
            box-shadow: 0 6px 20px rgba(0,0,0,0.03); /* ظل خفيف جداً */
            transition: 0.3s;
        }
        h3 { 
            margin: 0 0 15px 0; 
            color: #C5A059; font-size: 1.6rem; font-weight: 500;
        }
        p { 
            line-height: 2; font-size: 1rem; color: #6B6358; margin: 0; font-weight: 300; 
        }
        footer {
            margin-top: 80px; font-size: 0.75rem; color: #C5A059;
            border-top: 0.5px solid #E0DCD5; padding-top: 30px;
            letter-spacing: 1px;
        }
    </style>
</head>
<body>

    <div class="container">
        <header>
            <div class="concept-tag">CONCEPT</div>
            <h1>SIROZ</h1>
            <div class="tagline">جمال، يقين، ورُقي الملكة</div>
        </header>

        <div class="section-separator"></div>

        <div class="card">
            <h3>سكون الروح</h3>
            <p>مساحتكِ لأوراد الفجر، أذكار اليقين، وطمأنينة القلب التي تبدأ من عمق السجود، لأن ما قُدّر لكِ لن يخطئكِ.</p>
        </div>

        <div class="card">
            <h3>جوهر النضارة</h3>
            <p>أسرار العناية الملكية بالبشرة الجافة، دليلكِ الاحترافي للديرمابن، وسحر الزيوت الطبيعية (مثل زيت الورد) لجمالٍ دائم.</p>
        </div>

        <div class="card">
            <h3>قواعد الرُقي</h3>
            <p>الأناقة الهادئة وفلسفة 80/20.. لتكوني دائماً في كامل فخامتكِ الملكية بأبسط التفاصيل التي تعبر عن ذوقكِ الرفيع.</p>
        </div>

        <footer>
            بأيدي مهندسة IT - زاخو 2026<br>
            "ما كان لكِ لن يخطئكِ"
        </footer>
    </div>

</body>
</html>
