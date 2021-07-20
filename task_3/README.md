 ### task_3

This example pipeline was completed as a task under an acloudguru course- __Jenkins Pipelines__ . This task demonstrates working on two agents: docker 1 and docker 2. 

#### docker 1 

 The pipline  sets the agent as base image from docker pyhon:alpine as a root user and assigns the label 'docker-1'. SCM is taken care by cloning from github (course files under linux academy). The requirements are installed and build is completed consequently through __shell sripts__. Post actions demonstrate message of completing the task and artifacts archieved.

 ###### The artifacts are of .jpg extension and thus are archieved under post-actions.
 
 #### docker 2
 
 The pipline  sets the agent as base image from docker centos:7 as a root user and assigns the label 'docker-2'. Dependicies and artifacts from previous pipeline are copied into workspace through __shell srips__. SCM is taken care by cloning from github (course files under linux academy). The requirements are installed and build is completed consequently again through __shell sripts__. Post actions demonstrate cleanup and artifacts archieved. 

 ###### The artifacts are of .jpg extension and thus are archieved under post-actions.
