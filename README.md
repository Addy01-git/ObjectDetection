# Guide to Real Time Object Detection

NOTE: Change the labels list in image collection according to your requirements and make sure the label map exactly matches the labels you create.

Step 1: Run the Image Collection jupyter notebook file to collect your images<br />
Step 2: Clone LabelImg from https://github.com/tzutalin/labelImg into teh TensorFlow directory<br />
Step 3: Install PyQt5 and lxml<br />
Step 4: Run the command 'pyrcc5 -o resources.py resources.qrc' from the labalImg directory<br />
Step 5: Move resources.py resources.qrc to the libs folder<br />
Step 6: Run python labelImg.py and label all the images<br />
Step 7: Run the training and testing jupyter notebook file<br />
