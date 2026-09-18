# OX — Type eXperience（仮）

> **仮置き**: もともと **TX** にあった「Type eXperience / Type OS」を、TX を **Traveler X** に明け渡すため **OX へ暫定移動**した。安定したら然るべき名へ移す。
>
> （本文中に残る "TX" は移設前の名残。順次 OX に読み替える。）

OX は、**TYPE のライフサイクル全体を規定するエコシステム**です。

TYPE を単なるデータ型としてではなく、既存の型から新しいゴール型を設計し、Agentによって実体化し、評価結果から次の型へ進化させるための生成仕様として扱います。

## Type is not limited to objects

> **type はオブジェクトに限らない。**

TYPE は名詞（オブジェクト）だけでなく、**動詞（体験・行為）**、**エージェント**、**ワークフロー**、**関係**、**界面**をも型として扱う。

```text
TYPE
 ├─ Object Type      名詞
 ├─ Verb Type        動詞（体験を語る）
 ├─ Agent Type       動詞を持つエージェント
 ├─ Workflow Type    動詞の連鎖
 ├─ Relation Type    関係（オントロジ）
 └─ Interface Type   型が交流する界面
```

## Verbs, Ontology, Interfaces

- **体験は動詞で語られる。** Experience is narrated by verbs.
- **動詞はオントロジで関係される。** Verbs are related through ontology.
- **動詞を持つエージェントはチームを作る。** Agents with verbs form teams → ecosystem.
- **界面で異なる型たちが交流する。** At interfaces, different types interact.
- **物理層と記号層を統一する。** Unify the physical layer and the symbolic layer.

```text
Experience → Verb → Ontology → Agent → Team → Ecosystem
                                   ↕
                              Interface
                                   ↕
                     Physical layer  ⇄  Symbolic layer
```

## Actor — 型学者 / Type Scholar

> **OX の主体は「型学者（Type Scholar）」である。**
> 既存の型（Archetype）を観察し、GoalType を設計し（protoTYPEing）、Agent に実体化させ、評価から型を進化させる人。

- **Role**: Type Scholar（型学者）
- **Handles**: TYPE
- **Method**: 観察 → 抽象化 → 型設計 → 実体化 → 評価 → 進化

## Core Flow

```text
                    TX
              TYPE Ecosystem
                     │
        ┌────────────┴────────────┐
        │                         │
    Archetype                 Environment
     原型・既存型                 市場・世界
        │                         │
        └──────────┬──────────────┘
                   ↓
                  MX
                 見る
                   ↓
             protoTYPEing
          型を発見・仮説化
                   ↓
              GoalType
             ゴール型を設計
                   ↓
             TYPE Definition
       MD / YAML / JSON / TS / RDF
                   ↓
                  AW
          Agentをspawnする
                   ↓
                  AX
           Agentを動かす
                   ↓
                  WX
                 書く
                   ↓
               Instance
              実際の成果物
                   ↓
              Evaluation
                   ↓
             Environment
                   ↓
                  MX
                   ↺
```

## TYPE Lifecycle

### 1. Archetype

既に存在する「型」。

- 受賞作
- 成功事例
- 既存プロダクト
- 既存ワークフロー
- 既存Agent
- 既存データ構造

### 2. Type

Archetypeから抽象化した、再利用可能な型。

```text
Archetype
    ↓ abstraction
Type
```

### 3. GoalType

今回、到達したい型。

```text
Type
  + 目的
  + 制約
  + 環境
  + 差分
      ↓
  GoalType
```

### 4. Instance

GoalTypeを実体化した成果物。

```text
GoalType
    ↓ instantiate
Instance
```

## protoTYPEing

**protoTYPEing** は、ArchetypeからGoalTypeを設計する活動です。

単に既存作品を模倣するのではなく、既存の型を観察・抽象化し、目的・環境・制約・差分を加えて、新しいゴール型を設計します。

```text
Archetype
   │
   ├── inherits structure
   ├── inherits function
   ├── inherits constraints
   │
   └── changes
        ├── theme
        ├── setting
        ├── technology
        └── experience
              ↓
          GoalType
```

## Type Representation

TYPEは一つの記法に限定しません。目的に応じて複数の表現を使います。

| Format | Role |
|---|---|
| MD | TYPEの意味・要求を人間向けに記述 |
| YAML | TYPEの宣言・設定 |
| JSON | TYPEの機械可読なデータ表現 |
| TS | TYPEの実装・型制約 |
| RDF | TYPE間の意味関係・Ontology |
| XML | TYPEの構造化・交換形式 |

```text
                    TYPE
                     │
        ┌────────────┼────────────┐
        ↓            ↓            ↓
      意味          構造          関係
       MD           YAML          RDF
                     │
                 データ表現
                  JSON/XML
                     │
                   実装
                    TS
```

## Agent Ecosystem

TXではAgentもTYPEとして扱います。

```text
TYPE
 ├─ Object Type
 ├─ Work Type
 ├─ Agent Type
 ├─ Workflow Type
 ├─ Data Type
 ├─ Requirement Type
 └─ Goal Type
```

Agent TypeからAgent Instanceを生成します。

```text
AgentType
    ↓ spawn
Agent Instance
```

AWとAXはこの型システムを実行する層です。

- **AW = Agentをspawnする**
- **AX = Agentを動かす**
- **WX = 書く**
- **DX = 人が操作する**

## MX / RX / WXとの関係

```text
MX
見る
 ↓
RX
掘る
 ↓
TYPX / protoTYPEing
型を仮説化・GoalTypeを設計
 ↓
AW
Agentをspawnする
 ↓
AX
Agentを動かす
 ↓
WX
書く・作る
 ↓
Instance
 ↓
Evaluation
 ↓
MX
また見る
```

## Example: Novel Type

`hoshi-novel` をTXの具体例として考えると、次のようになります。

```text
Archetype
  過去の受賞作
      ↓
Type
  受賞につながった可能性のある短編の型
      ↓
GoalType
  2026年に成立する1万字短編の型
      ↓
Requirement
  GoalTypeを満たす作品要求
      ↓
WX
  実際に小説を書く
      ↓
Instance
  1万字小説
      ↓
Evaluation
  評価・反応
      ↓
MX
  次の型を再検討
```

重要なのは、**受賞を保証する型を作ることではなく、観察可能な過去の作品・選評・条件などから「次に成立し得る型」を仮説化すること**です。

## OX as Type OS

OX は、

> **Archetype → Type → GoalType → Agent → Instance → Evaluation → 次のType**

という型の循環を規定します。

つまりOXは、TYPEを保存するだけではなく、**TYPEを発見し、継承設計し、Agentに実行させ、成果物として実体化し、評価結果からTYPEを進化させるためのType OS**です。
