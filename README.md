<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>住まいナビ｜学校の近くのお部屋探し</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="top-notice">学生・新社会人のお部屋探しを応援！学校の近くから、ぴったりの住まいを見つけよう。</div>

  <header class="site-header">
    <a class="logo" href="#" aria-label="住まいナビ トップ">
      <span class="logo-mark">住</span>
      <span><strong>住まいナビ</strong><small>学校の近くのお部屋探し</small></span>
    </a>
    <nav class="main-nav" aria-label="メインメニュー">
      <a class="active" href="#rent">借りる</a>
      <a href="#buy">買う</a>
      <a href="#features">便利な機能</a>
      <a href="#guide">お部屋探しガイド</a>
    </nav>
    <div class="header-actions"><a href="#favorites">♡ お気に入り</a><button class="menu-button" aria-label="メニュー">☰</button></div>
  </header>

  <main>
    <section class="hero">
      <div class="hero-copy">
        <p class="eyebrow">YOUR NEW LIFE STARTS HERE</p>
        <h1>学校の近くに、<br><span>ちょうどいい暮らし。</span></h1>
        <p class="hero-text">通学距離・築年数・広さ・駐輪場まで。<br>あなたの希望に合わせて、かんたん検索。</p>
        <a class="hero-link" href="#search">理想のお部屋を探す <span>→</span></a>
      </div>
      <div class="hero-art" aria-label="家と街のイラスト">
        <div class="sun"></div><div class="cloud cloud-one"></div><div class="cloud cloud-two"></div>
        <div class="hill hill-back"></div><div class="hill hill-front"></div>
        <div class="house"><div class="roof"></div><div class="house-body"><div class="window"></div><div class="window second"></div><div class="door"></div></div></div>
        <div class="tree tree-one"><i></i><b></b></div><div class="tree tree-two"><i></i><b></b></div>
        <div class="path"></div>
      </div>
    </section>

    <section class="search-panel" id="search">
      <div class="section-heading">
        <div><p class="eyebrow red">FIND YOUR ROOM</p><h2>希望条件からお部屋を探す</h2></div>
        <p>条件を選んで「検索する」を押してください。</p>
      </div>
      <form class="search-form" action="#" method="get">
        <label class="field school-field"><span>学校名・駅名・エリア</span><input type="text" placeholder="例：横浜駅、〇〇専門学校"></label>
        <label class="field"><span>家賃</span><select><option>指定なし</option><option>5万円以下</option><option>5〜7万円</option><option>7〜9万円</option><option>9万円以上</option></select></label>
        <label class="field"><span>間取り</span><select><option>指定なし</option><option>ワンルーム</option><option>1K</option><option>1DK</option><option>1LDK以上</option></select></label>
        <label class="field"><span>学校までの距離</span><select><option>指定なし</option><option>徒歩5分以内</option><option>徒歩10分以内</option><option>自転車15分以内</option></select></label>
        <label class="field"><span>築年数</span><select><option>指定なし</option><option>新築</option><option>築5年以内</option><option>築10年以内</option><option>築20年以内</option></select></label>
        <label class="field"><span>部屋の広さ</span><select><option>指定なし</option><option>20㎡以上</option><option>25㎡以上</option><option>30㎡以上</option></select></label>
        <label class="check-field"><input type="checkbox"> 駐輪場あり</label>
        <button class="search-button" type="submit">⌕　この条件で検索</button>
      </form>
      <div class="quick-tags"><span>人気の条件：</span><a href="#search">家賃5万円以下</a><a href="#search">駅近</a><a href="#search">バス・トイレ別</a><a href="#search">家具・家電付き</a><a href="#search">学生向け</a></div>
    </section>

    <section class="categories" id="rent">
      <div class="section-heading"><div><p class="eyebrow red">CATEGORY</p><h2>住まいの種類から探す</h2></div><a class="text-link" href="#search">すべて見る →</a></div>
      <div class="category-grid">
        <a class="category-card rent-card" href="#search"><span class="category-icon">⌂</span><span><strong>賃貸</strong><small>マンション・アパート・一戸建て</small></span><b>→</b></a>
        <a class="category-card" href="#buy"><span class="emoji-icon">🏢</span><strong>マンション</strong><small>買う・借りる</small></a>
        <a class="category-card" href="#buy"><span class="emoji-icon">🏠</span><strong>一戸建て</strong><small>戸建て住宅</small></a>
        <a class="category-card" href="#buy"><span class="emoji-icon">🌳</span><strong>売土地</strong><small>土地を探す</small></a>
        <a class="category-card" href="#buy"><span class="emoji-icon">🛠️</span><strong>注文住宅</strong><small>家を建てる</small></a>
        <a class="category-card" href="#search"><span class="emoji-icon">🏪</span><strong>貸店舗</strong><small>店舗・事務所</small></a>
        <a class="category-card" href="#search"><span class="emoji-icon">🚗</span><strong>駐車場</strong><small>月極駐車場</small></a>
      </div>
    </section>

    <section class="features" id="features">
      <div class="section-heading"><div><p class="eyebrow red">SMART SEARCH</p><h2>ここが便利！こだわり検索</h2></div><p>学校生活にぴったりの条件をまとめてチェック。</p></div>
      <div class="feature-grid">
        <article class="feature-card"><span class="feature-number">01</span><div class="feature-icon">📍</div><h3>学校からの距離</h3><p>学校名を入力して、徒歩や自転車で通いやすい物件を探せます。</p></article>
        <article class="feature-card"><span class="feature-number">02</span><div class="feature-icon">🏗️</div><h3>築年数で選ぶ</h3><p>新築・築5年以内など、建物の新しさから絞り込めます。</p></article>
        <article class="feature-card"><span class="feature-number">03</span><div class="feature-icon">📐</div><h3>広さを比較</h3><p>部屋の面積を指定して、生活スタイルに合う広さを見つけます。</p></article>
        <article class="feature-card"><span class="feature-number">04</span><div class="feature-icon">🚲</div><h3>駐輪場あり</h3><p>自転車通学にうれしい駐輪場の有無も、検索条件に追加できます。</p></article>
      </div>
    </section>

    <section class="region-section">
      <div class="section-heading"><div><p class="eyebrow red">AREA SEARCH</p><h2>エリアから探す</h2></div><p>住みたい地域を選んで物件をチェック。</p></div>
      <div class="region-grid">
        <a href="#search">北海道・東北 <span>北海道　青森　宮城　福島</span> <b>→</b></a>
        <a href="#search">関東 <span>東京　神奈川　埼玉　千葉　茨城</span> <b>→</b></a>
        <a href="#search">中部 <span>愛知　静岡　新潟　長野　岐阜</span> <b>→</b></a>
        <a href="#search">関西 <span>大阪　京都　兵庫　奈良　滋賀</span> <b>→</b></a>
        <a href="#search">中国・四国 <span>広島　岡山　香川　愛媛</span> <b>→</b></a>
        <a href="#search">九州・沖縄 <span>福岡　熊本　長崎　沖縄</span> <b>→</b></a>
      </div>
    </section>

    <section class="guide" id="guide">
      <div><p class="eyebrow">ROOM HUNTING GUIDE</p><h2>はじめてのお部屋探しも安心。</h2><p>家賃の決め方や契約の流れなど、知っておきたい情報をわかりやすく紹介します。</p></div>
      <a href="#search">お部屋探しガイドを見る　→</a>
    </section>
  </main>

  <footer><a class="footer-logo" href="#">住まいナビ</a><span>学校の近くから、あなたに合う住まいを。</span><small>© 2026 住まいナビ　※学校課題用のサンプルサイトです。</small></footer>
</body>
</html>
