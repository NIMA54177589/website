<!DOCTYPE html>
<html lang="fa-IR">
<head>
<title>قالب ساده HTML - طراحی شده با DIV</title>
<meta charset="UTF-8">
<!-- برای واکنش گرایی صفحه -->
<meta name="viewport" content="width=device-width, initial-scale=1">
<!-- فراخوانی آیکون ها - برای نمایش آیکون منو در گوشی های موبایل -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<!-- فراخوانی فایل سی اس اس -->
<link rel="stylesheet" href="css/my-style.css">
<!-- برای فاوآیکون | تصویر کوچک در کنار عنوان صفحه در مرورگرها -->
<link href="img/icon.png" rel="icon" sizes="16x16">
</head>
<body>

<!-- هدر سایت -->
<div class="header">
  <h1>سایت آموزشی من</h1>
  <p>به سایت من خوش آمدید</p>
</div>

<!-- منو -->
<div class="navbar" id="myTopnav">
  <a href="#" class="active">خانه</a>
  <a href="#">تست 1</a>
  <a href="#">تست 2</a>
  <a href="#">تست 3</a>
  <a href="#">تست 4</a>
  <a href="#">تست 5</a>
  <a href="#" class="right">تست 6</a>
  <a href="javascript:void(0);" class="icon" onclick="mymenumobile()">
  <i class="fa fa-bars"></i>
  </a>
</div>

<!-- باکس اصلی -->
<div class="row">
<!-- سایدبار سمت راست -->
<div class="side">

<!-- باکس اول -->
<div class="side-box">
<h3>درباره من</h3>
<div style="text-align:center;">
<img src="img/logo.png">
</div>
<p>این یک متن برای تست می باشد. این یک متن برای تست می باشد. این یک متن برای تست می باشد.</p>
</div>

<!-- باکس دوم -->
<div class="side-box">
<h3>یک متن دیگه</h3>
<p>این یک متن برای تست می باشد. این یک متن برای تست می باشد. این یک متن برای تست می باشد. این یک متن برای تست می باشد. این یک متن برای تست می باشد. این یک متن برای تست می باشد.</p>
</div>

<!-- باکس سوم -->
<div class="side-box">
<h3>محبوب ترین دسته ها</h3>
<a href="#" target="_blank"><div class="fakeimg-1"></div></a><br>
<a href="#" target="_blank"><div class="fakeimg-2"></div></a><br>
<a href="#" target="_blank"><div class="fakeimg-3"></div></a><br>
<a href="#" target="_blank"><div class="fakeimg-4"></div></a>
</div>
	
<!-- باکس چهارم -->
<div class="side-box">
<h3>یک متن دیگه</h3>
<p>این یک متن برای تست می باشد. این یک متن برای تست می باشد. این یک متن برای تست می باشد. این یک متن برای تست می باشد. این یک متن برای تست می باشد. این یک متن برای تست می باشد.</p>
</div>
	
</div>

<!-- باکس مطالب سایت -->
  <div class="main">
  
   <!-- مطلب شماره 1 -->
   <div class="mypost">
    <h2><a href="#" title="مطلب شماره 1">مطلب شماره 1</a></h2>
    <h5>این مطلب توسط فری لرن در تاریخ 1399/01/17 نوشته شده است</h5>
	<hr>
    <div class="img-post">
	 <img src="img/img-post-2.jpg"> 
	</div>
    <p>این یک متن برای تست می باشد. این یک متن برای تست می باشد. این یک متن برای تست می باشد. این یک متن برای تست می باشد. این یک متن برای تست می باشد. این یک متن برای تست می باشد. این یک متن برای تست می باشد. این یک متن برای تست می باشد. این یک متن برای تست می باشد. این یک متن برای تست می باشد. این یک متن برای تست می باشد. این یک متن برای تست می باشد. </p>
	<p>این یک متن برای تست می باشد. این یک متن برای تست می باشد. این یک متن برای تست می باشد. این یک متن برای تست می باشد. این یک متن برای تست می باشد. این یک متن برای تست می باشد. این یک متن برای تست می باشد. این یک متن برای تست می باشد. این یک متن برای تست می باشد. این یک متن برای تست می باشد. این یک متن برای تست می باشد. این یک متن برای تست می باشد. </p>
	<hr>
	<div class="more-post"><a href="#" title="درباره این مطلب بیشتر بخوانید">ادامه مطلب</a></div>
    </div>
     
	 <!-- مطلب شماره 2 -->
	<div class="mypost">
    <h2><a href="#" title="مطلب شماره 2">مطلب شماره 2</a></h2>
    <h5>این مطلب توسط فری لرن در تاریخ 1399/01/17 نوشته شده است</h5>
	<hr>
    <div class="img-post">
	 <img src="img/img-post-2.jpg"> 
	</div>
    <p>این یک متن برای تست می باشد. این یک متن برای تست می باشد. این یک متن برای تست می باشد. این یک متن برای تست می باشد. این یک متن برای تست می باشد. این یک متن برای تست می باشد. این یک متن برای تست می باشد. این یک متن برای تست می باشد. این یک متن برای تست می باشد. این یک متن برای تست می باشد. این یک متن برای تست می باشد. این یک متن برای تست می باشد. </p>
	<p>این یک متن برای تست می باشد. این یک متن برای تست می باشد. این یک متن برای تست می باشد. این یک متن برای تست می باشد. این یک متن برای تست می باشد. این یک متن برای تست می باشد. این یک متن برای تست می باشد. این یک متن برای تست می باشد. این یک متن برای تست می باشد. این یک متن برای تست می باشد. این یک متن برای تست می باشد. این یک متن برای تست می باشد. </p>
	<div class="more-post"><a href="#" title="درباره این مطلب بیشتر بخوانید">ادامه مطلب</a></div>
    </div>
	
</div>
</div>

<!-- فوتر سایت -->
<div class="footer">
  <p>این یک قالب ساده می باشد که طرح بندیش توسط تگ DIV انجام شده. [ <a href="https://free-learn.ir/" target="_blank" title="سایت آموزشی فری لرن">فری لرن</a> ]</p>
</div>

<!-- برای واکنش گرایی منو در گوشی های موبایل -->
<script>
function mymenumobile() {
  var x = document.getElementById("myTopnav");
  if (x.className === "navbar") {
    x.className += " responsive";
  } else {
    x.className = "navbar";
  }
}
</script>

</body>
</html>
