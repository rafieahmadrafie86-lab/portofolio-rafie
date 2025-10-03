# portofolio-rafie
Project Teknik komputer jaringan dan telekomunikasi
<!doctype html>
<html lang="id">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>Portofolio - TJKT</title>
<meta name="description" content="Portofolio TJKT - Network, Linux, Security, IoT" />
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;800&display=swap" rel="stylesheet">
<style>
:root{
--bg:#0f1724; --card:#0b1220; --accent:#06b6d4; --muted:#94a3b8; --glass: rgba(255,255,255,0.03);
--radius:14px; --maxw:1100px;
font-family: 'Inter', system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;
}
*{box-sizing:border-box}
html,body{height:100%}
body{
margin:0; background:linear-gradient(180deg,#071022 0%, #071728 60%); color:#e6eef6; -webkit-font-smoothing:antialiased; -moz-osx-font-smoothing:grayscale; line-height:1.5;
display:flex; align-items:center; justify-content:center; padding:32px;
}
.wrap{width:100%; max-width:var(--maxw);}
header{display:flex; align-items:center; justify-content:space-between; gap:18px; margin-bottom:22px}
.brand{display:flex; align-items:center; gap:12px}
.logo{width:56px; height:56px; border-radius:12px; background:linear-gradient(135deg,var(--accent), #2563eb); display:flex; align-items:center; justify-content:center; font-weight:800; color:#021025}
.name h1{margin:0; font-size:20px}
.name p{margin:0; font-size:12px; color:var(--muted)}


.btn{background:var(--accent); color:#021025; padding:10px 14px; border-radius:10px; font-weight:700; text-decoration:none}


.grid{display:grid; grid-template-columns: 1fr 380px; gap:20px}
.card{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01)); border-radius:var(--radius); padding:22px; box-shadow: 0 6px 18px rgba(2,6,23,0.6);}


/* Hero */
.hero{display:flex; gap:18px; align-items:flex-start}
.hero-left h2{margin:0 0 10px 0; font-size:26px}
.hero-left p{color:var(--muted); margin:0 0 18px 0}
.kpis{display:flex; gap:12px}
.kpi{background:var(--glass); padding:12px; border-radius:12px; text-align:center; width:120px}
.kpi strong{display:block; font-size:18px}


/* Sidebar */
.profile{display:flex; gap:14px; align-items:center}
.avatar{width:84px; height:84px; border-radius:12px; background:linear-gradient(180deg,#1f2937,#111827); display:flex; align-items:center; justify-content:center; font-weight:800}
.skills{margin-top:16px}
.skill{margin-bottom:10px}
.skill .bar{height:10px; background:rgba(255,255,255,0.06); border-radius:999px; overflow:hidden}
.skill .fill{height:100%; width:60%; border-radius:999px; background:linear-gradient(90deg,var(--accent), #7c3aed)}


/* Projects */
.projects{display:grid; grid-template-columns:repeat(2,1fr); gap:12px; margin-top:12px}
.project{padding:12px; border-radius:10px; background:rgba(255,255,255,0.02)}
.project h4{margin:0 0 8px 0}
.tags{display:flex; gap:8px; flex-wrap:wrap}
.tag{font-size:11px; padding:6px 8px; border-radius:8px; background:rgba(255,255,255,0.03)}


/* Contact */
.contact{display:flex; gap:12px; align-items:center; justify-content:space-between}
</html>
