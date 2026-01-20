<h3 align="center">DDC CWICR - 建設工事項目・コンポーネント・リソースデータベース</br>
  + 説明文、写真、CAD (BIM) に基づく見積計算のための n8n パイプライン</h3>

<p align="center">
  <a href="README.md">English</a> •
  <a href="README.zh-CN.md">中文</a> •
  <a href="README.es.md">Español</a> •
  <a href="README.pt-BR.md">Português</a> •
  <a href="README.ru.md">Русский</a> •
  <a href="README.ja.md"><b>日本語</b></a> •
  <a href="README.de.md">Deutsch</a> •
  <a href="README.fr.md">Français</a>
</p>

<p align="center">
  <img src="https://github.com/datadrivenconstruction/cad2data-Revit-IFC-DWG-DGN-pipeline-with-conversion-validation-qto/blob/main/DDC_in_additon/DDC_readme_content/OpenConstructionEstimate.jpg" alt="OpenConstructionEstimate" width="1000">
</p>

<div align="center">
  <img src="https://img.shields.io/badge/工事項目-55,719-2563eb?style=for-the-badge" alt="Work Items">
  <img src="https://img.shields.io/badge/リソース-27,672-059669?style=for-the-badge" alt="Resources">
  <img src="https://img.shields.io/badge/言語-9-d97706?style=for-the-badge" alt="Languages">
  <img src="https://img.shields.io/badge/国-10+-dc2626?style=for-the-badge" alt="Countries">
</div>

<br>

<p align="center">
  <a href="https://openconstructionestimate.com">
    <img src="https://img.shields.io/badge/🌐_ライブデモ-openconstructionestimate.com-2563eb?style=for-the-badge" alt="Live Demo">
  </a>
</p>

---

## 🚀 AIプロダクトのための完璧な燃料

<p align="center">
  <b>リポジトリをクローンして、欲しいものを説明するだけ — AIが残りを行います</b>
</p>

DDC CWICRは単なるデータベースではありません — **AI駆動アプリケーションのためのすぐに使える燃料**です。コスト見積ボットの構築、建設ワークフローの自動化、インテリジェントアシスタントの作成など — このデータは最新のAIツールですぐに使用できます。

### このデータベースがAIに最適な理由

| 特徴 | メリット |
|------|----------|
| **事前計算済みエンベディング** | ベクトル生成不要 — セマンティック検索が即座に機能 |
| **85フィールドの構造化スキーマ** | AIがデータ関係を推論し、正確な回答を提供可能 |
| **9言語を含む** | 翻訳コストなしで多言語アプリケーションを構築 |
| **55,000以上の工事項目** | あらゆる建設見積タスクを包括的にカバー |
| **リソースベースの方法論** | AIが説明・分解できる透明性のあるデータ |

### 🛠️ 最適な連携ツール

<table>
<tr>
<td align="center" width="25%">
<img src="https://img.shields.io/badge/Claude_Code-000000?style=for-the-badge&logo=anthropic&logoColor=white" alt="Claude Code"/><br/>
<b>Claude Code</b><br/>
<sub>AIコーディングアシスタント</sub>
</td>
<td align="center" width="25%">
<img src="https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white" alt="n8n"/><br/>
<b>n8n</b><br/>
<sub>ワークフロー自動化</sub>
</td>
<td align="center" width="25%">
<img src="https://img.shields.io/badge/Dify-1677FF?style=for-the-badge&logo=openai&logoColor=white" alt="Dify"/><br/>
<b>Dify</b><br/>
<sub>LLMアプリ開発</sub>
</td>
<td align="center" width="25%">
<img src="https://img.shields.io/badge/Sim_AI-6366F1?style=for-the-badge&logo=simpleicons&logoColor=white" alt="Sim AI"/><br/>
<b>Sim AI他</b><br/>
<sub>AIプラットフォーム</sub>
</td>
</tr>
</table>

---

### 💻 Claude Code — AIコーディングアシスタント

DDC CWICRを使用する最速の方法。Claude Codeでリポジトリを開き、自然言語で質問するだけです。

**はじめに：**
```bash
# リポジトリをクローン
git clone https://github.com/datadrivenconstruction/OpenConstructionEstimate-DDC-CWICR.git

# Claude Codeで開く
cd OpenConstructionEstimate-DDC-CWICR
claude
```

**プロンプト例：**

| タスク | プロンプト |
|--------|------------|
| **データ探索** | 「この建設データベースの構造を表示し、どのようなデータが利用可能か説明してください」 |
| **項目検索** | 「コンクリート基礎に関連するすべての工事項目を見つけ、コストを表示してください」 |
| **クエリ作成** | 「労働時間が100時間以上の配管工事項目を検索するPythonスクリプトを書いてください」 |
| **レポート作成** | 「住宅リノベーション工事のコスト内訳レポートを生成してください」 |
| **コスト分析** | 「異なる壁構築方法の材料コストを比較してください」 |
| **統合構築** | 「Qdrantデータベースに接続してセマンティック検索を行うスクリプトを作成してください」 |

---

### ⚡ n8n — ビジュアルワークフロー自動化

コーディングなしで強力な自動化パイプラインを構築。DDC CWICRを400以上のアプリやサービスに接続。

**ユースケース：**

| ワークフロー | 説明 |
|--------------|------|
| **Telegramボット** | ユーザーがテキスト/写真を送信 → AIが工事項目を抽出 → 見積を返送 |
| **メール自動化** | メールでBOQを受信 → AIで処理 → フォーマットされた見積を送信 |
| **CRM統合** | CRMの新規プロジェクト → 予備見積を自動生成 → 取引額を更新 |
| **BIMパイプライン** | Revitからエクスポート → 数量を抽出 → DDCレートとマッチング → 5Dレポート生成 |
| **Slackボット** | チームが質問 → AIがデータベースを検索 → 関連項目を返送 |

---

### 🤖 Dify — LLMアプリケーション構築

DDC CWICRをナレッジベースとしてカスタムAIアプリケーションを作成。

**セットアップ：**
1. 新しいDifyアプリケーションを作成
2. ナレッジベースを追加 → Parquet/CSVファイルをアップロードまたはQdrantに接続
3. エンベディング付きRAGパイプラインを設定
4. チャットインターフェースまたはAPIを構築

**アプリケーションアイデア：**

| アプリタイプ | 説明 |
|--------------|------|
| **建設見積チャットボット** | コスト照会のための会話型インターフェース |
| **工事項目検索** | 55,000以上の項目を自然言語で検索 |
| **コストアドバイザー** | コスト内訳を説明し最適化を提案するAI |
| **多言語アシスタント** | 言語を自動検出しユーザーの言語で応答 |
| **APIエンドポイント** | 他システムとの統合用REST API |

---

### 🔮 Sim AIおよび類似プラットフォーム

DDC CWICRは以下をサポートするあらゆるAIプラットフォームと統合可能：
- **ベクトルデータベース**（Qdrant、Pinecone、Weaviate、Milvus）
- **構造化データ**（CSV、Parquet、Excel）
- **OpenAIエンベディング**（text-embedding-3-large、3072次元）

**互換性のあるプラットフォーム：**
- **Sim AI** — AIシミュレーションとモデリング
- **LangChain / LlamaIndex** — LLMアプリケーションフレームワーク
- **Flowise** — ローコードLLMアプリビルダー
- **Botpress** — 会話型AIプラットフォーム
- **Voiceflow** — 音声とチャットのデザイン
- **Stack AI** — ノーコードAIワークフロー
- **Relevance AI** — AIワークフォースプラットフォーム

---

### 📋 ユニバーサルユースケース

どのAIツールを選んでも、DDC CWICRは以下を可能にします：

| ユースケース | 説明 |
|--------------|------|
| **即座のコスト見積** | テキスト説明や写真から建設コストを取得 |
| **BOQ生成** | プロジェクト説明から数量明細書を自動生成 |
| **価格ベンチマーキング** | 地域や言語間でコストを比較 |
| **リソース計画** | 労働時間、材料、機器ニーズを計算 |
| **投資分析** | 完全なリソース透明性による詳細なコスト監査 |
| **多言語サポート** | 9言語でローカライズされた価格でユーザーにサービス |
| **BIM統合** | Revit/IFCに接続して自動4D/5D見積 |
| **AIモデルトレーニング** | 構造化データを使用した建設AIのファインチューニング |

---

## 概要

**DDC CWICR**（Construction Work Items, Components & Resources）は、土工事やコンクリート打設から専門的な設備工事まで、建設活動の全範囲をカバーする建設コスト見積のためのオープンデータベースです。

このデータベースは、統一された技術標準化エコシステムが10以上の急成長経済圏の共通エンジニアリング言語として機能するユーラシアおよびアジア太平洋地域の近代的な建設慣行を記述するソースに基づいています。

### 利用可能なフォーマット

| フォーマット | 拡張子 | サイズ | 最適な用途 | 特徴 |
|--------------|--------|--------|------------|------|
| **Excel** | `.xlsx` | ~150–400 MB | 手動分析、フィルタリング、ピボット | 人間が読める、完全なフォーマット |
| **Parquet** | `.parquet` | ~55 MB | ETLパイプライン、MLトレーニング、ビッグデータ | 列指向、優れた圧縮 |
| **CSV** | `.csv` | ~1.3 GB | データベースインポート、レガシーシステム | 普遍的な互換性 |
| **Qdrant** | `.snapshot` | ~1 GB | セマンティック検索、RAG、AIアシスタント | 事前計算済みOpenAIエンベディング |

---

## クイックスタート

### Python - 表形式データ

```python
import pandas as pd

# Parquet（推奨）
df = pd.read_parquet("DDC_CWICR_EN.parquet")

# Excel
df = pd.read_excel("DDC_CWICR_EN.xlsx")

print(f"レコード数: {len(df):,} | フィールド数: {len(df.columns)}")
```

### Python - セマンティック検索

```python
from qdrant_client import QdrantClient
from openai import OpenAI

client = QdrantClient("localhost", port=6333)
openai = OpenAI()

# 自然言語で検索
query = "鉄筋コンクリート基礎の打設"
embedding = openai.embeddings.create(
    input=query,
    model="text-embedding-3-large"
).data[0].embedding

results = client.search(
    collection_name="ddc_cwicr_en",
    query_vector=embedding,
    limit=5
)

for r in results:
    print(f"[{r.score:.3f}] {r.payload['rate_code']}: {r.payload['rate_original_name']}")
```

---

## 🌍 対応言語と価格レベル

| コード | 言語 | 価格レベル | 通貨 | Qdrantコレクション |
|--------|------|------------|------|-------------------|
| `AR` | アラビア語 | ドバイ | AED | `ddc_cwicr_ar` |
| `DE` | ドイツ語 | ベルリン | EUR | `ddc_cwicr_de` |
| `EN` | 英語 | トロント | CAD | `ddc_cwicr_en` |
| `ES` | スペイン語 | バルセロナ | EUR | `ddc_cwicr_es` |
| `FR` | フランス語 | パリ | EUR | `ddc_cwicr_fr` |
| `HI` | ヒンディー語 | ムンバイ | INR | `ddc_cwicr_hi` |
| `PT` | ポルトガル語 | サンパウロ | BRL | `ddc_cwicr_pt` |
| `RU` | ロシア語 | サンクトペテルブルク | RUB | `ddc_cwicr_ru` |
| `ZH` | 中国語 | 上海 | CNY | `ddc_cwicr_zh` |

---

## リソースとコミュニティ

[![ウェブサイト](https://img.shields.io/badge/🌐_ウェブサイト-datadrivenconstruction.io-2563eb?style=for-the-badge)](https://datadrivenconstruction.io)
[![デモ](https://img.shields.io/badge/🎯_デモ-openconstructionestimate.com-059669?style=for-the-badge)](https://openconstructionestimate.com)
[![GitHub](https://img.shields.io/badge/💻_GitHub-datadrivenconstruction-181717?style=for-the-badge&logo=github)](https://github.com/datadrivenconstruction)
[![YouTube](https://img.shields.io/badge/📺_YouTube-@datadrivenconstruction-FF0000?style=for-the-badge&logo=youtube)](https://youtube.com/@datadrivenconstruction)
[![Telegram](https://img.shields.io/badge/💬_Telegram-datadrivenconstruction-26A5E4?style=for-the-badge&logo=telegram)](https://t.me/datadrivenconstruction)

---

## ライセンス

**データベース**（DDC CWICR）— [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)。商用利用、共有、改変自由。帰属表示："DDC CWICR by DataDrivenConstruction"

**コード**（ワークフロー、スクリプト）— [MIT](https://opensource.org/licenses/MIT)。制限なく自由に使用、修正、配布可能。

---

<p align="center">
  <b>📖 完全なドキュメントは<a href="README.md">英語README</a>をご覧ください</b>
</p>

<p align="left">
  <sub>© 2025 Artem Boiko · <a href="https://datadrivenconstruction.io">datadrivenconstruction.io</a></sub>
</p>
