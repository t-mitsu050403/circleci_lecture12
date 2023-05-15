# circleci
circleciの動作testを行うためのリポジトリです。  
「cloudformation」ディレクトリ配下にcloudformaton用のyamlファイルを配置し（拡張子は「.yaml」のみ）、  
git pushを行うと、cfn-lintがテンプレートの構文チェックをしてくれます。  

※circleciとgithubの事前連携が必要です。  
