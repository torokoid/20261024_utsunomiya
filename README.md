# 20261024_utsunomiya
<html lang="ja" data-loaded="false" data-scrolled="false" data-spmenu="closed">
<head>

<meta charset="UTF-8">
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE=EmulateIE10" />
<meta http-equiv="X-UA-Compatible" content="IE=edge">

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<!--ここから上はお決まりの定型文です-->


<!--ここからが表現の書式などを決めるcssという部分-->

<style type="text/css">
p {
color: #fffafa;
font-size: 1.5em;
}


.red {color:#ff0000;}
.grey {color:#ffffff; background:#999999;}
.snow {color:#fffafa;}
.yellow {color:#ff0000; background:#ffff00;}
.blue {color:#0000ff;}
.white {color:#ffffff;}
.waku {border:2px dotted #99cc66;
line-height: 200%;
padding: 10px;}


main {
background-color: rgba(255, 255, 255, 0.5);
}

section {
background-color: rgba(0, 225, 0, 0.3);
}


/* 点滅 */
.blinking{
-webkit-animation:blink 1.5s ease-in-out infinite alternate;
-moz-animation:blink 1.5s ease-in-out infinite alternate;
animation:blink 1.5s ease-in-out infinite alternate;
}
@-webkit-keyframes blink{
0% {opacity:0;}
100% {opacity:1;}
}
@-moz-keyframes blink{
0% {opacity:0;}
100% {opacity:1;}
}
@keyframes blink{
0% {opacity:0;}
100% {opacity:1;}
}

#wrap {background:none} /*PC用の背景はオフ*/

/*背景を表示させる部分*/
body::before {
content:"";
display:block;
position:fixed;
top:0;
left:0;
z-index:-1;
width:100%;
height:100vh;
background:url(https://torokoid.github.io/20261024_nasu_nikko/20261024_00054.jpeg) center/cover no-repeat;
-webkit-background-size:cover;/*Android4*/
}

a.p:hover {
position: relative;
text-decoration: none;
}
a.p span {
display: none;
position: relative;
top: -0.5em;
left: 2em;
}
a.p:hover span {
border: none;
display: block;
width: 800px;
}


@media screen and (min-width: 540px),
screen and (orientation: landscape) {
p.note { display: none; }
}


.media-container {
  width: 100%;
  max-width: 900px;
  margin: 0 auto;
}

.responsive-media {
  width: 100%;
  display: block;
}

.youtube-wrapper {
  position: relative;
  width: 100%;
  padding-bottom: 56.25%; /* 16:9比率 */
  height: 0;
}

.youtube-wrapper iframe {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  border: none;
}





/* オープニング画面のスタイリング（写真を表示するように変更） */
#splash {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100vh;
  background-color: #000000; /* 読み込み前の万一の背景（黒） */
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  z-index: 9999; /* 最前面に表示 */
  opacity: 1;
  visibility: visible;
  transition: opacity 0.8s ease, visibility 0.8s ease; /* 0.8秒かけてふわっと消える */
  padding: 20px;
  box-sizing: border-box;
}

.splash-content {
  max-width: 800px;
  width: 100%;
  text-align: center;
}

.splash-content img {
  width: 100%;
  height: auto;
  max-height: 75vh;
  object-fit: contain;
  box-shadow: 0 10px 30px rgba(0,0,0,0.5);
  border-radius: 4px;
}

.splash-text {
  color: #fff;
  margin-top: 15px;
  font-size: 1.2em;
}

/* 読み込み完了後に付与するクラス（非表示状態） */
#splash.loaded {
  opacity: 0;
  visibility: hidden;
}

/* メインコンテンツ */
#container {
  opacity: 1;
}




/* --- スクロールでズームインしながら浮き出るアニメーション --- */
.scroll-fade {
  opacity: 0;
  transform: translateY(40px) scale(0.85); /* 最初は少し下にいて、サイズも少し縮小（0.85倍）しておく */
  transition: opacity 1.2s cubic-bezier(0.16, 1, 0.3, 1), transform 1.2s cubic-bezier(0.16, 1, 0.3, 1);
  will-change: opacity, transform;
}

/* 画面内に入ったときに、元のサイズ・透明度になりながらズームイン・アップする */
.scroll-fade.is-show {
  opacity: 1;
  transform: translateY(0) scale(1); /* 通常のサイズ・位置に戻る（ズームイン） */
}



</style>

<link href="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.7.1/css/lightbox.css" rel="stylesheet">

</head>

<body>

<!-- オープニング（スプラッシュ画面に写真とタイトルを配置） -->
<div id="splash">
  <div class="splash-content">
    <img src="https://torokoid.github.io/20261024_nasu_nikko/20261024_00047.jpeg" alt="オープニング画像">
    <div class="splash-text">最初の一枚は赤い薔薇</div>
  </div>
</div>

<!-- メインコンテンツ -->
<div id="container">
  <h1>メインのホームページ画像</h1>
  <p><a href="https://torokoid.github.io/20261024_nasu_nikko/20261024_00047.jpeg" target="_blank"><img src="https://torokoid.github.io/20261024_nasu_nikko/20261024_00047.jpeg" alt="サンプル画像" class="responsive-media"></a></p>
</div>



<!--
    <p><a href="https://peyng.github.io/restart/">前回までの記録</a>><a><span class="grey">今回2026,05,28</span></a></p>
-->


<p class="note">
モバイル端末をお使いの場合は、画面を横向きにすると
背景画像の横方向がご覧頂けます。
</p>


<!--ここ上は、ほぼそのまま使います！-->


<!--QRコードの挿入例-->
<p align="left"> <img src="QR_2026Oct24_.png" alt="アクセス用QRコード" width="100">QR for Access</p>
<p align="right"><marquee direction="left" scrollamount="20" width="30%">(^_^)/~S,Hada</marquee></p>

<!--流れ文字の挿入例-->
<h1><span class="yellow"><marquee behavior="left">!!! 2026/10/24、那須温泉に一泊して日光の中禅寺湖と華厳滝まで !!!</marquee></span></h1>




<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

<!--ここから下が、本体部分-->


<div class="media-container">

<h2><span class="yellow">2026Oct22、那須の温泉に一泊予定で移動、前方が那須の山々</span></h2>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00001.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00001.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">道の駅やいた、で一休み、山々が近づきました</span></h2>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00002.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00002.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00008.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00008.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">道の駅のお花達が満開です</span></h2>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00003.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00003.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00004.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00004.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00005.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00005.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00006.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00006.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00007.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00007.jpeg" alt="サンプル画像" class="responsive-media"></a>


<h2><span class="yellow">那須エリアのお蕎麦屋さんでお昼</span></h2>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00012.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00012.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00009.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00009.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">店内はそこそこのお客さん達</span></h2>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00010.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00010.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">天ざるをいただきました</span></h2>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00011.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00011.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">那須の殺生石に到着</span></h2>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00013.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00013.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00014.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00014.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00015.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00015.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00017.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00017.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00018.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00018.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00019.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00019.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00020.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00020.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00021.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00021.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">那須温泉神社にお参り</span></h2>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00022.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00022.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">神社から見下ろす殺生石の眺めは壮観</span></h2>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00023.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00023.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00024.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00024.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00025.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00025.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00026.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00026.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">したから神社を見上げました</span></h2>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00027.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00027.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">少し上がって、那須高原展望台から南を眺めました</span></h2>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00028.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00028.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">筑波山も綺麗に見えてました</span></h2>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00029.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00029.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">茨城方面の山々も綺麗に見えてます</span></h2>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00030.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00030.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">サンバレー那須にお泊まり、フォレスト・ビラ</span></h2>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00031.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00031.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00032.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00032.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">お昼過ぎから温泉</span></h2>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00033.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00033.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">夕方の東の空にはお月様</span></h2>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00034.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00034.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">月齢10.9のお月様、うさぎさんも見えてます</span></h2>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00035.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00035.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">23日も晴天の朝</span></h2>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00040.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00040.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">木々も紅葉が始まっています</span></h2>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00041.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00041.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">朝食はバイキング</span></h2>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00042.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00042.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">ホテルの敷地内にはお花達が咲いています</span></h2>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00043.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00043.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00044.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00044.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00045.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00045.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00047.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00047.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00048.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00048.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00049.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00049.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00050.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00050.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00051.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00051.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00052.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00052.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00053.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00053.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00054.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00054.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00055.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00055.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00056.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00056.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00057.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00057.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00058.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00058.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00059.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00059.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00060.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00060.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00061.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00061.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">那須から日光に向かいます</span></h2>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00062.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00062.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">男体山が綺麗に見えています</span></h2>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00063.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00063.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">いろは坂の展望台からの眺め</span></h2>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00064.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00064.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00065.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00065.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">中禅寺湖に到着、男体山が綺麗</span></h2>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00066.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00066.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00067.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00067.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">ボートがたくさん浮かんでました</span></h2>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00068.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00068.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00069.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00069.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00070.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00070.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00071.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00071.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00072.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00072.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00073.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00073.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00074.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00074.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00075.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00075.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00078.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00078.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00079.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00079.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00080.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00080.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">カフェで軽くお昼</span></h2>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00081.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00081.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00083.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00083.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00084.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00084.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00085.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00085.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00086.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00086.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">華厳滝エレベータで100mほど下ります</span></h2>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00087.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00087.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00088.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00088.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00089.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00089.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">華厳滝の水量が多くて見応えがありました。1ton/minの水量とのこと</span></h2>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00090.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00090.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00091.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00091.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00092.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00092.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00093.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00093.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">滝エリアからの男体山も見事</span></h2>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00094.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00094.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00095.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00095.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">上からの滝見ポイントもありました</span></h2>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00096.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00096.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00097.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00097.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00098.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00098.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">滝の動画3枚、画像のクリックで動画再生します</span></h2>
<a href="https://youtube.com/shorts/4HJQc1clvWM" target="_blank"><img src="http://torokoid.github.io/20261024_00001.png" alt="サンプル画像" class="responsive-media"></a>
<a href="https://youtube.com/shorts/DMUGXXdCToY" target="_blank"><img src="http://torokoid.github.io/20261024_00002.png" alt="サンプル画像" class="responsive-media"></a>
<a href="https://youtube.com/shorts/olC5GdUGpuA" target="_blank"><img src="http://torokoid.github.io/20261024_00003.png" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">最後に男体山をもう一枚！</span></h2>
<a href="http://torokoid.github.io/20261024_nasu_nikko/20261024_00099.jpeg" target="_blank"><img src="http://torokoid.github.io/20261024_nasu_nikko/20261024_00099.jpeg" alt="サンプル画像" class="responsive-media"></a>

<!--
<h2><span class="yellow">宇都宮市北部、ヨークベニマル御幸ヶ原店までの走行経路はこのルート</span></h2>
<a href="20261022_00001.png" target="_blank"><img src="20261022_00001.png" alt="サンプル画像" class="responsive-media"></a>


<h2><span class="yellow">ヨークベニマル御幸ヶ原店までの行き帰り運転動画</span></h2>
<div class="youtube-wrapper">
<iframe width="560" height="315" src="https://www.youtube.com/embed/-Wua99x_vac?si=UUJzB1QLhTCnXvD_&autoplay=1&mute=1&loop=1&playlist=-Wua99x_vac" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
-->

<h2><span class="yellow">以上、今回は、那須温泉と日光、中禅寺湖と華厳滝でした</span></h2>


<br><br>
<h2><span class="yellow">月齢の説明リンク貼ります</span></h2>
<h2><a href="https://starwalk.space/ja/moon-calendar" target="_blank"><span class="snow">月齢カレンダー・リンク</span></a></h2>

<br><br>
<br><br>

<h2><span class="yellow">今日のBGMは、邦楽70年代ヒットソングメドレー ♪ღ♫ 70年代 ヒット曲 ♪ღ♫ 70年代 ヒット曲メドレー フォーク 昭和の名曲まとめ</span></h2>
<div class="youtube-wrapper">
<iframe width="560" height="315" src="https://www.youtube.com/embed/znGRYIU5-vI?si=AbxooADgWamfbe1t&autoplay=1&mute=0&loop=1&playlist=znGRYIU5-vI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>

<br><br><br>
<h2><span class="yellow">2026Oct24、那須温泉に一泊して日光の中禅寺湖と華厳滝まででした<br>Thank you for reading this far.</span></h2>

<br><br><br>

<!-- hitwebcounter Code START -->
<a href="https://www.hitwebcounter.com" target="_blank">
<p>you are <img src="https://hitwebcounter.com/counter/counter.php?page=21345151&style=0018&nbdigits=5&type=page&initCount=0" title="Counter Widget" Alt="Visit counter For Websites"   border="0" />visitor<br>The numbers are cumulative for the Bangkok ＆ Utsunomiya series websites launched since 2025 August 1st.</p></a>  



<style>
.responsive-media {
    opacity: 1 !important;
    filter: brightness(100%) !important;
}
</style>


<br><br><br><br><br><br><br><br><br>





<br><br>

<br><br><br><br><br><br>

<!--本体はここまで-->
    </div>

<!--画面に空白地帯を作って、背景が見えるようにしています-->
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>



<!-- フッタ -->
<footer>
<p>Copyright 2026/10/24 S,Hada</p>
</footer>

<!--HPにさまざまなJavaScriptを呼び込むための書式-->
<script src="https://code.jquery.com/jquery-1.12.4.min.js" type="text/javascript"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.7.1/js/lightbox.min.js" type="text/javascript"></script>

<script type='text/javascript' src='https://torokoid.github.io/shiba/jquery.js?ver=1.12.4'></script>
<script src="https://torokoid.github.io/shiba/jquery.goup.min.js"></script>
<script src="https://torokoid.github.io/shiba/my.js"></script>


<script>
window.addEventListener('load', function() {
  const splash = document.querySelector('#splash');
  setTimeout(function() {
    splash.classList.add('loaded');
  }, 800);
});
</script>


<script>
// オープニング画面を消す既存のコード
window.addEventListener('load', function() {
  const splash = document.querySelector('#splash');
  setTimeout(function() {
    splash.classList.add('loaded');
  }, 800);
});

// --- スクロール連動のフェードイン処理 ---
document.addEventListener("DOMContentLoaded", function() {
  // 動きをつけたい要素（ここでは画像と見出し h2）を指定
  const targets = document.querySelectorAll('.responsive-media, h2');

  const observer = new IntersectionObserver((entries, observer) => {
    entries.forEach(entry => {
      // 画面に少し入ってきたら
      if (entry.isIntersecting) {
        entry.target.classList.add('is-show');
        // 何度もアニメーションさせたい場合は unobserve を外してください
        // observer.unobserve(entry.target); 
      }
    });
  }, {
    threshold: 0.25 // 要素が25%見えたタイミングで発火
  });

  targets.forEach(target => {
    target.classList.add('scroll-fade'); // 初期状態のクラスを付与
    observer.observe(target); // 監視を開始
  });
});
</script>

    </body>
    
</html>
