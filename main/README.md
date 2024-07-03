# 🎨 PowerShell Profile (Pretty PowerShell)

A stylish and functional PowerShell profile that looks and feels almost as good as a Linux terminal.

Features:

    * Installs Winget
    * Installs latest PowerShell version (7+)
    * Installs Windows Terminal (if on Win10)
    * Set Powershell 7 as default in Terminal
    * Installs Oh My Posh
    * Installs Chocolaty
    * Installs Nerd Fonts
    * Installs Zoxide
    
## ⚡ One Line Install (Elevated PowerShell Recommended)

Execute the following command in an elevated PowerShell window to install the PowerShell profile:

```
irm "https://github.com/chiefspecialk/powershell-profile/raw/test/setup.ps1" | iex
```

## 🛠️ Fix the Missing Font

If after running the script, you find a downloaded `cove.zip` file in the folder you executed the script from. Follow these steps to install the required nerd fonts:

1. Extract the `cove.zip` file.
2. Locate and install the nerd fonts.

## Customize this profile

**Do not make any changes to the `Microsoft.PowerShell_profile.ps1` file**, since it's hashed and automatically overwritten by any commits to this repository.

After the profile is installed and active, run the `Edit-Profile` function to create a separate profile file for your current user. Make any changes and customizations in this new file named `profile.ps1`.

Now, enjoy your enhanced and stylish PowerShell experience! 🚀
