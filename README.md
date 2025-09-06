冷蔵庫管理アプリ (Refrigerator Management App)
![alt text](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![alt text](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![alt text](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![alt text](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
1. 概要
本プロジェクトは、日々の食材管理を効率化するためのWebアプリケーションです。
IT業界へのキャリアチェンジを目指す自身のポートフォリオとして、企画から設計、開発、インフラ構築までを一貫して手掛けています。
早期就職という目標のため、迅速なプロダクト完遂ために、UIの初期モックアップ作成に画像生成AIを活用しました。
このモックアップを元に、UI修正とコンポーネントの機能実装をReact/JavaScriptを使って実装することで、
デザイン案の検討にかかる時間を大幅に短縮し、本来注力すべきフロントエンドの実装作業に多くの時間を割くことができました。

また本機能の全体像とユーザーフローを明確にするため、
画面遷移図を生成しました。これにより、プロジェクトの仕様を第三者にも分かりやすく可視化し、ドキュメントとして整備しました。

アプリケーションURL
現在、フロントエンドのホーム画面UIのみを先行して公開しています。
URL: https://refrigerator-management-front-publi.vercel.app/
※ 現時点ではログアウトによる、画面遷移機能は動作しておりません。

3. 制作背景
毎日料理をする中で、「外出先から冷蔵庫の中身を確認したい」「食材の賞味期限を忘れて無駄にしてしまう」といった課題を感じていました。
既存のサービスも参考にしつつ、「自分が本当に欲しいと思う、シンプルで直感的な管理ツールを作りたい」という思いから、本アプリケーションの開発をスタートしました。

5. 主な機能（予定）
ユーザー登録・ログイン機能
食材の登録・一覧表示・編集・削除 (CRUD): モックデータ実装済み
カテゴリ別での食材絞り込み機能: 実装済み

7. 使用技術（予定）
フロントエンド: React / JavaScript
バックエンド: Java (Spring Boot)
データベース: PostgreSQL / MySQL (検討中)
インフラ: AWS (EC2, RDS, S3等を予定)
CI/CD: GitHub Actions (予定)

9. 現在の開発状況と今後の展望
✅ フェーズ1：フロントエンドUIの実装
ホーム画面のUIデザインとコンポーネント作成が完了し、Vercelにて公開済みです。
🚧 フェーズ2：バックエンド・認証機能の実装
現在、ユーザー登録とログイン機能の実装に着手しています。
🚀 フェーズ3：コア機能開発とインフラ構築
認証機能の実装後、バックエンドをJava(Spring Boot)で構築し、データベースと連携させます。
最終的にはAWS上にインフラを構築し、実際に利用可能なWebアプリケーションとして完成させることを目指しています
