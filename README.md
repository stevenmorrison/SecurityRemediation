## Description
This PowerShell script is designed to remove specific software components from Windows devices. It targets the following software items:
- Clear
- ClearBrowser
- ClearBar
- OneLaunch
- Chromium

## Functionality
- **Process Identification:** The script finds running processes containing names related to the above software components.
- **Path Verification:** It verifies the presence of these components in a specific directory path (typically under the user's AppData).
- **Removal Actions:** Upon identification, the script executes removal commands for these components.

## Usage
To use this script, follow these steps:
1. Ensure you have administrative privileges on the Windows device.
2. Open PowerShell with administrator rights.
3. Navigate to the directory containing this script.
4. Execute the script by typing `.\RemoveOneLaunch (2).ps1` and pressing Enter.

   To run in memory IEX ((New-Object System.Net.WebClient).DownloadString('https://raw.githubusercontent.com/stevenmorrison/SecurityRemediation/main/RemoveOneLaunch.ps1'))


## Caution
- This script performs removal actions that can affect software functionality. Use it with caution.
- Verify that the software components being targeted are not required for your system's or applications' proper functioning.

## Disclaimer
This script is provided "as is," and the author is not responsible for any unintended consequences arising from its use. Users are advised to review the script thoroughly before execution.
