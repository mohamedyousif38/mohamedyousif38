<!doctype html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Mohamed Yousif — Web Developer</title>
  <style>
    :root{
      --bg:#0f1724;
      --card:#0b1220;
      --accent:#0ea5a4;
      --muted:#94a3b8;
      --text:#e6eef6;
      --glass: rgba(255,255,255,0.03);
      font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      background:linear-gradient(180deg,#081026 0%, #07121a 100%);
      color:var(--text);
      min-height:100vh;
      padding:30px;
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
    }
    .container{
      max-width:980px;
      margin:0 auto;
    }
    header{
      display:flex;
      gap:20px;
      align-items:center;
      margin-bottom:20px;
    }
    .avatar{
      width:100px;
      height:100px;
      border-radius:12px;
      background:linear-gradient(135deg,var(--accent),#1fb6b3);
      display:flex;
      align-items:center;
      justify-content:center;
      font-weight:700;
      font-size:36px;
      color:#022;
      box-shadow:0 6px 20px rgba(0,0,0,0.6);
    }
    h1{margin:0;font-size:20px}
    p.lead{margin:6px 0 0;color:var(--muted);font-size:14px}
    .grid{
      display:grid;
      grid-template-columns: 1fr 320px;
      gap:20px;
      margin-top:18px;
    }
    .card{
      background:var(--card);
      border-radius:12px;
      padding:18px;
      box-shadow:0 6px 25px rgba(2,6,23,0.6);
      border:1px solid rgba(255,255,255,0.02);
    }
    .section-title{font-weight:700;margin-bottom:10px}
    .techs{display:flex;flex-wrap:wrap;gap:10px}
    .chip{background:var(--glass);padding:8px 10px;border-radius:999px;color:var(--text);font-size:13px;border:1px solid rgba(255,255,255,0.03)}
    ul.projects{list-style:none;padding:0;margin:0;display:flex;flex-direction:column;gap:12px}
    li.project{background:linear-gradient(180deg, rgba(255,255,255,0.01), transparent);padding:12px;border-radius:10px;border:1px solid rgba(255,255,255,0.02)}
    .meta{color:var(--muted);font-size:13px;margin-top:6px}
    a.cta{
      display:inline-block;
      background:var(--accent);
      color:#022;
      padding:10px 14px;
      border-radius:10px;
      text-decoration:none;
      font-weight:700;
      margin-top:10px;
    }
    .right .small{color:var(--muted);font-size:13px}
    footer{margin-top:20px;color:var(--muted);font-size:13px;text-align:center}
    @media(max-width:880px){
      .grid{grid-template-columns:1fr; padding-bottom:40px}
      header{flex-direction:row-reverse}
      .avatar{width:84px;height:84px;font-size:32px}
    }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="avatar">MY</div>
      <div>
        <h1>محمد يوسف — Web Developer</h1>
        <p class="lead">مطور Backend مختص بـ <strong>ASP.NET Core</strong> — أبني RESTful APIs آمنة وقابلة للتطوير.</p>
        <p class="lead" style="margin-top:6px;color:var(--muted)">C# · SQL Server · Entity Framework · JWT · AutoMapper</p>
      </div>
    </header>

    <div class="grid">
      <!-- main column -->
      <div>
        <div class="card">
          <div class="section-title">عنّي • About</div>
          <p style="color:var(--muted);line-height:1.6">
            أنا <strong>محمد يوسف</strong> مهتم بتطوير واجهات برمجة التطبيقات (APIs) باستخدام <strong>ASP.NET Core</strong>.
            أحب تنظيم الكود، تطبيق مبادئ SOLID، وكتابة اختبارات بسيطة. أعمل على مشاريع صغيرة لإدارة المستخدمين والمهام،
            وأتعلم تطوير واجهات أمامية بجانب تحسين مهارات الباكند.
          </p>

          <div style="margin-top:14px">
            <div class="section-title">المشاريع • Projects</div>
            <ul class="projects">
              <li class="project">
                <div style="font-weight:700">Task Management API</div>
                <div class="meta">REST API لإدارة المهام — تسجيل/تسجيل دخول JWT، CRUD للمهام، ربط المستخدم بالمهام.</div>
                <div class="meta" style="margin-top:8px">
                  <strong>Stack:</strong> ASP.NET Core • EF Core • SQL Server • AutoMapper
                </div>
                <div style="margin-top:8px">
                  <a class="cta" href="https://github.com/YourUsername/TaskManagementAPI" target="_blank">شاهد المشروع على GitHub</a>
                </div>
              </li>

              <li class="project">
                <div style="font-weight:700">Project 2 — Example</div>
                <div class="meta">مشروع تعليمي آخر أو repo صغير توضيحي.</div>
                <div class="meta" style="margin-top:8px"><strong>Stack:</strong> C# • SQL</div>
              </li>
            </ul>
          </div>
        </div>

        <div class="card" style="margin-top:16px">
          <div class="section-title">مهارات تقنية • Tech Stack</div>
          <div class="techs" style="margin-top:8px">
            <span class="chip">ASP.NET Core</span>
            <span class="chip">C#</span>
            <span class="chip">Entity Framework Core</span>
            <span class="chip">SQL Server</span>
            <span class="chip">JWT Authentication</span>
            <span class="chip">AutoMapper</span>
            <span class="chip">Swagger / Postman</span>
            <span class="chip">Git & GitHub</span>
          </div>
        </div>

        <div class="card" style="margin-top:16px">
          <div class="section-title">كيفية تشغيل المشروع • How to Run</div>
          <ol style="color:var(--muted);line-height:1.6">
            <li>انسخ المستودع: <code>git clone https://github.com/YourUsername/TaskManagementAPI.git</code></li>
            <li>حدّث ملف <code>appsettings.json</code> بقيم الاتصال وقيمة JWT key.</li>
            <li>شغّل المايجريشن: <code>dotnet ef database update</code></li>
            <li>شغّل المشروع: <code>dotnet run</code></li>
            <li>جَرِّب endpoints عبر Swagger أو Postman.</li>
          </ol>
        </div>
      </div>

      <!-- right column -->
      <aside class="right">
        <div class="card">
          <div style="display:flex;justify-content:space-between;align-items:center">
            <div>
              <div class="small">📬 تواصل • Contact</div>
              <div style="margin-top:8px;font-weight:700">Mohamed Yousif</div>
              <div class="small" style="margin-top:6px">Email: <a href="mailto:mohamed@example.com" style="color:var(--accent);text-decoration:none">mohamed@example.com</a></div>
            </div>
          </div>

          <div style="margin-top:12px">
            <div class="small">🔗 روابط</div>
            <div style="margin-top:8px;display:flex;flex-direction:column;gap:8px">
              <a href="https://github.com/YourUsername" target="_blank" style="color:var(--accent);text-decoration:none">GitHub /YourUsername</a>
              <a href="#" style="color:var(--accent);text-decoration:none">LinkedIn / your-link</a>
            </div>
          </div>

          <div style="margin-top:12px">
            <div class="small">📈 إحصائيات سريعة</div>
            <div style="margin-top:8px;color:var(--muted);font-size:13px">
              Repos: <strong>1</strong> • Stars: <strong>0</strong>
            </div>
          </div>

          <div style="margin-top:14px">
            <a class="cta" href="mohamedyousif44704@gmail.com">تواصل معي</a>
          </div>
        </div>

        <div class="card" style="margin-top:16px">
          <div class="section-title">نصيحة للمحاور • Quick note</div>
          <p style="color:var(--muted);line-height:1.6">
            أذكر في مقابلاتك أنك بنيت مشروع كامل (API) باستخدام ASP.NET Core، طبّقت JWT للأمان، وفهمت أساسيات التصميم مثل DI وRepository Pattern.
          </p>
        </div>
      </aside>
    </div>

    <footer>
      © <span id="year"></span> Mohamed Yousif • Web API Developer — ASP.NET Core
    </footer>
  </div>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
