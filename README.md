# Basic AWS EC2 Creation
## Silencer Scales Class7
-----------------------------------------------
### This repo contains homework to create an EC2 in AWS. I will soon add terraform files provisioning this resource.
-----------------------------------------------
## SCREENSHOT
![BASIC EC2 WEBPAGE](C:\Users\james\Documents\TheoWAF\class7\AWS\Homework\9.9.2025 Basic EC2")
-----------------------------------------------
# STEPS
## Creation Steps (all other options are default. DO NOT TOUCH!)
### 1. Search Security Groups in Search bar or select Security Group from sidebar under Network & Security
### 2. Select Orange Button Create Security Group
#### ****ONLY CHANGES NEEDED****
#### Give Name & Description
#### Inbound rules : HTTP | Source anywhere
### 3. Select Create Security Group
### 4. Search EC2 Instance in Search bar or Select Instances from sidebar under Instances
### 5. Select Orange button Create Instance
#### ****ONLY CHANGES NEEDED****
#### Create Key Pair
#### Link create Security Group
#### Advanced Details > User Data > Paste created script
### 6. Select Launch Instance
### 7. Go to Instance Summary and copy Public DNS
### 8. Paste in browser URL bar
------------------------------------------------
## Teardown Steps
### 1. Terminate Instance
#### Go to Instances, check instance, go to Instance State and select Terminate
### 2. Terminate Security Group
#### Go to Security Groups, select Security Group, go to Actions, and select Delete Security Group
