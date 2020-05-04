<h4>AWS CLI:</h4>
The AWS Command Line Interface (CLI) is used to control multiple AWS services from the command line.
We can create multiple services at the same time using AWS CLI.
Following syntax for AWS CLI:  
aws *<service-name> [command-option]*


<h4>IAM Roles:</h4>
AWS Identity and Access Management (IAM) is used to provide security to AWS services. Using IAM, we can give permissions to allow and deny certain things to certain users only.

<h4>Secret Key:</h4>
There is a key, secret key associated with each account using which we can access the AWS account. This is like the ID and Password of our account so it shouls not be shared.


<h4>Availability Zone:</h4>
The data centre is scattered over a geographical region so that in case of any natural disaster, the data is not lost.

<h4>IAM Roles vs Secret Key:</h4>
IAM roles are AWS specific. So we can use them inside AWS only. On the other hand, secret key is useed when we access AWS from outside.



<h4>EC2 vs RDS:</h4>
EC2 | RDS
------------ | -------------
EC2 is managed by AWS but if we install any application in EC2 it will be managed by us | Only server is provided. So there is no cost of OS and other services for full-time but as per use.
If there is any problem in MySQL, AWS will not be responsible | If there is any problem in MySQL, AWS will take responsibility.
