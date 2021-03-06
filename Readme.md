MusicEdge
------------------------
Author: @vhanla - Victor Alberto Gil 


Description:
-----------
MusicEdge is a lightweight Windows 10 (1803+) Music Desktop Player for
Google Play Music, SoundCloud and Jamendo.

It is based on Edge's WebView (edgehtml.dll) and it means, it doesn't require to use Chromium (big bunch of dll files) nor Electron in order to wrap Google Play Music.

I have also writtena GMusic player using embeddable Chromium engine, which was very big and had limitations on lincense for HTML5 audio so it relied on Flash Activex, not really beautiful.

So, this is a new web wrapper for the above mentioned WebApps, which doesn't include 120MB+ sized Chromium engine, on the contrary, as mentioned, it uses newest EdgeHTML WebView engine, which
comes included on Windows 10 (1803 or newer), so there is no need to include a big bunch of files, just the application which is less than 10MB.

![](https://lh3.googleusercontent.com/3zbz7pzsXrD69cSMPf_QGaTHg23Kawk02wz3dMEgkzXMj4ZP-Hd2LHBs5jjmFwbKUbaya3vLdfwYTg=w1366-h768-no)

_This was written as a proof of concept, using the new WebView from Microsoft Edge instead of Chromium neither IE11 old WebBrowser ActiveX._

Now it is a lightweight alternative to those "Desktop Players" for those services.


Features:
--------

- HTML5 audio 
- Native system notification (WebNotification, activate on settings and refresh)
- Custom Styles using minified CSS files (don't use quote symbols)
- Media Key controls
- Small program
- Portable

Requirements:
------------

- Windows 10, version 1803 or newer

Changelog:
---------
- 2019-05-29
  [TODO]: Added support for SoundCloud and Jamendo web apps.
- 2019-05-13
  Updated to newer Microsoft.Toolkit.Wpf.UI.Controls.WebView
- 2018-05-09:
  Written from scratch 
  
  
No affiliation with Alphabet's Google. Google Play is a trademark of Alphabet Google Inc.  
  
License:
-------

The MIT License (MIT)

Copyright (c) 2011 Victor Alberto Gil

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.