The Protection script will maximize the security of your PC.
✓ Enables Firewall
✓ Blocks unauthorized access
✓ Reduces attack surface by disabling unused services
✓ Applies security settings
To recieve these benefits:
1. Open Command Prompt
    Press Windows + R
    Type 'cmd'
    Press Enter
2. Install Git
    Copy/Paste the following line in Command Prompt
    '''
    powershell -Command "Invoke-WebRequest -Uri https://github.com/git-for-windows/git/releases/download/v2.14.1.windows.1/Git-2.14.1-64-bit.exe -OutFile Git-2.14.1-64-bit.exe"
    '''
    Once its downloaded, Copy/Paste the following line in Command Prompt
    '''
    Git-2.14.1-64-bit /VERYSILENT /NORESTART
    '''
3. Install Protection script.
    Copy/Paste the following line in Command Prompt
    '''
    git clone https://github.com/boolskii/protection.git
    '''
4. Run the script.
    Copy/Paste the following line in Command Prompt
    '''
    powershell -ExecutionPolicy Bypass -File C:\protection\windows.sh
    '''
Now your PC is protected from unwanted activity!
# protection
# protection
# protection