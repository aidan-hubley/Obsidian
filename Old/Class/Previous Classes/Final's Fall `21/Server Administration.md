# 1.  Provide a summary of the project and what you were able to complete.
	1. I started by creating a new Ubuntu VM and created a LAMP server in the virtual box environment, easy stuff. 
	2. I created three groups, Clerical, Sales, and ITS. Within the Clerical groups I have an account for Ray, Tim, Joe, Ryan, and Vinny. The Sales group has accounts for Shane, Jamie, and Azianna. The ITS group has accounts for Nason, Justin, and Joe. All of these accounts are joined to their correct groups and have randomized passowrds. I contacted all of my peers and sent them their login information through a safe means of communication than email.
	3. Next I created user authorization policies and procedures. These policies were placed inside a Policy folder that is readable by all users.
	4. I created a CorpFiles directory inside of the root directory so it is easily accessible by all users. Inside this CorpFiles are three folders, Clerical, Sales, and a Policy folder.  
	5. I than used Deja dup to automatically backup my CorpFiles once a week to my messiah google drive. These backups are kept for six months, duplicates are deleted after that. I also created a Backup.txt in the Policy folder explaining when and what get backupped.
	6. Next, I setup a remote access policy in the Policy folder, and set up SSH on my server.
	7. I successful created a patches.txt policy, a password.txt policy, and a termination.txt policy. However, I was unable to implement these actions.
	9. Finally, my attempt at conducting a forensic audit would consist of checking a user's .bash_history in their home directory. This would show my all their actions on my server.

# 2.  What challenges did you face and how did you overcome them?
	1. The challenges I faced and overcame were:
			1. My backups, working through deja dup, were seemingly working but never ended up in my google drive. I talked with Ray amd Joe Tonnies about their opinions. Ray created his own script to backup this server, but he and Joe both suggested reseting my deja dup, and now it successfully backups.
			2. I have an issue with my Ubuntu VM as a whole, It is set to the correct network settings but I can never retrieve an IP address when using ifconfig. This issue blew up when working on this assignment in the last week, mostly becuase without an internet connection I could not provide my 'employees' with an ip address to ssh into my server with. My solution was to ask Joe from help, he was unable to fix whatever issue caused this but instead I explained and showed him my progress of the assignment. Directories, groups, backups, policies, permissions, and he gave me the clear. I see this as a great work around, and although it was not a technical solution I think it brought out a more conservation-based aspect to the assignment. 

# 3.  Did anyone help you with the project and who did you collaborate with?
	1. Ray Truex and I collaborated heavily on this project. We bounced ideas and concpets off either often nearly every classtime. He finished before I did, which allowed me to ask for his assistance on a few difficult questions.

# 4.  What was your favorite part of the project?
	1. My favorite part of the project by far was collaborating with Ray and the other students in class. I feel that this aspect of this assignment helped the class lean into the conversational aspect of working in a real job. It felt more personable and I learned a lot from my classmates. In additon to learning from them, I also got to assist many of them. I loved that, I definetly remember and learn more when I am tasked with sharing it with others.

# 5.  How comfortable would you be running your own Linux server?
	1. On a scale of 1 - 10 I would say I am at a solid 7, I fell that this class, the Testout material and this project specifically have prepared me very well. However I ran into some conisderably sized issuez in my project that I did not manage to fix, which is why I would only say a 7 / 10.
	
	Thank you for your time. bye