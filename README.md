# Indra's Net (因陀羅網)

> 一即多・多即一 —— すべての存在が互いを映し出し合う、華厳の世界観をプログラムで表現するデジタルアート／シミュレーション

`indras-net` は、華厳宗の核心概念である**「因陀羅網（いんだらもう）」**や**「事事無礙法界（じじむげほうかい）」**の世界観をプログラミングおよび相互作用的なビジュアルで表現したプロジェクトです。

## 概念とモチーフ (Concept)

華厳の哲学において、宇宙は無限の結び目からなる網（インドラの網）に例えられます。それぞれの結び目には輝く宝珠（Jewel）が配置され、ひとつの宝珠の表面には他のすべての宝珠が映し出されています。

- **一即多・多即一 (One is All, All is One)**: ひとつのノード（宝珠）を深く掘り下げると、その中に全宇宙のデータ構造が内包されています。
- **事事無礙 (Unobstructed Interpenetration)**: 個々の存在が独立しつつも、互いに干渉・共鳴し合い、一つの変化が全体へ波及します。
- **無尽縁起 (Endless Dependent Origination)**: 部分と全体が無限に影響し合う連鎖的な関係性を表現します。

## 主な特徴 (Features)

- **再帰的データ構造 / グラフネットワーク**: ノード同士が相互に参照し合い、状態を映し出す相互依存モデル。
- **インタラクティブビジュアル**: ブラウザ（Canvas / WebGL等）上でノードを操作し、光や状態の波及・共鳴を可視化。
- **リアクティブ・イベント伝播**: 1つのノードへのアクションがネットワーク全体に即時かつ連鎖的に影響を与える仕組み。

## 技術スタック (Tech Stack)

- **Language**: Python / JavaScript (TypeScript)
- **Visualization**: HTML5 Canvas / WebGL (Three.js 等)
- **Architecture**: オブザーバーパターン / リアクティブプログラミング (Rx) / フラクタル構造

## クイックスタート (Getting Started)

### 依存関係のインストール

```bash
git clone [https://github.com/your-username/indras-net.git](https://github.com/your-username/indras-net.git)
cd indras-net
npm install  # または pip install -r requirements.txt
```

実行方法
npm start    # または python main.py

ブラウザで http://localhost:3000 を開いてシミュレーションを起動します。
使い方・操作方法 (Usage)
 * ノード（宝珠）の選択: ノードをクリックすると、そのノードが中心となり、他の全ノードとの相互投影・強調表示が行われます。
 * 状態の変化（共鳴）: ダブルクリックやドラッグで特定のノードにエネルギー（変化）を与えると、インドラの網を通じて全体へ波及します。
ライセンス (License)
MIT License

---

プロジェクトの具体的な実装言語（Python / JavaScript等）や描画ライブラリに合わせて、適宜「技術スタック」や「クイックスタート」のコマンドを変更してご活用ください。

