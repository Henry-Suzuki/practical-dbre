# エンジニアリング文化比較分析

## 概要

本ドキュメントでは、各社のエンジニアリング文化とプラクティスを比較分析します。

## エンジニアリング文化の特徴比較

### エンジニアリング文化の特徴

| 企業 | エンジニアリング文化の特徴 | 公式情報 |
|------|-------------------------|----------|
| Google | 心理的安全性、20%ルール（歴史的）、多様性と包括性 | ⚠️ 限定的（20%ルールは歴史的） |
| Microsoft | 成長マインドセット、オープンソースへの貢献、クラウド技術の活用 | ⚠️ 限定的 |
| Amazon | Leadership Principles（14の原則）、Two-Pizza Team | ✅ 公式情報あり（Leadership Principlesは公式公開） |
| Netflix | Freedom & Responsibility、Talent Density、Keeper Test | ✅ 公式情報あり（Culture Memo） |
| Spotify | Squad/Tribe/Chapter/Guild文化、アジャイル開発 | ⚠️ 限定的 |
| CircleCI | オープンな文化（エンジニアリングラダーを公開）、リモートファースト | ⚠️ 限定的 |

### 公式情報が詳細に公開されている文化

#### Amazon - Leadership Principles

- **公式情報から確認できること**: 
  - AmazonのLeadership Principlesは、公式に公開されている（[Amazon Leadership Principles](https://www.amazon.jobs/principles)）
  - 14の原則が公式に公開されている：
    1. Customer Obsession（顧客に執着する）
    2. Ownership（オーナーシップを持つ）
    3. Invent and Simplify（発明し、簡素化する）
    4. Are Right, A Lot（多くの場合、正しい判断をする）
    5. Learn and Be Curious（学び、好奇心を持つ）
    6. Hire and Develop the Best（最高の人材を採用し、育成する）
    7. Insist on the Highest Standards（最高の基準を堅持する）
    8. Think Big（大きく考える）
    9. Bias for Action（行動への偏見）
    10. Frugality（倹約）
    11. Earn Trust（信頼を獲得する）
    12. Dive Deep（深く潜る）
    13. Have Backbone; Disagree and Commit（背骨を持ち、反対し、コミットする）
    14. Deliver Results（結果を出す）
  - Leadership Principlesは、すべての意思決定と行動の指針となるとされている

#### Netflix - Freedom & Responsibility

- **公式情報から確認できること**: 
  - Netflixの組織文化の核心となる概念として、公式Culture Memoで言及されている
  - Freedom & Responsibility（自由と責任）が組織文化の核心
  - Talent Density（才能密度）を高めることを重視
  - Context, Not Control（コントロールではなくコンテキスト）を採用

#### Spotify - Squad/Tribe/Chapter/Guildモデル

- **公式情報から確認できること**: 
  - Spotifyの組織文化は、Squad/Tribe/Chapter/Guildモデルに基づいて構築されていると、公式Engineering Blogで言及されている

### 公式情報が限定的な文化

#### Google - 20%ルール

- **公式情報から確認できること**: 
  - Googleの20%ルールは、従業員が勤務時間の20%を通常業務以外のプロジェクトに充てることを奨励する制度として知られている
  - Gmail、Google News、AdSenseなどの革新的なサービスがこの制度から生まれた
  - 2013年頃に変化し、プロジェクトの承認が必要になった
  - 2020年代には、AI技術の進化に伴い、個々のエンジニアが自由にプロジェクトに取り組む余地が減少している
  - 20%ルールは静かに姿を消しつつあると指摘されている

#### Microsoft - 成長マインドセット

- **公式情報から確認できること**: 
  - Microsoftは成長マインドセットを重視している
  - オープンソースへの貢献を積極的に行っている
  - Azureなどのクラウド技術を積極的に活用している

#### CircleCI - オープンな文化

- **公式情報から確認できること**: 
  - CircleCIはエンジニアリングラダーをGoogle Spreadsheetで公開している
  - Creative Commons Attribution 4.0 International (CC BY 4.0) ライセンスで公開されている
  - リモートファーストの文化を持っているとされている

## プラクティスの特徴比較

### コードレビュー

| 企業 | コードレビューの実施 | 公式情報 |
|------|-------------------|----------|
| Google | **公式情報なし** | ❌ |
| Microsoft | **公式情報なし** | ❌ |
| Amazon | **公式情報なし** | ❌ |
| Netflix | **公式情報なし** | ❌ |
| Spotify | **公式情報なし** | ❌ |
| CircleCI | **公式情報なし** | ❌ |

### テスト戦略

| 企業 | テスト戦略の詳細 | 公式情報 |
|------|----------------|----------|
| Google | **公式情報なし** | ❌ |
| Microsoft | **公式情報なし** | ❌ |
| Amazon | **公式情報なし** | ❌ |
| Netflix | **公式情報なし** | ❌ |
| Spotify | **公式情報なし** | ❌ |
| CircleCI | **公式情報なし** | ❌ |

### CI/CD

| 企業 | CI/CDの実施 | 公式情報 |
|------|------------|----------|
| Google | **公式情報なし** | ❌ |
| Microsoft | **公式情報なし** | ❌ |
| Amazon | CI/CDを実施しているとされている | ⚠️ 限定的 |
| Netflix | Chaos Engineeringを推進しているとされている | ✅ 公式情報あり（Tech Blog） |
| Spotify | CI/CDを実施しているとされている | ⚠️ 限定的 |
| CircleCI | CI/CDプラットフォームを提供している（自社の製品） | ✅ 公式情報あり |

## 主要な発見

### 1. エンジニアリング文化の公式情報の公開状況

- **詳細に公開**: Amazon（Leadership Principles）、Netflix（Freedom & Responsibility）
- **限定的に公開**: Google、Microsoft、Spotify、CircleCI
- **公式情報なし**: プラクティス（コードレビュー、テスト戦略、CI/CD）の詳細は、ほとんどの企業が公開していない

### 2. エンジニアリング文化の特徴

- **Amazon**: Leadership Principlesという明確な文化原則を公式公開
- **Netflix**: Freedom & Responsibilityという独自の文化を公式公開（Culture Memo）
- **Spotify**: Squad/Tribe/Chapter/Guildモデルという独自の組織構造を公式公開
- **Google**: 20%ルールは歴史的な制度として知られているが、現在は制限されている

### 3. プラクティスの公式情報の公開状況

- **詳細に公開**: Netflix（Chaos Engineering）、CircleCI（CI/CDプラットフォーム）
- **限定的に公開**: Amazon、Spotify
- **公式情報なし**: コードレビュー、テスト戦略の詳細は、すべての企業が公開していない

### 4. 比較分析の限界

- 公式情報が限定的なため、詳細な比較分析は困難
- 各社のプラクティスの詳細は、公式に公開されていない場合が多い

## 更新日
2025年10月18日

