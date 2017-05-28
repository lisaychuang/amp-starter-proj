# AMP HTML boilerplate

<!doctype html>
<html amp>
<head>
  <meta charset="utf-8">
  <link rel="canonical" href="self.html" />
  <meta name="viewport" content="width=device-width,minimum-scale=1">

  <style amp-boilerplate>body{-webkit-animation:-amp-start 8s steps(1,end) 0s 1 normal both;-moz-animation:-amp-start 8s steps(1,end) 0s 1 normal both;-ms-animation:-amp-start 8s steps(1,end) 0s 1 normal both;animation:-amp-start 8s steps(1,end) 0s 1 normal both}@-webkit-keyframes -amp-start{from{visibility:hidden}to{visibility:visible}}@-moz-keyframes -amp-start{from{visibility:hidden}to{visibility:visible}}@-ms-keyframes -amp-start{from{visibility:hidden}to{visibility:visible}}@-o-keyframes -amp-start{from{visibility:hidden}to{visibility:visible}}@keyframes -amp-start{from{visibility:hidden}to{visibility:visible}}</style><noscript><style amp-boilerplate>body{-webkit-animation:none;-moz-animation:none;-ms-animation:none;animation:none}</style></noscript>

  <script async src="https://cdn.ampproject.org/v0.js"></script>
</head>
<body>Hello, AMP world.</body>
</html>


# AMP Custom style
<style amp-custom>
</style>

# AMP Custom Fonts
<link href="https://fonts.googleapis.com/css?family=Crimson+Text|Fredoka+One" rel="stylesheet">

font-family: 'Crimson Text', serif;
font-family: 'Fredoka One', cursive;

# AMP Custom Component Scripts:

<!--AMP Youtube video script-->
<script async custom-element="amp-youtube" src="https://cdn.ampproject.org/v0/amp-youtube-0.1.js"></script>
<!--AMP Lightbox script-->
<script async custom-element="amp-image-lightbox" src="https://cdn.ampproject.org/v0/amp-image-lightbox-0.1.js"></script>
<!--AMP Social Share script-->
<script async custom-element="amp-social-share" src="https://cdn.ampproject.org/v0/amp-social-share-0.1.js"></script>
<!--AMP Sidebar script-->
<script async custom-element="amp-sidebar" src="https://cdn.ampproject.org/v0/amp-sidebar-0.1.js"></script>


# AMP Sidebar
<!--Start AMP sidebar-->
<button on="tap:sidebar.toggle"
class="button-text menu">☰ Menu</button>

<amp-sidebar id='sidebar' layout='nodisplay' side="left" width="50vw">
    <button on="tap:sidebar.close" class="button-text">X</button>
    <h4>About</h4>
    <h4>Services</h4>
</amp-sidebar><!--End AMP sidebar-->


# AMP Youtube Player
 <!--Start AMP Youtube video player-->
<amp-youtube layout="responsive" 
    data-videoid="Wvt_K4LW29c"
    width=300
    height="250"
    autoplay>
</amp-youtube> <!--End AMP Youtube video player-->


# AMP image lightbox
<!--Star AMP img lightbox-->
<figure>
    <amp-img on="tap:lightbox1"
        role="button"
        tabindex="0"
        layout="responsive"
        src="http://placecorgi.com/300/250"
        width="400"
        height="350"
        alt="Picture of a corgi"
        title="Picture of a corgi, view in lightbox">
        <div fallback>offline</div>
    </amp-img>

<figcaption id="caption1">I'm a cute corgi!</figcaption><!-- Optional caption -->
</figure>

<amp-image-lightbox id="lightbox1" layout="nodisplay"></amp-image-lightbox>
<!--End AMP img lightbox-->


# AMP Social Share
 <!--Start AMP Social Buttons-->
<div class="social">
    <amp-social-share type="email"></amp-social-share>
    <amp-social-share type="facebook"
    data-param-app_id="254325784911610"></amp-social-share>
    <amp-social-share type="twitter"
    data-param-text="Check out this Corgi"></amp-social-share>
</div>
<!--End AMP Social Buttons-->