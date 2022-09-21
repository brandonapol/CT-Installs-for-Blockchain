# CT Installs Packages - Blockchain

Easy installation of requirements for CT's Blockchain coursework.

# Running the Installs 
## Mac/Linux:
Open your terminal using cmd+spacebar and typing "Terminal". 

In the terminal, copy and paste:
```bash 
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/brandonapol/CT-Installs-for-Blockchain/master/mac.sh)"
```

## Windows 
Open your command line interface. Copy and paste these TWO commands:
```bash 
$InstallFromCodingTemple = Invoke-WebRequest -Uri https://raw.githubusercontent.com/brandonapol/CT-Installs-for-Blockchain/master/windows.ps1 -UseBasicParsing

Invoke-Expression $($InstallFromCodingTemple.Content)
```

Should automatically install everything you need! Happy coding!
    