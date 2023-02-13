# class03 notes

## lab03 notes
  
 + git clone
   + cloned on to computer
  
  + gtiflow: ACP! (Add, Commit, Push)
    + git status = will help you know where you are at.
                 
           git status
    
    + Add = snapshot of file, tells git what changes we need to commit
             
           git add file
   
    + Commit = take the actual snapshot
   
          git commit -m ""
   
      + -m = (flag) specifies the message includded wit the commit (caption of snap shot)
   
   
  + Push = syncs code to your repo on GitHub
   
          git push origin main


## read03 notes

> ### Git Tutorial

  + **VCS** = Version Control Systems.

  + **CVCS** = Centeralized VCS, a single server saving all changes and acces by various clients.

  + **DVCS** = Distributed VCS, allows clients to create mirrored respositories. Prevents data loss.

  + **Snapshots** = saved changes to a file "*commit*".

  + **Local Operations** = allowing one to continue work on projects even when not online.

  + **Tracking Changes** = tracks file corruption or loss of information.
  
  + **Loss Data** = Designed to minimize data loss.
  
  + **States** = three main states.
       
       1. <u>*Committed*</u> = data stored in local database.
       
       2. <u>*Modified*</u> = file has been changed but not committed to database.

       3. <u>*Staged*</u> = flagged a file's changed version to be committed in the next snapshot.

       ![Image of WP](https://blog.udemy.com/wp-content/uploads/2015/08/image066.png)

### Setting up a Git Respository

   **Cloning** 
  + create a copy of an exisiting Git respository from a particular server by using the command with a repository URL: 
              
       + git clone "URL"
       
       + git clone "URL" "name of directory"

### Workflow

   **Local Repository Structure**
   1. Working Directory = the actual working file
   
   2. Index = area used for staging 
  
   3. Head = Most recent commit

   ![workflow](https://blog.udemy.com/wp-content/uploads/2015/08/image036.png)

   **Saving Changes** 
   
   + *Tracked* = most recent file snapshot can be modified
   
   + *Untracked* = do not reside in the staging area

   ![Life Cycle of a File Status](https://blog.udemy.com/wp-content/uploads/2015/08/image006.png)

   **Checkng, Tracking, and Stagging Files**
   + Commands :
       + git status = determine state of file
       
       + git add filename = single file add

       + git add * = alll files

   **Commiting a File**
   
   + git commit -m "made change x,y,z" = commiting changes

   + git commit -a = commits changes to all (multiple files)

   **Pushing Changes** 

   + git push origin master = This command pushes changes from the local "master" branch to the remote respository named origin
