# Creating a 2-tier architecture

Two tier architecture should be created on the AWS cloud with two servers deployed on Elastic Compute Cloud (EC2) Instances.

![Alt text](VPC-Architecture-1.jpg "a title")



## Why do we need to make a 2-tier architecture ?

![Alt text](AWS11.PNG "a title")

We need to make 2-tier architecture due to the risk of the monolith architecture failing and being completely unaccessable, users should still be able to access the app and be redirected to another page in the case of database failure. It also provieds security by keeping the data seperate from the app greater performance reliability and cost reduction.

## Why do we need to refactor a monolithic  architecture into a 2-tier?

Refactoring our monolithic architecture into two tiers is necassery to keep the application and database seperate and so these can function independantly, one does not disable the other.

## Why did we do it on the cloud?

Building two tier architecture on the cloud delivers all of the other benefits of hosting on the cloud.

## How does this fit into DevOps?

Devops is about improving our software in parallel , by having seperate components that can work independantly, Devops teams can improve the app without worrying about compromising functionality.

## How does this fit into agile/ SCRUM?

Having more than one tier allows improvemnts in smaller increments which is more in keeping with the scrum principles than monolithic which may have single larger releases.