# web code index
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us</title>
    <link rel="icon" sizes="32x32" href="favicon-32x32.png">
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="style2.css">
    <link rel="stylesheet" href="style_hamburger.css"> <!-- style for nav -->
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script src="https://code.jquery.com/jquery-3.6.0.js"
        integrity="sha256-H+K7U5CnXl1h5ywQfKtSj8PCmoN9aaq30gDh27Xc0jk=" crossorigin="anonymous"></script>
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css"
        integrity="sha512-z3gLpd7yknf1YoNbCzqRKc4qyor8gaKU1qmn+CShxbuBusANI9QpRohGBreCFkKxLhei6S9CQXFEbbKuqLg0DA=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />
    <style>
        /* Your existing CSS styles, except the styles related to the 2nd bar */
        * {
            box-sizing: border-box;
        }

        body {
            font-family: Verdana, sans-serif;
            background-color: #f1f1f1;
            margin: 0;
            padding: 0;
        }

        .mySlides {
            display: none;
        }

        /* Slideshow container */
        .slideshow-container {
            max-width: 1000px;
            position: relative;
            margin: auto;
            margin-top: 15px;
            /* Bring the image down a bit */
            margin-right: 20px
        }

        /* Caption text */
        .text {
            color: #f2f2f2;
            font-size: 30px;
            padding: 8px 12px;
            position: absolute;
            bottom: 8px;
            width: 100%;
            text-align: center;
            max-width: 50%;
            word-wrap: break-word;
        }

        /* Number text (1/3 etc) */
        .numbertext {
            color: #f2f2f2;
            font-size: 12px;
            padding: 8px 12px;
            position: absolute;
            top: 0;
        }

        .imgshow {
            width: 30%;
            border-radius: 12%;
            float: right;
            height: auto;
        }

        .content-wrapper {
            display: flex;
            flex-direction: column;
            align-items: flex-start;
            /* Align the text to the left side */
            justify-content: center;
            /*background-color: #f1f1f1;*/
            color: #000000;
            padding: 134px;
            /* margin-top: -30px; /* Remove the top margin to avoid gaps */
            max-width: 50%
        }

        .content-wrapper h1 {
            font-size: 36px;
            margin-bottom: 16px;
        }

        .content-wrapper p {
            font-size: 24px;
        }

        .text2 {
            text-align: center;
            margin-top: 0px;
            /* Adjust the margin-top to center the text vertically */
            margin-bottom: 15px;
            margin: auto;
            width: 50%;
            padding: 10px;
        }

        .text2 h1 {
            font-size: 36px;
            margin-bottom: 26px;
            background: linear-gradient(125deg, #e61b36, #9c1032);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .text2 p {
            font-size: 24px;
            margin-bottom: 36px;
        }

        /* Additional Styles for Three Round Frames */
        .frames-container {
            display: flex;
            justify-content: center;
            align-items: center;
            margin-top: 40px;
        }

        .round-frame {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            overflow: hidden;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
            margin: 20px;
        }

        .round-frame img {
            display: block;
            width: 100%;
            height: 100%;
            object-fit: cover;
        }


        .store-button-container {
            display: flex;
            justify-content: center;
            margin-top: 20px;
        }

        .store-button {
            display: inline-block;
            padding: 18px 50px;
            background: linear-gradient(125deg, #11998e, #38ef7d);
            color: white;
            text-decoration: none;
            border-radius: 200px;
            font-size: 18px;
            margin-top: 192px;
        }

        .section {
            padding: 40px;
            color: #000;
        }

        .section h2 {
            font-size: 36px;
            margin-bottom: 20px;
            background: linear-gradient(125deg, #e61b36, #9c1032);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .section p {
            font-size: 24px;
        }

        .gallery-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            margin-top: 40px;
        }

        .gallery-item {
            width: 200px;
            height: 200px;
            margin: 10px;
            overflow: hidden;
            border-radius: 50%;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
        }

        .gallery-item img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
    </style>
    <script>
        $(function () {
            $("#slideshow-image").load("slide_images.html");
        });
    </script>
    <script>
        $(function () {
            $("#test_button").load("test_button.html");
        });
    </script>
</head>

<body data-aos-easing="ease-in-out-back" data-aos-duration="1000" data-aos-delay="0">
    <nav>
        <button class="btn-hamburger">
            <i class="fas fa-bars"></i>
        </button>

        <img src="./imgs/logo-shabu.png" class="logonav" width="80px" height="80px"><h2>Shabu Easy By Ammy</h2>

        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="store.html">Store</a></li>
            <li><a href="contact.html">contract</a></li>
        </ul>
    </nav>
    <div class="wrapper">
        <div class="static-txt">We are</div>
        <ul class="dynamic-txts">
            <li><span>Shabu Easy by Ammy</span></li>
            <li><span>บุฟเฟ่ต์ชาบูแห่งจินตนาการ</span></li>
            <li><span>ของดีราคาโดน</span></li>
            <li><span>Shabu</span></li>
        </ul>
    </div>
    </div>
    <div class="text2" data-aos="fade-right" data-aos-duration="1000">
        <h1>Shabu Easy By Ammy</h1>
        <p>
            ยินดีต้อนรับสู่ร้าน Shabu Easy by Ammy! ร้านนี้เป็นสถานที่ที่คุณสามารถสนุกกับการรับประทานอาหารชาบูแบบง่าย ๆ
            แต่อร่อยมากได้ นี่คือข้อมูลเพิ่มเติมเกี่ยวกับร้าน Shabu Easy by Ammy
        </p>
    </div>
    <div class="text2">
        <!-- <a class="store-button" href="index.html">GO STORE</a> -->
        <div>
            <div id="test_button" data-aos="zoom-in" data-aos-delay="1000"></div>
        </div>
        <br><br>
        <div data-aos="fade-left" data-aos-duration="1000">
            <h1>ทำไมเราต้องกินชาบูร้านนี้</h1>
            <p>Shabu Easy by Ammy เป็นร้านอาหารชาบูที่มีคอนเซปต์แบบง่าย ๆ ที่เน้นความสดใหม่ของวัตถุดิบและรสชาติที่อร่อย
                ร้านนี้มุ่งเน้นให้ความสำคัญกับประสบการณ์ในการรับประทานอาหารแบบชาบู
                และพยายามทำให้การทานอาหารเป็นประสบการณ์ที่น่าจดจำในราคาที่เข้าถึงง่าย ๆ</p>
        </div>
    </div>
    <!-- Slideshow Section -->
    <div class="slideshow-container">
        <!-- ... (previously defined slideshow images) ... -->
    </div>



    <!-- New Section 2: Menu Gallery -->
    <div class="section" data-aos="fade-right" data-aos-duration="2000">
        <h2>ภาพสินค้าแนะนำ</h2>
        <div class="gallery-container">
            <div class="gallery-item">
                <img src="./imgs/หมูเด้ง.jpg" alt="Menu 1">
            </div>
            <div class="gallery-item">
                <img src="./imgs/แฮมหมูสเต็ก.jpg" alt="Menu 2">
            </div>
            <div class="gallery-item">
                <img src="./imgs/สาหร่ายพันปูอัด.jpg" alt="Menu 3">
            </div>

            <!-- Add more menu images here -->
        </div>
    </div>
    <script src="https://code.jquery.com/jquery-3.7.0.js"
    integrity="sha256-JlqSTELeR4TLqP0OG9dxM7yDPqX1ox/HfgiSLBj8+kM=" crossorigin="anonymous"></script>

<script>
    $(document).ready(function () {
        $(".btn-hamburger").on("click", function () {
            $("nav ul").toggleClass("nav-active");
        })
    });</script>
    <script>
        AOS.init();
    </script>
</body>

</html>
