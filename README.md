# AWS-Launch-Scripts
This repo contains scripts to automatically launch pentesting practice websites without the need to configure them by hand.

## Basic Process
- Select **services** > **compute** > **EC2**
- Select **EC2 Dashboard** > **Create Instance** > **Launch Instance**
- Select **Ubuntu Server 18.04 LTS (HVM), SSD Volume Type** > **Select**
- Select **t2.micro** >  **Next: Configure Instance Details**
  - Click **Advanced Details**
  - Paste script into the **User Data** field
- Select **Next: Add Storage**
- Select **Next: Add Tags**
- Select **Next: Configure Security Group**
- Set the following values:
  - Type: All Traffic
  - Source: My IP
- Select **Review and Launch**
- Select **Launch**
  - Chose/Create/Continue without a key pair
  - Select **Launch Instances**
- Select the first link after **The following instance launches have been initiated:**
- Select the instance > **Description** > **IPv4 Public IP**
