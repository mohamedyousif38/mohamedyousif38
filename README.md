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
