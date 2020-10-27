Dump Azure ARM VMs to CSV
=========================

            

Looks up details of any Azure Resource Manager (ARM) Virtual Machines across whatever subscriptions you have access to, and writes them to a .CSV file. This allows you to easily analyse the details in Excel, for example to show charts or Pivot Tables listing
 VMs by size, status, location, etc.** *** *


Writes the following information about each VM:


  *  Subscription Name 
  *  Deployment model (ARM) 
  *  VM Name 
  *  Resource Group Name 
  *  Location 
  *  VM Size 
  *  Status 
  *  Availability Set ID 

Usage:


 

If you omit -TenantId then the file will contain VMs from all subscriptions across all Azure Active Directory tenants you can access.

If you omit -File then the file will be written to 'Azure-ARM-VMs.csv' in the current directory.


To do the same with Classic (ASM) VMs, see [Dump Azure Classic VMs to CSV](https://gallery.technet.microsoft.com/scriptcenter/Dump-Azure-Classic-VMs-to-d964d3ce)**.


Enjoy!


        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
