# Secure I/O Unit Project
このプロジェクトは既存の入出力装置のセキュリティ上の問題点を克服したセキュアな入出力装置の開発を目指すと共に新しい処理装置と入出力装置の関係を模索するオープンソースハードウェアとそのコミュニティです。  
  
/\*何かいい感じのgif\*/  
![I-O_Unit_overview.jpg](https://github.com/Takana-Norimasa/Secure_I-O_Unit_Project/blob/master/images/I-O_Unit_overview.jpg)

ここでは、僕の考えた入出力それぞれの装置をまとめた新しいデバイスを紹介すると共に、作り方を公開し様々な人に実際に個人の好みにあった入力方式やパターンを持ったオリジナルの装置を作っていただこうと考えています。  

# 製作したデバイスの概要
このリポジトリで公開しているデバイスの概要について説明します。  
このデバイスは既存の入力装置（キーボードなど）と出力装置（ディスプレイ）を一つの単位にまとめた装置です。僕はこの単位をI/O Unitと呼ぶことにしました。  
I/O Unitの利点は既存の入出力装置を処理装置から独立させることで自由度を高め、デバイスの可能性を広げることができることや、さまざまなデバイスで同じ入出力装置を使えること、セキュアなI/O Unitを開発することでより広くのデバイスにショルダーハッキング対策などのセキュリティ対策をすることが可能なことなどが挙げられます。

## できること
/\*何かいい感じのgif\*/  
このリポジトリで公開しているデバイスの特徴は

# 構成
/\*構成図\*/  


# 作り方
さぁここまでくればあなたもこのデバイスが欲しくなったでしょう！  
[wiki](https://github.com/Takana-Norimasa/Secure_I-O_Unit/wiki)に作り方やカスタマイズの例を挙げています！  
このデモを見て自分も作ってみたい！と思った方はぜひwikiを見て挑戦して楽しんでください！   
wiki:[https://github.com/Takana-Norimasa/Secure_I-O_Unit/wiki](https://github.com/Takana-Norimasa/Secure_I-O_Unit/wiki) 

# このプロジェクトへの参加方法
このプロジェクトの基本方針は100人が一つのハードウェアについて開発を進めることより100人が各自100個の自作のデバイスを持ち寄り見せあうことで議論を進めることに重きを置きたいと考えています。  
理由としては回路やプログラム以外にも工作やアイデアの要素が強く、それらを共有して議論するにはできたものを見せあうことが一番だからです。
なので自作のI/O Unitを作ってTwitter等で#Secure_i-O_Unit のハッシュタグをつけて呟くだけでこのプロジェクトに大きく貢献していると言えます。  
もちろんソフトウェアや回路の面で改善の余地がある部分はこのリポジトリで議論しあい改善していきましょう。  
wikiについても誰でも編集できるように環境を整える予定です。  

# 作者
高名 典雅(Takana Norimasa)  
Mail    : j17423@kisarazu.kosen-ac.jp(official) or seigenkousya@outlook.jp   
github	: [Takana-Norimasa](https://github.com/Takana-Norimasa)  
Twitter	: [@seigenkousya_](https://twitter.com/Seigenkousya_)  
Qiita   : [@Seigenkousya](https://qiita.com/Seigenkousya)

# 経緯
最後になってしまいましたが何故僕がこの装置を作ってプロジェクトを立ち上げたのかを書いておきます。  
  
僕は日頃から既存の入出力装置のセキュリティに疑問を持っていました。  
ディスプレイは覗き見するだけでそこから簡単に情報を盗み出すことができてしまいます。  
キーボードは机などにおいて使うので入力しているところを動画に撮ってどこのキーを叩いてるのかを解析することで何を入力しているのかが簡単に分かってしまいます。  
これらの攻撃は専門的な知識が要らず準備も必要としないので誰でもできます。しかも攻撃対象は世界中のPCやスマホです。  
  
僕はこの状況を危惧しました。そしてショルダーハッキングや画面の覗き見に対策を施した新しい入出力装置の形(=I/O Unit)を考えると共にこのデバイスの開発とプロジェクトの立ち上げを決めました。  
入力装置では自由な姿勢での入力を実現することでカメラでの記録を防ぐと共に指の動きを最小限にとどめることで情報の窃取を最大限防ぐ工夫をしました。  
出力装置でも既存のプライバシーフィルタの弱点であった真後ろを克服するために画面と利用者の目の距離を縮めることで第三者の視線の介入を防ぎ、さらに自由な姿勢での入力を支援することも可能になりました。  
  
結果的にこのデバイスはセキュアであることだけで無く、処理装置から完全独立することでどのデバイスでも同じ入出力装置を使え、自由な姿勢での使用ができ、ポータブルなPC環境を構築できるなどさまざまな利点を獲得するに至りました。  
そして、作り方を公開することで様々な人にデバイスを作ってもらい、人それぞれの入力機構のカスタマイズをしてもらうことで更にショルダーハッキング耐性をつけると共に既存のqwertyキーボードとディスプレイ（またはスマホ）とは違った新しい可能性を模索する段階に入りました。  
皆さんが作ったものの中から新しい次世代の入出力機構が生まれるかもしれません。  

僕は将来的にI/O Unit+様々な処理装置という新しいデバイスの形がやってくることを予見しています。  
このプロジェクトによってたくさんの人がものづくりを楽しんでくれると共に次世代のデバイスの形を模索する場になることを期待しています。  
