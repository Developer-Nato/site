<!DOCTYPE html>
<html lang="en" data-theme="dark">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="color-scheme" content="dark">
<script>try{var _s=JSON.parse(localStorage.getItem("meteostorm_settings")||"{}");if(_s.theme==="light"||_s.theme==="dark")document.documentElement.dataset.theme=_s.theme}catch(e){}</script>
<title>METEOSTORM — Live Weather</title>
<style>
:root{--bg:#07090d;--panel:#10141b;--panel2:#171c25;--line:#232a36;--muted:#8791a0;--text:#e9ecf1;--accent:#7db4ff;--accent2:#4f8fe8;--good:#64e7a0;
--bgglow:#101a2b;--hdr:rgba(10,13,18,.72);--card-end:#0d1117;--line2:#1d2430;--shadow:rgba(0,0,0,.35);--hover:#162236;--t1:#fff;--t2:#9fc4ff;--logo-ring:#232a36;--cond:#b6bfcc;--ph:#5f6877;--compass-line:#2c3a4f;--compass-bg:#14213a;--teamspan:#aab3c0;--errc:#ff9b9b}
:root[data-theme="light"]{--bg:#f3f6fb;--panel:#ffffff;--panel2:#eef2f8;--line:#d9e0ea;--muted:#5d6878;--text:#141a24;--accent:#1d63d1;--accent2:#2f74e0;--good:#118a4f;
--bgglow:#dce8fb;--hdr:rgba(255,255,255,.78);--card-end:#f7f9fc;--line2:#e2e8f1;--shadow:rgba(30,50,90,.12);--hover:#e3edfc;--t1:#0b2a5c;--t2:#2f74e0;--logo-ring:#d9e0ea;--cond:#465163;--ph:#8a94a3;--compass-line:#b9cbe6;--compass-bg:#dbe8fb;--teamspan:#4a5565;--errc:#c53030}
*{box-sizing:border-box}
html{color-scheme:dark;scroll-behavior:smooth}
html[data-theme="light"]{color-scheme:light}
body{margin:0;background:radial-gradient(1200px 600px at 50% -10%,var(--bgglow) 0%,var(--bg) 60%) fixed,var(--bg);color:var(--text);font:14px/1.45 Inter,system-ui,Segoe UI,"Noto Sans Myanmar","Noto Sans Thai",sans-serif;min-height:100vh}
button,input{font:inherit}

/* Header: brand left, emblem + search centered, status right */
header{position:sticky;top:0;z-index:50;display:grid;grid-template-columns:1fr auto 1fr;align-items:center;gap:16px;padding:10px 22px;background:var(--hdr);backdrop-filter:blur(16px) saturate(1.3);-webkit-backdrop-filter:blur(16px) saturate(1.3);border-bottom:1px solid var(--line)}
.brandwrap{display:flex;align-items:center;gap:12px;min-width:0}
.brand{font-weight:850;letter-spacing:2px;font-size:18px;color:var(--text)}.brand span{color:var(--accent)}
.sub{color:var(--muted);font-size:11px;letter-spacing:1.4px}
.center{display:flex;align-items:center;gap:14px;justify-content:center}
.brand-logo{width:52px;height:52px;object-fit:contain;border-radius:50%;background:#fff;box-shadow:0 0 0 2px var(--logo-ring),0 0 24px rgba(125,180,255,.25);flex:none}
.search{display:flex;align-items:center;gap:8px}
input{background:var(--panel2);color:var(--text);border:1px solid var(--line);border-radius:10px;padding:10px 14px;width:clamp(180px,26vw,340px);min-width:0;height:44px;outline:none;transition:border-color .2s,box-shadow .2s}
input::placeholder{color:var(--ph)}
input:focus{border-color:var(--accent);box-shadow:0 0 0 3px rgba(125,180,255,.15)}
button{border:1px solid var(--line);background:var(--panel2);color:var(--text);padding:0 18px;height:44px;border-radius:10px;cursor:pointer;font-weight:650;transition:all .2s}
button:hover{border-color:var(--accent);color:var(--accent);background:var(--hover)}
.search button{background:var(--accent2);border-color:var(--accent2);color:#fff;min-width:96px}
.search button:hover{background:#6aa5f5;border-color:#6aa5f5;color:#07090d}
.topright{display:flex;gap:12px;align-items:center;justify-content:flex-end}
.live{color:var(--good);font-size:11px;letter-spacing:1px;white-space:nowrap}
.dot{display:inline-block;width:7px;height:7px;border-radius:50%;background:var(--good);margin-right:6px;box-shadow:0 0 10px var(--good);animation:pulse 2s infinite}
@keyframes pulse{50%{opacity:.35}}
.btn-link{display:inline-flex;align-items:center;justify-content:center;gap:8px;height:44px;padding:0 18px;border:1px solid #ea580c;background:#ea580c;color:#fff;border-radius:10px;font-weight:800;text-decoration:none;white-space:nowrap;transition:all .2s}
.btn-link:hover{border-color:#fb923c;background:#fb923c;color:#1a0f00;box-shadow:0 0 18px rgba(251,146,60,.45)}

/* Content */
main{padding:22px 16px 8px;max-width:1200px;margin:auto}
.grid{display:grid;grid-template-columns:minmax(0,1.1fr) minmax(0,1fr);gap:16px}
.card{background:linear-gradient(180deg,var(--panel),var(--card-end));border:1px solid var(--line);border-radius:16px;padding:20px;box-shadow:0 10px 40px var(--shadow)}
.eyebrow{font-size:10px;letter-spacing:1.6px;color:var(--muted);text-transform:uppercase}
.place{font-size:24px;font-weight:750;margin:6px 0 2px}
.updated{font-size:11px;color:var(--muted)}
.temp{font-size:72px;line-height:1.05;font-weight:750;margin:16px 0 2px;background:linear-gradient(180deg,var(--t1),var(--t2));-webkit-background-clip:text;background-clip:text;color:transparent}
.condition{color:var(--cond);font-size:16px}
.windrow{display:flex;align-items:center;gap:16px;margin-top:20px}
.compass{width:64px;height:64px;border:1px solid var(--compass-line);border-radius:50%;display:grid;place-items:center;color:var(--accent);font-size:28px;background:radial-gradient(circle,var(--compass-bg),transparent 70%);transition:transform .6s cubic-bezier(.2,.8,.2,1)}
.windval{font-size:24px;font-weight:750}.windval small{font-size:12px;color:var(--muted);font-weight:400}
.metrics{display:grid;grid-template-columns:1fr 1fr;gap:10px}
.metric{background:var(--panel2);border:1px solid var(--line2);padding:14px;border-radius:12px}
.metric span{display:block;color:var(--muted);font-size:10px;text-transform:uppercase;letter-spacing:.8px}
.metric strong{font-size:20px;display:block;margin-top:6px}
.forecast-card{grid-column:1/-1}
.hours{display:flex;gap:9px;overflow:auto;padding:12px 0 6px;scrollbar-width:thin;scrollbar-color:#2a3342 transparent}
.hour{min-width:78px;text-align:center;background:var(--panel2);border:1px solid var(--line2);border-radius:12px;padding:12px 6px}
.hour small{color:var(--muted);font-size:10px}.hour b{display:block;margin:8px 0 2px;font-size:16px}.hour em{font-style:normal;color:var(--accent);font-size:10px}
.hour .w{font-size:10px;color:var(--muted);margin-top:5px}
.status{color:var(--muted);font-size:11px;margin-top:10px}.error{color:var(--errc)}
.spacer{height:12vh}
footer{padding:18px 20px 40px;color:var(--muted);font-size:11px;text-align:center}
.team-logos{display:flex;justify-content:center;align-items:center;gap:clamp(12px,3vw,34px);flex-wrap:wrap;padding:10px 12px 18px}
.team-logo{display:flex;flex-direction:column;align-items:center;gap:6px}
.team-logo img{width:clamp(62px,10vw,104px);height:clamp(62px,10vw,104px);object-fit:contain;border-radius:50%;background:#fff;box-shadow:0 0 0 2px var(--logo-ring)}
.team-logo span{font-size:10px;font-weight:800;letter-spacing:1px;color:var(--teamspan)}
.credits{font-size:11px;color:var(--muted)}

/* Scroll reveal (blurred fade-in) */
.reveal{opacity:0;transform:translateY(28px);filter:blur(10px);transition:opacity .7s ease,transform .7s cubic-bezier(.2,.8,.2,1),filter .7s ease}
.reveal.in{opacity:1;transform:none;filter:none}

/* Reports */
.rep-bar{display:flex;justify-content:flex-end;margin-bottom:12px}
.rep-small{height:34px;padding:0 12px;font-size:12px;display:inline-flex;align-items:center;gap:6px}
.rep-small[hidden]{display:none}
.rep-box{background:var(--panel2);border:1px solid var(--line2);border-radius:12px;padding:14px;margin-bottom:14px;display:flex;flex-direction:column;gap:10px}
.rep-box[hidden]{display:none}
.rep-row{display:flex;gap:8px}
.rep-row input{flex:1;width:auto}
textarea{background:var(--panel);color:var(--text);border:1px solid var(--line);border-radius:10px;padding:10px 14px;width:100%;font:inherit;resize:vertical;min-height:84px;outline:none;transition:border-color .2s,box-shadow .2s}
textarea::placeholder{color:var(--ph)}
textarea:focus{border-color:var(--accent);box-shadow:0 0 0 3px rgba(125,180,255,.15)}
.file-btn{display:inline-flex;align-items:center;justify-content:center;height:44px;border:1px dashed var(--line);border-radius:10px;cursor:pointer;font-weight:650;color:var(--accent);background:var(--panel)}
.file-btn:hover{border-color:var(--accent)}
#repPreview{max-width:100%;max-height:220px;border-radius:10px;object-fit:contain;align-self:flex-start}
#repPreview[hidden]{display:none}
.rep-actions{display:flex;gap:8px}
.primary{background:var(--accent2);border-color:var(--accent2);color:#fff}
.primary:hover{background:#6aa5f5;border-color:#6aa5f5;color:#07090d}
.report{border:1px solid var(--line2);background:var(--panel2);border-radius:12px;overflow:hidden;margin-top:12px}
.report img{display:block;width:100%;max-height:420px;object-fit:cover}
.report .body{padding:12px 14px}
.report p{margin:0 0 8px;white-space:pre-wrap;overflow-wrap:anywhere}
.report .meta{display:flex;justify-content:space-between;align-items:center;gap:8px;color:var(--muted);font-size:11px}
.report .del{height:30px;padding:0 10px;font-size:12px}
.report .del.armed{border-color:var(--errc);color:var(--errc)}
/* Radar */
.seg.four{grid-template-columns:repeat(4,1fr);margin-bottom:12px}
.radar-frame{border-radius:12px;overflow:hidden;border:1px solid var(--line2);height:min(60vh,440px);background:var(--panel2)}
.radar-frame iframe{display:block;width:100%;height:100%;border:0}
.map-link{display:inline-block;margin-top:10px;color:var(--accent);font-weight:650;text-decoration:none}
.map-link:hover{text-decoration:underline}
/* Card tabs */
.tabs{display:flex;gap:8px;margin-bottom:16px}
.tab{height:36px;padding:0 16px;border-radius:999px;font-weight:700;font-size:13px}
.tab.on,.tab.on:hover{background:var(--accent2);border-color:var(--accent2);color:#fff}
/* Join modal */
.modal{position:fixed;inset:0;z-index:100;display:grid;place-items:center;padding:16px;background:rgba(0,0,0,.6);-webkit-backdrop-filter:blur(6px);backdrop-filter:blur(6px)}
.modal[hidden]{display:none}
.modal-card{position:relative;width:min(420px,100%);background:var(--panel);border:1px solid var(--line);border-radius:16px;padding:24px 22px 22px;box-shadow:0 24px 70px var(--shadow)}
.modal-title{font-size:18px;font-weight:800;line-height:1.3;padding-right:30px}
.modal-desc{color:var(--cond);margin:10px 0 18px;font-size:14px;line-height:1.55}
.modal-x{position:absolute;top:10px;right:10px;width:34px;height:34px;padding:0;border-radius:50%;font-size:14px}
.modal .btn-link{width:100%}
/* Settings */
.settings-wrap{position:relative}
.icon-btn{width:44px;padding:0;display:grid;place-items:center}
.panel-pop{position:absolute;right:0;top:calc(100% + 10px);width:min(330px,calc(100vw - 24px));background:var(--panel);border:1px solid var(--line);border-radius:14px;padding:16px;box-shadow:0 18px 50px var(--shadow);z-index:60}
.panel-pop[hidden]{display:none}
.set-title{font-weight:750;font-size:15px}
.set-row{margin-top:14px}
.set-label{font-size:10px;letter-spacing:1.4px;color:var(--muted);text-transform:uppercase;margin-bottom:8px}
.seg{display:grid;grid-template-columns:1fr 1fr;gap:4px;background:var(--panel2);border:1px solid var(--line);border-radius:10px;padding:3px}
.seg button,.langs button{height:36px;border:0;border-radius:8px;background:transparent;padding:0 10px;font-weight:600;color:var(--text)}
.langs{display:grid;grid-template-columns:1fr 1fr;gap:6px}
.langs button{border:1px solid var(--line);background:var(--panel2);height:auto;min-height:40px;padding:6px 8px;font-size:13px;line-height:1.2}
.seg button:hover,.langs button:hover{background:var(--hover);color:var(--accent)}
.seg button.on,.langs button.on,.seg button.on:hover,.langs button.on:hover{background:var(--accent2);border-color:var(--accent2);color:#fff}

@media(max-width:900px){.grid{grid-template-columns:1fr}}
@media(max-width:760px){
 header{grid-template-columns:1fr auto;padding:10px 12px;gap:8px}
 .brandwrap{order:1}.topright{order:2}
 .center{order:3;grid-column:1/-1;width:100%}
 .search{flex:1}.search input{width:auto;flex:1}
 .brand-logo{width:46px;height:46px}.sub,.live{display:none}
 .temp{font-size:60px}
}
@media(prefers-reduced-motion:reduce){.reveal{transition:none;opacity:1;transform:none;filter:none}html{scroll-behavior:auto}}
</style>
</head>
<body>
<!-- Vertical-only blur used for scroll motion blur -->
<svg width="0" height="0" style="position:absolute" aria-hidden="true"><defs><filter id="mblur" x="-5%" y="-20%" width="110%" height="140%"><feGaussianBlur id="mblurNode" in="SourceGraphic" stdDeviation="0 0"/></filter></defs></svg>

<header>
 <div class="brandwrap"><span class="brand">METEO<span>STORM</span></span><span class="sub" data-i18n="sub">WEATHER INTELLIGENCE</span></div>
 <div class="center">
  <img class="brand-logo" src="data:image/png;base64,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
