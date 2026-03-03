<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Prestigio Alex | للرقي عنوان</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;700&display=swap" rel="stylesheet">
</head>
<body>

    <header>
        <nav>
            <div class="logo">
                <img src="logo.jpg" alt="Prestigio Logo"> 
            </div>
            <ul>
                <li><a href="#home">الرئيسية</a></li>
                <li><a href="#products">منتجاتنا</a></li>
                <li><a href="#contact">اتصل بنا</a></li>
            </ul>
        </nav>
    </header>

    <section id="home" class="hero">
        <h1>مرحباً بكم في Prestigio Alex</h1>
        <p>أرقى الأزياء (رجالي - أطفالي - والمزيد)</p>
    </section>

    <section id="products" class="container">
        <h2 class="section-title">أقسامنا</h2>
        
        <div class="tabs">
            <button onclick="filterSelection('kids')">أطفالي</button>
            <button onclick="filterSelection('men')">رجالي</button>
            <button onclick="filterSelection('others')">منتجات أخرى</button>
        </div>

        <div class="products-grid">
            <div class="product-card kids">
                <img src="pro1.jpg" alt="منتج">
                <h3>طقم أطفال كاجوال</h3>
                <p class="desc">وصف بسيط للمنتج وخامته الممتازة</p>
                <p class="price">450 EGP</p>
            </div>
            
            <div class="product-card men">
                <img src="pro2.jpg" alt="منتج">
                <h3>قميص رجالي كلاسيك</h3>
                <p class="desc">قطن 100% مريح جداً</p>
                <p class="price">600 EGP</p>
            </div>
        </div>
    </section>

    <footer id="contact">
        <p>تواصل معنا عبر الواتساب: 0123456789</p>
        <p>© 2026 Prestigio Alex - جميع الحقوق محفوظة</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
# Prestigio
