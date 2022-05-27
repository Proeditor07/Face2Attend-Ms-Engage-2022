
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
 ```py -3 -m venv env```                                                                                                                                            
  
  3. Activate the virtual environment -                                                                                                                               ```.\env\scripts\activate```           
                                                                                                                                        
                                                                                                                                          

                                                                                                                                          
  3. Install the dependencies -  
  ```pip install -r requirements.txt```                                                                                                                               
   
  ## Running on local server - 
   
  1. Make sure you have enabled the virtual environment and then type - 

```python manage.py runserver``` 
   It will create the server and the site will be visible on the port ```121.0.0.80```                                                                                                                                            
                                                                                                                                          
🛑 If you get any error of dependencies like - dlib/numpy/opencv-python error, then you must to have installed ```visual studio``` on your machine  
