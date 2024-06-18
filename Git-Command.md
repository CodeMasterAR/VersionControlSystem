# Git Commands

## Create Repository

  - <p>First Create the repository in github. I have created VersionControlSystem repository.</p>
   
    ### **git init**
    <p>Using this command you can create local repository in your desktop in Version_Control_System folder.</p>
    <img src = "https://github.com/CodeMasterAR/VersionControlSystem/assets/114680435/319674df-83eb-435a-b0bb-3d64d117bf80" width = "700" height = "60"/>

## Syncing Repository
  
  - <p>Copy the link from below</p> 
    <img src = "https://github.com/CodeMasterAR/VersionControlSystem/assets/114680435/87f48ba1-3183-4779-8dd1-62898b64b5e4" width = "400" height = "300" />

    ### **git remote add origin <past-link-here\>**
    <p>Using this command you can sync remote repository with your local repository.</p>
    <img src = "https://github.com/CodeMasterAR/VersionControlSystem/assets/114680435/27b35874-36bc-41cd-8416-0347e35f056a" width = "900" height = "50"/>

  - <p>If you found error like below: </p>
    <img src = "https://github.com/CodeMasterAR/VersionControlSystem/assets/114680435/b7fd67e2-1aa2-4719-ab2f-fbbea5e06050" width = "900" height = "60"/>
    
    ### **git remote -v**
    <p>Using this command you can check the already exists url</p>
    <img src = "https://github.com/CodeMasterAR/VersionControlSystem/assets/114680435/a86232a6-5286-4ef0-9b27-2cec07cfccc5" width = "700" height = "80"/>

    ### **git remote set-url origin <correct-url\>**
    <p>Using this command you can set correct url in to add origin</p>
    <img src = "https://github.com/CodeMasterAR/VersionControlSystem/assets/114680435/44465628-34d1-45fc-b52f-b7bb69883294" width = "900" height = "40"/>

## Making Changes

  #### *1) git status*
  
  >>#### **git status**
  >><p>Tells you which files are added to index and are ready to commit.</p>
  <img src = "https://github.com/CodeMasterAR/VersionControlSystem/assets/114680435/4140dcb2-01d9-468d-9c80-9244e1992ced" width = "900" height = "170"/>
      
  >>- <p>After adding the file to index</p>
  <img src = "https://github.com/CodeMasterAR/VersionControlSystem/assets/114680435/d6ae3260-4b00-47e2-a51c-d7fd240748ad" width = "800" height = "150"/>
        
  >>- <p>If you have multiple files are ready to commit</p>
  <img src = "https://github.com/CodeMasterAR/VersionControlSystem/assets/114680435/d2cc0b87-d8d1-47c8-9225-7a17052fcfb7" width = "800" height = "170"/>
      
  #### *2) git add*
    
  >>#### **git add <file name\>**
  >><p>Lets you add files to your index.</p>
  <img src = "https://github.com/CodeMasterAR/VersionControlSystem/assets/114680435/9c11fc00-4cd7-445f-a354-c0be1908c0d3" width = "700" height = "40"/>
  
  >>- <p>If you have multiple files to add</p>
   >> #### **git add -A**
  <img src = "https://github.com/CodeMasterAR/VersionControlSystem/assets/114680435/99000c40-70eb-4faa-afa8-58b35bfd7129" width = "700" height = "40"/>
  
  #### *3) git commit*
    
  >>#### **git commit -m <message or comment\>**
  >><p>It refers to recording snapshots of the repository at a given time.</p>
  >><p>Commited snapshots will never change unless done explicitly</p>
  <img src = "https://github.com/CodeMasterAR/VersionControlSystem/assets/114680435/8fb6a276-f88e-416b-8dc7-4410174dad2b" width = "800" height = "100"/>
  
  >>- <p>If you have multiple files to commit</p>
  >>#### **git commit -a -m <message or comment\>**
  <img src = "https://github.com/CodeMasterAR/VersionControlSystem/assets/114680435/6452d7cb-cb8e-4288-96e3-01d704c665b7" width = "800" height = "120"/>
  
## Parallel Development

  #### _1) Branching_

  >><p>Branches are pointers to a specific commit.</p>
  >><p>Branches are of two types: </p>
  
  >>- <p>Local branches</p>
  >>- <p>Remote-tracking branches</p>
  
  >>#### **git branch <branch-name\>**
  >><p>Using this command you can create the new branch</p>
  <img src = "https://github.com/CodeMasterAR/VersionControlSystem/assets/114680435/b64c0628-91e5-4d8e-a671-5e92b4b9815a" width = "700" height = "40"/>
  
  >>#### **git checkout <branch-name\>**
  >><p>Using this command you can switch one current branch to given branch</p>
  <img src = "https://github.com/CodeMasterAR/VersionControlSystem/assets/114680435/a0162c5a-d64a-4c37-af48-a468ef5be6b9" width = "700" height = "50"/>

  >><p>I have created a demofile4 and commited in the new created branch called first branch, Then it only shaw in new created branch not in master branch</p>
  <img src = "https://github.com/CodeMasterAR/VersionControlSystem/assets/114680435/68ea85b6-d60f-4ce4-8950-96d6eab33bdf" width = "800" height = "250"/>
  
  #### _2) Merging_

  >><p>It is a way to combine the work to differet branches together.</p>
  >><p>Allows to branch off, develop a new feature & combine it back in.</p>
  
  >>#### **git merge <destination-branch\>**
  >><p>Using this command you can merge the destination branch to current branch</p>
  <img src = "https://github.com/CodeMasterAR/VersionControlSystem/assets/114680435/b50ceb8e-a4c7-4818-98ec-aa1dfc4867d0" width = "700" height = "40"/>
  
  #### _3) Rebaing_

  >><p>This is also a way to combining the work between different branches.</p>
  >><p>It can be used to make a linear sequence of commits</p>
