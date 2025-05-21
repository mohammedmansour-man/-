# -
زخرف اسمك والبايو الخاص بك على لعبه فري فاير مع المصمم محمد المنصور على موقعنا الذكي
<!DOCTYPE html><html lang="ar">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>زخرفة وتلوين أسماء فري فاير</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f0f0f0;
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 20px;
      direction: rtl;
    }
    .container {
      background: white;
      padding: 30px;
      border-radius: 15px;
      box-shadow: 0 0 15px rgba(0, 0, 0, 0.1);
      width: 90%;
      max-width: 400px;
      margin-top: 20px;
    }
    input, select, button {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border: 1px solid #ccc;
      border-radius: 8px;
      font-size: 16px;
    }
    #result {
      margin-top: 20px;
      font-weight: bold;
      word-break: break-word;
    }
    .footer {
      margin-top: 30px;
      font-size: 14px;
      color: #555;
      text-align: center;
    }
    .photo-box {
      margin-bottom: 20px;
    }
    .photo-box img {
      max-width: 150px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.2);
    }
  </style>
</head>
<body>
  <div class="photo-box">
    <img src="/mnt/data/file-HwF8TQzsfm82DwaLzjS1tQ" alt="صورة المطور">
  </div>  <div class="container">
    <h2>زخرفة وتلوين اسم فري فاير</h2>
    <input type="text" id="username" placeholder="اكتب اسمك هنا">
    <label for="color">اختر اللون:</label>
    <select id="color">
      <option value="FF0000">أحمر</option>
      <option value="00FF00">أخضر</option>
      <option value="0000FF">أزرق</option>
      <option value="FFFF00">أصفر</option>
      <option value="FF00FF">وردي</option>
      <option value="00FFFF">سماوي</option>
      <option value="FFFFFF">أبيض</option>
    </select>
    <button onclick="generateCode()">توليد الاسم الملون</button>
    <div id="result"></div>
  </div>  <div class="footer">
    تم الإنشاء بواسطة المطور محمد أكرم المنصور
  </div>  <script>
    function generateCode() {
      const username = document.getElementById('username').value.trim();
      const color = document.getElementById('color').value;

      if (username === '') {
        document.getElementById('result').innerText = 'الرجاء كتابة الاسم.';
        return;
      }

      const result = `[${color}]${username}`;
      document.getElementById('result').innerText = result;
    }
  </script></body>
</html>
