# Things-I-have-learned-and-want-to-remember-for-reference.
I will try to keep a log of things I have learned and want to use for reference in the future. 
I learn the best by hearing about it, researching about it, testing it in action and writing about it/sharing it with others. 


# Week 1 GitHub

1. I cloned a repository from Github to my local machine:
   A. In Terminal I entered git clone <url (https://) of the repository I wanted to clone>, i.e.
      **git clone git@github.com:saltsthlm/spring20-warmup.git**
      
2. I opened VSC from Terminal with **e .** or **code .**

3. I learned how to check somoebody else's file from a repository on Github:
   I opened a readMe file in my VSC from a repository spring20-warmup.git:
   **git checkout "teamAndreaSandraNjal"**
   (I think I first had to type **git pull** into Terminal. I must test this again.)
   **e readMe.md**
   (This command in Terminal opened the readMe.md file in VSC).

4. **git init .**
   _This command creates a reppository in the currently open dierctory._
   
5. **git commit -am "msg"**
   _This command both adds and commits changes to GitHub at the same time._
   _It is a combination of **add .** and **commit -m "msg"**_
   
6. I pushed my project *Scoreboard* into a new repository on Github called Scoreaboard and there was an error: 
> git push -u myOrigin master                                             
> To https://github.com/andreazajicova/Scoreboard.git
> ! [rejected]        master -> master (non-fast-forward)
> error: failed to push some refs to 'https://github.com/andreazajicova/Scoreboard.git'
> hint: Updates were rejected because the tip of your current branch is behind
> hint: its remote counterpart. Integrate the remote changes (e.g.
> hint: 'git pull ...') before pushing again.
> hint: See the 'Note about fast-forwards' in 'git push --help' for details.

I fixed it by looking into suggested *git push --help*.
It told me to use a command *git push --mirror*.
After making other changes, you jut simply push them to your repository with **git push -u origin master.** 

7. Escape git help terminal by clicking _q_ for 'quit'. 

8. When I want to pull any new changes/commits from GitHub repository into my local machine environment, I usse command 
**git pull origin master**.

9. Command to create a new branch to a master branch on GitHub: **git checkout -b /name of the new branch/**

10. When you push into a branch other than master, the command is: **git push -u origin /name of the new branch/**

11. You can clone any public repository on GitHub with **git clone /the repository's url or ssh**
   On GitHub you must FORK it into your account and you push any changes you make in the project on your local machine into      the FORK.
   If you later want to add your changes to the official project on GitHub you must pull a request first. 
   It is best practice to first FORK a public repository. Then clone it and work on the forked clone. Then push changes to the    forked clone. 



# Week 1 NodeJS

1. The commands to start a simple app through Terminal using NodeJS are:

* npm init
  _This creates a package.json which contains information about your app, like name, version, dependencies, that are later neccessary for installing all the dependencies for your app._

* npm install
  _This installs all the dependencies (node modules) for your app that npm finds in package.json._
  
* npm install -D nodemon 
  _This installs Nodemon, so you don't have to refresh your localhost webpage each time you make a change to it._
  

# Week 1 Visual Studio Code

The files that are not white, but yellow or green color need to be added and committed to Git.


# Week 1 General advice

* Software development is not software manufacture = development takes time, it is not about producing a lot, but producing well. It's science.

* Michael Jordan said: 

> Talent can hel you win the race. Teamwork makes you win the championship. 
 
URLParamsSearch
when we pass the URL string into URLSearchParameters as an argument, it gives us back an object.
Remember that an object has properties(key=value pairs) and methods(functions that can be called on the object). In this case we gain access to the method “get” that takes in 1 argument (the key in the key value pair “name”) and when called gives us back the value of the key we pass in. 


