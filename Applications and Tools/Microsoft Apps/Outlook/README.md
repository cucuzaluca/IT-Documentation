## Microsoft Outlook
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
