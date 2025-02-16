---
external help file: ADOPS-help.xml
Module Name: ADOPS
online version:
schema: 2.0.0
---

# Get-ADOPSProject

## SYNOPSIS

Gets one or several projects in an Azure DevOps organization.

## SYNTAX

```powershell
Get-ADOPSProject [[-Organization] <String>] [[-Project] <String>] [<CommonParameters>]
```

## DESCRIPTION

Gets one or several projects in an Azure DevOps organization.

## EXAMPLES

### Example 1

```powershell
PS C:\> Get-ADOPSProject -Organization 'ADOPS' -Project 'ADOPSproj'
```

Gets the project called "ADOPSproj" from the organization "ADOPS".

### Example 2

```powershell
PS C:\> Get-ADOPSProject -Project 'ADOPSproj'
```

Gets the project called "ADOPSproj" from the default organization.

## PARAMETERS

### -Organization

The name of the organization of the project.

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: 0
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Project

The name of the project to find.

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: 1
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters

This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### None

## OUTPUTS

### System.Object

## NOTES

## RELATED LINKS
