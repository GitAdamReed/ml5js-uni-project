# ml5js-uni-project

**IMPORTANT** <br>
Due to the CORS policy of most modern web-browsers, the images in this project will be blocked. To run correctly, you must install and run a server such as a WAMP server like Uniform Server. <br>

<a href="https://www.uniformserver.com/">Uniform Server Website</a><br>
<a href="https://sourceforge.net/projects/miniserver/">Uniform Server Download</a><br>

**Application Overview** <br>
This application classifies an unknown image of either a Jaguar or BMW by training itself with images
of the two car makes using the ml5.js library. Click the image you wish to classify, and the application
will train itself with all the other images that were not selected on the webpage. You may also want
to open the developer tools to see the operations in progress if you wish. The application trains itself
and does a classification attempt five times to increase the accuracy of the AI being able to classify
that image. The accuracy will be displayed at the top of the webpage. When the application is
finished running, you can select a different image to classify.
