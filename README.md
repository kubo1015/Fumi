<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>空き家＆マンション管理パートナーズ | 合同会社ワダツミ</title>
  <!-- Tailwind CSS CDN -->
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <!-- Googleフォント -->
  <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+JP:wght@300;400;500;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Noto Sans JP', sans-serif;
      color: #333;
      line-height: 1.6;
    }
    .hero-gradient {
      background: linear-gradient(135deg, #3182ce 0%, #5a67d8 100%);
    }
    .card-hover {
      transition: all 0.3s ease;
    }
    .card-hover:hover {
      transform: translateY(-5px);
      box-shadow: 0 10px 25px -5px rgba(0,0,0,0.1), 0 10px 10px -5px rgba(0,0,0,0.04);
    }
  </style>
</head>
<body>
  <!-- ヘッダー -->
  <header class="bg-white shadow-md sticky top-0 z-50">
    <div class="container mx-auto px-4 py-3 flex justify-between items-center">
      <a href="#" class="text-2xl font-bold text-blue-600">🏠 空き家＆マンション管理パートナーズ</a>
      <nav class="hidden md:block">
        <ul class="flex space-x-6">
          <li><a href="#services" class="text-gray-700 hover:text-blue-600">サービス</a></li>
          <li><a href="#pricing" class="text-gray-700 hover:text-blue-600">料金</a></li>
          <li><a href="#areas" class="text-gray-700 hover:text-blue-600">対応エリア</a></li>
          <li><a href="#faq" class="text-gray-700 hover:text-blue-600">よくある質問</a></li>
          <li><a href="#contact" class="text-gray-700 hover:text-blue-600">お問い合わせ</a></li>
        </ul>
      </nav>
      <!-- モバイルメニューはお好みで実装 -->
      <button class="md:hidden text-gray-700 focus:outline-none">
        <svg class="w-6 h-6 fill-current" viewBox="0 0 24 24">
          <path d="M4 6h16M4 12h16M4 18h16"></path>
        </svg>
      </button>
    </div>
  </header>

  <!-- ヒーローセクション -->
  <section class="hero-gradient text-white py-20">
    <div class="container mx-auto px-4 text-center">
      <h1 class="text-4xl md:text-5xl font-bold mb-6">
        安心と清潔をお届けする<br>
        管理のプロフェッショナル
      </h1>
      <p class="text-xl md:text-2xl mb-10 max-w-3xl mx-auto">
        合同会社ワダツミがお届けする<br>
        空き家＆マンション管理サービス。<br>
        東京・千葉・埼玉・神奈川対応！
      </p>
      <a href="#contact" class="inline-block bg-white text-blue-600 font-bold py-3 px-8 rounded-full hover:bg-gray-100 transition shadow-lg">
        お問い合わせはこちら
      </a>
    </div>
  </section>

  <!-- サービス紹介 -->
  <section id="services" class="py-16 bg-gray-50">
    <div class="container mx-auto px-4">
      <h2 class="text-3xl font-bold text-center mb-12">サービス内容</h2>
      <div class="grid md:grid-cols-2 gap-8">
        <!-- 空き家管理サービス -->
        <div class="bg-white rounded-lg shadow-lg p-6 card-hover">
          <h3 class="text-2xl font-bold mb-3 text-blue-600">空き家管理サービス</h3>
          <p class="mb-4">
            お留守中の住宅をしっかり見守り、定期的な点検・管理で大切な資産を守ります。
          </p>
          <ul class="space-y-3 mb-4">
            <li class="flex items-start">
              <span class="mr-2">✅</span>
              <span>スタンダード：月1回の定期見回り（写真付きレポート提出）</span>
            </li>
            <li class="flex items-start">
              <span class="mr-2">✅</span>
              <span>プロプラン：月2回の見回り＋玄関周り簡易清掃・庭木の水やり</span>
            </li>
            <li class="flex items-start">
              <span class="mr-2">✅</span>
              <span>郵便物整理、換気、水回りチェック</span>
            </li>
          </ul>
          <a href="#pricing" class="inline-block bg-blue-600 text-white font-medium py-2 px-6 rounded-full hover:bg-blue-700 transition">
            詳しく見る
          </a>
        </div>

        <!-- マンション共用部清掃 -->
        <div class="bg-white rounded-lg shadow-lg p-6 card-hover">
          <h3 class="text-2xl font-bold mb-3 text-blue-600">マンション共用部清掃</h3>
          <p class="mb-4">
            エントランス、廊下、階段などの共用部を定期的に清掃し、快適な住環境を維持します。
          </p>
          <ul class="space-y-3 mb-4">
            <li class="flex items-start">
              <span class="mr-2">✅</span>
              <span>小規模マンション（〜10戸）：月2回清掃</span>
            </li>
            <li class="flex items-start">
              <span class="mr-2">✅</span>
              <span>中規模（11〜30戸）：月3回清掃</span>
            </li>
            <li class="flex items-start">
              <span class="mr-2">✅</span>
              <span>大規模（31戸以上）：月4回清掃</span>
            </li>
          </ul>
          <a href="#pricing" class="inline-block bg-blue-600 text-white font-medium py-2 px-6 rounded-full hover:bg-blue-700 transition">
            詳しく見る
          </a>
        </div>
      </div>
    </div>
  </section>

  <!-- 料金プラン -->
  <section id="pricing" class="py-16 bg-white">
    <div class="container mx-auto px-4">
      <h2 class="text-3xl font-bold text-center mb-12">料金プラン</h2>
      <div class="grid md:grid-cols-2 gap-8">
        <!-- 空き家管理料金プラン -->
        <div class="bg-gray-50 p-6 rounded-lg shadow-md card-hover">
          <h3 class="text-xl font-bold mb-4 border-b pb-2 text-blue-600">空き家管理サービス</h3>
          <div class="space-y-6">
            <div>
              <h4 class="font-bold text-lg">スタンダードプラン</h4>
              <p class="text-2xl font-bold text-blue-600 my-2">月額 5,500円〜</p>
              <ul class="text-sm space-y-2">
                <li class="flex items-start"><span class="mr-2">✅</span><span>月1回の定期見回り</span></li>
                <li class="flex items-start"><span class="mr-2">✅</span><span>写真付きレポートの提出</span></li>
                <li class="flex items-start"><span class="mr-2">✅</span><span>郵便物整理・換気・水回りチェック</span></li>
              </ul>
            </div>
            <div>
              <h4 class="font-bold text-lg">プロプラン</h4>
              <p class="text-2xl font-bold text-blue-600 my-2">月額 9,900円〜</p>
              <ul class="text-sm space-y-2">
                <li class="flex items-start"><span class="mr-2">✅</span><span>月2回の定期見回り</span></li>
                <li class="flex items-start"><span class="mr-2">✅</span><span>玄関周り簡易清掃・庭木の水やり</span></li>
                <li class="flex items-start"><span class="mr-2">✅</span><span>スタンダードの内容に加えて充実のサポート</span></li>
              </ul>
            </div>
          </div>
        </div>

        <!-- マンション共用部清掃料金プラン -->
        <div class="bg-gray-50 p-6 rounded-lg shadow-md card-hover">
          <h3 class="text-xl font-bold mb-4 border-b pb-2 text-blue-600">マンション共用部清掃</h3>
          <div class="space-y-4">
            <div class="bg-white rounded-lg p-4 shadow-sm">
              <h4 class="font-bold text-lg text-blue-600">小規模マンション（〜10戸）</h4>
              <p class="text-2xl font-bold my-2">月額 22,000円〜</p>
              <p class="text-sm">月2回の定期清掃</p>
            </div>
            <div class="bg-white rounded-lg p-4 shadow-sm">
              <h4 class="font-bold text-lg text-blue-600">中規模マンション（11〜30戸）</h4>
              <p class="text-2xl font-bold my-2">月額 33,000円〜</p>
              <p class="text-sm">月3回の定期清掃</p>
            </div>
            <div class="bg-white rounded-lg p-4 shadow-sm">
              <h4 class="font-bold text-lg text-blue-600">大規模マンション（31戸以上）</h4>
              <p class="text-2xl font-bold my-2">月額 55,000円〜</p>
              <p class="text-sm">月4回の定期清掃</p>
            </div>
            <div class="bg-white rounded-lg p-4 shadow-sm border border-blue-200">
              <h4 class="font-bold text-lg text-blue-600">カスタムプラン</h4>
              <p>物件の状況に合わせたプランをご提案します</p>
              <a href="#contact" class="inline-block mt-2 text-blue-600 font-semibold hover:underline">お問い合わせください</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- 対応エリア -->
  <section id="areas" class="py-16 bg-gray-50">
    <div class="container mx-auto px-4">
      <h2 class="text-3xl font-bold text-center mb-12">対応エリア</h2>
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">
        <div class="bg-white rounded-lg shadow-md overflow-hidden card-hover">
          <div class="bg-blue-600 text-white p-4">
            <h3 class="text-xl font-bold text-center">東京都</h3>
          </div>
          <div class="p-6">
            <p class="text-center">東京都全域でサービス提供</p>
            <p class="text-center mt-3 text-sm text-gray-600">※一部離島を除く</p>
          </div>
        </div>
        <div class="bg-white rounded-lg shadow-md overflow-hidden card-hover">
          <div class="bg-green-600 text-white p-4">
            <h3 class="text-xl font-bold text-center">千葉県</h3>
          </div>
          <div class="p-6">
            <p class="text-center">千葉県内主要都市中心</p>
            <p class="text-center mt-3 text-sm text-gray-600">※詳細はお問い合わせください</p>
          </div>
        </div>
        <div class="bg-white rounded-lg shadow-md overflow-hidden card-hover">
          <div class="bg-yellow-600 text-white p-4">
            <h3 class="text-xl font-bold text-center">埼玉県</h3>
          </div>
          <div class="p-6">
            <p class="text-center">埼玉県内主要都市中心</p>
            <p class="text-center mt-3 text-sm text-gray-600">※詳細はお問い合わせください</p>
          </div>
        </div>
        <div class="bg-white rounded-lg shadow-md overflow-hidden card-hover">
          <div class="bg-red-600 text-white p-4">
            <h3 class="text-xl font-bold text-center">神奈川県</h3>
          </div>
          <div class="p-6">
            <p class="text-center">神奈川県内主要都市中心</p>
            <p class="text-center mt-3 text-sm text-gray-600">※詳細はお問い合わせください</p>
          </div>
        </div>
      </div>
      <div class="mt-10 text-center">
        <p class="text-gray-600">その他エリアもご相談ください</p>
        <a href="#contact" class="inline-block mt-4 bg-blue-600 text-white font-medium py-2 px-6 rounded-full hover:bg-blue-700 transition">
          お問い合わせはこちら
        </a>
      </div>
    </div>
  </section>

  <!-- よくある質問 -->
  <section id="faq" class="py-16 bg-white">
    <div class="container mx-auto px-4">
      <h2 class="text-3xl font-bold text-center mb-12">よくある質問</h2>
      <div class="max-w-3xl mx-auto space-y-6">
        <div class="bg-gray-50 rounded-lg p-6 shadow-sm">
          <h3 class="text-xl font-bold mb-3">Q. サービスの契約期間はどのくらいですか？</h3>
          <p>A. 基本的には3ヶ月からの契約となります。長期契約の場合は割引もご用意しております。</p>
        </div>
        <div class="bg-gray-50 rounded-lg p-6 shadow-sm">
          <h3 class="text-xl font-bold mb-3">Q. 鍵の受け渡し方法は？</h3>
          <p>A. 契約時に直接お会いして鍵をお預かりし、契約終了時に返却いたします。セキュリティには万全を期しております。</p>
        </div>
        <div class="bg-gray-50 rounded-lg p-6 shadow-sm">
          <h3 class="text-xl font-bold mb-3">Q. 清掃時の道具はどうなりますか？</h3>
          <p>A. 基本的な清掃道具は弊社でご用意いたします。特殊な洗剤が必要な場合は事前にご相談ください。</p>
        </div>
        <div class="bg-gray-50 rounded-lg p-6 shadow-sm">
          <h3 class="text-xl font-bold mb-3">Q. 緊急時の対応は？</h3>
          <p>A. 点検時に不審な事項を発見した場合は、速やかにご連絡いたします。状況に合わせた柔軟な対応を行います。</p>
        </div>
        <div class="bg-gray-50 rounded-lg p-6 shadow-sm">
          <h3 class="text-xl font-bold mb-3">Q. マンション管理組合への連絡は必要ですか？</h3>
          <p>A. 共用部清掃の場合、管理組合や管理会社への事前連絡が必要な場合がございます。必要に応じサポートいたします。</p>
        </div>
      </div>
    </div>
  </section>

  <!-- お問い合わせ -->
  <section id="contact" class="py-16 bg-gray-50">
    <div class="container mx-auto px-4">
      <h2 class="text-3xl font-bold text-center mb-12">お問い合わせ</h2>
      <div class="max-w-2xl mx-auto bg-white rounded-lg shadow-md p-8">
        <p class="mb-6 text-center">
          サービスに関するご質問やお見積もりのご依頼は、下記フォームからお気軽にお問い合わせください。<br>
          通常48時間以内にメールでご返信いたします。
        </p>
        <!-- ここにGoogleフォームの埋め込みコードを挿入（iframe推奨） -->
        <div class="w-full overflow-hidden">
          <iframe src="【ここにあなたのGoogleフォームの埋め込みURL】" width="100%" height="800" frameborder="0" marginheight="0" marginwidth="0">読み込んでいます…</iframe>
        </div>
      </div>
    </div>
  </section>

  <!-- フッター -->
  <footer class="bg-gray-800 text-white py-10">
    <div class="container mx-auto px-4">
      <div class="flex flex-col md:flex-row justify-between items-center">
        <div class="mb-6 md:mb-0">
          <h3 class="text-xl font-bold mb-2">空き家＆マンション管理パートナーズ</h3>
          <p class="text-gray-400">合同会社ワダツミ</p>
        </div>
        <div class="mb-6 md:mb-0">
          <h4 class="font-bold mb-2">対応エリア</h4>
          <p class="text-gray-400">東京都・千葉県・埼玉県・神奈川県</p>
        </div>
        <div>
          <a href="#contact" class="inline-block bg-blue-600 text-white font-medium py-2 px-6 rounded-full hover:bg-blue-700 transition">お問い合わせ</a>
        </div>
      </div>
      <div class="border-t border-gray-700 mt-8 pt-8 text-center">
        <p>&copy; 2025 空き家＆マンション管理パートナーズ All Rights Reserved.</p>
      </div>
    </div>
  </footer>
</body>
</html>
