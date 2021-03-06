Weather Fox [![Build Status](https://travis-ci.org/rishabhsrao/weather-fox.png)](https://travis-ci.org/rishabhsrao/weather-fox)
-----------

### Introduction

WeatherFox displays the current weather conditions for a given location.

Version: **0.0.1**

Developer: **[Rishabh Rao](http://rishabhsrao.github.com)**

License: **[Apache License 2.0](/rishabhsrao/weather-fox/blob/master/LICENSE.md)**

### Screenshots

<img src="http://rishabhsrao.github.io/img/posts/2013-03-10-weather-fox/4.jpg" height="240"/>
<img src="http://rishabhsrao.github.io/img/posts/2013-03-10-weather-fox/5.jpg" height="240" />
<img src="http://rishabhsrao.github.io/img/posts/2013-03-10-weather-fox/7.png" height="240" />
<img src="http://rishabhsrao.github.io/img/posts/2013-03-10-weather-fox/9.jpg" height="240" />
<img src="http://rishabhsrao.github.io/img/posts/2013-03-10-weather-fox/10.jpg" height="240" />

### Live app

* Your favourite web browser: [rishabhsrao.github.io/weather-fox/dist](http://rishabhsrao.github.io/weather-fox/dist) or [bit.ly/weatherfox-web](http://bit.ly/weatherfox-web)
* **Android**: [Download](http://rishabhsrao.github.com/images/posts/2013-03-10-weather-fox/WeatherFox-Android.apk) or [bit.ly/weatherfox-a](http://bit.ly/weatherfox-a)
* **Firefox Marketplace**: [marketplace.firefox.com/app/weatherfox](https://marketplace.firefox.com/app/weatherfox) or [bit.ly/weatherfox-fm](http://bit.ly/weatherfox-fm)
* **Windows Mobile**: [Download](http://rishabhsrao.github.io/images/posts/2013-03-10-weather-fox/WeatherFox-WinMob.xap) or [bit.ly/weather-wm](http://bit.ly/weather-wm)

### Technologies used

* KnockoutJS
* Yeoman.io
* RequireJS
* jQuery deferred
* HTML5 GeoLocation API
* Yahoo! Weather API via Yahoo! Query Language and Yahoo! Pipes (http://pipes.yahoo.com/pipes/pipe.info?_id=687279a3ea30ea78c978b1bf6e235055)

### Build instructions

This project's library dependencies are listed in [component.json](weather-fox/blob/master/component.json).

Just run `npm install && bower install` in the top level directory of this project to download the dependencies.

Once done, you can run `grunt server` to run locally or `grunt build` to generate a build.
