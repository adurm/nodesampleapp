# Node Sample App

The repository contains the development environment for a Nodejs app.

#### Prerequisites
- Packer
- Chef
- Git
- AWS Credentials
- Nodejs
- mongodb

#### Installation
- Clone this repository:
```
git clone git@github.com:adurm/nodesampleapp.git
```
#### Testing the NodeSampleApp_tf
- Execute the following commands in terminal:
```
cd tests
rake spec
```

#### Building the AMI using packer
- Validate and build the packer file using the commands below:
```
packer validate packer.json
packer build packer.json
```
- Once you have your AMI you can follow the steps in this repository to build an ec2:
https://github.com/adurm/first-terraform
