# 職務経歴書

## 概要

大学院(情報系)を卒業して以来4年間ほど、主にデータ分析・ETL周辺の業務に携わってきました。主な業務内容としては、Hadoop/EMRを用いた分散並列処理、Pythonを用いたデータ加工・集計、BigQuery/Redshiftを用いたデータ集計、Airflowを用いたETLワークフロー構築等の経験があります。役割は基本的に設計・実装・テストです。

## スキル

実務経験のあるもののみの記載です。

### 言語

Python | Ruby | Java | Bash | TTL

### フレームワーク

Hadoop | AsakusaFW | Ruby on Rails

### DB / DWH

MySQL | PostgreSQL | Oracle | Redshift | BigQuery | Hive

### クラウド

#### AWS

Athena | EMR | Redshift | Glue | EC2 | Lambda | ECS | ECR | Connect | DynamoDB | CodeCommit | CodeBuild | CodeDeploy | CodePipeline | CloudWatch | CloudFormation | PHD | SSM | IAM | S3 | EBS

#### GCP

BigQuery | GCS

### その他

Docker | Airflow | Git | GitHub Actions | GAS | Tableau | Redash

## 職務経歴

### Airflowを用いたETLパイプラインの構築・運用<br>【Airflow/Docker/Python/Redshift/Glue/DynamoDB】(2020年4月〜2021年3月)

【概要】 映像メディア系のデータ活用チームにおいて、Airflowを用いたETLパイプラインの構築を担当

【業務内容】
  - Airflow上においてRedshiftやGlue, S3, DynamoDB等を用いたETLワークフローを実装
  - 主なETL内容としては、GlueにS3データのスキーマを登録し、Redshift Spectrumで集計・変換し、Redshiftへロード。(ロード処理の非同期制御にDynamoDBを利用)
  - Airflow環境の整備(puckel/docker-airflowの拡張)

### BigQuery等を用いたデータ分析<br>【BigQuery/GAS/Tableau】（2019年10月〜2020年3月）

【概要】 国内最大級のネット予約サービスを運営している企業様のデータ分析チームにおいて、BigQueryを主に用いたデータ抽出・集計やデータマート作成を担当。

【業務内容】 以下のような業務において設計から実装、テストまでを担当。
  - サイト利用状況や予約状況といったKPIをモニタリングするデータマート作成
  - AdobeアナリティクスやGoogleアナリティクスのデータを用いたPVモニタリングのデータマート作成
  - DWH上のデータへのアドホックなデータ抽出
  - RedshiftからBigQueryへの移行に伴うSQL書き換え
  - GASとBigQueryを用いたデータマートの自動定期更新/Slack配信の実装
  - Tableauでのビューの作成

### 画像認識AIモデル開発案件<br>【Python/Bash】（2018年9月〜2019年3月）

【概要】メガバンクのAI開発チームにおいて、案件推進サポートやAIモデルの学習データの作成等を担当。

【業務内容】
  - AIモデル学習用のデータ作成・加工（アノテーション）
  - Pythonライブラリを用いたAIモデル推論結果のPrecision, Recall算出
  - 案件推進サポート
  - 設計書等のプロジェクト文書作成
  - AIモデル運用ルール策定

### ビッグデータ分析基盤EOS対応<br>【Bash/Python/Java/Hadoop/EMR/Lambda/DynamoDB】（2017年10月〜2018年2月）

【概要】同上のチームにおいて、EOSを迎えたオンプレミスのビッグデータ分析基盤をAWS上に構築・移行するプロジェクトにおけるPoCを担当。

【業務内容】以下のようなフィージビリティ検証や性能検証等のPoCを担当。
  - 基盤移行に伴い、分析ジョブの実行フレームワークも変更となったため、変更後フレームワークに合わせた形にジョブ内容を修正
  - AWS上で利用するサーバー(インスタンス)選定のための性能検証
  - AWS Lambdaを利用した自動ジョブ連携のフィージビリティ検証
  - AWS Lambdaの多重起動問題を発見し、対応策を策定・実装。

### Hadoopを用いたデータ処理<br>【Java/Hadoop/AsakusaFW/Hive】（2017年7月〜2017年9月）

【概要】同上のチームにおいて、Webログと顧客データの紐付けバッチ開発における設計から実装、テストまでを担当。

【業務内容】
  - データ処理フローをフローチャートにより設計
  - Hadoopのフレームワークを用いた実装
  - フレームワークの機能を用いて単体テストと結合テストを実施

### Ruby on Rails アプリの保守運用<br>【Ruby on Rails/MySQL】（2019年5月〜2019年9月）

【概要】Ruby on Railsで実装されたインフラ監視システムの保守・運用を担当。

【業務内容】トラブル発生の報告を受け、原因箇所を特定、開発環境上で改修、テスト、本番適用までを実施。

### その他（細かいもの等）

- AWSのデータ分析サービス比較調査 【EMR/Redshift/Athena/PostgreSQL】（2018年3月〜2018年5月）
  - 【概要】ビッグデータ分析チームにおいて、オンプレミスの分析DBをクラウドに移行する際の事前調査として、AWSのデータ分析サービスであるAmazon EMR, Amazon Redshift, Amazon Athenaそれぞれの特徴、差異の調査を担当。
- 定期作業の自動化 【Bash/MySQL/TTL(TeraTermマクロ)】（2019年5月〜2019年9月）
  - 【概要】システム稼働情報レポーティング作業等の自動化を担当。

## 取得資格

- 2020年12月  AWS認定データアナリティクス
- 2018年12月  AWS認定ソリューションアーキテクト アソシエイト
- 2018年10月  LPIC レベル1
- 2018年9月  LinuC レベル1
- 2018年6月  AWS認定クラウドプラクティショナー
- 2017年12月  応用情報技術者
- 2015年5月  基本情報技術者

## その他

- 業務使用ツール：Slack | GitHub | Redmine | Jira/Confluence | Office | Gsuite
- GitHubアカウント: https://github.com/kosei-s
- Kaggleアカウント: https://www.kaggle.com/koseis
