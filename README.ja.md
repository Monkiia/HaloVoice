<p align="center">
  <a href="README.md">English</a> · <a href="README.es.md">Español</a> · <a href="README.ru.md">Русский</a> · <a href="README.pt-BR.md">Português</a> · <b>日本語</b> · <a href="README.zh-CN.md">简体中文</a>
</p>

<div align="center">
  <img src="assets/icon.png" width="120" height="120" alt="HaloVoice ロゴ">

  # HaloVoice

  **配信・ゲーム・会議のためのリアルタイム AI 音声翻訳**

  あなたの声を 30 以上の言語にリアルタイムで翻訳。OBS、Discord、Zoom、Teams などで使えます。

  [![無料で試す](https://img.shields.io/badge/%E7%84%A1%E6%96%99%E3%81%A7%E8%A9%A6%E3%81%99-%E4%BB%8A%E3%81%99%E3%81%90%E5%A7%8B%E3%82%81%E3%82%8B-brightgreen?style=for-the-badge)](https://console.halovoice.app)
  [![公式サイト](https://img.shields.io/badge/%E5%85%AC%E5%BC%8F%E3%82%B5%E3%82%A4%E3%83%88-halovoice.app-blue?style=for-the-badge)](https://halovoice.app)

</div>

---

## 主な機能

- **リアルタイム AI 翻訳** - 200ms 未満の遅延で、あなたの声を 30 以上の言語に瞬時に翻訳
- **双方向翻訳** - あなたの声は相手の言語に翻訳され、相手の話す内容は字幕または音声であなたの言語に翻訳されます
- **シーン別モード** - ゲーム、配信、会議の各モードを、それぞれの環境に合わせて最適化
- **Voice Mod** - 言語はそのままに、声のスタイルだけを変更
- **Voice Studio** - プレミアムボイスを選んだり、自分だけのボイスクローンを作成
- **クリアな音声** - 高度なノイズキャンセリングでプロ品質のサウンドを実現
- **ライブ字幕と移動できるオーバーレイ** - リアルタイムの文字起こしと翻訳テキストを表示。デスクトップアプリでは、常に最前面に表示されるドラッグ可能な字幕オーバーレイも利用できます
- **どこでも使える** - OBS、Discord、Zoom、Teams、Slack、Google Meet、TikTok、Steam にそのまま対応
- **軽量** - すべての処理はクラウドで行われるため、CPU に負荷をかけません
- **30 以上の言語** - 英語、スペイン語、フランス語、ドイツ語、日本語、韓国語、中国語（北京語）など多数

## ✨ 新機能

- **音声再生付きの双方向翻訳** - 翻訳が双方向で動作するようになりました。*相手の話を理解する* 機能で、相手の発話をあなたの言語のライブ字幕として表示するか、**あなたの言語で読み上げて聞く**（Pro）こともできます。字幕を読む代わりに、ゲームや会議に集中できます。
- **3 つの最適化モード** - シーンを選ぶだけで、HaloVoice が自動的に調整します：
  - **ゲームモード** - 最小の遅延と、システムリソースへの最小限の負荷
  - **配信モード** - スタジオ品質の音声処理と、ライブ配信向けに強化された声の明瞭さ
  - **会議モード** - ビジネス通話向けに、バランスの取れた音声と強化されたノイズ抑制
- **移動できる字幕オーバーレイ** - ゲーム、配信、会議の上に常に表示される、フローティングのドラッグ可能な字幕バー（デスクトップアプリ）。ライブ翻訳を画面上の好きな場所に配置できます。
- **AI 精度コントロール** - 設定で、翻訳の速度と精度のバランスを自分で選べます。
- **友達を招待して特典を獲得** - 友達を招待すると、両方にプレミアムボイス無制限の 7 日間が付与されます。

## 🎮 実際の動作を見る

<div align="center">

  <a href="https://www.youtube.com/shorts/fkarPVR5gPU">
    <img src="assets/rust-demo-thumb.jpg" width="270" alt="視聴：Rust をプレイしながらのリアルタイム音声翻訳">
  </a>

  **▶ Rust で海外のチームメイトと会話するプレイヤーの様子 — HaloVoice によるライブ翻訳**

</div>

## クイックスタート

1. ブラウザで [console.halovoice.app](https://console.halovoice.app) を**開く**
2. Google またはメールアドレスで**サインイン**
3. 翻訳元と翻訳先の言語を**選択**
4. **「START SESSION」をクリック**して話し始める

> Discord、OBS、Zoom などのアプリとシームレスに連携するには、アプリ内から仮想オーディオドライバーをインストールすることもできます（任意）。

## 連携

HaloVoice はブラウザ上でそのまま動作します。翻訳された声を他のアプリで使うには、オプションの仮想オーディオドライバーをインストールし、マイク入力として選択してください。

### Discord で使う
<img src="assets/discord.png" width="600" alt="Discord 連携">

1. **Discord の設定** > **音声・ビデオ** を開く
2. 入力デバイスとして **HaloVoice Virtual Microphone** を選択
3. すべてのゲームセッションで、あなたの声がリアルタイムに翻訳されます

### OBS Studio で使う
<img src="assets/obs.png" width="600" alt="OBS 連携">

1. **OBS Studio** で **音声入力キャプチャ** ソースを追加
2. **HaloVoice Virtual Microphone** を選択
3. 翻訳された声が Twitch、YouTube、TikTok の視聴者にそのまま届きます

### Teams / Zoom / Google Meet で使う
**Teams のマイク設定**<img src="assets/teams.jpg" width="600" alt="Microsoft Teams 連携">
**Zoom のマイク設定**<img src="assets/zoom.png" width="600" alt="Zoom 連携">

1. 会議アプリの**オーディオ**設定を開く
2. マイクとして **HaloVoice Virtual Microphone** を選択
3. 自分の言語で話すと、参加者には翻訳が即座に届きます

**Slack**、**Google Meet** をはじめ、マイク入力に対応したあらゆるアプリで使えます。

## こんな用途に

- **ライブ配信** - Twitch、YouTube、TikTok で、世界中の視聴者にそれぞれの言語で届ける
- **ゲーム** - Steam や Discord などで海外のチームメイトとコミュニケーション
- **オンライン会議** - Zoom、Teams、Google Meet、Slack で言語の壁を越える

## 料金

| プラン | 料金 | 内容 |
|--------|------|------|
| **Free** | $0 | 月 60 分、ライブ字幕と翻訳、OBS/Zoom/Discord 対応 |
| **Pro** | $9.9/月 | 無制限の翻訳、全言語、優先処理、プレミアムボイス、カスタムボイスクローン、新機能への早期アクセス |
| **Enterprise** | 要相談 | 専用サーバー、API アクセス、SLA、24 時間 365 日サポート、SSO 連携 |

<div align="center">

  [無料で始める](https://console.halovoice.app)

</div>

## プライバシー

- 音声は安全に処理されます
- 録音データは保存されません
- GDPR 準拠
- [プライバシーポリシー](https://halovoice.app/#privacy)をご覧ください

## サポート

- メール：support@halovoice.app
- [問題を報告](https://github.com/Monkiia/HaloVoice/issues)
- [公式サイト](https://halovoice.app)

## ライセンス

Copyright 2026 HaloVoice. All rights reserved.

---

<div align="center">

  **世界中のクリエイター、ゲーマー、リモートチームのために**

  <a href="https://github.com/Monkiia/HaloVoice/issues">
    <img src="https://img.shields.io/github/issues/Monkiia/HaloVoice?style=flat-square" alt="Issues">
  </a>
  <a href="https://halovoice.app">
    <img src="https://img.shields.io/badge/%E5%85%AC%E5%BC%8F%E3%82%B5%E3%82%A4%E3%83%88-halovoice.app-blue?style=flat-square" alt="公式サイト">
  </a>
  <a href="https://console.halovoice.app">
    <img src="https://img.shields.io/badge/app-%E7%84%A1%E6%96%99%E3%81%A7%E8%A9%A6%E3%81%99-brightgreen?style=flat-square" alt="無料で試す">
  </a>

</div>
