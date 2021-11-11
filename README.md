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



