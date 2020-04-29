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
 




