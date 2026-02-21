# 職務経歴書

## 職務要約

大学院(情報理工学)修了後、ITエンジニアとして主にデータ基盤・ETLパイプライン・データ分析の領域に従事してきました。主な内容としては、Python/Hadoop/Sparkを用いたデータ集計・処理、BigQuery/Redshift/Athena等のSQLを用いたデータ集計、Airflowを用いたETLワークフロー構築等の経験があります。役割は基本的に実装・テスト・保守運用です。

## 強み

- AWS Glue（PySpark/Pandas）を用いた大規模 ETL ジョブの設計・実装・パフォーマンスチューニング
- Athena/Redshift/S3 を活用したデータレイク・DWH の構築と運用
- QuickSight を用いた BI ダッシュボード構築およびデータソース最適化
- Python/SQL を用いたデータ加工、データ品質担保、分析用データマート整備
- ライブラリ・ランタイムのバージョンアップやリンター導入など技術的負債の解消

## スキルサマリー

特に実務で利用頻度が高い技術: **Python / SQL / Airflow / PySpark / Athena / Redshift / BigQuery / Glue / QuickSight**

| 区分 | 技術 |
|---|---|
| 言語 | Python, SQL, Ruby, Java, JavaScript, Shell Script, C |
| フレームワーク/ミドルウェア | PySpark, Pandas, Polars, Airflow, Hadoop, Hive, Presto, Ruby on Rails |
| DB / DWH | Redshift, BigQuery, Athena, PostgreSQL, MySQL |
| クラウド（AWS） | Glue, S3, Athena, Redshift, QuickSight, SageMaker, Step Functions, EMR, Lambda, DynamoDB, ECS, ECR, IAM, EC2, API Gateway, CloudFormation, CloudWatch, CodeCommit, CodePipeline, Data Pipeline, Systems Manager |
| クラウド（GCP） | BigQuery |
| ツール | Docker, Git, GitHub Actions, SQLFluff, Tableau, Redash, GAS |

## 主な職務経歴

### PySpark/SQLを用いたデータ処理の開発・運用・改善およびBI構築（2022年8月〜2026年2月）

- プロジェクト概要: 在庫データ分析基盤チームにて、在庫・販売分析機能のデータ処理開発、ETL/データマート整備、BIダッシュボード改善を担当
- 担当業務:
  - Glue（PySpark/Pandas）/Athena/Redshift/Aurora（PostgreSQL）/S3 を用いた ETL・集計処理の実装と運用
  - PySpark/Pandas/Polars/Athena 処理の性能チューニング
  - Glue バージョンアップ（2.0/3.0 → 4.0 → 5.0）、Python バージョンアップ（3.7 → 3.10 → 3.11）対応
  - QuickSight を用いた BI ダッシュボードの新規構築・改修、SPICE/Direct Query の使い分けとクエリパフォーマンス改善
- 使用技術:
  - 言語: Python, SQL（Athena, Redshift, PostgreSQL）
  - フレームワーク/ミドルウェア: Spark（PySpark）, Pandas, Polars
  - AWS: Glue, S3, Athena, Redshift, Aurora (PostgreSQL), QuickSight, SageMaker, Step Functions, Lambda
  - ツール: Cursor, Docker, Git, GitHub Actions, Redash

### データ基盤の運用・保守（2022年4月〜2022年7月）

- プロジェクト概要: 大手OA機器メーカーのデータ基盤チームにて、データ基盤の運用・保守を担当
- 担当業務:
  - CloudFormation を用いた開発環境の構築
  - Glue クローラの仕様調査、および S3 データの自動テーブル化の仕組み実装
  - データ基盤利用者（各事業部）向け環境の構築・提供
- 使用技術:
  - 言語: Ruby, Python, SQL（Athena）, Shell Script
  - フレームワーク: Ruby on Rails（rake）
  - AWS: Glue, Athena, S3, CloudFormation, CloudWatch

### Airflow等を用いたETLパイプラインの構築・運用（2020年4月〜2022年3月）

- プロジェクト概要: 大手放送局子会社のデータ活用チームにて、ETLパイプラインの構築・運用を担当
- 担当業務:
  - Airflow 上で Redshift/Glue/S3/DynamoDB を組み合わせた ETL ワークフローを実装
  - Glue でスキーマ登録した S3 データを Redshift Spectrum で集計・変換し、Redshift（データマート）へロード
  - AWS Data Pipeline, EMR（Spark）を用いた ETL バッチ実装
  - Python によるデータクレンジング・構造化処理
  - Docker を用いたローカル開発環境（Jupyter Notebook, Hadoop）構築
  - CodePipeline/GitHub Actions を用いた CI/CD 構築
- 使用技術:
  - 言語: Python, SQL（Redshift, Athena, Presto）, Shell Script
  - フレームワーク/ミドルウェア: Airflow, Spark, Presto
  - AWS: Redshift, Athena, Glue, S3, EMR, Lambda, ECS, CodeCommit, CodePipeline, Data Pipeline
  - ツール: Docker, Git, GitHub Actions, Redash

### BigQuery等を用いたデータ分析（2019年10月〜2020年3月）

- プロジェクト概要: 国内最大級のネット予約サービスを運営している企業のデータ分析チームにて、BigQueryを中心としたデータ抽出・集計・データマート作成を担当
- 担当業務:
  - サイト利用状況・予約状況など KPI モニタリング用データマート作成
  - Adobe Analytics / Google Analytics データを用いた PV モニタリング用データマート作成
  - DWH データのアドホック抽出
  - Redshift から BigQuery への移行に伴う SQL 書き換え
  - GAS と BigQuery を用いたデータマートの自動定期更新・Slack配信実装
  - Tableau での可視化ビュー作成
- 使用技術:
  - 言語: SQL（BigQuery, Redshift）, JavaScript, Shell Script
  - AWS: Redshift
  - GCP: BigQuery
  - ツール: Tableau, GAS, Git

### Ruby on Railsアプリの保守運用（2019年5月〜2019年9月）

- プロジェクト概要: Ruby on Rails で実装されたインフラ監視システムの保守・運用を担当
- 担当業務:
  - 障害報告を受けた際の原因調査、改修、テスト、本番適用まで一連で対応
- 使用技術:
  - 言語: Ruby, SQL（MySQL）
  - DB: MySQL
  - フレームワーク: Ruby on Rails

### 画像認識AIモデル開発（2018年9月〜2019年3月）

- プロジェクト概要: メガバンク向け AI 開発チームにて、開発支援および学習データ作成を担当
- 担当業務:
  - AIモデル学習用データの作成・加工（アノテーション/オーグメンテーション）
  - Python ライブラリを用いた推論精度評価（Precision/Recall算出）
  - 案件推進サポート、設計書などのプロジェクト文書作成
  - AIモデル運用ルール策定
- 使用技術:
  - 言語: Python, Shell Script

### Hadoopを用いたデータ処理およびビッグデータ基盤EOS対応（2017年7月〜2018年2月）

- プロジェクト概要: 上記と同一組織にて、データ処理バッチ開発およびオンプレミス基盤のEOS対応に伴う AWS 移行 PoC を担当
- 担当業務:
  - Webログと顧客データの紐付けなど、データ加工バッチ実装
  - 移行先フレームワークに合わせた分析ジョブ修正
  - 移行先インスタンス選定のための性能検証
  - Lambda を用いた自動ジョブ連携の実現性検証
  - Lambda 多重起動問題を検知し、対応策を策定・実装
- 使用技術:
  - 言語: Java, Shell Script, Python
  - フレームワーク/ミドルウェア: Hadoop, AsakusaFW, Hive
  - AWS: EMR, Lambda, DynamoDB

## 学歴

- 東京工業大学大学院 情報理工学研究科 計算工学専攻 修了
- 東京工業大学 工学部 情報工学科 卒業

## 取得資格

| 取得時期 | 資格名 |
|---|---|
| 2025年7月 | TOEIC L&R 755点 |
| 2022年4月 | OSS-DB Exam Silver |
| 2022年2月 | 統計検定2級 |
| 2020年12月 | AWS認定データアナリティクス |
| 2018年12月 | AWS認定ソリューションアーキテクト アソシエイト |
| 2018年10月 | LPIC レベル1（LinuC レベル1） |
| 2017年12月 | 応用情報技術者 |
| 2015年5月 | 基本情報技術者 |

## その他

- 業務使用ツール: Slack, GitHub, Redmine, Jira/Confluence, Backlog, Microsoft Office, Google Workspace
- GitHub: [https://github.com/kosei-s](https://github.com/kosei-s)
