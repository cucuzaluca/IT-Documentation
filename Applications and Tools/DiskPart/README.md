## DiskPart

DiskPart is a command-line disk management tool built into Windows. It is used to view and manage storage devices such as HDDs, SSDs and USB drives.

DiskPart can be used to:
- View connected disks and partitions.
- Create and delete partitions.
- Format volumes.
- Assign or remove drive letters.
- Completely remove a disk's partition structure.
- Prepare a drive for another operating system or device.

## How to use
Open Command Prompt, PowerShell or Windows Terminal as Administrator and run: diskpart
The prompt will change to: DISKPART>


### Useful DiskPart Commands
- list disk: Displays all physical storage devices detected by Windows
- select disk (number): selects the physical disk that subsequent commands will affect
- detail disk: displays more information about the currently selected disk
- list partition: Displays the partitions on the selected disk
- clean: removes the disk's partition and volume information (removes partition information quickly)
- clean all: writes zeros across the entire disk
- create partition primary: creates a new primary partition using unallocated space.
- format: Formats the selected volume with a filesystem (format fs=ntfs quick)
