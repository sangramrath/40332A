# Launch an Azure VM with Server 2012 DC with either DS_V3 or E_V3 machines.

# Open PowerShell in Administrator mode
Enable-WindowsOptionalFeature –Online -FeatureName Microsoft-Hyper-V –All -NoRestart
Install-WindowsFeature RSAT-Hyper-V-Tools -IncludeAllSubFeature
# Reboot Server
# Login to Server Manager and verify Hyper-V role is enabled

