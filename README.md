Start StorSimple Virtual Appliance
==================================

            

 

 

This runbook starts the StorSimple virtual appliance in case it is in shut down state. This script is to be used in the context of ASR (Azure Site Recovery) recovery plan for workloads hosted on StorSimple devices. If the StorSimple virtual appliance is
 online, this step will be skipped. This script needs to be added to the ASR recovery plan as the first step after failover so that the further steps of mounting volumes by connecting iSCSI target will not fail.


        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
