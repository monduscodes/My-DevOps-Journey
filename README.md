# My-Journey
A record of my learning, and notes for reflection
Day 1-5:
KodeKloud learning:
Learnt the basics about Linux such as the developer, its open source nature, and how to navigate within the CLI.
Learnt basic prompts such as ls, cp, cd.
Learnt about the different shells that can be used, Current favourite is BASH.
Explored Package managment such as RPM, YUM, DPKG, APT & APT-GET
Stepped into the VI and VIM editors.
Dived into the security and file permissions elements including SSH and Cronjobs.
SYSTEMD - explored what systemd is and what it is used for. This has been my favourite topic so far.
Learnt about storage on Linux, explored and trialed with partioning.
Finished the Linux Basic and labs section on there website.

Day 6-10:
Spent day 6 and 7 revisiting the labs from above to retain the information and attempted to complete with a limited amount of tip usage and note checking. (this was reasonably succsesful with only a handful of times where I found myself stuck and needing to revist material)
Day 8 I moved onto the DevOps pre-requisite course. 
Found the revisiting of Linux basics helpful to concrete in the learning from the previous week. I was surprised with how much I had retained and how little i found myself needing to check my notes or use the hints section to be able to pass the labs.
Networking Basics, I have found myself enjoying learning and trialing the basics of networking such as setting up IP/Routing tables. 
Day 9 I began the applications basics section, this seems like where the course will begin adding complexity with the addition of Java and Python. I look forward to begining the labs and trying my hand at some more complex tasks than the basics that I have undertaken so far.

Day 11-15:
I spent day 11 revisiting the labs and notes from the prior week to re-affirm the materials learned about networking basics.
Days 12-13 were spent learning the basics about python and java. I found this challenging given that the labs asked questions that had not been covered in the lessons leading to a lot of self-led research to find context around the missing knowledge. 
To allow for a break from this subject I then returned to the labs about CLI basics to ensure these had been retained. Which it was aside from one particular question in the DNS Labs question 9 that asked:
On host01, configure the system to resolve the name news to news.yahoo.com automatically without directly editing the /etc/hosts file. Implement the necessary changes to achieve this.
I was unsure on how to complete this and the solution in the solutions tab was:
echo "search yahoo.com" | sudo tee -a /etc/resolv.conf
Upon entering this it still said incorrect and am currently trying to work out why.
Day 14 and 15 were spent re-doing labs surrounding Linux basics, commands, VI editor, and user managment. Aiming to complete all linux labs available at least once per week untill the commands become second nature and I am no longer needing to look at MAN pages or my cheat sheet of flags and arguments. The commands I am remembering but the flags and arguments are where I am currently struggling. I have also began reading The Linux Command Line by William Shots. This pdf has helped me understand the why more than KodeKloud as the service they provide doesn't go into details as for the why, and I have increasingly found that the lessons they provide do not provide the learning/answers for the questions in the labs.

Day 15:
Weeks break taken due to holiday, whilst away i spent time reading The Linux Command Line 7th Edition and UNIX and Linux System Administration Handbook. whilst William Shotts book was interesting it has become apparent that the handbook is going to be the more valuable read as it is based on administration as opposed to using Linux on a single machine.

Day 21: 
Returned to studying and installed VirtualBox to begin exploring Linux outside of the labs provided by the learning path. I found this a little daunting at first as thre is not the safety net of being able to reset the lab, but ultimatley this led to me having to ensure the commands I was running were correct. I have allocated 8GB RAM, 4 cores and 60 GB SSD to this VM so I can fully explore what Linux offers without worry of any bottlenecks occuring or running out of space.

Day 22: 
went through the entirety of Kodeklouds Linux labs and was surprised that I retained the required information to carry out the tasks required aswell as the ability to search man files using grep to find any information I could not, this proved to be testing at first as i forgot the flags to include lines before and after but with a little extra help from googling common flags surrounding grep it only took a few moments to overcome.
On the studying side i began learning about YAML and JSON. YAML I have found to come very naturaly to myself even tho I have only covered the basics. My goal for the remainder of the week is to continue practising the labs aswell as continue with the learning path. I am looking forward to the Dev-Ops pre-requisite path finishing and moving back onto modules focussing on Linux. Once these are completed I am going to start a second README outlining my project portfolio, for now i can see the need to run multiple VM servers to practice SSH skills, set up firewalls, DNS, Web server, Database server, Monitoring server and have recently read about load balancing so possibly adding this to the list aswell, I am also interested in automation so looking at the viability of setting up a dedicated server that will do basic task such as configuring, and updating to remove the need for constant manual tasks.

Day 23 -28:
I spent this time continuing to read Unix and Linux systtem administration handbook, seeing information from a different approach and gaining more depth of understanding around the fundementals of sys admin work and why it is important in the bigger picture. Began the KodeKloud LFCS preperation course, which i found beneficial as it covered many of the same topics but in much greater depth. The labs that run alongside this course are also more in-depth and allowed me to refine my skills in the lan environment.

Day 29-34:
Spent the makority of the time watching the video lectures and note taking about the topics covered. I also spent time researching alternative ways to write commands that also allowed me to write more complicated commands. Finding out how to use pipelines for command dramatically reduced the time and repetiveness of executing commands as it allows the output to then be manipulated in a meanigfull manner. The labs covered so far have required me to try multiple times to become fully efficent with and iron out any lapse of knowledge. I then focused on the laps of knowledge such as hard and soft links, finding ways to remember how to corredctly write and remember these commands without having to constantly rely up apropos and man / help searches to complete the required tasks. 
I also spent time setting up a clean home lab for my portfolio project. Looking into what is required for the LFCS qualification and whether this would be a suitable option for me which i believe it will be as achieving this will provide evidence of practical skills. I am going to further explore this and killer.sh? with the goal that before the end of the year to achieve the LFCS certification.

Day 34-36:
Mainly spent my time playing around in my home lab creating and manipulating text files with use of basic commands. Some of the activities i undertook were creating and editing files, moving and removing files, setting file permissions, modifying file permissions, creating a localised back up of files although on the same 'system'. Time was also spent ironing out details for my project i have decided that the project will require multiple VMS, to include but not limited to 2 web servers with a laod balancer, 2 database servers, a managment/dashboard server, and a back-up server. This may increase as i research the project further, but to begin with the general outline of the project will be to replicate an enterprise grade set-up. the web-servers will be basic and have a landing page/text that will display what server has been conected to, some form of data that can stored in both sql an nosql databses even if it just basic metrics like site visitors etc, a back up server to safely store data that will be automatically backed-up daily. After completing this set up my next logical stage would be to make this so it can automatically set itself up. But i need to research this further as from what i have understood so far ansible would be a key factor to incorporate to allow this to happen. At this stage i think ewxploring kubernetes would also be benefical for both my understanding and project application.

Day 37-39:
Was spent finishing off the essential commands section of lectures and labs on KodeKlouds LFCS course, i also completed all the available labs in this section multiple times to move past the sticking point, what i have learned is that any person is highly unlikely to be able to remember the list of commands needed and what is more important is to remember how to search for what is needed by using the various utilities that linux cli is equipped with. This marked a big shift in my learning process as allowed me to not focus on remembering the command but remembering the essence of the command and what i was trying to complete with said command. It feels as if a whole new level has been reached and upon learning this i spent several hours simply practising how to properly and efficently use the various search utilities to find the information. I feel this will be one of the most benefical things in my very early journey/career as knowing how to find the solution is more important than knowing the answer to the solution. I feel this way because there will always be times where the answer is not known, but by knowing how to find the answer any scenario can be tackled. I liken this to understanding how to read manufactures literature when i have been fault finding boilers and other systems in my previous career as a heating engineer. 
