
# Face-2-Attend

<p align="center">
  <img src="https://user-images.githubusercontent.com/93596441/170276115-71567319-cfdd-4ad6-b489-7bba3eda9997.png"?raw=true" alt="Sublime's custom image"/>
</p>
Face-2-Attend is a Attendance recording system that works based on the profile Images of the recorded persons in the database. The face recognition process is live and the profile detail page will change If a new face has detected.
                                                                                                                                          
See the video demo here - https://www.youtube.com/watch?v=jz21Mj4T_m8
                                                                                                                                          
## Tech Stack                                                                                                                                           
#### Frontend: ```HTML,CSS,JAVASCRIPT```    
#### Backend:
* Language: ```Python```
* Framework: ```Django```                                                                                                                                         
* Database: ```SQLite```
* Libraries: ```face-recognition,face-recognition-models,numpy,opencv-python```                                                                                                                                         
## Features
* It can detect multiple faces at same time.
* It can detect faces in low light.
* It gives a Beep-Sound to ensure the attendance has been taken.                                                                                                                                          
## Application Setup Guidelines                                                                                                                                          
                                                                                                                                          
  1. Clone the project -                                                                                                                                        
  ```https://github.com/Proeditor07/Face2Attend-Ms-Engage-2022.git```
                                                                                                                                          
  2. Create the virtual environment - 
 </br>```py -3 -m venv env```                                                                                                                                            
  
  3. Activate the virtual environment -                                                                                                                               </br>```.\env\scripts\activate```           
                                                                                                                                        
                                                                                                                                          

                                                                                                                                          
  3. Install the dependencies -  
  ```pip install -r requirements.txt```                                                                                                                               
   
  ## Running on local server - 
   
  1. Make sure you have enabled the virtual environment and then type - 
    </br>```python manage.py runserver``` 
    </br>It will create the server and the site will be visible on the port ```http://127.0.0.1:8000/```     
                                                                                                                                                                                                                                                                             
## Errors 🛑
 If you get any error of dependencies like - dlib/numpy/opencv-python error, then you must have to install ```visual studio``` community on your machine</br>  
![Screenshot (39)](https://user-images.githubusercontent.com/73808096/170742475-4d8a8e5a-6d2b-454f-84d5-a64481b7a9a4.png)

                                                                                                                                          
After installing vs studio, Install the Marked options                                                                                                                          
              
 ![vs_interface_LI](https://user-images.githubusercontent.com/73808096/170742922-a8ce501a-c0d8-4d7d-a087-b619c6774c5b.jpg)
Your erros will be resolved ^_^

## Screenshots 📁                                                                                                                                          
**Home Page**
                                                                                                                                          
 ![Screenshot (40)](https://user-images.githubusercontent.com/73808096/170746440-63867f32-1b66-49e1-b617-d1d60ec485b8.png)
 
**Prfiles Section**
                                                                                                                                          
![Screenshot (43)](https://user-images.githubusercontent.com/73808096/170747763-4e225644-a2c6-47b0-b93c-a578a34155fd.png)

**Add New Profile**
 
![Screenshot (44)](https://user-images.githubusercontent.com/73808096/170748354-7ec0a249-eaf6-416e-9312-3b3cfabc749b.png)

**Scanning Page Before Detecting Any Face**
 
![Screenshot (41)](https://user-images.githubusercontent.com/73808096/170749106-cc3fb173-ab80-408f-8f08-57d2df1922e1.png)
                                                                                                                                          
**Detecting Faces**

![Screenshot (45)](https://user-images.githubusercontent.com/73808096/170749991-a93cd656-6cbf-49f6-94d7-2d4dfd462d85.png)

![Screenshot (46)](https://user-images.githubusercontent.com/73808096/170750137-09b490df-0c51-49c3-a096-5f247a6e44df.png)                                                                                                                                          
![Screenshot (47)](https://user-images.githubusercontent.com/73808096/170750217-eb1dd579-9245-4419-abf0-1dbb870eabe7.png)
                                                                                                                                         
![Screenshot (42)](https://user-images.githubusercontent.com/73808096/170750297-c26f5878-38b5-4d4d-b99d-c7bc918f18a6.png)
                                                                                                                                          
                                                                                                                                          
