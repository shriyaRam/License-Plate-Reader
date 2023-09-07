# License-Plate-Recognition

A number plate reading system built over the live stream environment of Agora.io

Download the weights.npz file from [here](https://drive.google.com/file/d/0B-MtVXQMUxQiZElfSy1ON09QQ0U/view?usp=sharing). and paste it to the main directory.This file contains a pretrained model. 

# Prerequisites
1. All python libraries given in requirements.txt
2. An Agora app-id 
3. Latest version of any text editor that supports python, preferably 'Sublime Text3'

# Guide to a Quick Start:
1. Create an agora.io account 
2. 
-  Sign-up and login [here](https://dashboard.agora.io).
-  Navigate to the 'project management' tab in the dashboard.
-  Create a new project with a name of your choice.
-  Procure the app-id by copying it onto your clipboard and pasting it somewhere accessible from where you will later access while           developing the code.

3. Install all the dependencies given in requirements.txt using:
   ## windows:
   ```bash
     pip install -r requirements.txt
   ```
   ## Linux:
    ```bash
      sudo pip install -r requirements.txt
   ```
4. Download a zip file of this repository

5. Download chromedriver.exe and weights.npz

6. Open detect.py in sublime or any compatible text editor of your choice.
  - paste the app-id and link to the chromedriver.exe as directed on line 20 of the code and a channel name on line 21.
  - paste the link to a high resolution(approx 2000x1500) image on line 30
  - give links to in.png on line 161 and weights.npz on line 164 as directed in the code.
  - give a link to out.png on line 194
  
7. Go [here](https://sidsharma27.github.io)
  - paste app-id and channel name in the respective input boxes  on sender and reciever side.
  - click on join to activate call on sender and receiver side.

8. Execute detect.py from the master folder on the terminal 

9. The desired result will be in out.png

There you go!
 
    
    

