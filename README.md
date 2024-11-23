# WebOpener

Foobar is a Python library for dealing with word pluralization.

## What is WebOpener?

WebOpener is a bookmarklet to open web pages via about:blank cloaking.

## How to Use

You can either go to the file with the code or copy it from here. Run the code in a html compiler and click on the button that shows up.
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

## MIT License

Copyright (c) 2024 DoodoouserLabs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
