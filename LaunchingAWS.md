# Setting up AWS

## Opening AWS

make sure region is ireland or whichever is necassry for this instance as it is regionally specific.

## Starting AWS instance

Navigate to EC2 from ireland then launch a new instance.

![Alt text](AWS2.png "a title")

scroll down to Application and OS image. change this to ubuntu 18.04, leave options on default

![Alt text](AWS1.png "a title")

Select the key pair for this instance, or create a new key pair. The key should be in the .ssh folder.

![Alt text](AWS3.png "a title")

Change Network Settings

![Alt text](AWS4.png "a title")

When ready launch the instance.

## Starting AWS instance on GitBash

If, for some reason the .pem key pair cannot be copied into the ssh folder, another can be made by making the file there and using nano to copy and paste a key into it. Make sure there are no spaces at the beginning or end of the text and you should be inside your .ssh file.

$ `nano devops-tech201.pem`

![Alt text](AWS6.png "a title")

## Setup on Gitbash

Then do this, where chmod means to change the permissions , 400 means read only (0 for other permissions) and then our file name at the end.

$ `chmod 400 devops-tech201.pem`

![Alt text](AWS5.png "a title")

Now we have to get a line from our AWS console to complete the next step. by clicking on our instance in the list of instances and then connect, this line should be generated for us.

![Alt text](AWS7.png "a title")

use this line in the GitBash terminal next

$ `ssh -i "devops-tech201.pem" ubuntu@ec2-3-252-250-105.eu-west-1.compute.amazonaws.com`

