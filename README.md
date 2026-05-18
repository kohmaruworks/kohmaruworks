<div align="center">

# 🪐 Categorical Physics Engine × Geometric Deep Learning

**Bridging mathematical rigor and predictive ML — open, reproducible, public.**

[🇬🇧 English](#-english-version) ・ [🇯🇵 日本語](#-japanese-version)

[![physics-gnn-surrogate CI](https://github.com/kohmaruworks/physics-gnn-surrogate/actions/workflows/ci.yml/badge.svg)](https://github.com/kohmaruworks/physics-gnn-surrogate/actions/workflows/ci.yml)

</div>

---

## 🇬🇧 English Version

### Pioneering Next-Generation Physics Surrogate Models via Applied Category Theory and Geometric Deep Learning

We are developing and validating **surrogate models** that enable high-precision, high-speed physical simulations by combining physically rigorous worlds formulated through Applied Category Theory (ACT) with Geometric Deep Learning, including Graph Neural Networks (GNNs).

### 🌌 Two Core Pillars of Architecture

Our architecture consists of two independent pillars: a backend that guarantees rigorous mathematical structures, and a highly efficient frontend ecosystem for validation.

1. **[`categorical_physics_engine`](https://github.com/kohmaruworks/categorical_physics_engine) — Base Backbone Engine**
   A foundational mathematical engine utilizing Discrete Exterior Calculus (DEC) and Applied Category Theory to extract topological structures, generate rigorous data, and apply quantum computation theories (e.g., ZX-calculus) for efficient data compression.
2. **[`physics-gnn-surrogate`](https://github.com/kohmaruworks/physics-gnn-surrogate) — Validation Applications**
   A highly isolated frontend ecosystem that receives refined system representations from the backbone and performs spatiotemporal dynamic predictions using GNNs. Public monorepo with end-to-end CI.

### 🚀 Research & Validation Tracks

Our research evolves in parallel across specific themes (**Tracks**) based on the complexity of physical phenomena, rejecting traditional linear progressions.

- **Foundation Track** — exploring 1D topological structures (e.g. spring-mass chains). We compare GNNs against parameter-matched MLPs on a delta-prediction protocol using Minimal Reproducible Examples (MREs), establishing the empirical baseline for when graph structure does — and does not — help.
- **Multiphysics Track** — tackling high-dimensional discrete geometric structures (2D heterogeneous meshes) to validate heterogeneous message passing on topological graphs derived from ACT, with inference-time scaling characterized across mesh sizes.
- **Long-Term Stability Track** — simulating long-term time evolution of autoregressive wave propagation. We evaluate cumulative energy drift `|H(t_n) − H(0)| / |H(0)|` over many timesteps and build symplectic / Hamiltonian penalty-based stabilization techniques against vanilla MSE baselines.
- **Quantum Computation Track** *(upcoming)* — applying quantum graph theory and ZX-calculus for topological compression, mapping geometric structures to quantum representations for synergy with deep learning.
- **Cosmology Track** *(future exploration)* — simulating large-scale cosmic structures driven by fluid and gravitational interactions to reproduce macroscopic emergence from local mathematical rules.

### ⚖️ Scientific Integrity & Reproducibility

- **Visual Evidence** — we permanently embed *spatial topology network diagrams* and *Ground-Truth comparison curves* in our repositories to eliminate black boxes.
- **Single Quality Gate** — an integrated automated workflow maintains end-to-end visibility of dependencies, code quality, and convention consistency across the whole monorepo.

### 🧭 Explore

→ [`categorical_physics_engine`](https://github.com/kohmaruworks/categorical_physics_engine) (categorical / DEC / ZX backbone) ・ [`physics-gnn-surrogate`](https://github.com/kohmaruworks/physics-gnn-surrogate) (GNN validation monorepo)

---

## 🇯🇵 Japanese Version

### 応用圏論（ACT）と深層学習の融合による、次世代物理サロゲートモデル構築への挑戦

応用圏論（Applied Category Theory）に基づき数理的に定式化された物理世界と、グラフニューラルネットワーク（GNN）をはじめとする幾何学的深層学習を結合し、高精度かつ高速な物理シミュレーションを可能にする「**サロゲートモデル**（代替モデル）」の開発・検証を行っています。

### 🌌 アーキテクチャの 2 大支柱

本プロジェクトは、厳密な数学的構造を担保するバックエンドと、それらを検証・評価する高効率なフロントエンドの 2 つの独立した支柱から構成されています。

1. **[`categorical_physics_engine`](https://github.com/kohmaruworks/categorical_physics_engine) — バックエンド・基盤エンジン**
   離散外微分幾何学（DEC）や応用圏論を活用し、トポロジー構造の抽出、厳密なデータ生成、および量子計算理論（ZX 計算等）を応用したデータ圧縮を担う基盤数理エンジン。
2. **[`physics-gnn-surrogate`](https://github.com/kohmaruworks/physics-gnn-surrogate) — フロントエンド・検証アプリケーション**
   基盤エンジンから提供される洗練されたシステム表現を受け取り、幾何学的深層学習（GNN）を用いて時空間の動態予測を行うフロントエンド群。end-to-end CI 付きの Public monorepo。

### 🚀 研究・検証ロードマップ（Research Tracks）

開発と検証は単なる時間軸ではなく、対象とする物理現象の複雑度に応じた以下の「**研究編（Tracks）**」として並列・進化的に展開しています。

- **基礎編（Foundation Track）** — 1 次元のトポロジー構造 (例: バネ–質量チェーン) における相互作用。最小再現コード（MRE）上で GNN と同パラメータ規模の MLP をデルタ予測プロトコルで比較し、「グラフ構造が効くケース／効かないケース」の経験的ベースラインを確立する。
- **マルチフィジックス編（Multiphysics Track）** — 高次元離散幾何構造（2 次元・異種メッシュ）。応用圏論から導かれるトポロジカルグラフ上での Hetero メッセージパッシングの有効性を検証し、メッシュサイズに対する推論時間スケーリングも併せて定量化する。
- **長期安定化編（Long-Term Stability Track）** — 自己回帰的な波動伝播の長期時間発展。多タイムステップ自己回帰推論における累積エネルギードリフト `|H(t_n) − H(0)| / |H(0)|` を評価し、Vanilla MSE ベースラインに対し symplectic / Hamiltonian ペナルティに基づく安定化手法を構築する。
- **量子計算・データ圧縮編（Quantum Computation Track）** *(着手予定)* — ZX 計算によるトポロジー構造の量子論的圧縮と深層学習のシナジー探求。幾何構造を量子表現にマップする。
- **宇宙論・大規模構造編（Cosmology Track）** *(将来探索)* — 局所的な数理規則からマクロな宇宙構造の創発を再現する究極の適用検証。

### ⚖️ 科学的誠実さと再現可能性

- **視覚的エビデンス（Visual Evidence）** — 「空間トポロジーのネットワーク図」および「真値との比較曲線」の正規画像を永続化し、ブラックボックス化を排除。
- **厳格な品質ゲート（Single Quality Gate）** — 統合された自動化ワークフローにより、依存関係・コード品質・記述規約の一貫性を monorepo 全体で常に保全。

### 🧭 Explore

→ [`categorical_physics_engine`](https://github.com/kohmaruworks/categorical_physics_engine)（categorical / DEC / ZX backbone） ・ [`physics-gnn-surrogate`](https://github.com/kohmaruworks/physics-gnn-surrogate)（GNN 検証 monorepo）
