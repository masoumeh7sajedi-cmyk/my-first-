<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>دنیای سرگرمی</title>
<style>
body {
  margin: 0;
  font-family: Tahoma, sans-serif;
  background: linear-gradient(135deg, #17152f, #44316b);
  color: white;
  text-align: center;
  min-height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
}
.card {
  padding: 35px 20px;
  width: 85%;
  max-width: 400px;
  background: #ffffff12;
  border: 1px solid #ffffff30;
  border-radius: 25px;
}
h1 { color: #e5baff; }
button {
  background: #d6a7ff;
  border: none;
  border-radius: 12px;
  padding: 14px 25px;
  font-size: 16px;
  cursor: pointer;
  margin-top: 15px;
}
#message { margin-top: 20px; line-height: 2; }
</style>
</head>
<body>
<div class="card">
  <h1>به دنیای سرگرمی خوش اومدی!</h1>
  <p>اینجا قراره از حوصله‌سربری فرار کنیم.</p>
  <button onclick="showMessage()">یه چیزی نشونم بده!</button>
  <div id="message"></div>
</div>
<script>
const messages = [
  "امروز یه چیز جدید یاد بگیر!",
  "یه معما حل کن؛ مغزت بیکار نمونه!",
  "گاهی بهترین کار، یه استراحت درست‌وحسابه.",
  "یه ایده عجیب داری؟ امتحانش کن!"
];
function showMessage() {
  document.getElementById("message").textContent =
    messages[Math.floor(Math.random() * messages.length)];
}
</script>
</body>
</html># my-first-
