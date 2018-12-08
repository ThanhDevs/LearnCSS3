
Tìm hiểu về sự kế thừa trong CSS
================================

## Kiến thức chính

* Sự kế thừa từ cha con

## Thực hành

### index.html

~~~html
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="utf-8" />
    <title>Học CSS3 cơ bản | La Văn Thanh</title>
    <link rel="stylesheet" type="text/css" href="style.css" />
</head>
<body>
	<h1>Học CSS3 cơ bản</h1>
    <p>Tôi tên là thanh rất vui được chia sẻ tới các bạn khóa học này</p>
</body>
</html>
~~~

### style.css
 
body thiết lập css chung có thể kế thừa lại cho phần tử con h1 và p

~~~css
body {
    color: red; /* Có thể thừa kế */
    border: 3px solid green; /* Không thể thừa kế */
}
~~~

Nhưng mà chỉ có `color` thì bị kế thừa từ thuộc tính của phần tử cha, `border` thì không, như thế là như thế nào? 

## Website tham khảo

### color

https://developer.mozilla.org/en/docs/Web/CSS/color

### border

https://developer.mozilla.org/en/docs/Web/CSS/border

**Kế thừ theo nghĩa bắt buộc**

~~~css
h1 {
    border: inherit;
}
~~~

## Kế hoạch cho video
* Mỗi video chỉ bao gồm một điểm chính, và sẽ được không chế trong vòng khoảng 5 - 15p 

## Nội dung code 
* Code sẽ được chia sẻ:
  - https://github.com/lavanthanh


## Website & Youtube

https://lavanthanh.com/

