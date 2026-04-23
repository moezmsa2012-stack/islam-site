# islam-site
🌙 الموسوعة الإسلامية الشاملة 🌙  القرآن الكريم كاملاً + الأحاديث الصحيحة من المصادر الموثوقة
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>القرآن الكريم والحديث الشريف - النسخة المتكاملة</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body {
            font-family: 'Arial', Tahoma, sans-serif;
            line-height: 1.6;
            color: #333;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        .header {
            background: rgba(255,255,255,0.95);
            padding: 30px;
            border-radius: 20px;
            text-align: center;
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
            margin-bottom: 30px;
        }
        .header h1 {
            color: #1e3c72;
            font-size: 2.5rem;
            margin-bottom: 15px;
        }
        .links-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 25px;
            margin-bottom: 40px;
        }
        .link-card {
            background: white;
            padding: 30px;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.15);
            transition: all 0.3s ease;
            text-align: center;
            border-top: 5px solid #1e3c72;
            cursor: pointer;
        }
        .link-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 20px 40px rgba(0,0,0,0.25);
        }
        .link-card h3 {
            color: #1e3c72;
            font-size: 1.5rem;
            margin-bottom: 15px;
        }
        .link-card p {
            color: #666;
            margin-bottom: 20px;
        }
        .external-link {
            display: inline-block;
            background: linear-gradient(45deg, #28a745, #20c997);
            color: white;
            padding: 15px 30px;
            text-decoration: none;
            border-radius: 50px;
            font-weight: bold;
            font-size: 1.1rem;
            transition: all 0.3s;
            box-shadow: 0 5px 15px rgba(40,167,69,0.4);
        }
        .external-link:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 25px rgba(40,167,69,0.6);
            color: white;
            text-decoration: none;
        }
        .quran-link {
            background: linear-gradient(45deg, #007bff, #0056b3) !important;
            box-shadow: 0 5px 15px rgba(0,123,255,0.4) !important;
        }
        .quran-link:hover { box-shadow: 0 10px 25px rgba(0,123,255,0.6) !important; }
        .hadith-link {
            background: linear-gradient(45deg, #ffc107, #e0a800) !important;
            color: #212529 !important;
            box-shadow: 0 5px 15px rgba(255,193,7,0.4) !important;
        }
        .hadith-link:hover { 
            box-shadow: 0 10px 25px rgba(255,193,7,0.6) !important; 
            color: #212529 !important;
        }
        .features {
            background: rgba(255,255,255,0.95);
            padding: 40px;
            border-radius: 20px;
            text-align: center;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
        }
        .features h2 {
            color: #1e3c72;
            margin-bottom: 30px;
            font-size: 2rem;
        }
        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }
        .feature-item {
            padding: 20px;
            background: linear-gradient(135deg, #f8f9ff, #e8f0ff);
            border-radius: 15px;
            border-right: 5px solid #1e3c72;
        }
        .footer {
            background: rgba(0,0,0,0.8);
            color: white;
            text-align: center;
            padding: 30px;
            margin-top: 50px;
            border-radius: 20px 20px 0 0;
        }
        @media (max-width: 768px) {
            .links-grid { grid-template-columns: 1fr; }
            .header h1 { font-size: 2rem; }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>🌙 الموسوعة الإسلامية الشاملة 🌙</h1>
            <p>القرآن الكريم كاملاً + الأحاديث الصحيحة من المصادر الموثوقة</p>
        </div>

        <div class="links-grid">
            <!-- القرآن الكريم -->
            <div class="link-card">
                <h3>📖 القرآن الكريم كاملاً</h3>
                <p>114 سورة - 6236 آية - مع التفسير والتلاوة الصوتية</p>
                <a href="https://quran.com/ar" class="external-link quran-link" target="_blank">
                    افتح القرآن الكريم كاملاً
                </a>
            </div>

            <!-- القرآن بصوت مشاري -->
            <div class="link-card">
                <h3>🎵 القرآن بتلاوة مشاري العفاسي</h3>
                <p>تلاوة تجمل القلب - كل السور بجودة عالية</p>
                <a href="https://quran.ksu.edu.sa/index.php#aya=1_1&m=hafs" class="external-link quran-link" target="_blank">
                    استمع للقرآن كاملاً
                </a>
            </div>

            <!-- صحيح البخاري -->
            <div class="link-card">
                <h3>✅ صحيح البخاري كامل</h3>
                <p>أصح كتاب بعد القرآن - 7000+ حديث</p>
                <a href="https://sunnah.com/bukhari" class="external-link hadith-link" target="_blank">
                    اقرأ صحيح البخاري
                </a>
            </div>

            <!-- صحيح مسلم -->
            <div class="link-card">
                <h3>✅ صحيح مسلم كامل</h3>
                <p>ثاني أصح كتاب - 7000+ حديث نبوي</p>
                <a href="https://sunnah.com/muslim" class="external-link hadith-link" target="_blank">
                    اقرأ صحيح مسلم
                </a>
            </div>

            <!-- الجامع الكبير -->
            <div class="link-card">
                <h3>📚 السنة النبوية كاملة</h3>
                <p>كل الأحاديث الصحيحة من 6 كتب موثوقة</p>
                <a href="https://sunnah.com/" class="external-link quran-link" target="_blank">
                    كل الأحاديث الصحيحة
                </a>
            </div>

            <!-- تفسير القرآن -->
            <div class="link-card">
                <h3>💡 تفسير القرآن الكريم</h3>
                <p>تفسير الطبري + ابن كثير + الجلالين</p>
                <a href="https://quran.ksu.edu.sa/tafseer/" class="external-link quran-link" target="_blank">
                    تفسير شامل للقرآن
                </a>
            </div>

            <!-- إسلام ويب -->
            <div class="link-card">
                <h3>❓ فتاوى إسلامية موثوقة</h3>
                <p>إسلام ويب - أكبر موقع فتاوى</p>
                <a href="https://www.islamweb.net/ar/" class="external-link" target="_blank">
                    فتاوى من العلماء
                </a>
            </div>

            <!-- الإسلام سؤال وجواب -->
            <div class="link-card">
                <h3>📖 إسلام سؤال وجواب</h3>
                <p>أكثر من مليون فتوى من الشيخ ابن باز وصالح الفوزان</p>
                <a href="https://islamqa.info/ar" class="external-link" target="_blank">
                    إسلام سؤال وجواب
                </a>
            </div>
        </div>

        <div class="features">
            <h2>✨ مميزات هذه الروابط</h2>
            <div class="features-grid">
                <div class="feature-item">
                    <h4>✅ مصادر موثوقة 100%</h4>
                    <p>مواقع رسمية معتمدة من العلماء</p>
                </div>
                <div class="feature-item">
                    <h4>🎵 تلاوة صوتية</h4>
                    <p>أشهر القراء بجودة HD</p>
                </div>
                <div class="feature-item">
                    <h4>🔍 بحث ذكي</h4>
                    <p>ابحث في القرآن والحديث بثواني</p>
                </div>
                <div class="feature-item">
                    <h4>📱 متجاوب</h4>
                    <p>يعمل على الموبايل والكمبيوتر</p>
                </div>
                <div class="feature-item">
                    <h4>💾 حفظ ومشاركة</h4>
                    <p>احفظ الآيات والأحاديث المفضلة</p>
                </div>
                <div class="feature-item">
                    <h4>🌍 متعدد اللغات</h4>
                    <p>العربية + الإنجليزية + ترجمات</p>
                </div>
            </div>
        </div>

        <div class="footer">
            <h3>بِسْمِ اللَّهِ الرَّحْمَٰنِ الرَّحِيمِ</h3>
            <p>جميع الروابط من مصادر إسلامية موثوقة ✅</p>
            <p>احفظ هذه الصفحة للوصول السريع للقرآن والسنة</p>
        </div>
    </div>

    <script>
        // إضافة تأثيرات تفاعلية
        document.querySelectorAll('.link-card').forEach(card => {
            card.addEventListener('click', function(e) {
                const link = this.querySelector('.external-link');
                if (link) {
                    // تأثير صوتي بسيط
                    const audio = new Audio('data:audio/wav;base64,UklGRnoGAABXQVZFZm10IBAAAAABAAEAQB8AAEAfAAABAAgAZGF0YQoGAACBhYqFbF1fdJivrJBhNjVgodDbq2EcBj+a2/LDciUFLIHO8tiJNwgZaLvt559NEAxQp+PwtmMcBjiR1/LMeSwFJHfH8N2QQAo');
                    audio.play().catch(() => {});
                    // فتح الرابط بعد ثانية صغيرة
                    setTimeout(() => {
                        window.open(link.href, '_blank');
                    }, 200);
                }
            });
        });

        // رسالة ترحيب
        setTimeout(() => {
            if (confirm('هل تريد حفظ هذه الصفحة للوصول السريع للقرآن والحديث؟')) {
                // حفظ كـ Bookmark
                const bookmarkUrl = window.location.href;
                const bookmarkTitle = 'الموسوعة الإسلامية الشاملة';
                if (window.sidebar && window.sidebar.addPanel) {
                    window.sidebar.addPanel(bookmarkTitle, bookmarkUrl, '');
                } else if (document.all && window.external) {
                    window.external.AddFavorite(bookmarkUrl, bookmarkTitle);
                } else {
                    alert('اضغط Ctrl+D لحفظ الصفحة في المفضلة');
                }
            }
        }, 3000);
    </script>
</body>
</html>
