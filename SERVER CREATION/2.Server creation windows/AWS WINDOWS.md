<div align="center">
  <img src="https://github.com/Adarsh1169/AWS-internship/blob/main/SERVER%20CREATION/2.Server%20creation%20windows/screenshots/Screenshot%202025-07-13%20200601.png?raw=true"/>
</div>


<p align="center">
  <img src="screenshots/awswindowslogo.gif" width="120"/>
</p>

<h1 align="center" style="color:#2E86C1;">AWS EC2 - Windows Server Creation Guide</h1>
</br>

<h3 align="left" style="color:#2E86C1;">📝 Introduction</h3>

---

This guide walks you through creating a **Windows Server** on AWS EC2 using the AWS Management Console. Steps include launching the server, configuring networking, connecting via RDP, and setting up IIS for hosting a webpage.

</br>

<h3 align="left" style="color:#2E86C1;">🧭 Step-by-Step Instructions</h3>

---

### 📌 Step 1: Search EC2 and Click "Launch Instance"
- Go to the AWS Console
- Search for **EC2**
- Click on **"Launch Instance"**

<p align="center">
  <img src="https://github.com/Adarsh1169/AWS-internship/blob/main/SERVER%20CREATION/2.Server%20creation%20windows/screenshots/Screenshot%202025-07-13%20201041.png?raw=true" width="600"/>
  <br/>
  <i>Figure 1: Launch EC2 from AWS Console</i>
</p>

---

### 📌 Step 2: Provide a Name for Your Server
- Example name: `windows-demo-server`

<p align="center">
  <img src="https://github.com/Adarsh1169/AWS-internship/blob/main/SERVER%20CREATION/2.Server%20creation%20windows/screenshots/Screenshot%202025-07-13%20201254.png?raw=true" width="600"/>
  <br/>
  <i>Figure 2: Naming the EC2 instance</i>
</p>

---

### 📌 Step 3: Choose the Operating System
- Select **Microsoft Windows Server 2019 Base** or later

<p align="center">
  <img src="https://github.com/Adarsh1169/AWS-internship/blob/main/SERVER%20CREATION/2.Server%20creation%20windows/screenshots/Screenshot%202025-07-13%20201312.png?raw=true" width="600"/>
  <br/>
  <i>Figure 3: Selecting the Windows OS</i>
</p>

---

### 📌 Step 4: Select Instance Type
- Use **t3.micro** (Free Tier eligible)
- Suitable for basic testing and small workloads

<p align="center">
  <img src="https://github.com/Adarsh1169/AWS-internship/blob/main/SERVER%20CREATION/2.Server%20creation%20windows/screenshots/Screenshot%202025-07-13%20201333.png?raw=true" width="600"/>
  <br/>
  <i>Figure 4: Selecting the instance type</i>
</p>

---

### 📌 Step 5: Configure Key Pair Login
- Select or create a **key pair**
- Download the `.pem` file — required to decrypt your Windows admin password

<p align="center">
  <img src="screenshots/step5.png" width="600"/>
  <br/>
  <img src="screenshots/step5.1.png" width="600"/>
  <br/>
  <img src="screenshots/step5.2.png" width="600"/>
  <br/>
  <i>Figure 5: Key pair configuration for secure access</i>
</p>

---

### 📌 Step 6: Configure Network Settings
- Allow:
  - ✅ RDP (Port 3389) for remote desktop connection
  - ✅ HTTP (Port 80)
  - ✅ HTTPS (Port 443)

<p align="center">
  <img src="screenshots/step6.png" width="600"/>
  <br/>
  <img src="screenshots/step6.1.png" width="600"/>
  </br>
  <i>Figure 6: Configuring the security group for RDP & web access</i>
</p>

---

### 📌 Step 7: Launch the Instance
- Click **“Launch Instance”**
- Wait for instance status to become **"running"**

<p align="center">
  <img src="screenshots/step7.png" width="600"/>
  <br/>
  <i>Figure 7: Launching the EC2 Windows instance</i>
</p>

---

## ✅ Final Result

<p align="center">
  <img src="screenshots/final1.png" width="600"/>
  <br/>
  <img src="screenshots/final2.png" width="600"/>
  </br>
  <img src="screenshots/final3.png" width="600"/>
  </br>
  <i>Figure 8: Windows EC2 instance running successfully</i>
</p>

