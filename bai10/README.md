Màu sắc trong CSS
=================

## Nội dung chính

Màu sắc trong css

* Tên màu：red, blue, green, ...
* rgb：rgb(255, 0, 128), #ff0080
* hsl：hsl(0, 50%, 50%)

  + HSL là hệ thống màu tổ hợp theo 3 trục chính là H(Hue), S(Saturation) và L(Lightness), mỗi giá trị này thuộc một phạm vi khác nhau: 0 ≤ H < 360, 0% ≤ S ≤ 100% and 0% ≤ L ≤ 100%.

  + Hue là màu sắc mà chúng ta nhìn thấy phụ thuộc vào bước sóng ánh sáng được phản xạ hoặc sản xuất ra. Màu sắc được đo theo góc sắp xếp trên hình tròn và giúp chúng ta dễ cảm nhận sự thay đổi hơn so với hệ tọa độ RGB.

  + Saturation (độ bão hòa) đề cập đến sự tinh khiết và cường độ của một HUE đã cho. 100% độ bão hòa nghĩa là không có thêm màu xám cho màu sắc. Màu sắc hoàn toàn tinh khiết. Ở một cực khác, một màu với độ bão hòa 0% xuất hiện như một màu xám trung bình.

  + Lightness (Độ sáng) đo mức độ tương đối của màu đen hoặc trắng đã được pha trộn với một màu sắc nhất định. Thêm màu trắng làm cho màu sắc nhẹ hơn (sáng thêm nhưng mờ hơn) và thêm màu đen làm cho nó tối hơn (tạo bóng đen).

* Độ trong suốt：rgba(255, 0, 0, 1), hsla(120, 50%, 50%, 1)

## Thực hành

### index.html

~~~html
<!DOCTYPE html>
<html lang="Vi">
<head>
    <meta charset="utf-8" />
    <title>CSS3 nhập môn | La Văn Thanh</title>
    <link rel="stylesheet" type="text/css" href="style.css" />
</head>
<body>
    <h1>Cách chỉ định sự hiện tự của màu sắc</h1>
</body>
</html>
~~~

### style.css

~~~css
h1 {
    line-height: 128px;
    color: white;
    background-color: red;
    /* background-color: rgb(255, 0, 128); */
    /* background-color: hsl(0, 50%, 50%); */
    /* background-color: rgba(255, 0, 128, 1); */
    /* background-color: hsla(0, 50%, 50%, 1); */
}
~~~

## Kế hoạch cho video
* Mỗi video chỉ bao gồm một điểm chính, và sẽ được không chế trong vòng khoảng 5 - 15p 
* Code sẽ được chia sẻ:
  - https://github.com/ThanhDevs/LearnCSS3

## Website & Youtube 

http://lavanthanh.com
