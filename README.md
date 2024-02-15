***
<a name="M"></a>
# Menu:   

| 0   | [About](#AB)                       |                                                                                                                    |
|-----|------------------------------------|--------------------------------------------------------------------------------------------------------------------|
| 1   | [Setup](#SU)                       |                                                                                                                    |
| 2   | [Versions](#VS)                    |                                                                                                                    |


<a name="AB"></a>
## About   

***

Bash-x is a lightweight framework for running and creating SRE applications.    
It provides the SRE-consumer with a range of 'projects' that are easily configurable for their environments and needs.   
It enables  the SRE-developer to rapidly create any data-driven workflow.    
         
Bash-x can be run from any linux machine but is best integrated as part of a Jenkins / Gitlab pipeline.    

This repository contains the projects that have been developed using the framework.    
A project can be used in its minimised as well as its original format.    
Minimised files are more portable and so easier to use if git clone is not available in an environment.   

***

[Menu](#M) 
<a name="SU"></a>
## Setup

```bash
# [1] Get bash-x-projects.    

# Change to the parent folder of the bash-x project. 
# This repository will become a sibling folder.

$ git clone ssh://git@git.swisscom.com:7999/csl/bash-x-projects.git

# [2] Setup bash-x-project.

# Follow the README for the project.

```    
***

[Menu](#M) 
<a name="VS"></a>
## Versions    

Each minimised project version is recorded as a hash in its version table in its README.    
The master branch always has the latest stable version and older versions are added to their own branch.    

```bash
# Run this command locally to verify the integrity of the minimised framework file.     
$ sha256sum <bash-x-project-name.min>
```
