# Welcome to InVerte Submodule Repository V2
This repository serves as a submodule for the main software team Q2-2023. It provides access to the 3 main software components: Firmware, Cloud, AI/ML, and Client. 
#### Copyright ©2023, InVerte FoodTech Inc. - All rights reserved.

# Getting Started
To use this submodule, follow the instructions below.

### Installation: 

1. Clone the *main project* repository:
   ```shell
   git clone https://github.com/jarco0204/inverte-v2.git

2. Initialize and Update the submodules: 
    ```shell
    git submodule init
    git submodule update

### How to Update (Pull) Submodules:

1. Navigate to the submodule directory and run:
    ```shell
    git submodule update --remote
#### OR
1. Navigate to root directory and run:
    ```shell
    git submodule foreach git pull origin master

### How to Make Changes (Push) Submodules: 
+ When you make changes in a submodule, you need to commit and push those changes separately in the submodule's repository.

+ In the main project repository, you also need to commit and push the updated reference to the submodule. This indicates which commit of the submodule should be used by the main project.
    ```shell
    git add <submodule-path>
    git commit -m "[WHERE]:[ACTION]:[DESCRIPTION]"
    git push origin master

# OUR REPOS

### AI-v1
Latest Version: 1.0.0
#### How to Run?

### Firmware-v3
Latest Version: 3.0.0
#### How to Run?

### Serverless-v1
Latest Version: 1.0.0
#### How to Run?
