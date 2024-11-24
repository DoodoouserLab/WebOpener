# WebOpener

## What is WebOpener?

WebOpener is a bookmarklet that opens web pages via about:blank cloaking.

## How to Use

To change the site, change the string for the variable "url." You can either go to the file with the code or copy it from here. Run the code in a html compiler and click on the button that shows up. It will take you to a webpage with a url "about:blank" that will hide the site's actual url. The default url is a proxy.
```html
<!-- Created by DoodoouserLab -->

<html>

<head>
</head>

<body>
 <button onclick="openSite()">Biology Resources</button>
 <script>
   function openSite() {
var win = window.open()
var url = "https://im-in-the-thick-of-it-everybody-knows.dynorex.com"
var iframe = win.document.createElement('iframe')
iframe.style.width = "100%";
iframe.style.height = "100%";
iframe.style.border = "none";
iframe.src = url
win.document.body.appendChild(iframe)
}
 </script>
</body>

</html>
```
