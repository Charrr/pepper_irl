# irl_pepper_choregraphe
 Interacting with Pepper the robot with Choregraphe

## Instruction
1. Make sure the Choregraphe version is 2.5.5. [Link here.](https://www.softbankrobotics.com/emea/en/support/pepper-naoqi-2-9/downloads-softwares/former-versions?os=45&category=98)
2. Open the .pml file to open the project.
3. Connect to the robot.
    - Make sure the robot and the PC are under the same network.
    - If you connect to a virtual robot, note that the speech recognition is not supported.
4. On the left there are many behavior folders. The main program is in folder *behavior_main*.
    - Open the folder *behavior_main*, then the file *behavior.xar*.
5. Run the program by hitting the green play button at the top.

<div><img src="src/choregraphe-screenshot-1.png" align=center /><div/>

## Dialog walkthrough

---INTRO--- <br>
🧑 Human: Hi Pepper, can you **help me**? <br>
🤖 Pepper: Hello, of course. How can I help you today?  <span style="color:grey"> // Pepper recognizes the phrase "help me" </span> <br>
🧑 Human: WoW, is super busy today ... <br>

---WALK--- <br>
🧑 Human: **Walk** with me, Pepper. <br>
🤖 Pepper: (Walk forwards)  <span style="color:grey"> // Pepper recognizes the word "walk" </span> <br>

---OUTRO--- <br>
... <br>
🧑 Human: Which shoes fit well together with the dress, **coat and trousers** I chose? <br>
🤖 Pepper: Mmm. I am afraid, I cannot help you with this. Let me call an expert for help.  <span style="color:grey"> // Pepper recognizes the phrase "coat and trousers" </span> <br>


## Customize the behavior
There are certain parameters that you can change in the diagram according to your wish. <br>

1. The words that trigger Pepper's recognition: <br>
    On each SpeechRecognition box, click the wrench icon at the bottom left. There you can input the words that you want Pepper to recognize. (use semicolon to separate single words)
2. The texts that Pepper says: <br>
    Directly edit in the TextEdit boxs. 
3. The trajectory that Pepper walks: <br>
    On the MoveTo box, click the wrench icon. There you can edit how far you want Pepper to move. (x being the forward direction, y the perpendicular)
4. The short interval before Pepper speaks: <br>
    On the Wait box, click the wrench icon. There you can tune the length of the interval.
