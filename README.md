<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="utf-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1"/>
<title>منصة التنظيم المدرسي والموارد التعليمية</title>
<link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@400;600;700;800&display=swap" rel="stylesheet">
<style>
:root{
  --ink:#0b3f43; --muted:#5d737a; --line:#e6eeee;
  --bg1:#ffffff; --bg2:#f3f7f8;
  --card:#ffffff; --accent:#0a7f79; --accent2:#3db2aa;
  --maxW:1200px;
}
*{box-sizing:border-box}
html,body{margin:0;background:linear-gradient(180deg,var(--bg1),var(--bg2));color:#0b3f43;font-family:"Tajawal",system-ui,sans-serif}
a{color:inherit;text-decoration:none}
button{font-family:inherit;cursor:pointer}

.masthead{display:flex;justify-content:center;align-items:center;padding:8px 0 0}
.masthead img{display:block;width:100%;max-width:var(--maxW);height:auto;object-fit:contain;margin-inline:auto;border-bottom:1px solid var(--line);border-radius:0}

.announce{max-width:var(--maxW);margin:10px auto 0;background:linear-gradient(90deg,#0e6462,#2f7f79);color:#eafffb;border:1px solid rgba(255,255,255,.25);border-radius:12px;padding:8px 12px;display:none;align-items:center;gap:8px}
.announce .dot{width:8px;height:8px;border-radius:50%;background:#fff}
.announce .txt{font-size:13px}
.announce .close{margin-inline-start:auto;background:rgba(255,255,255,.12);border:1px solid rgba(255,255,255,.25);color:#fff;border-radius:10px;padding:4px 10px;font-weight:700;font-size:12px}

.note{background:#fff;border:1px solid var(--line);border-radius:12px;padding:10px 12px;font-size:13px;color:#4b6166}
.note b{color:#0a6e5f}

.container{max-width:var(--maxW);margin-inline:auto;padding:10px 16px 72px}
.section{background:var(--card);border:1px solid var(--line);border-radius:16px;padding:14px;box-shadow:0 10px 22px rgba(0,0,0,.04)}
.section h2{
  margin:0 0 10px;
  font-size:18px;
  color:#0a4a46;
  display:flex;
  align-items:center;
  gap:6px;
  justify-content:flex-start;
  flex-wrap:wrap
}

.count-glow{
  font-size:13px;
  color:#00bfa5;
  margin-right:6px;
  animation:glowPulse 1.8s infinite alternate;
}

@keyframes glowPulse{from{opacity:.6}to{opacity:1}}

.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(140px,1fr));gap:10px}
.card{background:#fff;border:1px solid var(--line);border-radius:12px;padding:12px;text-align:center;cursor:pointer;transition:all .2s}
.card:hover{transform:translateY(-2px);box-shadow:0 6px 16px rgba(0,0,0,.08)}
.card img{width:60px;height:60px;object-fit:contain;margin:0 auto 8px}
.card-label{font-size:12px;color:var(--muted);margin-top:4px;line-height:1.4}

footer{text-align:center;padding:20px;color:var(--muted);font-size:12px;border-top:1px solid var(--line);margin-top:40px}
</style>
</head>
<body>

<div class="masthead">
  <img src="header.jpg" alt="Header">
</div>

<div class="announce">
  <span class="dot"></span>
  <span class="txt">عناصر جديدة متاحة الآن</span>
  <button class="close">إغلاق</button>
</div>

<div class="container">
  
  <div class="note">
    <b>ملاحظة:</b> تأكد من تحديث بيانات منصتك بانتظام للحصول على أفضل النتائج.
  </div>

  <div class="section">
    <h2>
      <span class="count-glow">📚</span>
      المنصات التعليمية
    </h2>
    <div class="grid">
      <div class="card">
        <img src="madrasati.png" alt="منصة مدرستي">
        <div class="card-label">منصة مدرستي</div>
      </div>
      <div class="card">
        <img src="teams.svg" alt="Teams">
        <div class="card-label">Microsoft Teams</div>
      </div>
      <div class="card">
        <img src="noor.svg" alt="نور">
        <div class="card-label">نظام نور</div>
      </div>
      <div class="card">
        <img src="outlook.svg" alt="Outlook">
        <div class="card-label">Outlook</div>
      </div>
      <div class="card">
        <img src="ien.svg" alt="منصة آي إن">
        <div class="card-label">منصة آي إن</div>
      </div>
      <div class="card">
        <img src="huduri.svg" alt="حضوري">
        <div class="card-label">نظام حضوري</div>
      </div>
    </div>
  </section>

  <div class="section">
    <h2>
      <span class="count-glow">🎓</span>
      الموارد التعليمية
    </h2>
    <div class="grid">
      <div class="card">
        <img src="منصة تميز 1.png" alt="منصة تميز">
        <div class="card-label">منصة تميز</div>
      </div>
      <div class="card">
        <img src="dam.svg" alt="دام">
        <div class="card-label">منصة دام</div>
      </div>
      <div class="card">
        <img src="faris.svg" alt="فارس">
        <div class="card-label">نظام فارس</div>
      </div>
    </div>
  </section>

  <div class="section">
    <h2>
      <span class="count-glow">🏢</span>
      الجهات المسؤولة
    </h2>
    <div class="grid">
      <div class="card">
        <img src="المركز الوطني للتدريب .svg" alt="المركز الوطني للتدريب">
        <div class="card-label">المركز الوطني للتدريب</div>
      </div>
      <div class="card">
        <img src="المركز الوطني للتعليم الإلكتروني.svg" alt="المركز الوطني للتعليم الإلكتروني">
        <div class="card-label">المركز الوطني للتعليم الإلكتروني</div>
      </div>
      <div class="card">
        <img src="هيئة تقويم التعليم والتدريب.svg" alt="هيئة تقويم التعليم والتدريب">
        <div class="card-label">هيئة تقويم التعليم والتدريب</div>
      </div>
    </div>
  </section>

</div>

<footer>
  <p>© 2025 منصة التنظيم المدرسي والموارد التعليمية</p>
</footer>

<script>
// Dark Mode Toggle
document.addEventListener('DOMContentLoaded', () => {
  const root = document.documentElement;
  const isDark = localStorage.getItem('darkMode') === 'true';
  
  if (isDark) {
    root.style.setProperty('--bg1', '#1a1a1a');
    root.style.setProperty('--bg2', '#2d2d2d');
    root.style.setProperty('--card', '#333');
    root.style.setProperty('--ink', '#e0e0e0');
    root.style.setProperty('--line', '#444');
  }
});

// Close Announcement
document.querySelector('.announce .close')?.addEventListener('click', function() {
  this.parentElement.style.display = 'none';
});

// Interactive Cards
document.querySelectorAll('.card').forEach(card => {
  card.addEventListener('click', function() {
    alert('تفاصيل: ' + this.querySelector('.card-label').textContent);
  });
});
</script>

</body>
</html>
