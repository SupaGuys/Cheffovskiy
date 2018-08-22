# Vagrant+Chef tasks

## Task 1
1. Create branch with your login and in this branch create folder **#{login}-t1**. All files should be located in this folder
1. Create **ONE** Vagrantfile which will contain config for 2 hosts: chef-server and chef-client (node names irrelevant in bot config and on host itself) with virtualbox provider
1. Use private network for both hosts
1. Make **shell** provision for both hosts so that chef-server will be configured as chef-server (org name and other stuff choose as you like), chef-client will automatically addedd to chef-server
1. Create PR to merge your branch into master upon completion
