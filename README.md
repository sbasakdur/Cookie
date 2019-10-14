<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
    <style>
  
    p {                                                  /* Static banner style */
        display: block;
        margin-left: 0;
        margin-right: 0;
        background-color: rgb(200, 74, 45);
        text-align: left;
        font-family: Verdana, sans-serif; margin:0;
        font-size: 20px;
        margin: -8px 8px;
        padding: 24px 20px 30px 30px;
        width: 100%;
        color: #fff;  }

        .mySlides {display:none;}

        .button:hover {background-color: darkred;}
        
        .right {                                          /* Button style */
            position: absolute;
            right: 297px;
            background-color: #b03124;
            border: none;
            color: #fff;
            padding: 14px 28px 30px 30px;
            font-family: Arial, Helvetica, sans-serif;
            font-weight: bold;
            width: 150px;
            height: 1px;
            text-align: center;
            display: block;
            margin: -8px 8px;
            cursor: pointer;
            font-size: 10px;
            opacity: 1;
            transition: 0.5s;   }

            .right1 {                                      /* Button style */
            position: absolute;
            right: 145px;
            background-color: #b03124 ;
            border: none;
            color: #fff;
            padding: 14px 28px 30px 30px;
            font-family: Arial, Helvetica, sans-serif;
            font-weight: bold;
            width: 150px;
            height: 1px;
            text-align: center;
            text-decoration: none;
            display: block;
            margin: -8px 8px;
            cursor: pointer;
            font-size: 10px;
            opacity: 1;
            transition: 0.5s;  }
            .right2 {
            border-radius: 50px;
            float: right;
            margin: -50px 70px 0 0;
            font-weight: bold;
            border: 1px solid #1a2a34;  }

            * {box-sizing: border-box;}
            body {font-family: Verdana, sans-serif;}
            .mySlides {display: none;}
            img {vertical-align: middle;}
            .slideshow-container {                          /* Slideshow container */
              max-width: 100%;
              position: relative;
              margin: auto;  }
            .numbertext {                                   /* Number text (1/4 etc) */
                color: #f2f2f2;
                font-size: 12px;
                padding: 8px 12px;
                position: absolute;
                top: 0;   }   
            .dot {                                          /* The dots/bullets/indicators */
              height: 15px;
              width: 15px;
              margin: 0 2px;
              background-color: #717171;
              border-radius: 50%;
              display: inline-block;
              transition: background-color 0.6s ease;  }
            .active {
              background-color: #b03124;   }
            .fade {                                         /* Fading animation */
              -webkit-animation-name: fade;
              -webkit-animation-duration: 1.5s;
              animation-name: fade;
              animation-duration: 1.5s;  }
            
            @-webkit-keyframes fade {
              from {opacity: .4} 
              to {opacity: 1}   }
            @keyframes fade {
              from {opacity: .4} 
              to {opacity: 1}  }
            @media only screen and (max-width: 300px) {     /* On smaller screens, decrease text size */
              .text {font-size: 11px}  }
            .mySlides img {
                height: 370px;  }
            </style>
            
        </head>
        
        <body onload="checkCookies()"> 
            
            <p> BİREYSEL MÜŞTERİ </p>
            <button type="submit" class="right2 button right1" >HEMEN TIKLA</button>

            <br/>
            
            <button id="demo1" class="button right"  onclick="checkCookie('albaraka_b')">BİREYSEL <br /> İNTERNET ŞUBESİ</button>
            <button id="demo2" class="button right1" onclick="checkCookie('albaraka_k')">KURUMSAL <br /> İNTERNET ŞUBESİ</button>
            
            <br>
            <br>
            <br>
            <br>
            
            <div class="slideshow-container"> 

            <div  class="mySlides">
              <div class="numbertext">1 / 4</div>
              <img id="img1" src="https://piynirekmek.files.wordpress.com/2013/03/doga-wallpaper-42.jpg" style="width: 100%">
            </div>
            
            <div class="mySlides">
              <div class="numbertext">2 / 4</div>
              <img id="img2"  src="https://i.pinimg.com/originals/e6/f6/48/e6f648b439081d9f0009c0d73f874df8.jpg" style="width:100%">
            </div>
            
            <div  class="mySlides">
              <div class="numbertext">3 / 4</div>
              <img id="img3"  src="https://profegitim.com/wp-content/uploads/2019/04/Y%C3%BCksek-%C3%87%C3%B6z%C3%BCn%C3%BCrl%C3%BCkl%C3%BC-Wallpaper.jpg" style="width:100%">
            </div>

            <div  class="mySlides">
               <div class="numbertext">4 / 4</div>
               <img id="img4"  src="https://jssorcdn7.azureedge.net/demos/img/gallery/980x380/002.jpg" style="width:100%">
            </div>
                  
            <div  class="mySlides">
               <div class="numbertext"></div>
               <img id="img5"  src="http://wowslider.com/sliders/demo-77/data1/images/field175959_1920.jpg" style="width:100%">
            </div>

            <div  class="mySlides">
               <div class="numbertext"></div>
               <img id="img6"  src="http://wowslider.com/sliders/demo-5/data/images/sur.jpg" style="width:100%">
            </div>

            <div  class="mySlides">
               <div class="numbertext"></div>
               <img id="img7"  src="http://wowslider.com/sliders/demo-77/data1/images/road220058.jpg" style="width:100%">
            </div>

            <div  class="mySlides">
               <div class="numbertext"></div>
               <img id="img8"  src="https://epnext.com/wp-content/uploads/2017/07/Zencommerce-Laptop2.jpg" style="width:100%">
            </div>

            <div  class="mySlides">
               <div class="numbertext"></div>
               <img id="img9"  src="https://www.alikus.av.tr/3X/img.php?d=/alikus.av.tr/uploads/genel/0_1548342976_bankacilik.jpg&w=1920&h=1080" style="width:100%">
                </div>

            <div  class="mySlides">
               <div class="numbertext"></div>
               <img id="img10" src="https://cdn.comu.edu.tr/cms/bigaubf/foto/180-bankacilik-ve-finans-io-bolumune-ogrenci-alimi-kab.jpg" style="width:100%">
            </div>
            </div>

            <br>
            
            <div style="text-align:center">
              <span class="dot"></span>
              <span class="dot"></span>
              <span class="dot"></span>
              <span class="dot"></span>
            </div>
            
            <script>
            
            function setCookie(cname,cvalue,exdays) {          // setCookie fonksiyonu ile butona basıldığında aranan cookie olmadığı takdirde cookie oluşturulur.
            var d = new Date();
            d.setTime(d.getTime() + (exdays*24*60*60*1000));
            var expires = "expires=" + d.toGMTString();
            document.cookie = cname + "=" + cvalue + ";" + expires + ";path=/";  }


            function getCookie(cname) {                        // cname parametresi ile istenen tipte cookie olup olmadığı bilgisini verir.
            var name = cname + "=";
            var decodedCookie = decodeURIComponent(document.cookie);
            var ca = decodedCookie.split(';');
            for(var i = 0; i < ca.length; i++) {
                var c = ca[i];
                while (c.charAt(0) == ' ') {
                    c = c.substring(1);
                    }
                    if (c.indexOf(name) == 0) {
                        return c.substring(name.length, c.length);
                        }
                        }
                        return "";    }
                        
                        
                        var resim1= "https://epnext.com/wp-content/uploads/2017/07/Zencommerce-Laptop2.jpg";
                        var resim2= "https://www.alikus.av.tr/3X/img.php?d=/alikus.av.tr/uploads/genel/0_1548342976_bankacilik.jpg&w=1920&h=1080";
                        var resim3= "https://cdn.comu.edu.tr/cms/bigaubf/foto/180-bankacilik-ve-finans-io-bolumune-ogrenci-alimi-kab.jpg";


                        function checkCookies(){               // sayfaya ilk girildiğinde aranan cookie olup olmadığı tespit edilir. varsa cookie'nin çeşidine özel görüntüler ekrana yazdırılır. yoksa akış aynen devam eder.
                        var test1 = document.getElementById("img1");
                        if( getCookie('albaraka_b') != "" ){
                            if( getCookie('albaraka_k') != "")
                            test1.src= resim1;
                            else
                            test1.src= resim2;    }
                            else if( getCookie('albaraka_k') != "" ){
                            test1.src= resim3;    }
                            else return "";    }
                            

                            function checkCookie(cus_type){    // 2 butondan herhangi birine basıldığı anda parametreyi cus_type olarak algılar ve bu profilde daha önceden oluşturulmuş bir cookie yoksa yeni oluşturur.
                            var cctrl = getCookie(cus_type);   // getCookie fonksiyonu çağrılarak istenen tipte cookie nin varlığı test edilir.
                            if(cctrl == "")                    // cookie bulunamadıysa şart sağlanarak setCookie fonksiyonu ile aranan tipte bir cookie oluşturulur.
                            setCookie(cus_type, "deger", 15);
                            else return "";      }             //cookie varsa döngüden çıkar.
                               

                            var slideIndex = 0;                // 4 sn aralıklarda ilk dört resmi altındaki geçiş butonlarıyla eşzamanlı değiştiren fonksiyon.
                            showSlides();
                            
                            function showSlides() {
                                var i;
                                var slides = document.getElementsByClassName("mySlides");
                                var dots = document.getElementsByClassName("dot");
                                for (i = 0; i < 4; i++) {
                                    slides[i].style.display = "none";    }
                                    slideIndex++;
                                    if (slideIndex > 4) {slideIndex = 1}  
                                    for (i = 0; i < dots.length; i++) {
                                        dots[i].className = dots[i].className.replace(" active", "");    }
                                        slides[slideIndex-1].style.display = "block";
                                        dots[slideIndex-1].className += " active";
                                        setTimeout(showSlides, 5000);     }               // Change image every 5 seconds
                                        
                                        </script>
</body>
</html>
