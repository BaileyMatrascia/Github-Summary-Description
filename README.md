# Github-Summary-Description
A description of git summary and how it differs from git log and aids CSE
practice

fjhjhklghaklfj

sdgfdsfhsdjsdgjs


## git log
![image](https://user-images.githubusercontent.com/46755902/141370148-2b275b3a-ae84-4e48-b56c-76f2c685929a.png)
### When a user ustilizes git log, it prints out the commit ID, the author of the commit, and the date and time of the commit




## git log --raw
![image](https://user-images.githubusercontent.com/46755902/141370209-41c4e5b1-52d4-4647-9cab-59fc93504655.png)
### When a user adds on the --raw extension to the git log command it also tells the user which file was added to the commit and how. So A = added, M = Modified, R = Renamed, and D = Deleted and it




## git log --patch
![image](https://user-images.githubusercontent.com/46755902/141370248-7f2a3fd8-e506-4eb0-82e7-1fbee4d7aad5.png)
### When a user adds on the --patch extension to the git log command, it tells the user what was specifically changed in a file as shown towards the bottom of the terminal in the picture.




##git summary
![image](https://user-images.githubusercontent.com/46755902/141372675-d67c2bb3-80be-4d1a-864d-c8405b4e8481.png)
### When a user uses one simple command, git summary will output and entire summary for the day that will include the date, number of the amount of commits included in this particular summary, and all of the above information and more as it will include the actual commit message associated with the corresponding commit and lines of code that the code change is in that will be able to give the user context around what was specifically changed in the code with highlights of the specific line number and text change.



## Differences

### What makes git summary different from git log is that with git log you must type in muiltiple commands in order to gather all of the data that git summary provides and even then, you do not get the commit message nor actual code from the file that shows the entire line or surrounding code and lines. Git summary as well will provide a cleaner interface that is more visually appealing and easy to read with all of itsheader at the top of the summary to provide the user with how many commits are included in the summary so user can quickly know how long the summary is or in short, how many changes were implemented and labels for everything. Git log has a few labels but not everything is labeled and the random numbers and lack of a commit message can be somewhat confusing at first glance. For gitlog to be useful you need to know what many of the symbols mean.

## CSE

### CSE is a software engineering approach that includes shorter iteration cycles with numerous continuous processes made continuous centerd around the principle of continuous improvement. As a result of CSE, higher quality software is created in a shorter amount of time. In order for a higher quality software to be created in a shorter amount of time, these shorter iteration cycles combined with continuous improvement must be undercontrol and organized so continuous improvement and these continuous processes can be executed efficiently.

### git summary is more sufficient for CSE and helps aid CSE better than git log. CSE is all about "trimming the fat" and making constant edits to code to make the code the best it can possibly be. With git summary, the user is provided with muiltiple lines of code surrounding the specific change as opposed to git log which only provides the specific words added and deleted. So if a user only adds or moves around a word, git log is only displaying that word and showing it was added to the file, however due to the types of improvement edits and changes made through continuous improvement in CSE, that single word change is not enough and does not give clues on maybe why that change was implemented. These muiltiple lines of code and the specific line numbers is important as it provides code context. For CSE, in order to make sure that code is created in the best way possible, it must be organized a certain way or certain code must utilized in a certain way based on the code itself and the goals of the code. This makes context of the code important because the why important for CSE. THis is why the commit message is important as commit messages can help provide context on what or why was changed.

### Furthermore, the fact that all of the information provided is a provided within one command saves time. CSE prioritizes efficiency and in order to accomplish everything within shorter iteration cycles and with the continuous improvement aspect, numerous edits and changes of the code will be happening. Therefore, if a user uses git log, they will be forced to type mutiple commands just to get some of the information that git summary will provide which over time adds up and slows the whole process down especially when accross the project various people needing to access that information numerous times throughout the project. This extra time and excessive use of muiltiple commands contradicts the goals and theme of CSE. Git summary outputing all of the information needed and more all within 1 command makes git summary a more efficient tool in comparison to git log and using more efficent tools for CSE allows software to be continuously improved and created within the shorter iteration cycles and overall allows for more to be accomplished in a shorter amount of time which is one of the key benefits of CSE

### On top of all of that, git summary will provide a more visually appealing, easy to read, and organized interface. Everything will be clearly labeled. Why this in particular is beneficial to CSE is because it makes it quicker to understand as opposed to git log which can seem to be a little much at first glance with the long git id and various long patterns of numbers with no commit message which can make it a little confusing to know which commit this is refering without knowing specific details already unless the one who created it knows all of the other details. The git summary look makes it clear to someone who may not know as much about the project to more clearly see what it the commit as opposed to git log where you need to know what certain terms and symbols mean in order to fully understand and further look into the specific details of the commit perhaps on github to get a general understanding of the code. This overall contributes to CSE's prioritization of efficiency as well as when things are clearly labeled and easier to read in comparision to git log, then it takes less time to digest and understand the commits in order to make progress and understand the project faster which in return allows for more the be accomplished in these shorter iterations which CSE needs in order to be successfully executed. And with that as well, with CSE and its devOPS and BizDEV components, it gives opportunity for the commits and progress be easier understood for the business side to read understand if needed and allows for the business to be more connected and involved by utilizeing git summary which is also a key aspect of CSE as well and necessary for CSE to operate.

## Feasibility

### Feasibility of creating this tool is demonstrated through git log and git-standup (which is similar to git log but is made using github) where I can utilize these tool's code which is availible to look at and compare, as well as use them for better evaluation as well. On top of that, the github api is open source so i can utilize availible comands and code as well for my benefit. Even further than, it will be created using github like git-standup and ran in the terminal which are are tools that i am familar with. for the aspect of the lines changed with the code, there is an aspect of that availible through github when looking at the specific details of commits and all of the other info is stored in the github repo so i should be able to extract all of that info from the github repo just as git log and git-standup is able to.


gjihfgjahkghakjhfdsfhtestubg
