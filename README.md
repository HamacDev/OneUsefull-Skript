# One-Skript

※下に重要な説明があります

![tgdeg](https://user-images.githubusercontent.com/81562786/115990668-700bd800-a5ff-11eb-9366-573a855d36ce.png)

------
ベータ版です。バグの報告はメール(https://HamacDev.github.io に記載してあります)にお願いします。
------


- 注意！いじるところがあります。ちゃんと下まで見てね。


一部＆参考(というかちょっといじっただけ) : https://qiita.com/meoto2408/items/938a1035998ca80ee59e

- 使い方

/serveropen <text> または /svo <text>
  
<text>の所に
  
"c"でホワリスオフ "o"でホワリスオンです。

/noblock <text>
  
<text>の所に
  
ブロックを設置・壊せなくするワールド名を入れてください。

/dev でクレジット

/os <text> で <text> に "dev" でクレジット "by" で作者 "github" で私のGitHubとこのレポジトリ
  
------------------

- (いじるとこ)特定の場所へtpコマンド1つ目(GUI式)

.skファイルの最初らへんに、tpコマンドがあるので、tpする先(ロビーとか)を入力してください。これでセーブしましょう。

コマンドは /menu です。


- 特定の場所へtpコマンド2つ目(非推奨)(Beta)(バグあるかも？)

動作確認はしていません。権限の要求がされるかもなので管理者専用かも？改善します。

/lobbyset <x> <y> <z> <向き1個目> <向き2個目>
  
で特定の場所の座標を設定できます。

/lobbyでtpします。

- 一応いじるやつ

.skファイルの、最初が「command /hider <text>:」となっているやつがあります。そこに、
  
send "&e%player% joined game" to player  

っていうやつと

send "&e%player% left the game" to player

これを自分のサーバーのログに合わせてください。

例えばプレイヤー名が「Ohayou」だとすると

Ohayou joined game とか Ohayou left the game とか自分のサーバーのやつに合わせてください。

これでOKです。


-------------------



-



-


バグ報告について

メール：https://HamacDev.github.io に記載してあります。

私がMinecraftのSkriptを作ったやつを配布しよ〜ってやつです。

※Skriptをマジで何も勉強せずQiitaの記事を1つ見ただけで作ったやつです。

Bye.

-------------
コマンドの一部にsiso_az様のsiso packを改変したものを使わせてもらっています。ありがとうございます。
