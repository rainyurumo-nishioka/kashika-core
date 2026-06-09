ご提示いただいたシビックテック・プロジェクト「KASHIKA」のドキュメントを、オープンソースの思想やテックカルチャー（GitHubやWeb3の文脈）に馴染む自然でプロフェッショナルな英語に翻訳しました。

KASHIKA - Global Open Policy Ledger
KASHIKA is an autonomous, decentralized civic-tech platform designed to refactor politics and social infrastructure based on "data (facts)" rather than emotion. By leveraging the technology and labor of citizens, we aim to update outdated state systems and opaque processes into structured data (JSON), semi-permanently sustaining a "cycle of trust" across the globe.

🏛 Core Principles (Project Constitution)
Facts Only
We never handle political bias, emotional criticism, or scandals. The platform's foundation consists solely of structured data rooted in verifiable records (logs).

Identity & Accountability (Visualizing Responsibility & Contribution)
We clarify exactly "who converted which primary source into data." Verified individuals or organizations are automatically awarded SBTs (Soulbound Tokens) by the system based on their track record, which serve as trust coefficients for governance.

Decentralized Multi-National Hub
Information is created where it belongs (the local country folder) by the local experts who know it best. Rather than copying and siloing other countries' data, nations use a common language (English) to reference it via pointers, synchronizing global knowledge by "donating" translated data back to the original repository.

🌐 Global-Localization Rules
Local Folder Rules: When writing out your own country's policy data, you must include the global lingua franca text ("English") in addition to the "Local Language."

Translation Rules for External (Global) Use Cases:
If contributors in Japan wish to reference and translate a pioneering case from overseas (e.g., the India folder 91/), do not create a copy in the Japan folder. Instead, submit a pull request (donation) containing the translation file formatted as _ja.json directly within the relevant folder of that overseas repository.

🏛 The Two Iron Rules for Handling Imperial Era & Former Overseas Territory Data (1895–1945)
The historical facts show that legislation and infrastructure investments in Manchuria, Taiwan, the Korean Peninsula, and Southeast Asia (during the Southern Military Administration period) under the Empire of Japan served as "prototypes (testing grounds)" for post-war Japanese bureaucratic institutions and social systems. Therefore, they fall within the tracking scope of this project.

However, because this is an extremely sensitive historical and political domain, you must strictly adhere to the following two iron rules to prevent unnecessary friction with the data grid of the international community.

① Commit to "Design Specifications (Facts)" and Eliminate Adjectives
Political right or wrong and subjective evaluations (e.g., "significantly contributed to modernization and development" or "unjustly plundered local resources through oppressive military rule") belong to the realm of human emotion and interpretation. This platform does not handle them at all. Describe only the data structures that exist within the records (logs).

❌ NG (Mixing in adjectives/subjectivity):
"Japan greatly contributed to the modernization and development of local infrastructure."
"The oppressive military government wrongfully stripped the local population of their resources."

⭕ OK (Pure Fact Logs):
"In 1938, a funds transfer of XX yen from the Ministry of Finance to the Government of Manchukuo occurred. (Source: Ministry of Finance, Shōwa Fiscal History)"
"Execution log for the modernization (structured data conversion) of land rights relationships based on Government-General of Taiwan Ordinance No. XX."

② Design with Cross-Referencing (Pointer Coupling) to Other Country Gates as a Prerequisite
Data stored in the Japan folder (81/) is strictly "design data extracted from Japanese official documents and budgets."

In the future, when independent gates (repositories) for Taiwan (886/) or other countries/regions are launched and they accumulate data based on "local perspectives and primary sources," the frontend interface will seamlessly snap both datasets together into a single timeline via mutual pointer references to visualize them.

Do not attempt to make history self-contained within your own country's data. Design your JSON as an "open grid" that can interface with external repositories.

📂 Directory Structure
The repository directories are separated by international calling codes (country codes). This ensures the independence of each country and avoids merge conflicts.

Plaintext
kashika-core/
├── schema.json                 # Global data definition file
├── README.md                   # This document
├── 1/                          # North America (US, Canada, etc.)
├── 81/                         # Japan
│   ├── config.json             # Japan local settings / Organization index
│   └── policies/               # Policy and bill folder (Japanese + English required)
│       └── 81_digital_infra.json
├── 886/                        # Taiwan
└── 91/                         # India
    └── policies/
        ├── 91_aadhaar.json     # Source file (Hindi/English)
        └── 91_aadhaar_ja.json  # Japanese translation "donated" by a Japanese contributor



# KASHIKA (可視化) - Global Open Policy Ledger

KASHIKAは、感情ではなく「データ（事実）」で政治と社会インフラをリファクタリングするための、自律分散型のシビックテック・プラットフォームです。国が作った古いシステムや不透明なプロセスを、市民の側の技術と労働力によって構造化データ（JSON）へとアップデートし、世界中で「信頼の循環」を半永続化させることを目指します。

## 🏛 基本理念（プロジェクトの憲法）

1. **Facts Only (事実のみを扱う)**
   政治的な偏向、感情的な批判、スキャンダルは一切扱いません。記録（ログ）に基づく構造化データのみをプラットフォームの土台とします。
2. **Identity & Accountability (責任と貢献の可視化)**
   「誰が、どの一次ソースを基にデータ化したか」を明確にします。検証された個人や団体には、行動実績に応じてSBT（Soulbound Token）がシステムから自動付与され、ガバナンスの信頼度係数となります。
3. **Decentralized Multi-National Hub (自律分散型の多国籍ハブ)**
   情報は「それがあるべき場所（現地の国フォルダ）」で、最も詳しい現地の人々が作成します。他国はそれをコピーして囲い込むのではなく、共通語（英語）を介してポインタ参照し、翻訳データを元リポジトリへ「寄贈」する形で世界中の知見を同期します。

## 🌐 グローバル・ローカリゼーションルール

- **自国（Local）フォルダのルール:** 自国の政策データを書き出す際は、必ず「現地語」に加えて、世界共通語である「英語（global）」のテキストを内包させてください。
- **他国（Global）事例の翻訳ルール:**
  日本側が海外（例: インドフォルダ `91/`）の先行事例を参照・翻訳したい場合、日本側にコピーを作るのではなく、海外リポジトリの該当フォルダ内に `_ja.json` の形式で翻訳ファイルをプルリクエスト（寄贈）してください。

  ## 🏛 帝国期・旧外地データ（1895〜1945）の取扱における2つの鉄則

大日本帝国期における満州、台湾、朝鮮半島、東南アジア（南方軍政期）等の法整備やインフラ投資は、戦後の日本型官僚機構や社会システムの「プロトタイプ（実験場）」となっていたファクトが存在するため、本プロジェクトの追跡対象に含みます。ただし、歴史的・政治的に極めて繊細な領域であるため、国際社会のデータ（格子）と不必要な衝突を起こさないよう、以下の2つの鉄則を厳守してください。

### ① 「設計仕様書（ファクト）」に徹し、形容詞を排除する
政治的な善悪、主観的な評価（例：「近代化に貢献した」「搾取・植民地支配を行った」等）は人間の感情と解釈の領域であり、本プラットフォームでは一切扱いません。記録（ログ）に存在するデータ構造のみを記述してください。

- ❌ **NG（形容詞・主観の混入）:**
  「日本が現地インフラの近代化と発展に大きく寄与した」
  「抑圧的な軍政によって現地の物資を不当に剥奪した」
- ⭕ **OK（純粋なファクトログ）:**
  「1938年、当時の大蔵省から満州国政府へ〇〇円の資金移動（ソース：大蔵省昭和財政史）」
  「台湾総督府令第〇号に基づく、土地権利関係の近代化（構造化データ化）の執行ログ」

### ② 他国ゲートとの「相互参照（ポインタ結合）」を前提とする
日本側（81）のフォルダに格納するデータは、あくまで「日本側の公文書や予算から抽出した設計データ」です。
将来、台湾（886）や他の国・地域の独立ゲート（リポジトリ）が立ち上がった際、彼らが「現地側の視点・1次資料」に基づくデータを蓄積した場合、フロントエンド（画面）は双方のデータを1つのタイムライン上でカチッと結合（相互ポインタ参照）して可視化します。

自国のデータだけで歴史を完結させようとせず、他国リポジトリと接続可能な「開かれた格子」としてJSONを設計してください。



## 📂 フォルダの雛形（Directory Structure）

リポジトリは国際電話番号（国番号）の格子によってディレクトリが分離されています。これによって各国の独立性とマージ時の衝突回避を担保します。

```text
kashika-core/
├── schema.json                 # 世界共通データ定義書
├── README.md                   # 本ドキュメント
├── 1/                          # 北米（アメリカ・カナダ等）
├── 81/                         # 日本（Japan）
│   ├── config.json             # 日本国内の設定・所属団体インデックス
│   └── policies/               # 政策・法案フォルダ（日本語＋英語必須）
│       └── 81_digital_infra.json
├── 886/                        # 台湾（Taiwan）
└── 91/                         # インド（India）
    └── policies/
        ├── 91_aadhaar.json     # 本家（インド語/英語）
        └── 91_aadhaar_ja.json  # 日本人コントリビューターが「寄贈」した日本語訳
