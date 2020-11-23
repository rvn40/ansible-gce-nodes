# ansible-gce-simple-cluster
Deploy three gcp compute engines using ansible 2.10

# Requirements
Before you use this ansible scripts, make sure you have installed all of these package on your ansible host:

- Python3
- Python3-pip
- Git

You need also install all of these packages requirements using pip:

- ansible==2.10
- requests>=2.18.4
- google-auth>=1.3.0
- docker>=1.8.0 
- boto
- boto3

Prepare all of neccesary files like serviceaccount, ssh keys, bash, ssl key, etc. Recommended to place those files under directory "files".
