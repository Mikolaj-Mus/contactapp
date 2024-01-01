
# Contact App
#### Frontend

## Description
The frontend of the Contact App is a React application that allows users to add, edit, and delete contacts. The application provides a beautiful visual appearance with a modern design. It also allows for the storage of a large number of contacts in a clean and organized way.


The frontend provides a simple and intuitive interface for adding and editing contacts. Users can enter the contact's name, email address, phone number, and other information.

It communicates with the backend through REST APIs, which repository you can find [there](https://github.com/Mikolaj-Mus/contactapi).

![Application view](https://imgur.com/a/S3Cm2vz)

## Prerequisites
Make sure you have Docker installed on your machine. You can check this by entering the following command in the command prompt:

```bash
docker --version
```
If Docker is not installed, please refer to the official installation guides for your operating system:

- Docker Desktop for [Windows](https://docs.docker.com/desktop/install/windows-install/)
- Docker Desktop for [Mac](https://docs.docker.com/desktop/install/mac-install/)
- For Linux, follow the installation instructions for your specific distribution.
```bash
sudo apt-get update

sudo apt-get install docker.io
```
## Installation and Startup
Get image from my Docker Hub repository
```bash
docker pull mikolajmus/contactapp
```
or clone repository and build image
```bash
git clone https://github.com/mikolaj-mus/contactapp.git

cd contactapp

docker build -t mikolajmus/contactapp
```
Then start up the container
```bash
docker run -it -p 3000:3000 mikolajmus/contactapp
```
