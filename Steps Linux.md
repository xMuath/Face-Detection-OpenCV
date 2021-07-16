#The steps to running Open CV and make a Face detection program (Linux Ubuntu/Mint OS)


Step 1: open your terminal you can do that by pressing (Ctrl+Shift+T).

Step 2: Now we are going to install Python 3.9 which is the programming language we use for the OpenCV library.

  Update and Refresh Repository Lists:
```
$ sudo apt update
```
  Install Supporting Software:
```
$ sudo apt install software-properties-common
```
  Add Deadsnakes PPA:
  ```
$ sudo add-apt-repository ppa:deadsnakes/ppa
$ sudo apt update
```
  Install Python 3:
  ```
$ sudo apt install python 3.9
```
  Allow the process to complete and verify the Python version was installed sucessfully:
```
python --version
```
you should see Python 3.9.x as the result.


Step 4: Install the openCV library.
Install PIP3
```
$ sudo apt update
$ sudo apt install python3-pip
```
To install OpenCV Via PIP give the following command
```
$ pip install opencv-python
```
Test OpenCV Installation
```
$ python3
 import cv2
 print(cv2.__version__)
'4.0.0'
```


Step 3: You need to install an Environment to run the python code there are alot of Environment but for this we will use Microsoft VS code you can download it from the link [here](https://code.visualstudio.com/download).

Step 4: Create a Project using VScode and download this face detection script file and put it inside your project folder you can download it from [Here](https://github.com/xMuath/Face-Detection-OpenCV/blob/main/haarcascade_frontalface_default.xml)

Step 5: Put this code as your main code in VS code [The code](https://github.com/xMuath/Face-Detection-OpenCV/blob/main/Detectfaceimg.py).

Step 6: Put a test picture that has faces inside the folder and rename it to 'test.jpg' 

or you can not rename it and change the python code
this is an included code in the main code in step 5.
```
img = cv2.imread('test.jpg')
```
as you see in the code above you can change the test.jpg to your picture's name.






