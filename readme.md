##### This is for Project 11 Jenkins-ansible webhook test 
##### using Bastion server on which Ansible and Jenkins is installed to Automate the installation of wireshark on NFS-SERVER, WEBSERVERS, DATABASE SERVERS, and LOAD BALANCING SERVER then Jenkins will later build the artifacts with the help of github webhooks.
### NB Bastion server connects to the Hosts using SSH-AGENT with their private IPs
### interestingly, this is BANJO BABADE's Project 11 at Darey.io DevOps learning platform

# PROJECT IMAGE 

![project Iamage](IMG-SCREENSHOT/project11-IMG.png)


### Renaming the EC2 instance to Ansible Jenkins
![Alt text](IMG-SCREENSHOT/Screenshot_20230205_005107.png)

### Creating a new repo in GitHub
![Alt text](IMG-SCREENSHOT/Screenshot_20230205_005336.png)

### Installing Ansible on the same machine that had Jenkins
![Alt text](IMG-SCREENSHOT/Screenshot_20230205_102651.png)

![Alt text](IMG-SCREENSHOT/Screenshot_20230205_102704.png)

### Creating a frestyle project namely 'ansible' on jenkins
![Alt text](IMG-SCREENSHOT/Screenshot_20230205_103638.png)

### create a webhook on github for the repo in jenkins
![Alt text](IMG-SCREENSHOT/Screenshot_20230205_103721.png)
![Alt text](IMG-SCREENSHOT/Screenshot_20230205_103941.png)


###  Testing and checking the build in jenkins
![Alt text](IMG-SCREENSHOT/Screenshot_20230205_111321.png)

[label](readme.md%0D) [label](IMG-SCREENSHOT/Screenshot_20230205_111351.png%0D) ![Alt text](IMG-SCREENSHOT/Screenshot_20230205_111636.png)
 
 ### Created FirstBranch and  Hotfix  Branches of ansible-config-mgt repo in Github 
 [label](readme.md%0D) [label](IMG-SCREENSHOT/Screenshot_20230205_115525.png%0D) ![Alt text](IMG-SCREENSHOT/Screenshot_20230205_123926.png)

### created readme.md and working with the FirstBranch Branch from VScode
 ![Alt text](IMG-SCREENSHOT/Screenshot_20230205_123933.png)

 ### Creating folders and files structures for ansible  

 [label](IMG-SCREENSHOT/Screenshot_20230205_124156.png%0D) [label](IMG-SCREENSHOT/Screenshot_20230206_224624.png%0D) ![Alt text](IMG-SCREENSHOT/Screenshot_20230206_224632.png)

### mearge and push changes to master
 ![Alt text](IMG-SCREENSHOT/Screenshot_20230206_233013.png)

### Github webhooks trioggers a build on jenkins
 ![Alt text](IMG-SCREENSHOT/Screenshot_20230206_233032.png)
![Alt text](IMG-SCREENSHOT/Screenshot_20230206_233039.png)
 
 ### confirm the jenkins build on terminal
 ![Alt text](IMG-SCREENSHOT/Screenshot_20230206_233319.png)

### ansible-playbook error 
 [label](readme.md%0D) [label](IMG-SCREENSHOT/Screenshot_20230207_003129.png%0D) ![Alt text](IMG-SCREENSHOT/Screenshot_20230207_004805.png)

 ### one worked, others failed
 ![Alt text](IMG-SCREENSHOT/Screenshot_20230209_012854.png)

![Alt text](IMG-SCREENSHOT/Screenshot_20230209_012929.png)

### troubleshooted and made sure other servers were available via ssh-agent 
![Alt text](IMG-SCREENSHOT/Screenshot_20230209_013808.png)

### MNow confirmed on my WEBSERVER2 that wireshark was installed successfully
![Alt text](IMG-SCREENSHOT/Screenshot_20230209_015715.png)

### installations on other servers succesfull
![Alt text](IMG-SCREENSHOT/Screenshot_20230209_020704.png)
![Alt text](IMG-SCREENSHOT/Screenshot_20230209_020747.png)

### confirm installation on Load Balancer
![Alt text](IMG-SCREENSHOT/Screenshot_20230209_020903.png)



