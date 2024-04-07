**Course CSE-362(Computer Networking Lab) Project submitted by**: Ananta Akash Podder(2016331102)

Summary:
------------------------------------------------------------------------------------------------------------------------------
P2P App Messenger is an instant messaging Android app that is built using Java socket. Anyone using this app must provide
their IP address and socket address to chat with each other. Only 2 person will be able to chat using this app using a socket.
They can exchange messages and files through this app. Custom app theme and custom buttons are provided which gives a new look
to this application.

**ScreenShots:**

![a](https://user-images.githubusercontent.com/49761339/137983578-b0d60336-fd1d-48e7-81e4-cfd29d5fbc1b.png)
![b](https://user-images.githubusercontent.com/49761339/137983589-f963d310-f84a-4e19-ae60-cdb4945bf1ff.png)
![c](https://user-images.githubusercontent.com/49761339/137983607-372ef023-b6ac-41f4-8589-075b858224f3.png)
![d](https://user-images.githubusercontent.com/49761339/137983620-75f9022f-95cc-4c4f-aa09-d271c54436c8.png)


Tech Stack:
------------------------------------------------------------------------------------------------------------------------------
Frontend: XML
Backend: Java
Platform: Android Studio


Features
---------------------------------------------------------------------------------------------------------------------------



Basic Features
...........................

1) Basic Text Messaging GUI
2) Background change option using a custom designed button
3) Saving chat option using a custom designed button
4) Sending Text file option using a custom designed button




Additional Extra features
...............................

1) "Voice recognition" to chat.
2) Splash Screen pops up during app bootload.
3) Chat view colors can also be changed.
4) Scroll view, one can easily scroll through previous messages that goes out of the window
5) "HOST IP address" of the device running the app, will be shown when Start Server is pressed
6) "Clear Text button" to clear text on chat history window of the user who pressed it.
7) Emoji sent option through message.
8) "Sound" option when file is sent.
9) "Text" can easily be copied from the chat box.
 




How the app works!
--------------------------------------------------------------------------------------------------------------------------
1) After opening the app a Splash screen will be shown for 3 seconds
2) After the Splash Screen, main interface of the app will come where the user should input port address of server, 
   IP address and Port address of another user at the other end and a Menu bar.
3) "Start Server" has to be clicked first to create a "Server".
4) After "Start Server" is clicked "Host IP Address" is auto-generated by the Application
5) Then "Target IP address" and "Targeted Port Number" must be enter to "Establish" between the two peers.
6) After each successful connection a Toast message will be shown on the screen.
7) A scrollview chat window will open where messaging between two party can be done.
8) Messages can be send using Send button
9) Text files can be send using Send File
10) Files will be saved inside root directory of the Android device in the same name.
11) Chat can be saved using the Save button
12) Background image can be changed by selecting different options from Menu bar.
13) Chat Colors can also be changed by selecting different options from Menu bar.
14) Clear Chat button to clear the chat. If this button is pressed then only the chat window of the user pressed it		
    will be cleared.
15) Chat view color can be changed by selecting differnt options from Menu.
