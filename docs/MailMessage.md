# MailMessage
 : [Object](Object.md)
___
### Methods  
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> [AddAttachment](#AddAttachment)()
>
> [AddRecipients](#AddRecipients)()
>
> [GetTable](#GetTable)()
>
> [RemoveAllAttachments](#RemoveAllAttachments)()
>
> [RemoveAllRecipients](#RemoveAllRecipients)()
>
> [Send](#Send)()
>
> [SetBody](#SetBody)()
>
> [SetHTMLBody](#SetHTMLBody)()
>
> [SetLogin](#SetLogin)()
>
> [SetPassword](#SetPassword)()
>
> [SetSender](#SetSender)()
>
> [SetServer](#SetServer)()
>
> [SetSubject](#SetSubject)()
>
### Registry Attributes
> [REGB_ControlView](#REGB_ControlView)
>
> [REGB_Hide](#REGB_Hide)
>
> [REGB_SupportsDoD](#REGB_SupportsDoD)
>
> [REGB_Unpredictable](#REGB_Unpredictable)
>
> [REGI_ClassType](#REGI_ClassType)
>
> [REGI_Priority](#REGI_Priority)
>
> [REGI_Version](#REGI_Version)
>
> [REGS_ID](#REGS_ID)
>
> [REGS_Name](#REGS_Name)
>
> [REGS_VersionString](#REGS_VersionString)
>
___

# Methods: <!-- {docsify-ignore} -->

### AddAttachment()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Attaches a filename to the body
>
> ```php
boolean MailMessage:AddAttachment(string filename)
> ```
>
___

### AddRecipients()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Adds a recipient to the To: list
>
> ```php
 MailMessage:AddRecipients(string addresses)
> ```
>
> ```php
 MailMessage:AddRecipients(table addresses)
> ```
>
> ```
Arguments:
   Addresses - a string of containing one or more email addresses,
               or table of email address strings (or name/address string pairs)
> ```
>
___

### GetTable()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Returns the message in the form of a table
>
> ```php
table MailMessage:GetTable()
> ```
>
> ```
Usage: table = GetTable()

Returns: table - a table with To, From, Subject and Body fields
                 containing the message data. Any attachment filenames
                 are listed in numbered fields.
> ```
>
___

### RemoveAllAttachments()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Removes all attachments from the message
>
> ```php
 MailMessage:RemoveAllAttachments()
> ```
>
___

### RemoveAllRecipients()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Removes all recipients from the To: field
>
> ```php
 MailMessage:RemoveAllRecipients()
> ```
>
___

### Send()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Sends the message
>
> ```php
boolean, string MailMessage:Send([number timeout])
> ```
>
> ```
Arguments: timeout - (optional) network timeout in milliseconds

Returns: success - true if the message was sent OK
         log     - nil, or a string containing a log of error messages
> ```
>
___

### SetBody()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Sets the message body
>
> ```php
 MailMessage:SetBody(string bodytext)
> ```
>
___

### SetHTMLBody()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Sets the message body using HTML
>
> ```php
 MailMessage:SetHTMLBody(string bodyhtml)
> ```
>
___

### SetLogin()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Sets the login to use for authentication
>
> ```php
 MailMessage:SetLogin(string login)
> ```
>
> ```
Arguments:
   login - a string containing the login or email address
             to use when authenticating with the server.
> ```
>
> *Se also: [SetPassword()](#SetPassword)*
___

### SetPassword()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Sets the password to use for authentication
>
> ```php
 MailMessage:SetPassword(string password)
> ```
>
> ```
password - a string containing the plaintext password
             to use when authenticating with the server.
> ```
>
> *Se also: [SetLogin()](#SetLogin)*
___

### SetSender()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Sets the From: field
>
> ```php
 MailMessage:SetSender(string sender)
> ```
>
> ```php
 MailMessage:SetSender(table sender)
> ```
>
> ```
sender - a string with the sender's address (or name and address),
             or a table containing strings of the sender's name
             and email address.

Note: If the sender is not set, it will default to the user's
      primary email name and address.
> ```
>
___

### SetServer()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Sets the outgoing mail server to use
>
> ```php
 MailMessage:SetServer(string servername)
> ```
>
> ```
Arguments:
   servername - a string containing the domain name of the SMTP server
             to use when sending mail.

Note: If servername is empty (the default), the Prefs->Network field
      or direct MX lookup will be used.
> ```
>
___

### SetSubject()
> [!TIP|labelVisibility:hidden|iconVisibility:hidden]
> Sets the Subject: field
>
> ```php
 MailMessage:SetSubject(string subject)
> ```
>
___


# Registry Attributes: <!-- {docsify-ignore} -->

### REGB_ControlView
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: boolean`
>
> false
>
___

### REGB_Hide
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: boolean`
>
> false
>
___

### REGB_SupportsDoD
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: boolean`
>
> false
>
___

### REGB_Unpredictable
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: boolean`
>
> false
>
___

### REGI_ClassType
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: number (integer)`
>
> 0 = CT_Any
>
___

### REGI_Priority
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: number (integer)`
>
> 0
>
___

### REGI_Version
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: number (integer)`
>
> 0
>
___

### REGS_ID
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> MailMessage
>
___

### REGS_Name
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> MailMessage
>
___

### REGS_VersionString
> [!WARNING|labelVisibility:hidden|iconVisibility:hidden]
> `Type: string`
>
> Built: Jul 19 2023
>
___

