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
- **BLE**
- センサ制御
- マイコン実装
- microSD logging
- リアルタイムデータ取得・保存設計

### Backend / Cloud
- **Python**
- **AWS SAM**
- API設計
- イベント駆動アーキテクチャ

### Frontend / Visualization
- **Next.js**
- Webダッシュボード
- データ可視化
- 現場向けUI設計

---

## 📌 Selected Projects

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

- 異常検知データをイベント化
- 通知や後続処理につなげるAPI設計
- AWS SAMベースで構築

**→ 現場データを、リアルタイムに価値へ変換する仕組み**

---

### [Eltres_CO2_Mapping](https://github.com/YUTAKONDO1205/Eltres_CO2_Mapping)
**Spresense + ELTRESによるCO2濃度マッピングシステム**

- CO2濃度と位置情報を交互に送信
- CLIP Viewer Lite API からMATLABで取得
- Webダッシュボードまで含めて可視化
- 通信・解析・表示まで一連で構築

**→ センサデータを“見える価値”に変えるIoTシステム**

---

### [my-portfolio](https://github.com/YUTAKONDO1205/my-portfolio)
**自分の技術領域と開発テーマを整理したポートフォリオサイト**

- 技術スタックの可視化
- 研究 / 開発テーマの整理
- GitHubプロフィールとの接続を意識した設計

---

## 🔍 Current Focus

- エッジAIによる**異常検知・損傷検出**
- 通信制約を前提にした**データ設計**
- センサ / 推論 / 通信 / API / 可視化をつなぐ**実運用志向のシステム開発**

---

## 🌱 Philosophy

I believe good engineering is not only about making something work.  
It is about designing systems that can actually be used in the real world.

だからこそ私は、  
**「どう動くか」だけでなく、「どう使われるか」まで設計すること**を大切にしています。

---

## 📫 Contact

- GitHub: https://github.com/YUTAKONDO1205
- Portfolio: https://kondo-yuta-my-portfolio.vercel.app/
- Elchika: https://elchika.com/user/kd_yuta/?page=0
- LinkedIn: https://www.linkedin.com/in/kondo-yuta-985430317
