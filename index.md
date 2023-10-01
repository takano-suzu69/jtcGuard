# 始めに

このリポジトリは技術同人誌「JTC向けAWSガードレール」のための公開リポジトリになります。

# コンテンツ

## サンプルコード

AWS公開Cloudformation サンプルテンプレート等をカスタマイズして作っております。

- 3.5 Cloudtrail

EnableAWSCloudtrail_Gurad.yml　です。
AWS公開テンプレートのS3バケットに、ライフサイクルルール、コメントで1つめのリージョンと次のリージョンに対してのParameter設定の記載を追加しています。

- 3.7 AWS Config

EnableAWSConfig_Guard.yaml です。Config保管バケットにライフサイクルルール、コメントで1つめのリージョンと次のリージョンに対してのParameter設定の記載を追加しています。
※2023/8/13 にナレッジを確認していたところ、「ExclusionByResourceTypes」が確認できました。Records の見直しをしていいかもしれません（後に更新しておきます）
※※ 10.1 UPしました。

- 3.8 GuradDuty

EnableGuardDuty.yaml です。非機能要件はケースによって違うため、ここではSNS、Lambdaのサンプルは掲載しておりませんのでご了承ください。

- 3.9 SecurityHub

EnableSecurityHub.yaml です。非機能要件はケースによって違うため、通知設定は入れておりません。

## 正誤表

準備中

## 更新サマリ

2023/8/13 1.0
2023/10/1 1.1 EnableAWSConfig_Guard.yaml の RecorderRecordingStrategy対応版UP

# 連絡先

Twitter(X)@takano0131、または本書公開のメールアドレス経由でお願いいたします。
