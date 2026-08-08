All you have to do is:

1.AT FIRST download all the libraries (all necessary libraries starts in the code with "import" - for those who did not know)

2. After that just copy and paste this code into the visual studio, Python IDLE or PyCharm
  
3. Download the version of vosk model(That depends on which language you choose and which amount of the words you will use) in my example i use the small English model(that approximately 45M words).
   
4.Then you should download the audio of the voice assistant, copy the path of them and paste into the code.

5.Finally you have to run it and enjoy.

THAT'S FOR THE VERSION 1.0.

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



**For people, who lives in another countries:**

1. Find your index for pyttsx3 by running "For another language" code

2. Change the index in Melody's system code

3. ENJOY
