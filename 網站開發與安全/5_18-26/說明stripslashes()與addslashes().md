---

    <!DOCTYPE HTML >

    <html>

    <head>

    <meta http-equiv="Content-Type" content="text/html; charset=utf-8">

    <title>應用addcslashes()函數和stripslashes()函數分別對字串進行轉義和還原</title>

    </head>

    <body>

    <?php

     $str = "select * from tb_book where bookname = 'PHP5從入門到放棄'";

     echo $str."<br>";

    $a = addslashes($str);  //對字串中的特殊字元進行轉義

     echo $a."<br>"; //輸出轉義後的字元

     $b = stripslashes($a); //對轉義後的字元進行還原

     echo $b."<br>"; //將字元原義輸出

    ?>

    </body>

    </html>

---
# stripslashes
---

    定義和用法
    stripslashes()函數刪除由addslashes()函數添加的反斜杠。
    
    語法:stripslashes( string )
    
    引用:https://www.w3school.com.cn/php/func_string_stripslashes.asp
---

# addslashes
---

    定義和用法:
    addslashes() 函數返回在預定義字符之前添加反斜杠的字符串。

    預定義字符是：

    單引號（'）
    雙引號（"）
    反斜杠（\）
    NULL
    
    語法:addslashes(string)
    
    引用:https://www.w3school.com.cn/php/func_string_addslashes.asp
---

    
