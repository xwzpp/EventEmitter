# EventEmitter

## Event based JavaScript for the browser

As the subtitle suggests, this script brings the power of events from platforms such as [node.js](http://nodejs.org/) to your browser.

This is actually the forth full rewrite of EventEmitter, my aim is for it to be faster and lighter than ever before.

I have been working on it for over a year so far and in that time my skills in JavaScript have come a long way. This script is a culmination of my learning which you can hopefully find very useful.

## Testing

Tests are performed using Jasmine in the following browsers via [BrowserStack](http://www.browserstack.com/).

 * Firefox
 * Chrome
 * Opera
 * Safari
 * IE6+

When testing in the more modern browsers, not Internet Explorer basically, I run it through the very early versions, some midrange versions and the very latest ones too. I don't just do the latest version.

EventEmitter will always be tested and working perfectly in all of them before a release. I will not release anything I think is riddled with bugs. However, if you do spot one, please [submit it as an issue](https://github.com/Wolfy87/EventEmitter/issues) and I will get right on it.

## Cloning

You can clone the repository with your generic clone commands as a standalone repository or submodule.

    git clone git://github.com/Wolfy87/EventEmitter.git
    git submodule add git://github.com/Wolfy87/EventEmitter.git assets/js/EventEmitter

If you wish to run the tests you will also need to fetch the required submodules. You can do that with the following command.

    git submodule update --init

## License (MIT)

Copyright (c) 2012 Oliver Caldwell

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.