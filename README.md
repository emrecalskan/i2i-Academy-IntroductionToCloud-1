# i2i-Academy-IntroductionToCloud-1

Welcome! This repository was created as part of my **Introduction to Cloud** course homework at **i2i Academy**.

# Project Overview

The main gol this assignment was to get hands-on experience with cloud infrastructure. I spun up a basic Linux Virtual Machine (VM) on a cloud platform,
configured its connectivity, and performed some fundamental linux operations.

For this homework, I choose Google Cloud Platform(GCP) as my cloud service provider.

# Cloud Environment
- Item: Description
- Cloud Provider:	Google Cloud Platform
- Service:	Compute Engine
- Virtual Machine Name:	cloud-homework-vm

# Step-by-Step Walkthrough

 #1 Setting up the Cloud Infrastructure
* Set up my GCP account and created a brand new project.
* Enabled the **Compute Engine API**.
* Configured and launched a lightweight Debian Linux Virtual Machine named `cloud-homework-vm`.
* Allocated a public IP address for the VM to verify external connectivity.

#2. Connectivity & Ping Test
To make sure the VM was up, running, and reachable from the outside world,
I grabbed its public IP (`34.135.237.183`) and ran a quick ping test from my local machine's terminal:

 ''Bash
 ping 34.135.237.183
Result: The test was fully successful with 0% packet loss, meaning the network configuration was spot on.

#3. SSH Connection & Linux Basics
Once connectivity was confirmed, I SSH'd into the instance using the GCP browser terminal and ran the following commands to create and verify a simple text file:

Bash

# Creating the file and writing the text
echo "Hello i2i Academy!" > hello.txt

# Verifying the file content
cat hello.txt

Terminal Output:
Plaintext:  Hello i2i Academy!


# Repository Content

This repository contains only the README file because this homework does not include source code or configuration files.
According to the homework requirements, screenshots and homework instruction documents are not uploaded to this repository.

Note: Following the official homework guidelines, screenshots and the final PDF assignment document are not uploaded here. Those files, along with this repository link, have been submitted directly via Google Classroom. This repository is kept public as requested by the instructions.
  
