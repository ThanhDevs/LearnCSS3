Bộ chọn trong CSS
=================

## Nội dung chính

* Slect everything
* Select (div, span, h1, p, a, img ...)
* ID (#)
* Class (.)

## Thực hành

## index.html

~~~html
<!DOCTYPE html>
<html lang="Vi">
<head>
    <meta charset="utf-8" />
    <title>Học CSS3 | La Văn Thanh</title>
    <link rel="stylesheet" type="text/css" href="style.css" />
</head>
<body>

    <h1>Bộ chọn trong CSS</h1>
    
    <p>Cascading Style Sheets (CSS) is a stylesheet language used to describe the presentation of a document written in HTML or XML (including XML dialects such as SVG or XHTML). CSS describes how elements should be rendered on screen, on paper, in speech, or on other media.</p>
   
   <p class="text-right">Cascading Style Sheets (CSS) is a stylesheet language used to describe the presentation of a document written in HTML or XML (including XML dialects such as SVG or XHTML). CSS describes how elements should be rendered on screen, on paper, in speech, or on other media.</p>
    
    <p>Cascading Style Sheets (CSS) is a stylesheet language used to describe the presentation of a document written in HTML or XML (including XML dialects such as SVG or XHTML). CSS describes how elements should be rendered on screen, on paper, in speech, or on other media.</p>

    <div class="text-right">
        <button id="btnRegister">Đăng ký</button>
        <button id="btnLogin">Đăng nhập</button>
    </div>

</body>
</html>
~~~

## style.css

~~~css
* {
    /* color: red; */
}

body {
    font-family: Arial, sans-serif;
    font-size: 15px;
    line-height: 26px;
    /* font: 15px/26px arial, sans-serif; */
}

p {
    background-color: bisque;
    font-size: 24px;
    line-height: 48px;
    /* line-height: 2em; */
}

button {
    background-color: dodgerblue;
    width: 150px;
    height: 50px;
    font-size: 24px;
}

#btnRegister {
    color: whitesmoke;
}

#btnLogin {
    font-weight: bolder;
}

.text-left {
    text-align: left;
}

.text-center {
    text-align: center;
}

.text-right {
    text-align: right;
}

~~~


