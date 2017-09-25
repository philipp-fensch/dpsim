## Tasks
- Sychronous generator model interfaced through current source
- connect with CIM parser
- include boost library for additional math functions and general tasks

## Setup
### Windows
Install Visual Studio 2017 C++ Desktop development package plus Windows 8.1 SDK
### Libraries

#### Windows
Create a folder called Libraries in DPsim and copy the Eigen library in there.

#### Linux
Copy the Eigen folder to /usr/local/include/eigen using `sudo cp -rf eigen /usr/local/include/eigen`

## Basic git commands
* initial download: git clone [url]
* download newest version: git pull
* see changed files: git status
* add modification or new file to commit: git add --all OR git add [filename]
* create commit: git commit -m 'your comment'
* push commits from local repo to server: git push

## Netlist structure
* **separate items with comma and end line with comma**
* see examples and store new netlist files in DPSolver/netlists
* first line: time step, final time e.g. 0.001,0.1,
* following lines: class name, component name, node1, node2, paramter1, parameter2... e.g. Resistor,R1,0,1,10
