
---

## Installation

1. **Open PowerShell with Remote Permissions**

   ```powershell
   Set-ExecutionPolicy RemoteSigned -scope CurrentUser
   ```

2. **Download the Installation Script**


   ```powershell
   irm get.scoop.sh -outfile 'install.ps1'
   ```

3. **Run the Installation Script**


   ```
   .\install.ps1 -ScoopDir 'your desired scoop directory' -ScoopGlobalDir 'directory for future global installations' -NoProxy

   ```



---
