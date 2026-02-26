<!doctype html>
<html lang="ja">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>福岡の地しょうゆ診断｜QRレコメンド（1ファイル版）</title>
  <style>
    :root{
      --bg:#0b0f19;
      --card:#121a2a;
      --muted:#aab7d1;
      --text:#eef3ff;

      /* ===== 紅梅色（こうばいいろ） ===== */
      --accent:#f2a0a1;
      --accent2:#f2a0a1;

      --warn:#ffcc66;
      --danger:#ff6b6b;
      --ok:#69db7c;
      --border:rgba(255,255,255,.10);
      --shadow: 0 14px 35px rgba(0,0,0,.35);
      --radius: 18px;
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      font-family: ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Hiragino Kaku Gothic ProN", "Noto Sans JP", "Yu Gothic", "Meiryo", sans-serif;
      background: radial-gradient(1000px 700px at 20% 10%, rgba(242,160,161,.22), transparent 60%),
                  radial-gradient(900px 650px at 85% 20%, rgba(242,160,161,.16), transparent 55%),
                  radial-gradient(900px 650px at 30% 90%, rgba(255,204,102,.10), transparent 60%),
                  var(--bg);
      color:var(--text);
      line-height:1.55;
    }
    a{color:inherit}
    .wrap{max-width:1100px;margin:0 auto;padding:26px 16px 60px}
    header{
      display:flex; gap:14px; align-items:flex-start; justify-content:space-between;
      margin: 8px 0 18px;
    }
    .brand{
      display:flex; gap:12px; align-items:center;
    }
    .logo{
      width:44px;height:44px;border-radius:14px;
      background: linear-gradient(135deg, rgba(242,160,161,.98), rgba(242,160,161,.75));
      box-shadow: 0 12px 25px rgba(0,0,0,.25);
      position:relative;
      overflow:hidden;
    }
    .logo:after{
      content:""; position:absolute; inset:-18px;
      background: radial-gradient(circle at 35% 35%, rgba(255,255,255,.55), transparent 45%);
      transform: rotate(20deg);
    }
    h1{margin:0;font-size:22px;letter-spacing:.02em}
    .sub{margin:4px 0 0;color:var(--muted);font-size:13px}
    .pill{
      display:inline-flex;align-items:center; gap:8px;
      padding:10px 12px;border:1px solid var(--border);
      border-radius:999px;background:rgba(255,255,255,.04);
      font-size:12px;color:var(--muted);
      box-shadow: 0 10px 20px rgba(0,0,0,.18);
      user-select:none;
      min-width: 260px;
    }
    .grid{
      display:grid;
      grid-template-columns: 1.2fr .8fr;
      gap:16px;
      align-items:start;
    }
    @media (max-width: 920px){
      .grid{grid-template-columns:1fr}
      header{flex-direction:column;align-items:flex-start}
      .pill{min-width: 0; width: 100%;}
    }
    .card{
      background: linear-gradient(180deg, rgba(255,255,255,.06), rgba(255,255,255,.03));
      border:1px solid var(--border);
      border-radius: var(--radius);
      box-shadow: var(--shadow);
      overflow:hidden;
    }
    .card .hd{
      padding:16px 16px 10px;
      border-bottom:1px solid var(--border);
      display:flex; align-items:center; justify-content:space-between; gap:10px;
    }
    .card .bd{padding:16px}
    .tag{
      font-size:12px;color:var(--muted);
      border:1px solid var(--border);
      padding:6px 10px;border-radius:999px;
      background:rgba(0,0,0,.18);
      white-space: nowrap;
    }
    .progress{
      height:8px;border-radius:99px;background:rgba(255,255,255,.07);
      overflow:hidden;flex:1;
    }
    .progress > div{
      height:100%; width:0%;
      background: linear-gradient(90deg, var(--accent), var(--accent2));
      transition: width .35s ease;
    }
    .qtitle{
      font-size:16px;margin:0 0 10px;
    }
    .qdesc{
      margin:0 0 14px;color:var(--muted);font-size:13px
    }
    .choices{
      display:grid; gap:10px;
    }
    .choice{
      display:flex; align-items:flex-start; gap:12px;
      padding:12px 12px;
      border:1px solid var(--border);
      border-radius: 14px;
      background: rgba(0,0,0,.14);
      cursor:pointer;
      transition: transform .08s ease, background .2s ease, border-color .2s ease;
    }
    .choice:hover{transform: translateY(-1px); background: rgba(255,255,255,.06); border-color: rgba(255,255,255,.16)}
    .radio{
      margin-top:2px;
      width:18px;height:18px;border-radius:999px;
      border:2px solid rgba(255,255,255,.35);
      display:grid;place-items:center; flex:0 0 auto;
    }
    .radio:after{
      content:""; width:10px;height:10px;border-radius:999px;
      background: linear-gradient(135deg, var(--accent), var(--accent2));
      transform: scale(0);
      transition: transform .16s ease;
    }
    .choice[data-selected="true"]{border-color: rgba(242,160,161,.60); background: rgba(242,160,161,.10)}
    .choice[data-selected="true"] .radio{border-color: rgba(242,160,161,.85)}
    .choice[data-selected="true"] .radio:after{transform: scale(1)}
    .ctas{
      display:flex; gap:10px; flex-wrap:wrap;
      margin-top:14px;
    }
    button{
      border:0; cursor:pointer;
      padding:11px 12px; border-radius: 12px;
      font-weight:600; letter-spacing:.02em;
      background: rgba(255,255,255,.08);
      color:var(--text);
      border:1px solid var(--border);
      transition: transform .08s ease, background .2s ease, border-color .2s ease;
    }
    button:hover{transform: translateY(-1px); background: rgba(255,255,255,.12); border-color: rgba(255,255,255,.18)}
    button.primary{
      background: linear-gradient(135deg, rgba(242,160,161,.96), rgba(242,160,161,.78));
      color:#101018; border:0;
    }
    button.primary:hover{filter: brightness(1.03)}
    button.danger{background: rgba(255,107,107,.10); border-color: rgba(255,107,107,.28)}
    button:disabled{opacity:.5; cursor:not-allowed; transform:none}
    .small{font-size:12px;color:var(--muted)}
    .divider{height:1px;background:var(--border);margin:14px 0}
    .result{display:none;}
    .result.show{display:block}
    .scorebar{
      height:10px;border-radius:99px;background:rgba(255,255,255,.07);
      overflow:hidden;margin:8px 0 6px;
    }
    .scorebar > div{height:100%;width:0%;background: linear-gradient(90deg, var(--accent2), var(--accent))}
    .kpi{
      display:flex; gap:10px; flex-wrap:wrap;
      margin-top:10px;
    }
    .kpi .item{
      flex:1 1 130px;
      padding:10px 12px;border:1px solid var(--border);
      border-radius:14px;background:rgba(0,0,0,.14)
    }
    .kpi .item .label{font-size:11px;color:var(--muted)}
    .kpi .item .val{font-size:14px;font-weight:700;margin-top:2px}
    .reco{
      margin-top:12px;
      display:grid; gap:10px;
    }
    .reco .box{
      padding:12px 12px;border-radius:14px;
      border:1px solid var(--border);
      background: rgba(255,255,255,.04);
    }
    .reco h3{margin:0 0 6px;font-size:14px}
    .reco p{margin:0;color:var(--muted);font-size:13px}
    .links{
      display:grid; gap:8px; margin-top:12px;
    }
    .link{
      display:flex; align-items:center; justify-content:space-between; gap:10px;
      padding:10px 12px;
      border:1px solid var(--border);
      border-radius:14px;
      background: rgba(0,0,0,.14);
      text-decoration:none;
    }
    .link:hover{background: rgba(255,255,255,.06); border-color: rgba(255,255,255,.16)}
    .link .meta{display:flex; flex-direction:column; gap:2px}
    .link .meta .t{font-weight:700;font-size:13px}
    .link .meta .s{font-size:11px;color:var(--muted)}
    .arrow{opacity:.6}
    .toast{
      position:fixed; left:50%; bottom:18px; transform:translateX(-50%);
      padding:10px 12px;border-radius:999px;
      background: rgba(0,0,0,.65);
      border:1px solid rgba(255,255,255,.16);
      color:var(--text);
      box-shadow: 0 10px 20px rgba(0,0,0,.35);
      font-size:12px;
      display:none;
      z-index:9999;
    }
    .toast.show{display:block}
    .footer{
      margin-top:18px;color:var(--muted);font-size:12px
    }
    .mono{font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;}
    .note{
      padding:12px 12px;border-radius:14px;border:1px dashed rgba(255,255,255,.18);
      background: rgba(255,255,255,.03);
      color:var(--muted);font-size:12px
    }

    /* ===== 横展開カード（ブランド紹介） ===== */
    .brandRowTitle{margin: 12px 0 10px; font-size:14px}
    .brandRow{
      display:flex; gap:12px;
      overflow-x:auto;
      padding: 2px 0 8px;
      scroll-snap-type:x mandatory;
    }
    .brandCard{
      min-width: 340px;
      scroll-snap-align:start;
      border:1px solid rgba(255,255,255,.12);
      border-radius:16px;
      background: rgba(0,0,0,.14);
      padding:12px;
    }
    .brandTop{
      display:flex; gap:12px; align-items:flex-start; justify-content:space-between;
    }
    .brandName{font-weight:800; font-size:14px; margin:0}
    .brandSub{font-size:12px; color:var(--muted); margin:2px 0 0}
    .brandGrid{
      display:grid;
      grid-template-columns: 180px 1fr;
      gap:10px;
      margin-top:10px;
    }
    canvas.radar{width:180px;height:180px; border-radius:12px}
    .brandQuote{
      border:1px dashed rgba(255,255,255,.18);
      border-radius:14px;
      padding:10px;
      font-size:12px;
      color:var(--muted);
      background: rgba(255,255,255,.03);
    }
    .brandBtn{
      display:flex; align-items:center; justify-content:space-between; gap:10px;
      margin-top:10px;
      padding:10px 12px;
      border-radius:14px;
      border:1px solid rgba(255,255,255,.12);
      text-decoration:none;
      color:inherit;
      background: rgba(0,0,0,.12);
    }
    .brandBtn:hover{background: rgba(255,255,255,.06); border-color: rgba(255,255,255,.18)}
    .brandBtn .t{font-weight:800;font-size:13px}
    .brandBtn .s{font-size:11px;color:var(--muted)}
  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <div class="brand">
        <div class="logo" aria-hidden="true"></div>
        <div>
          <h1>福岡の地しょうゆ診断 <span class="tag">QRでレコメンド</span></h1>
          <div class="sub">1ファイル完結プロトタイプ｜質問に答えるだけで “合いそうな醤油タイプ” と使い方を提案します。</div>
        </div>
      </div>
      <div class="pill">
        <span>進行状況</span>
        <div class="progress" aria-label="progress"><div id="bar"></div></div>
        <span id="stepText" class="mono">0/4</span>
      </div>
    </header>

    <div class="grid">
      <!-- Quiz -->
      <section class="card" aria-label="diagnosis">
        <div class="hd">
          <div style="display:flex;flex-direction:column;gap:2px">
            <strong>かんたん診断（約30秒）</strong>
            <span class="small">回答を選ぶと自動で次へ。戻って修正もできます。</span>
          </div>
          <span class="tag" id="modeTag">試作版</span>
        </div>

        <div class="bd">
          <div id="quiz"></div>

          <div class="ctas">
            <button id="backBtn">戻る</button>
            <button id="resetBtn" class="danger">最初から</button>
          </div>

          <div class="divider"></div>

          <div class="note">
            <div><strong>メモ：</strong>このページはサンプルです。商品データは “タイプ” 単位で仮置きしています（後で組合商品に差し替え可）。</div>
          </div>
        </div>
      </section>

      <!-- Result / Links -->
      <aside class="card" aria-label="result">
        <div class="hd">
          <strong>診断結果</strong>
          <span class="tag" id="statusTag">未回答</span>
        </div>
        <div class="bd">
          <div id="result" class="result">
            <h2 style="margin:0 0 6px;font-size:18px" id="resultTitle">—</h2>
            <div class="small" id="resultLead">—</div>

            <div class="scorebar" aria-label="score">
              <div id="scoreFill"></div>
            </div>
            <div class="small">一致度：<span class="mono" id="scoreText">—</span></div>

            <div class="kpi" id="kpis"></div>

            <div class="reco" id="reco"></div>

            <div class="ctas">
              <button class="primary" id="copyBtn">結果をコピー</button>
              <button id="shareHintBtn">共有ヒント</button>
            </div>

            <div class="divider"></div>

            <div class="links">
              <a class="link" href="https://www.fsjk.or.jp/product/" target="_blank" rel="noopener">
                <div class="meta">
                  <div class="t">組合販売の商品一覧（参考）</div>
                  <div class="s">商品情報の差し替え元として想定</div>
                </div>
                <span class="arrow">↗</span>
              </a>
              <a class="link" href="https://www.pref.fukuoka.lg.jp/contents/smasol-shoyu-hanbaiten.html" target="_blank" rel="noopener">
                <div class="meta">
                  <div class="t">福岡県｜地しょうゆ販売店（参考）</div>
                  <div class="s">オフライン導線の候補</div>
                </div>
                <span class="arrow">↗</span>
              </a>
              <a class="link" href="https://fukuoka-as.jp" target="_blank" rel="noopener">
                <div class="meta">
                  <div class="t">Fukuoka AS（参考）</div>
                  <div class="s">地域情報・連携の導線</div>
                </div>
                <span class="arrow">↗</span>
              </a>
            </div>

            <!-- ===== 横展開（ブランド紹介） ===== -->
            <div class="divider"></div>
            <h3 class="brandRowTitle">地域ブランド（横スクロール）</h3>
            <div id="brandRow" class="brandRow"></div>

            <div class="footer">
              <div>※リンクは参考。後で「QR→商品別ページ」へ差し替えられる想定。</div>
            </div>
          </div>

          <div id="empty" class="small" style="color:var(--muted)">
            右側に結果が表示されます。まずは左で質問に答えてください。
          </div>
        </div>
      </aside>
    </div>
  </div>

  <div class="toast" id="toast" role="status" aria-live="polite"></div>

  <script>
    // --- Simple one-file diagnosis prototype ---
    const QUESTIONS = [
      {
        id: "use",
        title: "① 何に使いたい？",
        desc: "一番よく使う用途を選んでください。",
        choices: [
          { key: "cook", label: "普段の料理（煮物・炒め物など）", score: { rich: 2, mild: 1, umami: 2, sweet: 1 } },
          { key: "dip",  label: "つけ・かけ（刺身/冷奴/納豆など）", score: { rich: 1, mild: 2, umami: 2, sweet: 1 } },
          { key: "marinade", label: "漬け込み・下味（唐揚げ/焼き鳥など）", score: { rich: 2, mild: 1, umami: 3, sweet: 1 } },
          { key: "sauce", label: "タレ・ソース作り（照り焼き/丼など）", score: { rich: 2, mild: 1, umami: 2, sweet: 3 } },
        ]
      },
      {
        id: "taste",
        title: "② 好みの味は？",
        desc: "近いものを選んでください。",
        choices: [
          { key: "deep", label: "コク重視（濃いめが好き）", score: { rich: 4, mild: 0, umami: 2, sweet: 0 } },
          { key: "light", label: "軽さ重視（あっさりが好き）", score: { rich: 0, mild: 4, umami: 1, sweet: 0 } },
          { key: "umami", label: "だし感/旨味重視", score: { rich: 1, mild: 1, umami: 4, sweet: 0 } },
          { key: "sweet", label: "甘めが好き（九州っぽい）", score: { rich: 1, mild: 0, umami: 1, sweet: 4 } },
        ]
      },
      {
        id: "salt",
        title: "③ 塩分はどうしたい？",
        desc: "体調や家族の事情も含めて選んでください。",
        choices: [
          { key: "normal", label: "気にしない（標準でOK）", score: { rich: 1, mild: 1, umami: 1, sweet: 1 } },
          { key: "less", label: "できれば控えめが良い", score: { rich: 0, mild: 2, umami: 2, sweet: 1 } },
          { key: "strong", label: "しっかり塩味が欲しい", score: { rich: 2, mild: 0, umami: 2, sweet: 0 } },
        ]
      },
      {
        id: "scene",
        title: "④ どんな食材が多い？",
        desc: "よく食べるものに近いものを選んでください。",
        choices: [
          { key: "fish", label: "魚・刺身が多い", score: { rich: 1, mild: 2, umami: 2, sweet: 1 } },
          { key: "meat", label: "肉が多い", score: { rich: 2, mild: 0, umami: 2, sweet: 2 } },
          { key: "veg",  label: "野菜・豆腐が多い", score: { rich: 0, mild: 2, umami: 2, sweet: 1 } },
          { key: "all",  label: "なんでも（バランス）", score: { rich: 1, mild: 1, umami: 2, sweet: 1 } },
        ]
      }
    ];

    const PROFILES = [
      {
        id: "UMAMI",
        name: "だし旨・万能タイプ",
        lead: "だし感/旨味が合いそう。煮物もつけかけも、幅広く使えるタイプです。",
        match: (s)=> s.umami*1.15 + s.mild*0.35,
        kpis: [
          { label:"おすすめ用途", val:"煮物/炒め物/冷奴" },
          { label:"相性食材", val:"豆腐・野菜・魚" },
          { label:"味の方向性", val:"旨味・まろやか" }
        ],
        recos: [
          { t:"使い方", p:"まずは「大さじ1」を基準に。だし感があるので、みりんは少なめでもまとまりやすい。" },
          { t:"簡単レシピ", p:"豆腐にかけて、刻みねぎ＋生姜。好みでごま油を数滴。" }
        ],
        tips: "（後で）組合商品の“だし入り/旨味系”に紐付け"
      },
      {
        id: "RICH",
        name: "コク深・濃厚タイプ",
        lead: "濃いめが好きならこれ。肉や炒め物、照り焼きが決まりやすいタイプです。",
        match: (s)=> s.rich*1.2 + s.umami*0.6,
        kpis: [
          { label:"おすすめ用途", val:"照り焼き/炒め物" },
          { label:"相性食材", val:"肉・きのこ" },
          { label:"味の方向性", val:"コク・香ばしさ" }
        ],
        recos: [
          { t:"使い方", p:"加熱すると香りが立つので、炒め物は最後に回しかけると◎" },
          { t:"簡単レシピ", p:"鶏ももに醤油＋酒＋生姜で下味→焼くだけ。" }
        ],
        tips: "（後で）木桶/熟成系など“コク系”商品に紐付け"
      },
      {
        id: "MILD",
        name: "あっさり・軽やかタイプ",
        lead: "軽さ重視の人向け。つけかけでも重くなりにくいタイプです。",
        match: (s)=> s.mild*1.25 + s.umami*0.55,
        kpis: [
          { label:"おすすめ用途", val:"刺身/冷奴/納豆" },
          { label:"相性食材", val:"魚・豆腐" },
          { label:"味の方向性", val:"すっきり・後味" }
        ],
        recos: [
          { t:"使い方", p:"つけかけ中心なら“少量でも伸びる”ので、出しすぎ注意。" },
          { t:"簡単レシピ", p:"刺身は醤油＋柑橘（すだち等）でさっぱり。" }
        ],
        tips: "（後で）淡口・再仕込み以外の軽やか系に紐付け"
      },
      {
        id: "SWEET",
        name: "甘め・九州テイストタイプ",
        lead: "甘め好きに刺さるタイプ。丼・照り焼き・タレ作りが楽になります。",
        match: (s)=> s.sweet*1.25 + s.rich*0.6,
        kpis: [
          { label:"おすすめ用途", val:"丼/照り焼き/タレ" },
          { label:"相性食材", val:"肉・卵・米" },
          { label:"味の方向性", val:"甘み・コク" }
        ],
        recos: [
          { t:"使い方", p:"砂糖やみりんを足しすぎると甘くなりすぎるので、まずは醤油だけで味見。" },
          { t:"簡単レシピ", p:"卵かけご飯に少量。追いでバター一片で背徳うまい。" }
        ],
        tips: "（後で）“九州甘口”商品やタレ系に紐付け"
      }
    ];

    const state = {
      step: 0,
      answers: {}, // qid -> choice key
      score: { rich:0, mild:0, umami:0, sweet:0 }
    };

    const el = (id)=> document.getElementById(id);
    const quizEl = el("quiz");
    const backBtn = el("backBtn");
    const resetBtn = el("resetBtn");
    const bar = el("bar");
    const stepText = el("stepText");
    const resultBox = el("result");
    const emptyBox = el("empty");
    const statusTag = el("statusTag");
    const resultTitle = el("resultTitle");
    const resultLead = el("resultLead");
    const scoreFill = el("scoreFill");
    const scoreText = el("scoreText");
    const kpisEl = el("kpis");
    const recoEl = el("reco");
    const copyBtn = el("copyBtn");
    const shareHintBtn = el("shareHintBtn");
    const toast = el("toast");

    function showToast(msg){
      toast.textContent = msg;
      toast.classList.add("show");
      clearTimeout(showToast._t);
      showToast._t = setTimeout(()=> toast.classList.remove("show"), 2200);
    }

    function computeScores(){
      state.score = { rich:0, mild:0, umami:0, sweet:0 };
      for(const q of QUESTIONS){
        const picked = state.answers[q.id];
        if(!picked) continue;
        const c = q.choices.find(x=>x.key===picked);
        if(!c) continue;
        for(const k of Object.keys(state.score)){
          state.score[k] += (c.score[k]||0);
        }
      }
    }

    function bestProfile(){
      computeScores();
      let best = null;
      let bestVal = -Infinity;
      for(const p of PROFILES){
        const v = p.match(state.score);
        if(v>bestVal){bestVal=v; best=p;}
      }
      const total = state.score.rich+state.score.mild+state.score.umami+state.score.sweet;
      const maxPossible = 4*4;
      const pct = Math.min(98, Math.max(45, Math.round((total/(maxPossible))*100 + (bestVal%7))));
      return {profile:best, pct};
    }

    function progress(){
      const done = Object.keys(state.answers).length;
      const total = QUESTIONS.length;
      const pct = Math.round((done/total)*100);
      bar.style.width = pct + "%";
      stepText.textContent = done + "/" + total;
      backBtn.disabled = state.step===0;
      statusTag.textContent = done===0 ? "未回答" : (done<total ? "途中" : "完了");
      el("modeTag").textContent = done<total ? "試作版" : "結果表示中";
    }

    function render(){
      progress();
      const total = QUESTIONS.length;
      if(state.step < total){
        const q = QUESTIONS[state.step];
        const picked = state.answers[q.id];

        quizEl.innerHTML = `
          <h2 class="qtitle">${q.title}</h2>
          <p class="qdesc">${q.desc}</p>
          <div class="choices">
            ${q.choices.map(c=>`
              <div class="choice" data-key="${c.key}" data-selected="${picked===c.key}">
                <div class="radio" aria-hidden="true"></div>
                <div>
                  <div style="font-weight:700">${c.label}</div>
                </div>
              </div>
            `).join("")}
          </div>
        `;

        [...quizEl.querySelectorAll(".choice")].forEach(node=>{
          node.addEventListener("click", ()=>{
            const k = node.getAttribute("data-key");
            state.answers[q.id]=k;
            if(state.step < total-1) state.step += 1;
            else state.step = total;
            render();
          });
        });

        resultBox.classList.remove("show");
        emptyBox.style.display="block";
      } else {
        const {profile, pct} = bestProfile();
        emptyBox.style.display="none";
        resultBox.classList.add("show");
        resultTitle.textContent = profile.name;
        resultLead.textContent = profile.lead;
        scoreFill.style.width = pct + "%";
        scoreText.textContent = pct + "%";

        kpisEl.innerHTML = profile.kpis.map(x=>`
          <div class="item">
            <div class="label">${x.label}</div>
            <div class="val">${x.val}</div>
          </div>
        `).join("");

        const s = state.score;
        const traits = [
          {k:"旨味", v:s.umami},
          {k:"コク", v:s.rich},
          {k:"軽さ", v:s.mild},
          {k:"甘み", v:s.sweet},
        ].sort((a,b)=>b.v-a.v);

        recoEl.innerHTML = `
          <div class="box">
            <h3>あなたの傾向</h3>
            <p>上位：<strong>${traits[0].k}</strong> / 次点：<strong>${traits[1].k}</strong></p>
            <p class="small" style="margin-top:6px">スコア：旨味 ${s.umami}｜コク ${s.rich}｜軽さ ${s.mild}｜甘み ${s.sweet}</p>
          </div>
          ${profile.recos.map(r=>`
            <div class="box">
              <h3>${r.t}</h3>
              <p>${r.p}</p>
            </div>
          `).join("")}
          <div class="box">
            <h3>運用メモ（組合向け）</h3>
            <p>${profile.tips}</p>
          </div>
        `;

        quizEl.innerHTML = `
          <h2 class="qtitle">診断完了</h2>
          <p class="qdesc">回答内容を確認・修正できます（右の結果も即更新）。</p>
          ${QUESTIONS.map((q,i)=>{
            const picked = state.answers[q.id];
            const label = q.choices.find(x=>x.key===picked)?.label ?? "—";
            return `
              <div class="choice" data-jump="${i}">
                <div class="radio" aria-hidden="true" style="border-color:rgba(255,255,255,.20)"></div>
                <div>
                  <div style="font-weight:800;font-size:12px;color:var(--muted)">${q.title}</div>
                  <div style="font-weight:700">${label}</div>
                </div>
              </div>
            `;
          }).join("")}
          <div class="small" style="margin-top:10px;color:var(--muted)">↑ クリックでその質問に戻れます</div>
        `;

        [...quizEl.querySelectorAll(".choice[data-jump]")].forEach(node=>{
          node.addEventListener("click", ()=>{
            state.step = parseInt(node.getAttribute("data-jump"),10);
            render();
          });
        });
      }
    }

    backBtn.addEventListener("click", ()=>{
      if(state.step>0) state.step -= 1;
      render();
    });

    resetBtn.addEventListener("click", ()=>{
      state.step = 0;
      state.answers = {};
      state.score = { rich:0, mild:0, umami:0, sweet:0 };
      render();
      showToast("リセットしました");
    });

    copyBtn.addEventListener("click", async ()=>{
      const {profile, pct} = bestProfile();
      const s = state.score;
      const text = [
        "【福岡の地しょうゆ診断｜結果】",
        `タイプ：${profile.name}`,
        `一致度：${pct}%`,
        `スコア：旨味${s.umami} / コク${s.rich} / 軽さ${s.mild} / 甘み${s.sweet}`,
        "",
        "（メモ）これはプロトタイプです。"
      ].join("\n");

      try{
        await navigator.clipboard.writeText(text);
        showToast("コピーしました");
      }catch(e){
        const ta = document.createElement("textarea");
        ta.value = text;
        document.body.appendChild(ta);
        ta.select();
        document.execCommand("copy");
        ta.remove();
        showToast("コピーしました（fallback）");
      }
    });

    shareHintBtn.addEventListener("click", ()=>{
      showToast("共有するなら：GitHub Pages のURLを送るだけでOK");
    });

    // ===== 横展開（ブランドカード）データ（2件）=====
    // 5軸：旨味 / 甘味 / 塩味 / 酸味 / 苦味（0〜5）
    const BRANDS = [
      {
        brandName: "オガワーマン",
        breweryName: "小川隼空",
        quote: "甘党な私だからこそたどり着けた甘さがここにあります。どうぞお楽しみください。",
        scores: { umami: 4.2, sweet: 4.6, salty: 2.2, sour: 1.4, bitter: 1.0 },
        stampText: "小川",
        url: "https://www.fsjk.or.jp/product/"
      },
      {
        brandName: "モロミちゃん",
        breweryName: "福醤モロミ",
        quote: "旨みで、毎日のごはんがちょっと楽しくなる味。",
        scores: { umami: 4.6, sweet: 2.6, salty: 2.4, sour: 1.2, bitter: 0.8 },
        stampText: "福醤",
        url: "https://www.fsjk.or.jp/product/"
      },
    ];

    function stampSVG(text){
      const safe = (text || "").slice(0,2);
      return `
        <svg width="58" height="58" viewBox="0 0 58 58" xmlns="http://www.w3.org/2000/svg" aria-label="stamp">
          <path d="M29 2 L50 11 L56 29 L50 47 L29 56 L8 47 L2 29 L8 11 Z"
            fill="rgba(0,0,0,.10)" stroke="rgba(255,255,255,.35)" stroke-width="2"/>
          <circle cx="29" cy="29" r="18" fill="rgba(255,255,255,.03)" stroke="rgba(242,160,161,.95)" stroke-width="2"/>
          <text x="29" y="34" text-anchor="middle" font-size="18" font-weight="800"
            fill="rgba(242,160,161,.98)" font-family="ui-sans-serif, system-ui">${safe}</text>
        </svg>`;
    }

    function drawRadar(canvas, scores){
      const ctx = canvas.getContext("2d");
      const size = 180;
      const dpr = window.devicePixelRatio || 1;
      canvas.width = size * dpr;
      canvas.height = size * dpr;
      canvas.style.width = size + "px";
      canvas.style.height = size + "px";
      ctx.scale(dpr, dpr);

      const cx = size/2, cy = size/2;
      const R = 70;
      const axes = [
        {key:"umami",  label:"旨味"},
        {key:"salty",  label:"塩味"},
        {key:"sweet",  label:"甘味"},
        {key:"sour",   label:"酸味"},
        {key:"bitter", label:"苦味"},
      ];

      ctx.clearRect(0,0,size,size);

      ctx.strokeStyle = "rgba(255,255,255,.18)";
      ctx.lineWidth = 1;
      for(let lv=1; lv<=5; lv++){
        const r = (R*lv)/5;
        ctx.beginPath();
        axes.forEach((a,i)=>{
          const ang = (-Math.PI/2) + (i*(2*Math.PI/axes.length));
          const x = cx + r*Math.cos(ang);
          const y = cy + r*Math.sin(ang);
          if(i===0) ctx.moveTo(x,y); else ctx.lineTo(x,y);
        });
        ctx.closePath();
        ctx.stroke();
      }

      axes.forEach((a,i)=>{
        const ang = (-Math.PI/2) + (i*(2*Math.PI/axes.length));
        const x = cx + R*Math.cos(ang);
        const y = cy + R*Math.sin(ang);
        ctx.beginPath();
        ctx.moveTo(cx,cy);
        ctx.lineTo(x,y);
        ctx.stroke();

        ctx.fillStyle = "rgba(255,255,255,.78)";
        ctx.font = "11px ui-sans-serif, system-ui";
        const lx = cx + (R+18)*Math.cos(ang);
        const ly = cy + (R+18)*Math.sin(ang);
        ctx.textAlign = (Math.abs(Math.cos(ang))<0.2) ? "center" : (Math.cos(ang)>0 ? "left":"right");
        ctx.textBaseline = (Math.abs(Math.sin(ang))<0.2) ? "middle" : (Math.sin(ang)>0 ? "top":"bottom");
        ctx.fillText(a.label, lx, ly);
      });

      const max = 5;
      ctx.fillStyle = "rgba(242,160,161,.22)";
      ctx.strokeStyle = "rgba(242,160,161,.95)";
      ctx.lineWidth = 2;

      ctx.beginPath();
      axes.forEach((a,i)=>{
        const v = Math.max(0, Math.min(max, scores[a.key] ?? 0));
        const r = (R * v)/max;
        const ang = (-Math.PI/2) + (i*(2*Math.PI/axes.length));
        const x = cx + r*Math.cos(ang);
        const y = cy + r*Math.sin(ang);
        if(i===0) ctx.moveTo(x,y); else ctx.lineTo(x,y);
      });
      ctx.closePath();
      ctx.fill();
      ctx.stroke();
    }

    function renderBrandRow(){
      const row = document.getElementById("brandRow");
      if(!row) return;

      row.innerHTML = BRANDS.map((b, idx)=>`
        <div class="brandCard">
          <div class="brandTop">
            <div>
              <p class="brandName">[醤油蔵] ${b.brandName}</p>
              <p class="brandSub">[蔵元] ${b.breweryName}</p>
            </div>
            <div title="荷印">${stampSVG(b.stampText)}</div>
          </div>

          <div class="brandGrid">
            <canvas class="radar" id="radar_${idx}"></canvas>
            <div class="brandQuote">${b.quote}</div>
          </div>

          <a class="brandBtn" href="${b.url}" target="_blank" rel="noopener">
            <div>
              <div class="t">詳細を見る</div>
              <div class="s">外部リンク（仮）</div>
            </div>
            <span class="arrow">↗</span>
          </a>
        </div>
      `).join("");

      BRANDS.forEach((b, idx)=>{
        const c = document.getElementById(`radar_${idx}`);
        if(c) drawRadar(c, b.scores);
      });
    }

    // init
    render();
    renderBrandRow();
  </script>
</body>
</html>
