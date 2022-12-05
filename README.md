# Docker Open Class

course material related to Docker and containers, intended for in-training new developers.
## 0. What is Docker
In a few words: Docker is an open source software that help us to **DEPLOY** applications without installing all the stuff required to make it work through a technology called container. 
## 0.1 Containers... Containers? Containers!
A container is a package of software that contains all the source code and its dependencies, for example, in the tabletop game Dungeons and Dragons you need to start buying books to know the rules, world building, gameplay, etc. but if you want to play right now, theres a starter kit which contains all the items to play immediately without knowing all the background, just open the box read a few pages and play, that's awesome, right? Well containers can act as a starter kit of a software application.

<img src="img/../imgs/dnd.jpg" alt="just works" width="200">

## 1. Documentation
The first place to start is <a href="https://docs.docker.com/"> the docs </a>, this is your best resource because is written by the creators 

## 2. Obtain Docker
If is your first time installing and working with docker, maybe it will be a little bit difficult, but theres always an answer in the docs 
### 2.1 How to install Docker in your OS

<br>

>1. <a href = "https://docs.docker.com/desktop/install/linux-install/"> Linux </a>
>2.  <a href="https://docs.docker.com/desktop/install/mac-install/">MacOS</a>
>3. <a href="https://docs.docker.com/desktop/install/windows-install/">Windows</a>


## **3. What, How, Why**
### **3.1 What**
As we mentioned, Docker is open source and can make the apps work with containers, a container is a lightweight unit, that includes all the packages of software that is needed to run an application:

- Source Code.
- System tools and libraries.
- Settings.

### **3.2 How**
The containers are part of the application layer (OSI), where the code is compiled.
#### **3.2.1 Containers as images**
A container image is a file which contains all the code  that allows it to run an only process, but in the industry this technology already exists and has a name: "Virtual machines", but a virtual machine needs to be initialized like a personal computer.
#### **3.2.2 Containers as standard**
As we mentioned a container can be used to run one application, but what if we need to create a new app based on the main app, well, you can create a standard container image,but you don´t need to start from zero, the Open container standard initiative (OCI) is the open governance structure with the purpose of create the open industry standards.

### **3.3 Why**
Standard, Lightweight and of course cheap, those are some of the reasons why companies use docker and their container technology. now it's time to work on our own containers.

## 4. Hands to work