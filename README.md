# Analyze-Artist-Play-Frequencies-on-an-Online-Radio-Station-using-MySQL
Listeners have complained about certain artists being overplayed on Radio Calico. The aim of the project is to check if this is true and identify underplayed artists. A CSV file of the previous month's play logs should be loaded to MySQL to find top/bottom 20 artists based on avg. daily.
![image](https://user-images.githubusercontent.com/20522169/221932780-5ee15a3e-4b2b-4762-a85a-9382cfea9487.png)
![image](https://user-images.githubusercontent.com/20522169/221932891-2baf1bbe-48d8-40cf-afb7-d4f2a7e96522.png)

Delete any rows from the playlogs table that contain empty or missing artist fields.
![image](https://user-images.githubusercontent.com/20522169/222985651-96cc12d8-e96b-43a2-b54e-d0b473ad1dfe.png)

Calculate number of days since each artist was added to the playlist and number of times the artist has been played:
![image](https://user-images.githubusercontent.com/20522169/222985848-f22adf76-3ea6-431c-bafb-f9b2909e0ca1.png)

![image](https://user-images.githubusercontent.com/20522169/222986035-d33293d5-aff0-46d4-b549-10141f9d94ef.png)

![image](https://user-images.githubusercontent.com/20522169/222986116-23edbb59-52d2-4d8c-a31e-7215ad84178e.png)

Computing Top and bottom 20 artists with the help of average daily plays count:
Bottom 20:
![image](https://user-images.githubusercontent.com/20522169/222988961-b53add47-05e0-45a9-b93e-6bedc581d598.png)

Top 20:
![image](https://user-images.githubusercontent.com/20522169/222988987-8dbdec86-1a05-4264-9a84-8a001ec6e1fd.png)

