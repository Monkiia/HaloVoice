<p align="center">
  <a href="README.md">English</a> · <a href="README.es.md">Español</a> · <a href="README.ru.md">Русский</a> · <a href="README.pt-BR.md">Português</a> · <b>日本語</b> · <a href="README.zh-CN.md">简体中文</a>
</p>

<div align="center">
  <img src="assets/icon.png" width="120" height="120" alt="HaloVoiceロゴ">

  # HaloVoice

  **配信・ゲーム・会議のためのリアルタイムAI音声翻訳**

  あなたの声を30以上の言語にリアルタイム翻訳。OBS、Discord、Zoom、Teamsなどに対応しています。

  [![無料で試す](https://img.shields.io/badge/%E7%84%A1%E6%96%99%E3%81%A7%E8%A9%A6%E3%81%99-%E4%BB%8A%E3%81%99%E3%81%90%E5%A7%8B%E3%82%81%E3%82%8B-brightgreen?style=for-the-badge)](https://console.halovoice.app)
  [![公式サイト](https://img.shields.io/badge/%E5%85%AC%E5%BC%8F%E3%82%B5%E3%82%A4%E3%83%88-halovoice.app-blue?style=for-the-badge)](https://halovoice.app)

</div>

---

## 主な機能

- **リアルタイムAI翻訳** - 遅延200ms未満。あなたの声を30以上の言語へ瞬時に翻訳
- **双方向翻訳** - あなたの声は相手の言語に。相手の発言は、字幕または音声であなたの言語に翻訳されて返ってきます
- **シーン別モード** - ゲームモード、配信モード、会議モードを、それぞれの環境に合わせて最適化
- **音声変換（Voice Mod）** - 言語はそのままに、声のスタイルだけを変える
- **ボイススタジオ** - 豊富なプレミアムボイスから選ぶか、カスタムボイスクローンを作成
- **クリアな音声** - 高度なノイズキャンセリングで、プロ品質のサウンドを実現
- **ライブ字幕と移動できるオーバーレイ** - 文字起こしと翻訳テキストをリアルタイムに表示。デスクトップアプリでは、常に最前面に表示されるドラッグ可能な字幕オーバーレイも使えます
- **どこでも使える** - OBS、Discord、Zoom、Teams、Slack、Google Meet、TikTok、Steamと、つなぐだけで連携
- **軽量** - 処理はすべてクラウド側。PCのCPUに負荷をかけません
- **30以上の言語に対応** - 英語、スペイン語、フランス語、ドイツ語、日本語、韓国語、中国語など多数

## ✨ 新機能

- **音声再生にも対応した双方向翻訳** - 翻訳が双方向になりました。*相手の発言を理解する*をオンにすると、相手の発言をあなたの言語のライブ字幕で表示。さらに**相手の言葉をあなたの言語で音声で聞く**（Pro）を選べば、字幕を読まずにゲームや会議に集中できます。
- **3つの最適化モード** - シーンを選ぶだけで、HaloVoiceが自動で最適化：
  - **ゲームモード** - 最小の遅延。システムリソースへの負荷も最小限
  - **配信モード** - スタジオ品質の音声処理で、ライブ配信の声をよりクリアに
  - **会議モード** - バランスの取れた音声とノイズ抑制の強化。ビジネス通話に最適
- **移動できる字幕オーバーレイ** - ゲーム、配信、会議のどの画面でも常に最前面に表示される、ドラッグで動かせるフローティング字幕バー（デスクトップアプリ）。ライブ翻訳を画面の好きな位置に置けます。
- **AI精度コントロール** - 設定の「AI精度」で、翻訳のスピードと正確さのバランスを自分で選べます。
- **友達を招待** - 友達を招待すると、お互いに7日間のプレミアムボイス使い放題がもらえます。

## 🎮 実際の動作を見る

<div align="center">

  <a href="https://www.youtube.com/shorts/fkarPVR5gPU">
    <img src="assets/rust-demo-thumb.jpg" width="270" alt="動画を見る：Rustをプレイしながらリアルタイム音声翻訳">
  </a>

  **▶ Rustで海外のチームメイトと話すプレイヤーを、HaloVoiceがその場で翻訳**

</div>

## クイックスタート

1. ブラウザで[console.halovoice.app](https://console.halovoice.app)を**開く**
2. Googleまたはメールで**ログイン**
3. 入力言語と翻訳先の言語を**選択**
4. **「セッション開始」をクリック**（START SESSION）。あとは話すだけ

> Discord、OBS、Zoomなどのアプリとシームレスに連携したい場合は、アプリ内からHaloVoice仮想オーディオドライバーをインストールできます（任意）。

## アプリ連携

HaloVoiceはブラウザだけで動作します。翻訳した声を他のアプリで使うには、HaloVoice仮想オーディオドライバー（任意）をインストールし、そのアプリのマイク入力に選ぶだけです。

### Discordで使う
<img src="assets/discord.png" width="600" alt="Discord連携">

1. Discordの**ユーザー設定** > **音声・ビデオ**を開く
2. **入力デバイス**で**HaloVoice Virtual Microphone**を選択
3. これで、どのゲームセッションでもあなたの声がリアルタイムに翻訳されます

### OBS Studioで使う
<img src="assets/obs.png" width="600" alt="OBS連携">

1. **OBS Studio**でソースに**音声入力キャプチャ**を追加
2. デバイスに**HaloVoice Virtual Microphone**を選択
3. 翻訳された声が、Twitch、YouTube、TikTokの視聴者にそのまま届きます

### Teams / Zoom / Google Meetで使う
**Teamsのマイク設定**<img src="assets/teams.jpg" width="600" alt="Microsoft Teams連携">
**Zoomのマイク設定**<img src="assets/zoom.png" width="600" alt="Zoom連携">

1. 会議アプリの**オーディオ**設定を開く（Teamsは**デバイス**、Google Meetは**音声**）
2. マイクに**HaloVoice Virtual Microphone**を選択
3. 自分の言語で話すだけで、参加者には翻訳がすぐに届きます

**Slack**や**Google Meet**はもちろん、マイク入力を選べるアプリならどれでも使えます。

## こんなシーンに最適

- **ライブ配信** - Twitch、YouTube、TikTokで、世界中の視聴者にそれぞれの言語で届ける
- **ゲーム** - SteamやDiscordで、海外のチームメイトとスムーズに会話
- **オンライン会議** - Zoom、Teams、Google Meet、Slackで、言語の壁を越える

## 料金

| プラン | 料金 | 内容 |
|--------|------|------|
| **Free** | $0 | 月60分、ライブ字幕と翻訳、OBS/Zoom/Discord対応 |
| **Pro** | $9.9/月 | 翻訳無制限、全言語、優先処理、プレミアムボイス、カスタムボイスクローン、新機能の先行利用 |
| **Enterprise** | 要相談 | 専用サーバー、APIアクセス、SLA、24時間365日サポート、SSO連携 |

<div align="center">

  [無料で始める](https://console.halovoice.app)

</div>

## プライバシー

- 音声データは安全に処理されます
- 録音は一切保存されません
- GDPR準拠
- 詳しくは[プライバシーポリシー](https://halovoice.app/#privacy)をご覧ください

## サポート

- メール：support@halovoice.app
- [不具合を報告](https://github.com/Monkiia/HaloVoice/issues)
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
