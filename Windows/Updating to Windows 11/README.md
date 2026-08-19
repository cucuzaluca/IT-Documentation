## Updating to Windows 11



##New PC Setup Procedure
1. Back Up User Data        
    - Open File Explorer → This PC → Users.  
    - Locate the correct user folder.  
    - Enable hidden files (View → Show → Hidden items) 
    - Go into Local and Delete the one drive storage
    - Copy the entire user folder to the external hard drive for backup.
    - If there issues you can try to run the command sfc /scannow to try to fix corrupted files

 
 2. Check if TPM is Installed
    - Press Windows + R, type tpm.msc, and hit Enter.  
    - Confirm that TPM is present and enabled.
  

 3. Update the Firmware and BIOS
    - Identify the motherboard model.  
    - Search the manufacturer’s website for the latest BIOS/firmware update
    - Follow the official instructions — often you’ll need to: 
      - Copy the update file to a bootable USB drive
      - Enter the BIOS and select the update option to flash it

  
 4. Check or Create the CLIENT Number
    - Look at the PC name for the client number
    - If unsure, remote the server and verify the record there
   
      
 5. Install Windows
    - Boot the system using a Windows installation USB.  
    - Install Windows 11 (do not update its default drivers — they’ll be replaced later)

    
 6. Upgrade Drivers
    - After Windows installation, update all drivers to their Windows 11 versions, especially: 
    - GPU 
    - Chipset 
    - Network/Audio

  
 7. Domain
    - Join the system to the company domain.

    
 8. Windows Debloater
    - Run the Windows Debloater script to remove preinstalled apps.

      
 9. Install Required Applications
    Log in as Administrator for convenience, install the following, and remove desktop shortcuts after installation:
    - Office 365 
    - OneDrive 
    - Teams
    - MS Project 2010 (You must activate it)
    - PlanSwift (run update)
    - Sigma 
    - Bluebeam 
    - Adobe Acrobat 
    - DWG TrueView 
    - PowerToys 
    - PDF Creator
    - Webroot
   

    
 10. PlanSwift Setup
    - Fix the resolution issue: 
    - Hold Shift + Left Click on the shortcut → Properties → Advanced.  
    - Adjust display settings as needed. 
    - Use the shared serial number provided by the app to share.  
    - Load PlanSwift data: 
    - Go to This PC → Data Storage → New Folder,  
    - Locate the folder starting with “R”,  
    - Name the data folder accordingly.


 11. Extra Adjustments
    - Change the default search engine to Google.  
    - Printers 
    - Access the App Share drive via:\\nf-dc-1  
    - Run Windows Update to apply system patches.  
    - If the Admin account login fails, try logging in as:NEWFORMS\Administrator   
    - After Windows installation - Set Power Plan → High Performance / Balanced
    - Turn off start up apps
    - Remove app cluster

     
 13. Enabling XMP
    - Go into the BIOS and head to AI Tweaker and try to find Overclocking and click XMP Profile leave it as Enabled
    - If not for XMP profile chose profile 1

     
13.  Log into 
    - Edge
    - Outlook
    - Teams
    - OneDrive
