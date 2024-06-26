## 0.2.0 (2024-06-13)

- Bundling the tools for processing file attachments in the new `AttachmentConverter` class
- Enhanced the `createNewMessage()` method in Kilamea.kt with the evaluation of application arguments as file attachments
- Added another MIME type `APPLICATION_OCTET_STREAM`
- Context class extended with the `appDataFolder` property and a way to unset command line arguments
- `HelpAppDataFolderAction` introduced to open the directory with application data directly from the client
- Integrated the Gmail API and encapsulated the calls in the new `GmailClient` class
- Enhanced `MailMapper` with methods for converting Gmail messages
- Automatically encode the sender name to UTF-8 when sending emails
- Extended the `Account` class with a "tokens" property (particularly relevant for Gmail) and the database manager with methods for loading and saving OAuth tokens
- Start of a simple logging mechanism (JUL)
- String extensions implemented
- Changed a few button labels

## 0.1.0 (2024-05-09)

- Start of the project
- UI-Design
- Implementation of the basic functionality
