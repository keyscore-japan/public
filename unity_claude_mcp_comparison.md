# Unity × Claude Code / MCP 比較表

## 1. 基本比較

| 項目 | Unity公式 Claude Code Plugin | Unity公式 MCP | CoplayDev MCP for Unity | KarnelLabs MCP |
|---|:---:|:---:|:---:|:---:|
| 開発元 | Unity | Unity | CoplayDev / Aura | KarnelLabs / OSS |
| 公式性 | 🟢 Unity公式 | 🟢 Unity公式 | 🔵 非公式 | 🔵 非公式 |
| Claude Code | ◎ | ◎ | ◎ | ◎ |
| Unity Editor操作 | ◎ | ◎ | ◎ | ◎ |
| Unity CLI操作 | ◎ | ○ | △ | △ |
| Scene操作 | ◎ | ◎ | ◎ | ◎ |
| GameObject操作 | ◎ | ◎ | ◎ | ◎ |
| Component操作 | ◎ | ◎ | ◎ | ◎ |
| C#編集 | ◎ | ◎ | ◎ | ◎ |
| Asset操作 | ◎ | ◎ | ◎ | ◎ |
| Console / エラー確認 | ◎ | ◎ | ◎ | ◎ |
| Animation | ○ | ○ | ◎ | ◎ |
| UI | ○ | ○ | ◎ | ◎ |
| テスト | ◎ | ◎ | ◎ | ◎ |
| Build | ◎ | ◎ | ◎ | ◎ |
| Profiling | ○ | ○ | ◎ | ◎ |
| AI画像/音声/3D生成 | △ | △ | ◎ | △ |
| カスタムMCP Tool | ○ | ◎ | ◎ | ◎ |
| Unity対応範囲 | Unity公式サポート範囲 | Unity公式サポート範囲 | 2021.3 LTS～Unity 6.x | Unity 6 |
| OSS | — | — | MIT | MIT |
| ツール数 | CLI / Skills中心 | Unity公式仕様 | 47 MCP entrypoints | 710+ tools / 74カテゴリ |
| 複数Unity同時操作 | ○ | ○ | ◎ | ◎ |
| 導入の簡単さ | ◎ | ◎ | ○ | ○ |
| 自由度 | ◎ | ◎ | ◎ | ◎ |
| 安定性・公式サポート | ◎ | ◎ | ○ | ○ |
| 主な用途 | Claude CodeでUnity開発全般 | Unity EditorをAIから操作 | 本格的なAI Unity開発 | 非常に細かいEditor操作 |

## 2. 「Claudeにゲームを1本作らせる」能力比較

| 開発作業 | Unity公式 Plugin | Unity公式 MCP | CoplayDev | KarnelLabs |
|---|:---:|:---:|:---:|:---:|
| C#コード生成 | ◎ | ◎ | ◎ | ◎ |
| 既存コード解析・修正 | ◎ | ◎ | ◎ | ◎ |
| Scene新規作成 | ○ | ◎ | ◎ | ◎ |
| GameObject生成 | ○ | ◎ | ◎ | ◎ |
| Component追加/変更 | ○ | ◎ | ◎ | ◎ |
| Prefab操作 | ○ | ◎ | ◎ | ◎ |
| Material作成/変更 | ○ | ◎ | ◎ | ◎ |
| Lighting設定 | ○ | ◎ | ◎ | ◎ |
| Camera設定 | ○ | ◎ | ◎ | ◎ |
| UI Toolkit | ◎ | ○ | ◎ | ◎ |
| uGUI | ○ | ○ | ◎ | ◎ |
| 2D / Tilemap | ◎ | ○ | ◎ | ◎ |
| Animation / Animator | ○ | ○ | ◎ | ◎ |
| Timeline | ○ | ○ | ◎ | ◎ |
| Cinemachine | ○ | ○ | ◎ | ◎ |
| Physics | ○ | ◎ | ◎ | ◎ |
| 敵AI / Gameplay | ◎ | ◎ | ◎ | ◎ |
| Input System | ◎ | ○ | ◎ | ◎ |
| Asset管理 | ◎ | ◎ | ◎ | ◎ |
| Asset自動生成/Import | ○ | ○ | ◎ | ◎ |
| Console確認 | ○ | ◎ | ◎ | ◎ |
| エラー修正ループ | ◎ | ◎ | ◎ | ◎ |
| Unity Test実行 | ○ | ◎ | ◎ | ◎ |
| Profiler / 最適化 | ○ | ○ | ◎ | ◎ |
| Build | ○ | ◎ | ◎ | ◎ |
| Screenshot取得/確認 | △ | ○ | ○ | ◎ |
| XR / VR | ○ | ○ | ○ | ◎ |
| 大量のEditor操作 | △ | ◎ | ◎ | ◎ |
| カスタムTool追加 | ○ | ◎ | ◎ | ◎ |
| 複数Unity Editor | △ | △ | ◎ | ◎ |

## 3. ゲーム制作工程ごとの比較

| 工程 | Unity公式 Plugin | 公式 MCP | CoplayDev | KarnelLabs |
|---|:---:|:---:|:---:|:---:|
| ① プロジェクト構成 | ◎ | ○ | ◎ | ◎ |
| ② Scene構築 | ○ | ◎ | ◎ | ◎ |
| ③ Player生成 | ○ | ◎ | ◎ | ◎ |
| ④ Character Controller | ◎ | ◎ | ◎ | ◎ |
| ⑤ Camera | ○ | ◎ | ◎ | ◎ |
| ⑥ 敵キャラクター | ○ | ◎ | ◎ | ◎ |
| ⑦ 敵AI | ◎ | ◎ | ◎ | ◎ |
| ⑧ 武器/攻撃 | ◎ | ◎ | ◎ | ◎ |
| ⑨ Animation | ○ | ○ | ◎ | ◎ |
| ⑩ Animator設定 | ○ | ○ | ◎ | ◎ |
| ⑪ UI | ◎ | ○ | ◎ | ◎ |
| ⑫ Audio | ◎ | ○ | ◎ | ◎ |
| ⑬ Lighting | ◎ | ◎ | ◎ | ◎ |
| ⑭ Level制作 | ○ | ◎ | ◎ | ◎ |
| ⑮ Test | ○ | ◎ | ◎ | ◎ |
| ⑯ Debug | ◎ | ◎ | ◎ | ◎ |
| ⑰ Optimization | ○ | ○ | ◎ | ◎ |
| ⑱ Build | ○ | ◎ | ◎ | ◎ |

## 4. モーション開発を重視した比較

| モーション関連 | 公式 Plugin | 公式 MCP | CoplayDev | KarnelLabs |
|---|:---:|:---:|:---:|:---:|
| Animation操作 | ○ | ○ | ◎ | ◎ |
| Animator操作 | ○ | ○ | ◎ | ◎ |
| Timeline | ○ | ○ | ◎ | ◎ |
| Cinemachine | ○ | ○ | ◎ | ◎ |
| Asset Import | ○ | ◎ | ◎ | ◎ |
| 独自Motion AI接続 | ◎ | ◎ | ◎ | ◎ |
| 独自MCP Tool | ○ | ◎ | ◎ | ◎ |

## 5. Claude Code + Unity の役割分担

```text
                    Claude Code
                         │
       ┌─────────────────┼─────────────────┐
       │                 │                 │
       ▼                 ▼                 ▼
 Unity公式 Plugin   Unity公式 MCP      非公式MCP
       │                 │          ┌──────┴──────┐
 Unityの正しい知識     Editor操作     CoplayDev  KarnelLabs
       │                 │          └──────┬──────┘
       └─────────────────┼─────────────────┘
                         ▼
                       Unity
                         │
        ┌────────────────┼────────────────┐
        ▼                ▼                ▼
      Game             Asset          Animation
```

## 6. Kinect / Motion AIとの組み合わせイメージ

```text
                    Claude Code
                         │
              ┌──────────┴──────────┐
              │                     │
        Unity公式 Plugin       MCP Server
              │                     │
        Unityの知識・Skills       Unity操作
              │                     │
              └──────────┬──────────┘
                         ▼
                    CoplayDev
                    or KarnelLabs
                         │
                         ▼
                       Unity
                         │
        ┌────────────────┼────────────────┐
        │                │                │
      Game             Asset          Animation
        │                │                │
        └────────────────┼────────────────┘
                         │
                     自作MCP
                         │
                 ┌───────┴───────┐
                 │               │
              Kinect         Motion AI
                 │               │
                 └───────┬───────┘
                         ▼
                    3D Motion
```

## 7. 要点

- **Unity公式 Claude Code Plugin**：Unity固有の知識・SkillsをClaude Codeに与える用途。
- **Unity公式 MCP**：Claude CodeなどからUnity Editorを操作する用途。
- **CoplayDev MCP**：Unity Editorの広範な操作をAIから実行することに重点。既存Unityプロジェクトへの対応範囲も広い。
- **KarnelLabs MCP**：非常に多数の細粒度Toolを提供し、Animation、Rendering、UI、XRなどまで広く操作する方向。
- これらは必ずしも排他的ではなく、**公式Plugin + MCP + 必要に応じて非公式MCP + 自作MCP**という構成も可能。
- Kinect / Motion AIを組み合わせる場合は、Animation、Animator、Timeline、Asset Import、自作MCP Toolの拡張性が特に重要。

> 注：◎/○/△は「AIゲーム開発での使いやすさ・操作範囲」を比較するための整理であり、各プロジェクトのUnityバージョン、導入方法、Tool設定によって実際の対応範囲は変わります。
