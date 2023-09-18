# dxikitai

<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>373_伴聡一郎</title>

  <!-- リセットCSS -->
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/destyle.css@3.0.2/destyle.css">
  
  <!-- style.css -->
  <link rel="stylesheet" href="./css/style.css">

    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+JP:wght@500;700&display=swap" rel="stylesheet">
    <style>
        .html {
            font-family: 'Noto Sans JP', sans-serif;
        }
        .container{
            width: 90%;
            max-width: 1120px;
            margin: 0 auto;
            position: relative;
        }
        .flex{
            display: flex;
            justify-content: space-between;
            flex-wrap: wrap;
            align-items: center;
        }

        header {
            font-size: 24px;
            font-weight: 700;
            width: 90%;
            padding: 27px 0;
            /* background-color: chartreuse; */
            color: #333;
            text-align: center;
        }
        .header_menu li{
            margin-left: 40px;
        }
        .header_menu li a{
            transition: .3s;
        }
        .header_menu li a:hover{
            color: chartreuse;
            transition: .3s;
        }

        #hero {
            background-image: url(https://cdn.pixabay.com/photo/2017/07/25/01/22/cat-2536662_1280.jpg);
            background-position: center;
            background-size: cover;            
            height: 540px;
            border-radius: 30px;
            display: flex;
            align-items: center;
            margin-bottom: 90px;
            overflow: hidden;
        }
        #hero::before {
            content: '';
            width: 100%;
            height: 100%;
            background-color: #000000;
            position: absolute;
            top: 0;
            left: 0;
            opacity: 0.2;
            z-index: 1;
        }
        .hero_inner {
            z-index: 2;
            color: #fff;
            width: 100%;
            text-align: center;
        }

        #concept {
            margin-bottom: 120px;
        }
        .title {
            font-size: 20px;
            font-weight: 500;
            color: chartreuse;
            margin-bottom: 40px;
        }
        #concept h3 {
            font-size: 36px;
            font-weight: 700;
            margin-bottom: 60px;
        }
        deka {
            font-size: 60px;
        }
        .column-2 {
            width: 48%;
        }
        .text {
            line-height: 2;
        }
        .concept-img {
            background-image: url(https://cdn.pixabay.com/photo/2017/07/12/08/34/industry-2496192_1280.jpg);
            background-position: center;
            background-size: cover;            
            height: 340px;
            border-radius: 20px;
        }
        .heading {
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            font-size: 120px;
            font-weight: 700;
            color: chartreuse;
            opacity: 0.1;
            position: absolute;
            top: 0;
            right: 0;
            transform: translateY(-30%);
            z-index: -1;
        }

        #service {
            margin-bottom: 120px;
        }
        .service_inner {
            margin-bottom: 40px;
            position: relative;
        }
        .column-40 {
            width: 40%;
        }
        #service img {
            border-radius: 20px;
        }
        #service h3 {
            font-size: 24px;
            font-weight: 700;
            margin-bottom: 24px;
        }

        #company {
            margin-bottom: 120px;
        }
        #company dl {
            max-width: 900px;
            margin-left: auto;
        }
        #company dt {
            width: 80%;
            padding: 8px 0;
            font-weight: 400;
            border-bottom: solid 1px #D2ECBA;
        }
        /* #company dd {
            width: 70%;
            padding: 48px 0;
            border-bottom: solid 1px #D2ECBA;
        } */

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
        }
        
        /* メディアクエリを使用してレスポンシブ対応にする */
        @media screen and (max-width: 768px) {
            header {
                padding: 10px 0;
            }

            main {
                padding: 10px;
            }

            footer {
                padding: 5px 0;
            }
        }
    </style>   
</head>
<body>

<header>
    <div class="container flex">
    <a href="" class="container">
        373 伴聡一郎
    </a>
    <nav>
        <ul class="header_menu flex">
          <li><a href="#concept">志望理由</a></li>
          <li><a href="#service">強み</a></li>
          <li><a href="#company">自己紹介</a></li>
        </ul>
      </nav>
    </div>
</header>

<main>
    
    <section id="hero" class="container">
      <div class="hero_inner">
        <p class="">Tap into Our Limitless Potential.</p>
        <h1>スタートラインの底力をもっとここから広めていきたい</h1>
      </div>
    </section>
    
    <section id="concept" class="container">
      <div class="heading">おもいやり</div>
      <h2 class="title pop">志望理由</h2>
      <h3>支援技術力×<deka>情報戦略</deka></h3>
      <div class="flex">
        <div class="column-2">
          <p class="text">
            私はデジタルトランスフォーメーションの力で、誰もが自分らしく生きる社会を実現するための貢献がしたい。<br>
            <br>
            “可能性を見つけ出す観察力、未来を描く想像力、形にする行動力、
可能性を可能に変えていく技術力、
そして関わる責任。”<br>
            <br>
            当社が掲げる企業理念を更に影響力を持って実現できるステージへ挑戦したい。
          </p>
        </div>
        <div class="column-2 concept-img"></div>
      </div>
    </section>
    
    <section id="service" class="container">
      <h2 class="title pop">強み</h2>
      <div class="service_inner flex">
        <div class="column-40">
          <img src="./images/service1.jpg" width="100%" alt="">
        </div>
        <div class="column-55">
          <div class="heading">変</div>
          <h3>挑戦と学習能力</h3>
          <p class="text">新しい分野での挑戦を歓迎します。未経験から学び、成長し、常に新しい課題に取り組む情熱を持っています。</p>
        </div>
      </div>
      <div class="service_inner flex">
        <div class="column-40">
          <img src="./images/service1.jpg" width="100%" alt="">
        </div>
        <div class="column-55">
          <div class="heading">速</div>
          <h3>素早い行動力</h3>
          <p class="text">
            新技術を学びながらも手を動かし、学習と実践をトライアンドエラーしながらスピード感を持って成果まで進みます。</p>
        </div>
      </div>
      <div class="service_inner flex">
        <div class="column-40">
          <img src="./images/service2.jpg" width="100%" alt="">
        </div>
        <div class="column-55">
          <div class="heading">強</div>
          <h3>課題解決力</h3>
          <p class="text">複雑な課題に冷静に取り組む分析力と、締め切りを守りながら自己主導的に行動する能力があります。</p>
        </div>
      </div>
      <div class="service_inner flex">
        <div class="column-40">
          <img src="./images/service3.jpg" width="100%" alt="">
        </div>
        <div class="column-55">
          <div class="heading">団</div>
          <h3>チームワーク</h3>
          <p class="text">個人のこだわりよりもチームの成果を優先し、異なる部門と協力しプロジェクトの成功に貢献します。</p>
        </div>
      </div>
    </section>
    
    <section id="company" class="container">
      <h2 class="title">自己紹介</h2>
      <dl class="flex">
        <dt>伴　聡一郎　35歳<br>趣味/好きなものは、映画や読書、ディズニー作品、理科っぽいもの、『萩の月』、休日は友人や親戚を家に招きボードゲームなどして遊んでいます。<br>
        コーヒーは飲むと頭痛や動悸が起きるため苦手<br>好きな言葉は“死ぬこと以外かすり傷”</dt>
      </dl>
    </section>
    
  </main>

<footer>
    <p>&copy; 2023 ban soichiro</p>
</footer>

</body>
</html>
