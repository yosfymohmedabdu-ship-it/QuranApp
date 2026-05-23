# QuranApp
# QuranApp تطبيق مبسط لعرض القرآن الكريم مع واجهة سهلة الاستخدام، يهدف إلى تسهيل القراءة والبحث في السور والآيات.  ## المميزات - واجهة عربية واضحة وبسيطة. - إمكانية البحث عن السور والآيات. - دعم العمل على الهواتف والأجهزة اللوحية. - تحديثات مستمرة لإضافة مزايا جديدة.  ## الهدف توفير تجربة سلسة للمستخدمين لقراءة القرآن الكريم بدون تعقيد، مع إم
style.css
/* تنسيق واجهة تطبيق القرآن الكريم */
body {
  background-color: #f5f5f5;
  font-family: "Traditional Arabic", serif;
  font-size: 18px;
  color: #006400; /* الأخضر الداكن */
}
buttons.css
/* تنسيق الأزرار */
button {
  background-color: #006400; /* الأخضر الداكن */
  color: white;
  font-size: 16px;
  border-radius: 8px;
  padding: 10px 20px;
  border: none;
}
button:hover {
  background-color: #228B22; /* لون أخضر أفتح عند التمرير */
}

/* الألوان الأساسية */
:root {
  --primary: #006400;
  --secondary: #228B22;
  --background: #f5f5f5;
  --text: #000000;
}
{
  "primary": "#006400",
  "secondary": "#228B22",
  "background": "#f5f5f5",
  "text": "#000000"
}
{
  "primary": "#006400",
  "secondary": "#228B22",
  "background": "#f5f5f5",
  "text": "#000000"
}## واجهة المستخدم (UI)
ملفات التصميم والتنسيق موجودة في مجلد UI، وتشمل الألوان والأزرار والخطوط الخاصة بالتطبيق.<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <title>تطبيق القرآن الكريم</title>
  <!-- ربط ملف التنسيق -->
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <h1>مرحبا بك في تطبيق القرآن الكريم</h1>
  <button>ابدأ الآن</button>
</body>
</html>
index.html
