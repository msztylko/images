# Images

The aim of this short project is to get familiar with OpenCV library and using Python for image manipulation. I'm going to create a timelapse of me working recorded with my computer camera. Let's see how it works out!

 *Update 29/08/2019*
 
My initial plan was to do face detection using Haar Cascades, but it doesn't seem to work very well. This solution highly depends on the position of my head and I decided to use tools from dlib library. However, I have problems with installing this library on Windows 10 and I'll probably spent the rest of this day trying to make it work...

Dlib 19.17.0 finally installed  after downloading VSC with CMake and C++ compilers.

 *Update 30/08/2019*
 
 I created my version of gif generator based on https://www.makeartwithpython.com/blog/deal-with-it-generator-face-recognition/
 This code seems to work better than Haar Cascades for face detection, so my plan is to make it work with the webcam in real time, then add mustache and finally prepare a timelapse.
 
<p align="center">
<img src="https://github.com/msztylko/images/blob/master/deal.gif" data-canonical- width="200" height="300" align="center" />
</p>
