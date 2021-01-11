# Hello-World


We will be using Github to handle code submission, review, etc. in PM520.
A way of testing that cloning/committing/pushing is working for you

Here are the first two lines of a popular English nursery rhyme:

1. Ring-a-ring o' roses,
2. A pocket full of posies,

...[next 2 lines go here]...

3. 
4. 

Your job is to Google the next two lines of this nursery rhyme. (You may find some 
interesting chit-chat aobut the origina of the nursery rhyme - the story I was told at 
school in the 1970s now seems to have been de-bunked).

Then add the third line by directly editing this file on Github.
Then add the fourth line by cloning this repository using Rstudio, updating the markdown
file (Readme.md) and then pushing it back onto Github.

You should need to complete the following steps.

1. Accept the invitation you received to work on this assignment, and then go to the 
   repository that is created for you at github.com

2. Click on the link there to edit the Readme.md file and manually add the third line.

3. Commit your change, and don't forgot to add a commit message.

   At this point your changes should be visible to me. See if you can work out how
   to send me a message saying that you have completed this step. Hand gestures will
   work in the classroom, but I am imagining something that will work in a more
   general setting.

Now, for the fourth line:

4. Go to Rstudio and click on File / New Project, then choose the option "Version Control"
   followed by "Git"
   
5. At this point you will be prompted to enter the url for your repository for this problem on github. 
   It will look something like this "https://github.com/PM520-Spring2021/Week0--Hello-World-username".
   
   At this point you will be prompted to enter your github username and password.
   
6. You should now have a copy of the repository on your local machine, in the form of an Rproject.

7. Open the file `README.md` and add the fourth line of the nursery rhyme.

8. You now need to "commit" (save a permanent record of) the changes to your local machine,
   and then "push" the changes back to github.com. First look for and click the Git
   tab in your Rstudio Gui. (For me it is at the top of the window to top right of
   the Gui.) Then check the box for the files you want to commit (here, just the 
   `README.md` will do) and hit the "commit" button. In the process of doing this it
   will prompt you to enter a commit message. This is a reminder of what you changed in
   this edit. So something like "added 4th line of nursery rhyme" will do here. You
   should get into the habit of adding an explanation to every commit.
   
   If you are into command line, you can also try doing the following:
   
   ```shell
   $ git clone [url path copied from github]
   $ cd [folder created]
   $ ... make your changes ...
   $ git commit -a -m "Adding the fourth line"
   $ git push
   ```
   
   That should work too :).
   
9. Now you are ready to push the changes back to github.  Look for the push button and
   hit it. If you don't get an error message your new version will now replace the
   one that was on Github, so go to your repository on Github and check that you see
   it there. (You will need to refresh that window if you already have it open in your
   browser.)
   
10. Your work is dnow one. In order to let me know that is ready for review create an "Issue". 
   You can find this option using the "Issue" tab near the top of the window, just under the 
   repository name. Add a message to the effect that you have completed the task and then include
   a reference to my Github id by typing "@pmarjora" anywhere in the message. I will then be
   sent a notification that you are finished and ready for review. you can also include my
   Id in commit messages when you upload code during future classes, which will have the same effect.
