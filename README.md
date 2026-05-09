# 👋 Hi, I'm 近藤悠太 (Kondo Yuta)

**Edge AI / Embedded / IoT Engineer**  
**センサー取得からエッジ推論、通信、可視化まで一気通貫で実装するエンジニアです。**

「仕組みで現場を変える」をテーマに、  
**現場で実際に使えるシステム**を設計から実装まで開発しています。

---

## 🚀 What I Build

- **Edge AI systems** for real-time anomaly detection and inspection
- **Embedded systems** with sensors, BLE, microcontrollers, and on-device inference
- **Communication-aware architectures** that send only the data that truly matters
- **End-to-end implementations** from device-side processing to API and dashboard
- **Security tooling** for AI-generated code review and vulnerability detection
- **LLM multi-agent systems** for real-world planning and evaluation tasks

---

## 🧠 Core Strengths

- 課題を構造化し、**仕組みとして解決できる**
- ハード × ソフトを横断し、**実装までやり切れる**
- 「動く」だけでなく、**現場で使える形まで設計できる**

---

## 🔧 Tech Stack

### Edge AI / Signal Processing
- Sony **Spresense**
- **TensorFlow Lite / TensorFlow Lite Micro**
- **Random Forest**
- **FFT / 振動・音響解析**
- Feature engineering / lightweight inference

### Embedded / IoT
- **BLE** / **ELTRES**
- センサ制御
- マイコン実装
- microSD logging
- リアルタイムデータ取得・保存設計

### Backend / Cloud
- **Python** / **Node.js** / **TypeScript**
- **Java 21** / **Spring Boot** / **Spring Security**
- **AWS SAM**
- API設計 / イベント駆動アーキテクチャ

### Security & Tooling
- **SARIF** / Static Analysis
- VS Code Extension / Chrome Extension
- GitHub Actions CI/CD

### Frontend / Visualization
- **Next.js** / **React**
- Webダッシュボード
- データ可視化
- 現場向けUI設計

---

## 📌 Research Projects

### [pdm_edge](https://github.com/YUTAKONDO1205/pdm_edge)
**Spresense × 加速度 / 音響センサによるエッジ異常検知システム**

- 4ch波形（accX / accY / accZ / mic）を入力
- FFTによる特徴量抽出
- Random Forestによる軽量分類
- 学習済みモデルをSpresense向けヘッダへ変換し、マイコン側で推論

**→ クラウドに依存しないリアルタイム異常検知を実装**

---

### [DroneInspector](https://github.com/YUTAKONDO1205/DroneInspector)
**狭小空間インフラ点検向けのエッジAIドローン研究**

- Spresenseベースの点検支援システム
- カメラ / IMU / microSD / BLE を統合
- 損傷検出時のみ「画像 + 位置 + 確信度」を扱う省通信設計
- 軽量なエッジ処理で現場点検を支援

**→ 必要な情報だけを送ることで、通信制約下でも使える設計を追求**

---

### [anomaly-event-api](https://github.com/YUTAKONDO1205/anomaly-event-api)
**異常検知結果をイベントとして扱うサーバーレスAPI**

- 画像アップロード・異常検知・Grad-CAM説明・イベント保存・ダッシュボード可視化を一体化
- local / AWS の両モードで同じ操作感を保つ構成
- NEW / CHECKING / RESOLVED の運用ステータス設計
- AWS SAMベースで構築

**→ 現場データを、リアルタイムに価値へ変換する仕組み**

---

### [Eltres_CO2_Mapping](https://github.com/YUTAKONDO1205/Eltres_CO2_Mapping)
**Spresense + ELTRESによるCO2濃度マッピングシステム**

- CO2濃度と位置情報を交互に送信
- CLIP Viewer Lite API からMATLABで取得
- Webダッシュボードまで含めて可視化
- 通信・解析・表示まで一連で構築

**→ センサデータを"見える価値"に変えるIoTシステム**

---

## 🛠 Selected Works

### [VibeGuard](https://github.com/YUTAKONDO1205/VibeGuard) — Security Tooling
**AI生成コード向けセキュリティ診断基盤**

- 開発中（VS Code）・閲覧中（Chrome）・マージ前（GitHub Actions / CLI）の3段階で同一解析コアを使用
- AIが書いたコードの典型的な脆弱性を検出
- SARIF形式で出力、GitHub Marketplace にも公開

**→ AI時代のコード品質を、開発フロー全体でガードする**

---

### [travel_app_patch](https://github.com/YUTAKONDO1205/travel_app_patch) — LLM Multi-Agent
**Maison Passage: 片道航空券2枚で組み立てる海外旅行プランナー**

- 海外旅行を「2枚の片道航空券」として検索するプレミアムプランナー
- Codex の Planner / Generator / Evaluator マルチエージェントハーネスをローカルで運用
- Next.js + TypeScript + Skyscanner API

**→ LLMエージェントを、実際に使える旅行体験へつなぐ**

---

### [Mountain-Supply-System](https://github.com/YUTAKONDO1205/Mountain-Supply-System) — Business System
**山小屋補給品の在庫・受注・売上管理システム**

- Java 21 / Spring Boot / Spring Security
- 商品マスタ、入出庫履歴、注文ヘッダと明細、ユーザー認証を分離した正規化設計
- JOIN・GROUP BY を中心とした集計SQL
- JUnit 5 によるテスト

**→ 実務水準の設計と実装力を示す業務システムミニプロジェクト**

---

### [my-portfolio](https://github.com/YUTAKONDO1205/my-portfolio)
**自分の技術領域と開発テーマを整理したポートフォリオサイト**

- Next.js + TypeScript
- 研究 / 開発テーマの整理と可視化
- GitHubプロフィールとの接続を意識した設計

---

## 🔍 Current Focus

- エッジAIによる**異常検知・損傷検出**
- 通信制約を前提にした**省通信データ設計**
- センサ / 推論 / 通信 / API / 可視化をつなぐ**実運用志向のシステム開発**
- AI生成コードの**品質・安全性の担保**

---

## 🌱 Philosophy

I believe good engineering is not only about making something work.  
It is about designing systems that can actually be used in the real world.

だからこそ私は、  
**「どう動くか」だけでなく、「どう使われるか」まで設計すること**を大切にしています。

センサ取得、エッジ推論、通信、API、可視化までを横断し、  
**必要な情報だけを送る省通信設計**と**運用へつなげるイベント設計**を、  
ひとつの体験として組み立てています。

---

## 📫 Contact

- GitHub: https://github.com/YUTAKONDO1205
- Portfolio: https://kondo-yuta-my-portfolio.vercel.app/
- Elchika: https://elchika.com/user/kd_yuta/?page=0
- LinkedIn: https://www.linkedin.com/in/kondo-yuta-985430317
