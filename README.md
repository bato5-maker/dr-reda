<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no, viewport-fit=cover">
<meta name="color-scheme" content="light">
<title>&#x631;&#x633;&#x627;&#x626;&#x644; &#x625;&#x644;&#x649; &#x62F;&#x643;&#x62A;&#x648;&#x631;&#x62A;&#x64A;</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Amiri:wght@400;700&family=Playfair+Display:wght@700;900&family=Tajawal:wght@400;500;700&display=swap" rel="stylesheet">
<style>
:root{color-scheme:light;--rose:#8c5e58;--ink:#3A2E30;--gold:#C9A86A;--gold2:#DFC498;--line:#E4D3D0;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
*{box-sizing:border-box;-webkit-tap-highlight-color:transparent;margin:0}
html,body{height:100%}
body{overflow:hidden;font-family:'Tajawal',system-ui,sans-serif;color:var(--ink);background:radial-gradient(circle at 20% 18%,#FDF9F4 0%,#F8EFE8 48%,#F2E3E4 100%);user-select:none;-webkit-user-select:none}
.glow{position:fixed;inset:0;pointer-events:none;overflow:hidden}
.glow i{position:absolute;border-radius:50%;filter:blur(64px)}
.screen{position:fixed;inset:0;transition:opacity .55s ease,transform .55s ease}
.hidden{display:none!important}
#lock{z-index:40;display:flex;align-items:center;justify-content:center;padding:16px}
.card{width:100%;max-width:448px;text-align:center;background:rgba(255,255,255,.82);backdrop-filter:blur(20px);-webkit-backdrop-filter:blur(20px);border:1px solid rgba(255,255,255,.9);border-radius:24px;padding:32px 28px;box-shadow:0 20px 55px rgba(140,94,88,.14)}
.emblem{width:64px;height:64px;margin:0 auto 20px;border-radius:16px;background:#FAF2F0;border:1px solid #EBD8D4;display:flex;align-items:center;justify-content:center;color:var(--rose)}
.emblem svg{width:32px;height:32px}
#lk-sub{font-size:13px;font-weight:700;color:var(--rose);margin-bottom:6px}
#lk-h{font-size:28px;font-weight:700;margin-bottom:8px}
#lk-hint{font-size:13px;color:#7A686A;margin-bottom:28px}
#wrap{position:relative;max-width:340px;margin:0 auto 16px;direction:ltr}
#pw{position:absolute;inset:0;width:100%;height:100%;opacity:0;z-index:3;border:0;outline:0;background:transparent;color:transparent;caret-color:transparent;font-size:20px}
#boxes{display:grid;grid-template-columns:repeat(7,1fr);gap:7px;pointer-events:none}
.b{height:52px;border-radius:12px;border:2px solid var(--line);background:rgba(255,255,255,.85);display:flex;align-items:center;justify-content:center;font-size:20px;font-weight:700;transition:all .2s cubic-bezier(.22,1,.36,1)}
.b.on{border-color:var(--rose);background:#fff;box-shadow:0 0 0 3px rgba(140,94,88,.18);transform:translateY(-2px)}
.b.f{border-color:#B98B82}
.b.ok{border-color:#6B9E78;background:#F2FAF4;color:#467853}
.b.er{border-color:#C85A53;background:#FDF3F2}
@keyframes shake{0%,100%{transform:translateX(0)}20%{transform:translateX(-8px)}40%{transform:translateX(8px)}60%{transform:translateX(-5px)}80%{transform:translateX(5px)}}
.shake{animation:shake .42s ease-in-out}
#err{min-height:24px;margin-bottom:16px;font-size:13px;font-weight:500;color:#C85A53;opacity:0;transition:opacity .2s}
.btn{border:0;cursor:pointer;color:#fff;font:700 15px 'Tajawal',sans-serif;border-radius:16px;padding:14px 28px;background:linear-gradient(90deg,#9E6D66,var(--rose));box-shadow:0 10px 24px rgba(140,94,88,.28);transition:transform .15s}
.btn:active{transform:scale(.97)}
#lk-btn{width:100%}
.foot{margin-top:24px;padding-top:16px;border-top:1px solid #EFE3E0;font:700 11px 'Playfair Display',serif;letter-spacing:.15em;color:#9C827E}
#main{z-index:10;opacity:0;padding-top:env(safe-area-inset-top,0px)}
header{position:relative;z-index:30;display:flex;justify-content:space-between;align-items:center;padding:20px 16px 12px;pointer-events:none}
.pill{background:rgba(255,255,255,.82);backdrop-filter:blur(12px);-webkit-backdrop-filter:blur(12px);border:1px solid rgba(255,255,255,.9);padding:8px 16px;border-radius:16px;box-shadow:0 1px 3px rgba(0,0,0,.06);display:flex;align-items:center;gap:10px;font-size:15px;font-weight:700}
.pill i{width:10px;height:10px;border-radius:50%;background:var(--rose)}
#cnt{font-size:13px;color:var(--rose)}
.mark{position:fixed;inset:0;display:flex;flex-direction:column;align-items:center;justify-content:center;text-align:center;pointer-events:none;z-index:0;padding:0 16px}
.mark b{font:900 15vw/1 'Playfair Display',serif;letter-spacing:.08em;color:rgba(140,94,88,.24);text-shadow:0 2px 16px rgba(255,255,255,.75)}
.mark p{margin-top:12px;font:400 14px 'Amiri',serif;color:rgba(140,94,88,.7)}
@media(min-width:640px){.mark b{font-size:9.5vw}}
#arena{position:fixed;inset:0;z-index:20;overflow:hidden;pointer-events:none;direction:ltr}
.orb{position:fixed;left:0;top:0;border-radius:50%;display:flex;align-items:center;justify-content:center;cursor:pointer;color:var(--rose);border:1.5px solid rgba(255,255,255,.85);backdrop-filter:blur(8px);-webkit-backdrop-filter:blur(8px);box-shadow:0 8px 20px rgba(140,94,88,.18),inset 0 -4px 10px rgba(255,255,255,.7);will-change:transform;z-index:20;pointer-events:auto;touch-action:manipulation;transition:box-shadow .35s}
.orb::before{content:'';position:absolute;top:11%;left:17%;width:34%;height:19%;border-radius:50%;background:linear-gradient(180deg,rgba(255,255,255,.9),rgba(255,255,255,0));transform:rotate(-28deg);pointer-events:none}
.orb svg{width:26px;height:26px;pointer-events:none}
.orb.read{box-shadow:0 0 0 2px rgba(201,168,106,.8),0 10px 26px rgba(140,94,88,.28),inset 0 -4px 10px rgba(255,255,255,.75)}
.orb.read svg{width:20px;height:20px}
#modal{position:fixed;inset:0;z-index:1000;display:flex;align-items:center;justify-content:center;padding:16px;background:rgba(42,31,33,.45);backdrop-filter:blur(12px);-webkit-backdrop-filter:blur(12px);opacity:0;pointer-events:none;transition:opacity .3s}
#modal.show{opacity:1;pointer-events:auto}
#mc{width:100%;max-width:512px;text-align:center;background:rgba(255,253,251,.96);border:2px solid var(--gold2);border-radius:24px;padding:28px 24px;box-shadow:0 25px 65px rgba(58,46,48,.28);transform:scale(.9);opacity:0;transition:transform .35s cubic-bezier(.175,.885,.32,1.275),opacity .3s}
#modal.show #mc{transform:scale(1);opacity:1}
.badge{display:inline-block;padding:4px 16px;border-radius:999px;font-size:13px;font-weight:700;background:#FAF2F0;color:var(--rose);border:1px solid #EBD8D4}
.q{margin:14px auto 8px;width:28px;height:28px;color:rgba(201,168,106,.85)}
#msg{font:400 24px/1.95 'Amiri',serif;min-height:115px;display:flex;align-items:center;justify-content:center;padding:12px 6px}
.div{margin:18px 0 20px;display:flex;align-items:center;justify-content:center;gap:12px}
.div span{height:1px;width:48px;background:linear-gradient(90deg,transparent,var(--gold2))}
.div span+i+span{background:linear-gradient(270deg,transparent,var(--gold2))}
.div i{width:6px;height:6px;border-radius:50%;background:var(--gold)}
@media(prefers-reduced-motion:reduce){*{transition:none!important;animation:none!important}}
</style>
</head>
<body>
<div class="glow"><i style="top:-96px;right:-96px;width:320px;height:320px;background:rgba(254,205,211,.35)"></i><i style="bottom:-112px;left:-96px;width:384px;height:384px;background:rgba(254,243,199,.45)"></i><i style="top:50%;left:50%;margin:-260px;width:520px;height:520px;background:rgba(255,237,213,.25)"></i></div>

<section id="lock" class="screen">
  <div class="card">
    <div class="emblem"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.75" stroke-linecap="round" stroke-linejoin="round"><path d="M4.8 2.3A.3.3 0 1 0 5 2H4a2 2 0 0 0-2 2v5a6 6 0 0 0 6 6v0a6 6 0 0 0 6-6V4a2 2 0 0 0-2-2h-1a.2.2 0 1 0 .3.3"/><path d="M8 15v1a6 6 0 0 0 6 6v0a6 6 0 0 0 6-6v-4"/><circle cx="20" cy="10" r="2"/></svg></div>
    <p id="lk-sub">&#x631;&#x633;&#x627;&#x626;&#x644; &#x625;&#x644;&#x649; &#x62F;&#x643;&#x62A;&#x648;&#x631;&#x62A;&#x64A;</p>
    <h1 id="lk-h">&#x623;&#x62F;&#x62E;&#x644; &#x643;&#x644;&#x645;&#x629; &#x627;&#x644;&#x645;&#x631;&#x648;&#x631;</h1>
    <p id="lk-hint">&#x623;&#x62F;&#x62E;&#x644;&#x64A; &#x627;&#x644;&#x631;&#x645;&#x632; &#x627;&#x644;&#x645;&#x643;&#x648;&#x651;&#x646; &#x645;&#x646; 7 &#x623;&#x631;&#x642;&#x627;&#x645; &#x644;&#x641;&#x62A;&#x62D; &#x631;&#x633;&#x627;&#x626;&#x644;&#x643;&#x650;</p>
    <div id="wrap">
      <input id="pw" type="tel" inputmode="numeric" pattern="[0-9]*" maxlength="7" autocomplete="one-time-code" aria-label="&#x643;&#x644;&#x645;&#x629; &#x627;&#x644;&#x645;&#x631;&#x648;&#x631;">
      <div id="boxes"><div class="b"></div><div class="b"></div><div class="b"></div><div class="b"></div><div class="b"></div><div class="b"></div><div class="b"></div></div>
    </div>
    <div id="err"></div>
    <button id="lk-btn" class="btn" type="button">&#x641;&#x62A;&#x62D; &#x627;&#x644;&#x631;&#x633;&#x627;&#x626;&#x644;</button>
    <div class="foot">SENIOR 2027</div>
  </div>
</section>

<main id="main" class="screen hidden">
  <header>
    <div class="pill"><i></i><h2 style="font-size:inherit">&#x631;&#x633;&#x627;&#x626;&#x644; &#x625;&#x644;&#x649; &#x62F;&#x643;&#x62A;&#x648;&#x631;&#x62A;&#x64A;</h2></div>
    <div class="pill"><span id="cnt"></span></div>
  </header>
  <div class="mark"><b>SENIOR<br> 2027</b><p>&#x627;&#x644;&#x645;&#x633;&#x64A; &#x623;&#x64A; &#x643;&#x631;&#x629; &#x644;&#x62A;&#x642;&#x631;&#x626;&#x64A; &#x631;&#x633;&#x627;&#x644;&#x629;&#x64B; &#x643;&#x64F;&#x62A;&#x628;&#x62A; &#x644;&#x623;&#x62C;&#x644;&#x643;&#x650;</p></div>
  <div id="arena"></div>
</main>

<div id="modal">
  <div id="mc">
    <span class="badge">&#x631;&#x633;&#x627;&#x626;&#x644; &#x625;&#x644;&#x649; &#x62F;&#x643;&#x62A;&#x648;&#x631;&#x62A;&#x64A;</span>
    <svg class="q" fill="currentColor" viewBox="0 0 24 24"><path d="M14.017 21v-7.391c0-5.704 3.731-9.57 8.983-10.609l.995 2.151c-2.432.917-3.995 3.638-3.995 5.849h4v10h-9.983zm-14.017 0v-7.391c0-5.704 3.748-9.57 9-10.609l.996 2.151c-2.433.917-3.996 3.638-3.996 5.849h3.983v10h-9.983z"/></svg>
    <p id="msg"></p>
    <div class="div"><span></span><i></i><span></span></div>
    <button id="save" class="btn" type="button">&#x62D;&#x641;&#x638;&#x62A;&#x647;&#x627; &#x641;&#x64A; &#x642;&#x644;&#x628;&#x64A;&#x60C; &#x627;&#x644;&#x645;&#x62A;&#x627;&#x628;&#x639;&#x629;</button>
  </div>
</div>

<script>
const MSGS=[
"\u064A\u0627 \u062F\u0643\u062A\u0648\u0631\u0629 \u0627\u0644\u0645\u0633\u062A\u0642\u0628\u0644\u060C \u0642\u062F \u062A\u0634\u062A\u062F\u0651 \u0639\u0644\u064A\u0643\u0650 \u0623\u064A\u0627\u0645 \u0627\u0644\u062F\u0631\u0627\u0633\u0629\u060C \u0648\u0642\u062F \u064A\u0637\u0648\u0644 \u0627\u0644\u0633\u0647\u0631\u060C \u0644\u0643\u0646\u0651 \u0641\u062C\u0631 \u0627\u0644\u0625\u0646\u062C\u0627\u0632 \u0642\u0631\u064A\u0628\u064C \u0648\u0623\u062C\u0645\u0644 \u0645\u0645\u0627 \u062A\u062A\u062E\u064A\u0651\u0644\u064A\u0646.",
"\u0644\u0627 \u062A\u0642\u0627\u0631\u0646\u064A \u062E\u0637\u0648\u0627\u062A\u0643\u0650 \u0628\u0623\u062D\u062F\u060C \u0628\u0644 \u0627\u062C\u0639\u0644\u064A \u062A\u0631\u0643\u064A\u0632\u0643\u0650 \u0645\u0646\u0635\u0628\u0651\u0627\u064B \u0639\u0644\u0649 \u0648\u0631\u0642\u062A\u0643\u0650 \u0648\u0647\u062F\u0641\u0643\u0650\u061B \u0641\u0645\u0646 \u0623\u062E\u0644\u0635 \u0641\u064A \u0633\u0639\u064A\u0647 \u0628\u0644\u063A \u0645\u0631\u0627\u062F\u0647 \u0628\u0625\u0630\u0646 \u0627\u0644\u0644\u0647.",
"\u0627\u062C\u0639\u0644\u064A \u0645\u0646 \u0634\u063A\u0641\u0643\u0650 \u0628\u0627\u0644\u0646\u062C\u0627\u062D \u0648\u0642\u0648\u062F\u0627\u064B \u064A\u0628\u062F\u0651\u062F \u0627\u0644\u0643\u0633\u0644\u060C \u0648\u0645\u0646 \u062A\u0648\u0643\u0651\u0644\u0643\u0650 \u0639\u0644\u0649 \u0627\u0644\u0644\u0647 \u0637\u0645\u0623\u0646\u064A\u0646\u0629\u064B \u062A\u0645\u0644\u0623 \u0642\u0644\u0628\u0643\u0650 \u0642\u0628\u0644 \u0643\u0644 \u0627\u0645\u062A\u062D\u0627\u0646.",
"\u0647\u0630\u0647 \u0627\u0644\u0645\u0631\u062D\u0644\u0629 \u0644\u064A\u0633\u062A \u0633\u0628\u0627\u0642 \u0633\u0631\u0639\u0629\u060C \u0628\u0644 \u0631\u062D\u0644\u0629 \u0646\u0641\u064E\u0633\u064D \u0637\u0648\u064A\u0644\u061B \u0641\u062E\u0630\u064A \u0642\u0633\u0637\u0627\u064B \u0645\u0646 \u0627\u0644\u0631\u0627\u062D\u0629 \u0645\u062A\u0649 \u0627\u062D\u062A\u062C\u062A\u0650\u060C \u062B\u0645 \u0639\u0648\u062F\u064A \u0623\u0634\u062F\u0651 \u0639\u0632\u0645\u0627\u064B.",
"\u0627\u0644\u0627\u0633\u062A\u0645\u0631\u0627\u0631\u064A\u0629 \u0644\u0627 \u062A\u0639\u0646\u064A \u0623\u0644\u0627 \u062A\u062A\u0639\u0628\u064A\u060C \u0628\u0644 \u0623\u0646 \u062A\u0631\u0641\u0636\u064A \u0627\u0644\u062A\u0631\u0627\u062C\u0639 \u0643\u0644\u0645\u0627 \u0647\u0645\u0651 \u0627\u0644\u0641\u062A\u0648\u0631 \u0623\u0646 \u064A\u0633\u0631\u0642 \u0634\u063A\u0641\u0643\u0650.",
"\u0643\u0644 \u0635\u0641\u062D\u0629\u064D \u062A\u0637\u0648\u064A\u0646\u0647\u0627 \u0627\u0644\u064A\u0648\u0645 \u0628\u0639\u0632\u064A\u0645\u0629\u064D \u0648\u0635\u0628\u0631\u060C \u0647\u064A \u062E\u0637\u0648\u0629\u064C \u0635\u0627\u0645\u062A\u0629 \u062A\u0642\u0631\u0651\u0628\u0643\u0650 \u0645\u0646 \u0627\u0644\u0645\u0643\u0627\u0646 \u0627\u0644\u0630\u064A \u064A\u0644\u064A\u0642 \u0628\u0637\u0645\u0648\u062D\u0643\u0650 \u0648\u0642\u0644\u0628\u0643\u0650.",
"\u0625\u0646\u0651 \u0627\u0644\u0645\u0642\u0627\u0639\u062F \u0627\u0644\u0628\u064A\u0636\u0627\u0621 \u0648\u0627\u0644\u062A\u062E\u0635\u0635\u0627\u062A \u0627\u0644\u0625\u0646\u0633\u0627\u0646\u064A\u0629 \u062A\u0644\u064A\u0642 \u0628\u0623\u0635\u062D\u0627\u0628 \u0627\u0644\u0647\u0645\u0645 \u0627\u0644\u0639\u0627\u0644\u064A\u0629 \u0645\u062B\u0644\u0643\u0650\u061B \u0641\u0648\u0627\u0635\u0644\u064A \u0627\u0644\u0645\u0633\u064A\u0631 \u0628\u0639\u064A\u0646\u064D \u062A\u0631\u0649 \u0627\u0644\u0642\u0645\u0629 \u0644\u0627 \u0627\u0644\u0639\u0642\u0628\u0627\u062A.",
"\u0644\u0627 \u062A\u0633\u062A\u0643\u062B\u0631\u064A \u0627\u0644\u062A\u0639\u0628 \u0639\u0644\u0649 \u063A\u0627\u064A\u0629\u064D \u0639\u0638\u064A\u0645\u0629\u061B \u0641\u0627\u0644\u0623\u064A\u0627\u0645 \u0627\u0644\u062A\u064A \u062A\u064F\u0646\u0641\u0642\u064A\u0646\u0647\u0627 \u0641\u064A \u0627\u0644\u062C\u062F\u0651 \u0627\u0644\u064A\u0648\u0645\u060C \u0633\u062A\u064F\u0632\u0647\u0631 \u063A\u062F\u0627\u064B \u0641\u062E\u0631\u0627\u064B \u064A\u0645\u0644\u0623 \u062D\u064A\u0627\u062A\u0643\u0650.",
"\u0625\u0646\u0651 \u0627\u0644\u0623\u062D\u0644\u0627\u0645 \u0627\u0644\u0643\u0628\u064A\u0631\u0629 \u0644\u0627 \u062A\u064F\u0645\u0646\u062D \u0635\u062F\u0641\u0629\u060C \u0628\u0644 \u062A\u064F\u0646\u062A\u0632\u0639 \u0628\u0627\u0644\u0633\u0647\u0631 \u0627\u0644\u062C\u0645\u064A\u0644\u060C \u0648\u0627\u0644\u064A\u0642\u064A\u0646 \u0627\u0644\u0630\u064A \u0644\u0627 \u064A\u0644\u064A\u0646 \u0645\u0647\u0645\u0627 \u0637\u0627\u0644 \u0627\u0644\u0637\u0631\u064A\u0642.",
"\u064A\u0643\u0641\u064A\u0643\u0650 \u0634\u0631\u0641\u0627\u064B \u0623\u0646\u0643\u0650 \u062A\u0633\u0639\u064A\u0646 \u0644\u062A\u0643\u0648\u0646\u064A \u0646\u0627\u0641\u0639\u0629\u064B \u0630\u0627\u062A \u0623\u062B\u0631\u064D \u062C\u0645\u064A\u0644 \u0641\u064A \u062D\u064A\u0627\u0629 \u0627\u0644\u0646\u0627\u0633\u061B \u0648\u0627\u0644\u0644\u0647 \u0644\u0627 \u064A\u062E\u0630\u0644 \u0642\u0644\u0628\u0627\u064B \u0635\u062F\u0642 \u0641\u064A \u0646\u064A\u062A\u0647 \u0648\u0633\u0639\u064A\u0647.",
"\u0623\u0646\u062A\u0650 \u0627\u0644\u0622\u0646 \u0641\u064A \u0645\u0631\u062D\u0644\u0629 \u0627\u0644\u0628\u0646\u0627\u0621 \u0627\u0644\u0623\u0647\u0645\u060C \u062D\u064A\u062B \u062A\u064F\u0635\u0627\u063A \u0627\u0644\u0625\u0631\u0627\u062F\u0629 \u0642\u0628\u0644 \u0627\u0644\u062F\u0631\u062C\u0627\u062A\u061B \u0641\u0643\u0648\u0646\u064A \u0639\u0644\u0649 \u0642\u062F\u0631 \u0627\u0644\u062D\u0644\u0645 \u0627\u0644\u0630\u064A \u0627\u062E\u062A\u0631\u062A\u0650\u0647 \u0644\u0646\u0641\u0633\u0643\u0650.",
"\u0643\u0644 \u0645\u0633\u0623\u0644\u0629\u064D \u062A\u062D\u0644\u0651\u064A\u0646\u0647\u0627 \u0628\u0625\u062A\u0642\u0627\u0646\u060C \u0648\u0643\u0644 \u0633\u0637\u0631\u064D \u062A\u0641\u0647\u0645\u064A\u0646\u0647 \u0628\u0635\u0628\u0631\u060C \u0647\u0648 \u0644\u0628\u0646\u0629\u064C \u0631\u0627\u0633\u062E\u0629 \u0641\u064A \u0635\u0631\u062D \u0645\u0633\u062A\u0642\u0628\u0644\u0643\u0650 \u0627\u0644\u0630\u064A \u064A\u0646\u062A\u0638\u0631\u0643\u0650.",
"\u0633\u064A\u0623\u062A\u064A \u0630\u0644\u0643 \u0627\u0644\u0635\u0628\u0627\u062D \u0627\u0644\u0630\u064A \u062A\u0642\u0641\u064A\u0646 \u0641\u064A\u0647 \u0639\u0644\u0649 \u0639\u062A\u0628\u0629 \u062C\u0627\u0645\u0639\u062A\u0643\u0650 \u0648\u062A\u062E\u0635\u0635\u0643\u0650 \u0627\u0644\u0630\u064A \u062A\u0645\u0646\u0651\u064A\u062A\u0650\u0647\u060C \u0648\u062A\u0628\u062A\u0633\u0645\u064A\u0646 \u0627\u0645\u062A\u0646\u0627\u0646\u0627\u064B \u0644\u0623\u0646\u0643\u0650 \u0644\u0645 \u062A\u0633\u062A\u0633\u0644\u0645\u064A.",
"\u062A\u0630\u0643\u0651\u0631\u064A \u0623\u0646 \u0647\u0630\u0647 \u0627\u0644\u0623\u0634\u0647\u0631 \u0627\u0644\u0645\u0639\u062F\u0648\u062F\u0629 \u0645\u0646 \u0627\u0644\u0645\u062B\u0627\u0628\u0631\u0629\u060C \u0647\u064A \u0627\u0644\u062C\u0633\u0631 \u0627\u0644\u0641\u0627\u0635\u0644 \u0628\u064A\u0646 \u0623\u0645\u0646\u064A\u0629\u064D \u0641\u064A \u0635\u062F\u0631\u0643\u0650 \u0648\u0648\u0627\u0642\u0639\u064D \u0645\u0634\u0631\u0642\u064D \u0633\u062A\u0639\u064A\u0634\u064A\u0646\u0647.",
"\u062D\u064A\u0646 \u064A\u062B\u0642\u0644 \u0639\u0644\u064A\u0643\u0650 \u0627\u0644\u0645\u0646\u0647\u062C \u0648\u062A\u0634\u062A\u062F\u0651 \u0633\u0627\u0639\u0627\u062A \u0627\u0644\u0645\u0630\u0627\u0643\u0631\u0629\u060C \u062A\u0630\u0643\u0651\u0631\u064A \u0644\u062D\u0638\u0629 \u0627\u0644\u0628\u0644\u0648\u063A \u0627\u0644\u062A\u064A \u0633\u062A\u0646\u0633\u064A\u0643\u0650 \u0643\u0644 \u0639\u0646\u0627\u0621\u064D \u0645\u0631\u0631\u062A\u0650 \u0628\u0647.",
"\u0641\u064A \u0644\u062D\u0638\u0627\u062A \u0627\u0644\u062A\u0634\u062A\u062A\u060C \u0623\u063A\u0645\u0636\u064A \u0639\u064A\u0646\u064A\u0643\u0650 \u0648\u062A\u062E\u064A\u0651\u0644\u064A \u0641\u0631\u062D\u0629 \u0625\u0639\u0644\u0627\u0646 \u0627\u0644\u0646\u062A\u0627\u0626\u062C \u0648\u0642\u062F \u0643\u064F\u062A\u0628 \u0627\u0633\u0645\u0643\u0650 \u0628\u064A\u0646 \u0645\u0646 \u0646\u0627\u0644\u0648\u0627 \u062B\u0645\u0631\u0629 \u0627\u062C\u062A\u0647\u0627\u062F\u0647\u0645.",
"\u0644\u0627 \u062A\u0633\u062A\u0635\u063A\u0631\u064A \u0625\u0646\u062C\u0627\u0632 \u0633\u0627\u0639\u0629\u064D \u0625\u0636\u0627\u0641\u064A\u0629\u064D \u0645\u0646 \u0627\u0644\u062A\u0631\u0643\u064A\u0632 \u0641\u064A \u064A\u0648\u0645\u064D \u0634\u0627\u0642\u061B \u0641\u0627\u0644\u0641\u0648\u0627\u0631\u0642 \u0627\u0644\u0639\u0638\u064A\u0645\u0629 \u062A\u0635\u0646\u0639\u0647\u0627 \u0627\u0644\u062A\u0641\u0627\u0635\u064A\u0644 \u0627\u0644\u0635\u063A\u064A\u0631\u0629."
];
const P=[
'<path d="M4.8 2.3A.3.3 0 1 0 5 2H4a2 2 0 0 0-2 2v5a6 6 0 0 0 6 6v0a6 6 0 0 0 6-6V4a2 2 0 0 0-2-2h-1a.2.2 0 1 0 .3.3"/><path d="M8 15v1a6 6 0 0 0 6 6v0a6 6 0 0 0 6-6v-4"/><circle cx="20" cy="10" r="2"/>',
'<path d="m18 2 4 4"/><path d="m17 7 3-3"/><path d="M19 9 8.7 19.3c-1 1-2.5 1-3.4 0l-.6-.6c-1-1-1-2.5 0-3.4L15 5"/><path d="m9 11 4 4"/><path d="m5 19-3 3"/><path d="m14 4 6 6"/>',
'<path d="M14.5 2v17.5c0 1.4-1.1 2.5-2.5 2.5s-2.5-1.1-2.5-2.5V2"/><path d="M8.5 2h7"/><path d="M14.5 16h-5"/>',
'<path d="m10.5 20.5 10-10a4.95 4.95 0 1 0-7-7l-10 10a4.95 4.95 0 1 0 7 7Z"/><path d="m8.5 8.5 7 7"/>',
'<path d="M6 18h8"/><path d="M3 22h18"/><path d="M14 22a7 7 0 1 0 0-14h-1"/><path d="M9 14h2"/><path d="M9 12a2 2 0 0 1-2-2V6h6v4a2 2 0 0 1-2 2Z"/><path d="M12 6V3a1 1 0 0 0-1-1H9a1 1 0 0 0-1 1v3"/>',
'<path d="M10 2v7.527a2 2 0 0 1-.211.896L4.72 20.55a1 1 0 0 0 .9 1.45h12.76a1 1 0 0 0 .9-1.45l-5.069-10.127A2 2 0 0 1 14 9.527V2"/><path d="M8.5 2h7"/><path d="M7 16h10"/>',
'<path d="M19 14c1.49-1.46 3-3.21 3-5.5A5.5 5.5 0 0 0 16.5 3c-1.76 0-3 .5-4.5 2-1.5-1.5-2.74-2-4.5-2A5.5 5.5 0 0 0 2 8.5c0 2.3 1.5 4.05 3 5.5l7 7Z"/><path d="M3.22 12H9.5l.5-1 2 4.5 2-7 1.5 3.5h5.27"/>',
'<path d="M2 15c6.667-6 13.333 0 20-6"/><path d="M9 22c1.798-1.998 2.518-3.995 2.807-5.993"/><path d="M15 2c-1.798 1.998-2.518 3.995-2.807 5.993"/><path d="m17 6-2.5-2.5"/><path d="m14 8-1-1"/><path d="m7 18 2.5 2.5"/><path d="m3.5 14.5.5.5"/><path d="m20 9 .5.5"/><path d="m6.5 12.5 1 1"/><path d="m16.5 10.5 1 1"/><path d="m10 16 1.5 1.5"/>',
'<path d="M8 6V4a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v2"/><rect width="20" height="14" x="2" y="6" rx="2"/><path d="M12 10v6"/><path d="M9 13h6"/>',
'<path d="M14 4v10.54a4 4 0 1 1-4 0V4a2 2 0 0 1 4 0Z"/>',
'<path d="M8 2h8"/><path d="M9 2v2.789a4 4 0 0 1-.672 2.219l-.656.984A4 4 0 0 0 7 10.212V20a2 2 0 0 0 2 2h6a2 2 0 0 0 2-2v-9.789a4 4 0 0 0-.672-2.219l-.656-.984A4 4 0 0 1 15 4.788V2"/><path d="M7 15h10"/>',
'<path d="M10 10.01h.01"/><path d="M10 14.01h.01"/><path d="M14 10.01h.01"/><path d="M14 14.01h.01"/><path d="M18 6v11.5"/><path d="M6 6v12"/><rect width="20" height="12" x="2" y="6" rx="2"/>',
'<path d="M12 22a7 7 0 0 0 7-7c0-2-1-3.9-3-5.5s-3.5-4-4-6.5c-.5 2.5-2 4.9-4 6.5C6 11.1 5 13 5 15a7 7 0 0 0 7 7z"/>',
'<circle cx="12" cy="12" r="1"/><path d="M20.2 20.2c2.04-2.03.02-7.36-4.5-11.9-4.54-4.52-9.87-6.54-11.9-4.5-2.04 2.03-.02 7.36 4.5 11.9 4.54 4.52 9.87 6.54 11.9 4.5Z"/><path d="M15.7 15.7c4.52-4.54 6.54-9.87 4.5-11.9-2.03-2.04-7.36-.02-11.9 4.5-4.52 4.54-6.54 9.87-4.5 11.9 2.03 2.04 7.36.02 11.9-4.5Z"/>',
'<rect width="8" height="4" x="8" y="2" rx="1" ry="1"/><path d="M16 4h2a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h2"/><path d="M12 11v6"/><path d="M9 14h6"/>',
'<path d="M2.062 12.348a1 1 0 0 1 0-.696 10.75 10.75 0 0 1 19.876 0 1 1 0 0 1 0 .696 10.75 10.75 0 0 1-19.876 0"/><circle cx="12" cy="12" r="3"/>',
'<path d="M20 13c0 5-3.5 7.5-7.66 8.95a1 1 0 0 1-.67-.01C7.5 20.5 4 18 4 13V6a1 1 0 0 1 1-1c2 0 4.5-1.2 6.24-2.72a1.17 1.17 0 0 1 1.52 0C14.51 3.81 17 5 19 5a1 1 0 0 1 1 1z"/><path d="M12 8v6"/><path d="M9 11h6"/>'
];
const icon=p=>'<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round">'+p+'</svg>';
const HEART='<svg viewBox="0 0 24 24" fill="currentColor"><path d="M12 21.35l-1.45-1.32C5.4 15.36 2 12.28 2 8.5 2 5.42 4.42 3 7.5 3c1.74 0 3.41.81 4.5 2.09C13.09 3.81 14.76 3 16.5 3 19.58 3 22 5.42 22 8.5c0 3.78-3.4 6.86-8.55 11.54L12 21.35z"/></svg>';
const $=id=>document.getElementById(id);
const CODE="6619999";
const pw=$('pw'),boxes=[...document.querySelectorAll('.b')],err=$('err'),row=$('boxes');
let unlocked=false,busy=false;

function norm(s){
  return s.replace(/[\u0660-\u0669]/g,d=>d.charCodeAt(0)-0x660).replace(/[\u06F0-\u06F9]/g,d=>d.charCodeAt(0)-0x6F0).replace(/\D/g,'').slice(0,7);
}
function draw(v){
  const foc=document.activeElement===pw;
  boxes.forEach((b,i)=>{
    b.textContent=v[i]||'';
    b.classList.remove('on','f','er','ok');
    if(v[i])b.classList.add('f');
    if(foc&&i===Math.min(v.length,6))b.classList.add('on');
  });
}
function fail(m){
  err.textContent=m;err.style.opacity=1;
  boxes.forEach(b=>b.classList.add('er'));
  row.classList.remove('shake');void row.offsetWidth;row.classList.add('shake');
}
function clear(){err.style.opacity=0;boxes.forEach(b=>b.classList.remove('er'))}
function open(){
  if(unlocked)return;unlocked=true;pw.blur();clear();
  boxes.forEach(b=>{b.classList.remove('on','f');b.classList.add('ok')});
  setTimeout(()=>{
    const l=$('lock');l.style.opacity=0;l.style.transform='scale(1.03)';
    setTimeout(()=>{
      l.classList.add('hidden');$('main').classList.remove('hidden');
      initOrbs();
      requestAnimationFrame(()=>$('main').style.opacity=1);
    },420);
  },260);
}
function check(v,byBtn){
  if(unlocked||busy)return;
  if(v.length===7){
    if(v===CODE)open();
    else{
      busy=true;fail('\u0643\u0644\u0645\u0629 \u0627\u0644\u0645\u0631\u0648\u0631 \u063A\u064A\u0631 \u0635\u062D\u064A\u062D\u0629\u060C \u062D\u0627\u0648\u0644\u064A \u0645\u0631\u0651\u0629\u064B \u0623\u062E\u0631\u0649');
      setTimeout(()=>{pw.value='';draw('');busy=false;pw.focus()},520);
    }
  }else if(byBtn){fail('\u064A\u0631\u062C\u0649 \u0625\u062F\u062E\u0627\u0644 \u0627\u0644\u0623\u0631\u0642\u0627\u0645 \u0627\u0644\u0633\u0628\u0639\u0629 \u0643\u0627\u0645\u0644\u0629\u064B');pw.focus()}
}
pw.addEventListener('input',()=>{
  if(unlocked||busy)return;
  clear();const c=norm(pw.value);
  if(pw.value!==c)pw.value=c;
  draw(c);if(c.length===7)check(c,false);
});
pw.addEventListener('focus',()=>draw(pw.value));
pw.addEventListener('blur',()=>draw(pw.value));
pw.addEventListener('keydown',e=>{if(e.key==='Enter'){e.preventDefault();check(pw.value,true)}});
$('lk-btn').addEventListener('click',()=>check(pw.value,true));
window.addEventListener('load',()=>{draw('');setTimeout(()=>pw.focus(),120)});

/* ---------- Orbs ---------- */
const TINTS=[
 'radial-gradient(circle at 32% 28%,#fff 0%,#FBE3E6 55%,#F3D2D8 100%)',
 'radial-gradient(circle at 32% 28%,#fff 0%,#E3F3EC 55%,#CFE8DC 100%)',
 'radial-gradient(circle at 32% 28%,#fff 0%,#ECE4F6 55%,#DCCFEE 100%)',
 'radial-gradient(circle at 32% 28%,#fff 0%,#FBF0E0 55%,#F4E2C8 100%)'
];
const READ_BG='radial-gradient(circle at 32% 28%,#fff 0%,#FBF3E6 60%,#F4E6CF 100%)';
const cntEl=$('cnt');
const orbs=[];
let readSet=new Set(),current=-1,raf=0;
try{const s=JSON.parse(localStorage.getItem('senior2027-read')||'[]');if(Array.isArray(s))s.forEach(n=>{if(n>=0&&n<17)readSet.add(n)})}catch(e){}
function updateCount(){cntEl.textContent=readSet.size+' / 17 \u0631\u0633\u0627\u0644\u0629'}
function markRead(o){o.el.classList.add('read');o.el.style.background=READ_BG;o.el.innerHTML=HEART}

function initOrbs(){
  const arena=$('arena');
  const W=window.innerWidth,H=window.innerHeight;
  const top=80,bottom=24;
  for(let i=0;i<17;i++){
    const size=44+Math.round(Math.random()*24);
    const el=document.createElement('div');
    el.className='orb';el.setAttribute('role','button');el.setAttribute('aria-label','\u0631\u0633\u0627\u0644\u0629 '+(i+1));
    el.style.width=el.style.height=size+'px';
    el.style.background=TINTS[i%4];
    el.innerHTML=icon(P[i]);
    const o={el,size,i,x:8+Math.random()*(W-size-16),y:top+Math.random()*(H-top-bottom-size),vx:(Math.random()-.5)*.5,vy:(Math.random()-.5)*.5,fz:Math.random()*6.28};
    if(Math.abs(o.vx)<.08)o.vx=.12;if(Math.abs(o.vy)<.08)o.vy=-.12;
    if(readSet.has(i))markRead(o);
    el.addEventListener('click',()=>show(i));
    arena.appendChild(el);orbs.push(o);
  }
  updateCount();
  window.addEventListener('resize',()=>{orbs.forEach(o=>{o.x=Math.min(o.x,window.innerWidth-o.size-8);o.y=Math.min(o.y,window.innerHeight-o.size-bottom)})});
  const still=matchMedia('(prefers-reduced-motion:reduce)').matches;
  function tick(t){
    const W=window.innerWidth,H=window.innerHeight;
    orbs.forEach(o=>{
      if(!still&&o.i!==current){
        o.x+=o.vx;o.y+=o.vy+Math.sin(t/1400+o.fz)*.12;
        if(o.x<4){o.x=4;o.vx=Math.abs(o.vx)}
        if(o.x>W-o.size-4){o.x=W-o.size-4;o.vx=-Math.abs(o.vx)}
        if(o.y<top){o.y=top;o.vy=Math.abs(o.vy)}
        if(o.y>H-o.size-bottom){o.y=H-o.size-bottom;o.vy=-Math.abs(o.vy)}
      }
      o.el.style.transform='translate3d('+o.x.toFixed(1)+'px,'+o.y.toFixed(1)+'px,0)';
    });
    raf=requestAnimationFrame(tick);
  }
  raf=requestAnimationFrame(tick);
}

/* ---------- Modal ---------- */
function show(i){
  current=i;
  $('msg').textContent='\u00AB '+MSGS[i]+' \u00BB';
  $('modal').classList.add('show');
}
function hide(){$('modal').classList.remove('show');current=-1}
$('save').addEventListener('click',()=>{
  if(current<0)return;
  const i=current;
  if(!readSet.has(i)){
    readSet.add(i);markRead(orbs[i]);updateCount();
    try{localStorage.setItem('senior2027-read',JSON.stringify([...readSet]))}catch(e){}
  }
  hide();
});
$('modal').addEventListener('click',e=>{if(e.target===$('modal'))hide()});
</script>
</body>
</html>
