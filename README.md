# CordovaJuerySwiper

User cordova@3.4.1-0.1.0, jquery and idangero swiper to create a simple page.
This page is modified from a demo of swiper.

> http://www.idangero.us/sliders/swiper/demos/main-demos/18-pull-to-refresh.html

The difference is the container and wrapper are contained in a page and that page has one header.

Mostly, the codes are just as the pull-to-refresh demo, the previous single index.html are split to www/index.html, www/css/index.js and www/js/index.js.

## launch it 

		cordova platform add ios
		cordova build ios
		open platforms/ios/HelloCordova.xcodeproj
		
Then, install it into your iOS7.1 simulator.
