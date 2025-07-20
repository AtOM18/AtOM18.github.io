## My OSCP Journey

Hi, this is going to be a long blog about my journey from start to finish to achieve the OSCP (PEN-200) certification. 
This was a great experience where I learned a lot. I passed on my first attempt. The preparation is about making good notes, gaining experience. 

---
#### Index
- Backstory: Nothing to do with the exam itself. Just about myself and how I started.
- Pre Exam Preparation: What I used before purchasing the actual course.
- Official Course Preparation
- The Exam!
- Reporting
- Final Tips

---
#### Backstory
_Note:_ This is nothing to do with the examination and its about my preparation and just some backstory.

This was before starting university. I started my cybersecurity journey about 5 years ago, when I randomly came across a freecodecamp [youtube video](https://youtu.be/3Kq1MIfTWCE?si=LzMnP8Z5wA8tOtUg), by TheCyberMentor(huge thanks to him, he is the only reason I started in cybersec) . This was the first time I heard about the OSCP. I had never thought about that i would have this certification in 5 years. Due to Covid I completed this entire playlist within a week and started practicing on hackthebox.
Way before starting my OSCP journey I used to do a lot of hackthebox machines, which I was honestly very bad then. But there was this addiction that kept me going. So I learned some fundamentals that way.
Then during University I wanted to do something interesting and thought of picking up this "habit" of mine into an actual career(which I didnt know was possible back then.)

I started my OSCP journey at the end of second year in university, taking it seriously. Purchasing and passing the course this month only, and the end of my third year in University.


---
#### Pre Exam Preparation
These are the content I used. To study for OSCP. 

 Through reddit I found about hackthebox academy  which provided CPTS path (penetration tester path) at a student discount. Honestly this was one of the best resources out there for a beginner in Penetration Testing. Not only the method, but they have done a great job at explaining the reason behind what we do and why. The CPTS path took me about 8 months to complete with some very detailed notes I created, which I use even today. (I dont know how you are supposed to complete this courses withing 42 days as listed).

After 2 months before I planned to purchase the OSCP course I got myself a subscription of Playing Grounds Practice by Offsec. I solved about 60 machines, from [Lainkusanagi OSCP List](https://docs.google.com/spreadsheets/d/18weuz_Eeynr6sXFQ87Cd5F0slOj9Z6rt/edit?usp=sharing&ouid=114202580042651295472&rtpof=true&sd=true). This way I built a great methodology and created detailed notes for every machine (which was very helpful later on). Solving about 2-3 boxes a day(somedays none) I got to a point where I felt I had a great methodology, for the exam.

Throughout this entire time, I used [Ippsec](https://www.youtube.com/channel/UCa6eh7gCkpPo5XXUDfygQQA)'s videos, to learn different methods. It was just used wherever I was not feeling good to study just to binge. But helped me learn how to take notes better.

Overall it took me about 10 months on and off, to complete and feel ready to purchase the OSCP 3 month bundle.

---
#### Official Preparation
Now that I had done the prerequisites, I had purchased the course in start of may 2025. I had a plan in mind which I roughly followed. I had to give my exam in july, within the 3 month period so I rushed it a bit, but there is no need to do so.
I made detailed notes for this course too, this included the exercises, and the challenge labs, and almost everything.


###### Study Material
 Completed the official study material with the capstone labs withing 5 weeks, which took my like 6-8 hours daily. I had no problems with the course itself, as the CPTS path beforehand had me everything clear. And this was kind of a revision for me. Honestly the course does not go in depth at some points, to understand why we are doing a certain technique. 

###### Challenge Labs
Then came the actual studying which was the Challenge labs. I highly suggest for everyone atleast give 3-4 weeks time for the challenge labs, as it is the most important part in the course. I completed SECURA, MEDTECH, RELIA.
Then I did the Post OSCP challenge labs LASER, POSEIDEN, ZEUS. Honestly I would suggest doing these post exam challenge labs also. Its just about gaining more experience and learning from your mistakes.

I would suggest completing OSCP A,B and C in a 24 hour timed based manner to  get a feel and time management idea for the exam without hints. I did 70+ points on all three of them. So I felt confident for the exam

**Should I use walkthroughs for hints?**
This is one of the most common questions. My method was to first give the machine about 1-2 hours with some breaks in between. Then if I was going nowhere, then just use the next hint in the walkthroughs.
After I had completed the machine. Then I looked at all the walkthroughs available to look at all the different methods and tools I could have tried. And made some notes on that. 

---
#### The Exam!
The exam itself was a mix of emotions, with a mix of frustration with my proctoring tool. It was challenging enough that getting enough points to pass was satisfying. From the 
I usually start my days late to study from 12 pm, so I scheduled my exam at 12:30 PM.

The proctoring process, in the start is very simple, all you have to do is connect to a portal on your browser, where you will be asked to turn on your camera and screenshare your entire screen. I had to give a 360 view of my entire room. But due to my wireless WIFI, I had to reconnect to the proctoring tool every 30 minutes, in the start. But somehow it fixed itself after about 6-7 hours. And had no issues further.

I started with active directory as usual, gaining local administrator on my first machine in about 1 1/2 hours. Then I got stuck on the second machine for about 3 hours gaining nothing, where I even questioned my proctor if the machine was working correctly. PS: I was trying the wrong thing. Getting nowhere, Then at about 6pm I took a break from AD and started with my first standalone.(Currently: 10 points, hour 6)

The first standalone was honestly very easy, thanks to PG practice I did. I got rce and root shell and completed it within an hour. And I gained some confidence for the exam. My plan at this point was to root all three standalones so I get enough points to pass. Which for me was always impossible to root all three standalone machines.(Currently 30 points, hour 7)

Next step was to pwn the second standalone machine, where in about an hour I had an attack vector, but I needed a second piece of information to use it, which I was not able to find. In about 1 hour. I had an idea to try on the Active Directory domain so I hoped back again at AD ( currently 30 points, hour 8)

Next I went again to Second machine on AD, where I knew what I was doing wrong with my first technique atleast. Took me about 30 minutes to find a interesting piece of info, that gave me a direct attack path to Domain Admin. (currently 30 points, hour 9). But I was sitting for too long on my desk so I took a break for dinner.

After about 40 minutes, with some great confidence I went back to attacking the active directory environment, This time I knew what I had to do. Pwned second machine and got Domain Administrator in about 1 hour. Boom! 30 points gained within an hour. This gave a me great boost of confidence. Now all I had to hope for was that I was able to pwn the last standalone machine. (currently: 60 points, hour: 11)

The final machine was a do or die situation for me. Had to do a lot of manual enumeration where in about an hour, I had figured out the foothold which  worked. Now all I had to do was get a reverse shell. This is where I struggled a bit. I found no vector to gain a reverse shell. Desperate in this situation i went to look for anything I can. This went on for about 3 hours with small breaks in between. Then then when I saw it, I knew that was it! I had a attack technique to gain reverse shell on this machine. Took me about 20 minutes from to gain reverse shell and rooted the entire machine. And there I had it, 80 points in total. I dreamt of this exact moment, it was honestly great :) (currently 80 points, hour:15)

Now it was 3 am, and I had no sleep. So I decided it was time to get some sleep. I had no intention to get points on the final standalone. All I had to do in the morning was review my notes, and see if anything was missing. Took a lot of screenshots, and made sure I did not mess up the flag screenshots. 

---
#### The Report
I used [SysReptor](https://docs.sysreptor.com/) for my report, so I didn't  have to deal with formatting. Took me about 6 hours to make the report, used another hour to verify it if everything was correct. Just didnt wanted to mess the report up and fail because of a missing screenshot or flag. I got my exam result in about 30 hours after submitting the report, where I passed!

---
#### Final Tips
If I would summarize, this entire post. Here is what I would suggest
- Please make notes for everything you learn, whether it is text material, exercise, or a machine you solved. Trust me it comes in handly, when you have done something before, and have it documented. I personally use Obsidian to take my notes. You can also use Notion.
- Use PG Practice list from  [Lainkusanagi OSCP List](https://docs.google.com/spreadsheets/d/18weuz_Eeynr6sXFQ87Cd5F0slOj9Z6rt/edit?usp=sharing&ouid=114202580042651295472&rtpof=true&sd=true) to build a great methodology.
- Do the CPTS path from hackthebox, for great fundamentals and understanding.
- Create a exam schedule and stick to it. Discipline is key.
- Get atleast 3-4 weeks for the challenge labs is the official courses.
- This is just a small tip(not for everyone) I create visual graphs using Obsidian canvas, which helps me understand what I am doing after a long break easily, when the environment gets too big.

Tools that I would recommend to everyone.
- [NXC](https://www.netexec.wiki/), honestly just makes everything easier. Switch from crackmapexec to this.
- [ligolo-ng](https://github.com/nicocha30/ligolo-ng), great tool for pivoting. Much easier and reliable to use then Chisel.
- [Bloodhound Community Edition](https://github.com/SpecterOps/BloodHound). The default bloodhound is outdated now, and bloodhound-ce just feels much better to me. Plus it works with latest versions of sharphound.
- [sysreptor](https://docs.sysreptor.com/): great tool for reporting, much easier to work with then any word tool.
- Obviously use [LinPEAS and winPEAS](https://github.com/peass-ng/PEASS-ng), but manual enumeration is key.

---

Thanks this was all I had to say about the exam and my journey. I will update this blog if I feel anything is missing, so ask me questions if you have any.

