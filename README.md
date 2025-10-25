<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Strategy 2: Golf Course Programs</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { font-family: 'Segoe UI', sans-serif; background: linear-gradient(135deg, #27ae60, #229954); padding: 20px; }
        .container { max-width: 1400px; margin: 0 auto; background: white; border-radius: 20px; box-shadow: 0 20px 60px rgba(0,0,0,0.3); }
        .language-toggle { position: sticky; top: 0; z-index: 1000; background: rgba(255,255,255,0.98); padding: 15px 40px; display: flex; justify-content: center; gap: 15px; border-bottom: 3px solid #27ae60; box-shadow: 0 3px 15px rgba(0,0,0,0.1); }
        .lang-btn { padding: 12px 30px; border: 2px solid #27ae60; background: white; color: #27ae60; border-radius: 8px; cursor: pointer; font-size: 1.1em; font-weight: bold; transition: all 0.3s ease; }
        .lang-btn:hover { background: #f0fff0; transform: translateY(-2px); }
        .lang-btn.active { background: #27ae60; color: white; }
        .lang-content { display: none; }
        .lang-content.active { display: block; }
        .header { background: linear-gradient(135deg, #27ae60, #229954); color: white; padding: 60px 40px; text-align: center; }
        .header h1 { font-size: 3.5em; margin-bottom: 15px; }
        .section { padding: 50px 40px; }
        .section:nth-child(even) { background: #f8f9fa; }
        .revenue-amount { font-size: 2.5em; font-weight: bold; color: #27ae60; text-align: center; margin: 30px 0; }
        .product-card { background: #f0fff0; padding: 25px; border-radius: 12px; margin: 20px 0; border-left: 5px solid #27ae60; }
        .product-card h3 { color: #27ae60; margin-bottom: 15px; font-size: 1.6em; }
        ul { line-height: 1.9; margin-left: 20px; }
        ul li { margin: 10px 0; }
        .back-link { display: inline-block; background: #3498db; color: white; padding: 12px 30px; border-radius: 8px; text-decoration: none; margin: 20px 0; font-weight: bold; }
        .back-link:hover { background: #2980b9; }
    </style>
</head>
<body>
    <div class="container">
        <div class="language-toggle">
            <button class="lang-btn active" onclick="switchLanguage('en')" data-lang="en">🇺🇸 English</button>
            <button class="lang-btn" onclick="switchLanguage('ru')" data-lang="ru">🇷🇺 Русский</button>
            <button class="lang-btn" onclick="switchLanguage('uz')" data-lang="uz">🇺🇿 O'zbek</button>
        </div>

        <div class="lang-content active" id="content-en">
            <div class="header">
                <h1>⛳ STRATEGY 2</h1>
                <h2 style="font-size: 2em;">Golf Course Medical Programs</h2>
                <p style="font-size: 1.3em; margin-top: 15px;">On-Site Medical Supply Stations for Active Seniors</p>
            </div>

            <div class="section">
                <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad4/" class="back-link">← Back to Portfolio</a>
                
                <div class="revenue-amount">Year 1: $280K - $700K</div>

                <div class="product-card">
                    <h3>🎯 Core Products (BOC 70%)</h3>
                    <ul>
                        <li><strong>Knee Braces (OR03):</strong> Golf-specific support braces $150-$800</li>
                        <li><strong>Compression Stockings (S01):</strong> Circulation support for walking 18 holes $40-$120</li>
                        <li><strong>Back Braces (OR07):</strong> Lumbar support for golf swing $80-$400</li>
                        <li><strong>Diabetic Shoes (DM06):</strong> Comfortable walking shoes $100-$400</li>
                        <li><strong>Elbow Braces (OR05):</strong> Golf elbow prevention $60-$250</li>
                    </ul>
                </div>

                <div class="product-card">
                    <h3>📊 Implementation</h3>
                    <ul>
                        <li>Partner with 8-12 golf courses in metro area</li>
                        <li>Install medical supply vending stations at clubhouses</li>
                        <li>Monthly on-site fitting events with certified fitters</li>
                        <li>Target: 15-25 sales per course per month</li>
                    </ul>
                </div>

                <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad4/" class="back-link">← Back</a>
            </div>
        </div>

        <div class="lang-content" id="content-ru">
            <div class="header">
                <h1>⛳ СТРАТЕГИЯ 2</h1>
                <h2 style="font-size: 2em;">Программы для Гольф-Клубов</h2>
                <p style="font-size: 1.3em; margin-top: 15px;">Станции Медицинских Товаров для Активных Пожилых</p>
            </div>

            <div class="section">
                <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad4/" class="back-link">← Назад</a>
                <div class="revenue-amount">1-й Год: $280K - $700K</div>

                <div class="product-card">
                    <h3>🎯 Основные Продукты (BOC 70%)</h3>
                    <ul>
                        <li><strong>Коленные Брейсы (OR03):</strong> Специальные поддерживающие брейсы для гольфа $150-$800</li>
                        <li><strong>Компрессионные Чулки (S01):</strong> Поддержка кровообращения при ходьбе 18 лунок $40-$120</li>
                        <li><strong>Поясничные Брейсы (OR07):</strong> Поясничная поддержка для удара в гольфе $80-$400</li>
                        <li><strong>Диабетическая Обувь (DM06):</strong> Удобная обувь для ходьбы $100-$400</li>
                        <li><strong>Локтевые Брейсы (OR05):</strong> Профилактика локтя гольфиста $60-$250</li>
                    </ul>
                </div>

                <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad4/" class="back-link">← Назад</a>
            </div>
        </div>

        <div class="lang-content" id="content-uz">
            <div class="header">
                <h1>⛳ STRATEGIYA 2</h1>
                <h2 style="font-size: 2em;">Golf Klub Dasturlari</h2>
                <p style="font-size: 1.3em; margin-top: 15px;">Faol Keksalar uchun Tibbiy Ta'minot Stansiyalari</p>
            </div>

            <div class="section">
                <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad4/" class="back-link">← Orqaga</a>
                <div class="revenue-amount">1-Yil: $280K - $700K</div>

                <div class="product-card">
                    <h3>🎯 Asosiy Mahsulotlar (BOC 70%)</h3>
                    <ul>
                        <li><strong>Tizza Breislari (OR03):</strong> Golf uchun maxsus qo'llab-quvvatlovchi breislar $150-$800</li>
                        <li><strong>Kompressiya Paypoqlari (S01):</strong> 18 teshikni yurish uchun qon aylanishini qo'llab-quvvatlash $40-$120</li>
                        <li><strong>Bel Breislari (OR07):</strong> Golf zarbasi uchun bel qo'llab-quvvatlash $80-$400</li>
                        <li><strong>Diabetik Poyafzallar (DM06):</strong> Yurish uchun qulay poyafzal $100-$400</li>
                        <li><strong>Tirsak Breislari (OR05):</strong> Golf tirsagini oldini olish $60-$250</li>
                    </ul>
                </div>

                <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad4/" class="back-link">← Orqaga</a>
            </div>
        </div>
    </div>

    <script>
        function switchLanguage(lang) {
            document.querySelectorAll('.lang-content').forEach(content => content.classList.remove('active'));
            document.querySelectorAll('.lang-btn').forEach(btn => btn.classList.remove('active'));
            document.getElementById('content-' + lang).classList.add('active');
            document.querySelector(`.lang-btn[data-lang="${lang}"]`).classList.add('active');
            localStorage.setItem('preferred-language', lang);
            window.scrollTo(0, 0);
        }
        window.addEventListener('DOMContentLoaded', function() {
            const savedLang = localStorage.getItem('preferred-language');
            if (savedLang && ['en', 'ru', 'uz'].includes(savedLang)) switchLanguage(savedLang);
        });
    </script>
</body>
</html>
