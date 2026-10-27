# 🧸 CH32V002マイコン搭載 電子オルゴールプロジェクト (CH32V_orgel_SW_V002)

安価でコストパフォーマンスに優れたWCH半導体製マイコン「CH32V002」を使用した、おもちゃ修理・マイコン換装用の電子オルゴールプロジェクトです。
音楽表現豊かなオルゴール演奏と、外部メモリの音源を高音質でコンカレントに音声再生します。

---

## 🎵 本プロジェクトの特徴と魅力

### 🌟 おもちゃ修理への応用
開発者である「名張市つつじが丘おもちゃ病院」さまのブログでは、電源条件や曲選択、周辺制御など多岐にわたるカスタマイズに対応するファームウェア開発スキルの重要性が述べられており、本プロジェクトはその実践的なベースとして活用いただけます。詳細は該当ブログもご参照ください。

### 🎹 約180曲の楽曲群と表現力
* 童謡からクラシックまで約180曲から選択可能で、情操教育にも最適です。
* エンベロープやエフェクト制御により、豊かなオルゴール音を奏でます。

### 🌟 IMA-ADPCMによる高音質な音声再生
SPI接続のフラッシュメモリ（または内蔵）から、IMA-ADPCM形式の音声をクリアに再生します。

---

### 🛠️ 現役ドクターの皆様へ：修理報告・カルテ募集中！
本プログラム（CH32_orgelシリーズ）を活用し、おもちゃのマイコン換装やオルゴール化による修理（蘇生）に成功しましたら、ぜひ知見をご共有ください！
皆様が残した1つのカルテが、全国の同志の「次の臨床」を支える大きな力になります。

#### 👉 **[おもちゃ修理・マイコン換装 報告フォームからカルテを投稿する](https://github.com/ToyDr-W/CH32_orgel_SW_V002/issues)**
（Issues画面右上の「New issue」ボタンをクリックし、報告フォームを選択）
<p align="center">
  <br>
  <a href="https://youtu.be/pcVJL7qO2WE">
<img width="45%" alt="SW_J4M6_CdS231018 (3)" src="https://github.com/user-attachments/assets/e878d739-6cdb-4d0c-9479-32af6f0cf8c2" />
  <br>
       <em>▶️ YouTubeで動作確認動画を再生する</em>
  </a>
</p>

---

## 🛠️ 対象プロジェクト（3モデル）

マイコンのPWM出力を活用したBTL駆動に対応する3つのモデルを同梱しています。

* **`orgel_SW_V002J4M6`**: 省スペースな8ピンパッケージ、スイッチ切り替えとBTL駆動を両立した小型おもちゃ向け。
* **`orgel_SW_V002A4M6`**: 16ピンパッケージ、複数スイッチやセンサー制御、LEDなどを追加しやすく拡張性が高い。
* **`orgel_SW_V002F4P6`**: 20ピンパッケージ、複数スイッチやセンサー制御、多数ポートでさらに拡張性が高い。

> [!NOTE]
> ### 📥 最新データのダウンロードについて（v1.2.0正式リリースまで）
> 現在はバグ修正等の調整期間中のため、正式な「Release」での公開は行っていません。2週間ほど様子を見て、安定後に **v1.2.0（安定版）** としてリリース予定です。
> 
> それまでの間、最新の回路図およびプログラム一式をダウンロードするには、
> [ここをクリックしてください。 ⬇️](https://github.com/ToyDr-W/CH32V_orgel_SW_V002/archive/refs/heads/main.zip)
> ダウンロード（52.0 MBのZIPファイル）が直ちに開始されます。
>
> ---
>
> ### 📥 Downloading the Latest Data (Prior to v1.2.0 Official Release)
> This project is currently undergoing final adjustments. We plan to officially release **v1.2.0 (Stable version)** in about two weeks.
> 
> In the meantime, [please click here to download ⬇️](https://github.com/ToyDr-W/CH32V_orgel_SW_V002/archive/refs/heads/main.zip) the latest circuit diagrams and the complete set of programs. The download (a 52.0 MB ZIP file) will begin immediately.
> 

---

## 🤝 地域貢献とリサイクルへの想い
おもちゃのリサイクル活動にお役立てください。

---

## 📖 詳しい解説・回路図（Wikiページ）

回路図やカスタマイズ方法などの詳細は、専用の Wiki ページをご確認ください。

👉 [📖 CH32V電子オルゴール解説・回路図（Wikiページ）へ移動する](https://github.com/ToyDr-W/CH32V_orgel_SW_V002/wiki)
