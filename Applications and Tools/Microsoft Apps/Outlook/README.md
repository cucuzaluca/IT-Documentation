<img width="618" height="444" alt="image" src="https://github.com/user-attachments/assets/3e5d24c2-d599-470f-94e8-5ffd05a3bd99" /><img width="618" height="444" alt="image" src="https://github.com/user-attachments/assets/7dfedee6-9229-41e8-95c2-b6fe2b6e9d05" />## Microsoft Outlook
Microsoft Outlook is Microsoft's email and personal information management application. It is primarily used to send and receive email, but also integrates with calendars, contacts, meetings and Microsoft 365 services

## How its used
In IT support, Outlook commonly involves setting up accounts, troubleshooting mailboxes, restoring email signatures, resolving send/receive problems, managing shared mailboxes and troubleshooting Microsoft 365 connectivity


## Troubleshooting

### Rebuilding an Outlook OST File
An OST (Offline Storage Table) file is a local cached copy of mailbox data used by classic Outlook. It allows Outlook to keep a local copy of emails and other mailbox information so Outlook can work efficiently and provide some offline access

When Rebuilding the OST Can Help
An OST file can sometimes become corrupted, excessively large, or have synchronisation problems. This may cause Outlook to behave incorrectly. If the mailbox data is safely stored on the Microsoft 365/Exchange server, the local OST can usually be removed or renamed, and Outlook will create a new copy

Procedure
- Close Outlook completely
- Open: %LOCALAPPDATA%\Microsoft\Outlook
- Before deleting anything, confirm it is an OST associated with a server-backed Microsoft 365/Exchange mailbox
- A safer troubleshooting approach is to rename the existing file first:
  - user@company.com.ost - user@company.com.ost.old
- Reopen Outlook
- Outlook should create a new OST file and begin downloading/synchronising the mailbox from the server
- Allow time for synchronisation to complete, particularly for large mailboxes
- Confirm that Outlook and the mailbox are working correctly before removing the old OST

### Full In-Place Archive

In-Place Archive (Online Archive) a second mailbox that Microsoft gives the user specifically for storing older email.
<img width="618" height="444" alt="image" src="https://github.com/user-attachments/assets/55a0b087-6c39-4777-b230-ff69bc36b9e4" />

To fix this issue you can sign into the users account and then go to their in-place archive section and start deleting older items from their sent items and their inbox make sure to notify user and not to delete newer items

<img width="873" height="286" alt="image" src="https://github.com/user-attachments/assets/e00052ef-21c6-439d-a2d4-82e7cfd58266" />

