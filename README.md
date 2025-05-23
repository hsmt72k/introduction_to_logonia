<img src="./images/logonia_cover.png" />

<div align="center">
  <div>
    <img src="https://img.shields.io/badge/Next.js-000?style=for-the-badge&logo=nextdotjs&logoColor=fff" alt="Next.js" />
    <img src="https://img.shields.io/badge/React-61dafb?style=for-the-badge&logoColor=000&logo=react" alt="React" />
    <img src="https://img.shields.io/badge/Vercel-000?style=for-the-badge&logo=vercel&logoColor=fff" alt="Vercel" />
    <img src="https://img.shields.io/badge/TypeScript-3178c6?style=for-the-badge&logo=typescript&logoColor=fff" alt="TypeScript" />
    <img src="https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=fff" alt="Tailwind CSS" />
    <img src="https://img.shields.io/badge/shadcn%2Fui-000?style=for-the-badge&logo=shadcnui&logoColor=fff" alt="shadcn/ui" />
    <img src="https://img.shields.io/badge/ESLint-4B32C3?style=for-the-badge&logo=eslint&logoColor=fff" alt="ESLint" />
    <img src="https://img.shields.io/badge/Prettier-F7B93E?style=for-the-badge&logo=prettier&logoColor=000" alt="Prettier" />
    <img src="https://img.shields.io/badge/Clerk-6C47FF?style=for-the-badge&logo=clerk&logoColor=fff" alt="Clerk" />
    <img src="https://img.shields.io/badge/Firebase-DD2C00?style=for-the-badge&logo=firebase&logoColor=fff" alt="Firebase" />
    <img src="https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=fff" alt="Google Gemini" />
    <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=000" alt="Hugging Face" />
    <img src="https://img.shields.io/badge/Together%20AI-1E96EB?style=for-the-badge&logo=slashdot&logoColor=fff" alt="Together AI" />
    <img src="https://img.shields.io/badge/Framer%20Motion-05F?style=for-the-badge&logo=framer&logoColor=fff" alt="Framer Motion" />
  </div>

  <h3 align="center">AI LOGO GENERATOR APP</h3>

  <div align="center">
    ロゴ生成 AI アプリ
  </div>
</div>

## 📋 <a name="table">もくじ</a>

1. 🤖 [はじめに](#intro)
2. 🔗 [URL](#url)
3. 😮‍💨 [logonia の概要](#description)
4. 🔋 [ロゴ生成 AI アプリの機能](#feature)
5. 🚀 [アプリの利用サンプル](#example)
6. 💻 [画面サンプル](#screen_sample)
7. 🤸 [終わりに](#outro)

## <a name="intro">🤖 はじめに</a>

数ステップの入力、選択だけでロゴが生成できる AI アプリ、**logonia** を紹介します。

## <a name="url">🔗 URL</a>

logonia | AI LOGO GENERATOR APP  
https://logonia.vercel.app

---

## <a name="description">😮‍💨 logonia の概要</a>

**logonia（ロゴニア）** は、AI モデルを活用してオリジナルのロゴデザインを自動生成できる Web アプリです。
おもな特徴や機能は以下の通りです。

### おもな特徴

#### 🥳 AIによるロゴ生成

ユーザーが入力したキーワードやイメージ（例：「猫」「テクノロジー」「シンプル」など）をもとに、
AI がロゴ画像を自動生成します。

#### 👯 直感的な操作

シンプルなインターフェースで、誰でも簡単にロゴ作成が可能です。
画面からイメージや要望を入力、選択し、「生成」ボタンを押すだけで、ロゴが自動生成、表示されます。

#### 💾 画像のダウンロード対応

気に入ったロゴは画像としてダウンロードでき、個人利用やプレゼン資料などにすぐ使えます。

#### 🤹‍♀️ 想定される利用シーン

- 新規プロジェクトやサービスのロゴ案を手軽に作りたいとき
- デザインのアイデア出しやブレインストーミング
- デザイナーへの発注前のたたき台作成
- SNS やプレゼン資料用の簡易ロゴ作成

#### 🔨 技術的背景

Google Gemini を利用したテキスト生成、Hugging Face などの画像生成 AI モデル（Midjourney 系）をバックエンドで利用しています。

フロントエンドと API は、Next.js を使った Web アプリ構成です。

#### まとめ

**logonia（ロゴニア）** は、AI を活用して誰でも簡単にオリジナルロゴを作成できる無料の Web サービスです。
キーワード入力、イメージ選択だけでロゴを自動生成し、ダウンロードも可能。
デザインの知識がなくても、直感的にロゴ作成を楽しめるアプリです。

---

## <a name="feature">🔋 ロゴ生成 AI アプリの機能</a>

### 生成ロゴ指定への入口

- ランディングページ

### ユーザ認証機能

- 🗝️ ログイン
- 🔐 ログアウト

### 生成ロゴ入力選択

- 🚶 設定ステップ表示
- 🔍 入力チェック
- 🌐 1. ロゴタイトル入力
- 🪶 2. ロゴイメージの説明入力
- 🎨 3. カラーパレット選択
- 🧑‍🎨 4. ロゴデザイン選択
- 👩‍🦯 5. ロゴアイディア選択
- 🤏 6. AI モデルプラン選択

### ロゴ生成ページ

- ⚡ ロゴのダウンロード
- 🧱 ダッシュボードへのリンク

### ダッシュボードページ

- 🧮 生成済みロゴ一覧表示
- 💰 クレジット残高表示
- 💅 各ロゴの個別表示

---

## <a name="example">🚀 アプリの利用サンプル</a>

##### ロゴ生成デモ
<!-- ./images/logonia_demo.mp4 -->
<video src="https://github.com/user-attachments/assets/a5a17130-b022-4a0c-9cde-5eb9aae681c0" controls="true"></video>

---

## <a name="screen_sample">💻 画面サンプル</a>

### 生成ロゴ指定への入口

#### ランディングページ 

<img src="./images/landing.png" width="360px" />

### ユーザ認証機能

#### ログイン

<img src="./images/login.png" width="360px" />

#### ログアウト

<img src="./images/logout.webp" width="360px" />

### 生成ロゴ入力選択

#### 🚶 設定ステップ表示

<img src="./images/steps.webp" width="360px" style="border: 1px solid #777;" />

#### 🔍 入力チェック

##### 未入力エラー

<img src="./images/check_error_in_form.webp" width="360px" />

##### 未選択エラー

<img src="./images/check_error_in_selecting_option.webp" width="360px" />

#### 🌐 1. ロゴタイトル入力

<img src="./images/enter_logo_title.png" width="360px" />

#### 🪶 2. ロゴイメージの説明入力

<img src="./images/enter_logo_description.png" width="360px" />

#### 🎨 3. カラーパレット選択

<img src="./images/color_palette_selection.png" width="360px" />

#### 🧑‍🎨 4. ロゴデザイン選択

<img src="./images/logo_design_selection.png" width="360px" />

#### 👩‍🦯 5. ロゴアイディア選択

<img src="./images/logo_idea_selection.png" width="360px" />

#### 🤏 6. AI モデルプラン選択

<img src="./images/ai_model_selection.png" width="360px" />

### ロゴ生成ページ

<img src="./images/ai_model_selection.png" width="360px" />

### ダッシュボードページ

<img src="./images/dashboard.png" width="360px" />

---

## <a name="outro">🤸 おわりに</a>

今回は一般的に公開された AI モデルを使って、「ロゴのアイディアの選択肢を生成」と「画像の生成」を行なっています。

このアプリでは AI モデルとして、以下の３つのモデルを利用しています。

- Google Gemini
- AI モデルの公開プラットフォーム Hugging Face で公開されている「strangerzonehf/Flux-Midjourney-Mix2-LoRA」
- AI モデルプロバイダ Together AI で公開されている「FLUX.1 [schnell]」 

RAG（検索拡張生成）といわれる方法を使って、そうした AI モデルに指示するプロンプトを工夫することで、AI から必要な回答を得て、画面に結果を表示しています。

RAG をカスタマイズしたり、利用する AI モデルを変えることで、アプリに様々な AI 機能を取り入れることが可能です。
