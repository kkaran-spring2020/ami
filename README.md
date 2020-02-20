# ami

#Student Information

Name	NEU ID	  Email Address
Karan	001449291	karan.k@husky.neu.edu

# Requirements
- Packer
CirclCI

# Installation guide

- Packer Installation

# Run Instruction

## clone directory

## validate template

## Packer validate template.json

## Build Template

- packer build -var-file=./vars.json template.json

# CircleCI

## build_deploy job:

- Install packer
- validate template file
- build the template

# Output

- Create AMI in accounts linked and share with accounts mentioned in ami_users object.
