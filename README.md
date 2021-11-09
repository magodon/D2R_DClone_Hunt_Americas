# D2R DClone Hunt Americas
Run as an Administrator in CMD to create Windows Defender Firewall rules to block specific IP ranges for DClone hunting in Diablo 2 Resurrected Region: Americas

netsh advfirewall firewall add rule name="Disable 34.x.x.x - D2 DClone Hunt" dir=out action=block program="YOUR_D2R_EXE_PATH_HERE" enable=no remoteip=34.1.1.1-34.116.255.255,34.118.1.1-34.255.255.255 profile=domain,private,public

netsh advfirewall firewall add rule name="Disable 35.x.x.x - D2 DClone Hunt" dir=out action=block program="YOUR_D2R_EXE_PATH_HERE" enable=no remoteip=35.1.1.1-35.255.255.255 profile=domain,private,public

netsh advfirewall firewall add rule name="Disable 158.115.221.x - D2 DClone Hunt" dir=out action=block program="YOUR_D2R_EXE_PATH_HERE" enable=no remoteip=158.115.221.1-158.115.221.255 profile=domain,private,public

netsh advfirewall firewall add rule name="Disable 158.115.221.x - D2 DClone Hunt" dir=out action=block program="YOUR_D2R_EXE_PATH_HERE" enable=no remoteip=158.115.221.1-158.115.221.255 profile=domain,private,public
