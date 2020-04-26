# Nodejs & Mongodb Development Environment :computer: :cd:

This project consists of a Nodejs App and a Mongo Database.

- The repository contains a development environment for the project. It uses node package manager and provisioning of the app/db to display a working app, posts and fibonacci on a web browser.

- Implementation of a reverse proxy within the application in order to add security, performance and reliability.

### Prerequisites
- In order to for this project to run you must have the items below:

```CSS
- Packer.json
- AMI
- Terraform
- pem key
- npm
- git
- Java
- Nodejs
- mongodb/mongod
```

### Installation
- In order to download this repository, open your terminal and run:

```python
git clone git@github.com:Aymz96/NodejsMongodb_Dev_Env.git
```
### Testing the files
- To test the files you must cd into the Nodejs_Dev_Environment:
run:
```python
cd tests
```
run:
```python
rake spec
```
- The tests will now run.

### Access the Vagrant machine.
run:
```python
vagrant up
```
run:
```python
vagrant ssh app
```
### Access the App inside the vm
- cd into the App:
```python
cd home/ubuntu/app
```
### Install npm
```python
npm install
```

### Running the App
run:
```python
npm start
```
### Displaying the App
- Once the app has started, open a new web browser and enter the following:

- `development.local` To view the app.

- `development.local:/posts` To view the posts.

- `development.local:/fibonacci5` To view the fibonacci.

### Success
- Tests have passed successfully.

#### Author
**Ayman Yousfi** - *Junior DevOps Engineer* - [Aymz96](https://github.com/Aymz96)
