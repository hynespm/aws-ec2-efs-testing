# AWS EFS Testing repository

## Author: Patrick Hynes

This repository contains a cloudformation template to create an EFS and some EC2 instances in autoscaling groups.

To gain ssh access to the instances, you should create a ssh key in the console and add the property to the launch configuration.

### Repository Structure

* [infrastructure.template](infrastructure.template)
* [README.md](README.md)