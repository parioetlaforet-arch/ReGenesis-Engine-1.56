# ReGenesis Engine – Full Eco Simulation  
A > B > C > A Ecosystem + Mutation + Predation + Memory Inheritance + E/F-type Evolution  
ReGenesis Engine ver1.56 / 2026  
Created by M. Morimoto
parioetlaforet@gmail.com
---

## 🌍 Overview
ReGenesis Engine は、人工生命をテーマにした **セルオートマトン型の生態系シミュレーション**です。  
個体はランダムに動き、捕食し、突然変異し、進化し、死に、そして環境そのものも変動します。

本プロジェクトは次の問いを追求します：

> **「生命は単純なルールからどこまで複雑さを獲得できるのか？」**

---

## 🧬 Features

### 🔁 1. Rock–Paper–Scissors 型の捕食関係（A > B > C > A）
- **A：捕食者（Predator）**  
- **B：腐食者（Scavenger）**  
- **C：吸収捕食者（Absorptive Predator）**  
- **G：生産者（Producer）**

三すくみ構造が世界の基本動態を形成します。

---

### 🧪 2. 突然変異と形質進化
- 分裂時に突然変異が発生  
- **トゲ（spikes）・伸長率（elongation）・色相（colorShift）** などの形質が継承・変異  
- A型は経験値に応じて進化（外見・能力が変化）  
- 死亡時に“記憶”を地面へ残し、次世代が吸収して強化（MEG: Memory-Embedded Ground）

---

### 🧓 3. E型（Elder / Worm）
C型が捕食を極めると昇華して誕生する上位存在。

- 長寿・高耐久  
- トゲ構造の急激な発達  
- 周囲の化学環境を操作  
- 群体（Cluster）への反撃行動  

---

### 🧠 4. F型（Collective Intelligence）
E型が密集し、廃棄物が蓄積すると自然発生する  
**集合知生命体（Collective Intelligence）**。

---

### 🧩 5. Cluster（群れ）システム
- C型が3体以上近接すると群れを形成  
- 単体より強力で周囲を排除  
- 寿命があり、時間とともに崩壊  

---

### 🌋 6. 環境イベント
- 粒子降雨（軽度の資源増加）  
- 天変地異（大規模な資源変動）  
- 毒気候の発生  
- 世界リセットイベント  

---

### 📊 7. リアルタイム統計チャート
- G / A / B / C / E / EvA（進化A）の個体数をリアルタイム表示  
- 最大 1000 ターン分のデータを保持  
- HTML5 Canvas による軽量描画  

---

## 🎮 Controls

| 操作 | 内容 |
|------|------|
| **Start** | シミュレーション開始 |
| **Stop** | 一時停止 |
| **Restart** | 世界をリセットして再生成 |
| **God’s Mischief** | 特殊イベント（始祖Eタイプの降臨） |
| **Canvas ダブルクリック** | スクリーンセーバーモード切替（全画面描画） |

---

## ⚙️ Parameters（スライダーで調整可能）
- 初期個体数  
- シミュレーション速度  
- A/B 突然変異率  
- 毒性係数 / 最大毒濃度  
- 栄養肥沃度  
- 密度依存死亡率  
- Gタイプ自然発生率  

---

## 🏗️ Technical Notes
- HTML5 Canvas による軽量描画  
- **純粋な JavaScript のみで動作（外部ライブラリ不使用）**  
- 160×160 のセルマップ  
- 1ターンごとに  
  - 移動 → 捕食 → 死亡判定 → 分裂 → 突然変異 → 環境変動  
  を実行  

---

## 📜 Philosophy
生命は単純なルールからどこまで複雑さを生み出せるのか。  
形質の蓄積、記憶の継承、群れの形成、環境との相互作用、死と再生。  
これらが絡み合い、予測不能な **“生態系の物語”** が生まれます。

---

## 📦 How to Run
1. このリポジトリをダウンロード  
2. `index.html` をブラウザで開く  
3. **Start ボタンを押すだけ**  

追加セットアップは不要です。

---

## 📝 License
MIT License（または任意のライセンスを記載）

---

## 🙌 Author
Created by **M. Morimoto**  
ReGenesis Engine ver1.56 / 2026
# ReGenesis Engine – Full Eco Simulation  
A > B > C > A Ecosystem + Mutation + Predation + Memory Inheritance + E/F-type Evolution  
ReGenesis Engine ver1.56 / 2026  
Created by M. Morimoto

---

## 🌍 Overview
ReGenesis Engine は、人工生命をテーマにした **セルオートマトン型の生態系シミュレーション**です。  
個体はランダムに動き、捕食し、突然変異し、進化し、死に、そして環境そのものも変動します。

本プロジェクトは次の問いを追求します：

> **「生命は単純なルールからどこまで複雑さを獲得できるのか？」**

---

## 🧬 Features

### 🔁 1. Rock–Paper–Scissors 型の捕食関係（A > B > C > A）
- **A：捕食者（Predator）**  
- **B：腐食者（Scavenger）**  
- **C：吸収捕食者（Absorptive Predator）**  
- **G：生産者（Producer）**

三すくみ構造が世界の基本動態を形成します。

---

### 🧪 2. 突然変異と形質進化
- 分裂時に突然変異が発生  
- **トゲ（spikes）・伸長率（elongation）・色相（colorShift）** などの形質が継承・変異  
- A型は経験値に応じて進化（外見・能力が変化）  
- 死亡時に“記憶”を地面へ残し、次世代が吸収して強化（MEG: Memory-Embedded Ground）

---

### 🧓 3. E型（Elder / Worm）
C型が捕食を極めると昇華して誕生する上位存在。

- 長寿・高耐久  
- トゲ構造の急激な発達  
- 周囲の化学環境を操作  
- 群体（Cluster）への反撃行動  

---

### 🧠 4. F型（Collective Intelligence）
E型が密集し、廃棄物が蓄積すると自然発生する  
**集合知生命体（Collective Intelligence）**。

---

### 🧩 5. Cluster（群れ）システム
- C型が3体以上近接すると群れを形成  
- 単体より強力で周囲を排除  
- 寿命があり、時間とともに崩壊  

---

### 🌋 6. 環境イベント
- 粒子降雨（軽度の資源増加）  
- 天変地異（大規模な資源変動）  
- 毒気候の発生  
- 世界リセットイベント  

---

### 📊 7. リアルタイム統計チャート
- G / A / B / C / E / EvA（進化A）の個体数をリアルタイム表示  
- 最大 1000 ターン分のデータを保持  
- HTML5 Canvas による軽量描画  

---

## 🎮 Controls

| 操作 | 内容 |
|------|------|
| **Start** | シミュレーション開始 |
| **Stop** | 一時停止 |
| **Restart** | 世界をリセットして再生成 |
| **God’s Mischief** | 特殊イベント（始祖Eタイプの降臨） |
| **Canvas ダブルクリック** | スクリーンセーバーモード切替（全画面描画） |

---

## ⚙️ Parameters（スライダーで調整可能）
- 初期個体数  
- シミュレーション速度  
- A/B 突然変異率  
- 毒性係数 / 最大毒濃度  
- 栄養肥沃度  
- 密度依存死亡率  
- Gタイプ自然発生率  

---

## 🏗️ Technical Notes
- HTML5 Canvas による軽量描画  
- **純粋な JavaScript のみで動作（外部ライブラリ不使用）**  
- 160×160 のセルマップ  
- 1ターンごとに  
  - 移動 → 捕食 → 死亡判定 → 分裂 → 突然変異 → 環境変動  
  を実行  

---

## 📜 Philosophy
生命は単純なルールからどこまで複雑さを生み出せるのか。  
形質の蓄積、記憶の継承、群れの形成、環境との相互作用、死と再生。  
これらが絡み合い、予測不能な **“生態系の物語”** が生まれます。

---

## 📦 How to Run
1. このリポジトリをダウンロード  
2. `index.html` をブラウザで開く  
3. **Start ボタンを押すだけ**  

追加セットアップは不要です。

---

## 📝 License
MIT License（または任意のライセンスを記載）

---

## 🙌 Author
Created by **M. Morimoto**  
ReGenesis Engine ver1.56 / 2026
# ReGenesis Engine – Full Eco Simulation  
A > B > C > A Ecosystem + Mutation + Predation + Memory Inheritance + E/F-type Evolution  
ReGenesis Engine ver1.56 / 2026  
Created by M. Morimoto

---

## 🌍 Overview
ReGenesis Engine is a **cellular automaton–based ecosystem simulation** themed around artificial life.  
Entities move randomly, prey on each other, mutate, evolve, die, and reshape their environment in real time.

This project explores a central question:

> **"How much complexity can emerge from simple rules?"**

---

## 🧬 Features

### 🔁 1. Rock–Paper–Scissors Predation (A > B > C > A)
- **Type A: Predator**  
- **Type B: Scavenger / Corrosive**  
- **Type C: Absorptive Predator**  
- **Type G: Producer (basic resource)**

This triadic structure forms the core dynamics of the ecosystem.

---

### 🧪 2. Mutation & Trait Evolution
- Entities mutate during division  
- Traits such as **spikes**, **elongation**, and **colorShift** are inherited and modified  
- Type A evolves based on accumulated “experience points”  
- Upon death, individuals leave **MEG (Memory-Embedded Ground)**, which enhances the next generation

---

### 🧓 3. Type E (Elder / Worm)
When a Type C reaches a predation threshold, it **sublimates** into Type E.

Characteristics:

- Extreme longevity  
- High durability  
- Rapid spike development  
- Ability to manipulate local chemical gradients  
- Capable of countering Clusters  

---

### 🧠 4. Type F (Collective Intelligence)
When Type E individuals cluster and waste accumulates, **Type F** emerges.

Type F is not a single organism but a **collective intelligence** formed through chemical networking.

---

### 🧩 5. Cluster System
- Triggered when three or more Type C entities gather  
- Stronger than individuals and aggressively clears surroundings  
- Has a finite lifespan and eventually collapses  

---

### 🌋 6. Environmental Events
- Particle rainfall (mild resource increase)  
- Cataclysm (large-scale resource fluctuation)  
- Toxic climate  
- World reset events  

---

### 📊 7. Real-Time Statistical Charting
- Tracks populations of **G / A / B / C / E / EvA (Evolved A)**  
- Stores up to 1,000 turns of data  
- Lightweight HTML5 Canvas rendering  

---

## 🎮 Controls

| Action | Description |
|--------|-------------|
| **Start** | Begin the simulation |
| **Stop** | Pause the simulation |
| **Restart** | Reset and regenerate the world |
| **God’s Mischief** | Trigger a special event (Descent of the Primordial Type E) |
| **Canvas Double-Click** | Toggle screensaver mode (full-screen rendering) |

---

## ⚙️ Adjustable Parameters
- Initial population  
- Simulation speed  
- A/B mutation rates  
- Toxicity coefficient / maximum toxin concentration  
- Nutrient fertility  
- Density-dependent mortality  
- Type G spontaneous generation rate  

---

## 🏗️ Technical Notes
- Lightweight HTML5 Canvas rendering  
- **Pure vanilla JavaScript (no external libraries)**  
- 160×160 cell map  
- Each turn executes:  
  **Movement → Predation → Death Check → Division → Mutation → Environmental Flux**

---

## 📜 Philosophy
How far can complexity arise from simple rules?  
Trait accumulation, memory inheritance, cluster formation, environmental interaction, death and rebirth—  
these elements intertwine to create an unpredictable **“ecosystem narrative.”**

---

## 📦 How to Run
1. Download or clone this repository  
2. Open `index.html` in any modern web browser  
3. Press **Start**  

No additional setup required.

---

## 📝 License
MIT License (or any license you choose)

---

## 🙌 Author
Created by **M. Morimoto**  
ReGenesis Engine ver1.56 / 2026
