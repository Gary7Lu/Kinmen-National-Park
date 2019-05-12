<center>
    <h1 style="font-size:40px;font-weight:bold;">金門國家公園</h1></center>
<p>

    <style>
        html {
            height: 100%;
        }
        
        body {
            background-image: url("https://png.pngtree.com/thumb_back/fw800/back_pic/04/08/98/405814a2ba920b1.jpg");
            background-repeat: no-repeat;
            background-attachment: fixed;
            background-position: center;
            background-size: cover;
        }
        
        p {
            font-size: 18px;
            font-family: Microsoft JhengHei;
        }
        
        h2 {
            font-family: "微軟正黑體";
            font-weight: bold;
        }
        
        td {
            font-family: "微軟正黑體";
            font-size: 18px;
        }
        /* button*/
        .button {
            background-color: #a0fdff;
            border: 2px solid black;
            color: ;
            padding: 8px 24px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            font-size: 16px;
            box-shadow: 0 8px 16px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
            display: block;
        }
        
        .button:hover {
            background-color: #A1D0FF;
        }
        
        #flip {
            background-color: #a0fdff;
            border: 2px solid black;
            color: black;
            padding: 8px 42px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            font-size: 16px;
            box-shadow: 0 8px 16px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
            display: block;
        }
        
        .button-bar {
            position: fixed;
            top: 5%;
            right: 5%;
        }
        
        
        /*light box*/
        
         * {
            box-sizing: border-box
        }
        
        body {
            font-family: Verdana, sans-serif;
            margin: 0
        }
        
        .mySlides {
            display: none
        }
        
        img {
            vertical-align: middle;
        }
        /* Slideshow container */
        
        .slideshow-container {
            max-width: 1000px;
            position: relative;
            margin: auto;
        }
        /* Next & previous buttons */
        
        .prev,
        .next {
            cursor: pointer;
            position: absolute;
            top: 50%;
            width: auto;
            padding: 16px;
            margin-top: -22px;
            color: white;
            font-weight: bold;
            font-size: 18px;
            transition: 0.6s ease;
            border-radius: 0 3px 3px 0;
            user-select: none;
        }
        /* Position the "next button" to the right */
        
        .next {
            right: 0;
            border-radius: 3px 0 0 3px;
        }
        /* On hover, add a black background color with a little bit see-through */
        
        .prev:hover,
        .next:hover {
            background-color: rgba(0, 0, 0, 0.8);
        }
        /* Caption text */
        
        .text {
            color: #f2f2f2;
            font-size: 15px;
            padding: 8px 12px;
            position: absolute;
            bottom: 8px;
            width: 100%;
            text-align: center;
        }
        /* Number text (1/3 etc) */
        
        .numbertext {
            color: #f2f2f2;
            font-size: 12px;
            padding: 8px 12px;
            position: absolute;
            top: 0;
        }
        /* The dots/bullets/indicators */
        
        .dot {
            cursor: pointer;
            height: 15px;
            width: 15px;
            margin: 0 2px;
            background-color: #bbb;
            border-radius: 50%;
            display: inline-block;
            transition: background-color 0.6s ease;
        }
        
        .active,
        .dot:hover {
            background-color: #717171;
        }
        /* Fading animation */
        
        .fade {
            -webkit-animation-name: fade;
            -webkit-animation-duration: 1.5s;
            animation-name: fade;
            animation-duration: 1.5s;
        }
        
        @-webkit-keyframes fade {
            from {
                opacity: .4
            }
            to {
                opacity: 1
            }
        }
        
        @keyframes fade {
            from {
                opacity: .4
            }
            to {
                opacity: 1
            }
        }
        /* On smaller screens, decrease text size */
        @media only screen and (max-width: 300px) {
            .prev,
            .next,
            .text {
                font-size: 11px
            }
        }
        
        
        /*tabs*/
         body {
            font-family: Arial;
        }
        /* Style the tab */
        
        .tab {
            overflow: hidden;
            border: 1px solid #ccc;
            background-color: #f1f1f1;
        }
        /* Style the buttons inside the tab */
        
        .tab button {
            background-color: inherit;
            float: left;
            border: none;
            outline: none;
            cursor: pointer;
            padding: 14px 16px;
            transition: 0.3s;
            font-size: 17px;
        }
        /* Change background color of buttons on hover */
        
        .tab button:hover {
            background-color: #ddd;
        }
        /* Create an active/current tablink class */
        
        .tab button.active {
            background-color: #ccc;
        }
        /* Style the tab content */
        
        .tabcontent {
            display: none;
            padding: 6px 12px;
            border: 1px solid #ccc;
            border-top: none;
        }
    </style>

    <head>
        <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.0/jquery.min.js"></script>
        <script>
            $(document).ready(function() {
                $('#top').click(function() {
                    $('html, body').animate({
                        scrollTop: 0
                    }, 1000);
                });
                $('#bottom').click(function() {
                    $('html, body').animate({
                        scrollTop: $(document).height() - $(window).height()
                    }, 1000);
                });
                $('#a').click(function() {
                    $('html, body').animate({
                        scrollTop: $("#A").offset().top
                    }, 1000);
                });
                $('#b').click(function() {
                    $('html, body').animate({
                        scrollTop: $("#B").offset().top
                    }, 1000);
                });
                $('#c').click(function() {
                    $('html, body').animate({
                        scrollTop: $("#C").offset().top
                    }, 1000);
                });
                $('#d').click(function() {
                    $('html, body').animate({
                        scrollTop: $("#D").offset().top
                    }, 1000);
                });
                $('#e').click(function() {
                    $('html, body').animate({
                        scrollTop: $("#E").offset().top
                    }, 1000);
                });
                $('#f').click(function() {
                    $('html, body').animate({
                        scrollTop: $("#F").offset().top
                    }, 1000);
                });
                $("#flip").click(function() {
                    $(".button").slideToggle("slow");
                });
            });
        </script>
    </head>
    
    

    <h2 class="header-level-2" id="A">基本資訊:</h2>
    <div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
        <ol>
            <li>
                <p>建立時間 : 1995 年 10 月 18日 </p>
            </li>
            <li>
                <p>面積大小 : 35.3 平方公里 </p>
            </li>
            <li>
                <p>地理位置 : 金門島中央的太武山區、西北的古寧頭區、 西南的古崗區、東北的馬山區，以及烈嶼區
                </p>
            </li>
            <li>
                <p>主要維護 : 首座以維護歷史文化資產、戰役紀念為主</p>
            </li>
        </ol>
    </div>

    <h2 class="header-level-2" id="B">國家公園標示意涵:</h2>
    <div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
        <img align="left" style="width: 100px; height: 100px;" src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/7c/Kinmen_National_Park_Headquarters_Logo.svg/2000px-Kinmen_National_Park_Headquarters_Logo.svg.png" data-type="image">
        <center>
            <p>以閩南式建築的馬背造型，搭配吉祥的紅色構成整體圖案 主軸，突顯金門豐富的人文史蹟與傳統聚落，外圈則以綠 色代表金門亦有豐富的自然資源，例如鳥類等自然資源。
            </p>
        </center>
    </div>

    <h2 class="header-level-2" id="C">公園特色介紹:</h2>
    <div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
    
    <p></p>
        <body>

    <div class="tab">
        <button class="tablinks" onclick="openCity(event, '氣候水文')" id="defaultOpen">氣候水文</button>
        <button class="tablinks" onclick="openCity(event, '地質地形')">地質地形</button>
        <button class="tablinks" onclick="openCity(event, '生態資源')">生態資源</button>
        <button class="tablinks" onclick="openCity(event, '戰役古蹟')">戰役古蹟</button>
        <button class="tablinks" onclick="openCity(event, '人文史蹟')">人文史蹟</button>
        <button class="tablinks" onclick="openCity(event, '相關影音')">相關影音</button>
    </div>

    <div id="氣候水文" class="tabcontent">
        <h2>氣候</h2>
        <p>四面無高山屏障，風力強勁，冬季乾冷，春季多霧，年降雨量大於年蒸發量 ，使島上出現半乾旱的現象，不宜耕作，故島上農作以耐旱性雜糧為主。</p>
        <h2>水文</h2>
        <p>以平均狀況來看，五、六月類似內地梅雨季節，經常降雨不止是唯一降雨量超過蒸發量的季節，七月、八月夏季雷雨或颱風，雨量豐但無法截用而流失，並甚至帶來災害，十月至翌年二月則為旱季。由於受地形影響，金門地區主要水源以人工湖庫及地下水為主。</p>
    </div>

    <div id="地質地形" class="tabcontent">
        <h2>地質</h2>
        <p> 以瓊林尚義一帶將金門本島分成東西兩半部，東半部明顯地大量出露花崗片麻岩，西半部則是以紅土層為主體。</p>
        <h2>地形</h2>
        <p> (一)丘陵地形 : 以花崗片麻岩為主。</p>
        <p> (二)臺地地形 : 金門和烈嶼的花崗岩地區臺地高度要比紅土層高度為高，原因為西部早期環境有利於大規模、厚層的紅土生成。</p>
        <p> (三)低地、窪地 : 以中山紀念林與白乳山附近出現的雨蝕溝最為顯著，其成因與第四紀以來的環境變遷有密切關係，在景觀及環境教育上皆有價值。</p>
        <p> (四)水體 : 金門地區陸上之水體除少數天然湖外，多為人工開發或築堤而成之湖庫，提高了此地環境的負載力，也為生物提供良好棲息和覓食地點。</p>
        <p> (五)沙丘、沙灘、海岸 : 金門東北、東南及烈嶼的東北至東南，為花崗片麻岩丘陵地被海水侵蝕而成之崖面，並且露出花崗片麻岩被岩脈侵入的景象。</p>
    </div>

    <div id="動物資源" class="tabcontent">
        <h2>(一)鳥類 </h2>
        <p>鳥類是金門最具特色的野生動物資源，於鹹淡水溼地、潮間 帶以及陸地田野、樹林、灌叢間，均可看到多樣且豐富的鳥類資源，其中過境鳥佔45%為最大宗。金門地區冬候鳥中以鸕鶿、赤頸鴨、小水鴨等為主要鳥種，留鳥以白頭翁、麻雀、八哥、珠頸斑鳩及喜鵲等族群量較多；夏候鳥則以家燕、杜鵑科鳥類及栗喉蜂虎 等最具特色。</p>
        <h2>(二)哺乳類</h2>
        <p>陸域哺乳動物中，除歐亞水獺體型較大外，其餘均為小型野生動物。歐亞水獺同時列名於國際與國內之保育類野生動物名錄，目前金門地區各主要溼地水體，如前埔溪流域、雙鯉湖及慈湖周邊、后豐港地區、金沙溪流域均可發現水獺活動痕跡，族群尚稱穩定，仍需與野生動物保育主管機關合作加強其動態調查及棲所之保護。</p>
    </div>
    
     <div id="植物資源" class="tabcontent">
        <h2>特色比較</h2>
        <p>金門與台灣在植群組成上差異性仍甚大，如殼斗科(Fagaceae)在台灣為相當重要之一科，約產五十餘種，然在金門迄今未發現；金門之植物種類另一與台灣差異甚大堵，為樟科之潺槁樹，此種為目前金門自生木本植物中蓄積量最豐者。惟未見於台灣。</p>
    </div>
    
    
    <div id="戰役古蹟" class="tabcontent">
        <p>翟山坑道 毋忘在莒 八二三戰史館 文臺寶塔</p>
    </div>
    
    <div id="人文史蹟" class="tabcontent">
        <p>由於東北季風旺盛，金門的居民自清朝時期，就開始設立鎮風的辟邪物來 鎮風驅邪，而在金門最多的鎮風辟邪物就是風獅爺。</p>
    </div>
    
    


    <script>
        function openCity(evt, cityName) {
            var i, tabcontent, tablinks;
            tabcontent = document.getElementsByClassName("tabcontent");
            for (i = 0; i < tabcontent.length; i++) {
                tabcontent[i].style.display = "none";
            }
            tablinks = document.getElementsByClassName("tablinks");
            for (i = 0; i < tablinks.length; i++) {
                tablinks[i].className = tablinks[i].className.replace(" active", "");
            }
            document.getElementById(cityName).style.display = "block";
            evt.currentTarget.className += " active";
        }

        // Get the element with id="defaultOpen" and click on it
        document.getElementById("defaultOpen").click();
    </script>

</body>
        <p></p>
            <div class="slideshow-container">

        <div class="mySlides fade">
            <div class="numbertext">1 / 5</div>
            <img style="width:100%;height:400px" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTfQCFj0ADar4qmp2KMNd0b7Sht7K2IJ9qc7vrBnW6NvJQiyEtEzQ">
            <div class="text"> 水獺</div>
        </div>

        <div class="mySlides fade">
            <div class="numbertext">2 / 5</div>
            <img style="width:100%;height:400px" src="http://4.bp.blogspot.com/-03iiuAoe_nw/VL5R5tjCLZI/AAAAAAAA1rU/Fa4gaoxWcVg/s1600/DSC_0828.jpg" >
            <div class="text"> 翟山坑道</div>
        </div>

        <div class="mySlides fade">
            <div class="numbertext">3 / 5</div>
            <img style="width:100%;height:400px" src="http://pic.pimg.tw/martin0912/1324641420-2164420230_l.png">
            <div class="text"> 毋忘在莒</div>
        </div>
        
        <div class="mySlides fade">
            <div class="numbertext">4 / 5</div>
            <img style="width:100%;height:400px" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRLv6yM48o24gzMcrLGibXEMLn2lR9pBG5D-7HLwND_-MVrQ-jCbg">
            <div class="text"> 八二三戰史館</div>
        </div>
        
        <div class="mySlides fade">
            <div class="numbertext">5 / 5</div>
            <img style="width:100%;height:400px" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSUapL94vVzfeDLCDvoock4Ns8n7-Na3qVdam7wFlJ-SS2m1NIj">
            <div class="text"> 風獅爺</div>
        </div>
        
        <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
        <a class="next" onclick="plusSlides(1)">&#10095;</a>

    </div>
    <br>

    <div style="text-align:center">
        <span class="dot" onclick="currentSlide(1)"></span>
        <span class="dot" onclick="currentSlide(2)"></span>
        <span class="dot" onclick="currentSlide(3)"></span>
        <span class="dot" onclick="currentSlide(4)"></span>
        <span class="dot" onclick="currentSlide(5)"></span>
    </div>

    <script>
        var slideIndex = 1;
        showSlides(slideIndex);

        function plusSlides(n) {
            showSlides(slideIndex += n);
        }

        function currentSlide(n) {
            showSlides(slideIndex = n);
        }

        function showSlides(n) {
            var i;
            var slides = document.getElementsByClassName("mySlides");
            var dots = document.getElementsByClassName("dot");
            if (n > slides.length) {
                slideIndex = 1
            }
            if (n < 1) {
                slideIndex = slides.length
            }
            for (i = 0; i < slides.length; i++) {
                slides[i].style.display = "none";
            }
            for (i = 0; i < dots.length; i++) {
                dots[i].className = dots[i].className.replace(" active", "");
            }
            slides[slideIndex - 1].style.display = "block";
            dots[slideIndex - 1].className += " active";
        }
    </script>
        
        
        
        <p></p>

    </div>

    <h2 class="header-level-2" id="D">交通資訊:</h2>
    <div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">

        <p style="color:#FF8800;font-weight:bold;">觀光公車:</p>
        <p>水頭翟山線 電話:082-332-721 </p>
        <p><img src="http://www.kmnp.gov.tw/filesys/image/sys/line1.gif" title="水頭翟山線"></p>
        <p>古寧頭戰場線 電話:082-332-721 </p>
        <p><img src="http://www.kmnp.gov.tw/filesys/image/sys/line2.gif" title="古寧頭戰場線"></p>

        <p style="color:#FF8800;font-weight:bold;">租車:</p>
        <p>
            <table border="1" cellpadding="5" cellspacing="0" width="90%">
                <thead>
                    <tr>
                        <th width="30%">租車行名稱 </th>
                        <th width="45%">地址 </th>
                        <th width="25%">聯絡電話 </th>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <td>大新小客車租賃行</td>
                        <td>金門縣金城鎮民權路65巷1號</td>
                        <td>082-324128</td>
                    </tr>

                    <tr>
                        <td>汎德小客車租賃中心</td>
                        <td>金門縣金湖鎮新武德新莊4號</td>
                        <td>082-334082</td>
                    </tr>

                    <tr>
                        <td>金馬小客車租賃社</td>
                        <td>金門縣金城鎮民生路1-1號</td>
                        <td>082-324518</td>
                    </tr>

                    <tr>
                        <td>冠城汽車租賃行</td>
                        <td>金門縣金城鎮民族路7-7號</td>
                        <td>082-323390</td>
                    </tr>

                    <tr>
                        <td>冠軍小客車租賃行</td>
                        <td>金門縣金城鎮環島西路一段20號</td>
                        <td>082-372122</td>
                    </tr>

                    <tr>
                        <td>富成租車公司</td>
                        <td>金門縣金城鎮伯玉路200號</td>
                        <td>082-322177</td>
                    </tr>

                    <tr>
                        <td>景昇租車行</td>
                        <td>金門縣金湖鎮新菜市場11-1號</td>
                        <td>082-334322</td>
                    </tr>

                    <tr>
                        <td>吉品租車</td>
                        <td>金門縣伯玉路二段351號</td>
                        <td>082-372608</td>
                    </tr>

                    <tr>
                        <td>艾上綠能電動機車租賃</td>
                        <td>金門縣金寧鄉伯玉路一段232號之2</td>
                        <td>082-328096</td>
                    </tr>

                </tbody>
            </table>
        </p>

        <p style="color:#FF8800;font-weight:bold;">空中運輸:</p>

        <table border="1" cellpadding="5" cellspacing="0" width="90%">
            <thead>
                <tr>
                    <th width="31%">航空公司 </th>
                    <th width="18%">聯絡電話 </th>
                </tr>
            </thead>

            <tbody>
                <tr>
                    <td>立榮航空</td>
                    <td>(07)791-1000</td>
                </tr>

                <tr>
                    <td>華信航空</td>
                    <td>(02)412-8008</td>
                </tr>

                <tr>
                    <td>遠東航空</td>
                    <td>(02)4499-567</td>
                </tr>

                <tr>
                    <td>相關諮詢</td>
                    <td>(08)2322-381</td>
                </tr>

            </tbody>
        </table>

    </div>

    <h2 class="header-level-2" id="E">住宿資訊:</h2>
    <div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
        <p>
            <table border="1" cellpadding="5" cellspacing="0" width="90%">
                <thead>
                    <tr>
                        <th width="25%">民宿/飯店 </th>
                        <th width="48%">地址 </th>
                        <th width="24%">聯絡電話 </th>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <td>八二三行館</td>
                        <td>金門縣金湖鎮夏興100號</td>
                        <td>082-333-823</td>
                    </tr>

                    <tr>
                        <td>單飛背包客棧</td>
                        <td>金門縣金湖鎮前港路7巷12號</td>
                        <td>082-335-821</td>
                    </tr>

                    <tr>
                        <td>小週末民宿</td>
                        <td>金門縣金城鎮西海路35巷25號</td>
                        <td>0905-588-750</td>
                    </tr>

                    <tr>
                        <td>彩虹行館</td>
                        <td>金門縣金湖鎮下莊中興路101號2樓</td>
                        <td>0963-195-159</td>
                    </tr>

                    <tr>
                        <td>背包客棧497</td>
                        <td>金門縣金湖鎮塔后497號</td>
                        <td>0905-134-369</td>
                    </tr>
                </tbody>
            </table>
        </p>
    </div>

    <h2 class="header-level-2" id="F">美食資訊:</h2>
    <div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
        <p>
            <table border="1" cellpadding="5" cellspacing="0" width="90%">
                <thead>
                    <tr>
                        <th width="31%">店名</th>
                        <th width="43%">地址 </th>
                        <th width="23%">聯絡電話 </th>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <td>蚵嗲之家</td>
                        <td>金門縣金城鎮莒光路一段59號</td>
                        <td>(08)232-2210</td>
                    </tr>

                    <tr>
                        <td>金道地小吃店</td>
                        <td>金門縣金城鎮前水頭15號</td>
                        <td>(08)232-7969</td>
                    </tr>

                    <tr>
                        <td>閩式燒餅</td>
                        <td>金門縣金沙鎮博愛街48號</td>
                        <td>(08)235-2922</td>
                    </tr>

                    <tr>
                        <td>阿芬海產店</td>
                        <td>金門縣金湖鎮復國墩25號</td>
                        <td>(08)233-1139</td>
                    </tr>

                </tbody>
            </table>
        </p>
    </div>

    <h2 class="header-level-2">資料來源:</h2>
    <div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
        <ul>
            <li><a href="http://np.cpami.gov.tw/">台灣國家公園</a></li>
            <br>
            <li><a href="http://www.kmnp.gov.tw/index.php">金門國家公園</a></li>
            <br>
            <li><a href="http://www.kcbfa.gov.tw/BusSite/wSite/ct?xItem=3010&ctNode=241&mp=6">金門公共車船管理處</a></li>
            <br>
            <li><a href="https://www.kma.gov.tw/main/index.aspx">金門航空站</a></li>
            <br>
            <li><a href="https://travel.yam.com/Article.aspx?sn=93981">輕旅行</a></li>
            <br>
            <li><a href="https://asiayo.com/zh-tw/list/tw/kinmen-county/">AsiaYo</a></li>
        </ul>
    </div>

    <div class="button-bar">
        <a id="flip">選單</a>
        <a class="button" id="a" href="#">基本資訊</a>
        <a class="button" id="b" href="#">標示意涵</a>
        <a class="button" id="c" href="#">特色介紹</a>
        <a class="button" id="d" href="#">交通資訊</a>
        <a class="button" id="e" href="#">住宿資訊</a>
        <a class="button" id="f" href="#">美食資訊</a>
        <a class="button" id="top" href="#">網頁頂端</a>
        <a class="button" id="bottom" href="#">網頁底部</a>
        <a class="button" id="home" href="https://jim99224.github.io/HomePage/">返回主頁</a>
    </div>

  
