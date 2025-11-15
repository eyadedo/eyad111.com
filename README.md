<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <title>تواصل معي على واتساب</title>

  <!-- كود Google AdSense -->
  <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-8258987336700999"
     crossorigin="anonymous"></script>

  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      text-align: center;
      padding: 50px;
      background-color: #f2f2f2;
      direction: rtl;
    }
    h1 {
      color: #333;
    }
    form {
      margin: 20px auto;
      max-width: 500px;
      background-color: #fff;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    input, textarea, button {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      font-size: 16px;
      border: 1px solid #ccc;
      border-radius: 6px;
    }
    button {
      background-color: #25D366;
      color: white;
      border: none;
      cursor: pointer;
      font-size: 18px;
    }
    button:hover {
      background-color: #1ebe5d;
    }
    .ad-container {
      margin: 30px auto;
      max-width: 500px;
    }
  </style>
</head>
<body>

  <h1>املأ بياناتك للتواصل معي</h1>

  <!-- نموذج البيانات -->
  <form onsubmit="goToWhatsApp(); return false;">
    <input type="text" id="name" placeholder="الاسم الكامل" required>
    <input type="email" id="email" placeholder="البريد الإلكتروني" required>
    <input type="tel" id="phone" placeholder="رقم الهاتف">
    <textarea id="message" rows="4" placeholder="اكتب رسالتك أو استفسارك هنا..."></textarea>
    <button type="submit">إرسال والتواصل على واتساب</button>
  </form>

  <!-- إعلان AdSense -->
  <div class="ad-container">
    <ins class="adsbygoogle"
         style="display:block"
         data-ad-client="ca-pub-8258987336700999"
         data-ad-slot="1234567890"
         data-ad-format="auto"
         data-full-width-responsive="true"></ins>
    <script>
         (adsbygoogle = window.adsbygoogle || []).push({});
    </script>
  </div>

  <script>
    function goToWhatsApp() {
      const name = document.getElementById("name").value;
      const email = document.getElementById("email").value;
      const phone = document.getElementById("phone").value;
      const message = document.getElementById("message").value;

      const fullMessage = `الاسم: ${name}%0Aالبريد: ${email}%0Aالهاتف: ${phone}%0Aالرسالة: ${message}`;
      const whatsappURL = `https://wa.me/201283391753?text=${encodeURIComponent(fullMessage)}`;

      window.open(whatsappURL, "_blank");
    }
  </script>

</body>
</html>
