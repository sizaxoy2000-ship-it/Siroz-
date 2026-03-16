<!DOCTYPE html>
<html lang="ku" dir="rtl">
<head>
    <meta charset="UTF-8">
    <title>Siroz Luxury</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Amiri:wght@700&family=Noto+Serif+Kurdish:wght@300;700&display=swap');
        body { background: #050a12; color: #ffffff; font-family: 'Noto Serif Kurdish', serif; margin: 0; padding: 0; display: flex; justify-content: center; }
        .main { background: #050a12; width: 100%; max-width: 400px; min-height: 100vh; padding: 60px 20px; box-sizing: border-box; }
        .brand-name { font-family: 'Amiri', serif; color: #C5A059; font-size: 3.2rem; letter-spacing: 12px; margin-bottom: 50px; text-align: center; }
        .card { background: rgba(255, 255, 255, 0.02); border: 1px solid rgba(197, 160, 89, 0.2); border-radius: 15px; padding: 25px; margin-bottom: 30px; display: flex; align-items: center; text-align: right; }
        .img-box { display: flex; flex-direction: column; align-items: center; margin-left: 15px; min-width: 80px; }
        .icon-img { width: 65px; height: 65px; margin-bottom: 5px; }
        .img-label { color: #C5A059; font-size: 0.6rem; letter-spacing: 1px; font-family: sans-serif; font-weight: bold; }
        .content { flex: 1; }
        h3 { color: #C5A059; margin: 0 0 8px 0; font-size: 1.3rem; }
        p { color: #ced4da; font-size: 0.95rem; margin: 0 0 15px 0; line-height: 1.7; }
        .btn-link { color: #C5A059; text-decoration: none; font-size: 0.85rem; border: 1px solid #C5A059; padding: 4px 12px; border-radius: 4px; }
        footer { margin-top: 50px; font-size: 0.8rem; color: #C5A059; opacity: 0.6; text-align: center; }
    </style>
</head>
<body>
<div class="main">
    <h1 class="brand-name">SIROZ</h1>
    <div class="card">
        <div class="img-box">
            <img src="https://raw.githubusercontent.com/Sebil-it/Siroz-/main/6914.png" class="icon-img">
            <span class="img-label">SIROZ IMAGE</span>
        </div>
        <div class="content">
            <h3>ئارامیا دل</h3>
            <p>ئارامیا دلێ کو ژ عومقێ سوجدێ دەستپێدکەت.</p>
            <a href="#" class="btn-link">کلیک بکە</a>
        </div>
    </div>
    <div class="card">
        <div class="img-box">
            <img src="https://raw.githubusercontent.com/Sebil-it/Siroz-/main/6916.png" class="icon-img">
            <span class="img-label">SIROZ IMAGE</span>
        </div>
        <div class="content">
            <h3>جەوهەرێ جوانیێ</h3>
            <p>نهێنیێن خودانکرنا شاهانە بۆ پیستی.</p>
            <a href="#" class="btn-link">کلیک بکە</a>
        </div>
    </div>
    <div class="card">
        <div class="img-box">
            <img src="https://raw.githubusercontent.com/Sebil-it/Siroz-/main/6915.png" class="icon-img">
            <span class="img-label">SIROZ IMAGE</span>
        </div>
        <div class="content">
            <h3>بنەمايێن ڕەوشەنبیریێ</h3>
            <p>ئەناقەتا هێمن و فەلسەفەیا سادە.</p>
            <a href="#" class="btn-link">کلیک بکە</a>
        </div>
    </div>
    <footer>ZAKHO 2026 | Hasbi Allah</footer>
</div>
</body>
</html>
            box-sizing: border-box;
            border: 1px solid rgba(197, 160, 89, 0.1);
        }

        /* اسم سيروز الذهبي الملكي */
        .brand-name { 
            font-family: 'Amiri', serif; 
            color: #C5A059; 
            font-size: 3.2rem; letter-spacing: 12px; 
            margin: 0 0 50px 0; text-transform: uppercase;
            text-shadow: 0 0 15px rgba(197, 160, 89, 0.2);
        }

        .features {
            display: flex;
            flex-direction: column;
            gap: 30px;
        }

        .feature-card { 
            background: rgba(255, 255, 255, 0.02); 
            border: 1px solid rgba(197, 160, 89, 0.2); 
            border-radius: 15px; padding: 25px; 
            display: flex; align-items: center; text-align: right;
            transition: 0.3s;
        }

        .feature-card:hover {
            transform: translateY(-3px);
            border-color: #C5A059;
            box-shadow: 0 5px 20px rgba(0,0,0,0.5);
        }

        /* الأيقونات الذهبية المدمجة (Medium) */
        .icon-box {
            display: flex; flex-direction: column;
            align-items: center; margin-left: 20px;
            min-width: 80px;
        }

        .gold-icon { 
            width: 65px; height: 65px; 
            margin-bottom: 8px;
            filter: drop-shadow(0 0 8px rgba(197, 160, 89, 0.5));
        }

        .icon-label {
            color: #C5A059; font-size: 0.65rem;
            letter-spacing: 2px; font-family: sans-serif;
            font-weight: bold;
        }

        .content { flex: 1; }
        h3 { color: #C5A059; margin: 0 0 8px 0; font-size: 1.3rem; }
        p { color: #ced4da; font-size: 0.95rem; margin: 0 0 15px 0; line-height: 1.7; }

        .btn-link {
            color: #C5A059; text-decoration: none; 
            font-size: 0.85rem; border: 1px solid #C5A059;
            padding: 5px 15px; border-radius: 4px;
            transition: 0.3s;
        }

        .btn-link:hover {
            background: #C5A059; color: #050a12;
        }

        footer { 
            margin-top: 60px; 
            font-size: 0.8rem; 
            color: #C5A059; 
            border-top: 1px solid rgba(197, 160, 89, 0.1); 
            padding-top: 25px;
            opacity: 0.8;
        }
    </style>
</head>
<body>

<div class="main">
    <h1 class="brand-name">SIROZ</h1>

    <div class="features">
        <div class="feature-card">
            <div class="icon-box">
                <svg class="gold-icon" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M12 2C10.6667 2.00001 9.33334 2.16667 8 2.5C12 3.5 14 7 14 11C14 15 12 18.5 8 19.5C9.33334 19.8333 10.6667 20 12 20C17.5228 20 22 15.5228 22 10C22 4.47715 17.5228 2 12 2Z" fill="#C5A059"/>
                    <path opacity="0.5" d="M12 2C6.47715 2 2 6.47715 2 12C2 17.5228 6.47715 22 12 22C13.3333 22 14.6667 21.8333 16 21.5C12 20.5 10 17 10 13C10 9 12 5.5 16 4.5C14.6667 4.16667 13.3333 4 12 4V2Z" fill="#C5A059"/>
                </svg>
                <span class="icon-label">SIROZ IMAGE</span>
            </div>
            <div class="content">
                <h3>ئارامیا دل</h3>
                <p>ئارامیا دلێ کو ژ عومقێ سوجدێ دەستپێدکەت.</p>
                <a href="#" class="btn-link">کلیک بکە</a>
            </div>
        </div>

        <div class="feature-card">
            <div class="icon-box">
                <svg class="gold-icon" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M12 22C12 22 8 18 8 13C8 8 12 4 12 4C12 4 16 8 16 13C16 18 12 22 12 22Z" fill="#C5A059"/>
                    <path opacity="0.7" d="M12 22C12 22 16 21 19 18C22 15 23 11 23 11C23 11 19 11 16 13C13 15 12 18 12 22Z" fill="#C5A059"/>
                    <path opacity="0.7" d="M12 22C12 22 8 21 5 18C2 15 1 11 1 11C1 11 5 11 8 13C11 15 12 18 12 22Z" fill="#C5A059"/>
                    <path opacity="0.4" d="M12 22C12 22 18 20 21 16C24 12 24 8 24 8C24 8 20 8 17 11C14 14 12 18 12 22Z" fill="#C5A059"/>
                    <path opacity="0.4" d="M12 22C12 22 6 20 3 16C0 12 0 8 0 8C0 8 4 8 7 11C10 14 12 18 12 22Z" fill="#C5A059"/>
                </svg>
                <span class="icon-label">SIROZ IMAGE</span>
            </div>
            <div class="content">
                <h3>جەوهەرێ جوانیێ</h3>
                <p>نهێنیێن خودانکرنا شاهانە بۆ پیستی.</p>
                <a href="#" class="btn-link">کلیک بکە</a>
            </div>
        </div>

        <div class="feature-card">
            <div class="icon-box">
                <svg class="gold-icon" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M12 0L14.7 8.3H23.5L16.4 13.5L19.1 21.8L12 16.6L4.9 21.8L7.6 13.5L0.5 8.3H9.3L12 0Z" fill="#C5A059"/>
                    <path opacity="0.3" d="M12 4L13.8 9.6H19.7L14.9 13L16.7 18.6L12 15.1L7.3 18.6L9.1 13L4.3 9.6H10.2L12 4Z" fill="#ffffff"/>
                </svg>
                <span class="icon-label">SIROZ IMAGE</span>
            </div>
            <div class="content">
                <h3>بنەمايێن ڕەوشەنبیریێ</h3>
                <p>ئەناقەتا هێمن و فەلسەفەیا سادە.</p>
                <a href="#" class="btn-link">کلیک بکە</a>
            </div>
        </div>
    </div>

    <footer>
        ZAKHO 2026 | Hasbi Allah
    </footer>
</div>

</body>
</html>
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .feature:hover {
            transform: scale(1.05);
            box-shadow: 0 10px 30px rgba(0,0,0,0.4);
            border-color: #C5A059;
        }

        /* حجم ميديم للأيقونات */
        .feature img {
            width: 75px; 
            height: 75px;
            margin-bottom: 5px;
        }

        /* كلمة IMAGE تحت الصورة */
        .img-label {
            color: #C5A059;
            font-size: 0.6rem;
            letter-spacing: 2px;
            font-family: sans-serif;
            margin-bottom: 15px;
        }

        .feature h3 {
            color: #C5A059; /* ذهبي سيروز */
            margin: 10px 0;
            font-family: 'Amiri', serif;
        }

        .feature p {
            color: #ffffff;
            font-size: 0.9rem;
            line-height: 1.6;
        }
    </style>
</head>
<body>

<div class="features">
    <div class="feature">
        <img src="https://raw.githubusercontent.com/Sebil-it/Siroz-/main/6914.png">
        <span class="img-label">SIROZ IMAGE</span>
        <h3>ئارامیا دل</h3>
        <p>ئارامیا دلێ کو ژ عومقێ سوجدێ دەستپێدکەت.</p>
    </div>

    <div class="feature">
        <img src="https://raw.githubusercontent.com/Sebil-it/Siroz-/main/6916.png">
        <span class="img-label">SIROZ IMAGE</span>
        <h3>جەوهەرێ جوانیێ</h3>
        <p>نهێنیێن خودانکرنا شاهانە بۆ پیستی و دێرمابەنێ.</p>
    </div>

    <div class="feature">
        <img src="https://raw.githubusercontent.com/Sebil-it/Siroz-/main/6915.png">
        <span class="img-label">SIROZ IMAGE</span>
        <h3>بنەمايێن ڕەوشەنبیریێ</h3>
        <p>ئەناقەتا هێمن و فەلسەفەیا سادەیا بەرز.</p>
    </div>
</div>

</body>
</html>
    border-color: #C5A059;
}

/* خطة الأيقونة الميديم مع كلمة IMAGE */
.feature img {
    width: 70px; /* حجم ميديم */
    height: 70px;
    margin-bottom: 5px;
}

.img-label {
    color: #C5A059;
    font-size: 0.65rem;
    letter-spacing: 2px;
    font-family: sans-serif;
    margin-bottom: 15px;
    font-weight: bold;
}

.feature h3 {
    color: #C5A059; /* ذهبي سيروز */
    margin: 10px 0;
    font-size: 1.3rem;
}

.feature p {
    color: #ffffff;
    font-size: 0.9rem;
    line-height: 1.6;
}
</style>

<div class="features">
    <div class="feature">
        <img src="https://raw.githubusercontent.com/Sebil-it/Siroz-/main/6914.png" alt="Siroz Image">
        <span class="img-label">SIROZ IMAGE</span>
        <h3>ئارامیا دل</h3>
        <p>ئارامیا دلێ کو ژ عومقێ سوجدێ دەستپێدکەت.</p>
    </div>

    <div class="feature">
        <img src="https://raw.githubusercontent.com/Sebil-it/Siroz-/main/6916.png" alt="Siroz Image">
        <span class="img-label">SIROZ IMAGE</span>
        <h3>جەوهەرێ جوانیێ</h3>
        <p>نهێنیێن خودانکرنا شاهانە بۆ پیستی و دێرمابەنێ.</p>
    </div>
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
