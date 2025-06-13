<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>تسجيل الدخول - Nevad</title>
  <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Cairo', sans-serif;
      background-color: #f4f4f4;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .login-container {
      background-color: white;
      padding: 30px;
      border-radius: 15px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
      width: 90%;
      max-width: 400px;
    }

    h2 {
      text-align: center;
      color: #333;
    }

    label {
      display: block;
      margin: 15px 0 5px;
      color: #555;
    }

    input[type="text"],
    input[type="password"] {
      width: 100%;
      padding: 10px;
      border-radius: 8px;
      border: 1px solid #ccc;
      font-size: 16px;
    }

    button {
      margin-top: 20px;
      width: 100%;
      padding: 10px;
      background-color: #3b82f6;
      border: none;
      color: white;
      font-size: 16px;
      border-radius: 8px;
      cursor: pointer;
    }

    .register-link {
      text-align: center;
      margin-top: 15px;
      font-size: 14px;
    }
  </style>
</head>
<body>
  <div class="login-container">
    <h2>تسجيل الدخول إلى Nevad</h2>
    <form action="dashboard.html" method="POST">
      <label for="phone">رقم الهاتف</label>
      <input type="text" id="phone" name="phone" required>

      <label for="password">كلمة المرور</label>
      <input type="password" id="password" name="password" required>

      <button type="submit">تسجيل الدخول</button>
    </form>
    <div class="register-link">
      ليس لديك حساب؟ <a href="register.html">سجل الآن</a>
    </div>
  </div>
</body>
</html>


تم إنشاء الكود الأولي لصفحة تسجيل الدخول الخاصة بموقع Nevad. يمكنك رفع هذا الملف على GitHub ضمن مجلد المشروع كمقدمة للموقع. هل تودّ أن نكمل الآن صفحة "التسجيل" و"لوحة التحكم"؟

