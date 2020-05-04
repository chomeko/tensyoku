***
# 転職用にまとめる
***

## ポートフォリオ解説

### 日数
>制作日数はデザインとブラッシュアップ含め24日ほどで作成しました。

### 環境構築
>タスクランナーでgulpを使用し、pugとsassを使ってコーディングしています。デプロイ先はよく使うnetlify(ネットリファイ)を活用しています。

### こだわった部分
>pugでcode量を減らすためにmixinやfor文を使ったり、jsでは便利なライブラリは使わずに勉強のためググりながらjqueryのみで実装しました。サイト訪問時のバイクで横切るアニメーションが1番のお気に入りです。

### jsの説明
#### jsはまだあまり勉強不足なため、ググりながらの実装をしています。

- サイト訪問時のバイク横切り
>cssにてtransformプロパティでX軸をマイナスにしtransition（トランジション）で3秒かけて、jsでX軸をプラスにし、3秒後にフェードアウトさせてます。
- タイトルのアニメーション
>テキストを１文字ずつ区切って配列にして、eachで配列の数だけspanタグをつけてopcity0を指定しています。
そしてindex番号にミリ秒をかけて順番にh1要素に追加していき、3秒かけてopcityを１にしています。
- 吹き出しのコメント
>settimeoutで3秒後にアニメーション開始し、配列を作りfor文で配列の数だけ消したりフェードINさせています。それを各コメント3秒で繰り返しています。
- モーダル
>クリックした位置を取得し、クリックでモーダルをフェードインさせて、閉じる時にクリックした位置まで戻すようにフェードアウトさせています。念の為モーダル展開時はbodyをスクロールさせないようにCSSにてoverflow: hidden（オーヴァーフロウ　ヒドゥン）クラスを作っています。
- toggleボタンの切り替え
>toggleをクリックしたらCSSにて作ったactiveクラスをつけて、トグルの形を変えています。activeクラスが付いていたら、cssにて作ったnavにopenクラスをつけてtransformにてX軸をマイナスの状態からプラスに変えてnavを出現させています。
- ハンバーガーのメニュークリック
>クリックしたエイチエフ属性の値を取得して、その値の位置を取得しアニメーションさせて移動させています。
- 各セクションのフェードIN
>cssにてfadeinクラスを用意してopacityを０にします。各セクションにそのクラスをつけといて、jsにて各セクションに付いてるfadainクラスの位置を取得して、その位置より下に２００pxスクロールした時にopcityを１にして出現させています。

### スキル説明

- html
>デザインカンプや模写サイトを見ながら自分で考えてマークアップしていけます。
- pug
>より簡潔にコードを書くためにpugを主に使ってコーディングしています。
- sass
>変数で使いまわしたり、ネストで記述量が減らせるので主に使っています。
- gulp
>pugとsassのコンパイルとブラウザ更新で普段から使用しています。画像やjsの圧縮もしています。
- boostrap
>railsチュートリアルで学び、ブログサイトを作成するときに使いました。レスポンシブやグリッドシステムが簡単にできます。
- rails
>progateで学んだ後にrailsチュートリアルをやり、書籍で勉強し、その後にブログサイトなどを作ったりしました。
- react
>progateで学び、その後に書籍を書い勉強して、twitter企画（１週間）で１つ作品を作りました。
- js
>ググりながらjquery（ジェイクエリー）などで簡単なアニメーションしたりできます。
- vscode
>普段使っているエディタはvscode（ブイエスコード）です
- GitHub
>普段からgithubでリポジトリを作成し、vscodeからコミット、pushをして管理しています。ターミナル上で、コミットやプッシュ、ブランチなどを作ったりできます。
- xd
>ブログサイトやポートフォリオを作る前にワイヤーフレームとデザインをXDで作りました。
- slack
>twitter経由でコミュニティーに入り、自分の分報を作って進歩報告や疑問点などを質問しています。また毎週discodeでオンラインもくもく会を開催しているので参加して色んな技術を勉強させていただいてます。
### study
>プログラミング勉強を初めて、今まで自分が何をしてきたかを簡単にまとめています。
### contact
>netlifyのメールフォームを使っています。
### その他制作物各種

- Calculator
>progateで勉強後にすぐ作成した初めてのアプリで、現職の仕事で使うために作った計算機になります。
>工場でプラスチック製品を機械で作っていて、その生産が終わる時間を計算できるようにしています。
>終わる時間を把握できるため次の段取りへの準備が余裕を持って行えます。railsで作っています。
- PGMG
>Railsチュートリアルをした後に作ったブログサイトになります。Boostrapを使ってコーディングをして、Rails6からあるactiontextを使ってブログ機能を作成し、
>桜のVPSにcapistrano(カピストラーノ)を使ったデプロイをしています。
- デイトラ
>コーディング力を上げるために30daysトライアルに挑戦しました。ここで初めてgulpやpugとsassを使ったコーディングをはじめました。この頃からフロントエンドエンジニアになりたいと思うようになりました。
- Bell
>reactに興味を持ったのでprogateと書籍で勉強後にtwitter企画にあった１週間で何かを作って投稿するという企画に挑戦しました。一人一回まで押せるいいねボタンを作成して投稿しました。react-redux(リダックス)とfirebaseを使ってカウントはforebaseのデーターベースに保存しています。

## 目指す会社
- web制作会社
- 受託または自社
- モダンな環境
- フロントエンドエンジニア
- コーダー

## 何になりたいか
>フロントエンドエンジニアとして働きたい
>サーバーサイドよりコーディングなどのフロント側の方が楽しいなて感じた
>できればモダンな環境でvueやgulpを使ってコーディングしていきたい
***
>インハウスは自分の求めてるところとは違う気がする
インハウスはもっと広くて、SEOやったり、競合分析やったり、広告やったり、コーディング（vue,react含む）やったり、デザインやったり、開発やったり、サーバー管理やったり。

## なぜITに行きたいと思ったか
>工場勤務で昇給もあまりなくボーナスもない会社で、このままそこにいてもずっと今と何も変わらないなと思ってた時に、去年に小学校でプログラミングの授業がはじまると聞き、そこで自分もやってみようかなと思ったのがきっかけです。
毎日プラグラミング勉強をすることでもっと自分でできるようになりたいと思うようになり、今まで目標が持てなかったけどプログラミングで手に職をつけたいという目標が持てるようになりました。今回のコロナでも、工場は会社が休業することになっている中、ITの人たちは自宅でリモートで仕事ができたり、そーいう部分でも工場ではこの先ダメだなと感じました。
仕事をしながら日々スキルを高めていって、もっともっとできることを増やして、自信をもってプログラミングして会社に貢献していけたらなと思っています！