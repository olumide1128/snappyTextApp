# snappyTextApp
Snappy Text is an app which makes it easier and faster to transfer text from phone and back. It was developed using Python and it uses FTP server.

![screenshot--17- (1)](https://user-images.githubusercontent.com/59411943/131224523-a9ea8c79-cc80-42b3-a246-504d97f9aba3.jpg) ![Webp net-resizeimage](https://user-images.githubusercontent.com/59411943/131224585-917459f1-2a0c-4b67-8f65-3a10db95efa5.jpg)


***REQUIREMENTS***
----------------------------------------------------------

1. A Phone and a PC
2. Download WiFi FTP Server (I recommend the one by Medha Apps for it's simplicity).
3. A text editor for phone to write and edit text.



***INSTRUCTIONS***
----------------------------------------------------------

1. First connect your phone and pc to same network.You could create a hotspot with your phone and connect to pc

2. Open your WiFi FTP Server app. You would see something like this.

![Webp net-resizeimage](https://user-images.githubusercontent.com/59411943/131224951-d4bc7bbe-b580-4200-9271-34e1c0398a53.jpg)

3. Before Clicking Start, first go to settings at the top-left, a screen would pop up, click "Port Number" and set the port to 1200.
   (You only have to do this once).

![Webp net-resizeimage](https://user-images.githubusercontent.com/59411943/131225142-80709376-7094-4ad7-aa95-ba58517f457e.jpg)        ![Webp net-resizeimage](https://user-images.githubusercontent.com/59411943/131225256-9a390b61-42af-4833-b8ed-44f5de1771e4.jpg)

4. After that, click on "Root Folder" and select "Internal Memory". (You only have to do this once).

![Webp net-resizeimage](https://user-images.githubusercontent.com/59411943/131225220-3b5f5a88-e388-4dba-b0ec-217469e688c4.jpg)         ![Webp net-resizeimage](https://user-images.githubusercontent.com/59411943/131225292-4e7216bd-465f-464f-ba6f-6a5f59f8aec7.jpg)

5. Now, click Start to fire up your FTP Server. You would see something like this..(Your ip address would be different)

![Webp net-resizeimage](https://user-images.githubusercontent.com/59411943/131225000-9e80b06d-2b31-4db2-928c-d06239b982d3.jpg)

6. Now, go to your pc and run your 'snappyText' App. You should see this..

![Webp net-resizeimage](https://user-images.githubusercontent.com/59411943/131225384-efbc6026-7a70-42c7-b11a-fbffc1cfcf81.jpg)

7. Click on 'CONNECT FTP' and if everything goes well, you should see this..

![screenshot--1](https://user-images.githubusercontent.com/59411943/131225402-095507c5-7a6f-4417-81e7-a099e54642b7.jpg)


8. Now put any text in th textarea e.g "Hello" and click the 'SEND TEXT' Button. You get a successful message. This has created a txt
   file called 'serverFile.txt' in the directory >> root\\Documents.


9. Now, anytime you want to send a text from your phone to your pc, just connect your network, turn on your FTP server, put the
   text in the 'serverFile.txt' file found the 'root\\Documents' directory then go over to your pc, turn on 'snappyText' App 
   and click 'RECEIVE TEXT'. The text would display on the Textbox.
   
   
  
   Voila!!
   
   


