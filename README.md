<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Giới thiệu về bản thân</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #000000;
        }

        header {
            background-color: #78e3f4;
            color: rgb(250, 9, 157);
            text-align: center;
            padding: 20px;
        }

        header h1 {
            margin: 0;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        .intro {
            display: flex;
            align-items: center;
            justify-content: center;
            flex-wrap: wrap;
        }

        .intro img {
            border-radius: 50%;
            margin-right: 20px;
            width: 150px;
            height: 150px;
        }

        .intro .text {
            max-width: 700px;
        }

        .section-title {
            font-size: 24px;
            color: #333;
            margin-bottom: 20px;
            text-decoration: underline;
        }

        .contact-info {
            display: flex;
            flex-direction: column;
            align-items: flex-start;
        }

        .contact-info p {
            margin: 10px 0;
        }

        footer {
            background-color: #9ff4b1;
            color: rgb(238, 80, 80);
            text-align: center;
            padding: 1px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

<header>
    <h1>Giới thiệu đôi nét về học sinh trường THPT Chuyên Bến Tre</h1>
</header>

<div class="container">
    <section class="intro">
        <img src="images/1.png" alt="Ảnh đại diện của tôi">
        <div class="text">
            <h2 >Thông tin</h2>
            <p>
                Xin chào! Tôi là Nguyễn Ngọc Ngạn (Ngạn Tattoo), học sinh lớp chuyên Toán-Tin năm học 2022-2025. Tôi được bạn bè trong lớp biết đến với sự thân thiện, vui vẻ và hài hước. 
            </p> 
            <p>
                Ngoài công việc học tập, tôi cũng có những sở thích riêng, đặc biệt là bộ môn thể thao điện tử. Tôi thường chơi game cùng các bạn trong lớp sao những giờ học và những ngày chạy deadline mệt mỏi. Và đôi khi tôi cũng tặng bạn bè một vài hình xâm độc đáo.
            </p>
        </div>
    </section>
    <section>
        <h2>Thành tích</h2>
            <img src="images/minh.jpg" width="200" height="200" alt="Ảnh đại diện của tôi">    <img src="images/minh1.jpg" width="200" height="200" alt="Ảnh đại diện của tôi">    <img src="images/minh3.jpg" width="200" height="200" alt="Ảnh đại diện của tôi">    <img src="images/tu.jpg" width="200" height="200" alt="Ảnh đại diện của tôi"> 
    </section>
    <section class="contact-info">
        <h2>Liên hệ </h2>
        <p>Email: <a href="mailto:example@example.com">nguyenngocngan8271@gmail.com</a></p>
        <p>Điện thoại: 0879540907</p>
        <p>Địa chỉ: 219C, ấp Bình Thạnh, xã Bình Phú, TP Bến Tre, Bến Tre, Việt Nam </p>
    </section>
</div>
</body>
</html>
