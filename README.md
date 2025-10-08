<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>أمراض القلب - Heart Diseases</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
            padding: 20px;
            min-height: 100vh;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            background: white;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
        }
        
        /* العناوين */
        h1 {
            color: #2c3e50;
            text-align: center;
            border-bottom: 3px solid #3498db;
            padding-bottom: 10px;
            margin-bottom: 30px;
            font-size: 2.2em;
        }
        
        h2 {
            color: #e74c3c;
            background: #ffeaa7;
            padding: 15px;
            border-radius: 10px;
            margin-top: 40px;
            border-right: 5px solid #e74c3c;
        }
        
        h3 {
            color: #2980b9;
            background: #d6eaf8;
            padding: 12px;
            border-radius: 8px;
            margin-top: 25px;
            border-right: 4px solid #2980b9;
        }
        
        /* الفقرات والقوائم */
        p {
            margin: 15px 0;
            font-size: 1.1em;
        }
        
        strong {
            color: #c0392b;
            font-size: 1.1em;
        }
        
        ol {
            background: #ecf0f1;
            padding: 20px 40px;
            border-radius: 10px;
            margin: 15px 0;
        }
        
        li {
            margin: 10px 0;
            padding: 8px;
            background: white;
            border-radius: 5px;
            border-right: 3px solid #3498db;
        }
        
        /* التأكيد على الأقسام */
        .section {
            background: #f8f9fa;
            padding: 20px;
            margin: 20px 0;
            border-radius: 10px;
            border-right: 5px solid #9b59b6;
        }
        
        .disease {
            background: #ffffff;
            padding: 15px;
            margin: 15px 0;
            border-radius: 8px;
            border: 1px solid #ddd;
        }
        
        /* شريط البحث */
        .search-container {
            margin: 20px 0;
            position: relative;
        }
        
        .search-box {
            width: 100%;
            padding: 15px 50px 15px 20px;
            border: 2px solid #3498db;
            border-radius: 50px;
            font-size: 1.1em;
            outline: none;
            transition: all 0.3s;
        }
        
        .search-box:focus {
            border-color: #2980b9;
            box-shadow: 0 0 10px rgba(52, 152, 219, 0.5);
        }
        
        .search-icon {
            position: absolute;
            left: 20px;
            top: 50%;
            transform: translateY(-50%);
            color: #3498db;
            font-size: 1.2em;
        }
        
        /* زر التمرير للأعلى */
        .scroll-top {
            position: fixed;
            bottom: 30px;
            left: 30px;
            background: #3498db;
            color: white;
            width: 50px;
            height: 50px;
            border-radius: 50%;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 1.5em;
            cursor: pointer;
            box-shadow: 0 4px 10px rgba(0,0,0,0.2);
            transition: all 0.3s;
            z-index: 1000;
        }
        
        .scroll-top:hover {
            background: #2980b9;
            transform: translateY(-3px);
        }
        
        /* علامة مهم */
        .important-tag {
            display: inline-block;
            background: #e74c3c;
            color: white;
            padding: 3px 10px;
            border-radius: 20px;
            font-size: 0.8em;
            margin-right: 10px;
            vertical-align: middle;
        }
        
        /* التنسيق للعربية */
        [lang="ar"] {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        /* التجاوب مع الشاشات الصغيرة */
        @media (max-width: 768px) {
            .container {
                padding: 15px;
                margin: 10px;
            }
            
            h1 {
                font-size: 1.8em;
            }
            
            ol {
                padding: 15px 25px;
            }
            
            h2, h3 {
                padding: 10px;
            }
            
            .search-box {
                padding: 12px 45px 12px 15px;
            }
            
            .scroll-top {
                bottom: 20px;
                left: 20px;
                width: 45px;
                height: 45px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>أمراض القلب - Heart Diseases <span class="important-tag">مهم</span></h1>
        
        <!-- شريط البحث -->
        <div class="search-container">
            <input type="text" class="search-box" id="searchInput" placeholder="ابحث عن مرض بالعربية أو الإنجليزية...">
            <i class="fas fa-search search-icon"></i>
        </div>
        
        <!-- محتوى أمراض القلب -->
        <div id="heartDiseases">
            <h2> ❤️‍🔥 أمراض نقص التروية والتاجية / Ischemic & Coronary Diseases</h2>
            
            <div class="disease">
                <h3>🔹 Stable Angina – الذبحة الصدرية المستقرة <span class="important-tag">مهم</span></h3>
                <p><strong>😤 Symptoms / الأعراض:</strong></p>
                <ol>
                    <li>Chest pain with exertion / ألم صدري مع الجهد</li>
                    <li>Shortness of breath / ضيق تنفس</li>
                    <li>Pain relieved by rest / ألم يتحسن بالراحة</li>
                    <li>Radiation to left arm / إشعاع للأذرع اليسرى</li>
                </ol>
                <p><strong>🧠 Cause / السبب:</strong></p>
                <ol>
                    <li>Atherosclerosis / تصلب الشرايين</li>
                    <li>Coronary artery disease / مرض الشريان التاجي</li>
                    <li>Risk factors: HTN, DM, smoking / عوامل خطر</li>
                </ol>
                <p><strong>🔬 Diagnosis / التشخيص:</strong></p>
                <ol>
                    <li>Stress test / اختبار الجهد</li>
                    <li>ECG / تخطيط القلب</li>
                    <li>Coronary angiography / تصوير الأوعية التاجية</li>
                </ol>
                <p><strong>💊 Treatment / العلاج:</strong></p>
                <ol>
                    <li>Nitroglycerin / النيتروجليسرين</li>
                    <li>Beta-blockers / حاصرات بيتا</li>
                    <li>ASA / الأسبرين</li>
                    <li>Lifestyle modification / تعديل نمط الحياة</li>
                </ol>
                <p><strong>⚠️ Complications / المضاعفات:</strong></p>
                <ol>
                    <li>Unstable angina / ذبحة غير مستقرة</li>
                    <li>MI / احتشاء عضلة القلب</li>
                    <li>Heart failure / فشل القلب</li>
                </ol>
            </div>
            
            <div class="disease">
                <h3>🔹 Acute Coronary Syndrome (NSTEMI/STEMI) – متلازمة الشريان التاجي الحادة <span class="important-tag">مهم</span></h3>
                <p><strong>😤 Symptoms / الأعراض:</strong></p>
                <ol>
                    <li>Severe chest pain / ألم صدري شديد</li>
                    <li>Diaphoresis / تعرق</li>
                    <li>Nausea and vomiting / غثيان وإقياء</li>
                    <li>Shortness of breath / ضيق تنفس</li>
                </ol>
                <p><strong>🧠 Cause / السبب:</strong></p>
                <ol>
                    <li>Coronary plaque rupture / تمزق اللويحة التاجية</li>
                    <li>Thrombus formation / تشكل الخثرة</li>
                    <li>Complete/incomplete occlusion / انسداد كامل/جزئي</li>
                </ol>
                <p><strong>🔬 Diagnosis / التشخيص:</strong></p>
                <ol>
                    <li>ECG (ST elevation/depression) / تخطيط القلب</li>
                    <li>Cardiac enzymes (Troponin) / إنزيمات القلب</li>
                    <li>Coronary angiography / تصوير الأوعية</li>
                </ol>
                <p><strong>💊 Treatment / العلاج:</strong></p>
                <ol>
                    <li>Reperfusion therapy / علاج إعادة التروية</li>
                    <li>Dual antiplatelet therapy / العلاج المزدوج</li>
                    <li>PCI / التدخل التاجي</li>
                    <li>Thrombolytics / مذيبات الجلطة</li>
                </ol>
                <p><strong>⚠️ Complications / المضاعفات:</strong></p>
                <ol>
                    <li>Arrhythmias / اضطرابات النظم</li>
                    <li>Cardiogenic shock / صدمة قلبية</li>
                    <li>Cardiac rupture / تمزق قلبي</li>
                </ol>
            </div>
            
            <h2> ❤️‍🔥 أمراض عضلة القلب / Myocardial Diseases</h2>
            
            <div class="disease">
                <h3>🔹 Myocardial Infarction – احتشاء عضلة القلب <span class="important-tag">مهم</span></h3>
                <p><strong>😤 Symptoms / الأعراض:</strong></p>
                <ol>
                    <li>Crushing chest pain / ألم صدري ساحق</li>
                    <li>Radiation to jaw/arm / إشعاع للفك/الذراع</li>
                    <li>Dyspnea / ضيق نفس</li>
                    <li>Autonomic symptoms / أعراض ذاتية</li>
                </ol>
                <p><strong>🧠 Cause / السبب:</strong></p>
                <ol>
                    <li>Coronary thrombosis / خثرة تاجية</li>
                    <li>Atherosclerosis / تصلب شرايين</li>
                    <li>Vasospasm / تشنج وعائي</li>
                </ol>
                <p><strong>🔬 Diagnosis / التشخيص:</strong></p>
                <ol>
                    <li>ECG changes / تغيرات التخطيط</li>
                    <li>Elevated troponin / ارتفاع التروبونين</li>
                    <li>Echocardiography / تخطيط صدى القلب</li>
                </ol>
                <p><strong>💊 Treatment / العلاج:</strong></p>
                <ol>
                    <li>Primary PCI / تدخل تاجي أولي</li>
                    <li>Thrombolysis / إذابة الجلطة</li>
                    <li>Medical therapy / العلاج الدوائي</li>
                    <li>Cardiac rehab / إعادة تأهيل</li>
                </ol>
                <p><strong>⚠️ Complications / المضاعفات:</strong></p>
                <ol>
                    <li>Heart failure / فشل القلب</li>
                    <li>Cardiogenic shock / صدمة قلبية</li>
                    <li>Arrhythmias / اضطرابات النظم</li>
                </ol>
            </div>
            
            <div class="disease">
                <h3>🔹 Myocarditis – التهاب عضلة القلب <span class="important-tag">مهم</span></h3>
                <p><strong>😤 Symptoms / الأعراض:</strong></p>
                <ol>
                    <li>Chest pain / ألم صدري</li>
                    <li>Fever / حمى</li>
                    <li>Fatigue / تعب</li>
                    <li>Palpitations / خفقان</li>
                </ol>
                <p><strong>🧠 Cause / السبب:</strong></p>
                <ol>
                    <li>Viral infections / عدوى فيروسية</li>
                    <li>Autoimmune diseases / أمراض مناعة ذاتية</li>
                    <li>Toxins / سموم</li>
                </ol>
                <p><strong>🔬 Diagnosis / التشخيص:</strong></p>
                <ol>
                    <li>Cardiac MRI / الرنين المغناطيسي</li>
                    <li>Endomyocardial biopsy / خزعة عضلة القلب</li>
                    <li>Elevated cardiac enzymes / ارتفاع إنزيمات القلب</li>
                </ol>
                <p><strong>💊 Treatment / العلاج:</strong></p>
                <ol>
                    <li>Supportive care / رعاية داعمة</li>
                    <li>Immunosuppressants / مثبطات المناعة</li>
                    <li>Heart failure management / علاج الفشل القلبي</li>
                </ol>
                <p><strong>⚠️ Complications / المضاعفات:</strong></p>
                <ol>
                    <li>Dilated cardiomyopathy / اعتلال عضلي توسعي</li>
                    <li>Heart failure / فشل القلب</li>
                    <li>Sudden death / موت مفاجئ</li>
                </ol>
            </div>
            
            <!-- باقي الأمراض بنفس النمط -->
            
            <h2> ❤️‍🔥 اعتلالات العضلة القلبية / Cardiomyopathies</h2>
            
            <div class="disease">
                <h3>🔹 Dilated Cardiomyopathy (DCM) – اعتلال عضلي توسعي <span class="important-tag">مهم</span></h3>
                <p><strong>😤 Symptoms / الأعراض:</strong></p>
                <ol>
                    <li>Dyspnea on exertion / ضيق نفس بالجهد</li>
                    <li>Fatigue / تعب</li>
                    <li>Edema / وذمة</li>
                    <li>Palpitations / خفقان</li>
                </ol>
                <p><strong>🧠 Cause / السبب:</strong></p>
                <ol>
                    <li>Idiopathic / مجهول السبب</li>
                    <li>Genetic / وراثي</li>
                    <li>Post-myocarditis / ما بعد التهاب العضلة</li>
                </ol>
                <p><strong>🔬 Diagnosis / التشخيص:</strong></p>
                <ol>
                    <li>Echocardiography / تخطيط صدى القلب</li>
                    <li>Cardiac MRI / الرنين المغناطيسي</li>
                    <li>ECG / تخطيط القلب</li>
                </ol>
                <p><strong>💊 Treatment / العلاج:</strong></p>
                <ol>
                    <li>ACE inhibitors / مثبطات الإنزيم</li>
                    <li>Beta-blockers / حاصرات بيتا</li>
                    <li>Diuretics / مدرات البول</li>
                    <li>Device therapy / العلاج بالأجهزة</li>
                </ol>
                <p><strong>⚠️ Complications / المضاعفات:</strong></p>
                <ol>
                    <li>Heart failure / فشل القلب</li>
                    <li>Arrhythmias / اضطرابات النظم</li>
                    <li>Thromboembolism / صمة خثرية</li>
                </ol>
            </div>
            
            <!-- باقي الأمراض ستكون بنفس النمط -->
            
        </div>
    </div>
    
    <!-- زر التمرير للأعلى -->
    <div class="scroll-top" id="scrollTop">
        <i class="fas fa-arrow-up"></i>
    </div>
    
    <script>
        // وظيفة البحث
        document.getElementById('searchInput').addEventListener('input', function() {
            const searchTerm = this.value.toLowerCase();
            const diseases = document.querySelectorAll('.disease');
            
            diseases.forEach(disease => {
                const diseaseText = disease.textContent.toLowerCase();
                if (diseaseText.includes(searchTerm)) {
                    disease.style.display = 'block';
                } else {
                    disease.style.display = 'none';
                }
            });
        });
        
        // وظيفة التمرير للأعلى
        document.getElementById('scrollTop').addEventListener('click', function() {
            window.scrollTo({
                top: 0,
                behavior: 'smooth'
            });
        });
        
        // إظهار/إخفاء زر التمرير
        window.addEventListener('scroll', function() {
            const scrollTop = document.getElementById('scrollTop');
            if (window.pageYOffset > 300) {
                scrollTop.style.display = 'flex';
            } else {
                scrollTop.style.display = 'none';
            }
        });
    </script>
</body>
</html>
