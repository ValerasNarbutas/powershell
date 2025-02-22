---
Module Name: PnP.PowerShell
title: New-PnPUser
schema: 2.0.0
applicable: SharePoint Online
external help file: PnP.PowerShell.dll-Help.xml
online version: https://pnp.github.io/powershell/cmdlets/New-PnPUser.html
---
 
# New-PnPUser

## SYNOPSIS
Adds a user to the built-in Site User Info List and returns a user object

## SYNTAX

```powershell
New-PnPUser -LoginName <String> [-Connection <PnPConnection>] [<CommonParameters>]
```

## DESCRIPTION

Allows to add a user to current site.

## EXAMPLES

### EXAMPLE 1
```powershell
New-PnPUser -LoginName user@company.com
```

Adds a new user with the login user@company.com to the current site

## PARAMETERS

### -Connection
Optional connection to be used by the cmdlet. Retrieve the value for this parameter by either specifying -ReturnConnection on Connect-PnPOnline or by executing Get-PnPConnection.

```yaml
Type: PnPConnection
Parameter Sets: (All)

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -LoginName
The users login name (user@company.com)

```yaml
Type: String
Parameter Sets: (All)
Aliases: LogonName

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```



## RELATED LINKS

[Microsoft 365 Patterns and Practices](https://aka.ms/m365pnp)

