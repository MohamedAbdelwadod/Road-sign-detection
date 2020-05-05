# Road-sign-detection
simple algoritm for detecting road signs using opencv


This project is a seed for a high-speed algorithm for detecting and recognizing street sign using opnecv library.
This would be very useful for real-time computer vision application, as the algorithm isn’t from deep learning category that need huge computational power, so it would be computationally inexpensive to cars CPU.
The algorithm is basically find circular areas using  Hough transform, then inspecting multiple areas inside every circle found by Hough transform.
Every street sign has a distinguished spatial distribution, this distribution has been inspected for 6 different signs , tested successfully with an acceptable performance for real-time video.
