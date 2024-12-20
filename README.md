# Verses  
  
 ## ■ サービス概要  
写真を音楽と一緒に投稿するアプリです。  
今の気持ちを視覚と聴覚で共有できるアプリです。  
  
 ## ■ このサービスへの思い・作りたい理由  
  
「この景色はあの人と一緒に眺めてたな、」  
「そう言えばあの人はあの曲をずっと聞いてたな」とセンチメンタルになる時。  
  
出先で突然好きな曲が流れてきた時のワクワク感、  
「今日はいいことが起こりそう、」とポジティブになる時。  
  
人のそういう感性に興味を持っています。  
歌うのも歌を聴くのも大好きです。  
文字も大事ですが、写真の方がより伝わりやすいと思います。  
手間暇をかけて完成した作品も、ふとした瞬間を写真にした景色も、  
その時の感情はきっとその人が知っている曲と繋がっています。  
  
SNSで直接に話しかけるのも、むやみにコメント返すのも嫌われるかもしれないです。  
文字で伝えてもキリがない時もあるのでコメントではなく、  
絵文字だけでそっと共感してくれたらいいなと思います。  
  
 ## ■ ユーザー層について  
音楽と写真に興味がある10~30代の方。  
音楽活動や写真関係の仕事をされて、自分の作品を共有したい方。  
SNSを利用されているが、あまり投稿しないシャイな方。  
  
 ## ■ サービスの利用イメージ  
・ユーザーが写真をアップロードしてタイトルを入力し、曲を選択して投稿します。  
・投稿を見た他のユーザーは、写真とともに曲を聴くことができます。  
・シンプルで直感的なデザインで、他のユーザーの投稿を閲覧でき、気に入った投稿には絵文字を付けられます。  
  
 ## ■ ユーザーの獲得について  
Xでの発信を通じて、ユーザーの皆様がXでシェアしていただくことでアプリを宣伝します。  
  
 ## ■ サービスの差別化ポイント・推しポイント  
・ユーザーはコメントを書くプレッシャーから解放され、絵文字で簡単に反応できる。  
・感情や反応を視覚的に伝える。  
  
 ## ■ 機能候補  
現状作ろうと思っている機能、案段階の機能をしっかりと固まっていなくても構わないのでMVPリリース時に作っていたいもの、  
本リリースまでに作っていたいものをそれぞれ分けて教えてください。  
  
■ 機能の実装方針予定  	

|  | 技術 |
|:-----------:|:------------:|
|Frontend|JavaScript, Tailwindcss, HTML, CSS|
|Backend|Ruby 3.3.5, Rails 7.2.1|
|Infrastructure|fly.io, Upstash|
|Database|PostgreSQL|
|CI/CL|GitHubActions|
|Web API|SpotifyAPI, GoogleAPI|  
<br>

## ■ MVPリリース時  
- 会員登録機能
- ログイン機能  
  - SNSログイン(GoogleAPI)  
- ログアウト機能
- 投稿一覧機能
- 新規投稿機能
  - 音楽検索機能(SpotifyAPI)
  - 絵文字機能
  - タグ機能
- 投稿編集・削除機能
- 投稿詳細
- いいね機能
- マイページ
- 会員情報変更ページ
- マイポスト機能
- パスワードリセット機能  
  
## ■ 本リリース時  
- SNSシェアする機能  
- 投稿検索機能  
- オートコンプリート検索  
- プライバシーポリシー・利用規約　　
- お問い合わせ　　
- OGP（静的）　　
- 独自ドメイン　　
- レスポンシブ対応  　
- Rspec

<br>

## 画面遷移図  
[Figma](https://www.figma.com/design/TzTv7FDIYN7R1reTDoCX4H/%E7%94%BB%E9%9D%A2%E9%81%B7%E7%A7%BB%E5%9B%B3?node-id=0-1&node-type=canvas&t=EQ6WUfPjyejrGv1y-0)
  
<br>

## ER図
<img src="https://i.gyazo.com/fc8a6cb0de9673c9a4523370260c9a7e.png" alt="ER図">  

