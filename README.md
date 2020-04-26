# Node Sample App :computer: :cd:

This project consists of a Nodejs App and a Mongo Database.

- The repository contains a development environment for the project. It uses node package manager and provisioning of the app/db to display a working app, posts and fibonacci on a web browser.

- Implementation of a reverse proxy within the application in order to add security, performance and reliability.

### Prerequisites
- In order to for this project to run you must have the items below:

```CSS
- Packer.json
- Chef
- AMI
- Berksfile
- Git
- AWS Credentials
- pem key
- Nodejs
- mongodb/mongod
- Atom
```

### Installation
- Download this repository, open your terminal and run:
```python
git clone git@github.com:Aymz96/NodeSampleApp_tf.git
```
### Testing the NodeSampleApp_tf
- To test the files you must cd into the Nodejs_Dev_Environment:
run:
```python
cd tests
```
run:
```python
rake spec
```
## Installation procedure
- Displayed below are the steps needed to take in order to get the files working correctly.

### Berksfile
- To download the relevant Cookbook files which Packer will be using in the later build process run the following command in the directory:
```python
berks vendor cookbooks
```

### Packer
- Validate the packer file using the command below:
```python
packer validate packer.json
```
- The terminal output will dispay `Validate successful`

- Now build your AMI using the following command:
```python
packer build packer.json
```
- The will successfully create your new AMI and display it's ID, you can now move on to the next repository to create a Terraform.
```python
https://github.com/Aymz96/First_Terraform
```

#### Author
**Ayman Yousfi** - *Junior DevOps Engineer* - [Aymz96](https://github.com/Aymz96)
