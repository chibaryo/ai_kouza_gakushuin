---
theme: default
layout: cover
class: text-center
highlighter: shiki
lineNumbers: false
info: |
  ## AI活用によるタスク効率化
  議事録・メール・要約の自動化
drawings:
  persist: false
transition: slide-left
title: AI活用によるタスク効率化
subtitle: 議事録・メール・要約の自動化
mdc: true
---

<style>
.text-gradient {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
}
.highlight {
  background: linear-gradient(135deg, #ffecd2 0%, #fcb69f 100%);
  color: #333;
  padding: 0.3em 0.6em;
  border-radius: 0.5em;
  font-weight: bold;
  box-shadow: 0 4px 15px rgba(0,0,0,0.1);
}
.card {
  background: rgba(255, 255, 255, 0.1);
  backdrop-filter: blur(10px);
  border-radius: 1rem;
  padding: 1.5rem;
  border: 1px solid rgba(255, 255, 255, 0.2);
  box-shadow: 0 8px 32px rgba(0,0,0,0.1);
}
.icon-large {
  font-size: 4rem;
  margin-bottom: 1rem;
}
</style>

# <span class="text-gradient">AI活用によるタスク効率化</span>

## <span class="highlight">議事録・メール・要約の自動化</span>

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-4 py-2 rounded-lg cursor-pointer bg-gradient-to-r from-blue-500 to-purple-600 text-white hover:from-blue-600 hover:to-purple-700 transition-all duration-300">
    講義を開始する <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <span class="text-sm opacity-50">90分講義 | 実践的なAI活用術</span>
</div>

---
layout: default
---

# 📚 今日の講義内容

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="card">

## 🎯 学習目標
- **議事録・メール**のAI活用による自動化
- **AI活用した要約**の実践手法
- **タスク効率化**のためのAIツール活用
- **従来のメモ・ブクマ**をAIで整理する方法

</div>

<div class="card">

## ⏰ 時間配分（90分）
- 🚀 導入・課題の整理：**10分**
- 🧠 AIツールの基本紹介：**15分**
- 🔧 **実践ワークショップ（前半）**：**25分**
- 📝 議事録・メール効率化：**20分**
- 🎯 **実践ワークショップ（後半）**：**20分**

</div>

</div>

---
layout: default
---

# 🎯 導入：学生生活での課題とAIが提供する解決策

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="card">

## 😰 日常的な悩み

<div class="space-y-2 mt-2">
  <div class="p-2 bg-red-100 rounded">
    <div class="font-bold text-red-800 text-sm">📝 議事録作成が面倒</div>
    <div class="text-xs">会議の要点を整理するのに時間がかかる</div>
  </div>
  
  <div class="p-2 bg-orange-100 rounded">
    <div class="font-bold text-orange-800 text-sm">📧 メール作成に時間</div>
    <div class="text-xs">適切な表現を考えるのに悩む</div>
  </div>
  
  <div class="p-2 bg-yellow-100 rounded">
    <div class="font-bold text-yellow-800 text-sm">📚 情報整理が追いつかない</div>
    <div class="text-xs">メモやブクマが散らばっている</div>
  </div>
  
  <div class="p-2 bg-blue-100 rounded">
    <div class="font-bold text-blue-800 text-sm">⏰ 作業効率が上がらない</div>
    <div class="text-xs">同じ作業の繰り返しが多い</div>
  </div>
</div>

</div>

<div class="card">

## ✨ AIが提供する解決策

<div class="space-y-2 mt-2">
  <div class="p-2 bg-green-100 rounded">
    <div class="font-bold text-green-800 text-sm">🤖 議事録の自動生成</div>
    <div class="text-xs">Zoom Pro AIで文字起こし・要約</div>
  </div>
  
  <div class="p-2 bg-purple-100 rounded">
    <div class="font-bold text-purple-800 text-sm">📧 メールの下書き作成</div>
    <div class="text-xs">Geminiで状況に応じた文章生成</div>
  </div>
  
  <div class="p-2 bg-indigo-100 rounded">
    <div class="font-bold text-indigo-800 text-sm">📖 情報の自動整理</div>
    <div class="text-xs">Notebook LMで要約・構造化</div>
  </div>
  
  <div class="p-2 bg-pink-100 rounded">
    <div class="font-bold text-pink-800 text-sm">⚡ 作業の自動化</div>
    <div class="text-xs">AIツールの組み合わせで効率化</div>
  </div>
</div>

</div>

</div>

---
layout: default
---

# 🧠 今回紹介するAIツール

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="card">

## 🎥 Zoom Pro (AI Companion)

<div class="space-y-2 mt-2">
  <div class="p-2 bg-blue-100 rounded">
    <div class="font-bold text-blue-800 text-sm">📹 動画クラウド録画</div>
    <div class="text-xs">会議を自動で録画・保存</div>
  </div>
  
  <div class="p-2 bg-green-100 rounded">
    <div class="font-bold text-green-800 text-sm">🎙️ AI文字起こし</div>
    <div class="text-xs">リアルタイムで字幕生成</div>
  </div>
  
  <div class="p-2 bg-purple-100 rounded">
    <div class="font-bold text-purple-800 text-sm">📋 自動要約</div>
    <div class="text-xs">会議内容の要点を自動抽出</div>
  </div>
</div>

</div>

<div class="card">

## 📝 Notebook LM

<div class="space-y-2 mt-2">
  <div class="p-2 bg-blue-100 rounded">
    <div class="font-bold text-blue-800 text-sm">📖 Zoom文字起こし要約</div>
    <div class="text-xs">議事録の自動整理・構造化</div>
  </div>
  
  <div class="p-2 bg-green-100 rounded">
    <div class="font-bold text-green-800 text-sm">🌐 YouTube要約</div>
    <div class="text-xs">動画内容の要点を自動抽出</div>
  </div>
  
  <div class="p-2 bg-purple-100 rounded">
    <div class="font-bold text-purple-800 text-sm">🔍 関連性分析</div>
    <div class="text-xs">複数文書の関連性を発見</div>
  </div>
</div>

</div>

</div>

---
layout: default
---

# 🧠 今回紹介するAIツール（続き）

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="card">

## 🎨 OpenAI Sora

<div class="space-y-2 mt-2">
  <div class="p-2 bg-blue-100 rounded">
    <div class="font-bold text-blue-800 text-sm">🎨 高品質画像生成</div>
    <div class="text-xs">テキスト説明からリアルな画像作成</div>
  </div>
  
  <div class="p-2 bg-green-100 rounded">
    <div class="font-bold text-green-800 text-sm">🎬 短編動画生成</div>
    <div class="text-xs">数秒の動画クリップを自動生成</div>
  </div>
  
  <div class="p-2 bg-purple-100 rounded">
    <div class="font-bold text-purple-800 text-sm">🔧 詳細な指示</div>
    <div class="text-xs">具体的な設定・スタイルの指定</div>
  </div>
</div>

</div>

<div class="card">

## 🎬 Google AI Studio Veo2

<div class="space-y-2 mt-2">
  <div class="p-2 bg-blue-100 rounded">
    <div class="font-bold text-blue-800 text-sm">📹 高品質動画作成</div>
    <div class="text-xs">プロ品質の動画を自動生成</div>
  </div>
  
  <div class="p-2 bg-green-100 rounded">
    <div class="font-bold text-green-800 text-sm">🎭 ストーリー性</div>
    <div class="text-xs">物語性のある動画を自動生成</div>
  </div>
  
  <div class="p-2 bg-purple-100 rounded">
    <div class="font-bold text-purple-800 text-sm">🔗 Google統合</div>
    <div class="text-xs">Googleアカウントでシームレス連携</div>
  </div>
</div>

</div>

</div>

---
layout: default
---

# 🧠 今回紹介するAIツール（続き）

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="card">

## 🗺️ Mapify

<div class="space-y-2 mt-2">
  <div class="p-2 bg-blue-100 rounded">
    <div class="font-bold text-blue-800 text-sm">🔗 YouTube Link入力</div>
    <div class="text-xs">動画URLから自動でマインドマップ作成</div>
  </div>
  
  <div class="p-2 bg-green-100 rounded">
    <div class="font-bold text-green-800 text-sm">🌱 AIマインドマップ生成</div>
    <div class="text-xs">動画内容を構造化して可視化</div>
  </div>
  
  <div class="p-2 bg-purple-100 rounded">
    <div class="font-bold text-purple-800 text-sm">📥 マークダウン出力</div>
    <div class="text-xs">Gammaでのスライド作成用</div>
  </div>
</div>

</div>

<div class="card">

## 🎨 Gamma

<div class="space-y-2 mt-2">
  <div class="p-2 bg-blue-100 rounded">
    <div class="font-bold text-blue-800 text-sm">📝 マークダウン入力</div>
    <div class="text-xs">Mapifyの出力を基にスライド作成</div>
  </div>
  
  <div class="p-2 bg-green-100 rounded">
    <div class="font-bold text-green-800 text-sm">🎨 自動スライド生成</div>
    <div class="text-xs">AIが美しいデザインで作成</div>
  </div>
  
  <div class="p-2 bg-purple-100 rounded">
    <div class="font-bold text-purple-800 text-sm">📤 多形式エクスポート</div>
    <div class="text-xs">PDF、PPTX、画像など</div>
  </div>
</div>

</div>

</div>

---
layout: default
---

# 🧠 今回紹介するAIツール（続き）

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="card">

## 🚀 Dify

<div class="space-y-2 mt-2">
  <div class="p-2 bg-blue-100 rounded">
    <div class="font-bold text-blue-800 text-sm">🤖 ノーコードAI開発</div>
    <div class="text-xs">プログラミング不要でAIアプリ作成</div>
  </div>
  
  <div class="p-2 bg-green-100 rounded">
    <div class="font-bold text-green-800 text-sm">🔗 複数AIモデル対応</div>
    <div class="text-xs">Gemini、OpenAI、Claudeなど</div>
  </div>
  
  <div class="p-2 bg-purple-100 rounded">
    <div class="font-bold text-purple-800 text-sm">📊 ビジュアルワークフロー</div>
    <div class="text-xs">ドラッグ&ドロップで簡単構築</div>
  </div>
</div>

</div>

</div>

---
layout: default
---

# 🔧 実践ワークショップ：プロンプトのコツ + 6つのAIワークフロー体験

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="card">

## 🎯 体験する6つのワークフロー

<div class="space-y-2 mt-2">
  <div class="flex items-center">
    <div class="w-5 h-5 bg-blue-500 rounded-full flex items-center justify-center text-white font-bold text-xs mr-2">1</div>
    <div class="text-xs">🎥 Zoom文字起こし</div>
  </div>
  
  <div class="flex items-center">
    <div class="w-5 h-5 bg-green-500 rounded-full flex items-center justify-center text-white font-bold text-xs mr-2">2</div>
    <div class="text-xs">📝 Notebook LM要約</div>
  </div>
  
  <div class="flex items-center">
    <div class="w-5 h-5 bg-purple-500 rounded-full flex items-center justify-center text-white font-bold text-xs mr-2">3</div>
    <div class="text-xs">🎨 Sora画像・動画生成</div>
  </div>
  
  <div class="flex items-center">
    <div class="w-5 h-5 bg-pink-500 rounded-full flex items-center justify-center text-white font-bold text-xs mr-2">4</div>
    <div class="text-xs">🎬 Veo2動画生成</div>
  </div>
  
  <div class="flex items-center">
    <div class="w-5 h-5 bg-orange-500 rounded-full flex items-center justify-center text-white font-bold text-xs mr-2">5</div>
    <div class="text-xs">🎨 Mapify + Gammaスライド作成</div>
  </div>
  
  <div class="flex items-center">
    <div class="w-5 h-5 bg-red-500 rounded-full flex items-center justify-center text-white font-bold text-xs mr-2">6</div>
    <div class="text-xs">🚀 Dify高度なAIワークフロー</div>
  </div>
</div>

</div>

<div class="card">

## 💻 実践の流れ

<div class="space-y-2 mt-2">
  <div class="p-2 bg-blue-100 rounded">
    <div class="font-bold text-blue-800 text-sm">📱 各ワークフローの基本操作</div>
    <div class="text-xs">実際に触ってみる</div>
  </div>
  
  <div class="p-2 bg-green-100 rounded">
    <div class="font-bold text-green-800 text-sm">🔄 ツールの連携体験</div>
    <div class="text-xs">入力→処理→出力の流れ</div>
  </div>
  
  <div class="p-2 bg-purple-100 rounded">
    <div class="font-bold text-purple-800 text-sm">💡 効果と注意点</div>
    <div class="text-xs">実際の使用感を確認</div>
  </div>
  
  <div class="p-2 bg-orange-100 rounded">
    <div class="font-bold text-orange-800 text-sm">🎯 自分の課題への応用</div>
    <div class="text-xs">今後の活用計画を策定</div>
  </div>
</div>

</div>

</div>

---
layout: default
---

# 📝 実例プロンプト：ビジネス活用の具体例

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="card">

## 🎯 このセクションで学ぶこと

<div class="space-y-2 mt-2">
  <div class="p-2 bg-blue-100 rounded">
    <div class="font-bold text-blue-800 text-sm">📧 メール・文書作成</div>
    <div class="text-xs">ビジネス文書の効率的作成</div>
  </div>
  
  <div class="p-2 bg-green-100 rounded">
    <div class="font-bold text-green-800 text-sm">⚡ 業務効率化</div>
    <div class="text-xs">PC操作・プログラミング支援</div>
  </div>
  
  <div class="p-2 bg-purple-100 rounded">
    <div class="font-bold text-purple-800 text-sm">📈 売上向上</div>
    <div class="text-xs">マーケティング・営業支援</div>
  </div>
  
  <div class="p-2 bg-orange-100 rounded">
    <div class="font-bold text-orange-800 text-sm">👥 人材採用・育成</div>
    <div class="text-xs">採用・研修の効率化</div>
  </div>
</div>

</div>

<div class="card">

## 💡 プロンプト作成のポイント

<div class="space-y-2 mt-2">
  <div class="p-2 bg-green-100 rounded">
    <div class="font-bold text-green-800 text-sm">🎯 具体的な指示</div>
    <div class="text-xs">「#内容」「#条件」で明確化</div>
  </div>
  
  <div class="p-2 bg-blue-100 rounded">
    <div class="font-bold text-blue-800 text-sm">📋 構造化された入力</div>
    <div class="text-xs">箇条書きで整理された情報</div>
  </div>
  
  <div class="p-2 bg-purple-100 rounded">
    <div class="font-bold text-purple-800 text-sm">🔒 セキュリティ配慮</div>
    <div class="text-xs">機密情報・個人情報は避ける</div>
  </div>
</div>

</div>

</div>

---
layout: default
---

# 📧 メール・文書作成の実例プロンプト

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="card">

## 📝 見積書送付メールの作成

<div class="p-3 bg-blue-50 rounded text-sm">
<div class="font-bold mb-2">入力内容例（プロンプト）:</div>
<div>見積書の送付メールを作成してください。<br/>
#内容<br/>
・見積書と関係資料を添付で送付<br/>
・見積書の有効期限は2025年9月30日<br/>
#条件<br/>
・ビジネス文書としてふさわしい文体で作成</div>
</div>

<div class="mt-3 p-2 bg-green-50 rounded text-xs">
💡 <strong>解説</strong>：「#内容」に含めたい情報を箇条書きで簡潔に記載。発注や請求、日程調整など、様々な内容のメール作成に応用可能。
</div>

</div>

<div class="card">

## 📄 社外文書の作成

<div class="p-3 bg-green-50 rounded text-sm">
<div class="font-bold mb-2">入力内容例（プロンプト）:</div>
<div>以下の社外向け文書を作成してください。<br/>
#内容<br/>
・顧客に対し、販売価格改定のお願いをする<br/>
・昨今の燃料費・材料費の高騰によるもの<br/>
#条件<br/>
・日本のビジネス文書（ビジネスレター）としてふさわしい体裁・文体で作成<br/>
・顧客名が先、自社名を後に記載</div>
</div>

<div class="mt-3 p-2 bg-blue-50 rounded text-xs">
💡 <strong>解説</strong>：「#内容」の部分に、文書に含めたい情報を箇条書きで簡潔に記載。様々なビジネス文書作成に応用可能。
</div>

</div>

</div>

---
layout: default
---

# 📋 タスク管理・プレゼン資料の実例プロンプト

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="card">

## ✅ タスクの洗い出し

<div class="p-3 bg-purple-50 rounded text-sm">
<div class="font-bold mb-2">入力内容例（プロンプト）:</div>
<div>新サービスのローンチに向けて対応すべきことと、そのスケジュールを提示してください。<br/>
#新サービスの概要<br/>
・AIを使った顧客対応サービス<br/>
・2026年1月 発売予定</div>
</div>

<div class="mt-3 p-2 bg-orange-50 rounded text-xs">
💡 <strong>解説</strong>：サービスや商品の詳細を細かく書くと情報漏洩のリスクがあるため、概要に留める。
</div>

</div>

<div class="card">

## 📊 プレゼン資料の目次作成

<div class="p-3 bg-indigo-50 rounded text-sm">
<div class="font-bold mb-2">入力内容例（プロンプト）:</div>
<div>以下のテーマと条件で、プレゼン資料の項目（目次）案を作ってください。<br/>
#テーマ<br/>
・中小企業のデジタル化の現状と課題<br/>
#条件<br/>
・プレゼン時間：10分</div>
</div>

<div class="mt-3 p-2 bg-pink-50 rounded text-xs">
💡 <strong>解説</strong>：プレゼンのテーマと時間を指定することで、内容の濃淡を調整。「スライド構成を作成してください」などと続けて質問することで、より実践的な回答を得ることも可能。
</div>

</div>

</div>

---
layout: default
---

# ✍️ 文章作成・校正の実例プロンプト

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="card">

## 🔍 文章の校正

<div class="p-3 bg-red-50 rounded text-sm">
<div class="font-bold mb-2">入力内容例（プロンプト）:</div>
<div>あなたはプロの校正者です。以下の文章を校正してください。<br/>
#入力文<br/>
＜ここに校正してもらいたい文章を記載してください＞<br/>
#条件<br/>
・誤字脱字、タイプミス、表記の揺れ、文脈に合わない単語、文末表現の不一致、主語と述語の不備をすべて指摘してください。<br/>
・修正点は、太字にしてください。</div>
</div>

</div>

<div class="card">

## 📝 文章の要約

<div class="p-3 bg-green-50 rounded text-sm">
<div class="font-bold mb-2">入力内容例（プロンプト）:</div>
<div>あなたはプロの編集者です。以下の文章を要約してください。<br/>
#入力文<br/>
＜ここに要約してもらいたい文章を記載してください＞<br/>
#条件<br/>
・300文字以内で要約してください。<br/>
・重要なキーワードを取りこぼさないでください。<br/>
・架空の表現や言葉を使用しないでください。<br/>
・文章内の数値は変更しないでください。</div>
</div>

</div>

</div>

---
layout: default
---

# 🌐 翻訳・多言語対応の実例プロンプト

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="card">

## 🔤 言語翻訳

<div class="p-3 bg-blue-50 rounded text-sm">
<div class="font-bold mb-2">入力内容例（プロンプト）:</div>
<div>あなたはプロの翻訳者です。以下の日本語の文章を英語に訳してください。<br/>
#入力文<br/>
＜ここに翻訳してもらいたい文章を記載してください＞</div>
</div>

<div class="mt-3 p-2 bg-green-50 rounded text-xs">
💡 <strong>解説</strong>：翻訳と同時に要約や文体の指定なども可能。
</div>

</div>

<div class="card">

## 📧 メールの多言語作成

<div class="p-3 bg-purple-50 rounded text-sm">
<div class="font-bold mb-2">入力内容例（プロンプト）:</div>
<div>以下の内容・言語・条件でメールを作成してください。<br/>
#内容<br/>
・お問い合わせありがとうございます<br/>
・オンライン商談の候補日：9月5日10-17時、9月6日10-12時（中国時間）<br/>
#言語<br/>
・中国語（簡体字）<br/>
#条件<br/>
・ビジネス文書としてふさわしい丁寧な文体で作成</div>
</div>

<div class="mt-2 p-2 bg-orange-50 rounded text-xs">
💡 <strong>解説</strong>：翻訳サイトで内容確認をおすすめ。
</div>

</div>

</div>

---
layout: default
---

# ⚡ 業務効率化の実例プロンプト

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="card">

## 💻 PC操作方法の確認

<div class="p-3 bg-indigo-50 rounded text-sm">
<div class="font-bold mb-2">入力内容例（プロンプト）:</div>
<div>Excelのセルに日付を入力しようとしても「#######」と表示されてしまいます。どのようにしたらよいですか？<br/>
#動作環境<br/>
・Windows11 ・Office2021</div>
</div>

<div class="mt-3 p-2 bg-blue-50 rounded text-xs">
💡 <strong>解説</strong>：WindowsなどのOSや、一般的に広く使われているオフィスソフトの操作方法にのみ対応。
</div>

</div>

<div class="card">

## 🖥️ プログラミング・コーディング

<div class="p-3 bg-green-50 rounded text-sm">
<div class="font-bold mb-2">入力内容例（プロンプト）:</div>
<div>以下の条件で、Excelの関数を書いてください。<br/>
#条件<br/>
B列に氏名が記載されており、姓名の間には半角スペースまたは全角スペースが入っています。C列に姓、D列に名を分けて記載したい。</div>
</div>

<div class="mt-3 p-2 bg-purple-50 rounded text-xs">
💡 <strong>解説</strong>：Excelの関数だけでなく、VBAコードの生成も可能。エラーが発生した場合は、エラーメッセージを伝えると解決策を提案してくれる。
</div>

</div>

</div>

---
layout: default
---

# 📊 情報収集・リサーチの実例プロンプト

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="card">

## 🔍 市場調査・リサーチ

<div class="p-3 bg-orange-50 rounded text-sm">
<div class="font-bold mb-2">入力内容例（プロンプト）:</div>
<div>以下の条件で、医療業界の市場規模・市場動向を調査してください。<br/>
#条件<br/>
・日本国内の市場規模・市場動向を調べてください。<br/>
・2023年以降のデータ・資料を用いてください。<br/>
・出典を必ず示してください。<br/>
#出力形式<br/>
市場規模<br/>
市場動向</div>
</div>

</div>

<div class="card">

## ⚠️ 重要な注意点

<div class="p-3 bg-red-50 rounded text-sm">
<div class="font-bold mb-2">生成AIの弱点について</div>
<div>生成AIは「ハルシネーション（幻覚）」と呼ばれる、あたかも事実かのように架空の情報を回答する弱点があります。</div>
</div>

<div class="mt-3 p-2 bg-yellow-50 rounded text-xs">
💡 <strong>対策</strong>：特に情報収集やリサーチに使う際は、必ず出典を確認し、信頼できる情報か検証してください。
</div>

</div>

</div>

---
layout: default
---

# 📈 売上向上の実例プロンプト

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="card">

## 📧 メールマガジン文面作成

<div class="p-3 bg-blue-50 rounded" style="font-size: 11px; line-height: 1.4;">
<div class="font-bold mb-2">入力内容例（プロンプト）:</div>
<div>以下の商品・サービスをPRするメールマガジンを作成してください。<br/>
#商品・サービス名<br/>
地域コミュニティ活性化サービス「コネクト！」<br/>
#概要<br/>
地域の店舗やイベント情報をまとめて発信するアプリ。地域住民が簡単に交流できる掲示板機能や、お得なクーポン機能も搭載。<br/>
#特徴<br/>
・地元の情報が手軽に手に入る<br/>
・地域住民同士の交流が活発になる<br/>
・地元の商店街の利用を促進できる<br/>
#ターゲット<br/>
地域に住む20〜60代の住民<br/>
#条件<br/>
・ビジネス上のメールとしてふさわしい文体で作成</div>
</div>

</div>

<div class="card">

## 📞 営業電話スクリプトの作成

<div class="p-3 bg-green-50 rounded" style="font-size: 11px; line-height: 1.4;">
<div class="font-bold mb-2">入力内容例（プロンプト）:</div>
<div>以下の商品・サービスの営業電話のスクリプトを作成してください。<br/>
#商品・サービス名<br/>
AI搭載型チャットボット「スマートサポート」<br/>
#概要<br/>
企業のカスタマーサポートを自動化し、24時間365日の問い合わせ対応を可能にするサービス。<br/>
#特徴<br/>
・初期設定が簡単<br/>
・自然言語処理により高度な会話が可能<br/>
・FAQの自動更新機能<br/>
#ターゲット<br/>
中小企業のIT部門責任者<br/>
#条件<br/>
・ビジネス上のやり取りとしてふさわしい丁寧な文体で作成<br/>
・「今回、お電話させていただきましたのは、」から始まる文章を作成<br/>
・ゴールは商談のアポイントメント取得</div>
</div>

</div>

</div>

---
layout: default
---

# 📱 SNS・マーケティングの実例プロンプト

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="card">

## 📸 SNS投稿文の作成

<div class="p-3 bg-purple-50 rounded text-sm">
<div class="font-bold mb-2">入力内容例（プロンプト）:</div>
<div>以下の商品・サービスをPRするInstagram投稿文を100文字以内で作成してください。<br/>
#商品・サービス名<br/>
オーガニックコスメブランド「ナチュラリエ」<br/>
#概要<br/>
敏感肌の方でも安心して使える、天然成分100%のスキンケア商品シリーズ。<br/>
#特徴<br/>
・合成香料、着色料、防腐剤不使用<br/>
・ローズマリー、ラベンダーなど天然のエッセンシャルオイル配合<br/>
・環境に配慮したリサイクル可能な容器<br/>
#ターゲット<br/>
美容と健康に関心のある20〜40代女性</div>
</div>

</div>

<div class="card">

## 🎯 キャッチコピー作成

<div class="p-3 bg-pink-50 rounded text-sm">
<div class="font-bold mb-2">入力内容例（プロンプト）:</div>
<div>広告に掲載する以下の商品・サービスのキャッチコピーを5個考えてください。<br/>
#商品・サービス名<br/>
無添加ドレッシング「彩り野菜」<br/>
#概要<br/>
契約農家で栽培された新鮮な野菜を使い、化学調味料や保存料を一切使用しないこだわりのドレッシング。<br/>
#特徴<br/>
・素材本来の味が楽しめる<br/>
・サラダだけでなく、肉料理やパスタにも合う<br/>
・子供からお年寄りまで安心して食べられる<br/>
#ターゲット<br/>
食の安全にこだわる主婦層</div>
</div>

</div>

</div>

---
layout: default
---

# 🏢 経営戦略・マーケティングの実例プロンプト

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="card">

## 🎯 経営戦略・課題解決のアドバイス

<div class="p-3 bg-indigo-50 rounded" style="font-size: 12px; line-height: 1.4;">
<div class="font-bold mb-2">入力内容例（プロンプト）:</div>
<div>あなたは一流の経営コンサルタントです。私は、製造業の会社の経営者です。今から私の悩みを伝えますので、アドバイスをお願いします。まず企業概要について記載します。<br/>
#会社概要<br/>
東京都大田区に所在する従業員30名の製造業。精密部品の設計・製造を得意とし、特に医療機器向けの部品製造に強みを持つ。短納期、多品種少量生産にも対応。<br/>
#自社の理念<br/>
①お客様のニーズに合わせた柔軟な生産体制を維持します ②高品質な製品を提供することで社会に貢献します ③従業員の技術力向上と働きやすい環境づくりに努めます<br/>
近年の人件費や原材料費の高騰により利益率が低下しており、コスト削減と新たな収益源の確保を2年以内に打ち出したいと思っています。</div>
</div>

</div>

<div class="card">

## 📊 SWOT分析

<div class="p-3 bg-green-50 rounded" style="font-size: 12px; line-height: 1.4;">
<div class="font-bold mb-2">入力内容例（プロンプト）:</div>
<div>私は小売業の経営者です。自社のSWOT分析を行いたいので、対話形式で手伝っていただけますか？<br/>
プロンプト例（対話開始）:<br/>
当社は、地方都市を中心に日用品と食料品を扱うスーパーマーケットを5店舗経営しています。新鮮な地元野菜の仕入れに力を入れていますが、近年は大型ショッピングモールやオンラインストアの台頭に苦戦しています。</div>
</div>

</div>

</div>

---
layout: default
---

# 🎨 マーケティング戦略・店名考案の実例プロンプト

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="card">

## 📈 マーケティング戦略の策定

<div class="p-3 bg-orange-50 rounded text-sm">
<div class="font-bold mb-2">入力内容例（プロンプト）:</div>
<div>当社の主要商品・サービスの売上を増加させるためのマーケティング戦略として考えられるアプローチは？<br/>
#商品・サービス名<br/>
健康食品「グリーンライフプロテイン」<br/>
#概要<br/>
天然由来のタンパク質を豊富に含み、美容と健康をサポートする粉末タイプのプロテイン。<br/>
#特徴<br/>
・味の種類が豊富（抹茶、きなこ、ココアなど）<br/>
・溶けやすく、飲みやすい<br/>
・人工甘味料、合成保存料不使用<br/>
#ターゲット<br/>
健康意識の高い30〜50代の男女</div>
</div>

</div>

<div class="card">

## 🏪 店名の考案

<div class="p-3 bg-pink-50 rounded text-sm">
<div class="font-bold mb-2">入力内容例（プロンプト）:</div>
<div>和風創作料理店を開業したいので、和を意識したお店の名前の候補を10個出してください。語感が良く記憶に残りやすいもので、日本語の意味も併記してください。</div>
</div>

</div>

</div>

---
layout: default
---

# 👥 人材採用・育成の実例プロンプト

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="card">

## 📋 募集要項の校正

<div class="p-3 bg-blue-50 rounded text-sm">
<div class="font-bold mb-2">入力内容例（プロンプト）:</div>
<div>新卒採用の募集要項を作成しました。以下の文章を、ターゲットに響くように修正し、魅力的にしてください。<br/>
#入力文<br/>
＜ここに募集要項の文章を記載してください＞<br/>
#ターゲット<br/>
・ITに興味がある大学生<br/>
#条件<br/>
・若者向けの親しみやすい文体にしてください。<br/>
・「挑戦」「成長」といったキーワードを盛り込んでください。<br/>
・当社の強みが伝わるようにしてください。</div>
</div>

</div>

<div class="card">

## 📱 SNSでのPR文作成

<div class="p-3 bg-green-50 rounded text-sm">
<div class="font-bold mb-2">入力内容例（プロンプト）:</div>
<div>新卒採用の告知として、LinkedInに投稿するPR文を作成してください。<br/>
#内容<br/>
・2026年度の新卒採用を開始したことを告知<br/>
・募集職種はエンジニアとデザイナー<br/>
・当社の技術力と成長環境をアピール<br/>
#条件<br/>
・ビジネスSNSにふさわしいフォーマルな文体で作成<br/>
・200文字以内で簡潔にまとめてください。</div>
</div>

</div>

</div>

---
layout: default
---

# 🎓 採用・研修の実例プロンプト

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="card">

## 🗣️ 採用面接質問の作成

<div class="p-3 bg-purple-50 rounded text-sm">
<div class="font-bold mb-2">入力内容例（プロンプト）:</div>
<div>新卒採用の面接官として、以下の候補者に対する面接質問案を作成してください。<br/>
#候補者の情報<br/>
・大学の機械工学専攻<br/>
・ロボットアームの研究に注力<br/>
・学生時代にプログラミングコンテストで入賞経験あり<br/>
#面接の目的<br/>
・論理的思考力と問題解決能力を測る<br/>
・チームでの協調性を確認する<br/>
・当社の業務内容との適性を判断する<br/>
#質問案<br/>
・面接の導入となるアイスブレイクの質問<br/>
・研究内容を深掘りする質問<br/>
・入社後の働き方やキャリアビジョンに関する質問<br/>
・逆質問を促す言葉</div>
</div>

</div>

<div class="card">

## 📚 研修内容企画書の作成

<div class="p-3 bg-indigo-50 rounded text-sm">
<div class="font-bold mb-2">入力内容例（プロンプト）:</div>
<div>新入社員向けのビジネスマナー研修の企画書を作成してください。<br/>
#研修目的<br/>
・社会人としての基礎的なマナーを習得する<br/>
・社内外での円滑なコミュニケーションを可能にする<br/>
#研修内容<br/>
・挨拶、言葉遣い<br/>
・電話応対、来客応対<br/>
・名刺交換<br/>
#条件<br/>
・3日間のプログラムとして構成してください。<br/>
・研修の各項目に具体的な実施時間と目標を明記してください。<br/>
・グループワークやロールプレイングを取り入れてください。</div>
</div>

</div>

</div>

---
layout: default
---

# 🎥 ワークフロー1：Zoom Pro AI文字起こし

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="card">

## 🎯 Zoom Pro AIの基本機能

<div class="space-y-3 mt-3">
  <div class="p-2 bg-blue-100 rounded">
    <div class="font-bold text-blue-800 text-sm">📹 クラウドレコーディング</div>
    <div class="text-xs">ミーティングを自動でクラウドに保存</div>
  </div>
  
  <div class="p-2 bg-green-100 rounded">
    <div class="font-bold text-green-800 text-sm">🗣️ AI自動字幕生成</div>
    <div class="text-xs">リアルタイムで高精度な字幕を生成</div>
  </div>
  
  <div class="p-2 bg-purple-100 rounded">
    <div class="font-bold text-purple-800 text-sm">📝 文字起こしファイル</div>
    <div class="text-xs">後から編集・ダウンロード可能</div>
  </div>
</div>

</div>

<div class="card">

## 💡 実践のポイント

<div class="space-y-3 mt-3">
  <div class="p-2 bg-green-100 rounded">
    <div class="font-bold text-green-800 text-sm">🎙️ 音声品質</div>
    <div class="text-xs">クリアな音声で字幕精度を向上</div>
  </div>
  
  <div class="p-2 bg-blue-100 rounded">
    <div class="font-bold text-blue-800 text-sm">📋 設定確認</div>
    <div class="text-xs">録画開始前に字幕機能を有効化</div>
  </div>
  
  <div class="p-2 bg-purple-100 rounded">
    <div class="font-bold text-purple-800 text-sm">🔄 次のステップ</div>
    <div class="text-xs">NoteBookLMでの要約・整理</div>
  </div>
</div>

</div>

</div>

---
layout: default
---

# 🎥 Zoom Pro実践：レコーディングと文字起こし管理

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="card">

## 📹 クラウドレコーディング管理

<div class="text-center">
  <img src="/zoom_ai/zoom_ai1.png" alt="Zoom レコーディングと文字起こし管理" class="w-full h-auto rounded-lg shadow-md mb-3" />
  <div class="text-xs text-gray-600">Zoomのレコーディングと文字起こし管理画面</div>
</div>

<div class="mt-3 p-2 bg-blue-50 rounded text-xs">
<div class="font-bold mb-1">主な機能：</div>
<div>• クラウドレコーディング一覧<br/>• 文字起こしファイル管理<br/>• 検索・フィルター機能<br/>• ダウンロード・削除操作</div>
</div>

</div>

<div class="card">

## 🗂️ 文字起こしファイルの活用

<div class="space-y-3 mt-3">
  <div class="p-2 bg-blue-100 rounded">
    <div class="font-bold text-blue-800 text-sm">📥 ダウンロード</div>
    <div class="text-xs">文字起こしファイルをローカルに保存</div>
  </div>
  
  <div class="p-2 bg-green-100 rounded">
    <div class="font-bold text-green-800 text-sm">📝 編集・修正</div>
    <div class="text-xs">必要に応じて内容を調整</div>
  </div>
  
  <div class="p-2 bg-purple-100 rounded">
    <div class="font-bold text-purple-800 text-sm">🔄 NoteBookLM連携</div>
    <div class="text-xs">要約・整理のための入力として活用</div>
  </div>
</div>

</div>

</div>

---
layout: default
---

# 🎥 Zoom Pro実践：AI字幕の詳細設定

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="card">

## ⚙️ AI字幕の設定画面

<div class="text-center">
  <img src="/zoom_ai/zoom_ai2.png" alt="Zoom AI字幕設定" class="w-full h-auto rounded-lg shadow-md mb-3" />
  <div class="text-xs text-gray-600">AI字幕の詳細設定とカスタマイズ</div>
</div>

</div>

<div class="card">

## 🎯 字幕設定のポイント

<div class="space-y-2 mt-2">
  <div class="p-2 bg-blue-100 rounded">
    <div class="font-bold text-blue-800 text-sm">🌐 言語設定</div>
    <div class="text-xs">日本語・英語など複数言語対応</div>
  </div>
  
  <div class="p-2 bg-green-100 rounded">
    <div class="font-bold text-green-800 text-sm">📊 字幕表示</div>
    <div class="text-xs">リアルタイム表示と録画保存</div>
  </div>
  
  <div class="p-2 bg-purple-100 rounded">
    <div class="font-bold text-purple-800 text-sm">🎨 カスタマイズ</div>
    <div class="text-xs">フォント・サイズ・色の調整</div>
  </div>
</div>

</div>

</div>

---
layout: default
---

# 🧠 ワークフロー2：NoteBookLM要約・整理

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="card">

## 🎯 NoteBookLMの基本機能

<div class="space-y-2 mt-2">
  <div class="p-2 bg-blue-100 rounded">
    <div class="font-bold text-blue-800 text-sm">📚 文書要約・分析</div>
    <div class="text-xs">Zoom字幕、PDF、ウェブ記事を自動分析</div>
  </div>
  
  <div class="p-2 bg-green-100 rounded">
    <div class="font-bold text-green-800 text-sm">🧠 知識の構造化</div>
    <div class="text-xs">複雑な情報を分かりやすく整理</div>
  </div>
  
  <div class="p-2 bg-purple-100 rounded">
    <div class="font-bold text-purple-800 text-sm">💡 学習支援</div>
    <div class="text-xs">学生向けに平易化・カスタマイズ</div>
  </div>
</div>

</div>

<div class="card">

## 🎓 学生向け活用ポイント

<div class="space-y-2 mt-2">
  <div class="p-2 bg-green-100 rounded">
    <div class="font-bold text-green-800 text-sm">📝 暗記カード作成</div>
    <div class="text-xs">重要なポイントを穴埋め問題形式で</div>
  </div>
  
  <div class="p-2 bg-blue-100 rounded">
    <div class="font-bold text-blue-800 text-sm">🧪 実験計画支援</div>
    <div class="text-xs">理論を証明する実験を提案</div>
  </div>
  
  <div class="p-2 bg-purple-100 rounded">
    <div class="font-bold text-purple-800 text-sm">📊 研究プロジェクト管理</div>
    <div class="text-xs">情報収集からレポート作成まで</div>
  </div>
</div>

</div>

</div>

---
layout: default
---

# 🧠 NoteBookLM実践：多様なソースからの要約・整理

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="card">

## 📋 基本的な要約プロセス

<div class="space-y-2 mt-2">
  <div class="p-2 bg-blue-100 rounded">
    <div class="font-bold text-blue-800 text-sm">1️⃣ 字幕ファイルアップロード</div>
    <div class="text-xs">Zoom Proで生成された字幕をNoteBookLMに投入</div>
  </div>
  
  <div class="p-2 bg-green-100 rounded">
    <div class="font-bold text-green-800 text-sm">2️⃣ AI要約の実行</div>
    <div class="text-xs">「要点を3つの箇条書きで」など具体的指示</div>
  </div>
  
  <div class="p-2 bg-purple-100 rounded">
    <div class="font-bold text-purple-800 text-sm">3️⃣ 学生向け平易化</div>
    <div class="text-xs">「高校生向けに分かりやすく」で専門用語を解説</div>
  </div>
</div>

</div>

<div class="card">

## 💡 効果的なプロンプト例

<div class="space-y-2 mt-2">
  <div class="p-2 bg-green-100 rounded">
    <div class="font-bold text-green-800 text-sm">📚 学習支援系</div>
    <div class="text-xs">「この内容で5つのテスト予想問題を作成して」</div>
  </div>
  
  <div class="p-2 bg-blue-100 rounded">
    <div class="font-bold text-blue-800 text-sm">🔍 分析系</div>
    <div class="text-xs">「話者の主張と証拠の信頼性を評価して」</div>
  </div>
  
  <div class="p-2 bg-purple-100 rounded">
    <div class="font-bold text-purple-800 text-sm">🎯 応用系</div>
    <div class="text-xs">「教育現場での活用方法を3つ提案して」</div>
  </div>
</div>

</div>

</div>

---
layout: default
---

# 🔄 Zoom AI + NoteBookLM連携ワークフロー

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="card">

## 🎯 連携の流れ

<div class="space-y-3 mt-3">
  <div class="p-2 bg-blue-100 rounded">
    <div class="font-bold text-blue-800 text-sm">1️⃣ Zoom Pro AI</div>
    <div class="text-xs">ミーティング録画・AI字幕生成</div>
  </div>
  
  <div class="p-2 bg-green-100 rounded">
    <div class="font-bold text-green-800 text-sm">2️⃣ 文字起こしファイル</div>
    <div class="text-xs">字幕ファイルをダウンロード</div>
  </div>
  
  <div class="p-2 bg-purple-100 rounded">
    <div class="font-bold text-purple-800 text-sm">3️⃣ NoteBookLM</div>
    <div class="text-xs">要約・分析・構造化</div>
  </div>
</div>

</div>

<div class="card">

## 💡 連携のメリット

<div class="space-y-3 mt-3">
  <div class="p-2 bg-green-100 rounded">
    <div class="font-bold text-green-800 text-sm">⏰ 時間効率化</div>
    <div class="text-xs">手動文字起こしの手間を削減</div>
  </div>
  
  <div class="p-2 bg-blue-100 rounded">
    <div class="font-bold text-blue-800 text-sm">🧠 深い分析</div>
    <div class="text-xs">AIが内容を構造化・要約</div>
  </div>
  
  <div class="p-2 bg-purple-100 rounded">
    <div class="font-bold text-purple-800 text-sm">📊 知識管理</div>
    <div class="text-xs">会議内容を体系的に整理</div>
  </div>
</div>

</div>

</div>

---
layout: default
---

# 🧠 NoteBookLM活用事例：Zoom文字起こしからメモ作成

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="card">

## 📝 Zoom文字起こしの活用

<div class="text-center">
  <img src="/notebooklm/zoom_notebooklm_memo.png" alt="Zoom文字起こしからメモ作成" class="w-full h-auto rounded-lg shadow-md mb-3" />
  <div class="text-xs text-gray-600">Zoomの文字起こしを基にした詳細なメモ作成</div>
</div>

<div class="mt-3 p-2 bg-blue-50 rounded text-xs">
<div class="font-bold mb-1">作成されるメモ：</div>
<div>• 会議の要点まとめ<br/>• 重要な決定事項<br/>• アクションアイテム<br/>• 次回への課題</div>
</div>

</div>

<div class="card">

## 💡 メモ作成のポイント

<div class="space-y-3 mt-3">
  <div class="p-2 bg-blue-100 rounded">
    <div class="font-bold text-blue-800 text-sm">📋 構造化</div>
    <div class="text-xs">情報を論理的に整理</div>
  </div>
  
  <div class="p-2 bg-green-100 rounded">
    <div class="font-bold text-green-800 text-sm">🔍 重要度</div>
    <div class="text-xs">優先順位をつけて整理</div>
  </div>
  
  <div class="p-2 bg-purple-100 rounded">
    <div class="font-bold text-purple-800 text-sm">📅 時系列</div>
    <div class="text-xs">議論の流れを時系列で整理</div>
  </div>
</div>

</div>

</div>

---
layout: default
---

# 🧠 NoteBookLM活用事例：Zoom文字起こしからマインドマップ作成

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="card">

## 🧠 マインドマップでの構造化

<div class="text-center">
  <img src="/notebooklm/zoom_notebooklm_mindmap.png" alt="Zoom文字起こしからマインドマップ作成" class="w-full h-auto rounded-lg shadow-md mb-3" />
  <div class="text-xs text-gray-600">会議内容をマインドマップで視覚的に整理</div>
</div>

<div class="mt-3 p-2 bg-green-50 rounded text-xs">
<div class="font-bold mb-1">マインドマップの特徴：</div>
<div>• 階層構造での整理<br/>• 関連性の可視化<br/>• 全体像の把握<br/>• 記憶の定着促進</div>
</div>

</div>

<div class="card">

## 🎯 マインドマップ活用のポイント

<div class="space-y-3 mt-3">
  <div class="p-2 bg-green-100 rounded">
    <div class="font-bold text-green-800 text-sm">🎨 視覚的整理</div>
    <div class="text-xs">複雑な議論を図解化</div>
  </div>
  
  <div class="p-2 bg-blue-100 rounded">
    <div class="font-bold text-blue-800 text-sm">🔗 関連性発見</div>
    <div class="text-xs">隠れたつながりを発見</div>
  </div>
  
  <div class="p-2 bg-purple-100 rounded">
    <div class="font-bold text-purple-800 text-sm">📚 学習効果</div>
    <div class="text-xs">理解度と記憶の向上</div>
  </div>
</div>

</div>

</div>

---
layout: default
---

# 🧠 NoteBookLM実践：インターフェースと基本操作

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="card">

## 🖥️ NoteBookLMのメイン画面

<div class="text-center">
  <img src="/notebooklm/notebooklm1.png" alt="NoteBookLM メイン画面" class="w-full h-auto rounded-lg shadow-md mb-3" />
  <div class="text-xs text-gray-600">左：ソース、中央：チャット、右：Studio > メモの3パネル構成</div>
</div>

<div class="mt-3 p-2 bg-blue-50 rounded text-xs">
<div class="font-bold mb-1">画面構成：</div>
<div>• 左：ソース管理（YouTube動画、PDF等）<br/>• 中央：AIとの対話・要約<br/>• 右：生成されたメモ・資料</div>
</div>

</div>

<div class="card">

## 🔍 ソース管理と分析

<div class="space-y-3 mt-3">
  <div class="p-2 bg-blue-100 rounded">
    <div class="font-bold text-blue-800 text-sm">📁 ソース追加</div>
    <div class="text-xs">YouTube動画、PDF、ウェブ記事を簡単追加</div>
  </div>
  
  <div class="p-2 bg-green-100 rounded">
    <div class="font-bold text-green-800 text-sm">🔗 複数ソース連携</div>
    <div class="text-xs">複数の資料を同時に分析・比較</div>
  </div>
  
  <div class="p-2 bg-purple-100 rounded">
    <div class="font-bold text-purple-800 text-sm">📊 自動要約生成</div>
    <div class="text-xs">AIが内容を分析して構造化</div>
  </div>
</div>

</div>

</div>

---
layout: default
---

# 🧠 NoteBookLM実践：詳細分析とメモ作成

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="card">

## 📝 詳細なブリーフィング資料

<div class="text-center">
  <img src="/notebooklm/notebooklm2.png" alt="NoteBookLM 詳細分析画面" class="w-full h-auto rounded-lg shadow-md mb-3" />
  <div class="text-xs text-gray-600">AIが生成した詳細な分析資料とメモ</div>
</div>

<div class="mt-3 p-2 bg-green-50 rounded text-xs">
<div class="font-bold mb-1">生成される内容：</div>
<div>• 詳細ブリーフィング資料<br/>• 多角的分析<br/>• 実践的な対処法<br/>• 専門家の見解まとめ</div>
</div>

</div>

<div class="card">

## 🎯 実践的な活用例

<div class="space-y-3 mt-3">
  <div class="p-2 bg-green-100 rounded">
    <div class="font-bold text-green-800 text-sm">📚 学習資料作成</div>
    <div class="text-xs">複雑な内容を学生向けに平易化</div>
  </div>
  
  <div class="p-2 bg-blue-100 rounded">
    <div class="font-bold text-blue-800 text-sm">🔬 研究分析</div>
    <div class="text-xs">複数資料の比較・統合分析</div>
  </div>
  
  <div class="p-2 bg-purple-100 rounded">
    <div class="font-bold text-purple-800 text-sm">📊 レポート構成</div>
    <div class="text-xs">研究の骨子と構成案を自動生成</div>
  </div>
</div>

</div>

</div>

---
layout: default
---

# 🎨 ワークフロー3：Sora画像・動画生成

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="card">

## 🖼️ OpenAI Soraの活用

<div class="space-y-3 mt-3">
  <div class="p-2 bg-blue-100 rounded">
    <div class="font-bold text-blue-800 text-sm">🎨 高品質画像生成</div>
    <div class="text-xs">テキスト説明からリアルな画像作成</div>
  </div>
  
  <div class="p-2 bg-green-100 rounded">
    <div class="font-bold text-green-800 text-sm">🎬 短編動画生成</div>
    <div class="text-xs">数秒の動画クリップを自動生成</div>
  </div>
  
  <div class="p-2 bg-purple-100 rounded">
    <div class="font-bold text-purple-800 text-sm">🔧 詳細な指示</div>
    <div class="text-xs">具体的な設定・スタイルの指定</div>
  </div>
</div>

</div>

<div class="card">

## 💡 実践のポイント

<div class="space-y-3 mt-3">
  <div class="p-2 bg-green-100 rounded">
    <div class="font-bold text-green-800 text-sm">🎯 具体的な指示</div>
    <div class="text-xs">「学祭の会場の様子、明るい雰囲気」</div>
  </div>
  
  <div class="p-2 bg-blue-100 rounded">
    <div class="font-bold text-blue-800 text-sm">✅ 生成結果の調整</div>
    <div class="text-xs">複数生成して最適なものを選択</div>
  </div>
  
  <div class="p-2 bg-purple-100 rounded">
    <div class="font-bold text-purple-800 text-sm">🔄 次のステップ</div>
    <div class="text-xs">Veo2での動画生成</div>
  </div>
</div>

</div>

</div>

---
layout: default
---

# 🎨 Sora実践：画像生成の手順

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="card">

## 📝 プロンプト入力画面

<div class="text-center">
  <img src="/sora/sora_imagegen.png" alt="Sora 画像生成プロンプト入力" class="w-full h-auto rounded-lg shadow-md mb-3" />
  <div class="text-xs text-gray-600">詳細なプロンプトを入力して画像生成を開始</div>
</div>

<div class="mt-3 p-2 bg-gray-50 rounded text-xs">
<div class="font-bold mb-1">プロンプト例：</div>
<div>"Professional female Japanese mechanic with medium-length golden hair, wearing work uniform, draining engine oil from underneath a blue Honda Civic car in a workshop..."</div>
</div>

</div>

<div class="card">

## ⚙️ 生成オプション設定

<div class="space-y-3 mt-3">
  <div class="p-2 bg-blue-100 rounded">
    <div class="font-bold text-blue-800 text-sm">🖼️ 生成モード</div>
    <div class="text-xs">Image（画像）を選択</div>
  </div>
  
  <div class="p-2 bg-green-100 rounded">
    <div class="font-bold text-green-800 text-sm">📐 アスペクト比</div>
    <div class="text-xs">2:3（縦長）を選択</div>
  </div>
  
  <div class="p-2 bg-purple-100 rounded">
    <div class="font-bold text-purple-800 text-sm">🔄 生成数</div>
    <div class="text-xs">2v（2バージョン）で複数生成</div>
  </div>
  
  <div class="p-2 bg-orange-100 rounded">
    <div class="font-bold text-orange-800 text-sm">🚀 生成開始</div>
    <div class="text-xs">上向き矢印で生成を実行</div>
  </div>
</div>

</div>

</div>

---
layout: default
---

# 🎨 Sora実践：ライブラリでの結果確認

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="card">

## 📚 生成結果のライブラリ

<div class="text-center">
  <img src="/sora/sora_imagelibrary.png" alt="Sora 画像ライブラリ" class="w-full h-auto rounded-lg shadow-md mb-3" />
  <div class="text-xs text-gray-600">生成された画像をライブラリで管理・確認</div>
</div>

</div>

<div class="card">

## 💡 ライブラリの活用方法

<div class="space-y-3 mt-3">
  <div class="p-2 bg-blue-100 rounded">
    <div class="font-bold text-blue-800 text-sm">📁 メディア管理</div>
    <div class="text-xs">生成された画像・動画を整理</div>
  </div>
  
  <div class="p-2 bg-green-100 rounded">
    <div class="font-bold text-green-800 text-sm">⭐ お気に入り</div>
    <div class="text-xs">気に入った作品を保存</div>
  </div>
  
  <div class="p-2 bg-purple-100 rounded">
    <div class="font-bold text-purple-800 text-sm">📤 アップロード</div>
    <div class="text-xs">外部画像の追加も可能</div>
  </div>
  
  <div class="p-2 bg-orange-100 rounded">
    <div class="font-bold text-orange-800 text-sm">🔍 検索・整理</div>
    <div class="text-xs">プロンプトで作品を検索</div>
  </div>
</div>

</div>

</div>

---
layout: default
---

# 🎬 ワークフロー4：Veo2動画生成

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="card">

## 🎥 Google AI Studio Veo2

<div class="space-y-3 mt-3">
  <div class="p-2 bg-blue-100 rounded">
    <div class="font-bold text-blue-800 text-sm">📹 高品質動画作成</div>
    <div class="text-xs">[Google AI Studio](https://aistudio.google.com/prompts/new_video)でプロ品質の動画生成</div>
  </div>
  
  <div class="p-2 bg-green-100 rounded">
    <div class="font-bold text-green-800 text-sm">🎭 ストーリー性</div>
    <div class="text-xs">物語性のある動画を自動生成</div>
  </div>
  
  <div class="p-2 bg-purple-100 rounded">
    <div class="font-bold text-purple-800 text-sm">🔗 Google統合</div>
    <div class="text-xs">Googleアカウントでシームレス連携</div>
  </div>
</div>

</div>

<div class="card">

## 💡 実践のポイント

<div class="space-y-3 mt-3">
  <div class="p-2 bg-green-100 rounded">
    <div class="font-bold text-green-800 text-sm">🎯 具体的な指示</div>
    <div class="text-xs">「学祭の様子を1分間の動画で」</div>
  </div>
  
  <div class="p-2 bg-blue-100 rounded">
    <div class="font-bold text-blue-800 text-sm">✅ 生成結果の調整</div>
    <div class="text-xs">Google AI Studioで細かい調整</div>
  </div>
  
  <div class="p-2 bg-purple-100 rounded">
    <div class="font-bold text-purple-800 text-sm">🔄 次のステップ</div>
    <div class="text-xs">Mapify + Gammaでの資料作成</div>
  </div>
</div>

</div>

</div>

---
layout: default
---

# 🎬 Veo2実践：動画生成の手順

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="card">

## 📝 動画生成プロンプト入力

<div class="text-center">
  <img src="/veo2/veo2_gen_vid.png" alt="Veo2 動画生成プロンプト入力" class="w-full h-auto rounded-lg shadow-md mb-3" />
  <div class="text-xs text-gray-600">Google AI Studioで動画生成のプロンプトを入力</div>
</div>

<div class="mt-3 p-2 bg-gray-50 rounded text-xs">
<div class="font-bold mb-1">プロンプト例：</div>
<div>"学祭の様子を1分間の動画で。明るい雰囲気、学生たちの笑顔、イベントの盛り上がりを表現"</div>
</div>

</div>

<div class="card">

## ⚙️ Veo2の生成オプション

<div class="space-y-3 mt-3">
  <div class="p-2 bg-blue-100 rounded">
    <div class="font-bold text-blue-800 text-sm">🎬 動画生成</div>
    <div class="text-xs">テキストから動画を自動生成</div>
  </div>
  
  <div class="p-2 bg-green-100 rounded">
    <div class="font-bold text-green-800 text-sm">⏱️ 動画の長さ</div>
    <div class="text-xs">数秒〜数分の動画を作成</div>
  </div>
  
  <div class="p-2 bg-purple-100 rounded">
    <div class="font-bold text-purple-800 text-sm">🎨 スタイル設定</div>
    <div class="text-xs">動画の雰囲気やテーマを指定</div>
  </div>
  
  <div class="p-2 bg-orange-100 rounded">
    <div class="font-bold text-orange-800 text-sm">🚀 生成開始</div>
    <div class="text-xs">AIが動画を自動生成</div>
  </div>
</div>

</div>

</div>

---
layout: default
---

# 🎬 Veo2実践：動画のダウンロード

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="card">

## 📥 生成された動画の確認

<div class="text-center">
  <img src="/veo2/veo2_download_vid.png" alt="Veo2 動画ダウンロード" class="w-full h-auto rounded-lg shadow-md mb-3" />
  <div class="text-xs text-gray-600">生成された動画を確認・ダウンロード</div>
</div>

</div>

<div class="card">

## 💡 動画の活用方法

<div class="space-y-3 mt-3">
  <div class="p-2 bg-blue-100 rounded">
    <div class="font-bold text-blue-800 text-sm">📱 SNS投稿</div>
    <div class="text-xs">Instagram、TikTok、YouTubeなど</div>
  </div>
  
  <div class="p-2 bg-green-100 rounded">
    <div class="font-bold text-green-800 text-sm">🎨 プレゼン資料</div>
    <div class="text-xs">Gammaでのスライドに組み込み</div>
  </div>
  
  <div class="p-2 bg-purple-100 rounded">
    <div class="font-bold text-purple-800 text-sm">📚 学習教材</div>
    <div class="text-xs">授業や説明動画として活用</div>
  </div>
  
  <div class="p-2 bg-orange-100 rounded">
    <div class="font-bold text-orange-800 text-sm">🔄 編集・加工</div>
    <div class="text-xs">他の動画編集ソフトで調整</div>
  </div>
</div>

</div>

</div>

---
layout: default
---

# 🎨 ワークフロー5：Mapify + Gamma

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="card">

## 🎯 Mapifyの基本機能

<div class="space-y-3 mt-3">
  <div class="p-2 bg-blue-100 rounded">
    <div class="font-bold text-blue-800 text-sm">🔗 YouTube連携</div>
    <div class="text-xs">YouTubeリンクから自動でマインドマップ生成</div>
  </div>
  
  <div class="p-2 bg-green-100 rounded">
    <div class="font-bold text-green-800 text-sm">🧠 マインドマップ作成</div>
    <div class="text-xs">AIが内容を分析して構造化</div>
  </div>
  
  <div class="p-2 bg-purple-100 rounded">
    <div class="font-bold text-purple-800 text-sm">📝 マークダウン出力</div>
    <div class="text-xs">Gammaでのスライド作成に最適化</div>
  </div>
</div>

</div>

<div class="card">

## 🎨 Gammaとの連携

<div class="space-y-3 mt-3">
  <div class="p-2 bg-green-100 rounded">
    <div class="font-bold text-green-800 text-sm">📊 スライド自動生成</div>
    <div class="text-xs">マークダウンから美しいプレゼン資料</div>
  </div>
  
  <div class="p-2 bg-blue-100 rounded">
    <div class="font-bold text-blue-800 text-sm">🖼️ 画像自動挿入</div>
    <div class="text-xs">AIが適切な画像を自動選択</div>
  </div>
  
  <div class="p-2 bg-purple-100 rounded">
    <div class="font-bold text-purple-800 text-sm">📤 多形式エクスポート</div>
    <div class="text-xs">PDF、PowerPoint、画像など</div>
  </div>
</div>

</div>

</div>

---
layout: default
---

# 🧠 Mapify実践：YouTubeからマインドマップ作成

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="card">

## 🔗 YouTubeリンク入力

<div class="text-center">
  <img src="/mapify/mapify1.png" alt="Mapify YouTubeリンク入力" class="w-full h-auto rounded-lg shadow-md mb-3" />
  <div class="text-xs text-gray-600">YouTubeのURLを入力してマインドマップ生成を開始</div>
</div>

<div class="mt-3 p-2 bg-gray-50 rounded text-xs">
<div class="font-bold mb-1">入力例：</div>
<div>https://www.youtube.com/watch?v=...</div>
</div>

</div>

<div class="card">

## ⏳ マインドマップ生成中

<div class="text-center">
  <img src="/mapify/mapify2.png" alt="Mapify マインドマップ生成中" class="w-full h-auto rounded-lg shadow-md mb-3" />
  <div class="text-xs text-gray-600">AIが動画内容を分析してマインドマップを作成中</div>
</div>

<div class="mt-3 p-2 bg-blue-50 rounded text-xs">
<div class="font-bold mb-1">生成プロセス：</div>
<div>1. 動画内容の解析<br/>2. キーワード抽出<br/>3. 構造化されたマインドマップ作成</div>
</div>

</div>

</div>

---
layout: default
---

# 🧠 Mapify実践：生成されたマインドマップ

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="card">

## 🎯 完成したマインドマップ

<div class="text-center">
  <img src="/mapify/mapify3.png" alt="Mapify 生成されたマインドマップ" class="w-full h-auto rounded-lg shadow-md mb-3" />
  <div class="text-xs text-gray-600">AIが生成した構造化されたマインドマップ</div>
</div>

<div class="mt-3 p-2 bg-green-50 rounded text-xs">
<div class="font-bold mb-1">特徴：</div>
<div>• 階層構造で整理<br/>• 関連性が明確<br/>• 視覚的に分かりやすい</div>
</div>

</div>

<div class="card">

## 🔍 マインドマップの詳細表示

<div class="text-center">
  <img src="/mapify/mapify4.png" alt="Mapify マインドマップ詳細" class="w-full h-auto rounded-lg shadow-md mb-3" />
  <div class="text-xs text-gray-600">拡大表示で細かい内容を確認</div>
</div>

<div class="mt-3 p-2 bg-purple-50 rounded text-xs">
<div class="font-bold mb-1">確認ポイント：</div>
<div>• 内容の正確性<br/>• 構造の合理性<br/>• 必要に応じた調整</div>
</div>

</div>

</div>

---
layout: default
---

# 🧠 Mapify実践：マークダウン出力

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="card">

## 📝 エクスポートオプション

<div class="text-center">
  <img src="/mapify/mapify5.png" alt="Mapify エクスポートオプション" class="w-full h-auto rounded-lg shadow-md mb-2" />
  <div class="text-xs text-gray-600">様々な形式でエクスポート可能</div>
</div>

<div class="mt-2 p-2 bg-orange-50 rounded text-xs">
<div class="font-bold mb-1">出力形式：</div>
<div>• Markdown (.md)<br/>• 画像 (.png)<br/>• PDF (.pdf)</div>
</div>

</div>

<div class="card">

## 🎯 Gamma用マークダウン

<div class="space-y-3 mt-3">
  <div class="p-2 bg-blue-100 rounded">
    <div class="font-bold text-blue-800 text-sm">📋 構造化されたテキスト</div>
    <div class="text-xs">Gammaが理解しやすい形式</div>
  </div>
  
  <div class="p-2 bg-green-100 rounded">
    <div class="font-bold text-green-800 text-sm">🔗 階層関係の保持</div>
    <div class="text-xs">見出しレベルが明確</div>
  </div>
  
  <div class="p-2 bg-purple-100 rounded">
    <div class="font-bold text-purple-800 text-sm">📝 キーポイント抽出</div>
    <div class="text-xs">重要な情報が整理済み</div>
  </div>
</div>

</div>

</div>

---
layout: default
---

# 🎨 Gamma実践：マークダウンからスライド作成

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="card">

## 🚀 Gamma.app/create アクセス

<div class="text-center">
  <img src="/mapify/m_gamma1.png" alt="Gamma テキスト入力選択" class="w-full h-auto rounded-lg shadow-md mb-3" />
  <div class="text-xs text-gray-600">Gammaにアクセスしてテキストを貼り付けるを選択</div>
</div>

<div class="mt-3 p-2 bg-blue-50 rounded text-xs">
<div class="font-bold mb-1">手順：</div>
<div>1. gamma.app/create にアクセス<br/>2. 「テキストを貼り付ける」を選択<br/>3. Mapifyのマークダウンを貼り付け</div>
</div>

</div>

<div class="card">

## 📊 プレゼンテーション形式選択

<div class="text-center">
  <img src="/mapify/m_gamma2.png" alt="Gamma プレゼンテーション選択" class="w-full h-auto rounded-lg shadow-md mb-3" />
  <div class="text-xs text-gray-600">プレゼンテーションを選択してマークダウンを貼り付け</div>
</div>

<div class="mt-3 p-2 bg-green-50 rounded text-xs">
<div class="font-bold mb-1">選択項目：</div>
<div>• プレゼンテーション<br/>• ドキュメント<br/>• ウェブページ<br/>• その他</div>
</div>

</div>

</div>

---
layout: default
---

# 🎨 Gamma実践：生成オプション設定

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="card">

## ⚙️ 生成オプションの選択

<div class="text-center">
  <img src="/mapify/m_gamma3.png" alt="Gamma 生成オプション選択" class="w-full h-auto rounded-lg shadow-md mb-3" />
  <div class="text-xs text-gray-600">スライドのスタイルやレイアウトを選択</div>
</div>

<div class="mt-3 p-2 bg-purple-50 rounded text-xs">
<div class="font-bold mb-1">オプション：</div>
<div>• テーマ選択<br/>• カラーパレット<br/>• レイアウトスタイル<br/>• アニメーション</div>
</div>

</div>

<div class="card">

## 🎨 プレゼンテーション設定

<div class="text-center">
  <img src="/mapify/m_gamma4.png" alt="Gamma プレゼンテーション設定" class="w-full h-auto rounded-lg shadow-md mb-2" />
  <div class="text-xs text-gray-600">詳細な設定でカスタマイズ</div>
</div>

<div class="mt-2 p-2 bg-orange-50 rounded text-xs">
<div class="font-bold mb-1">設定項目：</div>
<div>• スライド数<br/>• 画像の自動挿入<br/>• フォント・サイズ</div>
</div>

</div>

</div>

---
layout: default
---

# 🎨 Gamma実践：完成したプレゼンテーション

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="card">

## ✨ 生成されたプレゼンテーション

<div class="text-center">
  <img src="/mapify/m_gamma5.png" alt="Gamma 生成されたプレゼンテーション" class="w-full h-auto rounded-lg shadow-md mb-3" />
  <div class="text-xs text-gray-600">AIが自動生成した美しいスライド</div>
</div>

<div class="mt-3 p-2 bg-green-50 rounded text-xs">
<div class="font-bold mb-1">特徴：</div>
<div>• プロフェッショナルなデザイン<br/>• 適切な画像の自動挿入<br/>• 読みやすいレイアウト<br/>• 一貫性のあるスタイル</div>
</div>

</div>

<div class="card">

## 📤 エクスポートオプション

<div class="text-center">
  <img src="/mapify/m_gamma6.png" alt="Gamma エクスポートオプション" class="w-full h-auto rounded-lg shadow-md mb-2" />
  <div class="text-xs text-gray-600">様々な形式でエクスポート可能</div>
</div>

<div class="mt-2 p-2 bg-blue-50 rounded text-xs">
<div class="font-bold mb-1">出力形式：</div>
<div>• PowerPoint (.pptx)<br/>• PDF (.pdf)<br/>• 画像 (.png)<br/>• ウェブページ</div>
</div>

</div>

</div>

---
layout: default
---

# 🚀 Difyによる高度なAIワークフロー

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="card">

## 🎯 Difyとは

<div class="space-y-2 mt-2">
  <div class="p-2 bg-blue-100 rounded">
    <div class="font-bold text-blue-800 text-sm">🤖 ノーコードAI開発</div>
    <div class="text-xs">プログラミング不要でAIアプリ作成</div>
  </div>
  
  <div class="p-2 bg-green-100 rounded">
    <div class="font-bold text-green-800 text-sm">🔗 複数AIモデル対応</div>
    <div class="text-xs">Gemini、OpenAI、Claudeなど</div>
  </div>
  
  <div class="p-2 bg-purple-100 rounded">
    <div class="font-bold text-purple-800 text-sm">📊 ビジュアルワークフロー</div>
    <div class="text-xs">ドラッグ&ドロップで簡単構築</div>
  </div>
</div>

</div>

<div class="card">

## 💡 今回紹介するワークフロー

<div class="space-y-2 mt-2">
  <div class="p-2 bg-orange-100 rounded">
    <div class="font-bold text-orange-800 text-sm">📝 Google Forms</div>
    <div class="text-xs">アンケート回答の収集</div>
  </div>
  
  <div class="p-2 bg-blue-100 rounded">
    <div class="font-bold text-blue-800 text-sm">🤖 Dify API</div>
    <div class="text-xs">AIによる回答分析・レビュー</div>
  </div>
  
  <div class="p-2 bg-green-100 rounded">
    <div class="font-bold text-green-800 text-sm">📧 GAS + PDF</div>
    <div class="text-xs">自動メール送信・レポート添付</div>
  </div>
</div>

</div>

</div>

---
layout: default
---

# 🔄 Difyワークフロー：Google Forms → Dify API → GAS → PDF Email

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="card">

## 📊 ワークフローの全体像

<div class="text-center">
  <img src="/dify/dify1.png" alt="Difyワークフロー全体像" class="w-full h-auto rounded-lg shadow-md mb-3" />
  <div class="text-xs text-gray-600">Dify Studioでのワークフロー構築画面</div>
</div>

<div class="mt-3 p-2 bg-blue-50 rounded text-xs">
<div class="font-bold mb-1">ワークフロー構成：</div>
<div>• 開始ノード（入力受付）<br/>• LLMノード（AI処理）<br/>• 回答ノード（結果出力）</div>
</div>

</div>

<div class="card">

## 🎯 各ステップの役割

<div class="space-y-3 mt-3">
  <div class="p-2 bg-blue-100 rounded">
    <div class="font-bold text-blue-800 text-sm">1️⃣ Google Forms</div>
    <div class="text-xs">ユーザーからの回答を収集</div>
  </div>
  
  <div class="p-2 bg-green-100 rounded">
    <div class="font-bold text-green-800 text-sm">2️⃣ Dify API</div>
    <div class="text-xs">AIが回答を分析・レビュー</div>
  </div>
  
  <div class="p-2 bg-purple-100 rounded">
    <div class="font-bold text-purple-800 text-sm">3️⃣ GAS</div>
    <div class="text-xs">結果をPDF化・メール送信</div>
  </div>
</div>

</div>

</div>

---
layout: default
---

# 🤖 Dify LLM設定：AIモデルの選択と設定

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="card">

## ⚙️ LLMノードの設定画面

<div class="text-center">
  <img src="/dify/dify_llm.png" alt="Dify LLM設定画面" class="w-full h-auto rounded-lg shadow-md mb-3" />
  <div class="text-xs text-gray-600">LLMノードでのAIモデル設定とプロンプト定義</div>
</div>

<div class="mt-3 p-2 bg-green-50 rounded text-xs">
<div class="font-bold mb-1">設定内容：</div>
<div>• AIモデル：Gemini 2.5 Flash-Lite<br/>• システムプロンプト：猫っぽく元気よく回答<br/>• ユーザー入力：アンケート回答データ</div>
</div>

</div>

<div class="card">

## 🎯 プロンプトエンジニアリング

<div class="space-y-3 mt-3">
  <div class="p-2 bg-blue-100 rounded">
    <div class="font-bold text-blue-800 text-sm">🐱 システムプロンプト</div>
    <div class="text-xs">「ユーザの質問に対して、猫っぽく元気よく回答してください」</div>
  </div>
  
  <div class="p-2 bg-green-100 rounded">
    <div class="font-bold text-green-800 text-sm">📝 ユーザー入力</div>
    <div class="text-xs">Google Formsからの回答データを変数として設定</div>
  </div>
  
  <div class="p-2 bg-purple-100 rounded">
    <div class="font-bold text-purple-800 text-sm">🔧 出力制御</div>
    <div class="text-xs">Jinjaテンプレートで動的な内容生成</div>
  </div>
</div>

</div>

</div>

---
layout: default
---

# 🎨 Difyモデル選択：Gemini 2.5 Flash-Lite

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="card">

## 🔍 モデル選択画面

<div class="text-center">
  <img src="/dify/dify_models.png" alt="Dify モデル選択画面" class="w-full h-auto rounded-lg shadow-md mb-3" />
  <div class="text-xs text-gray-600">利用可能なAIモデルの一覧と選択</div>
</div>

</div>

<div class="card">

## 💡 Gemini 2.5 Flash-Liteの特徴

<div class="space-y-3 mt-3">
  <div class="p-2 bg-blue-100 rounded">
    <div class="font-bold text-blue-800 text-sm">⚡ 高速処理</div>
    <div class="text-xs">軽量で高速な応答</div>
  </div>
  
  <div class="p-2 bg-green-100 rounded">
    <div class="font-bold text-green-800 text-sm">🎯 高精度</div>
    <div class="text-xs">日本語での自然な回答</div>
  </div>
  
  <div class="p-2 bg-purple-100 rounded">
    <div class="font-bold text-purple-800 text-sm">🔗 多機能対応</div>
    <div class="text-xs">チャット、文書処理、画像認識など</div>
  </div>
  
  <div class="p-2 bg-orange-100 rounded">
    <div class="font-bold text-orange-800 text-sm">💰 コスト効率</div>
    <div class="text-xs">高品質ながら低コスト</div>
  </div>
</div>

</div>

</div>

---
layout: default
---

# 📧 最終出力：PDF添付メールの自動送信

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="card">

## 📨 自動送信メール

<div class="text-center">
  <img src="/dify/dify_email.jpg" alt="Dify 自動送信メール" class="w-full h-auto rounded-lg shadow-md mb-3" />
  <div class="text-xs text-gray-600">AIレビュー報告書がPDFで添付された自動メール</div>
</div>

<div class="mt-3 p-2 bg-blue-50 rounded text-xs">
<div class="font-bold mb-1">メール内容：</div>
<div>• 件名：【AIレビュー】アンケート回答のレビュー報告書<br/>• 添付：review.pdf（127KB）<br/>• 送信者：AIアンケートレビューシステム</div>
</div>

</div>

<div class="card">

## 📊 PDFレポートの内容

<div class="text-center">
  <img src="/dify/dify_pdf.jpg" alt="Dify 生成PDFレポート" class="w-full h-auto rounded-lg shadow-md mb-3" />
  <div class="text-xs text-gray-600">AIが生成した詳細なレビュー報告書</div>
</div>

  <div class="mt-3 p-2 bg-green-50 rounded text-xs">
    <div class="font-bold mb-1">レポート構成：</div>
    <div>• 回答者情報<br/>• アンケート回答内容<br/>• AIレビュー（猫っぽい文体）<br/>• 総合評価・改善提案
    </div>
  </div>
</div>

</div>

---
layout: default
---

# 🔄 6つのワークフローの連携

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="card">

## 📋 情報の流れ

<div class="space-y-3 mt-3">
  <div class="flex items-center">
    <div class="w-6 h-6 bg-blue-500 rounded-full flex items-center justify-center text-white font-bold text-xs mr-3">1</div>
    <div class="text-xs">🎥 Zoom Pro：会議録画・AI字幕生成</div>
  </div>
  
  <div class="flex items-center">
    <div class="w-6 h-6 bg-green-500 rounded-full flex items-center justify-center text-white font-bold text-xs mr-3">2</div>
    <div class="text-xs">📝 Notebook LM：要約・整理・構造化</div>
  </div>
  
  <div class="flex items-center">
    <div class="w-6 h-6 bg-purple-500 rounded-full flex items-center justify-center text-white font-bold text-xs mr-3">3</div>
    <div class="text-xs">🎨 Sora：画像・短編動画生成</div>
  </div>
  
  <div class="flex items-center">
    <div class="w-6 h-6 bg-pink-500 rounded-full flex items-center justify-center text-white font-bold text-xs mr-3">4</div>
    <div class="text-xs">🎬 Veo2：Google AI Studio動画生成</div>
  </div>
  
  <div class="flex items-center">
    <div class="w-6 h-6 bg-orange-500 rounded-full flex items-center justify-center text-white font-bold text-xs mr-3">5</div>
    <div class="text-xs">🎨 Mapify + Gamma：資料・スライド作成</div>
  </div>
  
  <div class="flex items-center">
    <div class="w-6 h-6 bg-red-500 rounded-full flex items-center justify-center text-white font-bold text-xs mr-3">6</div>
    <div class="text-xs">🚀 Dify：高度なAIワークフロー自動化</div>
  </div>
</div>

</div>

<div class="card">

## 💡 組み合わせの効果

<div class="space-y-3 mt-3">
  <div class="p-2 bg-green-100 rounded">
    <div class="font-bold text-green-800 text-sm">⚡ 時間効率</div>
    <div class="text-xs">従来の1/10の時間で作業完了</div>
  </div>
  
  <div class="p-2 bg-blue-100 rounded">
    <div class="font-bold text-blue-800 text-sm">🎯 品質向上</div>
    <div class="text-xs">AIによる自動最適化</div>
  </div>
  
  <div class="p-2 bg-purple-100 rounded">
    <div class="font-bold text-purple-800 text-sm">🔄 継続改善</div>
    <div class="text-xs">AI提案による継続的な改善</div>
  </div>
  
  <div class="p-2 bg-pink-100 rounded">
    <div class="font-bold text-pink-800 text-sm">📚 学習効果</div>
    <div class="text-xs">実際の作業を通じて習得</div>
  </div>
</div>

</div>

</div>

---
layout: default
---

# 💡 従来のメモ・ブクマをAIで整理する方法

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="card">

## 📚 従来の課題

<div class="space-y-3 mt-3">
  <div class="p-2 bg-red-100 rounded">
    <div class="font-bold text-red-800 text-sm">📝 メモが散らばっている</div>
    <div class="text-xs">ノート、スマホ、PCに分散</div>
  </div>
  
  <div class="p-2 bg-orange-100 rounded">
    <div class="font-bold text-orange-800 text-sm">🔖 ブクマが整理されていない</div>
    <div class="text-xs">カテゴリ分けができていない</div>
  </div>
  
  <div class="p-2 bg-yellow-100 rounded">
    <div class="font-bold text-yellow-800 text-sm">🔍 必要な情報が見つからない</div>
    <div class="text-xs">検索・関連性が分からない</div>
  </div>
  
  <div class="p-2 bg-blue-100 rounded">
    <div class="font-bold text-blue-800 text-sm">⏰ 整理に時間がかかる</div>
    <div class="text-xs">手動での整理は非効率</div>
  </div>
</div>

</div>

<div class="card">

## 🤖 AIによる解決策

<div class="space-y-3 mt-3">
  <div class="p-2 bg-green-100 rounded">
    <div class="font-bold text-green-800 text-sm">📁 Notebook LMで一元管理</div>
    <div class="text-xs">すべてのメモ・ブクマを統合</div>
  </div>
  
  <div class="p-2 bg-purple-100 rounded">
    <div class="font-bold text-purple-800 text-sm">🔗 自動関連性発見</div>
    <div class="text-xs">AIが関連情報を自動で発見</div>
  </div>
  
  <div class="p-2 bg-indigo-100 rounded">
    <div class="font-bold text-indigo-800 text-sm">📊 構造化・要約</div>
    <div class="text-xs">情報を体系的に整理</div>
  </div>
  
  <div class="p-2 bg-pink-100 rounded">
    <div class="font-bold text-pink-800 text-sm">🔍 高度な検索</div>
    <div class="text-xs">内容ベースでの検索が可能</div>
  </div>
</div>

</div>

</div>

---
layout: center
class: text-center
---

# 🎉 まとめ

<div class="text-6xl mb-8">🚀</div>

## <span class="text-gradient">AI活用でタスク効率化を実現しよう</span>

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="card">

### 🎯 今日学んだこと
- 議事録・メールのAI活用術
- AI活用した要約の実践手法
- タスク効率化のためのAIツール活用
- 従来のメモ・ブクマをAIで整理する方法

</div>

<div class="card">

### 🚀 期待される効果
- **作業時間短縮**
- **情報整理効率向上**
- **品質向上**
- **継続的改善の実現**

</div>

</div>

<div class="mt-6">
  <span class="highlight text-lg">AIと共に、新しい働き方を始めよう！</span>
</div>

---
layout: end
class: text-center
---

# ありがとうございました！

<div class="text-6xl mb-8">🙏</div>


<div class="mt-6 text-lg opacity-80">
  AI活用によるタスク効率化で、あなたの可能性を最大化しましょう！
</div>

<div class="abs-br m-6 flex gap-2">
  <span class="text-sm opacity-50">AI活用によるタスク効率化 | 90分講義完了</span>
</div>
