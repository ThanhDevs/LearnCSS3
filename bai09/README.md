Căn chỉnh theo chiều dọc
========================

## Nội dung chính

* vertical-align：Căn chỉnh theo chiều dọc

### Phương thức để căn chỉnh  (giá trị) 

* baseline
* top
* bottom
* middle
* 10px(baseline Trên)
* -10px(baseline Dưới)

## Thực hành

### index.html

~~~html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8" />
    <title>Nhập Môn CSS3 | La Văn Thanh</title>
    <link rel="stylesheet" type="text/css" href="style.css" />
</head>
<body>
    <h1>Nguyên lý Căn chỉnh theo chiều dọc cho một nội dung trong webiste</h1>
    <p class="css01">This is my <img src="bar.png"> page.</p>
</body>
</html>
~~~

### style.css

~~~css
p {
    font-size: 64px;
    line-height: 128px;
    background-color: bisque;
}

img {
    vertical-align: baseline;
}
~~~

## Kế hoạch cho video
* Mỗi video chỉ bao gồm một điểm chính, và sẽ được không chế trong vòng khoảng 5 - 15p 
* Code sẽ được chia sẻ:
  - https://github.com/lavanthanh

## Website & Youtube 

http://lavanthanh.com
