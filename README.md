# myrepo
This project is on Optical Character Recognition(ORC) using Computer Vision

Character detection is done which extracts printed text from an image
The code uses OpenCV and tesseract modules to process the image hence both the modules will be imported.

Since pytesseract can only accept the images in RGB format, 
the image under test is converted to RGB from BGR format.

Charaters are recognised using enumerate 
Then a rectangle is created around the characters for indication
Once the characters are recognised they are converted to text and added above the rectangles
