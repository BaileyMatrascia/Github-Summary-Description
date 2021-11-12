# Github-Summary-Description
A description of git summary and how it differs from git log and aids CSE




##git log
![image](https://user-images.githubusercontent.com/46755902/141370148-2b275b3a-ae84-4e48-b56c-76f2c685929a.png)
### When a user ustilizes git log, it prints out the commit ID, the author of the commit, and the date and time of the commit




##git log --raw
![image](https://user-images.githubusercontent.com/46755902/141370209-41c4e5b1-52d4-4647-9cab-59fc93504655.png)
### When a user adds on the --raw extension to the git log command it also tells the user which file was added to the commit and how. So A = added, M = Modified, R = Renamed, and D = Deleted and it




##git log --patch
![image](https://user-images.githubusercontent.com/46755902/141370248-7f2a3fd8-e506-4eb0-82e7-1fbee4d7aad5.png)
### When a user adds on the --patch extension to the git log command, it tells the user what was specifically changed in a file as shown towards the bottom of the terminal in the picture.




##git summary
![image](https://user-images.githubusercontent.com/46755902/141372675-d67c2bb3-80be-4d1a-864d-c8405b4e8481.png)
### When a user uses one simple command, git summary will output and entire summary for the day that will include the date, number of the amount of commits included in this particular summary, and all of the above information and more as it will include the actual commit message associated with the corresponding commit and lines of code that the code change is in that will be able to give the user context around what was specifically changed in the code with highlights of the specific line number and text change. 



## Differences

### What makes git summary different from git log is that with git log you must type in muiltiple commands in order to gather all of the data that git summary provides and even then, you do not get the commit message nor actual code from the file that shows the entire line or surrounding code and lines. Git summary as well will provide a cleaner interface that is more visually appealing and easy to read and provides a header at the top of the summary to provide the user with how many commits are included in the summary so user can quickly know how long the summary is or in short, how many changes were implemented.

## CSE 

### CSE is a software engineering approach that includes shorter iteration cycles with numerous continuous processes made continuous centerd around the principle of continuous improvement. As a result of CSE, higher quality software is created in a shorter amount of time. In order for a higher quality software to be created in a shorter amount of time, these shorter iteration cycles combined with continuous improvement must be undercontrol and organized so continuous improvement and these continuous processes can be executed efficiently. 

### git summary is more sufficient for CSE and helps aid CSE better than git log. CSE is all about "trimming the fat" and making constant edits to code to make the code the best it can possibly be. With git summary, the user is provided with muiltiple lines of code surrounding the specific change as opposed to git log which only provides the specific words added and deleted. So if a user only adds or moves around a word, git log is only displaying that word and showing it was added to the file, however due to the types of improvement edits and changes made through continuous improvement in CSE, that single word change is not enough and does not give clues on maybe why that change was implemented. These muiltiple lines of code and the specific line numbers is important as it provides code context. For CSE, in order to make sure that code is created in the best way possible, it must be organized a certain way or certain code must utilized in a certain way based on the code itself and the goals of the code. This makes context of the code important because the why important for CSE. THis is why the commit message is important as commit messages can help provide context on what or why was chan 



