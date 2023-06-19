****はじめにお読みください****

・本章で使用しておりますreset.cssでは、本書で紹介している「html5doctor Reset Stylesheet」を
　ベースにしたうえで、書籍内のCSSの記述を簡略化するために、すべてのreset.cssに対して
　以下のコードを追加しています。


■■■■■■■■■■■■（本章のreset.cssに追加したコード）■■■■■■■■■■■■

/* 本書サンプル用に以下のコードを追加しています。 */
ol, ul {
    list-style: none;
}
/* clearfix */
.cf {
	zoom: 1;
}
.cf:before, .cf:after {
	content: "";
	display: table;
}
.cf:after {
	clear: both;
}

■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■

これらのコードはreset.cssではなく、各サンプルのCSSに追記することもできますが、
全ページで共通のスタイルとなりますので、当サンプルではreset.cssに追記しています。
本書を読み進めるうえではこの点にご注意ください。


