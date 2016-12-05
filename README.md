Bootstrap Carousel Touch Slider with slide text Animation
========================

Adding Touch behavior to Bootstrap's Carousel and add animation in text slide.

## Usage

Just include the library in your page and create the carousel components
normally, as described in the [official Bootstrap documentation](http://getbootstrap.com/javascript/#carousel).


```html
<!--css Add this in header-->
<head>
<link href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/3.3.7/css/bootstrap.min.css" rel="stylesheet" media="all">
<link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet" media="all">
<link href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/3.5.2/animate.min.css" rel="stylesheet" media="all">

<!-- Bootstrap bootstrap-touch-slider Slider Main Style Sheet -->
<link href="bootstrap-touch-slider.css" rel="stylesheet" media="all">
</head>


<body>
        

<!--Slide effect: slide, fade 
Text Align: slide_style_center, slide_style_left, slide_style_right
Add animation in text: https://daneden.github.io/animate.css/
 -->

<!-- Create carousels normally: http://getbootstrap.com/javascript/#carousel -->
<div id="bootstrap-touch-slider" class="carousel bs-slider fade  control-round indicators-line" data-ride="carousel">
  ...
</div>



<!-- Add this before end body tag -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/3.3.7/js/bootstrap.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery.touchswipe/1.6.18/jquery.touchSwipe.min.js"></script>
<script src="bootstrap-touch-slider.js"></script>

<script type="text/javascript">
    $('#bootstrap-touch-slider').bsTouchSlider();
</script>

</body>
```


Inititalization: No option available just add this.

```javascript
    $('#bootstrap-touch-slider').bsTouchSlider();
```



 Credits: Bootstrap, jQuery, TouchSwipe, Animate.css, FontAwesome
