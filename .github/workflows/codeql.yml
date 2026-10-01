<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<meta name="theme-color" content="#1a0d14">
<title>دريسية — إلى أمي | من حمزة</title>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Amiri:ital,wght@0,400;0,700;1,400&family=Cairo:wght@300..800&family=Reem+Kufi:wght@400..700&display=swap" rel="stylesheet">

‏<style>
:root{
  --night:#150a10; --night2:#241019;
  --rose:#e88aa9; --rose-deep:#c2506f;
  --gold:#e3bd6a; --gold-soft:#f3dcae;
  --cream:#fdf6f1; --ink:#f6ece8; --muted:#c3a5ad;
  --shadow:0 30px 70px -30px rgba(0,0,0,.85);
}
*{box-sizing:border-box;margin:0;padding:0;-webkit-tap-highlight-color:transparent}
html{scroll-behavior:smooth;scroll-padding-top:70px}
body{
  font-family:'Cairo',-apple-system,BlinkMacSystemFont,"SF Arabic",sans-serif;
  background:var(--night);color:var(--ink);overflow-x:hidden;
  line-height:1.95;-webkit-font-smoothing:antialiased;
}

#fx{position:fixed;inset:0;z-index:0;pointer-events:none}
.glow{
  position:fixed;inset:0;z-index:0;pointer-events:none;
  background:
    radial-gradient(55% 40% at 12% 6%, rgba(226,138,169,.20), transparent 68%),
    radial-gradient(50% 38% at 88% 18%, rgba(227,189,106,.16), transparent 68%),
    radial-gradient(75% 55% at 50% 108%, rgba(194,80,111,.22), transparent 70%);
  animation:breathe 16s ease-in-out infinite alternate;
}
@keyframes breathe{from{transform:scale(1);opacity:.9}to{transform:scale(1.09);opacity:1}}

/* ============ الستارة ============ */
#curtain{
  position:fixed;inset:0;z-index:100;
  background:linear-gradient(160deg,#0d0509,#1d0d15 55%,#0d0509);
  display:grid;place-items:center;
  transition:opacity 1.2s ease,visibility 1.2s;
}
#curtain.gone{opacity:0;visibility:hidden}
#curtain .word{
  font-family:'Reem Kufi',sans-serif;font-size:clamp(1.5rem,7vw,2.6rem);
  font-weight:600;letter-spacing:.22em;
  background:linear-gradient(100deg,var(--gold),var(--gold-soft),var(--rose),var(--gold));
  background-size:280% 100%;-webkit-background-clip:text;background-clip:text;color:transparent;
  animation:sheen 3.4s linear infinite;
}
#curtain .hint{margin-top:16px;font-size:.8rem;color:#8b6a76;letter-spacing:.1em;text-align:center}
@keyframes sheen{to{background-position:-280% 0}}

/* ============ قائمة التنقّل ============ */
.nav{
  position:fixed;top:0;right:0;left:0;z-index:50;
  background:rgba(21,10,16,.82);
  -webkit-backdrop-filter:blur(14px);backdrop-filter:blur(14px);
  border-bottom:1px solid rgba(227,189,106,.18);
  transform:translateY(-100%);transition:transform .6s cubic-bezier(.2,.7,.3,1);
}
.nav.show{transform:translateY(0)}
.nav .in{
  max-width:880px;margin:0 auto;padding:9px 14px;
  display:flex;align-items:center;gap:4px;overflow-x:auto;
  scrollbar-width:none;
}
.nav .in::-webkit-scrollbar{display:none}
.nav .brand{
  font-family:'Amiri',serif;font-size:1.05rem;font-weight:700;
  color:var(--gold-soft);margin-inline-end:auto;white-space:nowrap;
  padding-inline-start:4px;
}
.nav a{
  font-family:'Reem Kufi',sans-serif;font-size:.76rem;
  color:var(--muted);text-decoration:none;white-space:nowrap;
  padding:7px 13px;border-radius:99px;transition:color .3s,background .3s;
}
.nav a:hover,.nav a:active{color:var(--gold-soft);background:rgba(227,189,106,.12)}

/* ============ الغلاف ============ */
.hero{
  position:relative;z-index:2;min-height:100svh;
  display:flex;flex-direction:column;align-items:center;justify-content:center;
  text-align:center;padding:80px 22px 70px;
}
.eyebrow{
  font-family:'Reem Kufi',sans-serif;font-size:clamp(.7rem,2.9vw,.85rem);
  letter-spacing:.34em;color:var(--rose);opacity:0;animation:up .9s .2s forwards;
}
.name{
  font-family:'Amiri',serif;font-weight:700;
  font-size:clamp(4rem,21vw,11rem);line-height:1.1;margin:10px 0 4px;
  background:linear-gradient(100deg,var(--gold) 0%,var(--gold-soft) 22%,var(--rose) 48%,var(--gold-soft) 72%,var(--gold) 100%);
  background-size:260% 100%;-webkit-background-clip:text;background-clip:text;color:transparent;
  opacity:0;
  animation:nameIn 1.5s .45s cubic-bezier(.2,.8,.25,1) forwards, sheen 7s 2s linear infinite;
}
@keyframes nameIn{
  0%{opacity:0;transform:scale(.86);filter:blur(14px)}
  100%{opacity:1;transform:scale(1);filter:blur(0) drop-shadow(0 0 32px rgba(232,138,169,.35))}
}
.role{font-family:'Amiri',serif;font-size:clamp(1.05rem,4vw,1.6rem);color:var(--muted);opacity:0;animation:up 1s .95s forwards}
.orn{margin:22px 0 6px;color:var(--gold);font-size:1.1rem;letter-spacing:.55em;opacity:0;animation:up 1s 1.15s forwards}
.from{font-family:'Amiri',serif;font-size:clamp(1rem,3.6vw,1.3rem);color:var(--muted);opacity:0;animation:up 1s 1.35s forwards}
.from b{color:var(--gold-soft);font-weight:700;text-shadow:0 0 18px rgba(227,189,106,.45)}
.scroll{margin-top:40px;color:var(--rose);font-size:1.25rem;opacity:0;animation:up 1s 1.6s forwards}
.scroll span{display:block;animation:bob 2s ease-in-out infinite}
@keyframes bob{0%,100%{transform:translateY(0)}50%{transform:translateY(9px)}}
@keyframes up{from{opacity:0;transform:translateY(24px)}to{opacity:1;transform:none}}

/* ============ الأقسام ============ */
.wrap{position:relative;z-index:2;max-width:880px;margin:0 auto;padding:0 20px}
section{padding:76px 0;border-top:1px solid rgba(227,189,106,.10)}
section:first-of-type{border-top:none}
.head{text-align:center;margin-bottom:38px}
.head .tag{font-family:'Reem Kufi',sans-serif;font-size:.72rem;letter-spacing:.3em;color:var(--gold);display:block;margin-bottom:10px}
.head h2{
  font-family:'Amiri',serif;font-weight:700;font-size:clamp(1.7rem,6vw,2.7rem);line-height:1.5;
  background:linear-gradient(100deg,var(--cream),var(--gold-soft) 45%,var(--rose));
  -webkit-background-clip:text;background-clip:text;color:transparent;
}

.panel{
  background:linear-gradient(170deg,rgba(255,255,255,.055),rgba(255,255,255,.018));
  border:1px solid rgba(227,189,106,.22);border-radius:26px;
  padding:clamp(24px,5vw,48px);box-shadow:var(--shadow);
}
.panel p{font-family:'Amiri',serif;font-size:clamp(1.12rem,4vw,1.42rem);line-height:2.25;color:#f2e4e4;margin-bottom:1.1em}
.panel p:last-child{margin-bottom:0}
.panel .first::first-letter{font-size:2.7em;float:inline-start;line-height:.82;padding-inline-end:.08em;color:var(--gold);font-weight:700}

/* ============ القصيدة ============ */
.poem{
  background:linear-gradient(175deg,rgba(227,189,106,.075),rgba(194,80,111,.05));
  border:1px solid rgba(227,189,106,.28);border-radius:26px;
  padding:clamp(26px,5vw,54px);box-shadow:var(--shadow);
}
.poem .title{
  font-family:'Amiri',serif;font-size:clamp(1.25rem,4.6vw,1.7rem);font-weight:700;
  color:var(--gold-soft);text-align:center;margin-bottom:8px;
}
.poem .by{
  text-align:center;font-family:'Reem Kufi',sans-serif;font-size:.7rem;
  letter-spacing:.24em;color:var(--rose);margin-bottom:30px;
}
.verse{
  display:grid;grid-template-columns:1fr auto 1fr;gap:16px;align-items:center;
  padding:11px 0;
}
.verse i{
  font-style:normal;color:var(--gold);font-size:.62rem;opacity:.75;
}
.verse span{
  font-family:'Amiri',serif;font-size:clamp(1.05rem,3.9vw,1.3rem);
  line-height:1.95;color:#f7ecec;
}
.verse span:first-child{text-align:left}
.verse span:last-child{text-align:right}
.verse:last-of-type{padding-bottom:0}

/* الخاطرة */
.khatira{
  margin-top:34px;padding-top:28px;
  border-top:1px solid rgba(227,189,106,.2);
}
.khatira .lbl{
  font-family:'Reem Kufi',sans-serif;font-size:.68rem;letter-spacing:.28em;
  color:var(--gold);display:block;text-align:center;margin-bottom:18px;
}
.khatira p{
  font-family:'Amiri',serif;font-size:clamp(1.1rem,3.9vw,1.32rem);
  line-height:2.3;color:#f0e0e0;text-align:center;margin-bottom:.85em;
}
.khatira p:last-child{margin-bottom:0}
.khatira b{color:var(--gold-soft)}

/* بيت مختار */
.chosen{
  margin-top:30px;text-align:center;
  border:1px dashed rgba(227,189,106,.35);border-radius:18px;
  padding:22px 18px;
}
.chosen p{
  font-family:'Amiri',serif;font-size:clamp(1.08rem,3.9vw,1.28rem);
  line-height:2.1;color:var(--gold-soft);
}

/* ============ البطاقات ============ */
.cards{display:grid;gap:16px;grid-template-columns:repeat(auto-fit,minmax(240px,1fr))}
.card{
  position:relative;
  background:linear-gradient(170deg,rgba(255,255,255,.06),rgba(255,255,255,.015));
  border:1px solid rgba(232,138,169,.2);border-radius:20px;padding:26px 24px;
  transition:transform .5s cubic-bezier(.2,.7,.3,1),border-color .5s,box-shadow .5s;
}
.card:hover{transform:translateY(-8px);border-color:rgba(227,189,106,.5);box-shadow:0 28px 50px -26px rgba(194,80,111,.75)}
.card .ic{font-family:'Amiri',serif;font-size:1.6rem;color:var(--gold);display:block;margin-bottom:10px;line-height:1}
.card h3{font-family:'Reem Kufi',sans-serif;font-size:1rem;font-weight:600;color:var(--rose);margin-bottom:8px}
.card p{font-family:'Amiri',serif;font-size:1.1rem;line-height:2;color:#e8d7d7}

/* ============ الشكر ============ */
.thanks-list{list-style:none}
.thanks-list li{
  display:grid;grid-template-columns:auto 1fr;gap:14px;align-items:start;
  padding:18px 0;border-bottom:1px solid rgba(227,189,106,.14);
}
.thanks-list li:last-child{border-bottom:none}
.thanks-list .mk{font-family:'Amiri',serif;font-size:1.5rem;color:var(--gold);line-height:1;margin-top:2px}
.thanks-list p{font-family:'Amiri',serif;font-size:clamp(1.05rem,3.8vw,1.28rem);line-height:2.1;color:#f0e2e2}

/* ============ الدعاء ============ */
.dua{
  text-align:center;border:1px solid rgba(227,189,106,.3);border-radius:26px;
  padding:clamp(26px,5vw,50px);
  background:linear-gradient(170deg,rgba(227,189,106,.09),rgba(194,80,111,.06));
  box-shadow:var(--shadow);
}
.dua p{font-family:'Amiri',serif;font-size:clamp(1.15rem,4.4vw,1.55rem);line-height:2.35;color:#fbf1e6}
.dua .amin{display:block;margin-top:20px;font-family:'Reem Kufi',sans-serif;font-size:.8rem;letter-spacing:.32em;color:var(--gold)}

/* ============ التفاعل ============ */
.play{text-align:center}
.btn{
  font-family:'Cairo',sans-serif;font-weight:700;font-size:1rem;
  color:#2a0d16;border:none;border-radius:99px;cursor:pointer;padding:16px 44px;
  background:linear-gradient(120deg,var(--gold-soft),var(--gold) 55%,var(--rose));
  box-shadow:0 20px 44px -18px rgba(227,189,106,.8);
  transition:transform .25s,box-shadow .25s,filter .25s;
}
.btn:hover{transform:translateY(-3px);filter:brightness(1.07);box-shadow:0 26px 54px -18px rgba(227,189,106,.95)}
.btn:active{transform:translateY(0) scale(.97)}
.play .note{margin-top:14px;font-size:.82rem;color:var(--muted)}

/* ============ الخاتمة ============ */
.finale{position:relative;z-index:2;text-align:center;padding:88px 22px 120px;border-top:1px solid rgba(227,189,106,.12)}
.finale .big{font-family:'Amiri',serif;font-weight:700;font-size:clamp(1.5rem,6vw,2.6rem);line-height:1.75;color:var(--cream)}
.finale .big em{font-style:normal;background:linear-gradient(100deg,var(--gold),var(--rose));-webkit-background-clip:text;background-clip:text;color:transparent}
.finale .sig{margin-top:26px;font-family:'Amiri',serif;font-size:clamp(1.1rem,4vw,1.5rem);color:var(--muted)}
.finale .sig b{color:var(--gold-soft)}
.finale .hearts{margin-top:20px;color:var(--rose);letter-spacing:.6em;font-size:1.1rem}

.reveal{opacity:0;transform:translateY(38px);transition:opacity 1s cubic-bezier(.2,.7,.3,1),transform 1s cubic-bezier(.2,.7,.3,1)}
.reveal.in{opacity:1;transform:none}

@media (prefers-reduced-motion:reduce){
  *{animation-duration:.01ms!important;animation-iteration-count:1!important;transition-duration:.01ms!important}
  .reveal{opacity:1;transform:none}
  #curtain{display:none}
}
@media (max-width:560px){
  section{padding:56px 0}
  .verse{grid-template-columns:1fr;gap:2px;padding:14px 0;text-align:center}
  .verse i{display:none}
  .verse span:first-child,.verse span:last-child{text-align:center}
  .verse span:first-child::after{content:"";display:block;height:1px;width:36px;margin:9px auto;background:rgba(227,189,106,.35)}
  .panel .first::first-letter{font-size:2.2em}
}
</style>
</head>
<body>

<canvas id="fx" aria-hidden="true"></canvas>
<div class="glow" aria-hidden="true"></div>

<div id="curtain">
  <div>
    <div class="word">هديّة</div>
    <div class="hint">اضغط في أي مكان</div>
  </div>
</div>

<nav class="nav" id="nav">
  <div class="in">
    <span class="brand">دريسية</span>
    <a href="#madah">مدح</a>
    <a href="#qasida">قصيدة</a>
    <a href="#shukr">شكر</a>
    <a href="#dua">دعاء</a>
  </div>
</nav>

<header class="hero">
  <p class="eyebrow">إلى من لا تُشبه أحدًا</p>
  <h1 class="name">دريسية</h1>
  <p class="role">أمي… ومعنى الأمّ كلّه</p>
  <div class="orn">❦ ❦ ❦</div>
  <p class="from">من ابنك <b>حمزة</b></p>
  <div class="scroll"><span>⌄</span></div>
</header>

<main class="wrap">

  <!-- ============ المدح ============ -->
  <section id="madah">
    <div class="head reveal">
      <span class="tag">مدحٌ لا يكفي</span>
      <h2>لو أنصفَ الشعرُ أمّي… لخجل</h2>
    </div>
    <div class="panel reveal">
      <p class="first">
        دريسية… اسمٌ إذا نُطق هدأ القلب، وإذا مرّ على السمع صار صوتًا يعرف طريقه إلى الطمأنينة.
        ليست أمًّا فقط، بل البيت الذي لا يسقط سقفه، والنافذة التي لا يُغلق ضوءها، واليد التي تصل قبل أن أطلب.
      </p>
      <p>
        رأيتُ الدنيا بأعين كثيرة، فما رأيت عينًا تنظر إليّ كما تنظرين أنت. ولا سمعتُ صوتًا يخاف عليّ
        كما يخاف صوتك — تخافين بلا ضجيج، وتدعين بلا أن يراكِ أحد، وتحملين عنّي ثقلي ثم تقولين إنك لم تحملي شيئًا.
      </p>
      <p>
        أنتِ صاحبة الفضل الأول في كل خير فيّ. فإن كان في كلامي أدب، فهو من تربيتك. وإن كان في قلبي رحمة،
        فهي أثر من يديك. وإن كان في خطواتي ثبات، فذلك لأني مشيتُ على طريقٍ مهدتِه أنت.
      </p>
    </div>
  </section>

  <!-- ============ القصيدة ============ -->
  <section id="qasida">
    <div class="head reveal">
      <span class="tag">قصيدة</span>
      <h2>يا دريسيةُ… يا نبعَ الحنانِ</h2>
    </div>

    <div class="poem reveal">
      <p class="title">إلى أمّي</p>
      <p class="by">شعر: حمزة</p>

      <div class="verse"><span>يا دريسيةُ، يا نبعَ الحنانِ</span><i>❋</i><span>ويا أوّلَ الدعاءِ على لساني</span></div>
      <div class="verse"><span>علّمتِني الصبرَ حينَ كنتُ صغيرًا</span><i>❋</i><span>والصبرُ درسٌ لا يُشترى بالأثمانِ</span></div>
      <div class="verse"><span>رأيتُ في عينيكِ دنيا واسعةً</span><i>❋</i><span>وضاقتِ الدنيا بغيرِ حنانِ</span></div>
      <div class="verse"><span>سهرتِ ليلي وأنا في غفلتي</span><i>❋</i><span>وكنتِ تَدعينَ لي في كلِّ آنِ</span></div>
      <div class="verse"><span>يا أمَّ حمزةَ، يا أغلى ما ملكتُ</span><i>❋</i><span>أنتِ الأمانُ وكنتِ خيرَ أمانِ</span></div>
      <div class="verse"><span>وإن كبرتُ، فسوفَ أبقى طفلَها</span><i>❋</i><span>يشتاقُ حضنَكِ في كلِّ زمانِ</span></div>

      <div class="khatira">
        <span class="lbl">خاطرة</span>
        <p>لو سألوني: ماذا تريد من الدنيا؟ لقلتُ: أن أرى وجهها كلّ صباح.</p>
        <p>ولو سألوني: ماذا تخاف؟ لقلتُ: أن يغيبَ ذلك الوجه يومًا.</p>
        <p>ولو سألوني: مَن أنت؟ لقلتُ: <b>أنا ابن دريسية</b>… وهذا حسبي.</p>
      </div>

      <div class="chosen">
        <p>«وما في الأرضِ أصدقُ من دعاءٍ<br>يخرجُ من فمِ الأمِّ في السَّحَرِ»</p>
      </div>
    </div>
  </section>

  <!-- ============ ما تعلمته ============ -->
  <section id="taallum">
    <div class="head reveal">
      <span class="tag">ما تعلّمته منك</span>
      <h2>دروسي الأولى كانت من يديك</h2>
    </div>
    <div class="cards">
      <div class="card reveal"><span class="ic">❦</span>
        <h3>الصبر</h3><p>تعلّمتُ منك أن الصبر ليس انتظارًا، بل أن تبقى واقفًا حتى لو تعبت.</p>
      </div>
      <div class="card reveal"><span class="ic">❦</span>
        <h3>الرضا</h3><p>رأيتك تفرحين بالقليل، فأفهمتُ أن الفرح ليس في الكثرة بل في القلب.</p>
      </div>
      <div class="card reveal"><span class="ic">❦</span>
        <h3>الكرم</h3><p>تعطينا وأنتِ محتاجة، ثم تقولين إنك لا تحتاجين شيئًا.</p>
      </div>
      <div class="card reveal"><span class="ic">❦</span>
        <h3>الدعاء</h3><p>تعلّمتُ أن دعاءك أسرع من كل الأسباب، وأنه يسبقني إلى حيث لا أعلم.</p>
      </div>
    </div>
  </section>

  <!-- ============ الشكر ============ -->
  <section id="shukr">
    <div class="head reveal">
      <span class="tag">شكرًا…</span>
      <h2>شكرًا لكل شيء لم تعرفي أني رأيته</h2>
    </div>
    <ul class="thanks-list reveal">
      <li><span class="mk">١</span><p>شكرًا لأنك سهرتِ ليالٍ وأنا نائم، ولم تخبريني بها إلا بعد سنين.</p></li>
      <li><span class="mk">٢</span><p>شكرًا لأنكِ كنتِ تخفين تعبك عني حتى لا أتعب، فتحمّلتِ أنتِ الاثنين.</p></li>
      <li><span class="mk">٣</span><p>شكرًا لأنكِ فرحتِ بنجاحي كأنه نجاحك، وحزنكِ على فشلي كان أكبر من حزني.</p></li>
      <li><span class="mk">٤</span><p>شكرًا لأنكِ لم تشتكِ مني يومًا، مع أني أعلم أني أخطأتُ كثيرًا.</p></li>
      <li><span class="mk">٥</span><p>شكرًا لأنكِ علّمتِني أن أرفع رأسي بلا كِبر، وأن أنحني بلا ذلّ.</p></li>
      <li><span class="mk">٦</span><p>شكرًا لأنكِ موجودة. هذه وحدها كافية لأن يكون في العمر معنى.</p></li>
    </ul>
  </section>

  <!-- ============ الدعاء ============ -->
  <section id="dua">
    <div class="head reveal">
      <span class="tag">دعاء</span>
      <h2>اللهم إن لك أمًّا حملتني ولم تشتكِ</h2>
    </div>
    <div class="dua reveal">
      <p>
        اللهم أطِل عمرها في طاعتك، واملأ قلبها فرحًا بقدر ما أفرحتني، وأرِح صدرها بقدر ما حملت عني،
        واجعل كل سنة قادمة عليها أهدى من التي قبلها. اللهم ارزقها من حيث لا تحتسب، واشفِ سقمها،
        واكتب لها الجنة — فإني لا أعرف أحدًا استحقّها أكثر منها.
      </p>
      <span class="amin">آمين يا ربّ العالمين</span>
    </div>
  </section>

  <!-- ============ التفاعل ============ -->
  <section class="play reveal">
    <button class="btn" id="love">أرسل لها قلبًا</button>
    <p class="note">اضغط… وشاهد ما يحدث في السماء</p>
  </section>

</main>

<footer class="finale">
  <p class="big">كلُّ عامٍ وأنتِ بخير يا <em>دريسية</em><br>يا أغلى ما أملك في هذه الدنيا</p>
  <p class="sig">بكل حبّي وامتناني — ابنك <b>حمزة</b></p>
  <div class="hearts">❤ ❤ ❤</div>
</footer>

<script>
/* ---------- جزيئات ذهبية ---------- */
(function(){
  var c=document.getElementById('fx'), x=c.getContext('2d');
  var parts=[], W=0, H=0, DPR=Math.min(window.devicePixelRatio||1,2);
  var reduce=window.matchMedia&&window.matchMedia('(prefers-reduced-motion: reduce)').matches;
  function size(){ W=c.width=innerWidth*DPR; H=c.height=innerHeight*DPR;
    c.style.width=innerWidth+'px'; c.style.height=innerHeight+'px'; }
  size(); addEventListener('resize', size);
  var n = innerWidth<640?55:110;
  for(var i=0;i<n;i++){
    parts.push({x:Math.random()*W,y:Math.random()*H,
      r:(Math.random()*1.9+0.5)*DPR, vy:-(Math.random()*0.32+0.08)*DPR,
      vx:(Math.random()-0.5)*0.22*DPR, a:Math.random()*0.55+0.15,
      tw:Math.random()*Math.PI*2, gold:Math.random()>0.42});
  }
  function frame(){
    x.clearRect(0,0,W,H);
    for(var i=0;i<parts.length;i++){
      var p=parts[i];
      p.y+=p.vy; p.x+=p.vx; p.tw+=0.02;
      if(p.y<-12){p.y=H+12;p.x=Math.random()*W;}
      if(p.x<-12)p.x=W+12;
      if(p.x>W+12)p.x=-12;
      var a=p.a*(0.6+0.4*Math.sin(p.tw));
      x.beginPath(); x.arc(p.x,p.y,p.r,0,Math.PI*2);
      x.fillStyle = p.gold ? 'rgba(227,189,106,'+a+')' : 'rgba(232,138,169,'+a+')';
      x.fill();
    }
    requestAnimationFrame(frame);
  }
  if(!reduce) frame();
})();

/* ---------- الستارة ---------- */
(function(){
  var cur=document.getElementById('curtain'), nav=document.getElementById('nav');
  var done=false;
  function open(){
    if(done)return; done=true;
    cur.classList.add('gone');
    setTimeout(function(){ cur.style.display='none'; },1300);
    setTimeout(function(){ nav.classList.add('show'); },1500);
  }
  cur.addEventListener('click',open);
  addEventListener('keydown',open);
  setTimeout(open,3200);
})();

/* ---------- ظهور الأقسام ---------- */
(function(){
  var items=document.querySelectorAll('.reveal');
  if(!('IntersectionObserver' in window)){
    for(var i=0;i<items.length;i++) items[i].classList.add('in');
    return;
  }
  var io=new IntersectionObserver(function(es){
    es.forEach(function(e,k){
      if(e.isIntersecting){
        setTimeout(function(){ e.target.classList.add('in'); },(k%4)*110);
        io.unobserve(e.target);
      }
    });
  },{threshold:0.12,rootMargin:'0px 0px -50px 0px'});
  for(var j=0;j<items.length;j++) io.observe(items[j]);
})();

/* ---------- زر القلوب ---------- */
(function(){
  var btn=document.getElementById('love');
  var g=['❤','🤍','🌹','✦','💛','❦'], count=0;
  btn.addEventListener('click',function(){
    for(var i=0;i<34;i++){
      var el=document.createElement('span');
      el.textContent=g[Math.floor(Math.random()*g.length)];
      el.style.cssText='position:fixed;z-index:99;pointer-events:none;'+
        'left:'+(Math.random()*100)+'vw;top:'+(58+Math.random()*22)+'vh;'+
        'font-size:'+(14+Math.random()*26)+'px;opacity:1;will-change:transform,opacity;'+
        'transition:transform 2.4s cubic-bezier(.22,.62,.35,1),opacity 2.4s linear;';
      document.body.appendChild(el);
      (function(node){
        requestAnimationFrame(function(){
          node.style.transform='translate('+((Math.random()-.5)*460)+'px,'+
            (-320-Math.random()*520)+'px) rotate('+((Math.random()-.5)*700)+'deg)';
          node.style.opacity='0';
        });
        setTimeout(function(){ node.remove(); },2600);
      })(el);
    }
    count++;
    if(count===1) btn.textContent='وألف قلب أيضًا ❤';
    if(count===2) btn.textContent='قلبي كله لها 🤍';
    if(count>=3)  btn.textContent='دريسية… لا يكفيها شيء ❦';
  });
})();
</script>
</body>
