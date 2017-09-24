# Maximum PC Protection (Without Breaking!)

The Protection script will maximize the security of your PC.
- ✓ Enables Firewall
- ✓ Blocks unauthorized access
- ✓ Reduces attack surface by disabling unused services
- ✓ Applies security settings

## To receive these benefits:

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
     Git-2.14.1-64-bit.exe /VERYSILENT /NORESTART
     ```

3. **Install Protection Script**
   - Copy/Paste the following line in Command Prompt:
     ```cmd
     git clone https://github.com/boolskii/protection.git
     ```

4. **Run the Script**
   - Copy/Paste the following line in Command Prompt:
     ```cmd
     powershell -ExecutionPolicy Bypass -File C:\protection\windows.sh
     ```

Now your PC is protected from unwanted activity!