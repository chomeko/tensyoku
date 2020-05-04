***
# 転職用にまとめる
***

# ブラッシュアップ事項

>何をしたいより、何をもたらすことができそうかっていうところを言いたいです。
未経験だから具体的なことは言えないけれど、ベースラインにそこがあるといいな。

>ITに行きたい理由については
2点
1つは工場勤務について。
金銭のことはリアルだけど、
将来性がないってことをメインに据えるとよいかなと。

>ITの魅力についても、なにかもう1つ言えるといいな。
できれば働き方というよりは、社会に対するインパクト的な。

>で、ちょめちゃんの「インハウスとは違う」ってのは、たぶん悪印象を与えてしまうかなと思うのね。

>それよりも、
ただの静的ページじゃなくて、動くシステムが作れますっていうのは強みだと思うのよ。
いまは経験ないけど、独学でここまで勉強したっていうのは強みです。

>コーディングっていう言葉も、人によって曖昧になりやすいワードなので
「cssのコーディングだけでなく
VueやReactを使って1つ簡単ではありますが
Webサービスを実際に作り…」

>「また、不慣れながら、サーバー管理もしました。
具体的には」とかね。

>会社によると思うけど、いまスクールとか訓練学校あがりの未経験者からの募集が多いと思うので
そいつらと比較して、独学でここまでやったっていうのは大いなる強みの1つだとは思う

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
>言語はrailsで作っています。
>progateで勉強後にすぐ作成した初めてのアプリで、現職の仕事で使うために作った計算機になります。
>工場でプラスチック製品を機械で作っていて、その生産が終わる時間を計算できるようにしています。
>終わる時間を把握できるため次の段取りへの準備が余裕を持って行えます。
- PGMG
>言語はrailsで作っています。
>Railsチュートリアルをした後に作ったブログサイトになります。Boostrapを使ってコーディングをして、Rails6からあるactiontextを使ってブログ機能を作成し、桜のVPSにcapistrano(カピストラーノ)を使ったデプロイをしています。
- デイトラ
>cssコーディング力を上げるために30daysトライアルに挑戦しました。ここで初めてgulpやpugとsassを使ったコーディングをはじめました。この頃からフロントエンドエンジニアになりたいと思うようになりました。
- Bell
>reactに興味を持ったのでprogateと書籍で勉強後にtwitter企画にあった１週間で何かを作って投稿するという企画に挑戦しました。一人一回まで押せるいいねボタンを作成して投稿しました。react-redux(リダックス)とfirebaseを使ってカウントはforebaseのデーターベースに保存しています。

## 目指す会社
- web制作会社
- 受託または自社
- モダンな環境
- フロントエンドエンジニア
- コーダー

## 何になりたいか
フロントエンジニアとして、CSSによるコーディングだけではなく、動きのあるサイトでvueやreactを使っていきたいです。

## なぜITに行きたいと思ったか

>工場勤務で昇給もあまりなくボーナスもない状態なので、このままそこにいても将来が不安でした。
今回のコロナでも、工場は会社が休業することになっている中、ITの人たちは自宅でリモートで仕事ができたり、そーいう部分でも工場ではこの先ダメだなと感じました。
他には独学だけで悩みながら作品を作り、それを世に公開した時の達成感や周りからの反響がすごく嬉しくて、作るのは難しいけれどその分作り切った時の感動や満足感がとても気持ちがいいと感じ、それで手に職を持ちたいと思うようになりました。
独学でも諦めずに最後まで作品を作り上げれる自走力はあるので、新しい技術などもどんどん吸収していけます。

# りんごさんのインタビューメモ

## ◯いま取り組んでいること

- ポートフォリオの作成
り）
  やってみて、どうですか？
  結構難しかったと思ったりもするところもあるだろうし、でもまわりからは高評価だよね！
  その辺について、今思ってることを教えてください。
ち）
  ポートフォリオを作成するにあたって難しいと感じたのは、デザインのことでした。
  最初デザインは自分のセンスで作ると思っていたけどそうじゃなく、デザインにはちゃんとルールがあって
  デザインの意味があることを知りました。
  まだデザインのことは詳しくありませんが、その辺のことが少し勉強になり今後の制作物等にも活きていくなと思いました。
  技術面の方では、jsの勉強がまだあまり深くはできてないので今回勉強として便利なライブラリは使わずに、
  Jqueryだけでググりながらすべて実装しました。
  とくに気に入っているのはサイト訪問時の僕がバイクで爆走する部分です。
  周りからの評価ですが、やっぱり苦労して作った分素直に嬉しいです。


>ポートフォリオに載ってるそれぞれの作品について、それぞれ説明してもらえると嬉しいかも！
そもそもどういう目的で、どういう人に見て／使ってほしくて作ったのかとか、工夫した点、苦労した点とか、使った技術スタックとか。
ポートフォリオを作り上げたら、ついに転職活動だけど、今のコロナで難しい局面もあり、結構つらいところもあると思うんだけど、
ちょめちゃんはポジティブに進めてるのがすごいと思ってます！　そのへんも含め、いまの気持ちとか思ってることとか教えてください！
このインタビューも転職活動にプラスになればいいなと思うので、ぜひぜひアピールしちゃってください。

## ポートフォリオに載ってるそれぞれの作品

- Calculator

ち）
> 言語はrailsで作っています。
  プログラミング勉強1か月後にはじめて作成してみたアプリで、現職の仕事で使うために作った計算機です。
  工場でプラスチック製品を機械で作っていて、その生産が終わる時間を計算できるようにしています。
  苦労した点は、これがはじめての作品で何もかも苦労しました。
  正直コードはぐっちゃぐちゃだと思います。
  でもあえてそのままのコードで残して、成長した時に比較して楽しもうと思っています。


- PGMG

ち）
> 言語はrailsで作っています。
  プログラミング勉強を始めて約3か月後に作成したブログサイトです。
  Boostrapを使ったコーディングをして、Rails6からあるactiontextを使ってブログ機能を作成しました。
　さくらのVPSにcapistrano（カピストラーノ）を使ったデプロイをしています。
  自分の勉強記録を残そうと思って作ったのですが、予想以上に色々ハマって1番悩んだ制作物です。
  この作品の後からもっと動きのあるサイトを自由に作りたいと思うようになり、railsを離れました。

- デイトラ2nd

ち）
> CSSコーディング力を上げるために挑戦したのがデイトラです。
  ここではじめてGulpを使った自動化やpugやsassを使いました。
  またemmetも覚えたのがここからでした。
  Gulpではブラウザの更新、pugとsassのコンパイルを自動化しています。
  JSと画像の圧縮もgulpでやっています。
  デイトラを通して色んなことを学べたので本当にやってよかったと思っています。

- Bell

ち）
> reactをやりたくなったのでprogateと書籍で勉強して作った作品で、1人1回押せるいいねボタンです。
  twitterの企画で1週間チャレンジという企画があったので参加して作りました。
  1週間でデザインやら何やら考えて作って投稿するので時間に追われながら作りました。
  はじめてfirebaseのデーターベースを使ったりデプロイしてすごく勉強になりました。
  お題がHOMEだった為、無理やり家のベルってことで呼び出しボタンにしてます。

## ◯勉強をはじめたきっかけと背景

ち）
> 工場勤務で昇給もあまりなくボーナスもない会社で、このままそこにいてもずっと将来今と何も変わらないなと思ってた時に、去年小学校でプログラミ    ングの授業がはじまると聞き、そこで自分もやってみようかなと思ったのがきっかけです。
  毎日独学で勉強して、今まで目標が何も持てなかったけどプログラミングで手に職をつけたいという目標が持てるようになりました。
  今回のコロナでも、工場は会社が休業することになっている中、ITの人たちは自宅でリモートの仕事ができたり、そーいう部分でも工場ではこの先ダメだなと感じました。

## ◯にゅ～ぶる会への参加

り）
> ちょめちゃんがにゅ～ぶる会に参加したのって、どの時点だっけ？
  誰に声掛けして／誘ってもらってですか？
  入ってみての第一印象どうでした


ち）
> 独学でずっとやってる中わからない事を誰にも聞けない状態が続いたり悩んでる時に
  Twitterで会長のにゅ〜ぶるさんの呟きをたまたま発見して、思い切ってDMして参加させていただきました。
  初めはこんな初心者なんかでも大丈夫なんだろうかって不安でしたが、入ってみて皆さんの分報を見たりしてると、
  案外同じような所で悩んでる方も多く、同じ悩みを共有できたり一緒に悩んだりする事ですごく心強く感じて
  モチベーションがすごく保てるようになりました。


り）
> あの頃は最初PGMG作ってた頃だったっけ。
  そのときのエピソードとかあればｗ


ち）
> herokuにしかデプロイしたことがなくて、PGMGではじめてVPSにデプロイしたんですが、こんなにエラー出るのってくらいエラー祭りで
  めっちゃ心折れました。
  これ一生デプロイできんわって思ってたけれど、にゅーぶる会長へ相談したりめっちゃググってなんとかデプロイすることができました。
  これ以来VPSは恐くてデプロイの選択肢には入れてません。

## ◯にゅ～ぶる会の好きなとこ！

り）
> そして、にゅ～ぶる会のいいところとかをアピールしてもらおうと思いますｗ
  まぁ嘘を言ってもしょうがないので、ちょめちゃんの思ういいところ、（もしあれば悪いところもｗ）教えてください。


ち）
> にゅ〜ぶる会の良いところはやっぱ個人の分報が作れることだと思います。
  そこで勉強で詰まった時だけじゃなく、勉強以外でも色んなことを呟いていける。
  もちろん主に勉強のことについてですが、それ以外でも気軽に言えるのでそこがモチベーションの管理に
  繋がるのかなと思います。
  困った時には助言をくれたり時には励ましてくれたり、いつも感謝しています。
  そして最近から始まった毎週開催するオンラインもくもく会。
  これがすごく勉強になる。毎週参加してますがいつも勉強になる会で本当にありがたいですね。
  とくにりんごさんに関しては毎週MCってか進行してくれて感謝しかありません！
  これからもお願いしますw


## ◯今後の目標

り）
> 最後に、ちょめちゃんの目標について教えてください。
  まぁ短期的には就職かな。
  長期的にこういうエンジニアになって、世の人にこういう価値を届けたいとかあれば。
  あともちろん年収1,000万！とか報酬的なところもいいと思いますし、
  働き方の点もいいですね。
  正直ベースな話とちょっと壮大な話で長期的な目標を語ってもらればー。


ち）
> 目標は転職です。
  今コロナの時期で転職はかなり厳しいと思いますが、コロナだからって立ち止まって
  ズルズル転職せずに引っ張るわけにはいかないので、5月末には色々準備して活動しようと思っています。
  フロントエンジニアとして働いていき、お客様が求める物をしっかり作っていき、満足してもらえるように
  技術面をどんどん鍛えて、僕がこれを作ったんだよって胸張って言えるよなエンジニアになりたいと思います。
  年収としては今は共働きなので、それを一人でまかなえるほどの年収目指して仕事を頑張ります。
  またコロナでもリモートで仕事をさせていただけるような会社に出会いたいです。
  今は休業があったりで収入が減ったいるので。
  現状を変えるため31歳になりますが、ここで人生を変えて残り30年か40年ほどをエンジニアとして生きて生きたいです！
