# Git Commands

## Create Repository

  - <p>First Create the repository in github. I have created VersionControlSystem repository.</p>
   
    ### **git init**
    <p>Using this command you can create local repository in your desktop in Version_Control_System folder.</p>
    <img src = "https://github.com/CodeMasterAR/VersionControlSystem/assets/114680435/319674df-83eb-435a-b0bb-3d64d117bf80" width = "700" height = "60"/>

## Syncing Repository

  #### *1) git remote*

  >>#### **HTTPS link**
  >>- <p>Copy the link from below</p> 
  <img src = "https://github.com/CodeMasterAR/VersionControlSystem/assets/114680435/76598064-1829-4b14-a843-8f82cf20c9a1" width = "400" height = "300" />

  >>### **git remote add origin <past-link-here\>**
  >><p>Using this command you can sync remote repository with your local repository.</p>
  <img src = "https://github.com/CodeMasterAR/VersionControlSystem/assets/114680435/27b35874-36bc-41cd-8416-0347e35f056a" width = "900" height = "50"/>

  >>- <p>If you found error like below: </p>
  <img src = "https://github.com/CodeMasterAR/VersionControlSystem/assets/114680435/b7fd67e2-1aa2-4719-ab2f-fbbea5e06050" width = "900" height = "60"/>
    
  >>### **git remote -v**
  >><p>Using this command you can check the already exists url</p>
  <img src = "https://github.com/CodeMasterAR/VersionControlSystem/assets/114680435/a86232a6-5286-4ef0-9b27-2cec07cfccc5" width = "700" height = "80"/>

  >>### **git remote set-url origin <correct-url\>**
  >><p>Using this command you can set correct url in to add origin</p>
  <img src = "https://github.com/CodeMasterAR/VersionControlSystem/assets/114680435/44465628-34d1-45fc-b52f-b7bb69883294" width = "900" height = "40"/>

  >>#### **SSH link**
  >>- <p>Using SSH (Secure Shell) links in Git repositories offers several benefits over using HTTPS links.</p>
  >>#### *Benefits of SSH key*
  >>+ <p>Enhanced Security</p>
  >>+ <p>Convenience</p>
  >>+ <p>Consistency</p>
  >>+ <p>Firewall and Proxy Friendly</p>
  <img src = "https://github.com/CodeMasterAR/VersionControlSystem/assets/114680435/e1617923-0ceb-45b2-93fb-dfeb6251331f" width = "400" height = "300"/>

  >>### **ssh-keygen**
  >><p>You must generate an SSH key to use the SSH link.</p>
  <img src = "https://github.com/CodeMasterAR/VersionControlSystem/assets/114680435/60be0a58-62ce-49bd-8359-188fd7a0e6ef" width = "800" height = "400"/>
  
  >><p>Copy the highlighted part. Your SSH key is generated in this path. You can see the key using the cat command.</p>
  <img src = "https://github.com/CodeMasterAR/VersionControlSystem/assets/114680435/91b273ee-e137-48b5-8c41-0dc06d07004d" width = "1000" height = "150"/>

  >><p>Copy the generated key. Now follow the path which given below: </p>
  
  >>#### *Settings \> *
  <img src = "https://github.com/CodeMasterAR/VersionControlSystem/assets/114680435/2fd0c4d7-b348-4c30-a3f8-c96a4fa0fa4d" width = "800" height = "600"/>
  
## Making Changes

  #### *1) git status*
  
  >>### **git status**
  >><p>Tells you which files are added to index and are ready to commit.</p>
  <img src = "https://github.com/CodeMasterAR/VersionControlSystem/assets/114680435/4140dcb2-01d9-468d-9c80-9244e1992ced" width = "900" height = "170"/>
      
  >>- <p>After adding the file to index</p>
  <img src = "https://github.com/CodeMasterAR/VersionControlSystem/assets/114680435/d6ae3260-4b00-47e2-a51c-d7fd240748ad" width = "800" height = "150"/>
        
  >>- <p>If you have multiple files are ready to commit</p>
  <img src = "https://github.com/CodeMasterAR/VersionControlSystem/assets/114680435/d2cc0b87-d8d1-47c8-9225-7a17052fcfb7" width = "800" height = "170"/>
      
  #### *2) git add*
    
  >>### **git add <file name\>**
  >><p>Lets you add files to your index.</p>
  <img src = "https://github.com/CodeMasterAR/VersionControlSystem/assets/114680435/9c11fc00-4cd7-445f-a354-c0be1908c0d3" width = "700" height = "40"/>
  
  >>- <p>If you have multiple files to add</p>
   >> ### **git add -A**
  <img src = "https://github.com/CodeMasterAR/VersionControlSystem/assets/114680435/99000c40-70eb-4faa-afa8-58b35bfd7129" width = "700" height = "40"/>
  
  #### *3) git commit*
    
  >>### **git commit -m <message or comment\>**
  >><p>It refers to recording snapshots of the repository at a given time.</p>
  >><p>Commited snapshots will never change unless done explicitly</p>
  <img src = "https://github.com/CodeMasterAR/VersionControlSystem/assets/114680435/8fb6a276-f88e-416b-8dc7-4410174dad2b" width = "800" height = "100"/>
  
  >>- <p>If you have multiple files to commit</p>
  >>### **git commit -a -m <message or comment\>**
  <img src = "https://github.com/CodeMasterAR/VersionControlSystem/assets/114680435/6452d7cb-cb8e-4288-96e3-01d704c665b7" width = "800" height = "120"/>
  
## Parallel Development

  #### _1) Branching_

  >><p>Branches are pointers to a specific commit.</p>
  >><p>Branches are of two types: </p>
  
  >>- <p>Local branches</p>
  >>- <p>Remote-tracking branches</p>
  
  >>### **git branch <branch-name\>**
  >><p>Using this command you can create the new branch</p>
  <img src = "https://github.com/CodeMasterAR/VersionControlSystem/assets/114680435/b64c0628-91e5-4d8e-a671-5e92b4b9815a" width = "700" height = "40"/>
  
  >>### **git checkout <branch-name\>**
  >><p>Using this command you can switch one current branch to given branch</p>
  <img src = "https://github.com/CodeMasterAR/VersionControlSystem/assets/114680435/a0162c5a-d64a-4c37-af48-a468ef5be6b9" width = "700" height = "50"/>

  >>- <p>I created a demo file 4 and committed to a newly created branch called first branch, then it only appears in the newly created branch, not in the master branch.</p>
  <img src = "https://github.com/CodeMasterAR/VersionControlSystem/assets/114680435/68ea85b6-d60f-4ce4-8950-96d6eab33bdf" width = "800" height = "250"/>
  
  #### _2) Merging_

  >><p>It is a way to combine the work to differet branches together.</p>
  >><p>Allows to branch off, develop a new feature & combine it back in.</p>
  
  >>### **git merge <destination-branch\>**
  >><p>Using this command you can merge the destination branch to current branch</p>
  <img src = "https://github.com/CodeMasterAR/VersionControlSystem/assets/114680435/6034c274-ec25-4120-a653-ebcc2c0ef4a4" width = "800" height = "180"/>

  >>- <p>If we don't merge and try to commit the newly modified demofile4 to a new branch called the first branch, it won't be modified in the master branch.</p>
  <img src = "https://github.com/CodeMasterAR/VersionControlSystem/assets/114680435/c0c040f0-42b3-43e0-b4f0-5d54b1759a8e" width = "800" height = "270"/>
   
  #### _3) Rebasing_

  >><p>This is also a way to combining the work between different branches.</p>
  >><p>It can be used to make a linear sequence of commits</p>
  
  >>- <p>When you create a new file in the first branch and commit it, it will not appear in the master branch. After rebasing, they all merge into a linear sequence.</p>
  <img src = "https://github.com/CodeMasterAR/VersionControlSystem/assets/114680435/f46bdb41-f4e4-4774-9b2d-85d287e2b976" width = "900" height = "650"/>
