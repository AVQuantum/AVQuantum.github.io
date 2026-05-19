<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1.0">
<title>NEXUS — Sovereign Intelligence Platform</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,600;0,700;1,400&family=Lato:wght@300;400;700&display=swap" rel="stylesheet">
<script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js"></script>
<style>
:root {
  --bg:#F5EFE2; --bg2:#EDE5D4; --bg3:#E4D9C6; --bg4:#D8CDB4;
  --surface:#FAF6EE; --surface2:#F0E9DA;
  --gold:#B8972A; --gold-light:#D4AF37; --gold-dark:#8A6E1A;
  --gold-glow:rgba(184,151,42,0.18); --gold-faint:rgba(184,151,42,0.08);
  --gold-faint2:rgba(184,151,42,0.04); --gold-border:rgba(184,151,42,0.30);
  --gold-border2:rgba(184,151,42,0.15);
  --marine:#1C2B4A; --marine-light:#2E4570; --marine-mid:#243760;
  --text:#1C2B4A; --text2:#3A4F6E; --text3:#7A8BA8; --text-inv:#FAF6EE;
  --border:rgba(28,43,74,0.08); --border2:rgba(28,43,74,0.14); --border3:rgba(28,43,74,0.24);
  --success:#2A6A44; --success-light:#3ABA72; --danger:#8B2A2A; --danger-light:#E05050;
  --fd:'Playfair Display',Georgia,serif; --fm:'Lato','Helvetica Neue',sans-serif;
  --r:3px; --r-lg:6px;
  --shadow:0 4px 20px rgba(28,43,74,0.12); --shadow-sm:0 2px 8px rgba(28,43,74,0.08);
  --t:0.2s ease;
}
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0;}
html{scroll-behavior:smooth;}
body{background:var(--bg);color:var(--text);font-family:var(--fm);font-size:14px;line-height:1.65;overflow-x:hidden;}
::-webkit-scrollbar{width:4px;}
::-webkit-scrollbar-thumb{background:var(--gold-border);border-radius:2px;}
*{scrollbar-width:thin;scrollbar-color:var(--gold-border) transparent;}

/* ── NAV ── */
#nav{position:fixed;top:0;left:0;right:0;height:60px;z-index:1000;background:var(--marine);backdrop-filter:blur(20px);border-bottom:2px solid var(--gold);display:flex;align-items:center;padding:0 44px;gap:16px;transition:box-shadow .3s ease;}
#nav.scrolled{box-shadow:0 4px 32px rgba(28,43,74,0.35);}
.nav-logo-wrap{display:flex;flex-direction:column;}
.nav-brand{font-family:var(--fd);font-size:20px;font-weight:700;letter-spacing:6px;color:var(--gold-light);}
.nav-sub{font-size:7px;letter-spacing:4px;color:rgba(212,175,55,0.5);font-weight:300;text-transform:uppercase;}
.nav-sep{width:1px;height:24px;background:rgba(212,175,55,0.2);}
.nav-badge{padding:3px 10px;border:1px solid rgba(58,186,114,0.4);border-radius:2px;font-size:8px;letter-spacing:2px;font-weight:700;color:#3ABA72;display:flex;align-items:center;gap:6px;}
.nav-badge::before{content:'';width:5px;height:5px;border-radius:50%;background:#3ABA72;box-shadow:0 0 6px #3ABA72;animation:pulse 2s infinite;}
.nav-links{margin-left:auto;display:flex;align-items:center;gap:28px;}
.nav-links a{color:rgba(212,175,55,0.6);text-decoration:none;font-size:9px;letter-spacing:2px;text-transform:uppercase;font-weight:700;transition:var(--t);}
.nav-links a:hover{color:var(--gold-light);}
.nav-cta{padding:8px 22px;border-radius:2px;border:1px solid var(--gold);background:var(--gold);color:var(--marine);font-size:8px;letter-spacing:2px;font-weight:700;cursor:pointer;transition:var(--t);font-family:var(--fm);text-transform:uppercase;}
.nav-cta:hover{background:var(--gold-light);border-color:var(--gold-light);transform:translateY(-1px);}
.nav-hamburger{display:none;flex-direction:column;gap:5px;background:transparent;border:none;cursor:pointer;padding:6px;margin-left:auto;}
.nav-hamburger span{display:block;width:22px;height:2px;background:var(--gold-light);border-radius:1px;transition:var(--t);}
.nav-hamburger.open span:nth-child(1){transform:translateY(7px) rotate(45deg);}
.nav-hamburger.open span:nth-child(2){opacity:0;}
.nav-hamburger.open span:nth-child(3){transform:translateY(-7px) rotate(-45deg);}
.nav-mobile-menu{display:none;position:fixed;top:60px;left:0;right:0;background:var(--marine);border-bottom:2px solid var(--gold);z-index:999;flex-direction:column;padding:20px 24px;gap:16px;animation:slideDown .25s ease;}
.nav-mobile-menu.open{display:flex;}
.nav-mobile-menu a{color:rgba(212,175,55,0.7);text-decoration:none;font-size:13px;font-weight:700;letter-spacing:2px;text-transform:uppercase;padding:10px 0;border-bottom:1px solid rgba(212,175,55,0.1);transition:var(--t);}
.nav-mobile-menu a:hover{color:var(--gold-light);}
.nav-mobile-cta{margin-top:8px;padding:12px 24px;border-radius:2px;background:var(--gold);color:var(--marine);font-size:10px;font-weight:700;letter-spacing:2px;text-transform:uppercase;cursor:pointer;border:1px solid var(--gold-dark);font-family:var(--fm);text-align:center;}
@keyframes slideDown{from{opacity:0;transform:translateY(-10px);}to{opacity:1;transform:none;}}

/* ── LAYOUT ── */
section{position:relative;}
.sec-inner{max-width:1180px;margin:0 auto;padding:0 44px;}
.divider{height:1px;background:linear-gradient(to right,transparent,var(--gold-border),transparent);max-width:1180px;margin:0 auto;}
.sec-header{text-align:center;margin-bottom:60px;}
.sec-tag{font-size:8px;letter-spacing:4px;color:var(--gold-dark);text-transform:uppercase;font-weight:700;margin-bottom:12px;}
.sec-title{font-family:var(--fd);font-size:clamp(28px,3.8vw,48px);font-weight:600;line-height:1.2;margin-bottom:14px;color:var(--marine);}
.sec-desc{font-size:15px;color:var(--text2);max-width:560px;margin:0 auto;font-weight:300;line-height:1.85;}

/* ═══════════════════ ACCORDION SYSTEM ═══════════════════ */
.acc-list{display:flex;flex-direction:column;gap:0;border:1px solid var(--border2);border-radius:var(--r-lg);overflow:hidden;box-shadow:var(--shadow-sm);}
.acc-item{border-bottom:1px solid var(--border2);position:relative;}
.acc-item:last-child{border-bottom:none;}
.acc-header{display:flex;align-items:center;gap:16px;padding:20px 24px;cursor:pointer;background:var(--surface);transition:background .2s ease;user-select:none;position:relative;overflow:hidden;}
.acc-header::before{content:'';position:absolute;left:0;top:0;bottom:0;width:3px;background:var(--gold);transform:scaleY(0);transform-origin:center;transition:transform .3s cubic-bezier(.4,0,.2,1);}
.acc-item.open .acc-header::before{transform:scaleY(1);}
.acc-header:hover{background:var(--gold-faint2);}
.acc-item.open .acc-header{background:var(--gold-faint);}
.acc-icon{width:40px;height:40px;border-radius:var(--r);border:1px solid var(--border2);display:flex;align-items:center;justify-content:center;font-family:var(--fd);font-size:14px;color:var(--gold);font-weight:700;background:var(--bg);flex-shrink:0;transition:var(--t);}
.acc-item.open .acc-icon{background:var(--marine);color:var(--gold-light);border-color:var(--gold-border);}
.acc-meta{flex:1;}
.acc-title{font-family:var(--fd);font-size:17px;font-weight:600;color:var(--marine);line-height:1.3;margin-bottom:3px;}
.acc-subtitle{font-size:11px;color:var(--text3);font-weight:300;letter-spacing:.5px;}
.acc-right{display:flex;align-items:center;gap:12px;flex-shrink:0;}
.acc-tag{font-size:8px;letter-spacing:2px;font-weight:700;text-transform:uppercase;padding:3px 8px;border-radius:2px;border:1px solid var(--border2);color:var(--text3);}
.acc-chevron{width:22px;height:22px;border-radius:50%;border:1px solid var(--border2);display:flex;align-items:center;justify-content:center;color:var(--text3);transition:transform .3s ease,background .2s,border-color .2s;}
.acc-item.open .acc-chevron{transform:rotate(180deg);background:var(--gold);border-color:var(--gold-dark);color:var(--marine);}
.acc-body{max-height:0;overflow:hidden;transition:max-height .45s cubic-bezier(.4,0,.2,1);}
.acc-item.open .acc-body{max-height:2000px;}
.acc-content{padding:28px 24px 28px 80px;background:var(--bg);border-top:1px solid var(--border);}

/* ── ACCORDION INNER CONTENT ── */
.acc-inner-grid{display:grid;grid-template-columns:1fr 1fr;gap:24px;}
.acc-prose{font-size:13px;color:var(--text2);line-height:1.85;font-weight:300;margin-bottom:16px;}
.acc-prose strong{color:var(--marine);font-weight:700;}
.acc-kv{display:flex;flex-direction:column;gap:6px;margin-bottom:16px;}
.acc-kv-row{display:flex;justify-content:space-between;align-items:baseline;font-size:11.5px;padding:6px 0;border-bottom:1px solid var(--border);}
.acc-kv-row:last-child{border-bottom:none;}
.acc-kv-key{color:var(--text3);font-weight:300;font-family:'Consolas',monospace;font-size:10.5px;}
.acc-kv-val{color:var(--marine);font-weight:700;font-size:10.5px;}
.acc-pills-row{display:flex;gap:6px;flex-wrap:wrap;margin-top:12px;}
.acc-pill{padding:3px 10px;border-radius:2px;font-size:8px;letter-spacing:1.5px;font-weight:700;border:1px solid var(--border2);color:var(--text3);background:var(--surface);font-family:'Consolas',monospace;}
.acc-result{padding:12px 16px;background:var(--surface);border-left:2px solid var(--gold-dark);border-radius:0 var(--r) var(--r) 0;font-size:11.5px;color:var(--text2);font-weight:300;line-height:1.7;margin-top:14px;}
.acc-result strong{color:var(--marine);font-weight:700;}
.acc-code-block{background:var(--marine);border-radius:var(--r);padding:14px 16px;font-family:'Consolas',monospace;font-size:10.5px;line-height:1.9;color:rgba(212,175,55,0.7);margin-top:12px;}
.acc-code-block .hl{color:var(--gold-light);}
.acc-code-block .ok{color:var(--success-light);}
.acc-code-block .wh{color:rgba(250,246,238,0.6);}
.acc-metrics{display:grid;grid-template-columns:repeat(3,1fr);gap:8px;margin-top:16px;}
.acc-metric{background:var(--surface);border:1px solid var(--border2);border-radius:var(--r);padding:12px;text-align:center;}
.acc-metric-v{font-family:var(--fd);font-size:22px;color:var(--gold);font-weight:600;}
.acc-metric-l{font-size:8px;letter-spacing:2px;color:var(--text3);margin-top:3px;text-transform:uppercase;font-weight:700;}
.acc-steps{display:flex;flex-direction:column;gap:10px;}
.acc-step{display:flex;align-items:flex-start;gap:12px;}
.acc-step-num{width:24px;height:24px;border-radius:50%;background:var(--marine);border:1px solid var(--gold-border2);display:flex;align-items:center;justify-content:center;font-family:var(--fd);font-size:11px;color:var(--gold-light);font-weight:600;flex-shrink:0;margin-top:2px;}
.acc-step-text{font-size:12px;color:var(--text2);line-height:1.7;font-weight:300;}
.acc-step-text strong{color:var(--marine);font-weight:700;}
.acc-sec-bar{height:3px;background:var(--bg3);border-radius:2px;overflow:hidden;margin-top:12px;}
.acc-sec-bar-fill{height:100%;border-radius:2px;transition:width 1.2s cubic-bezier(.4,0,.2,1);}

/* ═══════════════════ HERO ═══════════════════ */
#hero{min-height:100vh;background:var(--marine);display:grid;grid-template-columns:1fr 1fr;align-items:center;padding-top:60px;position:relative;overflow:hidden;}
.hero-hex-bg{position:absolute;inset:0;z-index:0;opacity:.055;background-image:url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='60' height='70'%3E%3Cpolygon points='30,2 56,17 56,53 30,68 4,53 4,17' fill='none' stroke='%23D4AF37' stroke-width='1'/%3E%3C/svg%3E");background-size:60px 70px;}
.hero-radial{position:absolute;inset:0;z-index:0;background:radial-gradient(ellipse 80% 70% at 30% 50%,rgba(184,151,42,0.08) 0%,transparent 65%);}
.hero-orb-side{display:flex;flex-direction:column;align-items:center;justify-content:center;padding:80px 40px 80px 60px;position:relative;z-index:2;}
.orb-container-hero{position:relative;width:420px;height:420px;flex-shrink:0;}
#orb-canvas-hero{width:100%;height:100%;display:block;}
.orb-glow-hero{position:absolute;inset:-60px;border-radius:50%;background:radial-gradient(circle,rgba(184,151,42,0.10) 0%,transparent 60%);animation:orbPulse 4s ease-in-out infinite;pointer-events:none;}
.hero-orb-state{text-align:center;margin-top:24px;z-index:2;}
.hero-orb-label{font-family:var(--fd);font-size:20px;font-style:italic;letter-spacing:8px;color:var(--gold-light);text-shadow:0 0 30px rgba(212,175,55,0.3);transition:opacity .4s ease;}
.hero-orb-sub{font-size:8px;letter-spacing:4px;color:rgba(212,175,55,0.5);margin-top:6px;font-weight:300;text-transform:uppercase;}
.hero-orb-caps{display:flex;gap:6px;flex-wrap:wrap;justify-content:center;max-width:420px;margin-top:20px;}
.orb-cap{padding:4px 12px;border-radius:20px;font-size:8px;letter-spacing:1.5px;border:1px solid rgba(212,175,55,0.2);color:rgba(212,175,55,0.5);background:rgba(212,175,55,0.04);text-transform:uppercase;font-weight:700;cursor:pointer;transition:var(--t);}
.orb-cap:hover,.orb-cap.active{border-color:var(--gold-border);color:var(--gold-light);background:rgba(184,151,42,0.1);}
.hero-text-side{padding:80px 60px 80px 40px;position:relative;z-index:2;}
.hero-eyebrow{display:inline-flex;align-items:center;gap:8px;padding:5px 16px;border-radius:20px;margin-bottom:30px;border:1px solid rgba(58,186,114,0.3);background:rgba(58,186,114,0.07);font-size:8px;letter-spacing:3px;text-transform:uppercase;color:#3ABA72;font-weight:700;animation:fadeDown .8s ease both;}
.hero-eyebrow::before{content:'';width:5px;height:5px;border-radius:50%;background:#3ABA72;box-shadow:0 0 6px #3ABA72;animation:pulse 2s infinite;}
.hero-h1{font-family:var(--fd);font-size:clamp(38px,5vw,68px);font-weight:600;line-height:1.1;letter-spacing:.5px;margin-bottom:26px;color:var(--text-inv);animation:fadeUp .9s .15s ease both;}
.hero-h1 em{color:var(--gold-light);font-style:italic;}
.hero-desc{font-size:16px;color:rgba(240,233,218,0.75);max-width:500px;line-height:1.85;font-weight:300;margin-bottom:36px;animation:fadeUp .9s .25s ease both;}
.hero-pills{display:flex;flex-direction:column;gap:10px;margin-bottom:36px;animation:fadeUp .9s .35s ease both;}
.hero-pill-item{display:flex;align-items:center;gap:12px;font-size:12px;color:rgba(240,233,218,0.7);font-weight:300;}
.hero-pill-dot{width:4px;height:4px;border-radius:50%;background:var(--gold);flex-shrink:0;}
.hero-ctas{display:flex;gap:12px;animation:fadeUp .9s .45s ease both;}
.btn-primary{padding:14px 34px;border-radius:var(--r);cursor:pointer;font-family:var(--fm);font-size:9px;font-weight:700;letter-spacing:2.5px;text-transform:uppercase;transition:var(--t);background:var(--gold);color:var(--marine);border:1px solid var(--gold-dark);box-shadow:0 4px 24px var(--gold-glow);}
.btn-primary:hover{background:var(--gold-light);transform:translateY(-2px);box-shadow:0 8px 32px var(--gold-glow);}
.btn-secondary{padding:14px 34px;border-radius:var(--r);cursor:pointer;font-family:var(--fm);font-size:9px;font-weight:700;letter-spacing:2.5px;text-transform:uppercase;transition:var(--t);background:transparent;color:rgba(212,175,55,0.7);border:1px solid rgba(212,175,55,0.3);}
.btn-secondary:hover{border-color:var(--gold-border);color:var(--gold-light);background:rgba(184,151,42,0.08);}

/* ── STATS ── */
#stats{background:var(--surface);border-top:2px solid var(--gold);border-bottom:1px solid var(--border2);padding:0;}
.stats-grid{display:grid;grid-template-columns:repeat(5,1fr);gap:0;}
.stat-item{padding:32px 24px;text-align:center;border-right:1px solid var(--border2);position:relative;overflow:hidden;}
.stat-item::after{content:'';position:absolute;bottom:0;left:0;right:0;height:2px;background:linear-gradient(90deg,transparent,var(--gold-dark),transparent);transform:scaleX(0);transition:transform .4s ease;}
.stat-item:hover::after{transform:scaleX(1);}
.stat-item:last-child{border-right:none;}
.stat-val{font-family:var(--fd);font-size:36px;font-weight:600;color:var(--gold);line-height:1;}
.stat-label{font-size:8px;letter-spacing:3px;color:var(--text3);margin-top:8px;text-transform:uppercase;font-weight:700;}
.stat-sub{font-size:11px;color:var(--text3);margin-top:4px;font-weight:300;}

/* ── WAITLIST ── */
#waitlist{padding:90px 0;background:var(--bg);position:relative;overflow:hidden;}
.wl-bg-hex{position:absolute;inset:0;opacity:.03;background-image:url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='60' height='70'%3E%3Cpolygon points='30,2 56,17 56,53 30,68 4,53 4,17' fill='none' stroke='%231C2B4A' stroke-width='1'/%3E%3C/svg%3E");background-size:60px 70px;}
.wl-inner{max-width:800px;margin:0 auto;padding:0 44px;position:relative;z-index:2;}
.wl-header{text-align:center;margin-bottom:44px;}
.wl-eyebrow{display:inline-flex;align-items:center;gap:8px;padding:4px 16px;border-radius:2px;margin-bottom:20px;border:1px solid var(--gold-border);background:var(--gold-faint);font-size:8px;letter-spacing:3px;text-transform:uppercase;color:var(--gold);font-weight:700;}
.wl-h2{font-family:var(--fd);font-size:clamp(30px,4vw,46px);font-weight:600;line-height:1.15;margin-bottom:16px;color:var(--marine);}
.wl-desc{font-size:15px;color:var(--text2);line-height:1.85;font-weight:300;max-width:600px;margin:0 auto;}
.wl-counter{display:flex;align-items:center;justify-content:center;gap:8px;margin-top:18px;font-size:11px;color:var(--text3);font-weight:300;}
.wl-dot{width:6px;height:6px;border-radius:50%;background:#3ABA72;box-shadow:0 0 6px #3ABA72;animation:pulse 2.5s infinite;}
#wl-count{color:var(--gold);font-weight:700;}
.wl-form{background:var(--surface);border:1px solid var(--border2);border-radius:var(--r-lg);padding:36px 40px;box-shadow:var(--shadow);}
.form-row{display:grid;grid-template-columns:1fr 1fr;gap:16px;margin-bottom:16px;}
.form-row.full{grid-template-columns:1fr;}
.form-group{display:flex;flex-direction:column;gap:5px;}
.form-label{font-size:9px;letter-spacing:2px;color:var(--text3);text-transform:uppercase;font-weight:700;}
.form-input{background:var(--bg2);border:1px solid var(--border2);border-radius:var(--r);padding:10px 14px;font-family:var(--fm);font-size:13px;color:var(--text);outline:none;transition:var(--t);width:100%;}
.form-input:focus{border-color:var(--gold);background:var(--bg);box-shadow:0 0 0 3px var(--gold-faint);}
.form-select{cursor:pointer;}
.form-checkbox-row{display:flex;align-items:flex-start;gap:12px;margin-bottom:24px;margin-top:4px;}
.form-checkbox{width:15px;height:15px;accent-color:var(--gold);margin-top:3px;flex-shrink:0;cursor:pointer;}
.form-checkbox-lbl{font-size:12px;color:var(--text3);line-height:1.6;font-weight:300;cursor:pointer;}
.form-submit{width:100%;padding:14px 24px;border-radius:var(--r);background:var(--marine);border:1px solid var(--marine);color:var(--gold-light);font-family:var(--fm);font-size:10px;font-weight:700;letter-spacing:2px;text-transform:uppercase;cursor:pointer;transition:var(--t);}
.form-submit:hover{background:var(--marine-light);transform:translateY(-1px);box-shadow:0 6px 20px rgba(28,43,74,0.25);}
.form-submit:disabled{opacity:.6;cursor:not-allowed;transform:none;}
.success-box{display:none;text-align:center;padding:50px 24px;background:var(--surface);border:1px solid var(--gold-border);border-radius:var(--r-lg);}
.success-box.show{display:block;animation:fadeUp .5s ease;}
.success-icon{font-size:40px;color:var(--gold);margin-bottom:20px;}
.success-box h3{font-family:var(--fd);font-size:28px;color:var(--marine);margin-bottom:10px;}
.success-box p{font-size:14px;color:var(--text2);font-weight:300;line-height:1.7;}

/* ── AUDIENCE TOGGLE ── */
#audience-section{padding:90px 0;background:var(--surface);}
.audience-toggle{display:flex;gap:0;background:var(--bg3);border:1px solid var(--border2);border-radius:2px;padding:3px;width:fit-content;margin:20px auto 8px;}
.aud-btn{padding:9px 28px;border-radius:2px;font-size:9px;letter-spacing:2px;font-weight:700;text-transform:uppercase;cursor:pointer;transition:var(--t);background:transparent;color:var(--text3);border:none;font-family:var(--fm);}
.aud-btn.on{background:var(--marine);color:var(--gold-light);}
.aud-desc{text-align:center;font-size:11px;color:var(--text3);margin-top:8px;}
.aud-panel{display:none;}
.aud-panel.on{display:block;animation:fadeUp .4s ease both;}

/* ── WORKFLOW SECTION ── */
#workflow-section{padding:90px 0;background:var(--bg2);}
.wf-demo-wrap{background:var(--surface);border:1px solid var(--border2);border-radius:var(--r);overflow:hidden;box-shadow:var(--shadow);height:520px;display:grid;grid-template-columns:180px 1fr 200px;grid-template-rows:40px 1fr;grid-template-areas:"wf-tb wf-tb wf-tb" "wf-pal wf-canvas wf-insp";}
.wf-toolbar{grid-area:wf-tb;background:var(--marine);border-bottom:2px solid var(--gold);display:flex;align-items:center;gap:8px;padding:0 14px;}
.wf-tb-title{font-size:8px;letter-spacing:3px;color:var(--gold);font-weight:700;text-transform:uppercase;margin-right:8px;}
.wf-tb-sep{width:1px;height:20px;background:rgba(212,175,55,0.2);}
.wf-tb-count{font-size:9px;color:rgba(212,175,55,0.5);}
.wf-tb-right{margin-left:auto;display:flex;gap:6px;align-items:center;}
.wf-btn{padding:0 10px;height:24px;border-radius:2px;font-size:8px;letter-spacing:1.5px;font-weight:700;text-transform:uppercase;cursor:pointer;font-family:var(--fm);transition:var(--t);background:transparent;border:1px solid rgba(212,175,55,0.3);color:rgba(212,175,55,0.7);}
.wf-btn:hover{border-color:var(--gold);color:var(--gold-light);background:rgba(184,151,42,0.1);}
.wf-btn.gold{background:var(--gold);color:var(--marine);border-color:var(--gold-dark);}
.wf-btn.gold:hover{background:var(--gold-light);}
.wf-palette{grid-area:wf-pal;background:var(--surface);border-right:1px solid var(--border2);overflow-y:auto;}
.wf-pal-hd{padding:8px 10px 4px;font-size:8px;font-weight:700;letter-spacing:2.5px;color:var(--gold);text-transform:uppercase;border-bottom:1px solid var(--border);}
.wf-pal-sec-hd{padding:6px 10px;font-size:8px;letter-spacing:2px;font-weight:700;text-transform:uppercase;cursor:pointer;display:flex;justify-content:space-between;align-items:center;}
.wf-pal-body{padding:2px 6px 6px;}
.wf-pill{display:flex;align-items:center;gap:6px;padding:4px 7px;border-radius:2px;cursor:grab;font-size:10px;color:var(--text2);transition:var(--t);user-select:none;border:1px solid transparent;margin-bottom:1px;}
.wf-pill:hover{background:var(--gold-faint);border-color:var(--border2);color:var(--text);}
.wf-pill-dot{width:7px;height:7px;border-radius:2px;flex-shrink:0;}
.wf-canvas-wrap{grid-area:wf-canvas;position:relative;overflow:hidden;background:var(--bg);}
#wf-svg{width:100%;height:100%;}
.wf-inspector{grid-area:wf-insp;background:var(--surface);border-left:1px solid var(--border2);display:flex;flex-direction:column;overflow-y:auto;}
.wf-insp-hd{padding:10px 12px;background:var(--bg2);border-bottom:1px solid var(--border2);font-size:8px;letter-spacing:2.5px;color:var(--gold);font-weight:700;text-transform:uppercase;flex-shrink:0;}
.wf-insp-empty{flex:1;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:8px;color:var(--text3);font-size:11px;padding:20px;text-align:center;}
.wf-insp-body{padding:12px 12px;display:flex;flex-direction:column;gap:10px;}
.wf-field{display:flex;flex-direction:column;gap:4px;}
.wf-field label{font-size:8px;letter-spacing:2px;color:var(--text3);font-weight:700;text-transform:uppercase;}
.wf-field input,.wf-field select,.wf-field textarea{background:var(--bg2);border:1px solid var(--border2);border-radius:var(--r);padding:5px 8px;font-size:10px;color:var(--text);outline:none;width:100%;font-family:var(--fm);transition:var(--t);}
.wf-field input:focus,.wf-field select:focus,.wf-field textarea:focus{border-color:var(--gold);}
.wf-run-log{margin:0 12px 10px;background:var(--bg2);border:1px solid var(--border2);border-radius:var(--r);padding:8px;font-size:9px;font-family:monospace;color:var(--text2);max-height:100px;overflow-y:auto;line-height:1.8;}

/* ── AGENTS ── */
#agents{padding:90px 0;background:var(--surface);}
.agents-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(155px,1fr));gap:8px;}
.agent-card{background:var(--bg);border:1px solid var(--border2);border-radius:var(--r);padding:18px 14px;text-align:center;transition:var(--t);position:relative;overflow:hidden;cursor:pointer;}
.agent-card::before{content:'';position:absolute;top:0;left:0;right:0;height:2px;background:linear-gradient(90deg,transparent,var(--gold),transparent);opacity:0;transition:var(--t);}
.agent-card:hover{border-color:var(--gold-border);transform:translateY(-3px);box-shadow:var(--shadow-sm);}
.agent-card:hover::before{opacity:1;}
.agent-card.expanded{border-color:var(--gold-border);background:var(--gold-faint);}
.agent-status{width:7px;height:7px;border-radius:50%;background:var(--success-light);box-shadow:0 0 6px var(--success-light);margin:0 auto 10px;animation:pulse 3s infinite;}
.agent-name{font-size:8.5px;letter-spacing:3px;color:var(--marine);font-weight:700;text-transform:uppercase;margin-bottom:5px;}
.agent-role{font-size:10px;color:var(--text3);font-weight:300;}
.agent-detail{display:none;margin-top:12px;padding-top:12px;border-top:1px solid var(--border);text-align:left;font-size:10.5px;color:var(--text2);line-height:1.7;font-weight:300;}
.agent-detail .agent-model{font-family:'Consolas',monospace;font-size:9px;color:var(--gold);margin-top:6px;}
.agent-card.expanded .agent-detail{display:block;animation:fadeUp .25s ease;}

/* ── CAPABILITIES ── */
#capabilities{padding:90px 0;}
.cap-tabs{display:flex;gap:0;margin-bottom:40px;border-bottom:1px solid var(--border2);overflow-x:auto;}
.cap-tab{padding:10px 22px;font-size:9px;letter-spacing:2px;font-weight:700;text-transform:uppercase;cursor:pointer;transition:var(--t);color:var(--text3);background:transparent;border:none;font-family:var(--fm);border-bottom:2px solid transparent;margin-bottom:-1px;white-space:nowrap;}
.cap-tab.on{color:var(--marine);border-bottom-color:var(--gold);}
.cap-tab:hover:not(.on){color:var(--text2);}
.cap-panel{display:none;}
.cap-panel.on{display:grid;grid-template-columns:1fr 1fr;gap:36px;align-items:start;animation:fadeUp .35s ease;}
.cap-visual{background:var(--surface);border:1px solid var(--border2);border-radius:var(--r);overflow:hidden;}
.cap-vis-hd{padding:10px 16px;background:var(--marine);border-bottom:2px solid var(--gold);font-size:8px;letter-spacing:3px;color:var(--gold-light);font-weight:700;text-transform:uppercase;display:flex;align-items:center;gap:8px;}
.cap-dot{width:5px;height:5px;border-radius:50%;background:#3ABA72;box-shadow:0 0 5px #3ABA72;animation:pulse 2s infinite;}
.cap-vis-body{padding:20px;font-family:'Consolas',monospace;font-size:11px;line-height:2;color:var(--text3);background:var(--bg2);}
.cap-vis-body .hl{color:var(--gold);}
.cap-vis-body .ok{color:var(--success);}
.cap-vis-body .wh{color:var(--marine);}
.cap-info{display:flex;flex-direction:column;gap:16px;}
.cap-info h3{font-family:var(--fd);font-size:26px;font-weight:600;line-height:1.25;color:var(--marine);}
.cap-info p{font-size:13.5px;color:var(--text2);line-height:1.85;font-weight:300;}
.cap-agents-used{display:flex;gap:6px;flex-wrap:wrap;}
.cap-agent-pill{padding:3px 10px;border-radius:2px;font-size:8px;letter-spacing:1.5px;font-weight:700;border:1px solid var(--border2);color:var(--text3);background:var(--surface);font-family:'Consolas',monospace;}
.cap-metrics{display:grid;grid-template-columns:repeat(3,1fr);gap:8px;}
.cap-metric{background:var(--surface);border:1px solid var(--border2);border-radius:var(--r);padding:14px;text-align:center;}
.cap-metric-v{font-family:var(--fd);font-size:24px;color:var(--gold);font-weight:600;}
.cap-metric-l{font-size:8px;letter-spacing:2px;color:var(--text3);margin-top:4px;text-transform:uppercase;font-weight:700;}

/* ── TERMINAL ── */
#terminal-demo{padding:90px 0;background:var(--surface);}
.terminal-wrap{background:var(--marine);border:1px solid var(--gold-border);border-radius:var(--r);overflow:hidden;box-shadow:var(--shadow);}
.terminal-header{padding:10px 16px;background:rgba(28,43,74,0.7);border-bottom:1px solid rgba(212,175,55,0.2);display:flex;align-items:center;gap:12px;}
.terminal-dots{display:flex;gap:6px;}
.terminal-dot{width:10px;height:10px;border-radius:50%;}
.terminal-dot.r{background:#FF5F57;}
.terminal-dot.y{background:#FEBC2E;}
.terminal-dot.g{background:#28C840;}
.terminal-title{font-size:9px;letter-spacing:3px;color:rgba(212,175,55,0.6);font-weight:700;text-transform:uppercase;}
.terminal-status{margin-left:auto;font-size:8px;letter-spacing:2px;color:#3ABA72;font-weight:700;}
.terminal-body{padding:20px 24px;font-family:'Consolas',monospace;font-size:11.5px;min-height:240px;line-height:2;}
.terminal-line{opacity:0;transform:translateX(-5px);transition:opacity .3s ease,transform .3s ease;}
.terminal-line.show{opacity:1;transform:none;}
.t-prompt{color:var(--gold);}
.t-cmd{color:var(--text-inv);}
.t-dim{color:rgba(212,175,55,0.4);}
.t-agent{color:#D4AF37;font-weight:700;}
.t-ok{color:#3ABA72;}
.t-info{color:rgba(212,175,55,0.7);}
.t-cursor::after{content:'▮';animation:blink 1s infinite;color:var(--gold);}

/* ── COMPARISON ── */
#comparison{padding:90px 0;}
.comp-table{width:100%;border-collapse:collapse;}
.comp-table thead tr th{padding:14px 18px;font-size:8.5px;letter-spacing:2.5px;text-transform:uppercase;font-weight:700;text-align:left;border-bottom:2px solid var(--border2);color:var(--text3);}
.comp-table thead tr th:last-child{color:var(--gold);text-align:center;}
.comp-table tbody tr{border-bottom:1px solid var(--border);transition:var(--t);}
.comp-table tbody tr:hover{background:var(--gold-faint2);}
.comp-table tbody tr td{padding:12px 18px;font-size:12px;}
.comp-table tbody tr td:first-child{color:var(--text2);font-weight:700;}
.comp-table tbody tr td:last-child{background:var(--gold-faint2);text-align:center;}
.comp-table tbody tr td:not(:first-child):not(:last-child){text-align:center;color:var(--text3);}
.check{color:var(--success);}
.cross{color:var(--danger);opacity:.6;}
.partial{color:var(--gold-dark);font-size:11px;}
.comp-nexus{color:var(--success);font-weight:700;}

/* ── FOOTER ── */
footer{background:var(--marine);border-top:2px solid var(--gold);padding:60px 0 0;}
.footer-inner{max-width:1180px;margin:0 auto;padding:0 44px;}
.footer-top{display:grid;grid-template-columns:2fr 1fr 1fr 1fr;gap:48px;padding-bottom:48px;border-bottom:1px solid rgba(212,175,55,0.15);}
.logo-n{font-family:var(--fd);font-size:20px;font-weight:700;letter-spacing:6px;color:var(--gold-light);margin-bottom:4px;}
.logo-sub{font-size:8px;letter-spacing:3px;color:rgba(212,175,55,0.4);text-transform:uppercase;margin-bottom:14px;font-weight:300;}
.footer-brand p{font-size:12px;color:rgba(212,175,55,0.5);line-height:1.75;font-weight:300;max-width:280px;}
.footer-col h4{font-size:9px;letter-spacing:3px;color:var(--gold);text-transform:uppercase;font-weight:700;margin-bottom:14px;}
.footer-col a{display:block;font-size:12px;color:rgba(212,175,55,0.5);text-decoration:none;margin-bottom:8px;transition:var(--t);font-weight:300;}
.footer-col a:hover{color:var(--gold-light);}
.footer-bottom{display:flex;align-items:center;justify-content:space-between;padding:18px 0;font-size:11px;color:rgba(212,175,55,0.35);font-weight:300;}
.footer-badges{display:flex;gap:8px;}
.footer-badge{padding:3px 10px;border:1px solid rgba(212,175,55,0.2);border-radius:2px;font-size:8px;letter-spacing:1.5px;color:rgba(212,175,55,0.5);font-weight:700;}

/* ═══════════════ ANIMATIONS ═══════════════ */
@keyframes fadeUp{from{opacity:0;transform:translateY(20px);}to{opacity:1;transform:none;}}
@keyframes fadeDown{from{opacity:0;transform:translateY(-10px);}to{opacity:1;transform:none;}}
@keyframes pulse{0%,100%{opacity:1;}50%{opacity:.4;}}
@keyframes blink{0%,100%{opacity:1;}50%{opacity:0;}}
@keyframes orbPulse{0%,100%{transform:scale(1);}50%{transform:scale(1.12);}}
@keyframes shimmer{0%{background-position:-200% 0;}100%{background-position:200% 0;}}
@keyframes floatUp{0%{transform:translateY(0);}50%{transform:translateY(-6px);}100%{transform:translateY(0);}}
@keyframes scanLine{0%{transform:translateY(-100%);}100%{transform:translateY(100vh);}}
@keyframes countUp{from{opacity:0;transform:scale(.8);}to{opacity:1;transform:scale(1);}}

.reveal{opacity:0;transform:translateY(18px);transition:opacity .6s ease,transform .6s ease;}
.reveal.vis{opacity:1;transform:none;}
.reveal-delay-1.vis{transition-delay:.1s;}
.reveal-delay-2.vis{transition-delay:.2s;}
.reveal-delay-3.vis{transition-delay:.3s;}

/* floating gold particle bg */
.particles-bg{position:absolute;inset:0;overflow:hidden;pointer-events:none;z-index:0;}
.particle{position:absolute;width:2px;height:2px;border-radius:50%;background:var(--gold);opacity:0;animation:particleFloat linear infinite;}
@keyframes particleFloat{0%{opacity:0;transform:translateY(100%) translateX(0);}10%{opacity:.4;}90%{opacity:.1;}100%{opacity:0;transform:translateY(-20px) translateX(20px);}}

/* ═══════════ RESPONSIVE ═══════════ */
@media(max-width:1024px){
  #hero{grid-template-columns:1fr;padding-top:60px;min-height:auto;}
  .hero-orb-side{padding:60px 24px 20px;order:1;}
  .orb-container-hero{width:280px;height:280px;}
  .hero-text-side{padding:20px 24px 60px;order:2;}
  .stats-grid{grid-template-columns:repeat(3,1fr);}
  .stat-item:nth-child(3){border-right:none;}
  .stat-item:nth-child(4),.stat-item:nth-child(5){border-top:1px solid var(--border2);}
  .sec-inner,.wl-inner{padding:0 28px;}
  .audience-toggle{flex-direction:column;width:100%;}
  .aud-btn{text-align:center;}
  .wf-demo-wrap{height:auto;display:flex;flex-direction:column;}
  .wf-toolbar{flex-wrap:wrap;height:auto;padding:8px 12px;}
  .wf-palette{height:120px;border-right:none;border-bottom:1px solid var(--border2);}
  .wf-canvas-wrap{height:300px;}
  .wf-inspector{height:200px;border-left:none;border-top:1px solid var(--border2);}
  .cap-panel.on{grid-template-columns:1fr;}
  .footer-top{grid-template-columns:1fr 1fr;gap:32px;}
  .footer-inner{padding:0 28px;}
  .comp-table{display:block;overflow-x:auto;-webkit-overflow-scrolling:touch;}
  .nav-links,.nav-cta{display:none;}
  .nav-hamburger{display:flex;}
  #nav{padding:0 20px;}
  .acc-content{padding:20px 20px 20px 20px;}
  .acc-inner-grid{grid-template-columns:1fr;}
}
@media(max-width:640px){
  body{font-size:13px;}
  #nav{padding:0 16px;gap:10px;}
  .nav-brand{font-size:16px;letter-spacing:4px;}
  .nav-sub,.nav-sep{display:none;}
  .sec-inner,.wl-inner{padding:0 16px;}
  .sec-header{margin-bottom:36px;}
  #hero{grid-template-columns:1fr;}
  .hero-orb-side{padding:40px 16px 16px;}
  .orb-container-hero{width:220px;height:220px;}
  .hero-text-side{padding:16px 16px 48px;}
  .hero-h1{font-size:clamp(28px,8vw,42px);}
  .hero-desc{font-size:14px;}
  .hero-ctas{flex-direction:column;}
  .btn-primary,.btn-secondary{width:100%;text-align:center;padding:14px 20px;}
  .stats-grid{grid-template-columns:1fr 1fr;}
  .stat-item:nth-child(5){grid-column:1/-1;border-right:none;}
  .stat-item:nth-child(3){border-right:1px solid var(--border2);}
  #waitlist{padding:60px 0;}
  .wl-form{padding:24px 16px;}
  .form-row{grid-template-columns:1fr;}
  .wf-canvas-wrap{height:260px;}
  .wf-inspector{height:180px;}
  .cap-tabs{gap:0;}
  .cap-tab{padding:10px 12px;font-size:8px;}
  .cap-panel.on{grid-template-columns:1fr;}
  .cap-metrics{grid-template-columns:1fr 1fr;}
  .terminal-body{font-size:10px;padding:14px;min-height:180px;}
  .terminal-status{display:none;}
  .footer-top{grid-template-columns:1fr;gap:24px;}
  .footer-inner{padding:0 16px;}
  .footer-bottom{flex-direction:column;gap:12px;align-items:flex-start;}
  .acc-content{padding:16px;}
  .acc-header{padding:16px;}
  .acc-icon{width:34px;height:34px;font-size:12px;}
  .acc-title{font-size:15px;}
  .acc-inner-grid{grid-template-columns:1fr;}
  .acc-metrics{grid-template-columns:1fr 1fr;}
  .agents-grid{grid-template-columns:repeat(auto-fill,minmax(130px,1fr));}
  #workflow-section,#audience-section,#agents,#capabilities,#terminal-demo,#comparison,#security,#usecases,#howitworks{padding:60px 0;}
}
</style>
</head>
<body>

<!-- NAV -->
<nav id="nav">
  <div class="nav-logo-wrap">
    <div class="nav-brand">NEXUS</div>
    <div class="nav-sub">Sovereign Intelligence · v9</div>
  </div>
  <div class="nav-sep"></div>
  <div class="nav-badge">BETA Q3 2026</div>
  <div class="nav-links">
    <a href="#waitlist">Accès Anticipé</a>
    <a href="#workflow-section">Workflows</a>
    <a href="#capabilities">Fonctionnalités</a>
    <a href="#agents">Les Agents</a>
    <a href="#comparison">vs Concurrents</a>
  </div>
  <button class="nav-cta" onclick="document.getElementById('waitlist').scrollIntoView({behavior:'smooth'})">Rejoindre la liste</button>
  <button class="nav-hamburger" id="nav-hamburger" onclick="toggleMobileMenu()" aria-label="Menu">
    <span></span><span></span><span></span>
  </button>
</nav>
<div class="nav-mobile-menu" id="nav-mobile-menu">
  <a href="#waitlist" onclick="closeMobileMenu()">Accès Anticipé</a>
  <a href="#workflow-section" onclick="closeMobileMenu()">Workflows</a>
  <a href="#capabilities" onclick="closeMobileMenu()">Fonctionnalités</a>
  <a href="#agents" onclick="closeMobileMenu()">Les Agents</a>
  <a href="#comparison" onclick="closeMobileMenu()">vs Concurrents</a>
  <div class="nav-mobile-cta" onclick="document.getElementById('waitlist').scrollIntoView({behavior:'smooth'});closeMobileMenu()">Rejoindre la liste</div>
</div>

<!-- HERO -->
<section id="hero">
  <div class="hero-hex-bg"></div>
  <div class="hero-radial"></div>
  <div class="hero-orb-side">
    <div class="orb-container-hero">
      <div class="orb-glow-hero" id="orb-glow-hero"></div>
      <canvas id="orb-canvas-hero"></canvas>
    </div>
    <div class="hero-orb-state">
      <div class="hero-orb-label" id="orb-hero-label">Nexus</div>
      <div class="hero-orb-sub" id="orb-hero-sub">Awaiting Command</div>
    </div>
    <div class="hero-orb-caps">
      <div class="orb-cap active" data-state="thinking">Reasoning</div>
      <div class="orb-cap" data-state="workflow">Workflow</div>
      <div class="orb-cap" data-state="coding">Code Gen</div>
      <div class="orb-cap" data-state="document">Documents</div>
      <div class="orb-cap" data-state="memory">Memory</div>
      <div class="orb-cap" data-state="research">Research</div>
      <div class="orb-cap" data-state="security">Security</div>
      <div class="orb-cap" data-state="idle">Idle</div>
    </div>
  </div>
  <div class="hero-text-side">
    <div class="hero-eyebrow">◆ Open Beta · Q3 2026</div>
    <h1 class="hero-h1">Votre IA tourne<br>sur <em>votre machine.</em><br>Pas la leur.</h1>
    <p class="hero-desc">NEXUS est un OS IA local — 17 agents spécialisés orchestrés en temps réel entièrement sur votre matériel. Aucun cloud. Zéro facturation à l'usage. Souveraineté totale des données.</p>
    <div class="hero-pills">
      <div class="hero-pill-item"><div class="hero-pill-dot"></div>17 agents autonomes coordonnés par le Neural Bus</div>
      <div class="hero-pill-item"><div class="hero-pill-dot"></div>Mémoire sémantique persistante · ChromaDB + BGE-M3</div>
      <div class="hero-pill-item"><div class="hero-pill-dot"></div>Workflows visuels · drag-and-drop · exécution autonome</div>
      <div class="hero-pill-item"><div class="hero-pill-dot"></div>GDPR natif · AES-256 · zéro donnée externe</div>
    </div>
    <div class="hero-ctas">
      <button class="btn-primary" onclick="document.getElementById('waitlist').scrollIntoView({behavior:'smooth'})">Demander l'accès anticipé →</button>
      <button class="btn-secondary" onclick="document.getElementById('audience-section').scrollIntoView({behavior:'smooth'})">Voir comment ça marche</button>
    </div>
  </div>
</section>

<!-- STATS -->
<section id="stats">
  <div class="stats-grid">
    <div class="stat-item"><div class="stat-val">17</div><div class="stat-label">Agents Autonomes</div><div class="stat-sub">Orchestrés par SYNERGY</div></div>
    <div class="stat-item"><div class="stat-val">0ms</div><div class="stat-label">Latence Cloud</div><div class="stat-sub">Tout tourne en local</div></div>
    <div class="stat-item"><div class="stat-val">€0</div><div class="stat-label">Par tâche</div><div class="stat-sub">Abonnement fixe uniquement</div></div>
    <div class="stat-item"><div class="stat-val">100%</div><div class="stat-label">Souveraineté</div><div class="stat-sub">Votre machine, vos données</div></div>
    <div class="stat-item"><div class="stat-val">&lt;10ms</div><div class="stat-label">Routage Neural Bus</div><div class="stat-sub">Latence agent-to-agent</div></div>
  </div>
</section>

<div class="divider"></div>

<!-- WAITLIST -->
<section id="waitlist">
  <div class="wl-bg-hex"></div>
  <div class="wl-inner">
    <div class="wl-header">
      <div class="wl-eyebrow">◆ Early Access · Places Limitées</div>
      <h2 class="wl-h2 reveal">Rejoindre la Waitlist<br><em style="color:var(--gold);font-style:italic">Sovereign Intelligence</em></h2>
      <p class="wl-desc reveal reveal-delay-1">Beta ouverte en Q3 2026. Les 500 premiers membres obtiennent un tarif Pro à vie. Cabinets d'avocats et structures médicales passent automatiquement en tête de liste.</p>
      <div class="wl-counter"><div class="wl-dot"></div><span id="wl-count">—</span> professionnels déjà inscrits</div>
    </div>
    <div class="wl-form reveal reveal-delay-2" id="waitlist-form-container">
      <div class="form-row">
        <div class="form-group"><label class="form-label">Prénom</label><input class="form-input" type="text" id="wl-fname" placeholder="Arthur"></div>
        <div class="form-group"><label class="form-label">Nom</label><input class="form-input" type="text" id="wl-lname" placeholder="Dupont"></div>
      </div>
      <div class="form-row full"><div class="form-group"><label class="form-label">Email professionnel</label><input class="form-input" type="email" id="wl-email" placeholder="arthur@cabinet-dupont.fr"></div></div>
      <div class="form-row">
        <div class="form-group"><label class="form-label">Rôle</label>
          <select class="form-input form-select" id="wl-role">
            <option value="">Sélectionnez…</option>
            <option value="attorney">Avocat / Juriste</option>
            <option value="doctor">Praticien médical</option>
            <option value="developer">Développeur / CTO</option>
            <option value="executive">Dirigeant / Fondateur</option>
            <option value="sme">PME / Entrepreneur</option>
            <option value="researcher">Chercheur / Analyste</option>
            <option value="other">Autre</option>
          </select>
        </div>
        <div class="form-group"><label class="form-label">Taille de l'équipe</label>
          <select class="form-input form-select" id="wl-size">
            <option value="">Sélectionnez…</option>
            <option value="solo">Solo / Freelance</option>
            <option value="small">2–10 personnes</option>
            <option value="medium">11–50 personnes</option>
            <option value="large">50+ personnes</option>
          </select>
        </div>
      </div>
      <div class="form-row full"><div class="form-group"><label class="form-label">Cas d'usage principal <span style="color:var(--text3);font-weight:300">(optionnel)</span></label><input class="form-input" type="text" id="wl-use" placeholder="Ex : Automatiser la rédaction de contrats et le tri des emails…"></div></div>
      <div class="form-checkbox-row">
        <input type="checkbox" class="form-checkbox" id="wl-consent">
        <label class="form-checkbox-lbl" for="wl-consent">Je comprends que NEXUS tourne entièrement sur mon matériel et j'accepte de recevoir des mises à jour occasionnelles sur le lancement beta. Désinscription en un clic.</label>
      </div>
      <button class="form-submit" id="wl-submit" onclick="submitWaitlist()">Sécuriser ma place en accès anticipé &rarr;</button>
    </div>
    <div class="success-box" id="success-box">
      <div class="success-icon">◆</div>
      <h3>Vous êtes sur la liste.</h3>
      <p>Nous vous contacterons à l'approche du Q3 2026.<br><span style="color:var(--gold);font-weight:700;margin-top:10px;display:inline-block;letter-spacing:5px">NEXUS</span></p>
    </div>
  </div>
</section>

<div class="divider"></div>

<!-- ══ POUR QUI — ACCORDION ══ -->
<section id="audience-section">
  <div class="sec-inner">
    <div class="sec-header reveal">
      <div class="sec-tag">◆ Choisissez votre perspective</div>
      <h2 class="sec-title">Fait pour tout le monde.<br><em style="font-style:italic;color:var(--gold)">Compris par tous.</em></h2>
      <div class="audience-toggle">
        <button class="aud-btn on" onclick="switchAud('biz',this)">Je gère une activité</button>
        <button class="aud-btn" onclick="switchAud('tech',this)">Je développe des logiciels</button>
      </div>
      <div class="aud-desc" id="aud-desc">Ce que NEXUS fait pour votre travail quotidien</div>
    </div>

    <!-- BIZ PANEL — ACCORDION -->
    <div class="aud-panel on" id="panel-biz">
      <div class="acc-list reveal">

        <div class="acc-item open">
          <div class="acc-header" onclick="toggleAcc(this)">
            <div class="acc-icon">AI</div>
            <div class="acc-meta">
              <div class="acc-title">Votre IA fait le travail — vous donnez la direction</div>
              <div class="acc-subtitle">Délégation par langage naturel · Résultats en secondes</div>
            </div>
            <div class="acc-right"><div class="acc-chevron">▾</div></div>
          </div>
          <div class="acc-body">
            <div class="acc-content">
              <div class="acc-inner-grid">
                <div>
                  <p class="acc-prose">Oubliez le copier-coller dans ChatGPT. NEXUS comprend ce dont vous avez besoin et le réalise. Rédigez un contrat, triez votre boîte, générez un rapport client. En une commande vocale ou textuelle.</p>
                  <p class="acc-prose"><strong>SYNERGY</strong>, l'agent orchestrateur, analyse l'intention de votre demande et délègue automatiquement aux agents spécialisés. <strong>ATLAS</strong> planifie le DAG d'exécution, décompose la tâche en sous-étapes parallélisables et coordonne l'ensemble.</p>
                  <div class="acc-result"><strong>Avant NEXUS :</strong> 3h à rédiger manuellement, copier dans ChatGPT, corriger, reformater.<br><strong>Avec NEXUS :</strong> "Génère le résumé client de la semaine" — 40 secondes. Local. Sécurisé. Livrable final.</div>
                </div>
                <div>
                  <div class="acc-code-block">
<div><span class="hl">[VOUS]</span> "Génère le résumé client Acme de la semaine"</div>
<div><span class="hl">[SYNERGY]</span> intent: résumé → routing ATLAS</div>
<div class="wh">[ATLAS] plan: emails + réunions + docs → résumé</div>
<div class="ok">[PROCURE] 12 emails · 3 réunions récupérés</div>
<div class="ok">[LIBRARIAN] contexte Acme: 8 mémoires</div>
<div class="ok">[SCRIBE] résumé.docx généré · 2 pages</div>
<div class="ok">[HERALD] "Votre résumé Acme est prêt" ✓</div>
                  </div>
                  <div class="acc-metrics">
                    <div class="acc-metric"><div class="acc-metric-v">40s</div><div class="acc-metric-l">Durée</div></div>
                    <div class="acc-metric"><div class="acc-metric-v">0</div><div class="acc-metric-l">Cloud</div></div>
                    <div class="acc-metric"><div class="acc-metric-v">L1</div><div class="acc-metric-l">Auth</div></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="acc-item">
          <div class="acc-header" onclick="toggleAcc(this)">
            <div class="acc-icon">PR</div>
            <div class="acc-meta">
              <div class="acc-title">Vos données ne quittent jamais votre bureau</div>
              <div class="acc-subtitle">RGPD natif · Zéro cloud · Confidentialité absolue</div>
            </div>
            <div class="acc-right"><span class="acc-tag" style="color:var(--success);border-color:rgba(42,106,68,0.3)">GDPR Art.9</span><div class="acc-chevron">▾</div></div>
          </div>
          <div class="acc-body">
            <div class="acc-content">
              <div class="acc-inner-grid">
                <div>
                  <p class="acc-prose">NEXUS tourne entièrement sur votre ordinateur. Aucun cloud. Aucun serveur externe. Aucune IA ne lit vos dossiers clients. Avocat, médecin, dirigeant — vos données sensibles restent vôtres.</p>
                  <p class="acc-prose">Toutes les communications inter-agents passent par un WebSocket local sur <strong>ws://localhost:8765</strong>. Aucun paquet ne sort de votre réseau. Les modèles LLM tournent via Ollama en local.</p>
                  <p class="acc-prose"><strong>CIPHER</strong> chiffre automatiquement tous les documents sensibles en AES-256 au repos. <strong>SENTINEL</strong> maintient un audit log SHA-256 immuable de chaque action — consultable, non modifiable.</p>
                  <div class="acc-result"><strong>GDPR natif par défaut.</strong> Documents, emails et mémoire ne touchent aucune API externe. Zéro upload. Zéro exposition. Certifiable pour cabinets d'avocats, cliniques et directions générales.</div>
                </div>
                <div>
                  <div class="acc-kv">
                    <div class="acc-kv-row"><span class="acc-kv-key">LLM runtime</span><span class="acc-kv-val">Ollama · local uniquement</span></div>
                    <div class="acc-kv-row"><span class="acc-kv-key">Communication</span><span class="acc-kv-val">WebSocket localhost:8765</span></div>
                    <div class="acc-kv-row"><span class="acc-kv-key">Chiffrement</span><span class="acc-kv-val">AES-256 at rest</span></div>
                    <div class="acc-kv-row"><span class="acc-kv-key">Audit trail</span><span class="acc-kv-val">SHA-256 append-only</span></div>
                    <div class="acc-kv-row"><span class="acc-kv-key">Appels cloud</span><span class="acc-kv-val">0 — jamais</span></div>
                    <div class="acc-kv-row"><span class="acc-kv-key">Conformité</span><span class="acc-kv-val">RGPD Art. 5, 9, 25</span></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="acc-item">
          <div class="acc-header" onclick="toggleAcc(this)">
            <div class="acc-icon">€0</div>
            <div class="acc-meta">
              <div class="acc-title">Un prix fixe. Des opérations illimitées.</div>
              <div class="acc-subtitle">Zéro facturation par token · Abonnement unique tout inclus</div>
            </div>
            <div class="acc-right"><div class="acc-chevron">▾</div></div>
          </div>
          <div class="acc-body">
            <div class="acc-content">
              <div class="acc-inner-grid">
                <div>
                  <p class="acc-prose">ChatGPT facture au mot. Copilot facture par siège. Claude facture à l'usage. NEXUS est un abonnement unique — usage illimité, agents illimités, tâches illimitées. 10 tâches par jour ou 10 000 : même coût.</p>
                  <p class="acc-prose">Une fois les modèles téléchargés via Ollama, chaque inférence est gratuite. Le coût marginal d'une tâche NEXUS est <strong>exactement zéro</strong>, que vous l'exécutiez une fois ou mille fois par jour.</p>
                  <div class="acc-result"><strong>Exemple d'économies réelles :</strong> Une équipe de 20 utilisant GPT-4 intensivement dépense ~€800–1200/mois en tokens. NEXUS : tarif fixe, tout inclus, usage illimité pour toute l'équipe.</div>
                </div>
                <div>
                  <div class="acc-kv">
                    <div class="acc-kv-row"><span class="acc-kv-key">ChatGPT Team</span><span class="acc-kv-val">~€25/siège/mois + tokens</span></div>
                    <div class="acc-kv-row"><span class="acc-kv-key">Copilot Ent.</span><span class="acc-kv-val">~€30/siège/mois</span></div>
                    <div class="acc-kv-row"><span class="acc-kv-key">Claude API</span><span class="acc-kv-val">~€3–15 / million tokens</span></div>
                    <div class="acc-kv-row"><span class="acc-kv-key">NEXUS</span><span class="acc-kv-val" style="color:var(--success)">Fixe · usage illimité</span></div>
                    <div class="acc-kv-row"><span class="acc-kv-key">Coût par tâche</span><span class="acc-kv-val" style="color:var(--success)">€0.000</span></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="acc-item">
          <div class="acc-header" onclick="toggleAcc(this)">
            <div class="acc-icon">WF</div>
            <div class="acc-meta">
              <div class="acc-title">Configurez une fois. Laissez tourner.</div>
              <div class="acc-subtitle">Workflows automatiques · Déclencheurs planifiés · Zero touch</div>
            </div>
            <div class="acc-right"><div class="acc-chevron">▾</div></div>
          </div>
          <div class="acc-body">
            <div class="acc-content">
              <div class="acc-inner-grid">
                <div>
                  <p class="acc-prose">NEXUS exécute des workflows automatiquement — chaque matin votre brief, chaque lundi l'agenda de la semaine, chaque nouvel email classé et priorisé. Sans déclenchement manuel.</p>
                  <p class="acc-prose"><strong>CHRONOS</strong> gère les déclencheurs planifiés (cron). <strong>HERALD</strong> surveille votre boîte et déclenche les workflows réactifs à chaque nouveau mail correspondant à vos filtres.</p>
                  <div class="acc-result"><strong>Exemple :</strong> HERALD surveille votre boîte toutes les heures, signale les urgences via notification vocale et pré-rédige les réponses — sans que vous le demandiez. Vous approuvez, vous envoyez.</div>
                </div>
                <div>
                  <div class="acc-steps">
                    <div class="acc-step"><div class="acc-step-num">1</div><div class="acc-step-text"><strong>Trigger Cron</strong> — Déclenchement planifié à heure fixe, chaque jour ouvré</div></div>
                    <div class="acc-step"><div class="acc-step-num">2</div><div class="acc-step-text"><strong>PROCURE</strong> — Récupère emails, données, fichiers depuis vos sources</div></div>
                    <div class="acc-step"><div class="acc-step-num">3</div><div class="acc-step-text"><strong>ATLAS + Agents</strong> — Traite, analyse, rédige en parallèle</div></div>
                    <div class="acc-step"><div class="acc-step-num">4</div><div class="acc-step-text"><strong>HERALD</strong> — Vous notifie avec le résultat, attend approbation si L3+</div></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="acc-item">
          <div class="acc-header" onclick="toggleAcc(this)">
            <div class="acc-icon">VO</div>
            <div class="acc-meta">
              <div class="acc-title">Parlez-lui. Tapez. Utilisez un raccourci.</div>
              <div class="acc-subtitle">Voix · Dashboard · Raccourci clavier · API · Planifié</div>
            </div>
            <div class="acc-right"><div class="acc-chevron">▾</div></div>
          </div>
          <div class="acc-body">
            <div class="acc-content">
              <div class="acc-inner-grid">
                <div>
                  <p class="acc-prose">NEXUS accepte les commandes vocales via <strong>COURIER</strong>, le texte via le dashboard, et les raccourcis clavier de n'importe où sur votre bureau. Interrompez, changez de cap, demandez des explications.</p>
                  <p class="acc-prose">Le modèle Whisper local transcrit votre voix en moins de 200ms. La reconnaissance est calibrée sur votre vocabulaire métier — noms de clients, termes juridiques, acronymes internes.</p>
                  <div class="acc-kv">
                    <div class="acc-kv-row"><span class="acc-kv-key">Voix</span><span class="acc-kv-val">COURIER · Whisper local · fr-FR / en-US</span></div>
                    <div class="acc-kv-row"><span class="acc-kv-key">Raccourci</span><span class="acc-kv-val">Configurable · n'importe quelle app</span></div>
                    <div class="acc-kv-row"><span class="acc-kv-key">API</span><span class="acc-kv-val">REST endpoint local</span></div>
                    <div class="acc-kv-row"><span class="acc-kv-key">Latence voix</span><span class="acc-kv-val">&lt; 200ms transcription</span></div>
                  </div>
                </div>
                <div>
                  <p class="acc-prose"><strong>Modes de contrôle disponibles :</strong></p>
                  <div class="acc-steps">
                    <div class="acc-step"><div class="acc-step-num">◈</div><div class="acc-step-text"><strong>Dashboard Web</strong> — Interface principale sur localhost:8000</div></div>
                    <div class="acc-step"><div class="acc-step-num">◈</div><div class="acc-step-text"><strong>Voix COURIER</strong> — Whisper + TTS local · fr-FR / en-US</div></div>
                    <div class="acc-step"><div class="acc-step-num">◈</div><div class="acc-step-text"><strong>Raccourci global</strong> — Ctrl+Shift+N depuis n'importe où</div></div>
                    <div class="acc-step"><div class="acc-step-num">◈</div><div class="acc-step-text"><strong>API REST</strong> — Intégrable dans vos outils existants</div></div>
                    <div class="acc-step"><div class="acc-step-num">◈</div><div class="acc-step-text"><strong>Automatisation</strong> — Cron, Webhook, Email trigger</div></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="acc-item">
          <div class="acc-header" onclick="toggleAcc(this)">
            <div class="acc-icon">MEM</div>
            <div class="acc-meta">
              <div class="acc-title">Il se souvient de tout ce que vous lui avez dit.</div>
              <div class="acc-subtitle">Mémoire sémantique persistante · ChromaDB · BGE-M3</div>
            </div>
            <div class="acc-right"><div class="acc-chevron">▾</div></div>
          </div>
          <div class="acc-body">
            <div class="acc-content">
              <div class="acc-inner-grid">
                <div>
                  <p class="acc-prose">NEXUS construit une mémoire sémantique de votre travail — documents traités, décisions prises, préférences exprimées. Demandez-lui un contrat du mois dernier, il le retrouve instantanément.</p>
                  <p class="acc-prose"><strong>LIBRARIAN</strong> utilise ChromaDB comme vector store persistant. Chaque action, conversation et document est découpé, embedé via BGE-M3 (1024 dimensions) et indexé. La recherche hybride (dense + sparse BM25) assure des rappels précis en moins de 30ms.</p>
                  <div class="acc-result"><strong>Powered by :</strong> ChromaDB · 1 000+ mémoires stockées · recherche sémantique en millisecondes · multilingue fr/en natif.</div>
                </div>
                <div>
                  <div class="acc-kv">
                    <div class="acc-kv-row"><span class="acc-kv-key">Vector store</span><span class="acc-kv-val">ChromaDB (local)</span></div>
                    <div class="acc-kv-row"><span class="acc-kv-key">Embedding</span><span class="acc-kv-val">BGE-M3 · 1024-d</span></div>
                    <div class="acc-kv-row"><span class="acc-kv-key">Recherche</span><span class="acc-kv-val">Dense + BM25 hybrid</span></div>
                    <div class="acc-kv-row"><span class="acc-kv-key">Latence recall</span><span class="acc-kv-val">&lt; 30ms @ 10k vectors</span></div>
                    <div class="acc-kv-row"><span class="acc-kv-key">Langues</span><span class="acc-kv-val">fr · en · multilingue</span></div>
                    <div class="acc-kv-row"><span class="acc-kv-key">Persistance</span><span class="acc-kv-val">Indéfinie · local disk</span></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

      </div>
    </div>

    <!-- TECH PANEL — ACCORDION -->
    <div class="aud-panel" id="panel-tech">
      <div class="acc-list reveal">

        <div class="acc-item open">
          <div class="acc-header" onclick="toggleAcc(this)">
            <div class="acc-icon" style="font-size:10px">CORE</div>
            <div class="acc-meta">
              <div class="acc-title">FastAPI + WebSocket Async Backend</div>
              <div class="acc-subtitle">Framework Python · Latence &lt;10ms · JWT auth</div>
            </div>
            <div class="acc-right"><span class="acc-tag" style="color:var(--gold);border-color:var(--gold-border2)">CORE</span><div class="acc-chevron">▾</div></div>
          </div>
          <div class="acc-body">
            <div class="acc-content">
              <div class="acc-inner-grid">
                <div>
                  <p class="acc-prose">Backend Python entièrement async avec communication WebSocket bidirectionnelle. Tous les messages d'agents sont persistés dans une queue rolling, rejouables et auditables. FastAPI 0.111 + Uvicorn gèrent jusqu'à 10 000 messages/s sans saturation.</p>
                  <p class="acc-prose">Le Neural Bus est le cœur de NEXUS — chaque agent s'y connecte en WebSocket et publie/souscrit aux canaux thématiques. La latence agent-to-agent est typiquement inférieure à <strong>10ms</strong> sur loopback localhost.</p>
                </div>
                <div>
                  <div class="acc-kv">
                    <div class="acc-kv-row"><span class="acc-kv-key">Framework</span><span class="acc-kv-val">FastAPI 0.111 + Uvicorn</span></div>
                    <div class="acc-kv-row"><span class="acc-kv-key">Protocol</span><span class="acc-kv-val">WebSocket ws://localhost:8765</span></div>
                    <div class="acc-kv-row"><span class="acc-kv-key">Latence routage</span><span class="acc-kv-val">&lt; 10ms agent-to-agent</span></div>
                    <div class="acc-kv-row"><span class="acc-kv-key">Auth</span><span class="acc-kv-val">JWT + HMAC session tokens</span></div>
                    <div class="acc-kv-row"><span class="acc-kv-key">Queue</span><span class="acc-kv-val">Rolling · rejouable · auditable</span></div>
                    <div class="acc-kv-row"><span class="acc-kv-key">Débit max</span><span class="acc-kv-val">~10 000 msg/s (loopback)</span></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="acc-item">
          <div class="acc-header" onclick="toggleAcc(this)">
            <div class="acc-icon" style="font-size:10px">LLM</div>
            <div class="acc-meta">
              <div class="acc-title">Ollama Multi-Model Routing</div>
              <div class="acc-subtitle">Routage dynamique · VRAM optim. · 32k–128k context</div>
            </div>
            <div class="acc-right"><span class="acc-tag" style="color:var(--success);border-color:rgba(42,106,68,0.3)">LLM</span><div class="acc-chevron">▾</div></div>
          </div>
          <div class="acc-body">
            <div class="acc-content">
              <div class="acc-inner-grid">
                <div>
                  <p class="acc-prose">Chaque agent est assigné au modèle optimal pour sa fonction. <strong>VISIONARY</strong> gère le routage dynamique selon la VRAM disponible, la complexité de la tâche et la charge courante du système.</p>
                  <p class="acc-prose">Les modèles sont chargés à la demande et déchargés après inactivité. Sur GPU 8GB, NEXUS maintient mistral:7b en mémoire permanente et charge les modèles spécialisés (coder 14B, vision) à la volée.</p>
                </div>
                <div>
                  <div class="acc-kv">
                    <div class="acc-kv-row"><span class="acc-kv-key">SYNERGY / ATLAS</span><span class="acc-kv-val">mistral:7b / llama3:8b</span></div>
                    <div class="acc-kv-row"><span class="acc-kv-key">GHOST (coder)</span><span class="acc-kv-val">qwen2.5-coder:14b</span></div>
                    <div class="acc-kv-row"><span class="acc-kv-key">OCULUS (vision)</span><span class="acc-kv-val">moondream2</span></div>
                    <div class="acc-kv-row"><span class="acc-kv-key">COURIER (voix)</span><span class="acc-kv-val">Whisper local</span></div>
                    <div class="acc-kv-row"><span class="acc-kv-key">Context window</span><span class="acc-kv-val">32k – 128k tokens</span></div>
                    <div class="acc-kv-row"><span class="acc-kv-key">VRAM min</span><span class="acc-kv-val">6GB · optimal 16GB+</span></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="acc-item">
          <div class="acc-header" onclick="toggleAcc(this)">
            <div class="acc-icon" style="font-size:10px">MEM</div>
            <div class="acc-meta">
              <div class="acc-title">ChromaDB Semantic Memory</div>
              <div class="acc-subtitle">Vector store persistant · BGE-M3 · Dense + sparse hybrid</div>
            </div>
            <div class="acc-right"><span class="acc-tag" style="color:var(--marine-light);border-color:rgba(46,69,112,0.3)">MEM</span><div class="acc-chevron">▾</div></div>
          </div>
          <div class="acc-body">
            <div class="acc-content">
              <div class="acc-inner-grid">
                <div>
                  <p class="acc-prose">Vector store persistant avec embeddings multilingues BGE-M3. Chaque action, conversation et document est chunké, embedé et indexé. Recherche hybride dense + sparse (BM25) pour des résultats précis quelle que soit la formulation.</p>
                  <p class="acc-prose">Les collections ChromaDB sont segmentées par domaine (emails, documents, code, réunions) pour des recherches ciblées. Un garbage collector automatique gère la priorité des mémoires selon leur fréquence d'accès.</p>
                </div>
                <div>
                  <div class="acc-kv">
                    <div class="acc-kv-row"><span class="acc-kv-key">Embedding</span><span class="acc-kv-val">BGE-M3 (multilingual)</span></div>
                    <div class="acc-kv-row"><span class="acc-kv-key">Dimensions</span><span class="acc-kv-val">1024-d</span></div>
                    <div class="acc-kv-row"><span class="acc-kv-key">Recherche</span><span class="acc-kv-val">Dense + BM25 sparse hybrid</span></div>
                    <div class="acc-kv-row"><span class="acc-kv-key">Recall latency</span><span class="acc-kv-val">&lt; 30ms @ 10k vectors</span></div>
                    <div class="acc-kv-row"><span class="acc-kv-key">Chunking</span><span class="acc-kv-val">Sliding window · 512 tokens</span></div>
                    <div class="acc-kv-row"><span class="acc-kv-key">Collections</span><span class="acc-kv-val">email · doc · code · réunions</span></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="acc-item">
          <div class="acc-header" onclick="toggleAcc(this)">
            <div class="acc-icon" style="font-size:10px">SEC</div>
            <div class="acc-meta">
              <div class="acc-title">SENTINEL 5-Level Authority Engine</div>
              <div class="acc-subtitle">L0–L5 · SHA-256 audit · Approbation granulaire</div>
            </div>
            <div class="acc-right"><span class="acc-tag" style="color:var(--danger);border-color:rgba(139,42,42,0.3)">SEC</span><div class="acc-chevron">▾</div></div>
          </div>
          <div class="acc-body">
            <div class="acc-content">
              <div class="acc-inner-grid">
                <div>
                  <p class="acc-prose">Chaque action agent est classifiée L0–L5 avant exécution. Les seuils d'auto-approbation sont configurables par l'utilisateur. Toutes les actions L3+ créent un audit log immuable SHA-256.</p>
                  <p class="acc-prose">La classification est instantanée (&lt;1ms) via un arbre de décision statique — pas de LLM dans la boucle de sécurité. Un agent compromis ne peut pas escalader ses propres droits : SENTINEL est exécuté en processus séparé.</p>
                </div>
                <div>
                  <div class="acc-kv">
                    <div class="acc-kv-row"><span class="acc-kv-key">L0 — Read-only</span><span class="acc-kv-val" style="color:var(--success)">Auto-approve</span></div>
                    <div class="acc-kv-row"><span class="acc-kv-key">L1–2 — Write/Create</span><span class="acc-kv-val" style="color:var(--gold)">Soft-confirm · 5s timeout</span></div>
                    <div class="acc-kv-row"><span class="acc-kv-key">L3 — Network/UI</span><span class="acc-kv-val" style="color:var(--gold)">Approbation explicite</span></div>
                    <div class="acc-kv-row"><span class="acc-kv-key">L4–5 — System/Crypto</span><span class="acc-kv-val" style="color:var(--danger)">Hard block + passphrase</span></div>
                    <div class="acc-kv-row"><span class="acc-kv-key">Audit log</span><span class="acc-kv-val">SHA-256 · append-only</span></div>
                    <div class="acc-kv-row"><span class="acc-kv-key">Classification</span><span class="acc-kv-val">&lt; 1ms · arbre de décision</span></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

      </div>
    </div>
  </div>
</section>

<div class="divider"></div>

<!-- ══ WORKFLOW SECTION ══ -->
<section id="workflow-section">
  <div class="sec-inner">
    <div class="sec-header reveal">
      <div class="sec-tag">◆ Workflow Engine</div>
      <h2 class="sec-title" style="color:var(--marine)">Automatisation Visuelle<br>par Drag &amp; Drop</h2>
      <p class="sec-desc">Construisez des workflows complexes en connectant des nœuds visuellement — puis laissez le swarm les exécuter de façon autonome, avec self-healing intégré.</p>
    </div>

    <!-- DÉMO INTERACTIVE -->
    <div class="wf-demo-wrap reveal">
      <div class="wf-toolbar">
        <div class="wf-tb-title">Workflow Engine</div>
        <div class="wf-tb-sep"></div>
        <span class="wf-tb-count" id="wf-nc">0 nœuds</span>
        <span class="wf-tb-count"> · </span>
        <span class="wf-tb-count" id="wf-ec">0 liens</span>
        <div class="wf-tb-right">
          <button class="wf-btn" onclick="wfReset()">FIT</button>
          <button class="wf-btn" onclick="wfZoom(0.1)">+</button>
          <button class="wf-btn" onclick="wfZoom(-0.1)">−</button>
          <button class="wf-btn" onclick="wfClearAll()">✕ Vider</button>
          <button class="wf-btn" onclick="wfLoadDefault()">⟳ Exemple</button>
          <button class="wf-btn gold" onclick="wfRunWorkflow()">▷ Exécuter</button>
        </div>
      </div>
      <div class="wf-palette" id="wf-palette"><div class="wf-pal-hd">Palette de nœuds</div></div>
      <div class="wf-canvas-wrap">
        <svg id="wf-svg" xmlns="http://www.w3.org/2000/svg">
          <defs>
            <marker id="wf-arr" viewBox="0 0 10 10" refX="9" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse">
              <path d="M2 2L8 5L2 8" fill="none" stroke="context-stroke" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
            </marker>
            <pattern id="wf-dots" x="0" y="0" width="24" height="24" patternUnits="userSpaceOnUse">
              <circle cx="1" cy="1" r="0.8" fill="currentColor" opacity=".18"/>
            </pattern>
          </defs>
          <rect width="100%" height="100%" fill="url(#wf-dots)" id="wf-grid-bg" style="color:var(--text3)"/>
          <g id="wf-edges-layer"></g>
          <g id="wf-nodes-layer"></g>
          <path id="wf-draw-edge" fill="none" stroke="var(--gold)" stroke-width="1.5" stroke-dasharray="5 3" opacity=".7" d=""/>
        </svg>
        <div style="position:absolute;bottom:8px;left:10px;font-size:8px;color:var(--text3);background:var(--surface);border:1px solid var(--border);border-radius:2px;padding:3px 8px;letter-spacing:1px">
          Double-clic sur palette · Drag pour déplacer · Shift+drag pour connecter
        </div>
      </div>
      <div class="wf-inspector">
        <div class="wf-insp-hd">Inspecteur</div>
        <div id="wf-insp-empty" class="wf-insp-empty">
          <span style="font-size:22px;opacity:.25">⬡</span>
          <span>Sélectionnez un nœud<br>pour l'inspecter</span>
        </div>
        <div id="wf-insp-content" style="display:none;flex-direction:column;flex:1">
          <div style="padding:10px 12px 8px;border-bottom:1px solid var(--border2);display:flex;align-items:center;gap:8px;flex-shrink:0">
            <div id="wf-insp-dot" style="width:9px;height:9px;border-radius:2px;flex-shrink:0;background:var(--gold)"></div>
            <div>
              <div id="wf-insp-title" style="font-size:11px;font-weight:700;color:var(--text)">—</div>
              <div id="wf-insp-type" style="font-size:9px;color:var(--text3)">—</div>
            </div>
          </div>
          <div id="wf-insp-body" class="wf-insp-body"></div>
          <div id="wf-run-log" class="wf-run-log" style="display:none"></div>
          <div style="display:flex;gap:5px;padding:0 12px 12px;flex-shrink:0">
            <button class="wf-btn" style="flex:1" onclick="wfDuplicateNode()">Dupliquer</button>
            <button class="wf-btn" style="flex:1;border-color:var(--danger);color:var(--danger)" onclick="wfDeleteNode()">Supprimer</button>
          </div>
        </div>
      </div>
    </div>

    <!-- ACCORDÉON WORKFLOW EXPLICATIONS -->
    <div style="margin-top:60px;">
      <div style="text-align:center;margin-bottom:40px;">
        <div class="sec-tag">◆ Documentation du Workflow Engine</div>
        <h3 style="font-family:var(--fd);font-size:clamp(22px,3vw,34px);font-weight:600;color:var(--marine);margin-top:10px;">Tout comprendre sur l'éditeur</h3>
      </div>
      <div class="acc-list reveal">

        <div class="acc-item open">
          <div class="acc-header" onclick="toggleAcc(this)">
            <div class="acc-icon">⬡</div>
            <div class="acc-meta">
              <div class="acc-title">Qu'est-ce qu'un Workflow NEXUS ?</div>
              <div class="acc-subtitle">Concept fondamental · DAG · Swarm orchestration</div>
            </div>
            <div class="acc-right"><div class="acc-chevron">▾</div></div>
          </div>
          <div class="acc-body">
            <div class="acc-content">
              <div class="acc-inner-grid">
                <div>
                  <p class="acc-prose">Un workflow est une séquence de nœuds connectés qui définit une automatisation complète. Chaque nœud représente soit un déclencheur (quand ?), une action (quoi ?), une logique de branchement (si/sinon), ou un gestionnaire d'erreur.</p>
                  <p class="acc-prose">Contrairement aux outils no-code classiques, chaque nœud Action peut invoquer un <strong>agent NEXUS complet</strong> — GHOST pour coder, SCRIBE pour rédiger, PROCURE pour récupérer des données. Le workflow devient un chef d'orchestre du swarm.</p>
                  <p class="acc-prose">Les workflows sont stockés en JSON et versionnés localement. Vous pouvez en exporter, importer et partager — chaque workflow est un programme autonome exécutable par ATLAS.</p>
                </div>
                <div>
                  <div class="acc-steps">
                    <div class="acc-step"><div class="acc-step-num">1</div><div class="acc-step-text"><strong>Trigger</strong> — Point d'entrée. Déclenche le workflow (cron, email, webhook, manuel)</div></div>
                    <div class="acc-step"><div class="acc-step-num">2</div><div class="acc-step-text"><strong>Action</strong> — Invoque un agent ou une opération (HTTP, shell, template, notification)</div></div>
                    <div class="acc-step"><div class="acc-step-num">3</div><div class="acc-step-text"><strong>Logique</strong> — Branche conditionnelle, boucle sur une liste, pause temporelle</div></div>
                    <div class="acc-step"><div class="acc-step-num">4</div><div class="acc-step-text"><strong>Erreur</strong> — Self-heal automatique ou retry configurable en cas d'échec</div></div>
                  </div>
                  <div class="acc-result" style="margin-top:12px"><strong>Format de stockage :</strong> JSON versionné · importable/exportable · partageable entre instances NEXUS</div>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="acc-item">
          <div class="acc-header" onclick="toggleAcc(this)">
            <div class="acc-icon">⏱</div>
            <div class="acc-meta">
              <div class="acc-title">Les 4 types de déclencheurs</div>
              <div class="acc-subtitle">Cron · Webhook · Email IMAP · Manuel</div>
            </div>
            <div class="acc-right"><div class="acc-chevron">▾</div></div>
          </div>
          <div class="acc-body">
            <div class="acc-content">
              <div class="acc-inner-grid">
                <div>
                  <p class="acc-prose">Chaque workflow commence par exactement un nœud déclencheur. Quatre types couvrent tous les cas d'usage professionnels.</p>
                  <div class="acc-steps">
                    <div class="acc-step"><div class="acc-step-num" style="width:28px;font-size:9px">CR</div><div class="acc-step-text"><strong>Cron</strong> — Expression unix standard. <code style="font-family:monospace;font-size:10px;background:var(--bg2);padding:1px 4px;border-radius:2px">0 9 * * 1-5</code> = chaque jour ouvré à 9h. Idéal pour briefs, rapports hebdo, nettoyages planifiés.</div></div>
                    <div class="acc-step"><div class="acc-step-num" style="width:28px;font-size:9px">WH</div><div class="acc-step-text"><strong>Webhook</strong> — Endpoint HTTP sur <code style="font-family:monospace;font-size:10px;background:var(--bg2);padding:1px 4px;border-radius:2px">/hook/nexus/[id]</code>. Déclenché depuis Zapier, votre ERP, CRM, ou un bouton web.</div></div>
                    <div class="acc-step"><div class="acc-step-num" style="width:28px;font-size:9px">EM</div><div class="acc-step-text"><strong>Email IMAP</strong> — Surveille votre boîte en continu. Lance le workflow dès qu'un mail correspond à vos filtres (expéditeur, objet, mots-clés).</div></div>
                    <div class="acc-step"><div class="acc-step-num" style="width:28px;font-size:9px">MN</div><div class="acc-step-text"><strong>Manuel</strong> — Clic dashboard, raccourci clavier global, ou commande vocale. Pour les workflows à la demande.</div></div>
                  </div>
                </div>
                <div>
                  <div class="acc-kv">
                    <div class="acc-kv-row"><span class="acc-kv-key">Cron min. interval</span><span class="acc-kv-val">1 minute</span></div>
                    <div class="acc-kv-row"><span class="acc-kv-key">Webhook auth</span><span class="acc-kv-val">HMAC-SHA256 signature</span></div>
                    <div class="acc-kv-row"><span class="acc-kv-key">Email poll</span><span class="acc-kv-val">IMAP IDLE · temps réel</span></div>
                    <div class="acc-kv-row"><span class="acc-kv-key">Manuel latence</span><span class="acc-kv-val">&lt; 100ms</span></div>
                    <div class="acc-kv-row"><span class="acc-kv-key">Triggers simultanés</span><span class="acc-kv-val">Illimité</span></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="acc-item">
          <div class="acc-header" onclick="toggleAcc(this)">
            <div class="acc-icon">◆</div>
            <div class="acc-meta">
              <div class="acc-title">Logique conditionnelle — branches, boucles, délais</div>
              <div class="acc-subtitle">Si/Sinon · Boucle itérative · Délai configurable</div>
            </div>
            <div class="acc-right"><div class="acc-chevron">▾</div></div>
          </div>
          <div class="acc-body">
            <div class="acc-content">
              <div class="acc-inner-grid">
                <div>
                  <p class="acc-prose">Les nœuds de logique transforment un workflow linéaire en système décisionnel. Chaque nœud Si/Sinon crée deux branches indépendantes qui peuvent être développées séparément.</p>
                  <p class="acc-prose"><strong>Si/Sinon</strong> — Évalue une expression. La branche vraie continue, la fausse va vers une erreur ou notification alternative. Les conditions supportent les opérateurs de comparaison, les regex, et les fonctions de test sur les variables.</p>
                  <p class="acc-prose"><strong>Boucle</strong> — Itère sur une liste variable. Les itérations peuvent être parallélisées automatiquement par ATLAS selon la charge disponible.</p>
                  <p class="acc-prose"><strong>Délai</strong> — Pause configurable entre deux nœuds. Utile pour espacer des requêtes API ou attendre qu'un processus externe se termine.</p>
                </div>
                <div>
                  <div class="acc-code-block">
<div class="hl">Exemple Si/Sinon :</div>
<div class="wh">condition: {"{{result}}"} != ""</div>
<div>  → Branche VRAIE: SCRIBE génère rapport</div>
<div>  → Branche FAUSSE: HERALD notifie "aucun résultat"</div>
<br>
<div class="hl">Exemple Boucle :</div>
<div class="wh">liste: {"{{emails}}"}</div>
<div>  → pour chaque {"{{item}}"}: SCRIBE rédige réponse</div>
<div>  → parallélisé: 4 threads simultanés</div>
<br>
<div class="hl">Délai :</div>
<div class="wh">durée: 5000ms (5 secondes)</div>
<div>  → Annulable à tout moment</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="acc-item">
          <div class="acc-header" onclick="toggleAcc(this)">
            <div class="acc-icon">◈</div>
            <div class="acc-meta">
              <div class="acc-title">Transmission de données entre nœuds</div>
              <div class="acc-subtitle">Variables template · Contexte partagé · Accès imbriqué</div>
            </div>
            <div class="acc-right"><div class="acc-chevron">▾</div></div>
          </div>
          <div class="acc-body">
            <div class="acc-content">
              <div class="acc-inner-grid">
                <div>
                  <p class="acc-prose">Chaque nœud produit un résultat accessible aux nœuds suivants via des variables de template. Les données circulent naturellement dans la chaîne sans configuration manuelle.</p>
                  <p class="acc-prose">Le résultat d'un nœud Agent est accessible via <code style="font-family:monospace;font-size:10px;background:var(--bg2);padding:1px 5px">{"{{result}}"}</code>. PROCURE peut remplir <code style="font-family:monospace;font-size:10px;background:var(--bg2);padding:1px 5px">{"{{emails}}"}</code> qu'une Boucle itère, dont chaque itération passe dans SCRIBE via <code style="font-family:monospace;font-size:10px;background:var(--bg2);padding:1px 5px">{"{{item}}"}</code>.</p>
                  <p class="acc-prose">Le template supporte les accès imbriqués : <code style="font-family:monospace;font-size:10px;background:var(--bg2);padding:1px 5px">{"{{result.subject}}"}</code>, <code style="font-family:monospace;font-size:10px;background:var(--bg2);padding:1px 5px">{"{{item.sender}}"}</code>. ATLAS gère le contexte global sur toute la durée du workflow.</p>
                </div>
                <div>
                  <div class="acc-kv">
                    <div class="acc-kv-row"><span class="acc-kv-key">{"{{result}}"}</span><span class="acc-kv-val">Sortie du nœud précédent</span></div>
                    <div class="acc-kv-row"><span class="acc-kv-key">{"{{item}}"}</span><span class="acc-kv-val">Élément courant (boucle)</span></div>
                    <div class="acc-kv-row"><span class="acc-kv-key">{"{{result.field}}"}</span><span class="acc-kv-val">Accès à un champ spécifique</span></div>
                    <div class="acc-kv-row"><span class="acc-kv-key">{"{{date}}"}</span><span class="acc-kv-val">Date/heure courante</span></div>
                    <div class="acc-kv-row"><span class="acc-kv-key">{"{{user.name}}"}</span><span class="acc-kv-val">Contexte utilisateur</span></div>
                    <div class="acc-kv-row"><span class="acc-kv-key">Contexte</span><span class="acc-kv-val">Persisté par ATLAS · global</span></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="acc-item">
          <div class="acc-header" onclick="toggleAcc(this)">
            <div class="acc-icon">🔧</div>
            <div class="acc-meta">
              <div class="acc-title">Self-Healing — que se passe-t-il en cas d'échec ?</div>
              <div class="acc-subtitle">Auto-récupération · Retry configurable · Escalade contrôlée</div>
            </div>
            <div class="acc-right"><div class="acc-chevron">▾</div></div>
          </div>
          <div class="acc-body">
            <div class="acc-content">
              <div class="acc-inner-grid">
                <div>
                  <p class="acc-prose">NEXUS n'abandonne pas silencieusement. Les nœuds d'erreur définissent un comportement de récupération automatique — jusqu'à 3 tentatives, avec agent correcteur intégré.</p>
                  <p class="acc-prose">Le nœud <strong>Self-Heal</strong> invoque GHOST ou ATLAS pour analyser le traceback de l'erreur et proposer une correction. Si la correction échoue après le nombre de tentatives configuré, HERALD vous notifie avec le contexte complet.</p>
                  <p class="acc-prose">Toutes les tentatives sont loguées dans l'audit SHA-256 — vous ne découvrez jamais un échec silencieux. L'historique complet est consultable depuis le dashboard.</p>
                </div>
                <div>
                  <div class="acc-steps">
                    <div class="acc-step"><div class="acc-step-num">1</div><div class="acc-step-text"><strong>Détection</strong> — Le nœud échoue et lève une exception avec traceback complet</div></div>
                    <div class="acc-step"><div class="acc-step-num">2</div><div class="acc-step-text"><strong>Self-Heal</strong> — GHOST analyse le traceback, propose une correction (max 3 cycles)</div></div>
                    <div class="acc-step"><div class="acc-step-num">3</div><div class="acc-step-text"><strong>Retry</strong> — Le nœud corrigé est ré-exécuté automatiquement</div></div>
                    <div class="acc-step"><div class="acc-step-num">4</div><div class="acc-step-text"><strong>Escalade</strong> — Si toujours KO, HERALD vous notifie avec contexte et log complet</div></div>
                    <div class="acc-step"><div class="acc-step-num">5</div><div class="acc-step-text"><strong>Audit</strong> — Toutes les tentatives loguées SHA-256 · consultables · non modifiables</div></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="acc-item">
          <div class="acc-header" onclick="toggleAcc(this)">
            <div class="acc-icon">↔</div>
            <div class="acc-meta">
              <div class="acc-title">Utiliser l'éditeur visuel — guide complet</div>
              <div class="acc-subtitle">Drag &amp; drop · Connexions · Inspecteur · Exécution</div>
            </div>
            <div class="acc-right"><div class="acc-chevron">▾</div></div>
          </div>
          <div class="acc-body">
            <div class="acc-content">
              <div class="acc-inner-grid">
                <div>
                  <p class="acc-prose">L'éditeur fonctionne par drag-and-drop. La palette liste les nœuds disponibles. Le canvas central est l'espace de construction. L'inspecteur configure le nœud sélectionné.</p>
                  <div class="acc-steps">
                    <div class="acc-step"><div class="acc-step-num">+</div><div class="acc-step-text"><strong>Ajouter un nœud</strong> — Double-clic sur un élément de la palette, ou glissez-le vers le canvas. Il apparaît à la position de dépôt.</div></div>
                    <div class="acc-step"><div class="acc-step-num">→</div><div class="acc-step-text"><strong>Connecter deux nœuds</strong> — Maintenez <code style="font-family:monospace;font-size:10px;background:var(--bg2);padding:1px 4px">Shift</code> et faites glisser depuis un nœud vers un autre. La flèche orientée apparaît.</div></div>
                    <div class="acc-step"><div class="acc-step-num">✎</div><div class="acc-step-text"><strong>Configurer</strong> — Cliquez sur un nœud pour l'ouvrir dans l'inspecteur. Modifiez nom, agent, prompt, condition.</div></div>
                    <div class="acc-step"><div class="acc-step-num">▷</div><div class="acc-step-text"><strong>Exécuter</strong> — Cliquez ▷ Exécuter. Chaque nœud s'allume au passage. Le log temps réel s'affiche dans l'inspecteur.</div></div>
                    <div class="acc-step"><div class="acc-step-num">✕</div><div class="acc-step-text"><strong>Supprimer un lien</strong> — Double-clic sur une connexion pour la supprimer.</div></div>
                  </div>
                </div>
                <div>
                  <div class="acc-kv">
                    <div class="acc-kv-row"><span class="acc-kv-key">Naviguer</span><span class="acc-kv-val">Clic+drag sur canvas vide</span></div>
                    <div class="acc-kv-row"><span class="acc-kv-key">Zoom</span><span class="acc-kv-val">Molette ou boutons +/−</span></div>
                    <div class="acc-kv-row"><span class="acc-kv-key">Connecter</span><span class="acc-kv-val">Shift + drag nœud→nœud</span></div>
                    <div class="acc-kv-row"><span class="acc-kv-key">Dupliquer</span><span class="acc-kv-val">Bouton dans l'inspecteur</span></div>
                    <div class="acc-kv-row"><span class="acc-kv-key">Centrer</span><span class="acc-kv-val">Bouton FIT</span></div>
                    <div class="acc-kv-row"><span class="acc-kv-key">Suppr. lien</span><span class="acc-kv-val">Double-clic sur la connexion</span></div>
                  </div>
                  <div class="acc-result" style="margin-top:12px"><strong>Conseil :</strong> Commencez par cliquer "⟳ Exemple" pour voir un workflow complet préconstruit avec trigger, agent, condition et gestion d'erreur.</div>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="acc-item">
          <div class="acc-header" onclick="toggleAcc(this)">
            <div class="acc-icon" style="font-size:11px">DAG</div>
            <div class="acc-meta">
              <div class="acc-title">Sous le capot — l'exécution par ATLAS</div>
              <div class="acc-subtitle">Validation · Parallélisation · Neural Bus · Audit SHA-256</div>
            </div>
            <div class="acc-right"><div class="acc-chevron">▾</div></div>
          </div>
          <div class="acc-body">
            <div class="acc-content">
              <div class="acc-inner-grid">
                <div>
                  <p class="acc-prose">Quand vous cliquez ▷ Exécuter, ATLAS transforme votre graphe visuel en un plan d'exécution optimisé en temps réel.</p>
                  <div class="acc-steps">
                    <div class="acc-step"><div class="acc-step-num">1</div><div class="acc-step-text"><strong>Validation du graphe</strong> — ATLAS vérifie que le workflow est un DAG valide (sans cycle), que chaque nœud est connecté et que les variables référencées existent.</div></div>
                    <div class="acc-step"><div class="acc-step-num">2</div><div class="acc-step-text"><strong>Planification parallèle</strong> — ATLAS identifie les branches indépendantes et les exécute simultanément pour minimiser la durée totale.</div></div>
                    <div class="acc-step"><div class="acc-step-num">3</div><div class="acc-step-text"><strong>Neural Bus</strong> — Chaque nœud Action envoie un message WebSocket à l'agent concerné (&lt;10ms). L'agent retourne son résultat dans le contexte partagé.</div></div>
                    <div class="acc-step"><div class="acc-step-num">4</div><div class="acc-step-text"><strong>SENTINEL</strong> — Chaque action est classifiée L0–L5. Les actions L3+ attendent votre confirmation avant de continuer.</div></div>
                    <div class="acc-step"><div class="acc-step-num">5</div><div class="acc-step-text"><strong>Audit immuable</strong> — Chaque exécution produit un log SHA-256 append-only : nœuds, durées, résultats, décisions SENTINEL.</div></div>
                  </div>
                </div>
                <div>
                  <div class="acc-code-block">
<div class="hl">// Exemple de plan ATLAS généré</div>
<div class="wh">{</div>
<div>  dag_valid: true,</div>
<div>  nodes: 5, edges: 4,</div>
<div>  parallel_groups: [</div>
<div>    [node_1],         <span class="hl">// trigger séquentiel</span></div>
<div>    [node_2, node_3], <span class="hl">// actions en parallèle</span></div>
<div>    [node_4, node_5]  <span class="hl">// branches conditionnelles</span></div>
<div>  ],</div>
<div>  estimated_duration: "4.2s",</div>
<div class="ok">  audit_hash: "sha256:a3f2c1d8..."</div>
<div class="wh">}</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

      </div>
    </div>
  </div>
</section>

<div class="divider"></div>

<!-- ══ AGENTS — ACCORDION GRID ══ -->
<section id="agents">
  <div class="sec-inner">
    <div class="sec-header reveal">
      <div class="sec-tag">◆ Le Swarm NEXUS</div>
      <h2 class="sec-title">17 Agents Spécialisés.</h2>
      <p class="sec-desc">Cliquez sur un agent pour voir ses capacités détaillées, son modèle LLM assigné et les tâches types qu'il gère.</p>
    </div>
    <div class="agents-grid reveal" id="agents-grid"></div>
  </div>
</section>

<div class="divider"></div>

<!-- ══ CAPABILITIES — TABS AVEC ACCORDION ══ -->
<section id="capabilities">
  <div class="sec-inner">
    <div class="sec-header reveal">
      <div class="sec-tag">◆ Fonctionnalités NEXUS</div>
      <h2 class="sec-title">Chaque Capacité.<br>En Détail.</h2>
      <p class="sec-desc">Sélectionnez un workflow pour voir exactement quels agents interviennent, ce qui se passe dans le Neural Bus, et quel est le résultat.</p>
    </div>
    <div class="cap-tabs reveal">
      <button class="cap-tab on" onclick="switchCap('email',this)">Triage Email</button>
      <button class="cap-tab" onclick="switchCap('code',this)">Code Gen</button>
      <button class="cap-tab" onclick="switchCap('doc',this)">Rédaction Doc</button>
      <button class="cap-tab" onclick="switchCap('research',this)">Recherche</button>
      <button class="cap-tab" onclick="switchCap('screen',this)">Contrôle Écran</button>
    </div>

    <div class="cap-panel on" id="cap-email">
      <div class="cap-visual"><div class="cap-vis-hd"><div class="cap-dot"></div>Neural Bus · Email Triage</div><div class="cap-vis-body"><div><span class="hl">[SYNERGY]</span> → intent: "triage inbox" → routing to PROCURE</div><div><span class="hl">[PROCURE]</span> → Gmail API · fetching unread (limit: 30)</div><div><span class="wh">[SENTINEL]</span> → L1 read-only · auto-approved</div><div><span class="ok">[PROCURE]</span> → 24 emails · priority scoring via TF-IDF</div><div><span class="hl">[LIBRARIAN]</span> → semantic recall: "email context" → 5 memories</div><div><span class="ok">[ATLAS]</span> → 4 urgent · 11 normal · 9 low</div><div><span class="hl">[SCRIBE]</span> → drafting response templates for urgent items</div><div><span class="ok">[HERALD]</span> → notification + voice alert pushed</div><div><span class="ok">[SYNERGY]</span> → task complete · 6.2s · 0 cloud calls</div></div></div>
      <div class="cap-info"><h3>Triage Email Intelligent</h3><p>NEXUS se connecte à votre Gmail localement via OAuth — les identifiants ne quittent jamais votre machine. PROCURE récupère votre boîte, ATLAS classe chaque fil par urgence, LIBRARIAN enrichit avec le contexte des interactions passées.</p><p>SCRIBE pré-rédige les réponses aux éléments prioritaires. Vous relisez, approuvez, envoyez — NEXUS n'envoie jamais de façon autonome sans autorisation L3+.</p><div><div class="sec-tag" style="margin-bottom:8px">Agents impliqués</div><div class="cap-agents-used"><div class="cap-agent-pill">SYNERGY</div><div class="cap-agent-pill">PROCURE</div><div class="cap-agent-pill">ATLAS</div><div class="cap-agent-pill">LIBRARIAN</div><div class="cap-agent-pill">SCRIBE</div><div class="cap-agent-pill">HERALD</div><div class="cap-agent-pill">SENTINEL</div></div></div><div class="cap-metrics"><div class="cap-metric"><div class="cap-metric-v">6.2s</div><div class="cap-metric-l">Durée totale</div></div><div class="cap-metric"><div class="cap-metric-v">0</div><div class="cap-metric-l">Appels cloud</div></div><div class="cap-metric"><div class="cap-metric-v">L1</div><div class="cap-metric-l">Niveau auth</div></div></div></div>
    </div>

    <div class="cap-panel" id="cap-code">
      <div class="cap-visual"><div class="cap-vis-hd"><div class="cap-dot"></div>Neural Bus · Code Generation</div><div class="cap-vis-body"><div><span class="hl">[SYNERGY]</span> → intent: "add auth to my API" → ATLAS</div><div><span class="hl">[ATLAS]</span> → plan: 4 steps · AST read → patch → test → commit</div><div><span class="ok">[GHOST]</span> → qwen2.5-coder:14b · reading codebase AST</div><div><span class="wh">[GHOST]</span> → 847 lines parsed · 3 injection points found</div><div><span class="hl">[GHOST]</span> → generating JWT middleware · bcrypt hash utils</div><div><span class="ok">[FORGE]</span> → patch applied → auth/middleware.py (new)</div><div><span class="wh">[SENTINEL]</span> → L2 write · soft-confirmed by user</div><div><span class="ok">[TERMINUS]</span> → pytest running · 12/12 passed</div><div><span class="ok">[GHOST]</span> → commit: "feat: JWT auth middleware"</div></div></div>
      <div class="cap-info"><h3>Génération de Code Autonome</h3><p>GHOST est un agent code complet — il lit votre codebase entier via AST, comprend votre architecture, et génère des patches qui s'intègrent dans votre style existant.</p><p>FORGE applique les fichiers atomiquement. TERMINUS exécute votre suite de tests. En cas d'échec, GHOST reçoit le traceback et itère — jusqu'à 3 cycles avant escalade vers vous.</p><div><div class="sec-tag" style="margin-bottom:8px">Agents impliqués</div><div class="cap-agents-used"><div class="cap-agent-pill">GHOST</div><div class="cap-agent-pill">ATLAS</div><div class="cap-agent-pill">FORGE</div><div class="cap-agent-pill">TERMINUS</div><div class="cap-agent-pill">SENTINEL</div></div></div><div class="cap-metrics"><div class="cap-metric"><div class="cap-metric-v">14B</div><div class="cap-metric-l">Modèle coder</div></div><div class="cap-metric"><div class="cap-metric-v">3x</div><div class="cap-metric-l">Retry auto</div></div><div class="cap-metric"><div class="cap-metric-v">L2</div><div class="cap-metric-l">Niveau auth</div></div></div></div>
    </div>

    <div class="cap-panel" id="cap-doc">
      <div class="cap-visual"><div class="cap-vis-hd"><div class="cap-dot"></div>Neural Bus · Document Drafting</div><div class="cap-vis-body"><div><span class="hl">[SYNERGY]</span> → intent: "draft NDA for Acme Corp" → ATLAS</div><div><span class="hl">[LIBRARIAN]</span> → recall: "Acme Corp context" → 8 memories</div><div><span class="ok">[LIBRARIAN]</span> → prior contracts, preferences, jurisdiction</div><div><span class="hl">[SCRIBE]</span> → template: NDA_FR_v3 · customizing clauses</div><div><span class="wh">[SENTINEL]</span> → L1 auto-approved · read-only generation</div><div><span class="ok">[SCRIBE]</span> → .docx generated · 8 pages · all clauses filled</div><div><span class="ok">[CIPHER]</span> → AES-256 encrypted at rest</div><div><span class="ok">[HERALD]</span> → "Votre NDA Acme Corp est prêt" · dashboard + voice</div><div><span class="ok">[SYNERGY]</span> → task complete · 4.1s · 0 cloud calls</div></div></div>
      <div class="cap-info"><h3>Rédaction de Documents</h3><p>SCRIBE génère des documents Word, PDF et présentations à partir de modèles que vous définissez. LIBRARIAN enrichit avec le contexte mémorisé de vos interactions passées.</p><p>CIPHER chiffre automatiquement les documents sensibles. HERALD vous notifie quand le document est prêt pour relecture.</p><div><div class="sec-tag" style="margin-bottom:8px">Agents impliqués</div><div class="cap-agents-used"><div class="cap-agent-pill">SCRIBE</div><div class="cap-agent-pill">LIBRARIAN</div><div class="cap-agent-pill">ATLAS</div><div class="cap-agent-pill">CIPHER</div><div class="cap-agent-pill">HERALD</div></div></div><div class="cap-metrics"><div class="cap-metric"><div class="cap-metric-v">4.1s</div><div class="cap-metric-l">Durée totale</div></div><div class="cap-metric"><div class="cap-metric-v">AES</div><div class="cap-metric-l">Chiffrement</div></div><div class="cap-metric"><div class="cap-metric-v">L1</div><div class="cap-metric-l">Niveau auth</div></div></div></div>
    </div>

    <div class="cap-panel" id="cap-research">
      <div class="cap-visual"><div class="cap-vis-hd"><div class="cap-dot"></div>Neural Bus · Deep Research</div><div class="cap-vis-body"><div><span class="hl">[SYNERGY]</span> → intent: "analyze AI regulation trends EU" → ATLAS</div><div><span class="hl">[ATLAS]</span> → plan: 3 parallel crawls + synthesis</div><div><span class="ok">[PROCURE]</span> → web crawl: 40 sources · EU regulation</div><div><span class="ok">[PROCURE]</span> → PDF extraction: 12 EU parliament documents</div><div><span class="hl">[OCULUS]</span> → chart OCR: 6 regulatory timeline graphs</div><div><span class="ok">[LIBRARIAN]</span> → indexing corpus · BGE-M3 · 1024-d</div><div><span class="ok">[ATLAS]</span> → synthesis: 18-page structured report</div><div><span class="ok">[SCRIBE]</span> → PDF report generated · executive summary</div><div><span class="ok">[SYNERGY]</span> → task complete · 38.4s · 0 cloud calls</div></div></div>
      <div class="cap-info"><h3>Recherche Approfondie Autonome</h3><p>PROCURE crawle le web et extrait des PDFs. OCULUS lit les graphiques et figures via OCR vision. LIBRARIAN indexe tout le corpus sémantiquement. ATLAS synthétise en rapport structuré.</p><p>Tout tourne localement — vos recherches concurrentielles, études de marché et veilles réglementaires ne transitent par aucun serveur externe.</p><div><div class="sec-tag" style="margin-bottom:8px">Agents impliqués</div><div class="cap-agents-used"><div class="cap-agent-pill">PROCURE</div><div class="cap-agent-pill">OCULUS</div><div class="cap-agent-pill">LIBRARIAN</div><div class="cap-agent-pill">ATLAS</div><div class="cap-agent-pill">SCRIBE</div></div></div><div class="cap-metrics"><div class="cap-metric"><div class="cap-metric-v">40</div><div class="cap-metric-l">Sources crawlées</div></div><div class="cap-metric"><div class="cap-metric-v">38s</div><div class="cap-metric-l">Durée totale</div></div><div class="cap-metric"><div class="cap-metric-v">0</div><div class="cap-metric-l">Appels cloud</div></div></div></div>
    </div>

    <div class="cap-panel" id="cap-screen">
      <div class="cap-visual"><div class="cap-vis-hd"><div class="cap-dot"></div>Neural Bus · Screen Control</div><div class="cap-vis-body"><div><span class="hl">[SYNERGY]</span> → intent: "fill the form on my screen"</div><div><span class="ok">[OCULUS]</span> → screen capture · form detection · field mapping</div><div><span class="wh">[SENTINEL]</span> → L3 UI control · explicit approval required</div><div><span class="ok">[HERALD]</span> → "Je vais remplir 4 champs. Confirmer ?"</div><div><span class="hl">[USER]</span> → confirmed</div><div><span class="ok">[OCULUS]</span> → click [Name] → type "Arthur Dupont"</div><div><span class="ok">[OCULUS]</span> → click [Email] → type "arthur@nexus.ai"</div><div><span class="ok">[OCULUS]</span> → click [Submit] → form sent</div><div><span class="ok">[SYNERGY]</span> → task complete · L3 audit hash: a3f2c1d8</div></div></div>
      <div class="cap-info"><h3>Vision &amp; Contrôle Écran</h3><p>OCULUS utilise moondream2 local pour voir votre écran, détecter les éléments d'interface et contrôler la souris et le clavier. Entièrement local, aucune capture envoyée à l'extérieur.</p><p>SENTINEL classe toute action UI en L3 — vous voyez l'intégralité du plan avant exécution et approuvez chaque étape. Hash SHA-256 dans l'audit log immuable.</p><div><div class="sec-tag" style="margin-bottom:8px">Agents impliqués</div><div class="cap-agents-used"><div class="cap-agent-pill">OCULUS</div><div class="cap-agent-pill">SYNERGY</div><div class="cap-agent-pill">SENTINEL</div><div class="cap-agent-pill">HERALD</div></div></div><div class="cap-metrics"><div class="cap-metric"><div class="cap-metric-v">L3</div><div class="cap-metric-l">Auth requise</div></div><div class="cap-metric"><div class="cap-metric-v">100%</div><div class="cap-metric-l">Local vision</div></div><div class="cap-metric"><div class="cap-metric-v">SHA256</div><div class="cap-metric-l">Audit log</div></div></div></div>
    </div>
  </div>
</section>

<div class="divider"></div>

<!-- ══ TERMINAL ══ -->
<section id="terminal-demo">
  <div class="sec-inner">
    <div class="sec-header reveal">
      <div class="sec-tag">◆ En Action</div>
      <h2 class="sec-title">Le Swarm au Travail</h2>
      <p class="sec-desc">Une boucle agentique complète — du langage naturel au livrable fini — tournant entièrement sur votre machine.</p>
    </div>
    <div class="terminal-wrap reveal">
      <div class="terminal-header">
        <div class="terminal-dots"><div class="terminal-dot r"></div><div class="terminal-dot y"></div><div class="terminal-dot g"></div></div>
        <div class="terminal-title">NEXUS Neural Bus · Live Trace</div>
        <div class="terminal-status">SOVEREIGN · ALL SYSTEMS ONLINE</div>
      </div>
      <div class="terminal-body" id="terminal-body"></div>
    </div>
  </div>
</section>

<div class="divider"></div>

<!-- ══ COMPARISON — ACCORDION ══ -->
<section id="comparison">
  <div class="sec-inner">
    <div class="sec-header reveal">
      <div class="sec-tag">◆ Paysage Concurrentiel</div>
      <h2 class="sec-title">NEXUS vs Le Marché</h2>
      <p class="sec-desc">Les outils IA cloud sont puissants. Mais ils ne sont pas les vôtres. NEXUS occupe une catégorie à part.</p>
    </div>
    <div class="reveal" style="overflow-x:auto;">
      <table class="comp-table">
        <thead><tr><th>Fonctionnalité</th><th>ChatGPT / Copilot</th><th>Manus / OpenClaw</th><th>LLM Local (bare)</th><th>NEXUS</th></tr></thead>
        <tbody>
          <tr><td>Exécution 100% Locale</td><td><span class="cross">✗</span></td><td><span class="cross">✗</span></td><td><span class="check">✓</span></td><td><span class="comp-nexus">✓ Natif</span></td></tr>
          <tr><td>Sans facturation par token</td><td><span class="cross">✗</span></td><td><span class="cross">✗</span></td><td><span class="check">✓</span></td><td><span class="comp-nexus">✓ Fixe</span></td></tr>
          <tr><td>Orchestration multi-agents</td><td><span class="partial">Partiel</span></td><td><span class="check">✓</span></td><td><span class="cross">✗</span></td><td><span class="comp-nexus">✓ 17 Agents</span></td></tr>
          <tr><td>Mémoire sémantique persistante</td><td><span class="partial">Limité</span></td><td><span class="partial">Session seul.</span></td><td><span class="cross">✗</span></td><td><span class="comp-nexus">✓ ChromaDB RAG</span></td></tr>
          <tr><td>Génération Doc (Word/PDF)</td><td><span class="partial">Texte seul.</span></td><td><span class="partial">Partiel</span></td><td><span class="cross">✗</span></td><td><span class="comp-nexus">✓ Agent SCRIBE</span></td></tr>
          <tr><td>Vision &amp; Contrôle Écran</td><td><span class="partial">Cloud seul.</span></td><td><span class="check">✓</span></td><td><span class="cross">✗</span></td><td><span class="comp-nexus">✓ OCULUS local</span></td></tr>
          <tr><td>RGPD / Compliance natif</td><td><span class="cross">✗</span></td><td><span class="cross">✗</span></td><td><span class="partial">Partiel</span></td><td><span class="comp-nexus">✓ By Design</span></td></tr>
          <tr><td>Fonctionne hors ligne</td><td><span class="cross">✗</span></td><td><span class="cross">✗</span></td><td><span class="check">✓</span></td><td><span class="comp-nexus">✓ Full Offline</span></td></tr>
          <tr><td>Self-Healing Swarm</td><td><span class="cross">✗</span></td><td><span class="cross">✗</span></td><td><span class="cross">✗</span></td><td><span class="comp-nexus">✓ ALCHEMIST</span></td></tr>
          <tr><td>Audit SHA-256 immuable</td><td><span class="cross">✗</span></td><td><span class="partial">Partiel</span></td><td><span class="cross">✗</span></td><td><span class="comp-nexus">✓ Append-only</span></td></tr>
        </tbody>
      </table>
    </div>
  </div>
</section>

<div class="divider"></div>

<!-- ══ SECURITY — ACCORDION ══ -->
<section id="security">
  <div class="sec-inner">
    <div class="sec-header reveal">
      <div class="sec-tag">◆ Moteur SENTINEL</div>
      <h2 class="sec-title">Rien ne se passe<br>sans votre accord.</h2>
      <p class="sec-desc">Chaque action NEXUS est classifiée sur une échelle d'autorisation à 5 niveaux. Vous contrôlez exactement l'autonomie du swarm.</p>
    </div>
    <div class="acc-list reveal">

      <div class="acc-item open">
        <div class="acc-header" onclick="toggleAcc(this)">
          <div class="acc-icon">L0</div>
          <div class="acc-meta">
            <div class="acc-title">Lecture seule — Auto-approuvé</div>
            <div class="acc-subtitle">Fichiers · Mémoire · Captures · Statut — aucune confirmation</div>
          </div>
          <div class="acc-right"><span class="acc-tag" style="color:var(--success);border-color:rgba(42,106,68,0.3)">AUTO</span><div class="acc-chevron">▾</div></div>
        </div>
        <div class="acc-body">
          <div class="acc-content">
            <div class="acc-inner-grid">
              <div>
                <p class="acc-prose">Lectures de fichiers, lookups mémoire, captures écran, vérifications de statut. NEXUS exécute instantanément — aucun risque, aucune intervention requise.</p>
                <p class="acc-prose">Exemples concrets : lire un document PDF, rechercher dans la mémoire sémantique, faire une capture d'écran pour OCULUS, vérifier l'état d'un processus, lister des fichiers.</p>
                <div class="acc-result">Ces actions sont classifiées L0 car elles ne modifient aucun état. Même si un agent est compromis, une action L0 ne peut causer aucun dommage.</div>
              </div>
              <div>
                <div class="acc-sec-bar"><div class="acc-sec-bar-fill" style="width:20%;background:var(--success-light)"></div></div>
                <div class="acc-kv" style="margin-top:12px">
                  <div class="acc-kv-row"><span class="acc-kv-key">Confirmation</span><span class="acc-kv-val" style="color:var(--success)">Aucune requise</span></div>
                  <div class="acc-kv-row"><span class="acc-kv-key">Latence</span><span class="acc-kv-val">&lt; 1ms classification</span></div>
                  <div class="acc-kv-row"><span class="acc-kv-key">Audit log</span><span class="acc-kv-val">Optionnel (configurable)</span></div>
                  <div class="acc-kv-row"><span class="acc-kv-key">Exemples</span><span class="acc-kv-val">file.read · memory.search · screen.capture</span></div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="acc-item">
        <div class="acc-header" onclick="toggleAcc(this)">
          <div class="acc-icon">L1–2</div>
          <div class="acc-meta">
            <div class="acc-title">Écriture &amp; Création — Confirmation douce</div>
            <div class="acc-subtitle">Fichiers · Documents · Brouillons — 5s timeout annulable</div>
          </div>
          <div class="acc-right"><span class="acc-tag" style="color:var(--gold);border-color:var(--gold-border2)">SOFT</span><div class="acc-chevron">▾</div></div>
        </div>
        <div class="acc-body">
          <div class="acc-content">
            <div class="acc-inner-grid">
              <div>
                <p class="acc-prose">Écriture de fichiers, création de documents, brouillons de réponses. NEXUS vous montre ce qu'il va faire et procède après 5 secondes — annulable à tout moment pendant le délai.</p>
                <p class="acc-prose">La confirmation douce est non-bloquante : vous continuez à travailler et une notification discrète apparaît. Un clic annule immédiatement. Passé 5 secondes sans annulation, l'action s'exécute.</p>
                <div class="acc-result"><strong>L1</strong> : écriture simple (un fichier, un brouillon).<br><strong>L2</strong> : écriture multiple ou modification d'existant. Même mécanisme, notification plus visible.</div>
              </div>
              <div>
                <div class="acc-sec-bar"><div class="acc-sec-bar-fill" style="width:45%;background:var(--gold)"></div></div>
                <div class="acc-kv" style="margin-top:12px">
                  <div class="acc-kv-row"><span class="acc-kv-key">Confirmation</span><span class="acc-kv-val" style="color:var(--gold)">Notification · 5s timeout</span></div>
                  <div class="acc-kv-row"><span class="acc-kv-key">Annulation</span><span class="acc-kv-val">1 clic · immédiate</span></div>
                  <div class="acc-kv-row"><span class="acc-kv-key">Exemples L1</span><span class="acc-kv-val">file.write · doc.create</span></div>
                  <div class="acc-kv-row"><span class="acc-kv-key">Exemples L2</span><span class="acc-kv-val">file.modify · batch.create</span></div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="acc-item">
        <div class="acc-header" onclick="toggleAcc(this)">
          <div class="acc-icon">L3</div>
          <div class="acc-meta">
            <div class="acc-title">Réseau &amp; Contrôle UI — Approbation explicite</div>
            <div class="acc-subtitle">Emails · Clics UI · Shell — plan complet avant exécution</div>
          </div>
          <div class="acc-right"><span class="acc-tag" style="color:var(--gold-dark);border-color:var(--gold-border2)">EXPLICIT</span><div class="acc-chevron">▾</div></div>
        </div>
        <div class="acc-body">
          <div class="acc-content">
            <div class="acc-inner-grid">
              <div>
                <p class="acc-prose">Envois d'emails, clics UI, commandes shell. Vous voyez le plan d'action complet — chaque clic, chaque frappe, chaque commande — et approuvez explicitement avant toute exécution.</p>
                <p class="acc-prose">Le plan est présenté dans un modal dédié qui liste : l'agent qui agit, l'action précise, les données impliquées, et l'impact attendu. Vous pouvez approuver tout, approuver partiellement, ou annuler.</p>
                <div class="acc-result">Toutes les actions L3 produisent un hash SHA-256 dans l'audit log immuable, même si vous les annulez. La décision est tracée.</div>
              </div>
              <div>
                <div class="acc-sec-bar"><div class="acc-sec-bar-fill" style="width:65%;background:var(--gold)"></div></div>
                <div class="acc-kv" style="margin-top:12px">
                  <div class="acc-kv-row"><span class="acc-kv-key">Confirmation</span><span class="acc-kv-val" style="color:var(--gold-dark)">Modale · approbation active</span></div>
                  <div class="acc-kv-row"><span class="acc-kv-key">Plan présenté</span><span class="acc-kv-val">Chaque étape détaillée</span></div>
                  <div class="acc-kv-row"><span class="acc-kv-key">Exemples</span><span class="acc-kv-val">email.send · ui.click · shell.exec</span></div>
                  <div class="acc-kv-row"><span class="acc-kv-key">Audit</span><span class="acc-kv-val">SHA-256 · même si annulé</span></div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="acc-item">
        <div class="acc-header" onclick="toggleAcc(this)">
          <div class="acc-icon">L4–5</div>
          <div class="acc-meta">
            <div class="acc-title">Système &amp; Cryptographie — Blocage dur</div>
            <div class="acc-subtitle">Processus · Clés · Système — passphrase requise · non-contournable</div>
          </div>
          <div class="acc-right"><span class="acc-tag" style="color:var(--danger);border-color:rgba(139,42,42,0.3)">HARD</span><div class="acc-chevron">▾</div></div>
        </div>
        <div class="acc-body">
          <div class="acc-content">
            <div class="acc-inner-grid">
              <div>
                <p class="acc-prose">Modifications système, gestion de clés de chiffrement, terminaison de processus. Requiert un déverrouillage manuel de SENTINEL avec passphrase. Non-contournable par aucun agent.</p>
                <p class="acc-prose">SENTINEL est exécuté en processus séparé avec un utilisateur système dédié. Aucun agent NEXUS ne peut modifier le code de SENTINEL, escalader ses propres droits ou désactiver la classification L4–L5.</p>
                <p class="acc-prose"><strong>L4</strong> — Modifications système, accès registre, gestion de processus sensibles.<br><strong>L5</strong> — Gestion des clés de chiffrement maîtres, opérations de déchiffrement bulk, modifications de SENTINEL lui-même.</p>
              </div>
              <div>
                <div class="acc-sec-bar"><div class="acc-sec-bar-fill" style="width:100%;background:var(--danger)"></div></div>
                <div class="acc-kv" style="margin-top:12px">
                  <div class="acc-kv-row"><span class="acc-kv-key">Déverrouillage</span><span class="acc-kv-val" style="color:var(--danger)">Passphrase SENTINEL</span></div>
                  <div class="acc-kv-row"><span class="acc-kv-key">Contournable</span><span class="acc-kv-val" style="color:var(--danger)">Non — jamais</span></div>
                  <div class="acc-kv-row"><span class="acc-kv-key">Processus</span><span class="acc-kv-val">Isolé · utilisateur dédié</span></div>
                  <div class="acc-kv-row"><span class="acc-kv-key">Auto-protect</span><span class="acc-kv-val">SENTINEL se protège lui-même</span></div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

    </div>
  </div>
</section>

<div class="divider"></div>

<!-- ══ USE CASES — ACCORDION ══ -->
<section id="usecases">
  <div class="sec-inner">
    <div class="sec-header reveal">
      <div class="sec-tag">◆ Conçu Pour</div>
      <h2 class="sec-title">Qui utilise NEXUS</h2>
      <p class="sec-desc">Fait pour les professionnels qui traitent des données sensibles et ne peuvent pas compromettre la vie privée, la conformité ou le contrôle.</p>
    </div>
    <div class="acc-list reveal">

      <div class="acc-item open">
        <div class="acc-header" onclick="toggleAcc(this)">
          <div class="acc-icon">LC</div>
          <div class="acc-meta">
            <div class="acc-title">Cabinets d'avocats</div>
            <div class="acc-subtitle">Rédaction · Jurisprudence · Délais · Dossiers clients locaux</div>
          </div>
          <div class="acc-right"><span class="acc-tag">Juridique</span><div class="acc-chevron">▾</div></div>
        </div>
        <div class="acc-body">
          <div class="acc-content">
            <div class="acc-inner-grid">
              <div>
                <p class="acc-prose">Rédigez contrats, mises en demeure et mémoires en secondes. Recherchez la jurisprudence, suivez les délais, gérez les dossiers clients — tout en local. Zéro fuite externe, conformité RGPD native.</p>
                <p class="acc-prose"><strong>SCRIBE</strong> génère vos documents depuis vos templates. <strong>LIBRARIAN</strong> rappelle instantanément le contexte de chaque client — toutes les interactions passées, les clauses spécifiques négociées, les préférences de juridiction.</p>
                <p class="acc-prose"><strong>CIPHER</strong> chiffre automatiquement tous les documents client en AES-256. <strong>CHRONOS</strong> surveille les délais procéduraux et vous alerte avant expiration.</p>
                <div class="acc-result"><strong>Cas réel :</strong> NDA multi-partie pour client récurrent → LIBRARIAN rappelle les 14 interactions passées, SCRIBE génère en 4.1s un NDA personnalisé avec les clauses spécifiques historiquement acceptées. Chiffré, archivé, traçable.</div>
              </div>
              <div>
                <div class="acc-code-block">
<div class="hl">[SCRIBE]</div>
<div>→ template: NDA_FR_v3</div>
<div>→ customizing 8 clauses</div>
<div class="hl">[LIBRARIAN]</div>
<div>→ recall Acme: 14 mémoires</div>
<div>→ juridiction: Paris · droit fr.</div>
<div class="ok">[CIPHER] → AES-256 at rest</div>
<div class="ok">[CHRONOS] → deadline +30j ajouté</div>
<div class="ok">NDA.docx · 8 pages · 4.1s</div>
                </div>
                <div class="acc-pills-row">
                  <div class="acc-pill">SCRIBE</div><div class="acc-pill">LIBRARIAN</div><div class="acc-pill">CIPHER</div><div class="acc-pill">CHRONOS</div><div class="acc-pill">SENTINEL</div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="acc-item">
        <div class="acc-header" onclick="toggleAcc(this)">
          <div class="acc-icon">MD</div>
          <div class="acc-meta">
            <div class="acc-title">Praticiens &amp; Cliniques</div>
            <div class="acc-subtitle">Dossiers patients · Facturation · Rendez-vous · RGPD Art. 9</div>
          </div>
          <div class="acc-right"><span class="acc-tag">Médical</span><div class="acc-chevron">▾</div></div>
        </div>
        <div class="acc-body">
          <div class="acc-content">
            <div class="acc-inner-grid">
              <div>
                <p class="acc-prose">Dossiers patients, automatisation de facturation, gestion de rendez-vous — traités localement sans exposition cloud. Conçu pour la conformité RGPD Art. 9 sur les données de santé catégorie spéciale.</p>
                <p class="acc-prose"><strong>LIBRARIAN</strong> maintient un dossier sémantique par patient — antécédents, traitements en cours, interactions médicamenteuses documentées. Accessible en moins de 30ms avant chaque consultation.</p>
                <p class="acc-prose"><strong>HERALD</strong> envoie des rappels de rendez-vous (SMS / email) automatiquement 24h et 2h avant. <strong>SCRIBE</strong> génère les ordonnances et compte-rendus selon vos templates réglementaires.</p>
              </div>
              <div>
                <div class="acc-kv">
                  <div class="acc-kv-row"><span class="acc-kv-key">Conformité</span><span class="acc-kv-val">RGPD Art. 9 · données santé</span></div>
                  <div class="acc-kv-row"><span class="acc-kv-key">Dossier patient</span><span class="acc-kv-val">LIBRARIAN · sémantique · &lt;30ms</span></div>
                  <div class="acc-kv-row"><span class="acc-kv-key">Rappels</span><span class="acc-kv-val">HERALD · 24h + 2h avant RDV</span></div>
                  <div class="acc-kv-row"><span class="acc-kv-key">Ordonnances</span><span class="acc-kv-val">SCRIBE · templates réglementaires</span></div>
                  <div class="acc-kv-row"><span class="acc-kv-key">Chiffrement</span><span class="acc-kv-val">CIPHER · AES-256 · toutes données</span></div>
                </div>
                <div class="acc-pills-row">
                  <div class="acc-pill">LIBRARIAN</div><div class="acc-pill">HERALD</div><div class="acc-pill">SCRIBE</div><div class="acc-pill">SENTINEL</div><div class="acc-pill">CIPHER</div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="acc-item">
        <div class="acc-header" onclick="toggleAcc(this)">
          <div class="acc-icon">DV</div>
          <div class="acc-meta">
            <div class="acc-title">Développeurs &amp; CTOs</div>
            <div class="acc-subtitle">GHOST 14B · AST-aware · Tests auto · Copilot local souverain</div>
          </div>
          <div class="acc-right"><span class="acc-tag">Dev</span><div class="acc-chevron">▾</div></div>
        </div>
        <div class="acc-body">
          <div class="acc-content">
            <div class="acc-inner-grid">
              <div>
                <p class="acc-prose">GHOST écrit, révise et patche le code avec tout le contexte de la codebase. FORGE applique les changements atomiquement avec snapshot. TERMINUS teste. Votre Copilot local sur modèle qwen2.5-coder:14B.</p>
                <p class="acc-prose">Contrairement à GitHub Copilot, GHOST lit l'AST complet de votre projet — il comprend votre architecture, vos conventions de nommage et votre style. Les patches générés s'intègrent nativement sans refactoring.</p>
                <p class="acc-prose"><strong>TERMINUS</strong> exécute pytest, jest, ou votre runner custom après chaque patch. En cas d'échec, GHOST reçoit le traceback complet et itère automatiquement — jusqu'à 3 cycles.</p>
              </div>
              <div>
                <div class="acc-code-block">
<div class="hl">[GHOST] qwen2.5-coder:14b</div>
<div>→ AST scan: 847 lignes</div>
<div>→ 3 injection points trouvés</div>
<div class="ok">[FORGE] patch atomique + snapshot</div>
<div class="ok">[TERMINUS] pytest: 12/12 ✓</div>
<div>→ commit: "feat: JWT auth"</div>
<br>
<div class="hl">Si test échoue :</div>
<div class="ok">[GHOST] analyse traceback</div>
<div>→ correction auto · retry 1/3</div>
                </div>
                <div class="acc-pills-row">
                  <div class="acc-pill">GHOST</div><div class="acc-pill">ATLAS</div><div class="acc-pill">FORGE</div><div class="acc-pill">TERMINUS</div><div class="acc-pill">ALCHEMIST</div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="acc-item">
        <div class="acc-header" onclick="toggleAcc(this)">
          <div class="acc-icon">SM</div>
          <div class="acc-meta">
            <div class="acc-title">PME &amp; Entrepreneurs</div>
            <div class="acc-subtitle">Triage email · Reporting · Devis · Brief vocal · Sans DSI</div>
          </div>
          <div class="acc-right"><span class="acc-tag">PME</span><div class="acc-chevron">▾</div></div>
        </div>
        <div class="acc-body">
          <div class="acc-content">
            <div class="acc-inner-grid">
              <div>
                <p class="acc-prose">Triage email, reporting hebdomadaire, suivi clients, rédaction de devis — une couche d'opérations digitales complète pour des équipes de 1 à 20 personnes. Sans DSI requis, installable en 30 minutes.</p>
                <p class="acc-prose">NEXUS remplace une dizaine d'outils SaaS fragmentés. <strong>PROCURE</strong> trie votre boîte toutes les 2h. <strong>SCRIBE</strong> génère vos rapports PDF client. <strong>HERALD</strong> vous brieffe vocalement à 8h chaque matin sur les priorités de la journée.</p>
                <div class="acc-result"><strong>ROI typique :</strong> Une PME de 10 personnes économise ~€3 000/an en abonnements SaaS + 2h/personne/semaine de tâches manuelles automatisées.</div>
              </div>
              <div>
                <div class="acc-kv">
                  <div class="acc-kv-row"><span class="acc-kv-key">Email</span><span class="acc-kv-val">PROCURE · triage toutes les 2h</span></div>
                  <div class="acc-kv-row"><span class="acc-kv-key">Rapport client</span><span class="acc-kv-val">SCRIBE · PDF hebdo auto</span></div>
                  <div class="acc-kv-row"><span class="acc-kv-key">Brief matin</span><span class="acc-kv-val">HERALD · vocal à 8h</span></div>
                  <div class="acc-kv-row"><span class="acc-kv-key">Setup</span><span class="acc-kv-val">30 min · sans DSI</span></div>
                  <div class="acc-kv-row"><span class="acc-kv-key">Équipe max</span><span class="acc-kv-val">Illimité · licence fixe</span></div>
                </div>
                <div class="acc-pills-row">
                  <div class="acc-pill">SYNERGY</div><div class="acc-pill">PROCURE</div><div class="acc-pill">SCRIBE</div><div class="acc-pill">HERALD</div><div class="acc-pill">CHRONOS</div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="acc-item">
        <div class="acc-header" onclick="toggleAcc(this)">
          <div class="acc-icon">RS</div>
          <div class="acc-meta">
            <div class="acc-title">Chercheurs &amp; Analystes</div>
            <div class="acc-subtitle">Revue de littérature · OCR figures · Corpus sémantique vivant</div>
          </div>
          <div class="acc-right"><span class="acc-tag">Recherche</span><div class="acc-chevron">▾</div></div>
        </div>
        <div class="acc-body">
          <div class="acc-content">
            <div class="acc-inner-grid">
              <div>
                <p class="acc-prose">Revues de littérature autonomes, analyses concurrentielles, extraction depuis PDFs et sources web. OCULUS lit les graphiques. LIBRARIAN construit un index sémantique vivant de votre corpus.</p>
                <p class="acc-prose"><strong>PROCURE</strong> crawle jusqu'à 100 sources web simultanément et extrait le contenu des PDFs (texte + images). <strong>OCULUS</strong> reconnaît et transcrit les figures, graphiques et tableaux via OCR vision (moondream2).</p>
                <p class="acc-prose"><strong>ATLAS</strong> synthétise le corpus en rapport structuré. <strong>SCRIBE</strong> formate selon vos templates institutionnels — APA, Chicago, ou format custom.</p>
              </div>
              <div>
                <div class="acc-code-block">
<div class="hl">[PROCURE] · 40 sources web</div>
<div>→ extraction texte + métadonnées</div>
<div class="hl">[OCULUS] · OCR figure/chart</div>
<div>→ 6 graphiques transcrits</div>
<div class="hl">[LIBRARIAN] · indexation corpus</div>
<div>→ BGE-M3 · 1024-d · 2 840 chunks</div>
<div class="ok">[ATLAS] synthèse: 18 pages</div>
<div class="ok">[SCRIBE] rapport PDF APA · 38.4s</div>
                </div>
                <div class="acc-pills-row">
                  <div class="acc-pill">PROCURE</div><div class="acc-pill">OCULUS</div><div class="acc-pill">LIBRARIAN</div><div class="acc-pill">ATLAS</div><div class="acc-pill">SCRIBE</div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="acc-item">
        <div class="acc-header" onclick="toggleAcc(this)">
          <div class="acc-icon">EX</div>
          <div class="acc-meta">
            <div class="acc-title">Dirigeants &amp; Fondateurs</div>
            <div class="acc-subtitle">Chef de cabinet IA · Brief vocal · Intel concurrentiel · Board deck</div>
          </div>
          <div class="acc-right"><span class="acc-tag">Direction</span><div class="acc-chevron">▾</div></div>
        </div>
        <div class="acc-body">
          <div class="acc-content">
            <div class="acc-inner-grid">
              <div>
                <p class="acc-prose">Briefs quotidiens de HERALD, intel concurrentiel de PROCURE, notes de réunion de SCRIBE, gestion calendrier de CHRONOS. Un chef de cabinet privé qui ne fuite jamais vers la concurrence.</p>
                <p class="acc-prose">Chaque matin à 8h, <strong>HERALD</strong> vous brieffe vocalement : priorités email, actualités secteur, agenda du jour. Pendant vos réunions, <strong>OCULUS</strong> peut prendre des notes en transcrivant l'audio.</p>
                <p class="acc-prose"><strong>PROCURE</strong> surveille la presse, les annonces concurrentes et les publications réglementaires — vous recevez un digest quotidien synthétisé par ATLAS, sans jamais avoir à scroller.</p>
              </div>
              <div>
                <div class="acc-kv">
                  <div class="acc-kv-row"><span class="acc-kv-key">Brief matin</span><span class="acc-kv-val">HERALD · vocal · 8h quotidien</span></div>
                  <div class="acc-kv-row"><span class="acc-kv-key">Intel concurr.</span><span class="acc-kv-val">PROCURE · digest quotidien</span></div>
                  <div class="acc-kv-row"><span class="acc-kv-key">Réunions</span><span class="acc-kv-val">OCULUS · transcription + notes</span></div>
                  <div class="acc-kv-row"><span class="acc-kv-key">Board deck</span><span class="acc-kv-val">SCRIBE · auto-draft PowerPoint</span></div>
                  <div class="acc-kv-row"><span class="acc-kv-key">Calendrier</span><span class="acc-kv-val">CHRONOS · planning optimisé</span></div>
                </div>
                <div class="acc-pills-row">
                  <div class="acc-pill">HERALD</div><div class="acc-pill">PROCURE</div><div class="acc-pill">SCRIBE</div><div class="acc-pill">CHRONOS</div><div class="acc-pill">OCULUS</div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

    </div>
  </div>
</section>

<div class="divider"></div>

<!-- ══ HOW IT WORKS — ACCORDION ══ -->
<section id="howitworks">
  <div class="sec-inner">
    <div class="sec-header reveal">
      <div class="sec-tag">◆ Démarrage</div>
      <h2 class="sec-title">Opérationnel en 4 étapes.<br>Zéro configuration requise.</h2>
    </div>
    <div class="acc-list reveal">

      <div class="acc-item open">
        <div class="acc-header" onclick="toggleAcc(this)">
          <div class="acc-icon" style="font-family:var(--fd);font-size:22px">1</div>
          <div class="acc-meta">
            <div class="acc-title">Installer Ollama</div>
            <div class="acc-subtitle">Runtime LLM local · Détection matérielle auto · Stack optimale</div>
          </div>
          <div class="acc-right"><div class="acc-chevron">▾</div></div>
        </div>
        <div class="acc-body">
          <div class="acc-content">
            <div class="acc-inner-grid">
              <div>
                <p class="acc-prose">Téléchargez Ollama depuis ollama.ai — disponible macOS, Linux et Windows (WSL2). NEXUS détecte automatiquement votre configuration matérielle et recommande la stack de modèles optimale.</p>
                <p class="acc-prose"><strong>GPU Nvidia 8GB+</strong> → stack complète : mistral:7b + qwen2.5-coder:14b + moondream2<br><strong>Apple Silicon M1/M2/M3</strong> → stack optimisée Metal : performance quasi-GPU<br><strong>CPU-only 32GB RAM</strong> → stack légère : mistral:7b + qwen2.5-coder:7b</p>
                <div class="acc-result"><strong>Temps de setup Ollama :</strong> 5 minutes · Téléchargement des modèles : 10–30 min selon connexion · Tout est automatisé par le script NEXUS.</div>
              </div>
              <div>
                <div class="acc-kv">
                  <div class="acc-kv-row"><span class="acc-kv-key">GPU Nvidia</span><span class="acc-kv-val">8GB VRAM min · CUDA 11.8+</span></div>
                  <div class="acc-kv-row"><span class="acc-kv-key">Apple Silicon</span><span class="acc-kv-val">M1 / M2 / M3 · Metal natif</span></div>
                  <div class="acc-kv-row"><span class="acc-kv-key">CPU-only</span><span class="acc-kv-val">32GB RAM · stack légère</span></div>
                  <div class="acc-kv-row"><span class="acc-kv-key">OS</span><span class="acc-kv-val">macOS · Linux · Windows WSL2</span></div>
                  <div class="acc-kv-row"><span class="acc-kv-key">Stockage</span><span class="acc-kv-val">15–40GB selon stack choisie</span></div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="acc-item">
        <div class="acc-header" onclick="toggleAcc(this)">
          <div class="acc-icon" style="font-family:var(--fd);font-size:22px">2</div>
          <div class="acc-meta">
            <div class="acc-title">Lancer NEXUS</div>
            <div class="acc-subtitle">python main.py · Dashboard localhost:8000 · 30 secondes</div>
          </div>
          <div class="acc-right"><div class="acc-chevron">▾</div></div>
        </div>
        <div class="acc-body">
          <div class="acc-content">
            <div class="acc-inner-grid">
              <div>
                <p class="acc-prose">Une seule commande lance l'ensemble du système. Le dashboard s'ouvre sur localhost:8000 dans votre navigateur. Tous les agents s'initialisent, les modèles chargent en mémoire, et le Neural Bus se met en ligne.</p>
                <p class="acc-prose">La séquence de démarrage dure environ 30 secondes. VISIONARY optimise automatiquement la répartition des modèles selon la VRAM disponible. SENTINEL initialise les clés de chiffrement et l'audit log.</p>
              </div>
              <div>
                <div class="acc-code-block">
<div class="hl">$ python main.py</div>
<div></div>
<div class="wh">NEXUS Sovereign Intelligence v9</div>
<div>Détection GPU: RTX 3090 · 24GB ✓</div>
<div>Chargement mistral:7b ... <span class="ok">✓ 4.2s</span></div>
<div>Chargement qwen2.5-coder ... <span class="ok">✓ 8.1s</span></div>
<div>Neural Bus WebSocket ... <span class="ok">✓ :8765</span></div>
<div>Initialisation 17 agents ... <span class="ok">✓</span></div>
<div>SENTINEL auth engine ... <span class="ok">✓ L0-L5</span></div>
<div class="ok">Dashboard → http://localhost:8000</div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="acc-item">
        <div class="acc-header" onclick="toggleAcc(this)">
          <div class="acc-icon" style="font-family:var(--fd);font-size:22px">3</div>
          <div class="acc-meta">
            <div class="acc-title">Onboarding 2 min</div>
            <div class="acc-subtitle">Calibration personnelle · Langue · Domaine · Seuils SENTINEL</div>
          </div>
          <div class="acc-right"><div class="acc-chevron">▾</div></div>
        </div>
        <div class="acc-body">
          <div class="acc-content">
            <div class="acc-inner-grid">
              <div>
                <p class="acc-prose">NEXUS se calibre à vous lors du premier lancement — votre nom, langue préférée, domaine métier, niveau de sécurité SENTINEL et style de communication. Le swarm adapte ses modèles, son ton et ses seuils d'autorité.</p>
                <p class="acc-prose">L'onboarding enregistre vos préférences comme mémoire fondatrice dans LIBRARIAN. SYNERGY adapte son routage à votre vocabulaire métier. HERALD ajuste son niveau de proactivité selon vos préférences.</p>
              </div>
              <div>
                <div class="acc-kv">
                  <div class="acc-kv-row"><span class="acc-kv-key">Langue</span><span class="acc-kv-val">fr-FR · en-US · auto-detect</span></div>
                  <div class="acc-kv-row"><span class="acc-kv-key">Domaine</span><span class="acc-kv-val">Juridique · Tech · Médical · PME…</span></div>
                  <div class="acc-kv-row"><span class="acc-kv-key">SENTINEL</span><span class="acc-kv-val">Seuils L0–L5 configurables</span></div>
                  <div class="acc-kv-row"><span class="acc-kv-key">Ton NEXUS</span><span class="acc-kv-val">Formel · Concis · Détaillé</span></div>
                  <div class="acc-kv-row"><span class="acc-kv-key">Durée</span><span class="acc-kv-val">~2 minutes</span></div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="acc-item">
        <div class="acc-header" onclick="toggleAcc(this)">
          <div class="acc-icon" style="font-family:var(--fd);font-size:22px">4</div>
          <div class="acc-meta">
            <div class="acc-title">Déléguez librement</div>
            <div class="acc-subtitle">Parlez · Tapez · Raccourci · DAG visible · Contrôle total</div>
          </div>
          <div class="acc-right"><div class="acc-chevron">▾</div></div>
        </div>
        <div class="acc-body">
          <div class="acc-content">
            <div class="acc-inner-grid">
              <div>
                <p class="acc-prose">Parlez, tapez, ou déclenchez via raccourci. NEXUS planifie la tâche, vous montre le DAG d'exécution, et la réalise — vous restez en contrôle sans être dans la boucle à chaque étape.</p>
                <p class="acc-prose">Le DAG est visible en temps réel dans le dashboard : chaque nœud s'allume au passage, les durées s'affichent, les confirmations SENTINEL apparaissent en surbrillance. Vous voyez exactement ce que fait NEXUS à chaque instant.</p>
                <div class="acc-result"><strong>Première tâche recommandée :</strong> "Trie mes emails et dis-moi ce qui est urgent" — vous verrez le swarm complet en action en moins de 10 secondes.</div>
              </div>
              <div>
                <div class="acc-steps">
                  <div class="acc-step"><div class="acc-step-num">◈</div><div class="acc-step-text"><strong>Voix</strong> — "Nexus, trie mes emails" · COURIER transcrit · SYNERGY route</div></div>
                  <div class="acc-step"><div class="acc-step-num">◈</div><div class="acc-step-text"><strong>Texte</strong> — Dashboard ou raccourci global Ctrl+Shift+N</div></div>
                  <div class="acc-step"><div class="acc-step-num">◈</div><div class="acc-step-text"><strong>DAG visible</strong> — Plan d'exécution affiché avant de commencer</div></div>
                  <div class="acc-step"><div class="acc-step-num">◈</div><div class="acc-step-text"><strong>SENTINEL</strong> — Confirmations selon niveau · jamais de surprise</div></div>
                  <div class="acc-step"><div class="acc-step-num">◈</div><div class="acc-step-text"><strong>Résultat</strong> — Fichier, notification, réponse · en quelques secondes</div></div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

    </div>
  </div>
</section>

<!-- FOOTER -->
<footer>
  <div class="footer-inner">
    <div class="footer-top">
      <div class="footer-brand">
        <div class="logo-n">NEXUS</div>
        <div class="logo-sub">Sovereign Intelligence · v9</div>
        <p>Le premier OS IA local. 17 agents, zéro cloud, souveraineté totale des données. Conçu pour les professionnels qui ne peuvent pas compromettre vie privée, conformité et contrôle.</p>
      </div>
      <div class="footer-col">
        <h4>Produit</h4>
        <a href="#audience-section">Pour les entreprises</a>
        <a href="#audience-section">Pour les développeurs</a>
        <a href="#capabilities">Fonctionnalités</a>
        <a href="#workflow-section">Workflows</a>
      </div>
      <div class="footer-col">
        <h4>Cas d'usage</h4>
        <a href="#usecases">Juridique</a>
        <a href="#usecases">Médical</a>
        <a href="#usecases">Développement</a>
        <a href="#usecases">Recherche</a>
      </div>
      <div class="footer-col">
        <h4>Société</h4>
        <a href="mailto:arthurdecamps07@gmail.com">Contact</a>
        <a href="#waitlist">Accès anticipé</a>
        <a href="#comparison">vs Concurrents</a>
        <a href="#security">Sécurité</a>
      </div>
    </div>
    <div class="footer-bottom">
      <p>© 2026 NEXUS — Sovereign Intelligence. Tous droits réservés.</p>
      <div class="footer-badges">
        <div class="footer-badge">100% Local</div>
        <div class="footer-badge">RGPD Natif</div>
        <div class="footer-badge">AES-256</div>
        <div class="footer-badge">Offline-Ready</div>
      </div>
    </div>
  </div>
</footer>

<script>
// ── ORB STATES ────────────────────────────────────────────────
const ORB_STATES = {
  idle:     { speedRot:.003, waveAmp:.04, waveFreq:1.8, pulseAmp:.022, opacity:.82, r:.788, g:.659, b:.298, label:'Nexus', sub:'Awaiting Command', glowColor:'rgba(184,151,42,0.10)' },
  thinking: { speedRot:.016, waveAmp:.22, waveFreq:4.2, pulseAmp:.09,  opacity:.98, r:1,    g:.87,  b:.35,  label:'Reasoning', sub:'Deep Cognitive Processing', glowColor:'rgba(255,220,80,0.20)' },
  workflow: { speedRot:.009, waveAmp:.14, waveFreq:3.2, pulseAmp:.06,  opacity:.93, r:.4,   g:.72,  b:1,    label:'Orchestrating', sub:'Building Workflow', glowColor:'rgba(80,160,255,0.18)' },
  coding:   { speedRot:.018, waveAmp:.18, waveFreq:5.0, pulseAmp:.07,  opacity:.96, r:.22,  g:.80,  b:.42,  label:'Generating', sub:'Code Engine Active', glowColor:'rgba(58,186,114,0.18)' },
  document: { speedRot:.007, waveAmp:.10, waveFreq:2.8, pulseAmp:.04,  opacity:.88, r:.9,   g:.75,  b:.3,   label:'Writing', sub:'Document Creation', glowColor:'rgba(184,151,42,0.14)' },
  memory:   { speedRot:.006, waveAmp:.12, waveFreq:2.2, pulseAmp:.05,  opacity:.90, r:.6,   g:.4,   b:.88,  label:'Recalling', sub:'Semantic Memory Search', glowColor:'rgba(140,80,200,0.18)' },
  research: { speedRot:.012, waveAmp:.16, waveFreq:3.6, pulseAmp:.07,  opacity:.95, r:.3,   g:.65,  b:.95,  label:'Researching', sub:'Web Intelligence Active', glowColor:'rgba(50,140,240,0.18)' },
  security: { speedRot:.004, waveAmp:.06, waveFreq:1.4, pulseAmp:.03,  opacity:.85, r:.88,  g:.22,  b:.14,  label:'Auditing', sub:'SENTINEL Authority Engine', glowColor:'rgba(139,42,42,0.14)' },
};
const ORB_T = {...ORB_STATES.idle};
const ORB_C = {...ORB_STATES.idle};
let orbRenderer, orbScene, orbCamera, orbGroup, orbClock, orbUniforms;
let mNeb, mR1, mR2;

function setOrb(state) {
  const s = ORB_STATES[state] || ORB_STATES.idle;
  Object.assign(ORB_T, s);
  const lbl = document.getElementById('orb-hero-label');
  const sub = document.getElementById('orb-hero-sub');
  if (lbl) { lbl.style.opacity=0; setTimeout(()=>{ lbl.textContent=s.label; lbl.style.opacity=1; },280); }
  if (sub) { sub.style.opacity=0; setTimeout(()=>{ sub.textContent=s.sub; sub.style.opacity=1; },380); }
  const glow = document.getElementById('orb-glow-hero');
  if (glow) glow.style.background = `radial-gradient(circle, ${s.glowColor} 0%, transparent 65%)`;
}

function buildOrb(canvasId) {
  const canvas = document.getElementById(canvasId);
  if (!canvas || typeof THREE === 'undefined') return;
  const W = canvas.parentElement.clientWidth || 420;
  const H = canvas.parentElement.clientHeight || 420;
  orbScene = new THREE.Scene();
  orbCamera = new THREE.PerspectiveCamera(52, W/H, 0.1, 100);
  orbCamera.position.z = 2.6;
  orbRenderer = new THREE.WebGLRenderer({ canvas, antialias: true, alpha: true });
  orbRenderer.setPixelRatio(Math.min(window.devicePixelRatio, 2));
  orbRenderer.setSize(W, H);
  orbRenderer.setClearColor(0, 0);
  orbGroup = new THREE.Group();
  orbScene.add(orbGroup);
  orbClock = new THREE.Clock();

  orbUniforms = {
    uTime:{value:0}, uWaveAmp:{value:ORB_C.waveAmp}, uWaveFreq:{value:ORB_C.waveFreq},
    uColor:{value:new THREE.Color(ORB_C.r,ORB_C.g,ORB_C.b)}, uOpacity:{value:ORB_C.opacity}, uSize:{value:3.4},
  };
  const vS = `uniform float uTime,uWaveAmp,uWaveFreq,uSize;void main(){vec3 p=position;float w=sin(uWaveFreq*p.y*3.14159+uTime*2.)*cos(uWaveFreq*p.x*3.14159+uTime*1.7)*uWaveAmp;p+=normal*w;gl_Position=projectionMatrix*modelViewMatrix*vec4(p,1.);gl_PointSize=uSize;}`;
  const fS = `uniform vec3 uColor;uniform float uOpacity;void main(){float d=length(gl_PointCoord-.5);if(d>.5)discard;float a=smoothstep(.5,0.,d)*uOpacity;gl_FragColor=vec4(uColor,a);}`;
  const mat = new THREE.ShaderMaterial({uniforms:orbUniforms,vertexShader:vS,fragmentShader:fS,transparent:true,depthWrite:false});

  const N=3000,R=1.,phi=Math.PI*(3-Math.sqrt(5)),pos=new Float32Array(N*3),nor=new Float32Array(N*3);
  for(let i=0;i<N;i++){const y=1-(i/(N-1))*2,r=Math.sqrt(1-y*y),th=phi*i,x=Math.cos(th)*r,z=Math.sin(th)*r;pos[i*3]=x*R;pos[i*3+1]=y*R;pos[i*3+2]=z*R;nor[i*3]=x;nor[i*3+1]=y;nor[i*3+2]=z;}
  const g=new THREE.BufferGeometry();g.setAttribute('position',new THREE.BufferAttribute(pos,3));g.setAttribute('normal',new THREE.BufferAttribute(nor,3));orbGroup.add(new THREE.Points(g,mat));

  const NB=500,pN=new Float32Array(NB*3),nN=new Float32Array(NB*3);
  for(let i=0;i<NB;i++){const t=Math.random()*Math.PI*2,cp=Math.random()*2-1,sp=Math.sqrt(1-cp*cp),rn=.1+Math.random()*.65;pN[i*3]=rn*sp*Math.cos(t);pN[i*3+1]=rn*cp;pN[i*3+2]=rn*sp*Math.sin(t);nN[i*3]=pN[i*3]/(rn||1);nN[i*3+1]=pN[i*3+1]/(rn||1);nN[i*3+2]=pN[i*3+2]/(rn||1);}
  mNeb=mat.clone();mNeb.uniforms={uTime:orbUniforms.uTime,uWaveAmp:{value:.03},uWaveFreq:{value:.9},uColor:orbUniforms.uColor,uOpacity:{value:.35},uSize:{value:2.2}};
  const gN=new THREE.BufferGeometry();gN.setAttribute('position',new THREE.BufferAttribute(pN,3));gN.setAttribute('normal',new THREE.BufferAttribute(nN,3));orbGroup.add(new THREE.Points(gN,mNeb));

  const RI=800,pR=new Float32Array(RI*3),nR=new Float32Array(RI*3);
  for(let i=0;i<RI;i++){const a=(i/RI)*Math.PI*2;pR[i*3]=Math.cos(a)*1.06;pR[i*3+1]=(Math.random()-.5)*.012;pR[i*3+2]=Math.sin(a)*1.06;nR[i*3]=Math.cos(a);nR[i*3+2]=Math.sin(a);}
  mR1=mat.clone();mR1.uniforms={uTime:orbUniforms.uTime,uWaveAmp:{value:.003},uWaveFreq:{value:1},uColor:orbUniforms.uColor,uOpacity:{value:.75},uSize:{value:2.5}};
  const gR=new THREE.BufferGeometry();gR.setAttribute('position',new THREE.BufferAttribute(pR,3));gR.setAttribute('normal',new THREE.BufferAttribute(nR,3));orbGroup.add(new THREE.Points(gR,mR1));

  const RI2=400,pR2=new Float32Array(RI2*3),nR2=new Float32Array(RI2*3);
  for(let i=0;i<RI2;i++){const a=(i/RI2)*Math.PI*2;pR2[i*3]=Math.cos(a)*1.08;pR2[i*3+1]=Math.sin(a)*0.22;pR2[i*3+2]=Math.sin(a)*1.08*.96;nR2[i*3]=Math.cos(a);nR2[i*3+1]=0;nR2[i*3+2]=Math.sin(a);}
  mR2=mat.clone();mR2.uniforms={uTime:orbUniforms.uTime,uWaveAmp:{value:.003},uWaveFreq:{value:.8},uColor:orbUniforms.uColor,uOpacity:{value:.3},uSize:{value:1.8}};
  const gR2=new THREE.BufferGeometry();gR2.setAttribute('position',new THREE.BufferAttribute(pR2,3));gR2.setAttribute('normal',new THREE.BufferAttribute(nR2,3));orbGroup.add(new THREE.Points(gR2,mR2));

  function animate() {
    requestAnimationFrame(animate);
    const t=orbClock.getElapsedTime(),L=.045;
    for(const k of['speedRot','waveAmp','waveFreq','pulseAmp','opacity','r','g','b'])ORB_C[k]+=(ORB_T[k]-ORB_C[k])*L;
    orbGroup.rotation.y+=ORB_C.speedRot;orbGroup.rotation.x=Math.sin(t*.11)*.06;
    orbGroup.scale.setScalar(1+Math.sin(t*1.9)*ORB_C.pulseAmp);
    orbUniforms.uTime.value=t;orbUniforms.uWaveAmp.value=ORB_C.waveAmp;
    orbUniforms.uWaveFreq.value=ORB_C.waveFreq;orbUniforms.uOpacity.value=ORB_C.opacity;
    orbUniforms.uColor.value.setRGB(ORB_C.r,ORB_C.g,ORB_C.b);
    if(mNeb?.uniforms)mNeb.uniforms.uOpacity.value=ORB_C.opacity*.4;
    if(mR1?.uniforms)mR1.uniforms.uOpacity.value=ORB_C.opacity*.85;
    if(mR2?.uniforms)mR2.uniforms.uOpacity.value=ORB_C.opacity*.35;
    orbRenderer.render(orbScene,orbCamera);
  }
  animate();
  new ResizeObserver(()=>{
    const w=canvas.parentElement.clientWidth||420,h=canvas.parentElement.clientHeight||420;
    orbCamera.aspect=w/h;orbCamera.updateProjectionMatrix();orbRenderer.setSize(w,h);
  }).observe(canvas.parentElement);
}

document.querySelectorAll('.orb-cap').forEach(cap => {
  cap.addEventListener('click', () => {
    document.querySelectorAll('.orb-cap').forEach(c=>c.classList.remove('active'));
    cap.classList.add('active');
    setOrb(cap.dataset.state);
    clearInterval(autoTimer); autoTimer=null;
    setTimeout(startAutoCycle, 10000);
  });
});
const AUTO_STATES = ['idle','thinking','workflow','coding','document','memory','research','security'];
let autoCycleIdx=0, autoTimer=null;
function startAutoCycle() {
  autoTimer = setInterval(()=>{
    autoCycleIdx=(autoCycleIdx+1)%AUTO_STATES.length;
    const st=AUTO_STATES[autoCycleIdx];
    setOrb(st);
    document.querySelectorAll('.orb-cap').forEach(c=>c.classList.toggle('active',c.dataset.state===st));
  }, 3500);
}

// ── ACCORDION ─────────────────────────────────────────────────
function toggleAcc(header) {
  const item = header.parentElement;
  const wasOpen = item.classList.contains('open');
  // Close siblings in same list
  const list = item.parentElement;
  list.querySelectorAll('.acc-item.open').forEach(i => {
    if (i !== item) i.classList.remove('open');
  });
  item.classList.toggle('open', !wasOpen);
  // Animate bar fills on open
  if (!wasOpen) {
    setTimeout(() => {
      item.querySelectorAll('.acc-sec-bar-fill').forEach(f => {
        const w = f.style.width;
        f.style.width = '0';
        requestAnimationFrame(() => { f.style.transition = 'width 1.2s cubic-bezier(.4,0,.2,1)'; f.style.width = w; });
      });
    }, 50);
  }
}

// ── WORKFLOW ENGINE ────────────────────────────────────────────
const WF_NODE_DEFS = {
  triggers:{label:'Triggers',color:'#1C4A8A',nodes:[
    {id:'cron',    label:'Cron',         icon:'⏱',fields:[{id:'expr',label:'Expression cron',type:'text',default:'0 9 * * *'}]},
    {id:'webhook', label:'Webhook',       icon:'🔗',fields:[{id:'path',label:'Endpoint',type:'text',default:'/hook/nexus'}]},
    {id:'email',   label:'Email IMAP',    icon:'📧',fields:[{id:'folder',label:'Dossier',type:'text',default:'INBOX'}]},
    {id:'manual',  label:'Manuel',        icon:'▶',fields:[]},
  ]},
  actions:{label:'Actions',color:'#0F6E56',nodes:[
    {id:'agent',   label:'Agent NEXUS',   icon:'◈',fields:[{id:'agent',label:'Agent',type:'select',options:['SYNERGY','GHOST','FORGE','ATLAS','PROCURE','SCRIBE','TERMINUS','HERALD'],default:'SYNERGY'},{id:'prompt',label:'Prompt',type:'textarea',default:'Analyse et agis.'}]},
    {id:'shell',   label:'Terminal',      icon:'$', fields:[{id:'cmd',label:'Commande',type:'text',default:'echo "nexus"'}]},
    {id:'http',    label:'Requête HTTP',  icon:'🌐',fields:[{id:'url',label:'URL',type:'text',default:'https://...'}]},
    {id:'notif',   label:'Notification',  icon:'🔔',fields:[{id:'title',label:'Titre',type:'text',default:'NEXUS'}]},
    {id:'template',label:'Template',      icon:'📄',fields:[{id:'tpl',label:'Template',type:'textarea',default:'Rapport {{date}}:\n{{content}}'}]},
  ]},
  logic:{label:'Logique',color:'#854F0B',nodes:[
    {id:'if',   label:'Si/Sinon', icon:'◆',fields:[{id:'cond',label:'Condition',type:'text',default:'{{result}} != ""'}]},
    {id:'loop', label:'Boucle',   icon:'↻',fields:[{id:'list',label:'Liste (var)',type:'text',default:'{{items}}'}]},
    {id:'delay',label:'Délai',    icon:'⏸',fields:[{id:'ms',label:'Durée (ms)',type:'text',default:'1000'}]},
  ]},
  error:{label:'Erreurs',color:'#A32D2D',nodes:[
    {id:'heal', label:'Self-Heal',  icon:'🔧',fields:[{id:'agent',label:'Agent correcteur',type:'select',options:['GHOST','ATLAS','FORGE'],default:'GHOST'}]},
    {id:'retry',label:'Réessayer', icon:'↺', fields:[{id:'max',label:'Tentatives max',type:'text',default:'3'}]},
  ]}
};

let wfNodes=[], wfEdges=[], wfSelId=null;
let wfScale=1, wfPan={x:20,y:20};
let wfDragging=null, wfDragOff={x:0,y:0};
let wfConnecting=null, wfConnStart=null;
let wfNodeCtr=0;
const WF_NS='http://www.w3.org/2000/svg';

function wfGetDef(cat,id){ return WF_NODE_DEFS[cat]?.nodes.find(n=>n.id===id); }
function wfGetColor(cat){ return WF_NODE_DEFS[cat]?.color||'#666'; }
function wfGetLabel(node){ return wfGetDef(node.cat,node.type)?.label||node.type; }
function wfGetIcon(node){ return wfGetDef(node.cat,node.type)?.icon||'○'; }

function wfBuildPalette() {
  const pal=document.getElementById('wf-palette'); if(!pal) return;
  pal.innerHTML='<div class="wf-pal-hd">Palette de nœuds</div>';
  for(const [cat,def] of Object.entries(WF_NODE_DEFS)){
    const sec=document.createElement('div');
    sec.style.cssText='border-bottom:1px solid var(--border)';
    const hd=document.createElement('div');
    hd.className='wf-pal-sec-hd';
    hd.style.color=def.color;
    hd.innerHTML=def.label+'<span style="font-size:8px;color:var(--text3)">▾</span>';
    const body=document.createElement('div');
    body.className='wf-pal-body';
    for(const nd of def.nodes){
      const pill=document.createElement('div');
      pill.className='wf-pill';
      pill.draggable=true;
      pill.dataset.cat=cat; pill.dataset.nid=nd.id;
      pill.innerHTML=`<span class="wf-pill-dot" style="background:${def.color}"></span>${nd.label}<span style="font-size:9px;opacity:.5;margin-left:auto">${nd.icon}</span>`;
      pill.addEventListener('dragstart',e=>{e.dataTransfer.setData('wf-cat',cat);e.dataTransfer.setData('wf-nid',nd.id);});
      pill.addEventListener('dblclick',()=>wfAddNode(cat,nd.id,80+Math.random()*200,60+Math.random()*100));
      body.appendChild(pill);
    }
    hd.addEventListener('click',()=>{body.style.display=body.style.display==='none'?'':'none';});
    sec.appendChild(hd); sec.appendChild(body);
    pal.appendChild(sec);
  }
}

function wfSvgPt(cx,cy){
  const svg=document.getElementById('wf-svg');
  const rect=svg.getBoundingClientRect();
  return{x:(cx-rect.left)/wfScale-wfPan.x,y:(cy-rect.top)/wfScale-wfPan.y};
}
function wfApplyTransform(){
  const nl=document.getElementById('wf-nodes-layer'),el=document.getElementById('wf-edges-layer');
  if(!nl||!el)return;
  const t=`scale(${wfScale}) translate(${wfPan.x},${wfPan.y})`;
  nl.setAttribute('transform',t); el.setAttribute('transform',t);
}
function wfZoom(d){ wfScale=Math.max(0.3,Math.min(2.5,wfScale+d)); wfApplyTransform(); }
function wfReset(){wfScale=1;wfPan={x:20,y:20};wfApplyTransform();}
function wfUpdateCounts(){
  const nc=document.getElementById('wf-nc'),ec=document.getElementById('wf-ec');
  if(nc)nc.textContent=wfNodes.length+' nœud'+(wfNodes.length!==1?'s':'');
  if(ec)ec.textContent=wfEdges.length+' lien'+(wfEdges.length!==1?'s':'');
}

function wfRenderNode(g,node){
  g.innerHTML='';
  const col=wfGetColor(node.cat);
  const configLbl=node.config?.label||wfGetLabel(node);
  const w=160,h=50,x=node.x,y=node.y;
  const rect=document.createElementNS(WF_NS,'rect');
  rect.setAttribute('x',x);rect.setAttribute('y',y);
  rect.setAttribute('width',w);rect.setAttribute('height',h);
  rect.setAttribute('rx',4);rect.setAttribute('fill','var(--surface)');
  rect.setAttribute('stroke',wfSelId===node.id?col:'var(--border2)');
  rect.setAttribute('stroke-width',wfSelId===node.id?'2':'1');
  g.appendChild(rect);
  const acc=document.createElementNS(WF_NS,'rect');
  acc.setAttribute('x',x);acc.setAttribute('y',y);
  acc.setAttribute('width',4);acc.setAttribute('height',h);
  acc.setAttribute('rx',3);acc.setAttribute('fill',col);
  g.appendChild(acc);
  const txt=document.createElementNS(WF_NS,'text');
  txt.setAttribute('x',x+14);txt.setAttribute('y',y+18);
  txt.setAttribute('font-size','11');txt.setAttribute('font-weight','600');
  txt.setAttribute('fill','var(--text)');txt.setAttribute('dominant-baseline','central');
  txt.textContent=configLbl.length>18?configLbl.slice(0,17)+'…':configLbl;
  g.appendChild(txt);
  const sub=document.createElementNS(WF_NS,'text');
  sub.setAttribute('x',x+14);sub.setAttribute('y',y+35);
  sub.setAttribute('font-size','9');sub.setAttribute('fill','var(--text3)');
  sub.setAttribute('dominant-baseline','central');
  sub.textContent=wfGetIcon(node)+' '+node.cat;
  g.appendChild(sub);
  const portIn=document.createElementNS(WF_NS,'circle');
  portIn.setAttribute('cx',x);portIn.setAttribute('cy',y+h/2);portIn.setAttribute('r','4.5');
  portIn.setAttribute('fill','var(--surface)');portIn.setAttribute('stroke',col);portIn.setAttribute('stroke-width','1.5');
  portIn.style.cursor='crosshair'; g.appendChild(portIn);
  const portOut=document.createElementNS(WF_NS,'circle');
  portOut.setAttribute('cx',x+w);portOut.setAttribute('cy',y+h/2);portOut.setAttribute('r','4.5');
  portOut.setAttribute('fill',col);portOut.setAttribute('stroke','var(--surface)');portOut.setAttribute('stroke-width','1.5');
  portOut.style.cursor='crosshair';
  portOut.addEventListener('mousedown',e=>{e.stopPropagation();wfStartConnect(e,node.id);});
  g.appendChild(portOut);
  if(node.status){
    const sdot=document.createElementNS(WF_NS,'circle');
    sdot.setAttribute('cx',x+w-7);sdot.setAttribute('cy',y+7);sdot.setAttribute('r','5');
    const scols={ok:'var(--success-light)',fail:'var(--danger-light)',running:'var(--gold)',heal:'#7C5ABE'};
    sdot.setAttribute('fill',scols[node.status]||'gray');
    g.appendChild(sdot);
  }
}

function wfCreateNodeEl(node){
  const nl=document.getElementById('wf-nodes-layer'); if(!nl)return;
  const g=document.createElementNS(WF_NS,'g');
  g.id='wfn-'+node.id; g.dataset.nid=node.id; g.style.cursor='pointer';
  wfRenderNode(g,node);
  g.addEventListener('mousedown',e=>{if(e.shiftKey)wfStartConnect(e,node.id);else wfStartDrag(e,node.id);});
  g.addEventListener('click',e=>{if(!e.shiftKey)wfSelectNode(node.id);});
  nl.appendChild(g);
}
function wfRedrawNode(id){
  const node=wfNodes.find(n=>n.id===id),g=document.getElementById('wfn-'+id);
  if(node&&g)wfRenderNode(g,node);
}
function wfAddNode(cat,type,x,y){
  const id='wn'+(++wfNodeCtr);
  const def=wfGetDef(cat,type);
  const config={label:def?.label||type};
  if(def?.fields)for(const f of def.fields)config[f.id]=f.default||'';
  const node={id,cat,type,x,y,config,status:null};
  wfNodes.push(node); wfCreateNodeEl(node); wfUpdateCounts(); wfSelectNode(id);
  return node;
}
function wfDeleteNode(){
  if(!wfSelId)return;
  wfNodes=wfNodes.filter(n=>n.id!==wfSelId);
  wfEdges=wfEdges.filter(e=>e.from!==wfSelId&&e.to!==wfSelId);
  const g=document.getElementById('wfn-'+wfSelId); if(g)g.remove();
  wfSelId=null; wfRedrawAllEdges(); wfShowInspEmpty(); wfUpdateCounts();
}
function wfDuplicateNode(){
  const node=wfNodes.find(n=>n.id===wfSelId); if(!node)return;
  wfAddNode(node.cat,node.type,node.x+24,node.y+24);
}
function wfClearAll(){
  wfNodes=[]; wfEdges=[];
  const nl=document.getElementById('wf-nodes-layer'),el=document.getElementById('wf-edges-layer');
  if(nl)nl.innerHTML=''; if(el)el.innerHTML='';
  wfSelId=null; wfShowInspEmpty(); wfUpdateCounts();
}
function wfSelectNode(id){
  const prev=wfSelId; wfSelId=id;
  if(prev)wfRedrawNode(prev);
  const node=wfNodes.find(n=>n.id===id);
  if(!node){wfShowInspEmpty();return;}
  wfRedrawNode(id); wfShowInspector(node);
}
function wfShowInspEmpty(){
  const e=document.getElementById('wf-insp-empty'),c=document.getElementById('wf-insp-content');
  if(e)e.style.display='flex'; if(c)c.style.display='none';
}
function wfShowInspector(node){
  const e=document.getElementById('wf-insp-empty'),c=document.getElementById('wf-insp-content');
  if(e)e.style.display='none'; if(c)c.style.display='flex';
  const dot=document.getElementById('wf-insp-dot'),title=document.getElementById('wf-insp-title'),type=document.getElementById('wf-insp-type'),body=document.getElementById('wf-insp-body');
  if(dot)dot.style.background=wfGetColor(node.cat);
  if(title)title.textContent=node.config?.label||wfGetLabel(node);
  if(type)type.textContent=node.cat+' · '+node.type;
  if(!body)return;
  body.innerHTML='';
  const addField=(lbl,id,val,ft,opts)=>{
    const fd=document.createElement('div');
    fd.className='wf-field';
    let inp='';
    if(ft==='select'){
      inp=`<select class="wf-field select" onchange="wfUpdateConfig('${node.id}','${id}',this.value)">`;
      for(const o of opts)inp+=`<option${o===val?' selected':''}>${o}</option>`;
      inp+='</select>';
    }else if(ft==='textarea'){
      inp=`<textarea oninput="wfUpdateConfig('${node.id}','${id}',this.value)" rows="3">${val}</textarea>`;
    }else{
      inp=`<input value="${String(val).replace(/"/g,'&quot;')}" oninput="wfUpdateConfig('${node.id}','${id}',this.value)">`;
    }
    fd.innerHTML=`<label>${lbl}</label>${inp}`;
    body.appendChild(fd);
  };
  addField('Label','label',node.config.label||'','text',[]);
  const def=wfGetDef(node.cat,node.type);
  if(def?.fields)for(const f of def.fields)addField(f.label,f.id,node.config[f.id]||f.default||'',f.type||'text',f.options||[]);
}
function wfUpdateConfig(id,key,value){
  const node=wfNodes.find(n=>n.id===id); if(!node)return;
  node.config[key]=value; wfRedrawNode(id);
  if(key==='label'){const t=document.getElementById('wf-insp-title');if(t)t.textContent=value||wfGetLabel(node);}
}

function wfStartDrag(e,id){
  e.stopPropagation();
  const node=wfNodes.find(n=>n.id===id); if(!node)return;
  const pt=wfSvgPt(e.clientX,e.clientY);
  wfDragOff={x:pt.x-node.x,y:pt.y-node.y}; wfDragging=id;
  document.addEventListener('mousemove',wfOnDrag); document.addEventListener('mouseup',wfStopDrag);
}
function wfOnDrag(e){
  if(!wfDragging)return;
  const pt=wfSvgPt(e.clientX,e.clientY);
  const node=wfNodes.find(n=>n.id===wfDragging); if(!node)return;
  node.x=pt.x-wfDragOff.x; node.y=pt.y-wfDragOff.y;
  wfRedrawNode(wfDragging); wfRedrawAllEdges();
}
function wfStopDrag(){wfDragging=null;document.removeEventListener('mousemove',wfOnDrag);document.removeEventListener('mouseup',wfStopDrag);}

function wfStartConnect(e,fromId){
  e.stopPropagation();
  wfConnecting=fromId;
  const node=wfNodes.find(n=>n.id===fromId);
  wfConnStart={x:node.x+160,y:node.y+25};
  document.addEventListener('mousemove',wfOnConnect); document.addEventListener('mouseup',wfStopConnect);
}
function wfOnConnect(e){
  if(!wfConnecting)return;
  const pt=wfSvgPt(e.clientX,e.clientY);
  const de=document.getElementById('wf-draw-edge');
  const cx1=wfConnStart.x+60,cx2=pt.x-60;
  if(de)de.setAttribute('d',`M${wfConnStart.x},${wfConnStart.y} C${cx1},${wfConnStart.y} ${cx2},${pt.y} ${pt.x},${pt.y}`);
}
function wfStopConnect(e){
  const de=document.getElementById('wf-draw-edge'); if(de)de.setAttribute('d','');
  if(wfConnecting){
    const el=document.elementFromPoint(e.clientX,e.clientY);
    const toG=el?.closest('g[data-nid]');
    if(toG){const toId=toG.dataset.nid;if(toId&&toId!==wfConnecting&&!wfEdges.find(ed=>ed.from===wfConnecting&&ed.to===toId)){wfEdges.push({from:wfConnecting,to:toId});wfRedrawAllEdges();wfUpdateCounts();}}
  }
  wfConnecting=null; wfConnStart=null;
  document.removeEventListener('mousemove',wfOnConnect); document.removeEventListener('mouseup',wfStopConnect);
}

function wfDrawEdge(ed){
  const el=document.getElementById('wf-edges-layer'); if(!el)return;
  const fn=wfNodes.find(n=>n.id===ed.from),tn=wfNodes.find(n=>n.id===ed.to);
  if(!fn||!tn)return;
  const x1=fn.x+160,y1=fn.y+25,x2=tn.x,y2=tn.y+25;
  const path=document.createElementNS(WF_NS,'path');
  path.setAttribute('d',`M${x1},${y1} C${x1+60},${y1} ${x2-60},${y2} ${x2},${y2}`);
  path.setAttribute('stroke','var(--text3)');path.setAttribute('stroke-width','1.5');
  path.setAttribute('fill','none');path.setAttribute('opacity','0.5');
  path.setAttribute('marker-end','url(#wf-arr)');
  path.style.cursor='pointer';
  path.addEventListener('dblclick',()=>{wfEdges=wfEdges.filter(e=>!(e.from===ed.from&&e.to===ed.to));wfRedrawAllEdges();wfUpdateCounts();});
  el.appendChild(path);
}
function wfRedrawAllEdges(){const el=document.getElementById('wf-edges-layer');if(el)el.innerHTML='';for(const ed of wfEdges)wfDrawEdge(ed);}

function wfInitCanvas(){
  const svg=document.getElementById('wf-svg'); if(!svg)return;
  svg.addEventListener('dragover',e=>e.preventDefault());
  svg.addEventListener('drop',e=>{
    e.preventDefault();
    const cat=e.dataTransfer.getData('wf-cat'),nid=e.dataTransfer.getData('wf-nid');
    if(!cat||!nid)return;
    const pt=wfSvgPt(e.clientX,e.clientY);
    wfAddNode(cat,nid,pt.x-80,pt.y-25);
  });
  svg.addEventListener('click',e=>{
    if(e.target===svg||e.target.id==='wf-grid-bg'){
      wfSelId=null;wfShowInspEmpty();
      document.querySelectorAll('#wf-nodes-layer g').forEach(g=>{const node=wfNodes.find(n=>n.id===g.dataset.nid);if(node)wfRenderNode(g,node);});
    }
  });
  let isPanning=false,panStart={x:0,y:0},panOrigin={x:0,y:0};
  svg.addEventListener('mousedown',e=>{if(e.button===1||(e.button===0&&e.target===svg)){isPanning=true;panStart={x:e.clientX,y:e.clientY};panOrigin={...wfPan};svg.style.cursor='grabbing';}});
  document.addEventListener('mousemove',e=>{if(!isPanning)return;wfPan.x=panOrigin.x+(e.clientX-panStart.x)/wfScale;wfPan.y=panOrigin.y+(e.clientY-panStart.y)/wfScale;wfApplyTransform();});
  document.addEventListener('mouseup',()=>{isPanning=false;if(svg)svg.style.cursor='';});
  svg.addEventListener('wheel',e=>{e.preventDefault();wfZoom(e.deltaY<0?0.1:-0.1);},{passive:false});
}

function wfTopoSort(){
  const visited={},order=[];
  function visit(id){if(visited[id])return;visited[id]=true;for(const e of wfEdges)if(e.from===id)visit(e.to);order.unshift(id);}
  for(const n of wfNodes)visit(n.id);
  return order;
}

function wfRunWorkflow(){
  if(wfNodes.length===0)return;
  const log=document.getElementById('wf-run-log');
  if(log){log.style.display='block';log.innerHTML='';}
  const ordered=wfTopoSort();
  let delay=0;
  for(const id of ordered){
    const node=wfNodes.find(n=>n.id===id);if(!node)continue;
    const lbl=node.config?.label||wfGetLabel(node);
    setTimeout(()=>{
      node.status='running';wfRedrawNode(id);
      if(log){const l=document.createElement('div');l.style.lineHeight='1.8';l.innerHTML=`<span style="color:var(--text3)">${new Date().toLocaleTimeString()}</span> <span style="color:var(--gold)">▷</span> ${lbl}…`;log.appendChild(l);log.scrollTop=log.scrollHeight;}
    },delay);
    delay+=700+Math.random()*300;
    setTimeout(()=>{
      const ok=Math.random()>0.12;
      node.status=ok?'ok':'heal';
      if(!ok)setTimeout(()=>{node.status='ok';wfRedrawNode(id);},800);
      wfRedrawNode(id);
      if(log){const l=document.createElement('div');l.style.lineHeight='1.8';l.innerHTML=`<span style="color:var(--text3)">${new Date().toLocaleTimeString()}</span> <span style="color:${ok?'var(--success-light)':'#7C5ABE'}">${ok?'✓':'🔧'} ${lbl} ${ok?'— OK':'— Self-heal…'}</span>`;log.appendChild(l);log.scrollTop=log.scrollHeight;}
    },delay);
    delay+=200;
  }
  setTimeout(()=>{if(log){const l=document.createElement('div');l.innerHTML=`<span style="color:var(--text3)">${new Date().toLocaleTimeString()}</span> <span style="color:var(--success-light)">━ Workflow terminé (${wfNodes.length} nœuds)</span>`;log.appendChild(l);}},delay+200);
}

function wfLoadDefault(){
  wfClearAll();
  const t=wfAddNode('triggers','cron',30,80);
  const a=wfAddNode('actions','agent',220,80);
  const l=wfAddNode('logic','if',410,80);
  const ok=wfAddNode('actions','notif',600,30);
  const err=wfAddNode('error','heal',600,130);
  wfEdges.push({from:t.id,to:a.id},{from:a.id,to:l.id},{from:l.id,to:ok.id},{from:l.id,to:err.id});
  wfRedrawAllEdges(); wfUpdateCounts(); wfSelId=null; wfShowInspEmpty();
}

// ── AGENTS GRID ────────────────────────────────────────────────
const AGENTS = [
  {name:'SYNERGY', role:'Orchestrateur · Routage intent',    model:'mistral:7b',    detail:'Analyse l\'intention de chaque requête et la délègue aux agents spécialisés via le Neural Bus. Point d\'entrée de toutes les interactions.'},
  {name:'ATLAS',   role:'Planification · DAG exécution',      model:'llama3:8b',     detail:'Génère les plans d\'exécution en graphes acycliques dirigés. Identifie les branches parallélisables et optimise la durée totale de chaque tâche.'},
  {name:'GHOST',   role:'Génération de code · 14B coder',     model:'qwen2.5-coder:14b', detail:'Lit l\'AST complet de votre codebase, génère des patches contextuels et itère sur les erreurs de tests. Auto-retry 3x sur échec.'},
  {name:'FORGE',   role:'Gestionnaire de fichiers · Patch',   model:'—',             detail:'Applique les fichiers et patches atomiquement avec snapshot de rollback. Garantit l\'intégrité même en cas d\'interruption.'},
  {name:'PROCURE', role:'Web crawl · APIs · Email',           model:'mistral:7b',    detail:'Récupère emails (IMAP OAuth), crawle des sources web, extrait des PDFs et interroge des APIs REST. Jusqu\'à 100 sources simultanées.'},
  {name:'SCRIBE',  role:'Rédaction · Word · PDF',             model:'mistral:7b',    detail:'Génère des documents Word, PDF et présentations depuis vos templates. Intègre les données LIBRARIAN pour enrichir chaque document du contexte client.'},
  {name:'LIBRARIAN',role:'Mémoire sémantique · RAG',          model:'BGE-M3',        detail:'Vector store ChromaDB persistant. Indexe chaque action et document. Recherche hybride dense+BM25 en <30ms. Mémoire permanente entre sessions.'},
  {name:'HERALD',  role:'Notifications · TTS vocal',          model:'TTS local',     detail:'Envoie des notifications desktop, email et SMS. Génère des briefings vocaux quotidiens. Surveille votre boîte et alerte proactivement.'},
  {name:'SENTINEL',role:'Sécurité · Autorité L0–L5',          model:'Arbre décision',detail:'Classifie chaque action en L0–L5 en <1ms. Processus isolé, auto-protégé. Audit log SHA-256 immuable. Non-contournable par les autres agents.'},
  {name:'OCULUS',  role:'Vision écran · OCR figures',         model:'moondream2',    detail:'Vision locale pour capturer et analyser l\'écran, détecter des éléments UI, OCR des figures et graphiques, et contrôler la souris/clavier.'},
  {name:'CIPHER',  role:'Chiffrement · AES-256',              model:'—',             detail:'Chiffre automatiquement les documents sensibles en AES-256 au repos. Gère les clés avec dérivation PBKDF2. Déchiffrement transparent à l\'accès.'},
  {name:'CHRONOS', role:'Planificateur · Tâches récurrentes', model:'—',             detail:'Gère les déclencheurs cron et les rappels temporels. Surveille les délais procéduraux. Orchestre les workflows planifiés avec précision à la seconde.'},
  {name:'TERMINUS',role:'Tests · Exécution terminal',         model:'—',             detail:'Exécute votre suite de tests (pytest, jest, etc.) après chaque patch GHOST. En cas d\'échec, retourne le traceback complet pour auto-correction.'},
  {name:'ALCHEMIST',role:'Distillation · Auto-amélioration', model:'—',             detail:'Analyse les patterns d\'usage et distille des modèles optimisés pour votre domaine. Le système devient plus précis à chaque semaine d\'utilisation.'},
  {name:'VISIONARY',role:'Routage LLM · VRAM optim.',         model:'—',             detail:'Gère dynamiquement la charge des modèles selon la VRAM disponible. Charge à la demande, décharge après inactivité. Optimal sur 6–24GB GPU.'},
  {name:'TACTICIAN',role:'Surveillance ressources système',  model:'—',             detail:'Monitore CPU, RAM, VRAM et températures en temps réel. Throttle automatiquement les agents si les ressources sont sous pression.'},
  {name:'COURIER', role:'Voix → Texte · TTS · Audio',         model:'Whisper',       detail:'Transcrit votre voix en <200ms via Whisper local. Génère des briefings TTS naturels. Calibré sur votre vocabulaire métier.'},
];

function buildAgents(){
  const grid=document.getElementById('agents-grid'); if(!grid)return;
  grid.innerHTML='';
  AGENTS.forEach((a,i)=>{
    const card=document.createElement('div');
    card.className='agent-card';
    card.style.animationDelay=(i*0.04)+'s';
    card.innerHTML=`
      <div class="agent-status"></div>
      <div class="agent-name">${a.name}</div>
      <div class="agent-role">${a.role}</div>
      <div class="agent-detail">${a.detail}<div class="agent-model">Model: ${a.model}</div></div>`;
    card.addEventListener('click',()=>{
      const wasExp=card.classList.contains('expanded');
      document.querySelectorAll('.agent-card.expanded').forEach(c=>c.classList.remove('expanded'));
      if(!wasExp)card.classList.add('expanded');
    });
    grid.appendChild(card);
  });
}

// ── AUDIENCE TOGGLE ────────────────────────────────────────────
function switchAud(id,btn){
  document.querySelectorAll('.aud-btn').forEach(b=>b.classList.remove('on'));
  btn.classList.add('on');
  document.querySelectorAll('.aud-panel').forEach(p=>p.classList.remove('on'));
  document.getElementById('panel-'+id).classList.add('on');
  document.getElementById('aud-desc').textContent=id==='biz'?'Ce que NEXUS fait pour votre travail quotidien':'Architecture technique et détails d\'implémentation';
}

// ── CAPABILITY TABS ─────────────────────────────────────────────
function switchCap(id,btn){
  document.querySelectorAll('.cap-tab').forEach(b=>b.classList.remove('on'));
  btn.classList.add('on');
  document.querySelectorAll('.cap-panel').forEach(p=>p.classList.remove('on'));
  document.getElementById('cap-'+id).classList.add('on');
  const stateMap={email:'research',code:'coding',doc:'document',research:'research',screen:'thinking'};
  setOrb(stateMap[id]||'thinking');
}

// ── TERMINAL ────────────────────────────────────────────────────
const TERMINAL_LINES = [
  {html:'<span class="t-prompt">NEXUS:~$</span> <span class="t-cmd">nexus run "Analyse my emails and generate a priority report"</span>',delay:0},
  {html:'<span class="t-dim">Routing intent via SYNERGY...</span>',delay:400},
  {html:'<span class="t-agent">[SYNERGY]</span> <span class="t-info">→ complexity: high → delegating to ATLAS</span>',delay:900},
  {html:'<span class="t-agent">[ATLAS]</span> <span class="t-info">DAG plan generated in 380ms → 4 steps, 2 parallel</span>',delay:1400},
  {html:'<span class="t-dim">  step 1: PROCURE.fetch_emails(unread=true, limit=30)</span>',delay:1800},
  {html:'<span class="t-dim">  step 2: LIBRARIAN.recall(context="email priorities")</span>',delay:2100},
  {html:'<span class="t-dim">  step 3: ATLAS.synthesize(emails, memories)</span>',delay:2400},
  {html:'<span class="t-dim">  step 4: SCRIBE.build_report("priority_inbox.docx")</span>',delay:2700},
  {html:'<span class="t-agent">[PROCURE]</span> <span class="t-ok">✓</span> <span class="t-info">Fetched 24 emails · TF-IDF priority scoring applied</span>',delay:3300},
  {html:'<span class="t-agent">[SENTINEL]</span> <span class="t-ok">L1 auto-approved</span> — read-only, no escalation',delay:3700},
  {html:'<span class="t-agent">[LIBRARIAN]</span> <span class="t-ok">✓</span> <span class="t-info">5 relevant memories recalled · BGE-M3 · 24ms</span>',delay:4100},
  {html:'<span class="t-agent">[ATLAS]</span> <span class="t-ok">✓</span> Synthesis: 4 urgent · 12 normal · 8 low · 3 ignored',delay:4700},
  {html:'<span class="t-agent">[SCRIBE]</span> <span class="t-ok">✓</span> <span class="t-info">priority_inbox.docx → 6 pages · response drafts included</span>',delay:5200},
  {html:'<span class="t-agent">[HERALD]</span> <span class="t-ok">✓</span> Voice notification → "4 urgent emails require attention"',delay:5700},
  {html:'<span class="t-agent">[SYNERGY]</span> <span class="t-ok">✓</span> Task complete in 6.8s — <span class="t-info">zero cloud · zero token billing</span>',delay:6200},
  {html:'<span class="t-prompt">NEXUS:~$</span> <span class="t-cursor"></span>',delay:6800},
];
function runTerminal(){
  const body=document.getElementById('terminal-body'); if(!body)return;
  body.innerHTML='';
  TERMINAL_LINES.forEach(l=>{
    const div=document.createElement('div');
    div.className='terminal-line'; div.innerHTML=l.html;
    body.appendChild(div);
    setTimeout(()=>{div.classList.add('show');body.scrollTop=body.scrollHeight;},l.delay);
  });
  setTimeout(runTerminal,10000);
}

// ── SCROLL REVEAL ────────────────────────────────────────────────
const revealObs=new IntersectionObserver(entries=>{
  entries.forEach(e=>{
    if(e.isIntersecting){
      e.target.classList.add('vis');
      if(e.target.closest('#terminal-demo')&&e.target.classList.contains('terminal-wrap')){
        runTerminal();revealObs.unobserve(e.target);
      }
    }
  });
},{threshold:0.08});
document.querySelectorAll('.reveal').forEach(el=>revealObs.observe(el));

// ── WAITLIST ────────────────────────────────────────────────────
let wlCount = 312+Math.floor(Math.random()*50);
document.getElementById('wl-count').textContent=wlCount.toLocaleString();
setInterval(()=>{if(Math.random()>0.6){wlCount++;document.getElementById('wl-count').textContent=wlCount.toLocaleString();}},8000);

function submitWaitlist(){
  const fname=document.getElementById('wl-fname').value.trim();
  const lname=document.getElementById('wl-lname').value.trim();
  const email=document.getElementById('wl-email').value.trim();
  const role=document.getElementById('wl-role').value;
  const size=document.getElementById('wl-size').value;
  const use=document.getElementById('wl-use').value.trim();
  const consent=document.getElementById('wl-consent').checked;
  if(!fname){shake('wl-fname');return;}
  if(!email||!email.includes('@')){shake('wl-email');return;}
  if(!role){shake('wl-role');return;}
  if(!consent){shake('wl-consent');return;}
  const btn=document.getElementById('wl-submit');
  btn.disabled=true;btn.textContent='Sécurisation de votre place…';
  const subject=encodeURIComponent('NEXUS Waitlist — '+fname+' '+lname);
  const body=encodeURIComponent('Prénom: '+fname+'\nNom: '+lname+'\nEmail: '+email+'\nRôle: '+role+'\nTaille: '+size+'\nCas d\'usage: '+(use||'(non précisé)')+'\n\nTimestamp: '+new Date().toISOString());
  setTimeout(()=>{
    window.open('mailto:arthurdecamps07@gmail.com?subject='+subject+'&body='+body,'_blank');
    document.getElementById('waitlist-form-container').style.display='none';
    document.getElementById('success-box').classList.add('show');
    wlCount++;document.getElementById('wl-count').textContent=wlCount.toLocaleString();
  },1100);
}
function shake(id){
  const el=document.getElementById(id);if(!el)return;
  el.style.animation='none';el.offsetHeight;
  el.style.animation='shakeX 0.4s ease';el.style.borderColor='var(--danger)';
  setTimeout(()=>{el.style.borderColor='';el.style.animation='';},1000);
}
const ss=document.createElement('style');
ss.textContent='@keyframes shakeX{0%,100%{transform:translateX(0)}20%,60%{transform:translateX(-6px)}40%,80%{transform:translateX(6px)}}';
document.head.appendChild(ss);

// ── NAV SCROLL SHADOW ──────────────────────────────────────────
window.addEventListener('scroll',()=>{
  document.getElementById('nav').classList.toggle('scrolled', window.scrollY > 10);
},{ passive: true });

// ── MOBILE NAV ────────────────────────────────────────────────
function toggleMobileMenu(){
  const menu=document.getElementById('nav-mobile-menu');
  const btn=document.getElementById('nav-hamburger');
  const open=menu.classList.toggle('open');
  btn.classList.toggle('open',open);
}
function closeMobileMenu(){
  document.getElementById('nav-mobile-menu').classList.remove('open');
  document.getElementById('nav-hamburger').classList.remove('open');
}
document.addEventListener('click',e=>{
  const menu=document.getElementById('nav-mobile-menu');
  const btn=document.getElementById('nav-hamburger');
  if(menu.classList.contains('open')&&!menu.contains(e.target)&&!btn.contains(e.target)) closeMobileMenu();
});

// ── INIT ────────────────────────────────────────────────────────
requestAnimationFrame(()=>requestAnimationFrame(()=>{
  buildOrb('orb-canvas-hero');
  setTimeout(()=>{
    const c=document.getElementById('orb-canvas-hero');
    if(c&&orbRenderer){const w=c.parentElement.offsetWidth||420,h=c.parentElement.offsetHeight||420;if(w>0&&h>0){orbCamera.aspect=w/h;orbCamera.updateProjectionMatrix();orbRenderer.setSize(w,h);}}
  },100);
  setTimeout(startAutoCycle,2000);
}));

wfBuildPalette();
wfInitCanvas();
wfApplyTransform();
wfLoadDefault();
buildAgents();
</script>
</body>
</html>
