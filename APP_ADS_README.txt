AdMobアカウント作成後にやること:

1. AdMobコンソールに表示される app-ads.txt の1行をコピーする
   (例: google.com, pub-XXXXXXXXXXXXXXXX, DIRECT, f08c47fec0942fa0)
2. このフォルダ直下に「app-ads.txt」という名前のファイルを作り、その1行を貼り付ける
3. GitHubリポジトリ(ryyttc5-commits.github.io)で「Add file > Create new file」→
   ファイル名に app-ads.txt と入力 → その1行を貼り付け → Commit
   → https://ryyttc5-commits.github.io/app-ads.txt で見えればOK
4. Play Consoleの「ストアの設定 > ストアの掲載情報 > ウェブサイト」に
   https://ryyttc5-commits.github.io を設定していることを確認
   (AdMobはこのウェブサイトのapp-ads.txtを自動クロールする。反映まで最大24時間)
