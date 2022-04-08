# TeleMedicine-Web-App

## Optometry Exam App

### Exams coordinated with a Medical Professional
 
Uses OpenCV and Python to simulate Snellen Eye Exam and Visual test for Eye Movement and focus

* Visual Eye Movement Test utilizes OpenCv and webcam feed to compute pupil coordinates on screen
  * Shows Custom video to capture basic eye movements
  * Generates coordinates of Left and Right pupil every 10 ms
  * If valid appends to list during exam
  * Returns generated figure of X and Y coordinates of Left and Right Eye approximate to video play length 

 ![alt-text-1](https://user-images.githubusercontent.com/25168061/124337428-664ea580-db57-11eb-91a2-65ad4f0b2098.png)
 ![image](https://user-images.githubusercontent.com/25168061/124337568-191f0380-db58-11eb-9fea-b096defc9d37.png)

Scatter plot made with list generated from webcam feed
  * Used for medical professionals to diagnose more accurately 
  * Horizontal and Vertical positions used in the X axis to determine difference in change 
  * Time used in Y axis to show difference in position in regards to time

![image](https://user-images.githubusercontent.com/25168061/124336879-cdb72600-db54-11eb-9b8b-bc77bd909559.png)

* Snellen Eye Exam 
  * Uses conventional eye exam with randomly generated letters from a curated letter pool shown to increase accuracy
  * Follows the Traditionals exam guidelines for calculating test restrictions:https://www.teachingvisuallyimpaired.com/print-comparisons.html
  * Returns List of errors made at every layer of Snellen Exam  



![image](https://user-images.githubusercontent.com/25168061/124336933-fb9c6a80-db54-11eb-8d69-056e1ba7c797.png)
