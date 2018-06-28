# Remote-Control-Presentation-using-NodeJS-Socket.-io-Reveal.JS-
## Control your presentation with smartphone

Wouldn't be awesome to control your presentation's slides with your smart-phone swipes. 
With NodeJS and Socket.io we can achieve this easily. 
The concept is very simple. We will use Reveal.js Api to make our slide show. Reveal.js puts every slide number in URL with hashtag e.g. http://slide.com/#/1 , we will send this URL to every connected user and when they swipe URL will reflect and slide will change. We will use a pass code to connect with this URL(establish socket connection).
Here is a tutorial on this project https://tutorialzine.com/2015/02/smartphone-remote-control-for-presentations
