# VagrantLab-1

# Vagrant Setup Guide

## Installation

### Step 1: Install and Configure Vagrant
1. Download and install Vagrant on your operating system.
   - **Link**: [Vagrant Downloads](https://www.vagrantup.com/downloads)
2. Follow the installation instructions based on your OS.

### Step 2: Verify the Installation
After installing Vagrant, verify it by opening a new command prompt or console, and checking that Vagrant is available:

```bash

$ vagrant

#Create a new directory for the project:
$ mkdir vagrant_getting_started

#Move into the new directory:
$ cd vagrant_getting_started

# Initialize the Project
$ vagrant init


#Configuring Vagrant with a Box
Vagrant.configure("2") do |config|
  config.vm.box = "hashicorp/bionic64"
end


#Bringing Up the Virtual Machine
$ vagrant up


#Accessing the Virtual Machine
$ vagrant ssh


#Stopping and Destroying the Virtual Machine

###To stop the virtual machine without deleting it:
$ vagrant halt

###To completely destroy the virtual machine, freeing up resources:
$ vagrant destroy









