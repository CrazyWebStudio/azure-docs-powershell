---
external help file: Microsoft.Azure.Commands.ApiManagement.ServiceManagement.dll-Help.xml
online version: 
schema: 2.0.0
ms.assetid: B548EE5D-9507-486C-A422-4C2CDDD2A550
---

# New-AzureRmApiManagementGroup

## SYNOPSIS
Creates an API management group.

## SYNTAX

```
New-AzureRmApiManagementGroup -Context <PsApiManagementContext> [-GroupId <String>] -Name <String>
 [-Description <String>] [<CommonParameters>]
```

## DESCRIPTION
The **New-AzureRmApiManagementGroup** cmdlet creates an API management group.

## EXAMPLES

### Example 1: Create a management group
```
PS C:\> New-AzureRmApiManagementGroup -Context $APImContext -Name "Group0001"
```

This command creates a management group.

## PARAMETERS

### -Context
Specifies the instance of the **PsApiManagementContext** object.

```yaml
Type: PsApiManagementContext
Parameter Sets: (All)
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -GroupId
Specifies the identifier of the new management group.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Name
Specifies the management group name.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Description
Specifies the description of the management group.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

### Microsoft.Azure.Commands.ApiManagement.ServiceManagement.Models.PsApiManagementGroup

## NOTES

## RELATED LINKS

[Get-AzureRmApiManagementGroup](./Get-AzureRmApiManagementGroup.md)

[Remove-AzureRmApiManagementGroup](./Remove-AzureRmApiManagementGroup.md)

[Set-AzureRmApiManagementGroup](./Set-AzureRmApiManagementGroup.md)


