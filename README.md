# kadai4; LINE風アプリ

①課題内容（どんな作品か）
LINE風の画面は講義とほぼ変わっていないのですが，ベタにFirebaseの認証機能を使用しました。

②工夫した点・こだわった点
firebaseUIを使用したのと，Emulatorを使ってみたかったので動かしてみました。
※Hostingせず，Firebase Authの接続先がエミュレータ指定になっておりますのでご注意ください。
使用しているのはAUTHのみなので，firebase initでemulatorを使えるようにしたあと
  firebase emulators:start --only auth
で良いです。

③質問・疑問（あれば）

④その他（感想、シェアしたいことなんでも）
Firebaseは移り変わりが激しいようで，v8時代のlearning systemを学んだあとにv9仕様の公式ドキュメントを見て面食らいました。
最初はモジュールを格納する新しい方法で行っておりましたが，うまくいかないこともあったので直前でCDNで対応しました（ごちゃごちゃしていてすみません）。



