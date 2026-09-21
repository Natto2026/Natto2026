<h1 align="center">中本 智也 / Tomoya Nakamoto</h1>

<p align="center">
大阪公立大学大学院 情報学研究科 修士1年(2028年3月修了見込み)<br>
研究はコンピュータビジョンと機械学習。開発はテストと CI まで書くアプリケーション
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Osaka%20Metropolitan%20University-M1-1a5fb4?style=flat-square" alt="OMU M1">
  <img src="https://img.shields.io/badge/Field-Computer%20Vision-2ec27e?style=flat-square" alt="Computer Vision">
  <img src="https://img.shields.io/badge/Location-Osaka,%20Japan-e66100?style=flat-square" alt="Osaka">
</p>

---

## About Me

- 大学院で**コンピュータビジョン・機械学習**を専攻しています
- 作ったものを動く状態で保つことを大切にしています。設計・実装だけでなく、テストと CI まで用意します
- 技術以外では、大学体育会の会長として約30部活を統括した経験があり、**技術とマネジメントの両輪**で動けることが強みです

## 経歴

- 2022年4月　和歌山大学 システム工学部 入学
- 2023年4月　Python を独学で開始。以後、研究とプロダクト開発で継続
- 2025年度　大学体育会 会長。約30部活を統括し、[2大学対抗戦](https://www.wakayama-u.ac.jp/scenter/news/2025052000059/)の運営を主導
- 2026年2月　[第11回 紀陽イノベーションサポートプログラム 部門賞（奨励賞）](https://www.wakayama-u.ac.jp/edc/news/2026030300017/)。学生4名チームの技術担当
- 2026年3月　学部卒業。卒業研究はフィッシングサイト検知
- 2026年4月　大阪公立大学大学院 情報学研究科 入学（知能メディア処理研究室）。研究室で計算機管理のアルバイト
- 2026年8月　[IT企業の5daysインターン](https://github.com/Natto2026/AI-Intern-2026)。5人チームで RAG 型の社内問い合わせシステムを構築
- 2026年9月　[NTTドコモ ハッカソン](https://github.com/Natto2026/docomo-hackathon-2026)。6人チームで地域SNSを開発

## 作ったもの

| | 概要 | 技術 |
|---|---|---|
| **[shukatsu-tracker](https://github.com/Natto2026/shukatsu-tracker)** | 選考プロセスをローカルで管理するツール。締切・選考ステップ・提出した回答を一元管理する。認証情報を持たない設計。UI・ユースケース・永続化を層に分け、SQLite と PostgreSQL の両方に対して同じテストを CI で実行している | Python / Streamlit / SQLite / PostgreSQL / pytest / GitHub Actions |
| **[AI-Intern-2026](https://github.com/Natto2026/AI-Intern-2026)** | IT企業のインターン。5人チームでの5日間。企業サイトのデータから社内の問い合わせに答える RAG を構築。チームで20問の総合スコアを 0.567 から 0.801 に改善し、追加の5問では 0.868。その過程で、HTML の本文抽出と PDF・画像への対応を担当。判断の経緯と、できなかったことの記録 | Python / Azure AI Search / Azure OpenAI / RAG |
| **[docomo-hackathon-2026](https://github.com/Natto2026/docomo-hackathon-2026)** | 6人チームでの3日間開発。現在地の周辺に絞った地域SNSアプリ。フォローと公開範囲の制御、店舗情報の紐づけ、地図表示を担当し、テスト56件を追加した。ハッカソン後に、発表で出た指摘を受けて改良を足し、フォロー関係の保存を DynamoDB に移せるようにして、自分の AWS アカウントで動作を確認した | Flutter / Node.js / TypeScript / Google Maps / AWS (DynamoDB, CloudFormation) |
| **研究(非公開)** | 医療映像(外科手術動画)を対象としたコンピュータビジョン。セマンティックセグメンテーション、オプティカルフロー、器具の動きからの熟練度評価 | Python / PyTorch / OpenCV |

<sub>研究のコードは共同研究のため非公開です。インターンのコードは主催元の環境に基づくため載せず、担当範囲と判断の記録のみを公開しています。ハッカソンは、主催元の許可を得て、自分が単独で書いた範囲のコードだけを収録しています。</sub>

## Awards & Activities

- 🏆 **[第11回 紀陽イノベーションサポートプログラム 部門賞（奨励賞）](https://www.wakayama-u.ac.jp/edc/news/2026030300017/)**（紀陽銀行主催） — 学生4名チームの技術担当として、唯一の学生チームでの入賞
- **大学体育会 会長** — 約30部活を統括(2025年度)。2大学の体育会系部活動が一堂に会する[総合対抗戦](https://www.wakayama-u.ac.jp/scenter/news/2025052000059/)の運営を主導

## Tech Stack

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter">
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite">
  <img src="https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" alt="pytest">
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions">
</p>

- **画像・動画処理(研究で使用。コードは共同研究のため非公開)**: セグメンテーション(SAM系)、オプティカルフロー、単眼深度推定、点群処理(Open3D)
- **開発**: レイヤー分割、スキーマのバージョン管理、テスト設計(pytest / vitest)、CI、Git/GitHub でのPRベース開発
- **チーム開発で使ったもの**: Flutter と Node.js(ハッカソン)、Azure AI Search と Azure OpenAI による RAG(インターン)

## Now & Next

- 修士研究を進めつつ、研究の外ではテストと CI を備えたアプリケーションの開発を続けています
- 直近は shukatsu-tracker の 0.8.0 で、スプレッドシートからの CSV 取り込みを追加しました。取り込む前に結果の要約を見せ、確認のあとに1つのトランザクションで書き込みます。あわせて、古い画面からの保存や接続の失敗を利用者に知らせる修正を入れました
- 次は Issue に積んである画面のファイル分割と締切のリマインドに、1本ずつ PR で取り組みます
