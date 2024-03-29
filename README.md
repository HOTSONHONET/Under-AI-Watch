## 💻👓 Under AI Watcher 👓💻

<p><i>Under AI Watcher is a platfrom that will help any web application or native applicaiton to leaverage SOTA deep learning models. It aims to aid the authority incharge in making the students disciplined in school environment. Also the prototype is not only limited to students but also it can detect anomalies or interdisciplinary activities in all public environments. It uses SOTA ML models like dlib, YOLO, Haarcasdes to carry to perform video suvillence</i></p>

## Tech Stack 📚
- Python
- Tensorflow
- Flask
- OpenCV

### Features ✨
- ML models capable of doing the following activities
  *   Classroom attendance system 
  *   Detects students using phone for texting in the classroom 
  *   Detects students feeling drowsy in the classroom 
  *   Detects students wearing a mask or not
  *   Detects gents entering ladies washroom and vice versa
  *   Detects students outside their classroom
  *   Detecting vandalism
- Easy 3rd party application integration, so that those apps can leverage the ML model capabilities
- Can be used to perform detection from live feed

### How to use 🤔?
*    Visit the GitHub repository and download the resources folder which is given as a link in the “README.md file. Clone the repository and copy the [Resources](https://drive.google.com/file/d/1UvMmEMvJBkdMExU416_9MRsLphdE52vx/view) folder inside the cloned folder. For cloning use the below command:  
```
https://github.com/HOTSONHONET/Under-AI-Watch.git
```

* 	Create a virtual environment and then install the required packages via the ‘’requirements.txt” file (Recommended). We can also opt for root installation.

```
pip install virtualenv
python -m virtualenv <name-of-the-virtual-env>
<name-of-the-virtual-env>/Scripts/activate
```
* 	Make sure your python version is above 3.6. Open the command prompt inside the clone directory and type in this command to the flask app:
```
py app.py
```
* 	You will be directed to the homepage. You will see a navigation bar containing  🏠**Home**, 📜**About**,  🚶🏼‍♀️**Get Started**,  ⛑**Help**. If you have any queries, click on the **Help** button.
* 	To analyze the video click on the **Get Started** button. This will redirect you to a page where you will see an upload bar. Simply drag and drop or video file from your local disk. There is a drop-down menu below the upload bar named “monitor activity” which shows the list of activities that you can monitor. After selecting the activity, click on the *Upload* button.
* 	The video analysis will take some time and you will be redirected to a download page. Please be patient and do not click on other options in the navigation bar during the process. 
 *   Simply click on the “download”  button. A video file will be downloaded with the name **Evidence.mp4**. If you want to analyze more videos, simply click on the “Get Started” button on the navigation bar.
 *    For ‘attendance monitoring’ one has to upload a video file along with images of students. Select “ClassRoom Attendance” in the dropdown menu. After clicking on the *Upload* button, you will be redirected to a new page where you have to upload a zip file. The zip file must contain distinct images of each student in a classroom with labels as their respective names. After clicking on the ‘submit’ button, you will be redirected to the download page where you can download the analyzed video along with the attendance sheet.

### UI layout :

- The UI basically represent any web application or native application that wants to levarage our SOTA deep learning model facility

<table>
  <tr>
    <td>About</td>
     <td>Home</td>
  </tr>
  <tr>
    <td><img src="https://user-images.githubusercontent.com/54463399/99926692-84a22680-2d68-11eb-8b9c-d1e6cbbd2105.jpeg" width=500 height=200></td>
    <td><img src="https://user-images.githubusercontent.com/54463399/99926742-b915e280-2d68-11eb-94a2-0728d75905bb.jpeg" width=500 height=200></td>
  </tr>
  <tr>
    <td>Get Started Page</td>
     <td>Download Page</td>
  </tr>
  <tr>
    <td><img src="https://user-images.githubusercontent.com/54463399/99926828-06924f80-2d69-11eb-963a-6dae3a5e414a.jpeg" width=500 height=200></td>
    <td><img src="https://user-images.githubusercontent.com/54463399/99926842-19a51f80-2d69-11eb-8ba4-0c3031c2a2aa.jpeg" width=500 height=200></td>
  </tr>
 </table>

### Working of ML models :

<table>
  <tr>
    <td>Drowsiness detection</td>
     <td>People roaming outside</td>
  </tr>
  <tr>
    <td><img src="https://user-images.githubusercontent.com/56304060/148547269-ea00d7fd-5c5b-4931-89c9-e14aff83827e.gif" width=500 height=200></td>
    <td><img src="https://user-images.githubusercontent.com/56304060/148547180-7d5b63aa-03b9-49c0-9902-2be5d7060f2c.gif" width=500 height=200></td>
  </tr>
  <tr>
    <td>Mask and unmask detection</td>
     <td>Vandalism detection</td>
  </tr>
  <tr>
    <td><img src="https://user-images.githubusercontent.com/56304060/148547020-6e1c86c4-7b97-4550-a205-20a8db295ec5.gif" width=500 height=200></td>
    <td><img src="https://user-images.githubusercontent.com/56304060/129045537-b1329a4e-32d7-4d5b-ad3c-8d84ada3af27.gif" width=500 height=200></td>
  </tr>
  <tr>
    <td>Classroom attendance</td>
     <td>Student Using phones</td>
  </tr>
  <tr>
    <td><img src="https://user-images.githubusercontent.com/56304060/148547494-fad9cc5a-7622-4217-aced-9bda8ab90e80.jpg" width=500 height=200></td>
    <td><img src="https://user-images.githubusercontent.com/56304060/148553504-8659983d-815e-45e2-8f70-733054d3ec33.gif" width=500 height=200></td>
  </tr>
 </table>


### Created by :
* Rudra Prasad Dash (https://github.com/HOTSONHONET/)
* Kumar Abhishek (https://github.com/white-beard)
