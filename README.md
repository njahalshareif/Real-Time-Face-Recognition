# Real-Time-Face-Recognition
Real-time Face Recognition by OpenCV &amp; python

***Note: You should have Python3.8 and Visual studio code installed first***.

#### 1. install Python 3.8.3 Check Add Python 3.8 to PATH
#### 2. Downloaded Visual Studio with Python Development package, Node.JS, Desktop web c++
#### 3. Open windows Powershell

$ cd .\Desktop\

$ mkdir facerecog

$ cd .\facerecog\

$ git clone git://github.com/ageitgey/face_recognition

$ pip install virtualenv

$ virtualevn env

***Note : "env" is the name of your virtualevn***

#### activite the virtualevn

$ cd .\env\

$ cd .\Scripts\

$ cd .\activate\

***Error : PowerShell says “execution of scripts is disabled on this system.”*** when I run activate

Solution : As an Administrator, you can set the execution policy by typing this into your PowerShell window:

$ Set-ExecutionPolicy RemoteSigned 

For more information, see Using the Set-ExecutionPolicy Cmdlet.

When you are done, you can set the policy back to its default value with:

$ Set-ExecutionPolicy Restricted 

You may see an error:

Access to the registry key 'HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\PowerShell\1\ShellIds\Microsoft.PowerShell' is denied. To change the execution policy for the default (LocalMachine) scope, start Windows PowerShell with the "Run as administrator" option. To change the execution policy for the current user, run "Set-ExecutionPolicy -Scope CurrentUser".

So you may need to run the command like this : $ Set-ExecutionPolicy RemoteSigned -Scope CurrentUser

$ cd..

$ cd..

$ ls

$ cd .\face_recogintion\

$ python setup.py install

$ pip install cmake

$ python setup.py install


Now you can run $ pip freeze to check that all dep installed

#### 4. Put photo in face_recogintion dirctory the face in photo it should be clear
#### 5. Open face_recogintion folder in visual studio
#### 6. create python file "fileName.py"
#### 7. run the following code



https://github.com/njahalshareif/Real-Time-Face-Recognition/blob/main/face_recognition_webcam.py


# Results :

#### Unknown

#### known
