<html lang="ja">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>介護の基本 - 項目を選ぶ | 介護福祉士国家試験対策</title>
  
  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- Font Awesome 6.5.1 -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
  <!-- Google Fonts: Noto Sans JP -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+JP:wght@400;600;700;900&display=swap" rel="stylesheet">

  <style>
    /* 全体フォント設定 */
    body {
      font-family: 'Noto Sans JP', sans-serif;
      background-color: #f8fafc; /* オフホワイト背景 */
      color: #1e293b;
    }

    /* ルビ（フリガナ）の指定装飾 */
    ruby rt {
      font-size: 0.55em;
      font-weight: 700;
      color: #b91c1c; /* 濃い赤色 */
      line-height: 1.1;
      font-family: 'Noto Sans JP', sans-serif;
    }

    /* トランプ風ポップカードのスタイル */
    .pop-card {
      background-color: #ffffff;
      border: 3px solid #e2e8f0;
      border-radius: 20px;
      box-shadow: 0 8px 0px #cbd5e1, 0 12px 20px rgba(0,0,0,0.06);
      transition: all 0.2s cubic-bezier(0.34, 1.56, 0.64, 1);
    }

    .pop-card:hover {
      transform: translateY(-4px);
      box-shadow: 0 12px 0px #94a3b8, 0 18px 25px rgba(0,0,0,0.1);
      border-color: #3b82f6;
    }

    .pop-card:active {
      transform: translateY(2px);
      box-shadow: 0 4px 0px #cbd5e1, 0 6px 10px rgba(0,0,0,0.05);
    }

    /* ボタン共通スタイル */
    .btn-back {
      background-color: #ffffff;
      border: 2px solid #cbd5e1;
      border-radius: 12px;
      box-shadow: 0 4px 0 #cbd5e1;
      transition: all 0.15s ease;
    }

    .btn-back:hover {
      background-color: #f1f5f9;
      transform: translateY(-2px);
      box-shadow: 0 6px 0 #94a3b8;
    }

    .btn-back:active {
      transform: translateY(2px);
      box-shadow: 0 2px 0 #cbd5e1;
    }
  </style>
</head>
<body class="min-h-screen pb-16">

  <!-- ヘッダーエリア -->
  <header class="bg-white border-b-2 border-slate-200 sticky top-0 z-10 shadow-sm">
    <div class="max-w-5xl mx-auto px-4 py-4 flex items-center justify-between">
      <!-- トップページへ戻るボタン（確実に遷移する仕様） -->
      <a href="https://tktora-tigers.github.io/kaifuku-home/" class="btn-back px-4 py-2 text-slate-700 font-bold text-sm inline-flex items-center gap-2 decoration-none">
        <i class="fa-solid fa-arrow-left text-slate-500"></i>
        <span><ruby>単元一覧<rt>たんげんいちらん</rt></ruby>へ<ruby>戻<rt>もど</rt></ruby>る</span>
      </a>

      <!-- ページタイトル小ラベル -->
      <div class="text-right">
        <span class="bg-blue-100 text-blue-800 text-xs font-bold px-3 py-1 rounded-full inline-block">
          <ruby>介護<rt>かいご</rt></ruby>の<ruby>基本<rt>きほん</rt></ruby>
        </span>
      </div>
    </div>
  </header>

  <!-- メインコンテンツ -->
  <main class="max-w-5xl mx-auto px-4 pt-8">
    
    <!-- タイトルセクション -->
    <div class="text-center mb-8">
      <h1 class="text-2xl md:text-3xl font-black text-slate-800 tracking-wide mb-2">
        <ruby>学習<rt>がくしゅう</rt></ruby>する<ruby>項目<rt>こうもく</rt></ruby>を<ruby>選<rt>えら</rt></ruby>ぶ
      </h1>
      <p class="text-slate-600 text-sm md:text-base font-semibold">
        <ruby>得意<rt>とくい</rt></ruby>な<ruby>分野<rt>ぶんや</rt></ruby>や<ruby>苦手<rt>にがて</rt></ruby>な<ruby>テーマ<rt>テーマ</rt></ruby>を<ruby>ピンポイント<rt>ピンポイント</rt></ruby>で<ruby>練習<rt>れんしゅう</rt></ruby>できます。
      </p>
    </div>

    <!-- 小項目グリッド一覧 -->
    <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-4 gap-4 md:gap-6">

      <!-- 1. 麻痺 -->
      <a href="https://tktora-tigers.github.io/seikatusienn.sub/" class="pop-card p-5 flex flex-col items-center text-center group decoration-none">
        <div class="w-14 h-14 bg-red-100 text-red-600 rounded-2xl flex items-center justify-center text-2xl mb-3 group-hover:scale-110 transition-transform">
          <i class="fa-solid fa-wheelchair"></i>
        </div>
        <h2 class="text-lg font-black text-slate-800 mb-1">
          <ruby>麻痺<rt>まひ</rt></ruby>
        </h2>
        <p class="text-xs text-slate-500 font-semibold mt-auto">
          <ruby>片麻痺<rt>かたまひ</rt></ruby>・<ruby>体位変換<rt>たいいへんかん</rt></ruby>
        </p>
      </a>

      <!-- 2. 食事 -->
      <a href="kaigo_kihon.html?topic=shokuji" class="pop-card p-5 flex flex-col items-center text-center group decoration-none">
        <div class="w-14 h-14 bg-orange-100 text-orange-600 rounded-2xl flex items-center justify-center text-2xl mb-3 group-hover:scale-110 transition-transform">
          <i class="fa-solid fa-utensils"></i>
        </div>
        <h2 class="text-lg font-black text-slate-800 mb-1">
          <ruby>食事<rt>しょくじ</rt></ruby>
        </h2>
        <p class="text-xs text-slate-500 font-semibold mt-auto">
          <ruby>嚥下<rt>えんげ</rt></ruby>・<ruby>食事介助<rt>しょくじかいじょ</rt></ruby>
        </p>
      </a>

      <!-- 3. 生活支援 -->
      <a href="kaigo_kihon.html?topic=seikatsu" class="pop-card p-5 flex flex-col items-center text-center group decoration-none">
        <div class="w-14 h-14 bg-amber-100 text-amber-600 rounded-2xl flex items-center justify-center text-2xl mb-3 group-hover:scale-110 transition-transform">
          <i class="fa-solid fa-hand-holding-heart"></i>
        </div>
        <h2 class="text-lg font-black text-slate-800 mb-1">
          <ruby>生活支援<rt>せいかつしえん</rt></ruby>
        </h2>
        <p class="text-xs text-slate-500 font-semibold mt-auto">
          <ruby>自立支援<rt>じりつしえん</rt></ruby>・ICF
        </p>
      </a>

      <!-- 4. 住環境 -->
      <a href="kaigo_kihon.html?topic=jukankyo" class="pop-card p-5 flex flex-col items-center text-center group decoration-none">
        <div class="w-14 h-14 bg-emerald-100 text-emerald-600 rounded-2xl flex items-center justify-center text-2xl mb-3 group-hover:scale-110 transition-transform">
          <i class="fa-solid fa-house-user"></i>
        </div>
        <h2 class="text-lg font-black text-slate-800 mb-1">
          <ruby>住環境<rt>じゅうかんきょう</rt></ruby>
        </h2>
        <p class="text-xs text-slate-500 font-semibold mt-auto">
          手すり・バリアフリー
        </p>
      </a>

      <!-- 5. 移動 -->
      <a href="kaigo_kihon.html?topic=idou" class="pop-card p-5 flex flex-col items-center text-center group decoration-none">
        <div class="w-14 h-14 bg-teal-100 text-teal-600 rounded-2xl flex items-center justify-center text-2xl mb-3 group-hover:scale-110 transition-transform">
          <i class="fa-solid fa-person-walking"></i>
        </div>
        <h2 class="text-lg font-black text-slate-800 mb-1">
          <ruby>移動<rt>いどう</rt></ruby>
        </h2>
        <p class="text-xs text-slate-500 font-semibold mt-auto">
          杖・車いす・<ruby>移乗<rt>いじょう</rt></ruby>
        </p>
      </a>

      <!-- 6. 入浴 -->
      <a href="kaigo_kihon.html?topic=nyuyoku" class="pop-card p-5 flex flex-col items-center text-center group decoration-none">
        <div class="w-14 h-14 bg-cyan-100 text-cyan-600 rounded-2xl flex items-center justify-center text-2xl mb-3 group-hover:scale-110 transition-transform">
          <i class="fa-solid fa-bath"></i>
        </div>
        <h2 class="text-lg font-black text-slate-800 mb-1">
          <ruby>入浴<rt>にゅうよく</rt></ruby>
        </h2>
        <p class="text-xs text-slate-500 font-semibold mt-auto">
          <ruby>清拭<rt>せいしき</rt></ruby>・<ruby>手浴<rt>しゅよく</rt></ruby>・足浴
        </p>
      </a>

      <!-- 7. 排泄 -->
      <a href="kaigo_kihon.html?topic=haisetsu" class="pop-card p-5 flex flex-col items-center text-center group decoration-none">
        <div class="w-14 h-14 bg-blue-100 text-blue-600 rounded-2xl flex items-center justify-center text-2xl mb-3 group-hover:scale-110 transition-transform">
          <i class="fa-solid fa-toilet"></i>
        </div>
        <h2 class="text-lg font-black text-slate-800 mb-1">
          <ruby>排泄<rt>はいせつ</rt></ruby>
        </h2>
        <p class="text-xs text-slate-500 font-semibold mt-auto">
          ポータブルトイレ・おむつ
        </p>
      </a>

      <!-- 8. 睡眠 -->
      <a href="kaigo_kihon.html?topic=suimin" class="pop-card p-5 flex flex-col items-center text-center group decoration-none">
        <div class="w-14 h-14 bg-indigo-100 text-indigo-600 rounded-2xl flex items-center justify-center text-2xl mb-3 group-hover:scale-110 transition-transform">
          <i class="fa-solid fa-bed"></i>
        </div>
        <h2 class="text-lg font-black text-slate-800 mb-1">
          <ruby>睡眠<rt>すいみん</rt></ruby>
        </h2>
        <p class="text-xs text-slate-500 font-semibold mt-auto">
          <ruby>環境整え<rt>かんきょうをととのえ</rt></ruby>・リズム
        </p>
      </a>

      <!-- 9. 終末期 -->
      <a href="kaigo_kihon.html?topic=shumatsuki" class="pop-card p-5 flex flex-col items-center text-center group decoration-none">
        <div class="w-14 h-14 bg-purple-100 text-purple-600 rounded-2xl flex items-center justify-center text-2xl mb-3 group-hover:scale-110 transition-transform">
          <i class="fa-solid fa-heart-pulse"></i>
        </div>
        <h2 class="text-lg font-black text-slate-800 mb-1">
          <ruby>終末期<rt>しゅうまつき</rt></ruby>
        </h2>
        <p class="text-xs text-slate-500 font-semibold mt-auto">
          ターミナルケア・看取り
        </p>
      </a>

      <!-- 10. 身支度 -->
      <a href="kaigo_kihon.html?topic=mijitaku" class="pop-card p-5 flex flex-col items-center text-center group decoration-none">
        <div class="w-14 h-14 bg-pink-100 text-pink-600 rounded-2xl flex items-center justify-center text-2xl mb-3 group-hover:scale-110 transition-transform">
          <i class="fa-solid fa-shirt"></i>
        </div>
        <h2 class="text-lg font-black text-slate-800 mb-1">
          <ruby>身支度<rt>みじたく</rt></ruby>
        </h2>
        <p class="text-xs text-slate-500 font-semibold mt-auto">
          <ruby>着脱<rt>ちゃくだつ</rt></ruby>・<ruby>整容<rt>せいよう</rt></ruby>
        </p>
      </a>

      <!-- 11. 家事 -->
      <a href="kaigo_kihon.html?topic=kaji" class="pop-card p-5 flex flex-col items-center text-center group decoration-none">
        <div class="w-14 h-14 bg-rose-100 text-rose-600 rounded-2xl flex items-center justify-center text-2xl mb-3 group-hover:scale-110 transition-transform">
          <i class="fa-solid fa-jug-detergent"></i>
        </div>
        <h2 class="text-lg font-black text-slate-800 mb-1">
          <ruby>家事<rt>かじ</rt></ruby>
        </h2>
        <p class="text-xs text-slate-500 font-semibold mt-auto">
          <ruby>調理<rt>ちょうり</rt></ruby>・<ruby>洗濯<rt>せんたく</rt></ruby>・<ruby>掃除<rt>そうじ</rt></ruby>
        </p>
      </a>

      <!-- 12. 全体（総合） -->
      <a href="kaigo_kihon.html?topic=all" class="pop-card p-5 flex flex-col items-center text-center group decoration-none border-blue-300 bg-blue-50/50">
        <div class="w-14 h-14 bg-blue-600 text-white rounded-2xl flex items-center justify-center text-2xl mb-3 group-hover:scale-110 transition-transform shadow-md">
          <i class="fa-solid fa-layer-group"></i>
        </div>
        <h2 class="text-lg font-black text-blue-900 mb-1">
          すべての<ruby>問題<rt>もんだい</rt></ruby>
        </h2>
        <p class="text-xs text-blue-600 font-semibold mt-auto">
          <ruby>全項目<rt>ぜんこうもく</rt></ruby>から<ruby>出題<rt>しゅつだい</rt></ruby>
        </p>
      </a>

    </div>

    <!-- ページ下部の補足ボタン -->
    <div class="mt-12 text-center">
      <a href="https://tktora-tigers.github.io/kaifuku-home/" class="inline-flex items-center gap-2 text-slate-500 hover:text-slate-800 font-bold text-sm underline underline-offset-4 decoration-2 transition-colors">
        <i class="fa-solid fa-house"></i>
        <span>トップページ（<ruby>単元一覧<rt>たんげんいちらん</rt></ruby>）へ<ruby>戻<rt>もど</rt></ruby>る</span>
      </a>
    </div>

  </main>

</body>
</html>
