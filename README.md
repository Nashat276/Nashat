<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Eng. Nashat Aldhoon | مهندس طيران</title>
  <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;700&display=swap" rel="stylesheet">
  <script src="https://kit.fontawesome.com/a2e0e6ad1a.js" crossorigin="anonymous"></script>
  <style>
    * {margin: 0; padding: 0; box-sizing: border-box;}
    body {
      font-family: 'Cairo', sans-serif;
      background-color: #0e1a2b;
      color: #f1f1f1;
      line-height: 1.6;
    }
    header {
      background: linear-gradient(to right, #142c49, #1f3d66);
      padding: 60px 20px;
      text-align: center;
    }
    header h1 {
      font-size: 2.8em;
      color: #00bfff;
    }
    header p {
      font-size: 1.2em;
      color: #ccc;
      margin-top: 10px;
    }
    nav {
      background-color: #111827;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
    }
    nav a {
      color: #f1f1f1;
      text-decoration: none;
      padding: 14px 20px;
      transition: background 0.3s;
    }
    nav a:hover {
      background-color: #1f2937;
    }
    section {
      max-width: 1000px;
      margin: auto;
      padding: 40px 20px;
      border-bottom: 1px solid #1f2937;
    }
    h2 {
      color: #00bfff;
      margin-bottom: 20px;
      border-right: 4px solid #00bfff;
      padding-right: 10px;
    }
    .card {
      background-color: #1f2937;
      padding: 20px;
      margin-bottom: 20px;
      border-radius: 8px;
    }
    .card h3 { color: #fff; margin-bottom: 10px; }
    .card p { color: #bbb; }
    footer {
      text-align: center;
      background-color: #0a0f1a;
      padding: 20px;
      color: #777;
      font-size: 0.9em;
    }
    .contact ul {
      list-style: none;
      padding: 0;
    }
    .contact li {
      margin: 10px 0;
    }
    .contact a {
      color: #00bfff;
      text-decoration: none;
    }
    @media (max-width: 600px) {
      header h1 { font-size: 2em; }
      nav a { padding: 10px; }
    }
  </style>
</head>
<body>

<header>
  <h1>Eng. Nashat Aldhoon</h1>
  <p>مهندس طيران | محاكاة وتحليل هياكل | ديناميكا هوائية</p>
</header>

<nav>
  <a href="#about">من أنا</a>
  <a href="#skills">المهارات</a>
  <a href="#projects">الأعمال</a>
  <a href="#publications">المنشورات</a>
  <a href="#thoughts">أفكار</a>
  <a href="#contact">تواصل</a>
</nav>

<section id="about">
  <h2>من أنا</h2>
  <p>
    أنا م. نشأت الذهون، متخصص في هندسة الطيران مع شغف كبير بتحليل الاهتزازات، تصميم الهياكل، ومحاكاة أداء الأجنحة باستخدام البرمجيات الهندسية. أعمل على تطوير حلول ذكية لتحسين كفاءة الأنظمة الجوية.
  </p>
</section>

<section id="skills">
  <h2>المهارات</h2>
  <div class="card">
    <ul>
      <li>🔧 تحليل اهتزازات الهياكل باستخدام ANSYS</li>
      <li>✈️ تصميم أجنحة وتقييم الأداء الديناميكي</li>
      <li>💻 برمجة ومحاكاة باستخدام MATLAB / Simulink</li>
      <li>🛠️ CAD وSolidWorks للتصميم ثلاثي الأبعاد</li>
      <li>📊 كتابة تقارير هندسية وعرض النتائج</li>
    </ul>
  </div>
</section>

<section id="projects">
  <h2>الأعمال والمشاريع</h2>
  <div class="card">
    <h3>تحليل مودال لجناح A320</h3>
    <p>تم تحليل الأوضاع الطبيعية والاهتزازات باستخدام عناصر محدودة (FEA) لمواد مختلفة بهدف مقارنة الأداء الهيكلي.</p>
  </div>
  <div class="card">
    <h3>مشروع تحسين كفاءة محرك كهربائي للسيارات</h3>
    <p>دراسة وتعديل نظام التبريد والمسار المغناطيسي لرفع الكفاءة بنسبة 15% ضمن مشروع ME527.</p>
  </div>
</section>

<section id="publications">
  <h2>المنشورات</h2>
  <div class="card">
    <h3>Wing Structural Vibration Analysis for Composite Materials</h3>
    <p>تم تقديم هذه الورقة في مؤتمر هندسي بجامعة XYZ، وتركز على تحليل الأداء الديناميكي لأجنحة الكومبوزيت.</p>
    <a href="#">تحميل الورقة PDF</a>
  </div>
</section>

<section id="thoughts">
  <h2>أفكار</h2>
  <div class="card">
    <p>"الهندسة ليست فقط أرقامًا، بل طريقة في التفكير." 💡</p>
  </div>
  <div class="card">
    <p>"في كل اهتزاز، فرصة لاكتشاف الخلل وتصميم الحل."</p>
  </div>
</section>

<section id="contact" class="contact">
  <h2>تواصل معي</h2>
  <ul>
    <li><i class="fas fa-envelope"></i> البريد: nashat@example.com</li>
    <li><i class="fab fa-linkedin"></i> LinkedIn: <a href="#">linkedin.com/in/nashataldhoon</a></li>
    <li><i class="fab fa-github"></i> GitHub: <a href="#">github.com/nashat-aero</a></li>
  </ul>
</section>

<footer>
  &copy; 2025 - Eng. Nashat Aldhoon | جميع الحقوق محفوظة
</footer>

</body>
</html>
