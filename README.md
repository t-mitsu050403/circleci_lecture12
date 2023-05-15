# circleci
circleciの動作testを行うためのリポジトリです。  
cloudformationディレクトリ配下にcloudformatonのyamlファイルを配置し（拡張子は「.yaml」のみ）、  
git add、git commit、git pushを行うと、cfn-lintがチェックしてくれます。  

※circleciとgithubの事前連携が必要です。  