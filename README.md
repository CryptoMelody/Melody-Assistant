All you have to do is:

1.AT FIRST download all the libraries (all necessary libraries starts in the code with "import" - for those who did not know)

2. After that just copy and paste this code into the visual studio, Python IDLE or PyCharm
  
3. Download the version of vosk model(That depends on which language you choose and which amount of the words you will use) in my example i use the small English model(that approximately 45M words).
   
4.Then you should download the audio of the voice assistant, copy the path of them and paste into the code.

5.Finally you have to run it and enjoy.


ALL AUDIO IN THIS CODE IS ON RUSSIAN LANGUAGE!!! JUST REMEMBER THAT!

YOU CAN RECORD YOUR OWN VOICE WITH THE VOICEMOD: https://www.voicemod.net/


IF YOU TRY TO SPEAK ON ANOTHER LANGUAGE THE VOICE RECOGNITION TEXT YOU SOME RANDOM WORDS:


![photo_2025-11-16_23-19-23](https://github.com/user-attachments/assets/1c66a2f2-1341-42a6-b748-8ea7962781f0)

THE COMMAND IS ONLY ON ENDLISH BECAUSE VISUAL STUDIO ON MY COMPUTER DOESN'T SUPPORT RUSSIAN LANGUAGE AND I RECIEVE THIS KIND OF THE MESSAGE FROM CONSOLE:


***SyntaxError: (unicode error) 'utf-8' codec can't decode byte 0xe2 in position 0: invalid continuation byte***


THIS LINES IN THE CODE RESPONSIBLE FOR REMOVING THE FIRST LETTERS AND SPACES:

**elif command_lower.startswith('search'):**

**p = command[6:].strip()** #IN THIS EXAMPLE WE REMOVE "search"

search - 6 letters, so that's why to remove this all word we have to write: **command[6:].strip()****


***FOR ESP32.ino code(connection):***

**First connection** for those who just wanna check the work of the server: 

<img width="801" height="743" alt="Снимок экрана (120)" src="https://github.com/user-attachments/assets/82787dc7-4225-4f93-b291-b8973d8986b2" />

**The second one** is for those who can connect some different devices and control them in distance: 

<img width="1174" height="611" alt="Снимок экрана (121)" src="https://github.com/user-attachments/assets/8e5120ae-bb26-489f-8a4a-8eb08dc8d899" />




**For people, who lives in another countries:**

1. Find your index for pyttsx3 by running "For another language" code

2. Change the index in Melody's system code

3. ENJOY


***BE CAREFUL WITH THE VOICEBOX, CAUSE IT CAN BE UNFRIENDLY FOR YOUR CPU:***

<img width="762" height="472" alt="1" src="https://github.com/user-attachments/assets/bddfb50b-ef81-4d79-b0fb-eb7c578fbb8f" />
