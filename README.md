<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>الأسئلة الشائعة - شات الاقصى</title>
    <meta name="description" content="الأسئلة الشائعة - إجابات على جميع استفساراتك حول استخدام شات الاقصى للجوال">
    <link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@400;700;800&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary: #2563eb;
            --primary-light: #3b82f6;
            --primary-dark: #1e40af;
            --secondary: #f97316;
            --bg: #fafafa;
            --card: #ffffff;
            --text: #1f2937;
            --text-light: #6b7280;
            --border: #e5e7eb;
            --shadow: rgba(37, 99, 235, 0.1);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            -webkit-user-select: none;
            -moz-user-select: none;
            -ms-user-select: none;
            user-select: none;
            -webkit-touch-callout: none;
        }

        body {
            font-family: 'Tajawal', sans-serif;
            background: linear-gradient(135deg, #fafafa 0%, #f3f4f6 100%);
            color: var(--text);
            line-height: 1.8;
            padding: 20px;
            min-height: 100vh;
        }

        .container {
            max-width: 1000px;
            margin: 0 auto;
        }

        .back-btn {
            display: inline-flex;
            align-items: center;
            gap: 10px;
            background: linear-gradient(135deg, var(--primary) 0%, var(--primary-light) 100%);
            color: white !important;
            padding: 12px 28px;
            border-radius: 30px;
            text-decoration: none;
            font-weight: 600;
            margin-bottom: 25px;
            transition: all 0.3s ease;
            box-shadow: 0 4px 15px var(--shadow);
        }

        .hero-section {
            background: linear-gradient(135deg, var(--primary) 0%, var(--secondary) 100%);
            color: white;
            padding: 60px 40px;
            border-radius: 25px;
            text-align: center;
            margin-bottom: 40px;
        }

        .card {
            background: var(--card);
            border-radius: 20px;
            padding: 30px;
            margin-bottom: 30px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.06);
            border: 1px solid var(--border);
        }

        .section-title {
            color: var(--primary);
            font-size: 1.8em;
            margin-bottom: 30px;
            padding-bottom: 15px;
            border-bottom: 3px solid var(--secondary);
            font-weight: 700;
        }

        .accordion-item {
            margin-bottom: 15px;
            border-radius: 15px;
            overflow: hidden;
            border: 1px solid var(--border);
        }

        .accordion-header {
            background: #f9fafb;
            padding: 18px 25px;
            cursor: pointer;
            display: flex;
            justify-content: space-between;
            align-items: center;
            font-weight: 700;
            color: var(--primary-dark);
            transition: 0.3s;
        }

        .accordion-header.active {
            background: linear-gradient(135deg, var(--primary) 0%, var(--secondary) 100%);
            color: white;
        }

        .accordion-content {
            background: white;
            max-height: 0;
            overflow: hidden;
            transition: all 0.4s cubic-bezier(0, 1, 0, 1);
            padding: 0 25px;
        }

        .accordion-content.open {
            max-height: 3000px; /* زيادة السعة لاستيعاب محتوى أكبر */
            padding: 25px;
            border-top: 1px solid var(--border);
            transition: all 0.4s ease-in;
        }

        .accordion-content h4 {
            color: var(--primary);
            margin-bottom: 10px;
            margin-top: 15px;
            border-right: 4px solid var(--secondary);
            padding-right: 10px;
        }

        .accordion-content p {
            margin-bottom: 15px;
            color: #4b5563;
        }

        .accordion-content hr {
            border: 0;
            border-top: 1px solid #eee;
            margin: 20px 0;
        }

        ul {
            list-style: none;
            padding-right: 15px;
        }

        ul li::before {
            content: "•";
            color: var(--secondary);
            font-weight: bold;
            display: inline-block; 
            width: 1em;
            margin-right: -1em;
        }

        .footer {
            text-align: center;
            padding: 40px;
            background: var(--card);
            border-radius: 20px;
            margin-top: 50px;
        }

        .footer-links a {
            color: var(--primary);
            text-decoration: none;
            margin: 0 10px;
            font-weight: 600;
        }
    </style>
</head>
<body oncontextmenu="return false;">

<div class="container">
    <a href="https://www.chat-jawwal.com" class="back-btn"><span>←</span> العودة إلى الشات</a>
    
    <div class="hero-section">
        <h1>❓ الأسئلة الشائعة</h1>
        <p>إجابات على جميع استفساراتك حول استخدام دردشتنا</p>
    </div>

    <div class="card">
        <h2 class="section-title">❓ الأسئلة الشائعة في الشات والدردشة</h2>

        <div class="accordion-item">
            <div class="accordion-header" onclick="toggleAccordion(this)">
                <span>💡 أسئلة عامة</span>
                <span class="icon">▼</span>
            </div>
            <div class="accordion-content">
                <h4>هل الشات مجاني؟</h4>
                <p><strong>نعم بالتأكيد!</strong> الشات مجاني بالكامل مع جميع المزايا الأساسية. يمكنك الاستمتاع بالدردشة النصية والصوتية دون أي تكلفة. هناك اشتراكات مميزة اختيارية توفر مزايا إضافية حصرية.</p>
                <hr>
                <h4>هل توجد خاصية المكالمة الخاصة المجانية؟</h4>
                <p><strong>نعم،</strong> خاصية المكالمات في الخاص مجانية ومتاحة لجميع المستخدمين.</p>
                <hr>
                <h4>هل يمكنني الدخول بالجوال؟</h4>
                <p><strong>بالطبع!</strong> الموقع مصمم بشكل احترافي ليعمل بسلاسة تامة على جميع الأجهزة الذكية، سواء كانت آيفون أو أندرويد أو آيباد.</p>
                <hr>
                <h4>هل يمكنني الدخول بكمبيوتر أو جهاز لوحي؟</h4>
                <p><strong>نعم،</strong> الموقع يعمل على جميع الأجهزة بما في ذلك الكمبيوتر والأجهزة اللوحية.</p>
                <hr>
                <h4>هل تطلبون مني الإيميل أو رقم الجوال عند التسجيل؟</h4>
                <p><strong>لا،</strong> نحن لا نطلب أي من هذه المعلومات أثناء التسجيل. فقط اسم المستخدم وكلمة المرور.</p>
            </div>
        </div>

        <div class="accordion-item">
            <div class="accordion-header" onclick="toggleAccordion(this)">
                <span>👤 الحساب والتسجيل</span>
                <span class="icon">▼</span>
            </div>
            <div class="accordion-content">
                <h4>كيف يمكنني التسجيل في الشات؟ وهل أحتاج إلى رقم جوال أو إيميل؟</h4>
                <p>لا، يمكنك التسجيل بدون رقم جوال أو بريد إلكتروني. فقط اختر "تسجيل عضوية جديدة" واملأ البيانات المطلوبة.</p>
                <hr>
                <h4>كيف أسجل حساب جديد؟</h4>
                <ul>
                    <li>اضغط على زر "تسجيل عضوية" في الصفحة الرئيسية</li>
                    <li>اختر اسم مستخدم مناسب وغير مخالف</li>
                    <li>أدخل كلمة مرور قوية وآمنة</li>
                    <li>أكمل البيانات البسيطة المطلوبة</li>
                    <li>ملاحظة: إذا وجدت حظراً، يرجى انتظار توثيق العضوية من الإدارة.</li>
                </ul>
                <hr>
                <h4>تم حظري بالخطأ أو ظهر لي تشابه ID، ماذا أفعل؟</h4>
                <p>تواصل مع الإدارة من صفحة "اتصل بنا" وسيتم حل المشكلة فوراً.</p>
                <hr>
                <h4>ماذا أفعل إذا نسيت العضوية أو الرقم السري؟</h4>
                <p>تواصل مع الإدارة وقدم لهم رقم العضوية أو أي معلومات تساعد في استعادتها.</p>
            </div>
        </div>

        <div class="accordion-item">
            <div class="accordion-header" onclick="toggleAccordion(this)">
                <span>💬 المزايا والاستخدام</span>
                <span class="icon">▼</span>
            </div>
            <div class="accordion-content">
                <h4>كيف أفعل المايك على الجوال أو الكمبيوتر؟</h4>
                <p><strong>للجوال:</strong> إعدادات المتصفح ← Site settings ← المايكروفون ← السماح.<br>
                <strong>للكمبيوتر:</strong> ستظهر نافذة إذن عند دخولك الغرفة، اختر "Allow" أو "سماح".</p>
                <hr>
                <h4>كيف أستخدم الميكروفون في الدردشة الصوتية؟</h4>
                <ul>
                    <li>ادخل إلى أي غرفة صوتية</li>
                    <li>اضغط على أيقونة الميكروفون</li>
                    <li>اسمح للمتصفح باستخدام المايك</li>
                </ul>
                <hr>
                <h4>كيف أرسل رسالة خاصة لشخص معين؟</h4>
                <p>اضغط على اسم المستخدم، ثم اختر "إرسال رسالة خاصة" من القائمة المنبثقة.</p>
                <hr>
                <h4>هل يمكن ترقيتي إلى سوبر؟</h4>
                <p>الترقية تعتمد على نشاطك وتعاملك الراقي، ويتم منحها من قبل الإدارة بناءً على معايير معينة.</p>
            </div>
        </div>

        <div class="accordion-item">
            <div class="accordion-header" onclick="toggleAccordion(this)">
                <span>🔒 الخصوصية والأمان</span>
                <span class="icon">▼</span>
            </div>
            <div class="accordion-content">
                <h4>هل محادثاتي محمية وآمنة؟</h4>
                <p><strong>نعم تماماً!</strong> جميع الرسائل مشفرة أثناء النقل، ولا يتم مشاركة بياناتك مع أي طرف خارجي. خصوصيتك هي أولويتنا.</p>
                <hr>
                <h4>كيف أحمي حسابي من الاختراق؟</h4>
                <ul>
                    <li>استخدم كلمة مرور قوية وغير متوقعة.</li>
                    <li>لا تشارك بيانات حسابك مع أي شخص مهما ادعى صلته بالإدارة.</li>
                    <li>احذر من الضغط على روابط مشبوهة يرسلها مستخدمون مجهولون.</li>
                </ul>
            </div>
        </div>

        <div class="accordion-item">
            <div class="accordion-header" onclick="toggleAccordion(this)">
                <span>💎 الاشتراكات والباقات</span>
                <span class="icon">▼</span>
            </div>
            <div class="accordion-content">
                <h4>ما هي الباقات المميزة المتاحة؟</h4>
                <ul>
                    <li>💎 عضوية النخبة - 600 ريال</li>
                    <li>👑 عضوية التاج الملكي - 500 ريال</li>
                    <li>⚜️ عضوية التميز - 400 ريال</li>
                    <li>🌟 عضوية الكريستال - 300 ريال</li>
                    <li>⭐ النجمة الذهبية - 200 ريال</li>
                    <li>🌑 النجمة السوداء - 150 ريال</li>
                </ul>
                <p>للاشتراك، يرجى التواصل مع الإدارة عبر قنوات التواصل الرسمية.</p>
            </div>
        </div>

        <div class="accordion-item">
            <div class="accordion-header" onclick="toggleAccordion(this)">
                <span>🛠️ حل المشاكل التقنية</span>
                <span class="icon">▼</span>
            </div>
            <div class="accordion-content">
                <h4>الموقع لا يعمل على جهازي، ماذا أفعل؟</h4>
                <ul>
                    <li>تأكد من تحديث المتصفح لأحدث إصدار.</li>
                    <li>قم بتنظيف ذاكرة التخزين المؤقت (Cache) للمتصفح.</li>
                    <li>جرب الدخول من متصفح آخر مثل Chrome أو Safari.</li>
                </ul>
                <hr>
                <h4>هل أحتاج VPN؟</h4>
                <p>الموقع يعمل بشكل طبيعي بدون VPN، ولكن يمكنك استخدامه لزيادة الخصوصية شرط أن يكون السيرفر سريعاً.</p>
            </div>
        </div>
    </div>

    <div class="footer">
        <div class="footer-links">
            <a href="https://www.chat-jawwal.com">شات الاقصى</a> | 
            <a href="https://www.chat-jawwal.com">الرئيسية</a>
        </div>
        <p>© 2026 جميع الحقوق محفوظة لـ شات الاقصى للجوال</p>
    </div>
</div>

<script>
    function toggleAccordion(element) {
        const content = element.nextElementSibling;
        const allHeaders = document.querySelectorAll('.accordion-header');
        const allContents = document.querySelectorAll('.accordion-content');

        // إغلاق باقي الأقسام عند فتح قسم جديد
        allHeaders.forEach((header, index) => {
            if (header !== element) {
                header.classList.remove('active');
                allContents[index].classList.remove('open');
                header.querySelector('.icon').textContent = '▼';
            }
        });

        element.classList.toggle('active');
        content.classList.toggle('open');
        const icon = element.querySelector('.icon');
        icon.textContent = element.classList.contains('active') ? '▲' : '▼';
    }

    // فتح القسم الأول تلقائياً عند التحميل
    document.addEventListener('DOMContentLoaded', () => {
        const firstHeader = document.querySelector('.accordion-header');
        if (firstHeader) toggleAccordion(firstHeader);
    });

    // حماية المحتوى
    document.addEventListener('contextmenu', event => event.preventDefault());
    document.addEventListener('keydown', function (e) {
        if (e.key === "F12" || (e.ctrlKey && e.shiftKey && e.key === "I") || (e.ctrlKey && e.key === "U")) {
            e.preventDefault();
        }
    });
</script>

</body>
</html>
