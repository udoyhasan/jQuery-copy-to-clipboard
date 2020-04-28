# Introduction

Copy to clipborard is a simple jQuery plugin by Softisia. It is very simple to use. It helps to copy anything to clip board in a website. To use this plugin just download the codes file and get started. If you dont want to download it you can use our high speed cnd links to your website. In this way it will not waste your hosting space.

/--------------------------------------------------------------------------/
# Installation:
You can use this plugin in two ways =>
(1) By Downloading && (2)By using our high speed cdn link
/--------------------------------------------------------------------------/


## Connect plugin to site

### By downloading:
* Download the file and extract it
* Copy and paste js and css file to your destination folders
* Link the jQueary codes inside head or body tag (Depends on you) using a script tag .
  - <script src="yourpath/jQuery.js"></script>
  - <script src="yourpath/clipboard.min.js"></script>
  - <script src="yourpath/copyMessage.js"></script>
  Note: Follow this js script sequence
  
* Link the css insite the head tag (optional => if you want the stylish buttons)
  * &lt;link rel="stylesheet" href="yourpath/cp_btn_style.css"/&gt;

### By using our high speed cdn link
* Add this js script cdns inside body or head tag
  - <script src="https://cdn.softisia.com/github/copy-to-clipboard/js/jQuery.js"></script>
  - <script src="https://cdn.softisia.com/github/copy-to-clipboard/js/clipboard.min.js"></script>
  - <script src="https://cdn.softisia.com/github/copy-to-clipboard/js/copyMessage.js"></script>
  Note: Follow this js script sequence

* Link the css insite the head tag (optional => if you want the stylish buttons)
  * &lt;link rel="stylesheet" href="https://cdn.softisia.com/github/copy-to-clipboard/css/cp_btn_style.css"/&gt;
  
/--------------------------------------------------------------------------/

# Using plugin
To use this plugin use $(element).copyBtn() and $(element).copyItem();

Ex.
<input type="text">
<button>copy</button>

suppose you need to copy the text inside the input element by clicking the button element. So for that you need to add a script
Ex.
<pre>
<script>
  $(document).ready(function(){
	  $('button').copyBtn();
	  $('input').copyItem();
  });
</script>
</pre>

you can also use it by giving a class or id
Ex.
<input id="input-feild" type="text">
<button id="copy-btn">copy</button>
<script>
  $(document).ready(function(){
	  $('#input-feild').copyBtn();
	  $('#copy-btn').copyItem();
  });
</script>

#### You can do the same using a class name (ID and Class name are optional you can use any id and class name)

/--------------------------------------------------------------------------/

# Video tutorial
### Comming soon

/--------------------------------------------------------------------------/

## Support us by Donating. Your donation inspires us to do more for you 

/--------------------------------------------------------------------------/
