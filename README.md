# Prime Player for Google Play Music

### Description

This is the repository for the Chrome extension for Google Play Music.
It is based on ideas of the extension "Better Music For Google Music".

Features include:

* last.fm integration (now playing, scrobbling, like/unlike)
* a powerful miniplayer with different layouts and color schemes
* toast notifications
* support for thumbs and 5-star ratings
* and more

You can install it from [here] (https://chrome.google.com/webstore/detail/prime-player-for-google-p/npngaakpdgeaajbnidkkginekmnaejbi).

### Notes for contributers

If you find any bugs or would like to see new features, please file an issue here on GitHub or - even better - send a pull request.
Please use the "develop" branch for contributing, as I use [git-flow](http://nvie.com/posts/a-successful-git-branching-model/)
(I know, that's pushing it a bit, but I try to learn sth. on developing this).

You'll need [Gulp](http://gulpjs.com/) for development. If you have [node.js](http://nodejs.org/) installed, just run setup.sh to install Gulp with all required plugins.
Afterwards you can execute `gulp watch` in the Prime player root directory to let Gulp watch for changes and automatically recompile artifacts (CSS/JS) as needed.

### License

(The BSD license)

Copyright (c) 2014, Sven Ackermann (svenrecknagel@googlemail.com)

All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

* Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.
* Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
