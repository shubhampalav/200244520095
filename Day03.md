# <h4>Private Key & Public Key:</h4>
Public Key is required to encrypt but it cannot decrypt. For decryption, the private key needed. So private key should not be shared.
In AWS, the .pem file that the user gets is a private key. The public key is set by AWS inside EC2. So, if any user has our .pem file, he can access our EC2.



# <h4>Linux Commands:</h4>

1. clear -> clear screen
2. ls -> list dir/file
3. pwd -> present working directory
4. cd -> change directory
5. mkdir -> make directory/create dierectory
6. vi -> To create/open a file in Editor



# <h4>Relative and Absolute Path:</h4>
**Absolute Pathnames:**
- It starts from the root and follows the tree branch until path to desired directory/file is reached.
Eg: /home/ec2-user/main


**Relative Pathnames:**
- It starts from current directory and we can navigate to any directory(till root) using this.
Eg: 
- .      -> Working directiry
- ..     -> Working directory's parent directory
- ../..  -> Parent's Parent Directory



# <h4>RDS:</h4>
It stands for Relational Database Service. This is an example of PaaS.It provides a relational database on cloud and we can access it from our local machine. Here, the responsibility of stability of the database is taken by AWS. So there is no chance of any outage of the service. Also, AWS keeps a backup of the used database.
