# Material Web  [![codebeat badge](https://codebeat.co/badges/6777a1ab-afc5-4dd5-8080-dfa8ecce21d3)](https://codebeat.co/projects/github-com-folgore95-materialweb-master) [![GitHub license](https://img.shields.io/github/license/mashape/apistatus.svg)](https://github.com/folgore95/materialweb/blob/master/LICENSE)
<img src="https://github.com/folgore95/media/blob/master/materialweb.png"/>

## About

Your personal Android app based on Google's material design.

## How does the app work?

The app needs an internet connection to work correctly because it uses the webview. The website will be cached in the app.
In this example i have used my personal website hosted on GitHub which follows the material design. You are free to fork it and design your copy. 

## Design the material page

Fork this <a href="https://github.com/folgore95/folgore95.github.io">repository</a> and rename it into `your-github-username.github.io` then start design your personal copy.

## Make the app

Download the project and after you have opened it in Android Studio open `MainActivity.java`. Now you need to change this line:
```xml
webview.loadUrl("https://folgore95.github.io");
```
into
```xml
webview.loadUrl("https://your-github-username.github.io");
```
After you have do that, open `colors.xml` which is located in `res/values` and change the app's colors to make them in line with the website colors.

## More

- <a href="https://developer.android.com/guide/webapps/webview.html">Android Developers - WebView</a>

## License

    MIT License

    Copyright (c) 2017 Giorgio Cantoni

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








