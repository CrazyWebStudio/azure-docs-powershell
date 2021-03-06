---
external help file: Microsoft.WindowsAzure.Commands.ServiceManagement.dll-Help.xml
online version: 
schema: 2.0.0
ms.assetid: 7FFBEB32-35B9-4575-8264-7AA9C7E82337
---

# Remove-AzureVMExtension

## SYNOPSIS
Removes resource extensions from a virtual machine.

## SYNTAX

### RemoveByExtensionName (Default)
```
Remove-AzureVMExtension [-ExtensionName] <String> [-Publisher] <String> -VM <IPersistentVM>
 [-Profile <AzureProfile>] [<CommonParameters>]
```

### RemoveByReferenceName
```
Remove-AzureVMExtension [-ReferenceName] <String> -VM <IPersistentVM> [-Profile <AzureProfile>]
 [<CommonParameters>]
```

### RemoveAll
```
Remove-AzureVMExtension [-RemoveAll] -VM <IPersistentVM> [-Profile <AzureProfile>] [<CommonParameters>]
```

## DESCRIPTION
The **Remove-AzureVMExtension** cmdlet removes resource extensions from a virtual machine.

## EXAMPLES

### Example 1: Remove an extension using a specific name and publisher
```
PS C:\>$VM = Remove-AzureVMExtension -VM $VM -ExtensionName $EXT -Publisher $PUB;
```

This command removes an extension with the specified name and publisher.

### Example 2: Remove all extensions from a specific virtual machine
```
PS C:\>$VM = Remove-AzureVMExtension -VM $VM -RemoveAll;
```

This command removes all extensions from the specified virtual machine as stored in the variable $VM.

## PARAMETERS

### -ExtensionName
Specifies the extension name that this cmdlet removes.

```yaml
Type: String
Parameter Sets: RemoveByExtensionName
Aliases: 

Required: True
Position: 1
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Publisher
Specifies the extension publisher.

```yaml
Type: String
Parameter Sets: RemoveByExtensionName
Aliases: 

Required: True
Position: 2
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -VM
Specifies the persistent virtual machine object.

```yaml
Type: IPersistentVM
Parameter Sets: (All)
Aliases: InputObject

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName, ByValue)
Accept wildcard characters: False
```

### -ReferenceName
Specifies the reference name of the extension.

```yaml
Type: String
Parameter Sets: RemoveByReferenceName
Aliases: 

Required: True
Position: 1
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -RemoveAll
Indicates that this cmdlet removes all resource extensions from the virtual machine.

```yaml
Type: SwitchParameter
Parameter Sets: RemoveAll
Aliases: 

Required: True
Position: 1
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Profile
Specifies the Azure profile from which this cmdlet reads.
If you do not specify a profile, this cmdlet reads from the local default profile.

```yaml
Type: AzureProfile
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Get-AzureVMExtension](./Get-AzureVMExtension.md)

[Set-AzureVMExtension](./Set-AzureVMExtension.md)

[Azure Service Cmdlets](./Azure.Service.md)


