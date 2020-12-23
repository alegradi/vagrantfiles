# This repo contains a collection of Vagrantfiles

## Description

These Vagrant configuration files were written to accomodate a mix of the below:
* Single or multiple instances
* SSH connection outside of Vagrant (to use Ansible for example)
* Private network IPs
* Additional disks

## Requirements 
(tested with the below versions, higher versions "should" also be compatible)

* Vagrant version 2.2.5
* Virtualbox 6.0

## Usage

1, Clone repo  
2, Make sure to update Vagrantfile as per your needs (SSH key, Distro)  
3, Run:  
`vagrant up` - to start the instance(s)  
`vagrant status` - to verify the state of the instance(s)  
`vagrant destroy` - to destroy the instance(s)
