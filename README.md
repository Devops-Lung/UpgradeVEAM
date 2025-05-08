# UpgradeVEAM
Upgrade VEAM to 12.3.1 \ 
_Hello Anh Em_

   ## 1. Stop all Veeam services on the Veeam Backup Server.

       Get-Service Veeam* | Stop-Service -Force
      
  ##  2. Run Install VEAM 

  ## 3. Start VEAM again

       Get-Service Veeam* | Start-Service

# Good luck!
