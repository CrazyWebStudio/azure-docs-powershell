---
external help file: Microsoft.Azure.Commands.SiteRecovery.dll-Help.xml
online version: 
schema: 2.0.0
ms.assetid: 846341E1-EEFC-4A72-B408-0914FC85CE30
---

# Set-AzureRmSiteRecoveryVaultSettings

## SYNOPSIS
Sets the Site Recovery vault context for further operations.

## SYNTAX

### AzureSiteRecoveryVault
```
Set-AzureRmSiteRecoveryVaultSettings -ASRVault <ASRVault> [<CommonParameters>]
```

### AzureRecoveryServicesVault
```
Set-AzureRmSiteRecoveryVaultSettings -ARSVault <ARSVault> [<CommonParameters>]
```

## DESCRIPTION
The **Set-AzureRmSiteRecoveryVaultSettings** cmdlet sets the Azure Site Recovery vault context for further operations.
This does not apply to recovery services vaults.

## EXAMPLES


## PARAMETERS

### -ASRVault
Specifies an **ASRVault** object.

```yaml
Type: ASRVault
Parameter Sets: AzureSiteRecoveryVault
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -ARSVault
Specifies an **ARSVault** object.

```yaml
Type: ARSVault
Parameter Sets: AzureRecoveryServicesVault
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Get-AzureRmSiteRecoveryVaultSettings](./Get-AzureRmSiteRecoveryVaultSettings.md)
