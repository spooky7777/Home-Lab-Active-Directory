# Home Lab Running Active Directory (Oracle VirtualBox) | Add Users w/PowerShell

<figure><img src=".gitbook/assets/pivd.png" alt=""><figcaption><p>Overview of the Home Lab</p></figcaption></figure>

***

## TL;DR

Technologies used: Oracle VirtualBox, PowerShell, VMWare, Windows

I set up a home lab to run Active Directory using Oracle VirtualBox. First, I created a Windows Server virtual machine (VM) to serve as my domain controller. After setting up the VM, I installed and configured Active Directory Domain Services (AD DS) and set up the domain. Once the domain was ready, I used PowerShell scripts to add users to my Active Directory efficiently, showcasing how automation can simplify user management tasks.

***

## Introduction

In this guide, I'll walk you through how I set up a home lab to run Active Directory using Oracle VirtualBox. I'll cover creating a Windows Server virtual machine (VM) to act as a domain controller, installing and configuring Active Directory Domain Services (AD DS), and using PowerShell to add users to Active Directory. This setup will help you understand how to manage an Active Directory environment and automate user management tasks.

***

## Stage 1: Setting Up Oracle VirtualBox and Creating a VM

* **Download and Install Oracle VirtualBox:** I started by downloading and installing Oracle VirtualBox on my computer from the official website.

<figure><img src=".gitbook/assets/Screenshot 2024-08-03 121716.png" alt=""><figcaption></figcaption></figure>

* **Create a New Virtual Machine:** Next, I launched VirtualBox and created a new VM. I chose "Windows Server" as the operating system and allocated appropriate resources (CPU, RAM, and disk space) for the server.]

***

**Stage 2: Installing Windows Server on the VM**

* **Download Windows Server ISO:** I downloaded the Windows Server ISO file from the official Microsoft website.
* **Install Windows Server:** I started the VM and mounted the Windows Server ISO file. I followed the installation wizard to install the operating system on the VM.
* **Configure Windows Server:** After installation, I configured the server settings, such as setting a strong password for the administrator account and adjusting network settings to ensure the VM could connect to the internet.
