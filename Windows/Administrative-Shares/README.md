## Windows Administrative Shares



# What is it?
Windows automatically creates hidden network shares for administrative purposes. These allow authorised administrators to remotely access drives 
and other resources on another Windows computer.


This provides administrative access to the remote computer's `C: ` drive

For example: \\CLIENT77\C$\Users\User\Documents
Corresponds to: C:\Users\User\Documents



# Finding the Computer Name
The hostname can be found using Command Prompt: hostname
It can also be found under: 

**Settings → System → About → Device name**



# Accessing an administrative share does not itself:
* Log the user out
* Lock their computer
* Display their desktop
* Control their mouse or keyboard
* Start an RDP session
  
(Care should still be taken when modifying files that are actively being used by applications)



# Common IT Support Uses
Administrative shares can be useful for:
* Retrieving files remotely
* Copying configuration files
* Restoring backed-up user data
* Troubleshooting Windows profiles
* Accessing application configuration folders
* Performing filesystem-related support without taking control of the user's desktop
