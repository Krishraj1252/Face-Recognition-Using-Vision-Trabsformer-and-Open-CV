# Face-Recognition-Using-Vision-Trabsformer-and-Open-CV
First make a Data Set Creator script :-  whenever the program capture the face will write that in folder . Before capturing the face we need to tell the scripts whose face it is. For that we need an identifier(ask from user for his/her User_Id ).Then it will capture face 200 times and write it in folder . 
After taking the snapshots it will save the User  info into the database.
For the database, used SqlLite3 Studio.
Train the recognizer :- For the trainer we need to extract the relative path where Data Set has been created. For the recognizer i used LBPH Face Recognizer Algorithm . Now if we run this code it will create a “ trainer.yml ” file inside the recognizer folder,We will use this file in our next post to actually recognize the faces that we trained the face recognizer to recognize.
Detector :- It will detect the user by fetching the data from the data base. If it match then its ok otherwise it will not detect it. 
