# maungkham.github.io
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Loikaw City Guide</title>
  <meta name="viewport" content="width=device-width, initial-scale=1, minimum-scale=1, maximum-scale=1">

  <!-- Link Swiper's CSS -->
  <link rel="stylesheet" href="swiper.min.css">

  <!-- Demo styles -->
  <style>
    body {
      background: #fff;
      font-family: Helvetica Neue, Helvetica, Arial, sans-serif;
      font-size: 14px;
      color:#000;
      margin: 0;
      padding: 0;
    }
    .swiper-container {
      width: 100%;
      padding-top: 50px;
      padding-bottom: 50px;
    }
    .swiper-slide {
      background-position: center;
      background-size: cover;
      width: 300px;
      height: 300px;
    }
  </style>
</head>
<body>
  <!-- Swiper -->
  <div class="swiper-container">
    <div class="swiper-wrapper">
      <div class="swiper-slide" style="background-image:url(1.jpg)"></div>
      <div class="swiper-slide" style="background-image:url(2.jpg)"></div>
      <div class="swiper-slide" style="background-image:url(3.jpg)"></div>
      <div class="swiper-slide" style="background-image:url(4.jpg)"></div>
      <div class="swiper-slide" style="background-image:url(5.jpg)"></div>
      <div class="swiper-slide" style="background-image:url(6.jpg)"></div>
      <div class="swiper-slide" style="background-image:url(7.jpg)"></div>
      <div class="swiper-slide" style="background-image:url(9.jpg)"></div>
      <div class="swiper-slide" style="background-image:url(10.jpg)"></div>
          <div class="swiper-slide" style="background-image:url(11.jpg)"></div>
      <div class="swiper-slide" style="background-image:url(12.jpg)"></div>
     
       
    </div>
    <!-- Add Pagination -->
    <div class="swiper-pagination"></div>
      </div>
 <h1 align="center">Taung Kywe Pagoda in Loikaw</h1>
    <p align="center"><h3>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Taung Kwe Pagoda Entry is free but use of a camera is 300K or 500K, and 1000K for a video camera. Strangely a mobile phone camera was no charge, perhaps keep it out of sight anyway if there is a double cost. At night the temple is lit like a fairground with twinkling lights. Also a good place to weather watch or star gaze on darker platforms.</h3></p>
  <!-- Swiper JS -->
  <script src="swiper.min.js"></script>

  <!-- Initialize Swiper -->
  <script>
    var swiper = new Swiper('.swiper-container', {
      effect: 'coverflow',
      grabCursor: true,
      centeredSlides: true,
      slidesPerView: 'auto',
      coverflowEffect: {
        rotate: 50,
        stretch: 0,
        depth: 100,
        modifier: 1,
        slideShadows : true,
      },
      pagination: {
        el: '.swiper-pagination',
      },
    });
  </script>
</body>
</html>
