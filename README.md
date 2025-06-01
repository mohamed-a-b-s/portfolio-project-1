# portfolio-project-1

<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>مقهى الراحة | Agadir</title>
  <meta name="description" content="أهلاً بك في مقهى الراحة. الجودة والذوق الرفيع في مكان واحد بأكادير.">
  <link rel="icon" href="https://blogger.googleusercontent.com/img/a/AVvXsEhYplpTJargIawhHQsPKPNQrPlaCxLpjfICwXQqPL-B1Na8TF3_hATNX21yMblusphveHgemQWxP9xF28rDOCN9Y5SrHTb0fNUeUCs83bhmpVCaxsqojQW-8xDX1gyGIFxQZDtZ0XCgTe7nvN4N85vF-xv1qI1PMNV_aQi4OJW8f_NSUIDdoEXey3JG" type="image/png">
  <link rel="stylesheet"
  <link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@400;700&display=swap" rel="stylesheet">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Tajawal', sans-serif;
      background-color: #1e1e1e;
      color: #f9f9f9;
      line-height: 1.8;
    }

    header {
      background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.8)), url('https://images.unsplash.com/photo-1542444459-db60d7e083f9?auto=format&fit=crop&w=1950&q=80') no-repeat center center/cover;
      padding: 100px 20px;
      text-align: center;
      color: #fff;
    }

    header h1 {
      font-size: 48px;
      color: #eabf55;
    }

    header h1 img {
      width: 80px;
      height: 80px;
      vertical-align: middle;
      border-radius: 12px;
      margin-left: 10px;
      box-shadow: 0 0 8px #eabf55;
    }

    header p {
      font-size: 20px;
      margin-top: 12px;
    }

    nav {
      background: #2a2a2a;
      display: flex;
      justify-content: center;
      gap: 30px;
      padding: 15px;
      border-bottom: 2px solid #eabf55;
    }

    nav a {
      color: #eabf55;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #ffffff;
    }

    section {
      max-width: 1100px;
      margin: 40px auto;
      padding: 0 20px;
    }

    section h2 {
      color: #eabf55;
      font-size: 28px;
      border-bottom: 2px solid #eabf55;
      padding-bottom: 8px;
      margin-bottom: 20px;
    }

    .menu-item {
      background-color: #2c2c2c;
      border-right: 4px solid #eabf55;
      padding: 12px 18px;
      margin-bottom: 14px;
      border-radius: 8px;
      box-shadow: 0 2px 4px rgba(0,0,0,0.2);
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .menu-item a {
      color: #1e1e1e;
      background-color: #eabf55;
      padding: 6px 12px;
      border-radius: 6px;
      text-decoration: none;
      font-weight: bold;
      font-size: 14px;
      transition: background-color 0.3s;
    }

    .menu-item a:hover {
      background-color: #cfa640;
    }

    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 20px;
    }

    .product {
      background: #2e2e2e;
      padding: 15px;
      border-radius: 10px;
      text-align: center;
      transition: transform 0.3s ease;
    }

    .product:hover {
      transform: scale(1.05);
    }

    .product img {
      width: 100%;
      height: 180px;
      border-radius: 10px;
      object-fit: cover;
    }

    .product p {
      margin: 12px 0;
      font-size: 16px;
    }

    .product a {
      display: inline-block;
      padding: 10px 18px;
      background-color: #eabf55;
      color: #1e1e1e;
      border-radius: 6px;
      text-decoration: none;
      font-weight: bold;
    }

    .contact p {
      margin: 10px 0;
      font-size: 16px;
    }

    .contact i {
      margin-left: 8px;
      color: #eabf55;
    }

    .contact a {
      text-decoration: none;
      color: #eabf55;
    }

    footer {
      background: #111;
      text-align: center;
      padding: 20px;
      color: #999;
      font-size: 14px;
      margin-top: 40px;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 32px;
      }

      header h1 img {
        width: 50px;
        height: 50px;
      }

      nav {
        flex-direction: column;
        gap: 15px;
      }
    }
  </style>
</head>
<body>
</body>
</html>
  <header>
    <h1>
      <img src="https://blogger.googleusercontent.com/img/a/AVvXsEhYplpTJargIawhHQsPKPNQrPlaCxLpjfICwXQqPL-B1Na8TF3_hATNX21yMblusphveHgemQWxP9xF28rDOCN9Y5SrHTb0fNUeUCs83bhmpVCaxsqojQW-8xDX1gyGIFxQZDtZ0XCgTe7nvN4N85vF-xv1qI1PMNV_aQi4OJW8f_NSUIDdoEXey3JG" alt="شعار المقهى">
      مقهى الراحة
    </h1>
    <p>مذاق خاص، مكان هادئ، ترحاب فخم - أكادير</p>
  </header>

  <nav>
    <a href="#about">من نحن</a>
    <a href="#menu">القائمة</a>
    <a href="#contact">تواصل معنا</a>
  </nav>

  <section id="about">
    <h2>من نحن</h2>
    <p>نحن مقهى محلي يقدم لزبنائه أفضل أنواع القهوة والشاي والعصائر الطبيعية في جو راقٍ وخدمة متميزة. نطمح دائماً لأن نكون وجهتكم المفضلة.</p>
  </section>
  <section id="menu">
    <h2>قائمة المشروبات والحلويات</h2>

    <h3 style="color:#eabf55; margin-top: 30px;">🥤 المشروبات الساخنة</h3>
    <div class="menu-item">أتاي بالنعناع - 10 دراهم <a href="https://wa.me/212635939690?text=سلام، بغيت نطلب أتاي بالنعناع" target="_blank" style="float:left; color:#000000;">اطلب الآن</a></div>
    <div class="menu-item">قهوة نص نص - 12 درهم <a href="https://wa.me/212635939690?text=سلام، بغيت نطلب قهوة نص نص" target="_blank" style="float:left; color:#000000;">اطلب الآن</a></div>
    <div class="menu-item">قهوة كحلة - 10 درهم <a href="https://wa.me/212635939690?text=سلام، بغيت نطلب قهوة كحلة" target="_blank" style="float:left; color:#000000;">اطلب الآن</a></div>
    <div class="menu-item">قهوة بالحليب - 12 درهم <a href="https://wa.me/212635939690?text=سلام، بغيت نطلب قهوة بالحليب" target="_blank" style="float:left; color:#000000;">اطلب الآن</a></div>
    <div class="menu-item">نسكافي - 15 درهم <a href="https://wa.me/212635939690?text=سلام، بغيت نطلب نسكافي" target="_blank" style="float:left; color:#000000;">اطلب الآن</a></div>
    <div class="menu-item">كابوتشينو - 18 درهم <a href="https://wa.me/212635939690?text=سلام، بغيت نطلب كابوتشينو" target="_blank" style="float:left; color:#000000;">اطلب الآن</a></div>
    <div class="menu-item">شوكولا ساخنة - 20 درهم <a href="https://wa.me/212635939690?text=سلام، بغيت نطلب شوكولا ساخنة" target="_blank" style="float:left; color:#000000;">اطلب الآن</a></div>

    <h3 style="color:#eabf55; margin-top: 30px;">🧊 المشروبات الباردة</h3>
    <div class="menu-item">عصير برتقال طبيعي - 15 درهم <a href="https://wa.me/212635939690?text=سلام، بغيت نطلب عصير برتقال طبيعي" target="_blank" style="float:left; color:#000000;">اطلب الآن</a></div>
    <div class="menu-item">عصير أفوكا بالحليب - 20 درهم <a href="https://wa.me/212635939690?text=سلام، بغيت نطلب عصير أفوكا بالحليب" target="_blank" style="float:left; color:#000000;">اطلب الآن</a></div>
    <div class="menu-item">كوكتيل فواكه - 25 درهم <a href="https://wa.me/212635939690?text=سلام، بغيت نطلب كوكتيل فواكه" target="_blank" style="float:left; color:#000000;">اطلب الآن</a></div>
    <div class="menu-item">مياه معدنية - 5 دراهم <a href="https://wa.me/212635939690?text=سلام، بغيت نطلب مياه معدنية" target="_blank" style="float:left; color:#000000;">اطلب الآن</a></div>
    <div class="menu-item">سودة (كوكا/فانطا/سبرايت) - 10 درهم <a href="https://wa.me/212635939690?text=سلام، بغيت نطلب سودة" target="_blank" style="float:left; color:#000000;">اطلب الآن</a></div>

    <h3 style="color:#eabf55; margin-top: 30px;">🍰 الحلويات والمرافقة</h3>
    <div class="menu-item">كرواسون - 7 دراهم <a href="https://wa.me/212635939690?text=سلام، بغيت نطلب كرواسون" target="_blank" style="float:left; color:#000000;">اطلب الآن</a></div>
    <div class="menu-item">طورطة اليوم - 15 درهم <a href="https://wa.me/212635939690?text=سلام، بغيت نطلب طورطة اليوم" target="_blank" style="float:left; color:#000000;">اطلب الآن</a></div>
    <div class="menu-item">بيصارة بالصوصيص - 20 درهم <a href="https://wa.me/212635939690?text=سلام، بغيت نطلب بيصارة بالصوصيص" target="_blank" style="float:left; color:#000000;">اطلب الآن</a></div>
    <div class="menu-item">بان كيك بالعسل - 18 درهم <a href="https://wa.me/212635939690?text=سلام، بغيت نطلب بان كيك بالعسل" target="_blank" style="float:left; color:#000000;">اطلب الآن</a></div>
  </section>

  <section id="contact">
    <h2>تواصل معنا</h2>
    <div class="contact">
      <p><i class="fa fa-phone"></i> الهاتف: +212 635-939690</p>
            <p><i class="fab fa-whatsapp"></i> <a href="https://wa.me/212635939690" target="_blank" style="color:#eabf55;">راسلنا على واتساب</a></p>
      <p><i class="fa fa-map-marker-alt"></i> أكادير، شارع الجيش الملكي</p>
    </div>
  </section>

  <footer>
    &copy; 2025 جميع الحقوق محفوظة - مقهى الراحة
  </footer>

</body>
</html>


