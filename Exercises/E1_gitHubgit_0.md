##15 minute exercise: begin using git and GitHub to maintain and share your work. 

##Description
Git and GitHub are different things.  

Git is a commandline program that you can use to keep control of your computational projects.  You make a directory, you initiate git in that directory to keep track of things, and then as you carry out your work, you make commits to your project repository.  It's incredibly powerful.  For example, if you make a disasterous mistake, you can just rewind you repository to a place where things were working as expected.  This exercise will not teach you how to do this.  In this exercise, you will use the git command to clone repositories from GitHub so that you can mess around locally on your computer.  

GitHub is a place up in the cloud that you can push work to and pull your work from.  It is free as long as you make your projects publicly accessable.  It is a giant space containing tons of cool things that you can play around with and start work from.  In fact you are reading this description on GitHub.  In this exercise, you will use the tools you have learned in the linux exercise to interact with this repository locally on your machine.  

## Commands
 * git 
 * cd
 * ls
 * cat

## Exercise
  1. open a terminal window and run `man git` to check out the man pages.
  2. run `git help -a` to see all the possible commands.  It is a massive list.  Don't be scared.
  3. make a directory that you will carry your work in.  `mkdir devel_demian` or something like that and the change your working directory to that directory.
  4. clone this repository, which you are reading right now! `git clone https://github.com/demianriccardi/EC-Chem452.git`
  5. change your working directory to EC-Chem452 and look around.  Try to find these words: "Computer Science is fun"
using a grep command with a wildcard.  e.g. `grep "Earlham is heaven on earth" */*`
  6. you now have your own local version of this repository.  
  7. change your working directoy back to base of the one you made in 3.  Now clone the HackaMol repository: `git clone https://github.com/demianriccardi/HackaMol.git` and then look around.  There is a directory of examples that you will be able to play with once you have more tools.
  8. Once you are ready to take the plunge, create a GitHub account!
  9. Login to GitHub, open a web-browser and navigate to [this repository](https://github.com/demianriccardi/EC-Chem452).  Find these words: "Earlham is on earth" and change them to whatever you want using the edit feature on GitHub (a little pencil... I'm using the edit feature right now to write this!).  If you figure out how to do this, a fork of this repository will be created in your github user space.  A fork is basically a copy, your copy, that you can change with abandon!  Thus, at this stage, you can take these exercises and write in your own solutions.   
  10. I think that is enough for now.  assuming you didn't do anything useful in the directory you created.  Change your working directory and `rm -r path/devel_demian` 
