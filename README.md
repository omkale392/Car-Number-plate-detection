# Car-Number-Plates-Detection
This project is a practical application of computer vision techniques for the detection of car number plates using Python and OpenCV. It utilizes a Haar Cascade classifier to identify number plates in real-time through a webcam feed.

**Features:**
1) Real-time Detection: The system captures video from a webcam and processes the frames in real-time to detect car number plates.
2) Haar Cascade Classifier: Employs a pre-trained Haar Cascade classifier designed to detect Russian car number plates.
3) Image Processing: Converts frames to grayscale to simplify the detection process and improves the efficiency of the algorithm.
4) Graphical Annotations: Draws rectangles around detected number plates and labels them, enhancing the visual representation for the user.
5) ROI Extraction: Isolates the region of interest (ROI) for further processing or storage.
6) Save Functionality: Allows the user to save the detected number plate with a simple keypress, facilitating data collection.

**Usage:**
To use this project, run the number_plate.py script. Ensure your webcam is activated and correctly configured. Detected number plates will be displayed in a separate window, and you can press 's' to save the image of the detected plate.

**Requirements:**
Python 3.x
OpenCV library (opencv-python)
Make sure all dependencies are installed using requirements.txt:

*Copy code*
pip install -r requirements.txt

**Contribution:**
Contributions to the project are welcome! Please consider forking the repository, making your changes, and submitting a pull request.

**License:**
This project is licensed under the MIT License - see the LICENSE file for details.

**Acknowledgments:**
Thanks to the OpenCV community for providing the tools and documentation that made this project possible.
