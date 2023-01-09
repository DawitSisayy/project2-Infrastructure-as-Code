<<<<<<< HEAD
## Project 2 - Deploy a High-Availability Web App using CloudFormation
In this project, I have deployed web servers for a highly available web app using CloudFormation.  I have included the deployment screenshots and output url as well as infrastructure diagram in my repo. 



### Infrastructure Diagram 








### Output
The IP address of the load balancer

http://devop-webap-1rucjuo98ty55-765368377.us-west-2.elb.amazonaws.com/





=======
## ND9991 - C2- Infrastructure as Code - Supporting Material and Starter Code
This folder provides the supporting material and starter code for the "ND9991 - C2- Infrastructure as Code" course. This folder contains the following folders:
1. project_starter - It contains the starter code.
2. supporting_material - It contains the essential files (.yml, .json, .bat, .sh, and .jpeg) that were referred in the different lessons of this course.

In addition to the current repo, there is one more repository, [nd9991-c2-Infrastructure-as-Code-v1-Exercises_Solution](https://github.com/udacity/nd9991-c2-Infrastructure-as-Code-v1-Exercises_Solution) that contains the solution to the exercises and video demos.  
projectoutputs
http://devop-webap-1rucjuo98ty55-765368377.us-west-2.elb.amazonaws.com/
### Dependencies
##### 1. AWS account
You would require to have an AWS account to be able to build cloud infrastructure.

##### 2. VS code editor
An editor would be helpful to visualize the image as well as code. Download the VS Code editor [here](https://code.visualstudio.com/download).

##### 3. An account on www.lucidchart.com
A free user-account on [www.lucidchart.com](www.lucidchart.com) is required to be able to draw the web app architecture diagrams for AWS.


### How to run the supporting material?
You can run the supporting material in two easy steps:
```bash
# Ensure that the AWS CLI is configured before runniing the command below
# Create the network infrastructure
# Check the region in the create.sh file
./create.sh myFirstStack network.yml network-parameters.json
# Create servers
# Change the AMI ID and key-pair name in the servers.yml
# Check the region in the update.sh file
./update.sh mySecStack servers.yml server-parameters.json
```
>>>>>>> c1ee80e31adc0a7a4325cada9bf411acb33340fa
