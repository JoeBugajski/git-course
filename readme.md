# Notes from Git course

Some helpful commands to get started:

-git init
  initializes a new git repo

-git commit -m "My commit message"
  Makes a commit of all changes made to the entire project, including everything stored inside this particular directory. The first line of the commit should be only one line, no more than 50 characters. If you need to add a more detailed message, hit enter twice to add a blank line. Then you can add a longer more descriptive message.

-git log
  returns a list of staged commits

-git help log
  returns the log section of the Git manual

-git log -n 1
  returns only one commit. Specify the number of commits you want to return here. Helpful if you've been working offline (on a plane, for example), and you don't want your whole list of commits popping up.