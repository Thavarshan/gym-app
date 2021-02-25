# Rathnayake Gym Application

## Introduction

Rathnayaka GYMS is a fitness center which has been grown rapidly throughout the country. They provide a quality healthcare service and giving their members control over their health is paramount at all Rathnayaka GYMS. They help members prevent and overcome degenerative diseases, achieve their optimum fitness goals, realize personal lifestyle development objectives and rehabilitate them into good health. This is accomplished by designing exercise programs which are effective, efficient and motivational.

Due to increasing number of members they have planned to automate their billing process. Imagine that you are a software developer in this project and design and develop a system for Rathnayaka GYMS.

**Basic functions of the app:**
- View fitness package details
- View food supplement details
- Calculate bill
- Information about business.

## Installation

Project is only installable through `git` and should be cloned from the remote repository. To clone the project to your local development environment or even production environment, run the below `shell` command through your terminal.

```shell
git clone git@github.com:Thavarshan/gym-app.git gym
```

You should see a directory called `gym` at the place where you cloned the project.

## Usage

If the project does not contain a executable file named `gym` the application will have to be compiled.

### Mac/Linux Systems

If you are running a `unix` based system you can execute the application by running:

```shell
./build/gym
```

### Windows Systems

On Windows systems run:

```shell
./build/gym.exe
```

On both cases a terminal window should open with a prompt asking you to choose and option.

> When running the executable `gym` or `gym.exe` make sure it is located near the `details` directory.

## Development

After cloning the project, the basic project structure should contain a `src` directory and `tests` directory. The `src` directory contains all the source files of the application while the `tests` directory contains all relevant tests for the application.

#### Compilation

##### Clang++

Use the following command when using `clang++` to compile the project.

```shell
/usr/bin/clang++ -std=c++17 -stdlib=libc++ -g -I/src/includes ./src/*.cpp -o ./build/gym
```

##### CMake

If you prefer to use `cmake` to build the application use the following command.

```shell
/usr/local/bin/cmake --build . --config Debug --target all -- -j 6
```

> This application and project as a whole was developed and is maintained by **Thavarshan Thayananthajothy**.
