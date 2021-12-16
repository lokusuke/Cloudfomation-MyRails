# Cloudfomation-MyRails
①　MyRailsVPC.yml：VPC、サブネット、IGW、ルートテーブルを作成しています。
②　MyRailsSG.yml：EC2、RDS、ELB用のセキュリティグループを作成しています。
③　MyRailsEC2.yml：Railsアプリを含んだAMIを利用して2台構築する内容になってます。SSMパラメータをReadしたいのでIAMロール、インスタンスプロファイルも一緒に作成しました。
④　MyRailsRDS.yml：RDSの作成をしています。
⑤　MyRailsELB.yml：上記で作成したEC2をターゲットグループに入れられるようにしています。
⑥　MyRails.drawio：上記スタックでで構築するAWS環境の構成図です。