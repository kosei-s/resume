# 職務経歴書

## 概要

大学院(情報系)を卒業して以来5年間ほど、エンジニアとして主にデータ分析・ETL・基盤周辺の業務に携わってきました。主な内容としては、EMR/Hadoop/Sparkを用いたデータ処理処理、Pythonを用いたデータ加工・集計、BigQuery/Redshiftを用いたデータ集計、Airflowを用いたETLワークフロー構築等の経験があります。役割は基本的に設計・実装・テストです。

## 職務経歴

### Airflow等を用いたETLパイプラインの構築・運用 (2020年4月〜2022年3月)

【概要】<br>
　大手放送局子会社様のデータ活用チームにおいて、Airflow等を用いたETLパイプラインの構築を担当

【業務内容】 以下のような業務において設計から実装、テストまでを担当
- Airflow上においてRedshiftやGlue, S3, DynamoDB等を用いたETLワークフローを実装
  - 主なETL内容としては、GlueにS3データのスキーマを登録し、Redshift Spectrumで集計・変換し、Redshift(データマート)へロード。(ロード処理の非同期制御にDynamoDBを利用)
- AWS Data Pipeline, EMR(Spark)を用いたETLバッチの実装
- Pythonでのrawデータのクレンジングや構造化等の加工処理
- Dockerを用いたローカル開発環境(Jupyter NotebookやHadoop)の構築
- AWS CodePipelineやGitHub Actionsを用いたCI/CDの構築

【使用技術】<br>
　(言語) Python3, SQL(Redshift, Athena, Presto), shell script<br>
　(FW) Airflow, Spark, Presto<br>
　(AWS) Redshift, Athena, Glue, S3, EMR, Lambda, ECS, CodeCommit, CodePipeline, Data Pipeline<br>
　(ツール) Docker, Git, GitHub Actions, Redash

### BigQuery等を用いたデータ分析 （2019年10月〜2020年3月）

【概要】<br>
　国内最大級のネット予約サービスを運営している企業様のデータ分析チームにおいて、BigQueryを主に用いたデータ抽出・集計やデータマート作成を担当

【業務内容】 以下のような業務において設計から実装、テストまでを担当
- サイト利用状況や予約状況といったKPIをモニタリングするデータマート作成
- AdobeアナリティクスやGoogleアナリティクスのデータを用いたPVモニタリングのデータマート作成
- DWH上のデータへのアドホックなデータ抽出
- RedshiftからBigQueryへの移行に伴うSQL書き換え
- GASとBigQueryを用いたデータマートの自動定期更新/Slack配信の実装
- Tableauでのビューの作成

【使用技術】<br>
　(言語) SQL(BigQuery, Redshift), JavaScript, shell script <br>
　(AWS) Redshift<br>
　(GCP) BigQuery<br>
　(ツール) Tableau, GAS, Git

### 画像認識AIモデル開発案件 （2018年9月〜2019年3月）

【概要】<br>
　メガバンクのAI開発チームにおいて、案件推進サポートやAIモデルの学習データの作成等を担当

【業務内容】
- AIモデル学習用のデータ作成・加工（アノテーション/オーグメンテーション）
- Pythonライブラリを用いたAIモデル推論精度の評価(Precision, Recall算出)
- 案件推進サポート
- 設計書等のプロジェクト文書作成
- AIモデル運用ルール策定

【使用技術】<br>
　(言語) Python2, shell script

### Hadoopを用いたデータ処理及びビッグデータ基盤EOS案件 （2017年7月〜2018年2月）

【概要】<br>
　同上の組織において、データ処理バッチ開発や、EOSを迎えたオンプレミスのビッグデータ分析基盤をAWS上に構築・移行するプロジェクトにおけるPoCを担当

【業務内容】
- Webログと顧客データの紐付けといったデータ加工処理バッチの実装
- 基盤EOSにおいて、以下のようなフィージビリティ検証や性能検証等のPoCを実施。
  - 基盤移行に伴い、分析ジョブの実行フレームワークも変更となったため、変更後フレームワークに合わせた形にジョブ内容を修正
  - AWS上で利用するサーバー(インスタンス)選定のための性能検証
  - AWS Lambdaを利用した自動ジョブ連携のフィージビリティ検証
  - AWS Lambdaの多重起動問題を発見し、対応策を策定・実装

【使用技術】<br>
　(言語) Java, shell script, Python3<br>
　(FW) Hadoop, AsakusaFW, Hive<br>
　(AWS) EMR, Lambda, DynamoDB

### Ruby on Rails アプリの保守運用 （2019年5月〜2019年9月）

【概要】 Ruby on Railsで実装されたインフラ監視システムの保守・運用を担当。

【業務内容】 トラブル発生の報告を受け、原因箇所を特定、開発環境上で改修、テスト、本番適用までを実施。

【使用技術】<br>
　(言語) Ruby, SQL(MySQL)<br>
　(DB) MySQL<br>
　(FW) Ruby on Rails

## スキル

### 言語

**Python3** | Ruby | **Java** | JavaScript | **shell script** | **C**

### フレームワーク

Hadoop | Spark | Hive | Presto | Ruby on Rails

### DB / DWH

MySQL | PostgreSQL | **Redshift** | **BigQuery**

### クラウド

#### AWS

EC2 | **Lambda** | **S3** | DynamoDB | API Gateway | **CodeCommit** | CodePipeline(Build, Deploy) | CloudWatch | CloudFormation | Systems Manager | **Athena** | **Redshift** | **EMR** | **Data Pipeline** | **Glue** | IAM | ECR | ECS

#### GCP

**BigQuery**

### その他

**Docker** | **Airflow** | **Git** | **GitHub Actions** | GAS | Tableau | Redash

## 学歴

- 東京工業大学大学院 情報理工学研究科 計算工学専攻 修了
  - 並列処理アルゴリズムに関する研究: http://id.nii.ac.jp/1001/00178818/
- 東京工業大学 工学部 情報工学科 卒業

## 取得資格

- 2020年12月  AWS認定データアナリティクス
- 2018年12月  AWS認定ソリューションアーキテクト アソシエイト
- 2018年10月  LPIC レベル1 (LinuC レベル1)
- 2018年6月  AWS認定クラウドプラクティショナー
- 2017年12月  応用情報技術者
- 2015年5月  基本情報技術者

## その他

- 業務使用経験ツール： Slack | GitHub | Redmine | Jira/Confluence | Backlog | Microsoft Office | Google Workspace
- GitHubアカウント: https://github.com/kosei-s
- Qiitaアカウント: https://qiita.com/kosei-s
- Kaggleアカウント: https://www.kaggle.com/koseis
