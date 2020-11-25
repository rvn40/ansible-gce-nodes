# ansible-gce-simple-cluster
Deploy three gcp compute engines using ansible 2.10. To use this scripts you need to make sure you have rancheros on your gce image collections. If you haven't, you can follow the intruction [here](https://github.com/rvn40/instructions/blob/main/rancheros/upload-image-to-gcp.md) to import rancheros image. 

We also have to make sure that vpc, subnetworks, and firewall rules has been existed and configured first before we start to deploy all resources by using these scripts.

# Requirements
When you use this ansible scripts, make sure you have installed all of these packages in advance on your ansible host:

- Python3
- Python3-pip
- Git

It's also necessary to install all of these packages requirements using pip:

- ansible==2.10
- requests>=2.18.4
- google-auth>=1.3.0
- docker>=1.8.0 
- boto
- boto3

Prepare all of neccesary files like serviceaccount, ssh keys, bash, ssl, etc. Recommended to place those files under directory called "files".
