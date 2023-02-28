#  Infrastructure as Code
## This repository contains IaC that deploys a high-availability web app using CloudFormation.

## Dependencies
1. AWS account
You would require to have an AWS account to be able to build cloud infrastructure.

2. VS code editor
An editor would be helpful to visualize the image as well as code. Download the VS Code editor here.

3. An account on www.lucidchart.com
A free user-account on www.lucidchart.com is required to be able to draw the web app architecture diagrams for AWS.

`# Ensure that the AWS CLI is configured before runniing the command below`
`# Create the network infrastructure`
`# Check the region in the create.sh file`
`./create.sh myFirstStack network.yml network-parameters.json`
`# Create servers
`# Change the AMI ID and key-pair name in the servers.yml`
`# Check the region in the update.sh file`
`./update.sh mySecStack servers.yml server-parameters.json`


## Files included:
- `network.yml` (./network.yml) - CloudFormation network infrastructure stack description.

- `network-parameters.json` (./network-parameters.json) - Parameters file for the network infrastructure stack

- `servers.yml` (./servers.yml) - CloudFormation servers infrastructure stack description

- `servers-parameters.json` (./servers-parameters.json) - Parameters file for the servers infrastructure stack

- `create.sh` (./create.sh) - bash script for creating stack

- `create.bat` (./create.bat) - bash script for creating stack

- `update.sh` (./update.sh) - bash script for updating stack

- `update.bat` (./update.bat) - bash script for updating stack

- `infrastructure-diagram.png` (./infrastructure-diagram.png) - infrastructure diagram

- `Stack screenshot` (./screenshot/stack.png) - Screenshot for infrastructure stacks

- `website screenshot` (./screenshot/webpage.png) - Screenshot for Udagram website
