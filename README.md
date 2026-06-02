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
