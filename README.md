# 📊 損益分岐点ゲーム - 動かして覚える会計 (Break-Even Simulator)

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](#)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](#)
[![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=flat&logo=chartdotjs&logoColor=white)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](#)

> **「限界利益」を見極めろ！**  
> 読むだけの教材やフラッシュカードではなく、**「動かして覚える」**新感覚の会計・経営学習シミュレーターです。


---

## 🎮 コンセプト

**「取引が会計に変わる瞬間を、指先で体感する」**

商品を1つ売るたびに、画面上の「固定費」「変動費」「売上」のブロックが積み上がります。落ちモノパズルのように**「固定費の壁」**を越え、赤字が消えて**「限界利益」**がそのまま利益へと変わる瞬間（＝損益分岐点）を、直感的に理解することができます。

---

## ✨ 主な機能 (Features)

- **🧱 動くT字勘定ブロック**  
  商品を売るボタンを押すたびに、ブロックがぽよんと成長。売上と費用のバランスが視覚的にわかります。
- **📈 リアルタイムCVPグラフ**  
  Chart.jsを用いた滑らかなグラフ描画。売上線、総費用線、固定費（黄色の点線）と、現在地（青丸）がリアルタイムに連動します。
- **🤖 AI経営アドバイス (逆算機能)**  
  「あと何個売れば黒字か？」「今の販売数のまま黒字にするには固定費をいくら削るべきか？」など、コンサルタント視点での具体的なアクションを自動計算して提示します。
- **📊 2つの損益計算書 (P/L)**  
  一般的な「損益計算書」と、経営分析に使われる「変動損益計算書」を並べて比較。数字がどう結びついているか一目でわかります。
- **🧮 8つのKPI ＆ ツールチップ辞書**  
  限界利益率、安全余裕率、損益分岐点比率などを自動計算。画面上の点線テキストにカーソルを合わせると、初心者向けの優しい用語解説がポップアップします。
- **🌍 日/英 多言語対応**  
  右上のボタン一つで、UIや専門用語、ツールチップがすべて英語（グローバルスタンダード）に切り替わります。
- **🐦 𝕏 (Twitter) シェア機能**  
  シミュレーションの現在状況（赤字、目標達成など）に合わせてシェア文面が自動生成されます。

---

## 🚀 公開方法 (How to Deploy)

このアプリは、**HTMLファイル1つだけで完全に動作**します。バックエンドやデータベースは不要です。

1. このリポジトリをFork、または新しく作成します。
2. 以下の3つのファイルをルートディレクトリに置きます。
   - `index.html` (本体)
   - `ogp.png` (Twitterなどでシェアされたときのサムネイル画像: 1200x630)
   - `favicon.png` (ブラウザのタブ用アイコン: 512x512等)
3. リポジトリの **[Settings]** > **[Pages]** を開きます。
4. **Source** を `Deploy from a branch` に設定し、`main` ブランチを指定して **[Save]** を押します。
5. 1〜2分待つと、無料で世界中に公開されます！🎉

---

## 📖 遊び方

1. **パラメータを設定する**  
   単価、変動費（1個あたりの仕入れなど）、固定費（家賃や人件費）、目標利益を自由に入力します。桁数に上限はありません。
2. **商品を売る**  
   「商品を1つ売る 🎯」ボタンをクリックして、ビジネスをスタートさせます。
3. **アドバイスを見る**  
   画面上部の「経営アドバイス」を見ながら、黒字化を目指して販売数を増やしたり、経費を削るシミュレーションを行います。
4. **チートシートを活用する**  
   「数式と具体例 📖」ボタンを押すと、CVP分析（損益分岐点分析）の8つの公式と、費用の具体例をいつでも確認できます。

---

## 🔧 カスタマイズ

`index.html` 内の以下の部分をご自身の環境に合わせて書き換えてください。

- **Google Analytics ID**:  
  `<script async src="https://www.googletagmanager.com/gtag/js?id=G-********"></script>`
- **OGP画像の絶対パス**:  
  `<meta property="og:image" content="https://YOUR-DOMAIN.github.io/ogp.png">`
- **寄付用アドレス**:  
  最下部 `<footer>` 内のBitcoin (Lightning) アドレス。

---

## 💝 サポート (Support)

このプロジェクトが役に立った、会計の勉強になったという方は、ぜひLightning Networkでのチップをお願いします☕️

**Bitcoin (Lightning) Donation:**  
`brashridge65@walletofsatoshi.com`

---

## 📄 ライセンス (License)

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
