## ***This is read02***
 ### Git Tutorial: A Comprehensive Guide
## **History of Git**
###  Git traces its roots to the open source software project Linux kernel. Developers of this project began using a DVCS called BitKeeper in 2002. In 2005, many of these developers stopped using this DVCS due to tension between the Linux kernel community and the company behind BitKeeper’s and the eventual revocation of the DVCS’ gratis status.
## Default Text Editor
#### Without configuration of a default text editor, Git will use the system’s default editor–most likely Vim. To configure a different text editor, such as Emacs, type the following into your Terminal or Command Line:

$ git config --global core.editor emacs
## Workflow
#### Local Repository Structure :
The local Git repository has three components:
-Working Directory: The actual files reside here.
-Index: The area used for staging.
-Head: Points to the most recent commit.
![image1](https://blog.udemy.com/wp-content/uploads/2015/08/image036.png)
## The Life Cycle of File Status

-After you  edit a file, Git flags it as modified because of changes made after the previous commit.
-You stage the modified file.
-Then, you commit staged changes.












![image12](https://blog.udemy.com/wp-content/uploads/2015/08/image006.png)
## The command :
### let me teach you some command :
- To determine the state of files > type : **git Status**
- Tracking and Staging a New File > type : **git add filename**
- Committing a File > type  :  ** git commit -m “made change x,y,z” **
- Pushing Changes > type : **git push**
## **Seeing Your Remotes**
By running the git remote command, you can view the short names, such as “origin,” of all specified remote handles.

![Check out this COOL penguin!](/images/penguins.jpg) 
