<!DOCTYPE html>
html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>بشير علي محمد ثابت - مهندس برمجيات</title>
<meta name="description" content="موقع شخصي احترافي لعرض أعمال وخدمات بشير علي محمد ثابت - مهندس برمجيات متكامل">
<meta name="theme-color" content="#0D9488">
<meta property="og:title" content="بشير ثابت - مهندس برمجيات">
<meta property="og:description" content="Software Engineer | Full-Stack Developer | Mobile App Developer | UI/UX Designer | AI Engineer">
<meta property="og:type" content="website">
<link rel="manifest" href="data:application/json;base64,eyJuYW1lIjoiQmFzaGlyIFRoYWJldCBQb3J0Zm9saW8iLCJzaG9ydF9uYW1lIjoiQmFzaGlyIiwic3RhcnRfdXJsIjoiLyIsImRpc3BsYXkiOiJzdGFuZGFsb25lIiwiYmFja2dyb3VuZF9jb2xvciI6IiMwZjE3MmEiLCJ0aGVtZV9jb2xvciI6IiMwRDk0ODgifQ==">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Noto+Kufi+Arabic:wght@300;400;500;600;700;800;900&family=IBM+Plex+Sans+Arabic:wght@200;300;400;500;600;700&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
<style>
/* ===== جميع الأنماط (نفس الكود السابق) ===== */
:root {
  --bg: #f8faf9;
  --bg-secondary: #ffffff;
  --fg: #0f1f1c;
  --fg-secondary: #3d5a52;
  --muted: #6b8f83;
  --accent: #0D9488;
  --accent-light: #14b8a6;
  --accent-glow: rgba(13,148,136,0.25);
  --accent2: #D97706;
  --accent2-light: #F59E0B;
  --card: #ffffff;
  --card-hover: #f0fdf9;
  --border: #d1e5df;
  --border-light: #e8f3ef;
  --shadow: 0 4px 24px rgba(13,148,136,0.08);
  --shadow-lg: 0 12px 48px rgba(13,148,136,0.12);
  --gradient-hero: linear-gradient(135deg, #0f172a 0%, #0d2d2a 40%, #0f172a 100%);
  --gradient-accent: linear-gradient(135deg, #0D9488, #06b6d4);
  --gradient-warm: linear-gradient(135deg, #D97706, #f59e0b);
  --radius: 16px;
  --radius-sm: 10px;
  --radius-full: 9999px;
  --transition: 0.35s cubic-bezier(0.4, 0, 0.2, 1);
  --font-display: 'Noto Kufi Arabic', sans-serif;
  --font-body: 'IBM Plex Sans Arabic', sans-serif;
}

[data-theme="dark"] {
  --bg: #0a1412;
  --bg-secondary: #0f1f1c;
  --fg: #e8f3ef;
  --fg-secondary: #a3c4b8;
  --muted: #6b8f83;
  --card: #12261f;
  --card-hover: #163329;
  --border: #1a3d32;
  --border-light: #1a3d32;
  --shadow: 0 4px 24px rgba(0,0,0,0.3);
  --shadow-lg: 0 12px 48px rgba(0,0,0,0.4);
  --gradient-hero: linear-gradient(135deg, #050d0b 0%, #0a1a16 40%, #050d0b 100%);
}

*, *::before, *::after { margin: 0; padding: 0; box-sizing: border-box; }
html { scroll-behavior: smooth; font-size: 16px; }
body {
  font-family: var(--font-body);
  background: var(--bg);
  color: var(--fg);
  line-height: 1.8;
  overflow-x: hidden;
  transition: background var(--transition), color var(--transition);
}
::-webkit-scrollbar { width: 8px; }
::-webkit-scrollbar-track { background: var(--bg); }
::-webkit-scrollbar-thumb { background: var(--accent); border-radius: 4px; }
::-webkit-scrollbar-thumb:hover { background: var(--accent-light); }

.container { max-width: 1200px; margin: 0 auto; padding: 0 24px; }

/* ===== شريط التنقل ===== */
.navbar {
  position: fixed; top: 0; right: 0; left: 0; z-index: 1000;
  background: rgba(248,250,249,0.85);
  backdrop-filter: blur(20px) saturate(180%);
  -webkit-backdrop-filter: blur(20px) saturate(180%);
  border-bottom: 1px solid var(--border-light);
  transition: all var(--transition);
}
[data-theme="dark"] .navbar { background: rgba(10,20,18,0.88); }
.navbar.scrolled { box-shadow: var(--shadow); }
.navbar-inner {
  display: flex; align-items: center; justify-content: space-between;
  padding: 14px 24px; max-width: 1200px; margin: 0 auto;
}
.nav-logo {
  font-family: var(--font-display); font-size: 1.5rem; font-weight: 800;
  background: var(--gradient-accent); -webkit-background-clip: text;
  -webkit-text-fill-color: transparent; background-clip: text;
  text-decoration: none; letter-spacing: -0.5px;
}
.nav-links { display: flex; align-items: center; gap: 6px; list-style: none; }
.nav-links a {
  text-decoration: none; color: var(--fg-secondary); font-size: 0.88rem;
  font-weight: 500; padding: 6px 14px; border-radius: var(--radius-full);
  transition: all var(--transition); position: relative;
}
.nav-links a:hover, .nav-links a.active {
  color: var(--accent); background: var(--accent-glow);
}
.nav-actions { display: flex; align-items: center; gap: 8px; }
.nav-btn {
  width: 40px; height: 40px; border: 1px solid var(--border); border-radius: 50%;
  background: var(--card); color: var(--fg-secondary); cursor: pointer;
  display: flex; align-items: center; justify-content: center;
  transition: all var(--transition); font-size: 1rem;
}
.nav-btn:hover { border-color: var(--accent); color: var(--accent); transform: scale(1.05); }
.nav-toggle { display: none; }

.mobile-menu {
  display: none; position: fixed; inset: 0; z-index: 999;
  background: rgba(10,20,18,0.95); backdrop-filter: blur(20px);
  flex-direction: column; align-items: center; justify-content: center; gap: 12px;
}
.mobile-menu.open { display: flex; }
.mobile-menu a {
  text-decoration: none; color: var(--fg); font-size: 1.25rem;
  font-weight: 600; padding: 12px 32px; border-radius: var(--radius-sm);
  transition: all var(--transition); font-family: var(--font-display);
}
.mobile-menu a:hover { color: var(--accent); background: var(--accent-glow); }
.mobile-close {
  position: absolute; top: 20px; left: 20px; background: none;
  border: none; color: var(--fg); font-size: 1.8rem; cursor: pointer;
}

/* ===== بقية الأنماط ===== */
.hero { min-height: 100vh; display: flex; align-items: center; justify-content: center; position: relative; overflow: hidden; padding: 120px 24px 80px; background: var(--gradient-hero); }
.hero-bg-grid { position: absolute; inset: 0; background-image: linear-gradient(rgba(13,148,136,0.06) 1px, transparent 1px), linear-gradient(90deg, rgba(13,148,136,0.06) 1px, transparent 1px); background-size: 60px 60px; animation: gridMove 20s linear infinite; }
@keyframes gridMove { 0% { transform: translate(0,0); } 100% { transform: translate(60px,60px); } }
.hero-glow { position: absolute; width: 600px; height: 600px; border-radius: 50%; filter: blur(120px); opacity: 0.15; pointer-events: none; }
.hero-glow-1 { top: -200px; right: -100px; background: var(--accent); }
.hero-glow-2 { bottom: -200px; left: -100px; background: var(--accent2); }
.hero-particles { position: absolute; inset: 0; pointer-events: none; }
.particle { position: absolute; width: 3px; height: 3px; background: var(--accent); border-radius: 50%; opacity: 0; animation: particleFloat 6s ease-in-out infinite; }
@keyframes particleFloat { 0% { opacity: 0; transform: translateY(0) scale(0); } 20% { opacity: 0.8; } 100% { opacity: 0; transform: translateY(-400px) scale(1); } }
.hero-content { text-align: center; position: relative; z-index: 2; max-width: 800px; }
.hero-badge { display: inline-flex; align-items: center; gap: 8px; background: rgba(13,148,136,0.15); border: 1px solid rgba(13,148,136,0.3); padding: 8px 20px; border-radius: var(--radius-full); color: var(--accent-light); font-size: 0.85rem; font-weight: 500; margin-bottom: 28px; animation: fadeInDown 0.8s ease; }
.hero-badge .dot { width: 8px; height: 8px; background: #22c55e; border-radius: 50%; animation: pulse 2s infinite; }
@keyframes pulse { 0%,100% { opacity: 1; } 50% { opacity: 0.4; } }
.hero-name { font-family: var(--font-display); font-size: clamp(2.5rem, 7vw, 4.5rem); font-weight: 900; color: #ffffff; line-height: 1.2; margin-bottom: 20px; animation: fadeInUp 0.8s ease 0.2s both; }
.hero-name .highlight { background: var(--gradient-accent); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text; }
.hero-role { font-size: clamp(0.95rem, 2.5vw, 1.2rem); color: rgba(255,255,255,0.6); font-weight: 300; margin-bottom: 16px; animation: fadeInUp 0.8s ease 0.4s both; }
.hero-role span { color: var(--accent-light); font-weight: 500; }
.hero-phones { display: flex; justify-content: center; gap: 16px; margin-bottom: 36px; animation: fadeInUp 0.8s ease 0.5s both; flex-wrap: wrap; }
.hero-phone { display: inline-flex; align-items: center; gap: 8px; color: rgba(255,255,255,0.7); font-size: 0.95rem; font-weight: 400; text-decoration: none; padding: 8px 18px; border-radius: var(--radius-full); border: 1px solid rgba(255,255,255,0.12); transition: all var(--transition); direction: ltr; }
.hero-phone:hover { border-color: var(--accent); color: var(--accent-light); background: rgba(13,148,136,0.1); }
.hero-cta { display: flex; gap: 16px; justify-content: center; flex-wrap: wrap; animation: fadeInUp 0.8s ease 0.6s both; }
.btn { display: inline-flex; align-items: center; gap: 10px; padding: 14px 32px; border-radius: var(--radius-full); font-family: var(--font-body); font-size: 0.95rem; font-weight: 600; text-decoration: none; cursor: pointer; border: none; transition: all var(--transition); position: relative; overflow: hidden; }
.btn-primary { background: var(--gradient-accent); color: #fff; box-shadow: 0 4px 20px var(--accent-glow); }
.btn-primary:hover { transform: translateY(-2px); box-shadow: 0 8px 30px rgba(13,148,136,0.4); }
.btn-outline { background: transparent; color: #fff; border: 1.5px solid rgba(255,255,255,0.25); }
.btn-outline:hover { border-color: var(--accent); color: var(--accent-light); background: rgba(13,148,136,0.08); }
.btn-sm { padding: 10px 22px; font-size: 0.85rem; }
.btn-accent2 { background: var(--gradient-warm); color: #fff; box-shadow: 0 4px 20px rgba(217,119,6,0.25); }
.btn-accent2:hover { transform: translateY(-2px); box-shadow: 0 8px 30px rgba(217,119,6,0.4); }
.hero-scroll { position: absolute; bottom: 40px; left: 50%; transform: translateX(-50%); display: flex; flex-direction: column; align-items: center; gap: 8px; color: rgba(255,255,255,0.4); font-size: 0.8rem; animation: bounce 2s infinite; }
@keyframes bounce { 0%,100% { transform: translateX(-50%) translateY(0); } 50% { transform: translateX(-50%) translateY(10px); } }

.section { padding: 100px 0; }
.section-header { text-align: center; margin-bottom: 60px; }
.section-label { display: inline-flex; align-items: center; gap: 8px; color: var(--accent); font-size: 0.85rem; font-weight: 600; text-transform: uppercase; letter-spacing: 2px; margin-bottom: 12px; }
.section-label::before, .section-label::after { content: ''; width: 30px; height: 2px; background: var(--accent); opacity: 0.4; }
.section-title { font-family: var(--font-display); font-size: clamp(1.8rem, 4vw, 2.6rem); font-weight: 800; color: var(--fg); line-height: 1.3; margin-bottom: 16px; }
.section-desc { color: var(--muted); font-size: 1.05rem; max-width: 600px; margin: 0 auto; }

.about-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 60px; align-items: center; }
.about-image-wrap { position: relative; }
.about-image { width: 100%; aspect-ratio: 4/5; border-radius: var(--radius); background: var(--gradient-accent); position: relative; overflow: hidden; box-shadow: var(--shadow-lg); }
.about-image::after { content: ''; position: absolute; inset: 0; background: url("data:image/svg+xml,%3Csvg width='60' height='60' viewBox='0 0 60 60' xmlns='http://www.w3.org/2000/svg'%3E%3Cg fill='none' fill-rule='evenodd'%3E%3Cg fill='%23ffffff' fill-opacity='0.05'%3E%3Cpath d='M36 34v-4h-2v4h-4v2h4v4h2v-4h4v-2h-4zm0-30V0h-2v4h-4v2h4v4h2V6h4V4h-4zM6 34v-4H4v4H0v2h4v4h2v-4h4v-2H6zM6 4V0H4v4H0v2h4v4h2V6h4V4H6z'/%3E%3C/g%3E%3C/g%3E%3C/svg%3E"); }
.about-image-text { position: absolute; inset: 0; display: flex; align-items: center; justify-content: center; font-family: var(--font-display); font-size: 4rem; font-weight: 900; color: rgba(255,255,255,0.2); }
.about-float-card { position: absolute; bottom: -20px; left: -20px; background: var(--card); border-radius: var(--radius); padding: 20px 24px; box-shadow: var(--shadow-lg); border: 1px solid var(--border-light); }
.about-float-card .number { font-family: var(--font-display); font-size: 2rem; font-weight: 800; color: var(--accent); }
.about-float-card .label { font-size: 0.85rem; color: var(--muted); }
.about-text h3 { font-family: var(--font-display); font-size: 1.8rem; font-weight: 700; margin-bottom: 20px; color: var(--fg); }
.about-text p { color: var(--fg-secondary); margin-bottom: 16px; line-height: 2; }
.about-stats { display: grid; grid-template-columns: repeat(3,1fr); gap: 20px; margin-top: 32px; }
.about-stat { text-align: center; padding: 20px; background: var(--card); border-radius: var(--radius-sm); border: 1px solid var(--border-light); }
.about-stat .num { font-family: var(--font-display); font-size: 1.8rem; font-weight: 800; color: var(--accent); }
.about-stat .txt { font-size: 0.8rem; color: var(--muted); margin-top: 4px; }

.skills-section { background: var(--bg-secondary); }
.skills-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(350px, 1fr)); gap: 24px; }
.skill-card { background: var(--card); border: 1px solid var(--border-light); border-radius: var(--radius); padding: 28px; transition: all var(--transition); position: relative; overflow: hidden; }
.skill-card::before { content: ''; position: absolute; top: 0; right: 0; width: 4px; height: 0; background: var(--gradient-accent); transition: height var(--transition); border-radius: 0 0 4px 0; }
.skill-card:hover { transform: translateY(-4px); box-shadow: var(--shadow-lg); border-color: var(--accent); }
.skill-card:hover::before { height: 100%; }
.skill-card-icon { width: 50px; height: 50px; border-radius: 12px; background: var(--accent-glow); display: flex; align-items: center; justify-content: center; color: var(--accent); font-size: 1.3rem; margin-bottom: 16px; }
.skill-card h4 { font-family: var(--font-display); font-weight: 700; font-size: 1.05rem; margin-bottom: 12px; }
.skill-tags { display: flex; flex-wrap: wrap; gap: 8px; }
.skill-tag { padding: 4px 12px; border-radius: var(--radius-full); font-size: 0.78rem; background: var(--bg); color: var(--fg-secondary); border: 1px solid var(--border-light); font-weight: 500; }
.skill-bar-wrap { margin-top: 16px; }
.skill-bar-label { display: flex; justify-content: space-between; font-size: 0.82rem; margin-bottom: 6px; color: var(--muted); }
.skill-bar { height: 6px; background: var(--border-light); border-radius: 3px; overflow: hidden; }
.skill-bar-fill { height: 100%; border-radius: 3px; background: var(--gradient-accent); width: 0; transition: width 1.5s cubic-bezier(0.4, 0, 0.2, 1); }

.services-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(280px, 1fr)); gap: 24px; }
.service-card { background: var(--card); border: 1px solid var(--border-light); border-radius: var(--radius); padding: 36px 28px; text-align: center; transition: all var(--transition); position: relative; overflow: hidden; }
.service-card::after { content: ''; position: absolute; bottom: 0; left: 0; right: 0; height: 3px; background: var(--gradient-accent); transform: scaleX(0); transition: transform var(--transition); }
.service-card:hover { transform: translateY(-6px); box-shadow: var(--shadow-lg); }
.service-card:hover::after { transform: scaleX(1); }
.service-icon { width: 72px; height: 72px; border-radius: 20px; margin: 0 auto 20px; background: var(--accent-glow); display: flex; align-items: center; justify-content: center; color: var(--accent); font-size: 1.8rem; }
.service-card h4 { font-family: var(--font-display); font-size: 1.2rem; font-weight: 700; margin-bottom: 12px; }
.service-card p { color: var(--muted); font-size: 0.9rem; margin-bottom: 20px; }
.service-price { font-weight: 600; color: var(--accent); font-size: 0.85rem; }

.projects-section { background: var(--bg-secondary); }
.projects-filter { display: flex; justify-content: center; gap: 12px; margin-bottom: 40px; flex-wrap: wrap; }
.filter-btn { padding: 8px 20px; border-radius: var(--radius-full); border: 1px solid var(--border); background: var(--card); color: var(--fg-secondary); cursor: pointer; transition: all var(--transition); font-size: 0.88rem; font-weight: 500; }
.filter-btn.active, .filter-btn:hover { background: var(--accent); color: #fff; border-color: var(--accent); }
.projects-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(350px, 1fr)); gap: 30px; }
.project-card { background: var(--card); border-radius: var(--radius); overflow: hidden; border: 1px solid var(--border-light); transition: all var(--transition); display: flex; flex-direction: column; }
.project-card:hover { transform: translateY(-8px); box-shadow: var(--shadow-lg); border-color: var(--accent); }
.project-img { width: 100%; aspect-ratio: 16/10; background: var(--gradient-hero); position: relative; overflow: hidden; display: flex; align-items: center; justify-content: center; }
.project-img i { font-size: 4rem; color: rgba(255,255,255,0.15); transition: all var(--transition); }
.project-card:hover .project-img i { transform: scale(1.1) rotate(5deg); color: var(--accent-light); }
.project-overlay { position: absolute; inset: 0; background: rgba(13,148,136,0.9); display: flex; align-items: center; justify-content: center; gap: 16px; opacity: 0; transition: all var(--transition); }
.project-card:hover .project-overlay { opacity: 1; }
.project-link { width: 45px; height: 45px; border-radius: 50%; background: #fff; color: var(--accent); display: flex; align-items: center; justify-content: center; text-decoration: none; font-size: 1.1rem; transition: all var(--transition); }
.project-link:hover { transform: scale(1.1); background: var(--accent2); color: #fff; }
.project-content { padding: 24px; flex-grow: 1; display: flex; flex-direction: column; }
.project-cat { font-size: 0.75rem; color: var(--accent); font-weight: 600; text-transform: uppercase; margin-bottom: 8px; display: block; }
.project-title { font-family: var(--font-display); font-size: 1.25rem; font-weight: 700; margin-bottom: 12px; color: var(--fg); }
.project-desc { color: var(--muted); font-size: 0.9rem; margin-bottom: 20px; flex-grow: 1; }
.project-techs { display: flex; flex-wrap: wrap; gap: 8px; }
.project-tech { font-size: 0.72rem; padding: 3px 10px; background: var(--bg); border-radius: 4px; color: var(--fg-secondary); border: 1px solid var(--border-light); }

.certificates-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(280px, 1fr)); gap: 24px; }
.cert-card { background: var(--card); border: 1px solid var(--border-light); border-radius: var(--radius); padding: 24px; display: flex; gap: 16px; align-items: center; transition: all var(--transition); }
.cert-card:hover { transform: translateX(-5px); border-color: var(--accent); box-shadow: var(--shadow); }
.cert-icon { width: 50px; height: 50px; border-radius: 12px; background: var(--accent-glow); display: flex; align-items: center; justify-content: center; color: var(--accent); font-size: 1.2rem; flex-shrink: 0; }
.cert-info h4 { font-size: 0.95rem; font-weight: 700; margin-bottom: 4px; }
.cert-info p { font-size: 0.8rem; color: var(--muted); }

.clients-section { background: var(--bg-secondary); }
.clients-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(320px, 1fr)); gap: 24px; }
.client-card { background: var(--card); border: 1px solid var(--border-light); border-radius: var(--radius); padding: 32px; position: relative; }
.client-quote { position: absolute; top: 20px; left: 20px; font-size: 3rem; color: var(--accent-glow); font-family: serif; line-height: 1; }
.client-text { font-size: 0.95rem; color: var(--fg-secondary); margin-bottom: 24px; position: relative; z-index: 1; font-style: italic; }
.client-info { display: flex; align-items: center; gap: 14px; }
.client-avatar { width: 48px; height: 48px; border-radius: 50%; background: var(--gradient-accent); display: flex; align-items: center; justify-content: center; color: #fff; font-weight: 700; }
.client-details h4 { font-size: 0.95rem; font-weight: 700; }
.client-details p { font-size: 0.78rem; color: var(--muted); }
.client-stars { color: #fbbf24; font-size: 0.8rem; margin-top: 4px; }

.faq-list { max-width: 800px; margin: 0 auto; display: flex; flex-direction: column; gap: 16px; }
.faq-item { background: var(--card); border: 1px solid var(--border-light); border-radius: var(--radius-sm); overflow: hidden; transition: all var(--transition); }
.faq-question { padding: 20px 24px; display: flex; justify-content: space-between; align-items: center; cursor: pointer; font-weight: 600; color: var(--fg); transition: all var(--transition); }
.faq-question:hover { background: var(--card-hover); color: var(--accent); }
.faq-question i { transition: transform var(--transition); font-size: 0.8rem; }
.faq-item.active .faq-question { background: var(--accent-glow); color: var(--accent); }
.faq-item.active .faq-question i { transform: rotate(180deg); }
.faq-answer { padding: 0 24px; max-height: 0; overflow: hidden; transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1); color: var(--fg-secondary); font-size: 0.92rem; }
.faq-item.active .faq-answer { padding: 0 24px 20px; max-height: 200px; }

.contact-grid { display: grid; grid-template-columns: 1fr 1.5fr; gap: 40px; }
.contact-info-cards { display: flex; flex-direction: column; gap: 16px; }
.contact-info-card { background: var(--card); border: 1px solid var(--border-light); border-radius: var(--radius-sm); padding: 20px; display: flex; gap: 16px; align-items: center; transition: all var(--transition); }
.contact-info-card:hover { transform: translateX(-8px); border-color: var(--accent); }
.contact-info-icon { width: 48px; height: 48px; border-radius: 12px; background: var(--accent-glow); display: flex; align-items: center; justify-content: center; color: var(--accent); font-size: 1.2rem; }
.contact-info-card h4 { font-size: 0.9rem; color: var(--muted); font-weight: 500; margin-bottom: 2px; }
.contact-info-card p { font-size: 1rem; font-weight: 600; color: var(--fg); }
.contact-form { background: var(--card); border: 1px solid var(--border-light); border-radius: var(--radius); padding: 40px; box-shadow: var(--shadow); }
.form-row { display: grid; grid-template-columns: 1fr 1fr; gap: 20px; margin-bottom: 20px; }
.form-group { margin-bottom: 20px; }
.form-group label { display: block; font-size: 0.85rem; font-weight: 600; color: var(--fg-secondary); margin-bottom: 8px; }
.form-group input, .form-group select, .form-group textarea { width: 100%; padding: 12px 16px; border-radius: 8px; border: 1px solid var(--border); background: var(--bg); color: var(--fg); font-family: var(--font-body); font-size: 0.95rem; transition: all var(--transition); }
.form-group input:focus, .form-group select:focus, .form-group textarea:focus { outline: none; border-color: var(--accent); box-shadow: 0 0 0 4px var(--accent-glow); }
.form-group textarea { height: 120px; resize: vertical; }

.footer { background: var(--bg-secondary); padding: 80px 0 30px; border-top: 1px solid var(--border-light); }
.footer-grid { display: grid; grid-template-columns: 2fr 1fr 1fr 1.5fr; gap: 40px; margin-bottom: 60px; }
.footer-brand p { color: var(--muted); font-size: 0.92rem; margin: 20px 0 24px; max-width: 300px; }
.footer-social { display: flex; gap: 12px; }
.footer-social a { width: 36px; height: 36px; border-radius: 50%; background: var(--bg); color: var(--fg-secondary); display: flex; align-items: center; justify-content: center; text-decoration: none; transition: all var(--transition); border: 1px solid var(--border-light); }
.footer-social a:hover { background: var(--accent); color: #fff; border-color: var(--accent); transform: translateY(-3px); }
.footer h4 { font-family: var(--font-display); font-size: 1.1rem; font-weight: 700; margin-bottom: 24px; color: var(--fg); }
.footer-links { list-style: none; }
.footer-links li { margin-bottom: 12px; }
.footer-links a { text-decoration: none; color: var(--muted); font-size: 0.9rem; transition: all var(--transition); }
.footer-links a:hover { color: var(--accent); padding-right: 5px; }
.footer-bottom { border-top: 1px solid var(--border-light); padding-top: 30px; text-align: center; color: var(--muted); font-size: 0.85rem; }

.back-to-top { position: fixed; bottom: 30px; right: 30px; width: 45px; height: 45px; border-radius: 50%; background: var(--accent); color: #fff; border: none; cursor: pointer; display: flex; align-items: center; justify-content: center; font-size: 1rem; opacity: 0; visibility: hidden; transition: all var(--transition); z-index: 99; box-shadow: 0 4px 12px rgba(13,148,136,0.3); }
.back-to-top.show { opacity: 1; visibility: visible; }
.back-to-top:hover { transform: translateY(-5px); background: var(--accent2); }

.chat-widget { position: fixed; bottom: 30px; left: 30px; z-index: 1000; }
.chat-toggle { width: 56px; height: 56px; border-radius: 50%; background: var(--gradient-accent); color: #fff; border: none; cursor: pointer; display: flex; align-items: center; justify-content: center; font-size: 1.5rem; box-shadow: 0 8px 24px rgba(13,148,136,0.3); transition: all var(--transition); position: relative; }
.chat-toggle:hover { transform: scale(1.05) rotate(5deg); }
.chat-toggle .badge { position: absolute; top: -2px; right: -2px; width: 20px; height: 20px; border-radius: 50%; background: var(--accent2); border: 2px solid #fff; font-size: 0.7rem; font-weight: 700; display: flex; align-items: center; justify-content: center; }
.chat-window { position: absolute; bottom: 70px; left: 0; width: 320px; background: var(--card); border-radius: var(--radius); box-shadow: var(--shadow-lg); border: 1px solid var(--border-light); display: none; flex-direction: column; overflow: hidden; transform-origin: bottom left; animation: chatOpen 0.3s cubic-bezier(0.4, 0, 0.2, 1); }
@keyframes chatOpen { from { opacity: 0; transform: scale(0.8); } to { opacity: 1; transform: scale(1); } }
.chat-window.open { display: flex; }
.chat-header { background: var(--gradient-accent); padding: 16px 20px; color: #fff; display: flex; justify-content: space-between; align-items: center; }
.chat-header h4 { font-size: 0.95rem; font-weight: 600; }
.chat-header button { background: none; border: none; color: #fff; cursor: pointer; font-size: 1rem; opacity: 0.8; }
.chat-messages { height: 300px; padding: 20px; overflow-y: auto; display: flex; flex-direction: column; gap: 12px; }
.chat-msg { padding: 10px 14px; border-radius: 14px; font-size: 0.88rem; max-width: 85%; line-height: 1.5; }
.chat-msg.bot { background: var(--bg); color: var(--fg); border-bottom-right-radius: 2px; align-self: flex-start; }
.chat-msg.user { background: var(--accent); color: #fff; border-bottom-left-radius: 2px; align-self: flex-end; }
.chat-input-wrap { padding: 12px 16px; border-top: 1px solid var(--border-light); display: flex; gap: 10px; }
.chat-input-wrap input { flex-grow: 1; border: none; background: var(--bg); padding: 8px 12px; border-radius: 20px; font-size: 0.85rem; }
.chat-input-wrap input:focus { outline: none; }
.chat-input-wrap button { background: none; border: none; color: var(--accent); cursor: pointer; font-size: 1rem; }

@media (max-width: 992px) {
  .about-grid, .contact-grid { grid-template-columns: 1fr; }
  .footer-grid { grid-template-columns: 1fr 1fr; }
  .nav-links { display: none; }
  .nav-toggle { display: flex; }
}
@media (max-width: 600px) {
  .form-row { grid-template-columns: 1fr; }
  .footer-grid { grid-template-columns: 1fr; }
  .hero-phones { flex-direction: column; align-items: center; }
  .hero-cta { flex-direction: column; width: 100%; }
  .btn { width: 100%; justify-content: center; }
}

.reveal { opacity: 0; transform: translateY(30px); transition: all 0.8s ease-out; }
.reveal.active { opacity: 1; transform: translateY(0); }
.reveal-delay-1 { transition-delay: 0.2s; }
.reveal-delay-2 { transition-delay: 0.4s; }
.reveal-delay-3 { transition-delay: 0.6s; }
</style>
</head>
<body>

<nav class="navbar" id="navbar">
  <div class="navbar-inner">
    <a href="#hero" class="nav-logo">بشير.</a>
    <ul class="nav-links">
      <li><a href="#hero" class="active">الرئيسية</a></li>
      <li><a href="#about">نبذة عني</a></li>
      <li><a href="#skills">المهارات</a></li>
      <li><a href="#services">الخدمات</a></li>
      <li><a href="#projects">المشاريع</a></li>
      <li><a href="#contact">تواصل معي</a></li>
    </ul>
    <div class="nav-actions">
      <button class="nav-btn" id="themeToggle" aria-label="تبديل الوضع الليلي"><i class="fas fa-moon"></i></button>
      <button class="nav-btn nav-toggle" id="menuToggle" aria-label="القائمة"><i class="fas fa-bars"></i></button>
      <a href="#contact" class="btn btn-primary btn-sm" style="margin-right:8px;"><i class="fas fa-rocket"></i> وظفني</a>
    </div>
  </div>
</nav>

<div class="mobile-menu" id="mobileMenu">
  <button class="mobile-close" id="menuClose"><i class="fas fa-times"></i></button>
  <a href="#hero">الرئيسية</a>
  <a href="#about">نبذة عني</a>
  <a href="#skills">المهارات</a>
  <a href="#services">الخدمات</a>
  <a href="#projects">المشاريع</a>
  <a href="#contact">تواصل معي</a>
</div>

<section class="hero" id="hero">
  <div class="hero-bg-grid"></div>
  <div class="hero-glow hero-glow-1"></div>
  <div class="hero-glow hero-glow-2"></div>
  <div class="hero-particles" id="heroParticles"></div>
  <div class="hero-content">
    <div class="hero-badge">
      <span class="dot"></span> متاح للمشاريع الجديدة
    </div>
    <h1 class="hero-name">أهلاً، أنا <span class="highlight">بشير ثابت</span></h1>
    <p class="hero-role">
      <span>مهندس برمجيات</span> | مطور تطبيقات متكامل | مصمم واجهات مستخدم | مهندس ذكاء اصطناعي
    </p>
    <div class="hero-phones">
      <a href="tel:+967776430697" class="hero-phone"><i class="fas fa-phone"></i> 776430697</a>
      <a href="tel:+967777962396" class="hero-phone"><i class="fas fa-phone"></i> 777962396</a>
    </div>
    <div class="hero-cta">
      <a href="#contact" class="btn btn-primary"><i class="fas fa-paper-plane"></i> تواصل معي</a>
      <a href="#projects" class="btn btn-outline"><i class="fas fa-eye"></i> معرض الأعمال</a>
    </div>
  </div>
  <div class="hero-scroll"><i class="fas fa-chevron-down"></i> اكتشف المزيد</div>
</section>

<!-- ===== قسم نبذة عني ===== -->
<section class="section" id="about">
  <div class="container">
    <div class="about-grid">
      <div class="about-image-wrap reveal">
        <div class="about-image">
          <div class="about-image-text">BT</div>
        </div>
        <div class="about-float-card">
          <div class="number">+5</div>
          <div class="label">سنوات خبرة</div>
        </div>
      </div>
      <div class="about-text reveal reveal-delay-2">
        <h3>نبذة عني</h3>
        <p>أنا بشير علي محمد ثابت، مهندس برمجيات متخصص في تطوير الويب والتطبيقات المحمولة والذكاء الاصطناعي. أعمل على تحويل الأفكار إلى منتجات رقمية احترافية تتجاوز توقعات العملاء.</p>
        <p>خبرتي تمتد عبر مجموعة واسعة من التقنيات الحديثة، من بناء واجهات المستخدم التفاعلية إلى تطوير الخدمات الخلفية المعقدة، مروراً بتصميم تجارب المستخدم المميزة وتكامل حلول الذكاء الاصطناعي.</p>
        <p>أؤمن بأن البرمجة ليست مجرد كتابة أكواد، بل هي فن صناعة حلول تُحدث فرقاً حقيقياً في حياة الناس وعملهم.</p>
        <div class="about-stats">
          <div class="about-stat">
            <div class="num" data-count="50">0</div>
            <div class="txt">مشروع منجز</div>
          </div>
          <div class="about-stat">
            <div class="num" data-count="35">0</div>
            <div class="txt">عميل سعيد</div>
          </div>
          <div class="about-stat">
            <div class="num" data-count="15">0</div>
            <div class="txt">شهادة مهنية</div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- ===== قسم المهارات ===== -->
<section class="section skills-section" id="skills">
  <div class="container">
    <div class="section-header reveal">
      <div class="section-label">الخبرات التقنية</div>
      <h2 class="section-title">المهارات والتقنيات</h2>
      <p class="section-desc">أمتلك خبرة عميقة في مجموعة شاملة من التقنيات الحديثة</p>
    </div>
    <div class="skills-grid" id="skillsGrid"></div>
  </div>
</section>

<!-- ===== قسم الخدمات ===== -->
<section class="section" id="services">
  <div class="container">
    <div class="section-header reveal">
      <div class="section-label">ما أقدمه</div>
      <h2 class="section-title">الخدمات الاحترافية</h2>
      <p class="section-desc">أقدم مجموعة متكاملة من الخدمات التقنية المصممة لتلبية احتياجات مشروعك</p>
    </div>
    <div class="services-grid" id="servicesGrid"></div>
  </div>
</section>

<!-- ===== قسم المشاريع ===== -->
<section class="section projects-section" id="projects">
  <div class="container">
    <div class="section-header reveal">
      <div class="section-label">أعمالي</div>
      <h2 class="section-title">معرض المشاريع</h2>
      <p class="section-desc">مجموعة مختارة من أحدث المشاريع التي عملت عليها</p>
    </div>
    <div class="projects-filter reveal">
      <button class="filter-btn active" data-filter="all">الكل</button>
      <button class="filter-btn" data-filter="web">تطوير الويب</button>
      <button class="filter-btn" data-filter="mobile">تطبيقات موبايل</button>
      <button class="filter-btn" data-filter="ai">ذكاء اصطناعي</button>
      <button class="filter-btn" data-filter="design">تصميم</button>
    </div>
    <div class="projects-grid" id="projectsGrid"></div>
  </div>
</section>

<!-- ===== قسم الشهادات ===== -->
<section class="section" id="certificates">
  <div class="container">
    <div class="section-header reveal">
      <div class="section-label">اعتماداتي</div>
      <h2 class="section-title">الشهادات المهنية</h2>
      <p class="section-desc">شهادات معتمدة من أعرق المنصات والمؤسسات التقنية العالمية</p>
    </div>
    <div class="certificates-grid" id="certsGrid"></div>
  </div>
</section>

<!-- ===== قسم العملاء ===== -->
<section class="section clients-section" id="clients">
  <div class="container">
    <div class="section-header reveal">
      <div class="section-label">آراء العملاء</div>
      <h2 class="section-title">ماذا يقول عملائي</h2>
      <p class="section-desc">تجارب حقيقية من عملاء تعاملت معهم في مشاريع مختلفة</p>
    </div>
    <div class="clients-grid" id="clientsGrid"></div>
  </div>
</section>

<!-- ===== قسم الأسئلة الشائعة ===== -->
<section class="section" id="faq">
  <div class="container">
    <div class="section-header reveal">
      <div class="section-label">إجابات سريعة</div>
      <h2 class="section-title">الأسئلة الشائعة</h2>
      <p class="section-desc">إجابات على أكثر الأسئلة التي تطرحها عن خدماتي وطريقة عملي</p>
    </div>
    <div class="faq-list" id="faqList"></div>
  </div>
</section>

<!-- ===== قسم التواصل ===== -->
<section class="section contact-section" id="contact">
  <div class="container">
    <div class="section-header reveal">
      <div class="section-label">تواصل معي</div>
      <h2 class="section-title">ابدأ مشروعك الآن</h2>
      <p class="section-desc">أنا جاهز لتحويل فكرتك إلى واقع رقمي. تواصل معي وسيتم الرد خلال ساعات</p>
    </div>
    <div class="contact-grid">
      <div class="contact-info-cards reveal">
        <div class="contact-info-card">
          <div class="contact-info-icon"><i class="fas fa-phone-alt"></i></div>
          <div><h4>الهاتف الأول</h4><p>+967 776 430 697</p></div>
        </div>
        <div class="contact-info-card">
          <div class="contact-info-icon"><i class="fas fa-mobile-alt"></i></div>
          <div><h4>الهاتف الثاني</h4><p>+967 777 962 396</p></div>
        </div>
        <div class="contact-info-card">
          <div class="contact-info-icon"><i class="fab fa-whatsapp"></i></div>
          <div><h4>واتساب</h4><p>+967 776 430 697</p></div>
        </div>
        <div class="contact-info-card">
          <div class="contact-info-icon"><i class="fas fa-envelope"></i></div>
          <div><h4>البريد الإلكتروني</h4><p>bashir@thabet.dev</p></div>
        </div>
        <div class="contact-info-card">
          <div class="contact-info-icon"><i class="fas fa-map-marker-alt"></i></div>
          <div><h4>الموقع</h4><p>اليمن</p></div>
        </div>
        <div style="margin-top:16px;display:flex;gap:12px;flex-wrap:wrap;">
          <a href="https://wa.me/967776430697" target="_blank" class="btn btn-sm btn-primary" style="background:#25D366;"><i class="fab fa-whatsapp"></i> واتساب مباشر</a>
          <a href="tel:+967776430697" class="btn btn-sm btn-accent2"><i class="fas fa-phone"></i> اتصل الآن</a>
        </div>
      </div>
      <form class="contact-form reveal reveal-delay-2" id="contactForm">
        <div class="form-row">
          <div class="form-group"><label for="name">الاسم الكامل</label><input type="text" id="name" placeholder="أدخل اسمك" required></div>
          <div class="form-group"><label for="email">البريد الإلكتروني</label><input type="email" id="email" placeholder="example@email.com" required dir="ltr" style="text-align:right;"></div>
        </div>
        <div class="form-row">
          <div class="form-group"><label for="phone">رقم الهاتف</label><input type="tel" id="phone" placeholder="+967..." dir="ltr" style="text-align:right;"></div>
          <div class="form-group"><label for="service">الخدمة المطلوبة</label>
            <select id="service">
              <option value="">اختر الخدمة</option>
              <option value="web">تطوير موقع ويب</option>
              <option value="mobile">تطبيق موبايل</option>
              <option value="uiux">تصميم واجهات</option>
              <option value="ai">حلول ذكاء اصطناعي</option>
              <option value="full">مشروع متكامل</option>
              <option value="other">أخرى</option>
            </select>
          </div>
        </div>
        <div class="form-group"><label for="message">رسالتك</label><textarea id="message" placeholder="اكتب تفاصيل مشروعك هنا..." required></textarea></div>
        <button type="submit" class="btn btn-primary" style="width:100%;justify-content:center;"><i class="fas fa-paper-plane"></i> إرسال الرسالة</button>
      </form>
    </div>
  </div>
</section>

<!-- ===== التذييل ===== -->
<footer class="footer">
  <div class="container">
    <div class="footer-grid">
      <div class="footer-brand">
        <a href="#hero" class="nav-logo">بشير.</a>
        <p>مهندس برمجيات متخصص في بناء حلول رقمية متكاملة. أحوّل أفكارك إلى منتجات تقنية عالية الجودة.</p>
        <div class="footer-social">
          <a href="#" aria-label="GitHub"><i class="fab fa-github"></i></a>
          <a href="#" aria-label="LinkedIn"><i class="fab fa-linkedin-in"></i></a>
          <a href="#" aria-label="Twitter"><i class="fab fa-x-twitter"></i></a>
          <a href="https://wa.me/967776430697" aria-label="WhatsApp"><i class="fab fa-whatsapp"></i></a>
          <a href="#" aria-label="Telegram"><i class="fab fa-telegram-plane"></i></a>
        </div>
      </div>
      <div><h4>روابط سريعة</h4><ul class="footer-links"><li><a href="#about">نبذة عني</a></li><li><a href="#skills">المهارات</a></li><li><a href="#services">الخدمات</a></li><li><a href="#projects">المشاريع</a></li></ul></div>
      <div><h4>المزيد</h4><ul class="footer-links"><li><a href="#certificates">الشهادات</a></li><li><a href="#clients">آراء العملاء</a></li><li><a href="#faq">الأسئلة الشائعة</a></li><li><a href="#contact">تواصل معي</a></li></ul></div>
      <div><h4>تواصل مباشر</h4><ul class="footer-links"><li><a href="tel:+967776430697" dir="ltr">+967 776 430 697</a></li><li><a href="tel:+967777962396" dir="ltr">+967 777 962 396</a></li><li><a href="mailto:bashir@thabet.dev">bashir@thabet.dev</a></li></ul></div>
    </div>
    <div class="footer-bottom"><p>&copy; <span id="footerYear"></span> بشير علي محمد ثابت. جميع الحقوق محفوظة. صُنع بشغف وكود نظيف.</p></div>
  </div>
</footer>

<!-- زر العودة للأعلى -->
<button class="back-to-top" id="backToTop" aria-label="العودة للأعلى"><i class="fas fa-arrow-up"></i></button>

<!-- ويدجت الدردشة -->
<div class="chat-widget">
  <div class="chat-window" id="chatWindow">
    <div class="chat-header"><h4><i class="fas fa-robot" style="margin-left:8px;"></i> المساعد الذكي</h4><button id="chatClose" aria-label="إغلاق"><i class="fas fa-times"></i></button></div>
    <div class="chat-messages" id="chatMessages">
      <div class="chat-msg bot">مرحباً! أنا المساعد الذكي لبشير. كيف يمكنني مساعدتك اليوم؟</div>
    </div>
    <div class="chat-input-wrap">
      <input type="text" id="chatInput" placeholder="اكتب سؤالك...">
      <button id="chatSend" aria-label="إرسال"><i class="fas fa-paper-plane"></i></button>
    </div>
  </div>
  <button class="chat-toggle" id="chatToggle" aria-label="المساعد الذكي">
    <i class="fas fa-comments"></i>
    <span class="badge">1</span>
  </button>
</div>

<script>
/* ===== البيانات ===== */
const skillsData = [
  { icon: 'fa-code', title: 'تطوير الواجهات الأمامية', tags: ['React', 'Next.js', 'Vue.js', 'TypeScript', 'Tailwind CSS'], level: 95 },
  { icon: 'fa-server', title: 'تطوير الخدمات الخلفية', tags: ['Node.js', 'Express', 'Python', 'Django', 'REST API'], level: 90 },
  { icon: 'fa-mobile-alt', title: 'تطوير تطبيقات الموبايل', tags: ['React Native', 'Flutter', 'iOS', 'Android'], level: 88 },
  { icon: 'fa-palette', title: 'تصميم واجهات المستخدم', tags: ['Figma', 'Adobe XD', 'Photoshop', 'Prototyping'], level: 92 },
  { icon: 'fa-brain', title: 'الذكاء الاصطناعي', tags: ['OpenAI API', 'TensorFlow', 'NLP', 'LLM'], level: 85 },
  { icon: 'fa-database', title: 'قواعد البيانات', tags: ['PostgreSQL', 'MongoDB', 'Firebase', 'Redis'], level: 90 },
  { icon: 'fa-cloud', title: 'النشر والبنية التحتية', tags: ['Docker', 'AWS', 'Vercel', 'CI/CD', 'Linux'], level: 82 },
  { icon: 'fa-shield-alt', title: 'الأمان والأداء', tags: ['JWT', 'OAuth', 'HTTPS', 'SEO', 'PWA'], level: 87 }
];

const servicesData = [
  { icon: 'fa-laptop-code', title: 'تطوير مواقع الويب', desc: 'مواقع ويب سريعة ومتجاوبة باستخدام أحدث التقنيات مع تحسين الأداء ومحركات البحث', price: 'يُحدد حسب المشروع', color: '#0D9488' },
  { icon: 'fa-mobile-alt', title: 'تطبيقات الموبايل', desc: 'تطبيقات أصلية ومتعددة المنصات لأنظمة iOS و Android بتجربة مستخدم سلسة', price: 'يُحدد حسب المشروع', color: '#D97706' },
  { icon: 'fa-paint-brush', title: 'تصميم UI/UX', desc: 'تصميم واجهات مستخدم جذابة وتجارب استخدام مميزة تعزز التفاعل والرضا', price: 'يُحدد حسب المشروع', color: '#8B5CF6' },
  { icon: 'fa-robot', title: 'حلول الذكاء الاصطناعي', desc: 'تكامل نماذج الذكاء الاصطناعي في تطبيقاتك مثل روبوتات المحادثة والتحليل الذكي', price: 'يُحدد حسب المشروع', color: '#EC4899' },
  { icon: 'fa-shopping-cart', title: 'المتاجر الإلكترونية', desc: 'متاجر إلكترونية متكاملة مع أنظمة الدفع وإدارة المنتجات والطلبات', price: 'يُحدد حسب المشروع', color: '#F59E0B' },
  { icon: 'fa-chart-line', title: 'لوحات التحكم', desc: 'لوحات تحكم تفاعلية مع رسوم بيانية وتقارير ديناميكية لإدارة أعمالك', price: 'يُحدد حسب المشروع', color: '#10B981' }
];

const projectsData = [
  { title: 'منصة تجارة إلكترونية متكاملة', desc: 'متجر إلكتروني شامل مع نظام دفع، إدارة مخزون، ولوحة تحكم متقدمة', cat: 'web', techs: ['Next.js', 'Stripe', 'PostgreSQL', 'Tailwind'], icon: 'fa-store' },
  { title: 'تطبيق تواصل اجتماعي', desc: 'تطبيق محمول للتواصل الاجتماعي مع ميزات البث المباشر والرسائل المشفرة', cat: 'mobile', techs: ['React Native', 'Firebase', 'WebRTC'], icon: 'fa-users' },
  { title: 'نظام إدارة المدارس', desc: 'نظام شامل لإدارة المدارس يشمل التسجيل، الدرجات، الحضور، والتقارير', cat: 'web', techs: ['Vue.js', 'Node.js', 'MongoDB'], icon: 'fa-graduation-cap' },
  { title: 'مساعد ذكي للعملاء', desc: 'روبوت محادثة ذكي مدعوم بالذكاء الاصطناعي لخدمة العملاء على مدار الساعة', cat: 'ai', techs: ['OpenAI', 'Python', 'FastAPI', 'React'], icon: 'fa-robot' },
  { title: 'تطبيق لياقة بدنية', desc: 'تطبيق لتتبع التمارين والتغذية مع خطط مخصصة وتوصيات ذكية', cat: 'mobile', techs: ['Flutter', 'Firebase', 'TensorFlow Lite'], icon: 'fa-dumbbell' },
  { title: 'لوحة تحكم تحليلات', desc: 'لوحة تحكم تفاعلية تعرض بيانات تحليلية مع رسوم بيانية وتقارير لحظية', cat: 'web', techs: ['React', 'D3.js', 'Express', 'WebSocket'], icon: 'fa-chart-pie' }
];

const certsData = [
  { icon: 'fa-certificate', title: 'Full-Stack Web Development', org: 'Meta (Coursera)', year: '2023' },
  { icon: 'fa-robot', title: 'AI for Everyone', org: 'DeepLearning.AI', year: '2023' },
  { icon: 'fa-mobile-alt', title: 'React Native Expert', org: 'Udemy', year: '2022' },
  { icon: 'fa-shield-alt', title: 'Cybersecurity Fundamentals', org: 'Google', year: '2022' }
];

const clientsData = [
  { name: 'أحمد صالح', role: 'مدير شركة تقنية', text: 'بشير مهندس محترف جداً، قام بتنفيذ المشروع في وقت قياسي وبجودة عالية تفوق التوقعات. أنصح بالتعامل معه بشدة.', stars: 5 },
  { name: 'سارة خالد', role: 'رائدة أعمال', text: 'تجربة رائعة في تصميم وتطوير متجري الإلكتروني. بشير يهتم بأدق التفاصيل ويقدم حلولاً مبتكرة.', stars: 5 },
  { name: 'محمد علي', role: 'مؤسس تطبيق موبايل', text: 'من أفضل المطورين الذين تعاملت معهم. التزام تام بالمواعيد وفهم عميق للمتطلبات التقنية.', stars: 5 }
];

const faqData = [
  { q: 'ما هي مدة تنفيذ المواقع البسيطة؟', a: 'تتراوح مدة التنفيذ للمواقع البسيطة (Landing Pages) بين 3 إلى 7 أيام عمل، حسب المتطلبات والتفاصيل المطلوبة.' },
  { q: 'هل تقدم خدمات الدعم الفني بعد التسليم؟', a: 'نعم، أقدم فترة دعم فني مجانية لمدة شهر بعد تسليم المشروع للتأكد من عمل كل شيء بسلاسة، مع إمكانية التعاقد للصيانة الدورية.' },
  { q: 'هل يمكنني التعديل على التصميم أثناء العمل؟', a: 'بالتأكد، أتبع منهجية عمل مرنة تسمح بمراجعة العمل في مراحل مختلفة وإجراء التعديلات اللازمة لضمان رضاك التام.' },
  { q: 'كيف يتم احتساب تكلفة المشروع؟', a: 'يتم احتساب التكلفة بناءً على حجم العمل، التقنيات المستخدمة، والمدة الزمنية المطلوبة. يمكنك التواصل معي للحصول على عرض سعر دقيق.' }
];

/* ===== الوظائف ===== */
document.getElementById('footerYear').textContent = new Date().getFullYear();

// توليد المهارات
const skillsGrid = document.getElementById('skillsGrid');
skillsData.forEach(skill => {
  const card = document.createElement('div');
  card.className = 'skill-card reveal';
  card.innerHTML = `
    <div class="skill-card-icon"><i class="fas ${skill.icon}"></i></div>
    <h4>${skill.title}</h4>
    <div class="skill-tags">
      ${skill.tags.map(tag => `<span class="skill-tag">${tag}</span>`).join('')}
    </div>
    <div class="skill-bar-wrap">
      <div class="skill-bar-label"><span>مستوى الخبرة</span><span>${skill.level}%</span></div>
      <div class="skill-bar"><div class="skill-bar-fill" style="width: ${skill.level}%"></div></div>
    </div>
  `;
  skillsGrid.appendChild(card);
});

// توليد الخدمات
const servicesGrid = document.getElementById('servicesGrid');
servicesData.forEach(service => {
  const card = document.createElement('div');
  card.className = 'service-card reveal';
  card.innerHTML = `
    <div class="service-icon" style="color: ${service.color}; background: ${service.color}15;"><i class="fas ${service.icon}"></i></div>
    <h4>${service.title}</h4>
    <p>${service.desc}</p>
    <div class="service-price">${service.price}</div>
  `;
  servicesGrid.appendChild(card);
});

// توليد المشاريع
const projectsGrid = document.getElementById('projectsGrid');
function renderProjects(filter = 'all') {
  projectsGrid.innerHTML = '';
  const filtered = filter === 'all' ? projectsData : projectsData.filter(p => p.cat === filter);
  filtered.forEach(p => {
    const card = document.createElement('div');
    card.className = 'project-card reveal';
    card.innerHTML = `
      <div class="project-img">
        <i class="fas ${p.icon}"></i>
        <div class="project-overlay">
          <a href="#" class="project-link" title="معاينة"><i class="fas fa-external-link-alt"></i></a>
          <a href="#" class="project-link" title="الكود"><i class="fab fa-github"></i></a>
        </div>
      </div>
      <div class="project-content">
        <span class="project-cat">${p.cat}</span>
        <h3 class="project-title">${p.title}</h3>
        <p class="project-desc">${p.desc}</p>
        <div class="project-techs">
          ${p.techs.map(t => `<span class="project-tech">${t}</span>`).join('')}
        </div>
      </div>
    `;
    projectsGrid.appendChild(card);
  });
}
renderProjects();

// فلترة المشاريع
document.querySelectorAll('.filter-btn').forEach(btn => {
  btn.addEventListener('click', () => {
    document.querySelector('.filter-btn.active').classList.remove('active');
    btn.classList.add('active');
    renderProjects(btn.dataset.filter);
  });
});

// توليد الشهادات
const certsGrid = document.getElementById('certsGrid');
certsData.forEach(cert => {
  const card = document.createElement('div');
  card.className = 'cert-card reveal';
  card.innerHTML = `
    <div class="cert-icon"><i class="fas ${cert.icon}"></i></div>
    <div class="cert-info">
      <h4>${cert.title}</h4>
      <p>${cert.org} • ${cert.year}</p>
    </div>
  `;
  certsGrid.appendChild(card);
});

// توليد آراء العملاء
const clientsGrid = document.getElementById('clientsGrid');
clientsData.forEach(client => {
  const card = document.createElement('div');
  card.className = 'client-card reveal';
  card.innerHTML = `
    <div class="client-quote">"</div>
    <p class="client-text">${client.text}</p>
    <div class="client-info">
      <div class="client-avatar">${client.name[0]}</div>
      <div class="client-details">
        <h4>${client.name}</h4>
        <p>${client.role}</p>
        <div class="client-stars">${'<i class="fas fa-star"></i>'.repeat(client.stars)}</div>
      </div>
    </div>
  `;
  clientsGrid.appendChild(card);
});

// توليد الأسئلة الشائعة
const faqList = document.getElementById('faqList');
faqData.forEach((item, index) => {
  const div = document.createElement('div');
  div.className = 'faq-item reveal';
  div.innerHTML = `
    <div class="faq-question">${item.q} <i class="fas fa-chevron-down"></i></div>
    <div class="faq-answer">${item.a}</div>
  `;
  div.addEventListener('click', () => {
    div.classList.toggle('active');
  });
  faqList.appendChild(div);
});

// شريط التنقل و
