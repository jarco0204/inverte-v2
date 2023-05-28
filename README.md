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
# THE CODE REPOSITORIES
## AI-v1
+ Latest Release: 1.0.0

+ [inverte-ai-v1](https://github.com/jarco0204/inverte-ai-v1)

# Getting Started
To use this *Python/Jupyter* Repository, follow the instructions below.

### Installation: 
• Make sure you have *Miniconda* installed in your machine to begin environment with correct versions.

### Running Scripts: 
+ *Windows*: Make sure you have GitBash enabled in your machine.

+ *Mac*: Open Terminal (Unix-based)

1. Update permissions of script with:
    ```shell
    chmod +x NAME_SCRIPT_HERE.sh

2. Run the script with:
     ```shell
    ./NAME_SCRIPT_HERE.sh

## Firmware-v3
+ Latest Release: 3.0.0
# Getting Started
To use this *C++* & *Arduino* Repository, follow the Documentation below:

+ [inverte-firmware-v3](https://github.com/jarco0204/inverte-firmware-v3)

+ [inverte-firmware-v3 Documentation](https://www.notion.so/inverte-ai/Firmware-cd5e2b6e5b6c4b9399aa28c4a36be48a?pvs=4)

## Serverless-v1
+ Latest Release: 1.0.0

+ [inverte-serverless-v1](https://github.com/jarco0204/inverte-serverless-v1)
# Getting Started

To use this *JS* Repository, follow the instructions below.
### Installation: 
• This is the set of lambdas that allow us to talk to our serverless API hosted in AWS Lambda, API Gateway & DynamoDB.