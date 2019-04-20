## Examples

[![Demo 1](https://cloud.githubusercontent.com/assets/398893/3709347/ec72876c-1453-11e4-8450-149d06d487f2.jpg)](http://trackingjs.com/examples/face_tag_friends.html)
[![Demo 2](https://cloud.githubusercontent.com/assets/398893/3709357/1a1c2e16-1454-11e4-804d-e6ada6c65997.jpg)](http://trackingjs.com/examples/face_fish_tank.html)
[![Demo 3](https://cloud.githubusercontent.com/assets/398893/3709361/38f86e8a-1454-11e4-811d-52bd21b37e85.jpg)](http://trackingjs.com/examples/color_hexgl.html)
[![Demo 4](https://cloud.githubusercontent.com/assets/398893/3709464/5447a302-1456-11e4-96b2-d2fae28e2a01.jpg)](http://trackingjs.com/examples/color_draw_something.html)
[![Demo 5](https://cloud.githubusercontent.com/assets/398893/3709469/6a3e859a-1456-11e4-982a-d46a55890e1e.jpg)](http://trackingjs.com/examples/color_fish_tank.html)

## Features

* [Trackers](http://trackingjs.com/docs.html#trackers)
  * [Color Tracker](http://trackingjs.com/docs.html#color-tracker)
  * [Object Tracker](http://trackingjs.com/docs.html#object-tracker)
* [Utilities](http://trackingjs.com/docs.html#utilities)
  * [Feature Detection (Fast)](http://trackingjs.com/docs.html#feature-detection)
  * [Feature Descriptor (Brief)](http://trackingjs.com/docs.html#feature-descriptor)
  * [Convolution](http://trackingjs.com/docs.html#convolution)
  * [Gray Scale](http://trackingjs.com/docs.html#gray-scale)
  * [Image Blur](http://trackingjs.com/docs.html#image-blur)
  * [Integral Image](http://trackingjs.com/docs.html#integral-image)
  * [Sobel](http://trackingjs.com/docs.html#sobel)
  * [Viola Jones](http://trackingjs.com/docs.html#viola-jones)
* [Web Components](http://trackingjs.com/docs.html#web-components)
  * [Color Element](http://trackingjs.com/docs.html#color-element)
  * [Object Element](http://trackingjs.com/docs.html#object-element)
  # mediaLab4

This lab aims to build your first WebRTC app.

There are many open source alternatives to build a simple communication application like Skype. One of the web based solution is WebRTC. You can try a huge set of examples: 
https://webrtc.github.io/samples/

# Requirements for repository
  - You have to clone this repository and make two branches (master and develop).
  - The develop branch should contain commits of every new feature of the AR application.
  - When all features will be ready you have to merge the development branch to the master.

# Requirements for WebRTC application
There are three options to choose from. 

Option A:
  - Use WebRTC filter application code (https://github.com/webrtc/samples/tree/gh-pages/src/content/getusermedia/filter) and additional filter like Canny Edge filter or any other non existing in the sample.
  - It is also needed to add a slider to control a threshold/gain for your filter. It should work realtime.  

Option B:
  - Use WebRTC filter application code (https://github.com/webrtc/samples/tree/gh-pages/src/content/getusermedia/filter) and add face detector. Tracking.js is good place to start (https://trackingjs.com/examples/face_camera.html).

Option C:
  - It is your chance to show your skills and creativity.
  - You can add extra features to existing WebRTC examples.
  - Or anything other.
  
The general requirements for option A, B & C:
  - Test application on at least two browsers and specify in README.md which version and browser it was.
  - To pass this lab, you have to fully complete an option.  
  
# Important notes
  - SSL server is needed to run this lab material.
  - You will be needed to generate self signed sertificate and set up your web server. 
You can try to use these file servers:  
  - Apache: https://www.raspberrypi.org/documentation/remote-access/web-server/apache.md 
  - Tomcat: http://androidsrc.net/installing-tomcat8-raspberry-pi-3/ 
  - HFS: http://www.rejetto.com/hfs/ or any other server.
Proxy http to https:
  - https://technique.arscenic.org/lamp-linux-apache-mysql-php/apache-le-serveur-http/modules-complementaires/article/installer-et-configurer-le-module-ssl-pour-apache2?fbclid=IwAR1_nXNQlrMIdJ5tilVUyr45xeiA91yw21vhnMxWHnuvY01VTd2FVR_T2ao  