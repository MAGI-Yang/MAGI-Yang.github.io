---
layout: post
title:  "CLANNAD full voice　NoDVD化"
categories: games
---

REF: [http://kuroiryuwu.blog98.fc2.com/blog-entry-14.html](http://kuroiryuwu.blog98.fc2.com/blog-entry-14.html)

このソフトのNoDVD化には、パッチでもいいのですが。「書き換え」を今回はご紹介いたします。

なお、記載された方法は、本製品版ディスク（オリジナルディスク）やシリアルの紛失。および破損等の理由でお困りの方を対象とさせていただきます。犯罪行為の助長ではございません。

バイナリ

※既にインスコしたものとします。

REALLIVE.EXEをエディタで変更してください。

左を右に書き換えてください。

002E9F10: 

55 8B EC 6A FF 68 79 A6 AC 01 64 A1 00 00 00 00

　　　　→ C7 05 DF 91 4E 00 67 44 F7 F5 C7 05 E3 91 4E 00 

002E9F20:

 50 64 89 25 00 00 00
 
 　→ CB 95 BE A0 33 C0 C3 

以上です。お疲れ様でした。


不过比较讨厌的是，这样子修改会破坏原有的可执行文件的签名，每次运行都会弹窗要求管理员权限Orz

之所以会有这个问题，是因为 CLANNAD 的 FV 版有个防止非法复制光碟的保护措施，不过这个防盗程序在比较新的操作系统里似乎总是会错误判断，以至于官方都在产品里随了一份说明，所以说要是自己不想改程序的话，可以到[这个地方](http://www.product.co.jp/avg-support/)寻求官方支持。