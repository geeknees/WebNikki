---
title: RubyKaigi 2023 に参加してきた
description: >-
  長野県松本市で開催されたRubyKaigiに参加してきた。先月はEthGlobal Tokyo
  のハッカソンにて3日ほど家を空け（おかげでLensProtocolからTop10の賞をいただきました）、GW…
pubDate: '2023-05-14T11:50:17.187Z'
categories: []
keywords: []
---

長野県松本市で開催されたRubyKaigiに参加してきた。先月はEthGlobal Tokyo のハッカソンにて3日ほど家を空け（おかげでLensProtocolからTop10の賞をいただきました）、GW は家庭内で子供がウィルスと抗生物質とのアレルギー反応のようなものを起こし、雪崩れ込むような流れの中で松本に向かうことになった。とはいえ、普段からスケジュールが重なることは常であり、単純に優先度の問題である。心理的には純粋な高揚感を持ちながら、車中ではラップトップを開きながら駅弁を食べる。

RubyKaigi は所属しているキャタルという会社にとって重要なイベントであり、チケット代、期間中の滞在費、交通費は会社として完全にサポートしている。来年は沖縄開催ということで、同様のサポートをするか（できるか）悩ましいところではあるが、まずは予算感を計算してみようと思っている。大きな会社ではないので、採用枠も常にあるわけではなく、そうした背景からスポンサーなどは検討できないが、参加者としての参加はバックアップしたいと考えている。普段フルリモートで働くメンバーにとって普段の喧騒から離れて、エンジニアとしての理想を語り合う貴重な場所であり、長期的なマインドセットをアップデートできる機会でもある。なかなか、定量化できないが投資と考えても充分すぎるリターンが得られる。このようなイベントは本当に貴重である。

こうした事を考えていると、CfP を出すか悩んでいた塩井さんに対してチーフオーガナイザーである松田さんが、このような奇跡的な場所がいつまでも続くとは考えずに、今登壇したいと思うのであれば悩まず出すべき的なことを話されていたというブロク記事を思い出す。このような奇跡的なコミュニティに魅せられた一員として、また会社の意思決定に少しだけ影響を与えることができる立場として、僕は僕の立場で、後悔がないように最も良い判断をし行動をしたい。

[**RubyKaigi Takeout 2021に登壇しました - shioimm || coe401\_**
_しおいです。 9/9-9/11に開催された RubyKaigi Takeout 2021 DAY1にて登壇しました。 RubyKaigiはわたしにとって憧れのテックカンファレンスであり、 Ruby…_coe401.hatenablog.com](https://coe401.hatenablog.com/entry/2021/09/18/174221 "https://coe401.hatenablog.com/entry/2021/09/18/174221")[](https://coe401.hatenablog.com/entry/2021/09/18/174221)

そういう流れの中で、今回のカンファレンスでは大倉さんのLTがとても印象に残った。会社で技術顧問をお願いしているという繋がりがあるのも大きいのかもしれない。が、内容の面白さ、実用もさることながら、大倉さんの全ての熱意があの5分に詰め込まれていたきがしていたく感動した。このことが、後述するリチャード・リンクレイター監督の『6才のボクが、大人になるまで。（原題 BoyHood )』のことを思い出させた。

会議の前日に入り、松本市民美術館に向かった。目当ては草間彌生の常設展。2020年に松本市での開催が決まった時から来たいと思っていた。草間彌生の作品はアイコニックなドット柄のかぼちゃを思い浮かべる人が多いかもしれないが、実は絵画からインスタレーションから小説や詩といった文章まで多岐にわたる。なぜか、それは、彼女の、その時々の、刹那的に自分が生きた証を残す闘いだったのだとのだと思う。初期から現在まで時系列で並ばられた展示を通じてみることでそのことを、強烈に感じた。

2020年に松本開催を予定したところ、新型コロナウイルスの大流行によってオンライン開催を余儀なくされた。2021年も同様にオンライン開催をし、2022年には晴れて三重県での開催となった。 Ruby 3x3のキャッチフレーズの元で3倍速を目指したRuby3.0 （25 Dec 2020にリリース）ということもあり、三重県での開催を優先する必要があったのだと思う。三重県ではコロナ禍で明けのはじめの開催ということもあり公式にパーティー等の開催はなかった。今年は Official Partyも復活し、海外からの登壇者も多く訪れて、本格的に以前と同様の規模に戻った印象だった。さらに言うとオンライン開催の知見を活かして、ハイブリッド開催となっておりパワーアップしての開催となった。（なお、ハイブリッド開催は家庭や他の職務遂行との調整において非常にありがたい形式で、とても感謝している。）

その上で、来年はなんと沖縄で開催するとのことだ。運営の方々の尽力には頭が上がらない。その都度都度でできる最大限のことをする、そのことを非常に学ばせてもらっている。

かつての職場の同僚であった塩井さんは、上記のブログにもあった初登壇から3年連続の登壇となり、非常に風格があった発表だった。満員で立ち見状態の中、非常に難解なParserについて、非常にわかりやすい解説を展開していたと思う。その発表から僕が受け取ったことは、遠い雲の上のような存在に見えることでも一歩一歩進めていくことはできる、少なくとも私はこうして来ている、あなたもどうですか、と言っているように感じた。懇親会のとき、ビギナーだった頃の塩井さんを知る存在として、どうしたら塩井さんのようになれますかと聞かれることが数回あった。僕から語れることは殆どないが、せめてと思って当時の様子をコメントした。思い返せば、そのコメントは失敗だったかもしれない。本人に直接聞いてみて、もしその機会がなければ登壇発表をもう一回見てみるといいと思う、多分その解答が発表にあると思う（と僕は感じた）と答えればよかった気がする。

Rizap さんが企画してくれた、Drink UpでMatzと直接お話させて頂くことができた。きっかけは、たまたま同じイベントに参加していた大倉さんがせっかくならMatzと同じ席に座りましょう、と声をかけていただいたからだ。大変ありがたい。Rubyについてお客さん以上の気持ちを持っている人ではあるのでRubyistを名乗らせてもらってはいるものの、職責上、プロダクトマネジメントを行う必要があり、プログラマーとしては中途半端な存在である。そのため、RubyKaigi に参加する際には少し引け目を感じているので、後押しがなければ話す機会がなかったと思う。Matz は自分が発表したRuby のビジョンの話は直接的には皆さんの生産性に影響がなく、福利厚生的なものだと仰っていたが、個人的にはそんなことはなく、むしろMatzがどの様に人々にビジョンを語り、人を動かしていくかということを直接的に学ばせてもらっていると思っている。 Matz is nice so we are niceなことが直接的な価値であり、niceな人たちこそがRubyKaigiの中心にあるように思う。

【余談：Matz に機会があったら話したいと思っていたこともここで話せてよかった。LLM が勃興する中、LangChain（Python）が重要なポジションを取る可能性が高いと思っており、このRuby版をということを考えてみたかったのだった。話したあと、ホテルで調べていたら、すでにRuby版があったので、また時間をとって調査したいと思っている】

[**GitHub - andreibondarev/langchainrb: Build ML/AI-supercharged applications with Ruby's LangChain**
_⚡ Building applications with LLMs through composability ⚡ 👨‍💻 👩‍💻 CURRENTLY SEEKING PEOPLE TO FORM THE CORE GROUP…_github.com](https://github.com/andreibondarev/langchainrb "https://github.com/andreibondarev/langchainrb")[](https://github.com/andreibondarev/langchainrb)

『6才のボクが、大人になるまで。（原題 BoyHood )』 の中の象徴的な台詞を抜き出してみる。

[**Nicole**](http://m.imdb.com/name/nm3878243)**:** You know how everyone’s always saying seize the moment? I don’t know, I’m kinda thinking it’s the other way around. You know, like **the moment seizes us.**

[**Mason**](http://m.imdb.com/name/nm1294664)**:** Yeah. Yeah, I know. It’s constant — -the moment. It’s just… It’s like it’s always right now, you know?

_（ChatGPT和訳）_

_ニコル：「みんながいつも『今をつかむんだ』って言うじゃない？でもさ、逆じゃないかなって思うんだよ。なんか、瞬間が私たちをつかんでるって感じるんだよね。_

_メイソン：うん、そうだね。わかるよ。その瞬間って、ずっと続いてるんだよね。いつでも今、って感じなんだよね？」_

![](/web-nikki/img/medium/1__Ls4ctdN15WwlNx8tVTABfw.jpeg)

RubyKaigi は今をつかんでる人たちの祭典のように思う。だからRubyKaigiは私達をつかんで離さない。そんな気がした。