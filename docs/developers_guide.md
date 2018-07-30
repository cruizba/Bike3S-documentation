# Prerequisites
1. JDK 1.8
2. Maven 3.5
3. Node.js 8.9
4. Git

Please make sure that all the binaries are registered in your PATH.

The package manager NPM is also required but is usually bundled with the Node.js installer.

# Getting Started for Development 
This project is development environment agnostic. You can use an IDE or just the command line.

## General overview of the software architecture
The project is separated in two main parts: a **backend** and a **frontend**.

![It shows the architecture of the software. It shows two clear parts: backend and frontend](img/Arquitecture_10.png?raw=true "Software arquitecture")


The **backend** is related to all the simulation logic and is implemented in Java.

The folder `/backend-bikesurbanfleets` contains this part of the project.

The **frontend** is related to all the GUI and data analysis of the simulations. It is implemented in TypeScript, using
Angular and Electron.

The folder `/frontend-bikesurbanfleets` contains this part of the project.

## Setup

1. First of all, be sure you have all the [Prerequisites](#prerequisites) installed and working in your system.
2. Execute this in the project directory.
```
git clone https://github.com/stimonm/Bike3S.git
cd Bike3S
npm install
node fuse configure:dev
```

## Execute Frontend 

You can now execute your program and try it just by running:

```
node fuse build:frontend
```


## Execute Backend

TODO - Execute Backend users generator and Backend Users Core example


## Build From Command Line
To build the backend execute:
```
node fuse build:dev-backend
```
To build the frontend and execute the GUI:
```
node fuse build:frontend
```

To build all the project:
```
node fuse build:dist
```

# Distribute
To distribute an executable or installer for your OS, just run
```
npm run distribute
```
Executables are generated in `build/dist/`

# Fundamentals

TODO - Link to pdf developer manual

