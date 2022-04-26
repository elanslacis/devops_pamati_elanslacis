# DevOps repozitorijs
Elana Lāča DevOps repozitorijs pamati iesācējiem


Hash no module_1 mapes: 93e7469ad8b537f9d1349038b4f466a5c37572bc
Hash no module_2 mapes: 10528b248411845ddd611d2e67d366faa2e13991


scr.png module_1: f51717315ab2e85424d69db4f432312def72ab64
scr.png module_2: ce469818c1c41aa269ef27ecead01bef0563ae21




16. task: a bit confused about this one, not sure what exactly is requested. 


- git log
- git log --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit
- git log --all --decorate --oneline --graph


- git log --since "APRIL 10 2022" --until "APRIL  17 2022"
- git log --since="2 weeks ago" --until="1 week ago" 
- git log --since="2022-04-11" --until="2022-04-18" 


This is for me, planning to update default view:
git config --global alias.lg "log --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit --date=relative"

17. task
git log --author="Laura Pacilio"

18. task
git log --since "SEPTEMBER 1 2021" --until "SEPTEMBER 30 2021" --author="Laura Pacilio"

Answer - yes, there are commits

19. task
git log --since=yesterday.0:00am --author="Laura Pacilio"

Answer - no, no commits.

20* task

git log --since "APRIL 20 2021" --until "APRIL  21 2021"
- with above command there are no commits from other dates then 20 and 21 april shown.

but with this command:
git log --since="2021-04-20" --until="2021-04-21"

There is: 
commit f8493bf5cd78bc2a723f5ddc6f6bceb0e08813ea
Author: James Bardin <j.bardin@gmail.com>
Date:   Fri Apr 16 17:11:27 2021 -0400

    update hcl
    
    update to v2.10.0




My answer would be (that is a guess without google help, haha): local changes were made & saved but commits were not pushed to GitHub (?)
test