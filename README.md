<h1 align="center">中本 智也 / Tomoya Nakamoto</h1>

<p align="center">
大阪公立大学大学院 情報学研究科 修士1年（2028年3月修了見込み）<br>
研究はコンピュータビジョンと機械学習。対象は外科手術の映像
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Osaka%20Metropolitan%20University-M1-1a5fb4?style=flat-square" alt="OMU M1">
  <img src="https://img.shields.io/badge/Field-Computer%20Vision-2ec27e?style=flat-square" alt="Computer Vision">
  <img src="https://img.shields.io/badge/Location-Osaka,%20Japan-e66100?style=flat-square" alt="Osaka">
</p>

---

## 自己紹介

- 作ったものを動く状態で保つことを大切にしている。個人開発では、設計・実装だけでなくテストと CI まで用意する
- 技術以外では、学部時代に和歌山大学体育会の会長を務めた。**技術とマネジメントの両輪**で動けることが強み

## 経歴

- 2022年4月　和歌山大学 システム工学部 入学
- 2023年4月　Python を開始
- 2025年度　和歌山大学体育会 会長。約30部活を統括し、2大学の体育会系部活動が一堂に会する[和滋二大学学長杯争奪総合定期戦](https://www.wakayama-u.ac.jp/scenter/news/2025052000059/)の運営を主導
- 2026年2月　[第11回 紀陽イノベーションサポートプログラム 部門賞（奨励賞）](https://www.wakayama-u.ac.jp/edc/news/2026030300017/)（紀陽銀行主催）。学生4名チームの技術担当。唯一の学生チームでの入賞
- 2026年3月　学部卒業。卒業研究はフィッシングサイト検知
- 2026年4月　大阪公立大学大学院 情報学研究科 入学（知能メディア処理研究室）。研究室で計算機管理のアルバイト
- 2026年8月　[IT企業の AI エンジニア 5日間インターン](https://github.com/Natto2026/AI-Intern-2026)。社内問い合わせ RAG の構築
- 2026年9月　[NTTドコモ ハッカソン](https://github.com/Natto2026/docomo-hackathon-2026)。地域SNSアプリの開発

## 作ったもの

| 成果物 | 概要 | 技術 |
|---|---|---|
| **[shukatsu-tracker](https://github.com/Natto2026/shukatsu-tracker)** | **個人開発**。選考の締切・ステップ・回答を手元で管理するツール。パスワードは保存しない。UI・ユースケース・永続化を層に分け、SQLite と PostgreSQL の両方に同じテストを CI で流している | Python / Streamlit / SQLite / PostgreSQL / pytest / GitHub Actions |
| **[AI-Intern-2026](https://github.com/Natto2026/AI-Intern-2026)** | **5日間インターン**。5人チームで社内問い合わせ RAG を構築し、20問の総合スコアを 0.567 から 0.801 へ。担当は HTML の本文抽出と PDF・画像への対応 | Python / Azure AI Search / Azure OpenAI / RAG |
| **[docomo-hackathon-2026](https://github.com/Natto2026/docomo-hackathon-2026)** | **ハッカソン**。6人チーム3日間で、現在地の周辺に絞った地域SNSアプリ。担当はフォローと公開範囲、店舗の紐づけ、地図の部品とテスト56件。後日 DynamoDB 版を足し、自分の AWS で動作を確認 | Flutter / Node.js / TypeScript / Google Maps / AWS（DynamoDB・CloudFormation） |
| **研究（コード非公開）** | **修士研究**。外科手術動画を対象としたコンピュータビジョン。器具の動きから熟練度を評価する | Python / PyTorch / OpenCV |

<sub>研究のコードは共同研究のため非公開。インターンのコードは主催元の環境に基づくため載せず、担当範囲と判断の記録のみを公開している。ハッカソンは、主催元の許可とチームの了承を得て、自分が書いた・手を入れたファイルをすべて収録している（共同で編集したファイルを含み、画面まで動かせる）。</sub>

## 技術スタック

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

- **画像・動画処理（研究で使用）**: セグメンテーション（SAM系）、オプティカルフロー、単眼深度推定、点群処理（Open3D）
- **開発**: レイヤー分割、スキーマのバージョン管理、テスト設計（pytest / vitest）、Git/GitHub での PR ベース開発
- **チーム開発で使ったもの**: Flutter と Node.js（ハッカソン）、Azure AI Search と Azure OpenAI による RAG（インターン）

## 現在と今後

- 直近は shukatsu-tracker の 0.9.0 で、障害時の振る舞いを見直した。COMMIT が一度失敗すると以後の書き込みが止まる不具合や、接続が切れたときに画面へ生のエラーが出る問題を直し、PostgreSQL を再起動しても接続を張り直して動き続けるようにした
- 次は Issue に積んである画面のファイル分割と締切のリマインドに、1本ずつ PR で取り組む
