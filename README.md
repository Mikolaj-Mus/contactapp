
# Contact App
#### Frontend

## Description
The frontend of the Contact App is a React application that allows users to add, edit, and delete contacts. The application provides a beautiful visual appearance with a modern design. It also allows for the storage of a large number of contacts in a clean and organized way.


The frontend provides a simple and intuitive interface for adding and editing contacts. Users can enter the contact's name, email address, phone number, and other information.

It communicates with the backend through REST APIs, which repository you can find [there](https://github.com/Mikolaj-Mus/contactapi).

![Zrzut ekranu 2024-01-01 171615](https://github.com/Mikolaj-Mus/contactapp/assets/114436599/b3e5090a-1a07-453c-b987-ae25e35d2571)


## Usage
By clicking the blue button in the top right corner, you can add a new contact.


https://github.com/Mikolaj-Mus/contactapp/assets/114436599/02c5b215-1b85-4202-8087-89037117dc3d


After entering the details, you can save the person, and they will appear in your contacts.


https://github.com/Mikolaj-Mus/contactapp/assets/114436599/148081f9-2616-4470-9bbf-db36f466d1c8


If you want to modify contact details, you can do so by clicking on the contact.


https://github.com/Mikolaj-Mus/contactapp/assets/114436599/735bcad7-ec6c-4aa6-a1ea-fc8b8ff1eab1


Similarly, you can change the profile picture of your contact.


https://github.com/Mikolaj-Mus/contactapp/assets/114436599/63744e26-18a8-43d9-b944-e4d807f90f98

Don't worry if your contact list is long; all of them will fit.


https://github.com/Mikolaj-Mus/contactapp/assets/114436599/5e752c80-6f35-4658-aa64-e0e70dcb51ba



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
## License

This project is currently not licensed. The project is continuously being developed by me, and it is a work in progress.
