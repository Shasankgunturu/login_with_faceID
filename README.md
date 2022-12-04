# login_with_faceID
This code mainly uses python modules openCV, face_regocnition, and pandas. 
It provides the user, the following options:
  - Login through faceID
  - login through Password
  - check all the entries so far 
  
It keeps a track of all the people that logged in so far in a csv file and displays if you enter the admin password.
The faceID recognition uses the webcam to get the face of the person trying to login and then, it compares the image of the person trying to 
  login with the list of already encoded faces.
