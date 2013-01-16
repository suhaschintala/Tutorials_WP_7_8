Tutorials_WP_7_8
================

Tutorials on building Windows Phone 7 and 8 apps using App42 API and AppWarp.


SETUP OF PROJECT FOR WP7 AND WP8:

1. App HQ sign in on https://apphq.shephertz.com( Join with your account or sign up for new account). 


2. Now create app (appwarp) on this website by clicking on Create App button. You will get  API_KEY and SECRET_KEY. Provide API_KEY and SECRET_KEY obtained in GlobalContext.cs file


3. Create room and get its room id at same place. Provide Room ID obtained in GlobalContext.cs file of downloaded project.
Note: While creating room for tic tac toe specify max user as 2


4. Open solution file in VisualStudio 2k10(For Win7 Phone) or 2k12 (For Win8 Phone)
a. To run in emulator just Run the project or click on debug in IDE . We Can run 2 instances on a single machine
   or one instance on one machine and other on differnt OS machine or even on different Window Mobile Phone.
b. To Run it on Window 7 or Window 8 phone use TicTacToeAppWarp.xap file with Zune software to Install game . File will be obtained after building solution in following folder- 
   (Tutorials_WP_7_8\TicTacToeAppWarp\Bin\Debug).


5. How to play the game.
a. Once one user Join the game by entering his name and clicking on join it will wait till secvond user join
b. Once Second user will join first user will get message for his move and second player will have to wait till first player move and game proceed with alternate
   moves
c. User clicking on new gtame button before game completion will lose game and new game will be initialized.
d. User clicking on end game button before game completion will lose game and other user will get notification of it


6. Blocked Zipped file issue
a. If downloaded files are in zip format sometimes we need to unblock it before Unzipping it (by clicking on zipped file and then clicking on property we will get Unblock checkbox).






 
