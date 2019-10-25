# Video Doorbell, Lab 7

*A lab report by Frans Fourie. Student*

### In This Report

1. Upload a video of your version of the camera lab to your lab Github repository
1. As usual, update your class Hub repository to add your [forked IDD-Fa18-Lab7](/FAR-Lab/IDD-Fa18-Lab7) repository.
1. Answer the questions in-line below on your README.md.

## Part A. HelloYou from the Raspberry Pi

[Hello You code Demo](https://youtu.be/UYng2GflEJw)<br />

## Part B. Web Camera

**a. Compare `helloYou/server.js` and `IDD-Fa18-Lab7/pictureServer.js`. What elements had to be added or changed to enable the web camera? (Hint: It might be good to know that there is a UNIX command called `diff` that compares files.)**

There are three main differences. Firstly the variables in the server.js file is initialized as constants whereas they are initialized as variables in the pictureServer.js file. Secondly the pictureServer.js file contains the unique variable NodeWebcam that is used to laod and start the webcam module. The NodeWebcam variable is also used to later in the code that takes the picture, names it, stores it and then sends it to clien.js to be displayed in the web server. The third difference is that pictureServer.js contains the functionality for the new button take picture that is used to tell the server to take a picture when pressed. The code to do this is the same as the code explained in difference number two.

**b. [Hello You code Demo with camera functionality added](https://youtu.be/GbRqAlS6LPA)<br />**

## Part C. Make it your own

**a. Find, install, and try out a node-based library and try to incorporate into your lab. Document your successes and failures (totally okay!) for your writeup. This will help others in class figure out cool new tools and capabilities.**

**b. [My doorbell camera with sound demo](https://youtu.be/dZsj-K6zsL8)<br />**
