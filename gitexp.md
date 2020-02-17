# My First GITHUB Experience
----------------------------
I had started using github from my third semester class onwards especially for my **web programming lab**.Before our teacher RahulNath sir's introduction to github,i didnt even have basic knowledge about github.But from my first github lab session onwards,I started understanding and exploring github through the github desktop platform which was my IDE for git.The very first thing I have done with github was creating a **public repository**.My first repository was named as *web-programming*. It was created only for my web programming lab sessions. The URL for that repository is [web-programming](https://github.com/Anjali-941/Web-programming).But after starting my **system design lab** of fourth semester,I started using *terminal and commands* to access git hub and my repository.The following steps have been used by me to start accessing github via linux terminal.

**1.Installing git in my system**.

Since my system has already git installed on it,I didnt face any trouble in installing git in my system.

**2.Initializing git in a folder**.

For this step to begin,first i created a folder named *first-repo* in home.In the terminal , typed the command after redirecting the prompt to first-repo folder **git init** to initialize git in the corresponding folder.

**3.Create a git repository named first-repo in github via IDE.**

After creating git repository,invite your teams as collaborators.

**4.Setting the git configurations in terminal.**

Use the below commands to set git configurations.

             git config --global user.name Anjali-941.
            
             git config --global user.email anjalivenugobal@gmail.com.
            
             git config --global core.edit gedit.
             
**5.Adding a file in your git initialized folder to staging area**.

Use the command **git add file.txt** to add the file to staging area. We can use **git status** command to see both tracked and untracked files.

**6.To commit the added file.**

Use the command **git commit -m "a meaninful comment"**.

**7.Cloning the github repository.**

To clone the entire github repository , use the command **git clone https://github.com/Anjali-941/first-repo.git**.

**8.Pushing your commited file to your github repository**.

To push the committed file to our git repository , use the below command.

              git push https://github.com/Anjali-941/first-repo.git master
              
**9.Creating a new branch and branch operations.**

Use the following commands :-
    
              git checkout -b repos  /*to create a branch named repos*/
              
              git branch             /*to show all branches*/
              
              git push https://github.com/Anjali-941/first-repo.git repos   /*to push the commited file to repos branch*/
              
**10.Merging the branch to master branch.**

To merge the branch to our master branch,use following commands.

               git checkout master /*switching to master branch*/
               
               git merge repos    /*merging the branch repos*/
               
               git pull . repos    /*merging the branch repos*/
               
 
The URL for the above repository in github is [first-rep](https://github.com/Anjali-941/demoteam).
These are the main operations or steps that i have done with linux terminal as part of git lab.During all these steps i felt very easiness in doing all these steps through command line just like with IDE.At all the time , when our team got proper output after each procedure , I felt very happy and become satisfied.The only difficulty we faced was in finding proper commands , after all git tutorials helped me a lot in finding proper commands.
My hearty thanks to our RahulNath sir for providing this wonderful lab session and providing hands on experience rather than mere theory classes.We felt like we are really working on a team project via this version control system.I used **Mark Down** tool to prepare this document which is also a new experience for me.I express my sincere gratitude to our sir for this fruitful session.
