<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
    <style>
        .button:hover {opacity: 1}
        .button {
            background-color:darkred ;
            border: none;
            color: white;
            padding: 15px 32px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            margin: 4px 2px;
            cursor: pointer;
            font-size: 16px;
            opacity: 0.6;
            transition: 0.7s;
            }
            </style>
</head>
<body onload="checkCookie(cus_type)">
    

<input type="button" name="button" id="demo1" class="button button1" onclick="checkCookie('albaraka_b')"  value="BİREYSEL İNTERNET ŞUBESİ" title="Bireysel İnternet Şubesi"> 
<input type="button" name="button" id="demo2" class="button button1" onclick="checkCookie('albaraka_k')"  value="KURUMSAL İNTERNET ŞUBESİ" title="Kurumsal İnternet Şubesi">

<script>

function setCookie(cname,cvalue,exdays) {
    var d = new Date();
    d.setTime(d.getTime() + (exdays*24*60*60*1000));
    var expires = "expires=" + d.toGMTString();
    document.cookie = cname + "=" + cvalue + ";" + expires + ";path=/";
}

function getCookie(cname) {
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
    return "";
}

 function checkCookie(cus_type){
    var cctrl = getCookie(cus_type);
    if(cctrl != ""){
        if(cus_type == "albaraka_b")
            document.write('<img src="http://www.yenislayt.com/upload/3547273837.png"  width="300" height="300">');
        else if(cus_type == "albaraka_k")
            document.write('<img src="https://www.ziraatbank.com.tr/PublishingImages/Subpage/dijitalBankacilik/InternetBankaciligi/Kurumsal_Internet_Subesi.jpg"  width="300" height="300">'); 
            else return 0;
    }
     else{
         setCookie(cus_type, "deger", 15); 
        }
    
}


</script>
</body>
</html>
