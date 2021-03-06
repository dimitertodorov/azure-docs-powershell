---
external help file: Microsoft.Azure.Commands.Network.dll-Help.xml
Module Name: AzureRM.Network
online version:
schema: 2.0.0
content_git_url: https://github.com/Azure/azure-powershell/blob/preview/src/ResourceManager/Network/Commands.Network/help/New-AzureRmApplicationGatewayConnectionDraining.md
original_content_git_url: https://github.com/Azure/azure-powershell/blob/preview/src/ResourceManager/Network/Commands.Network/help/New-AzureRmApplicationGatewayConnectionDraining.md
gitcommit: https://github.com/Azure/azure-powershell/blob/66ff7aae79d21e8503f3b1bdbf11915a7c4ed3ee
---

# New-AzureRmApplicationGatewayConnectionDraining

## SYNOPSIS
Creates a new connection draining configuration for back-end HTTP settings.

## SYNTAX

```
New-AzureRmApplicationGatewayConnectionDraining -Enabled <Boolean> -DrainTimeoutInSec <Int32>
 [<CommonParameters>]
```

## DESCRIPTION
The **New-AzureRmApplicationGatewayConnectionDraining** cmdlet creates a new connection draining configuration for back-end HTTP settings.

## EXAMPLES

### Example 1
```
PS C:\> $connectionDraining = New-AzureRmApplicationGatewayConnectionDraining -Enabled $True -DrainTimeoutInSec 42
```

The command creates a new connection draining configuration with Enabled set to True and DrainTimeoutInSec set to 42 seconds and stores it in $connectionDraining.

## PARAMETERS

### -DrainTimeoutInSec
The number of seconds connection draining is active.
Acceptable values are from 1 second to 3600 seconds.

```yaml
Type: Int32
Parameter Sets: (All)
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Enabled
Whether connection draining is enabled or not.

```yaml
Type: Boolean
Parameter Sets: (All)
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### None

## OUTPUTS

### Microsoft.Azure.Commands.Network.Models.PSApplicationGatewayConnectionDraining

## NOTES

## RELATED LINKS

[Get-AzureRmApplicationGatewayConnectionDraining](./Get-AzureRmApplicationGatewayConnectionDraining.md)

[Remove-AzureRmApplicationGatewayConnectionDraining](./Remove-AzureRmApplicationGatewayConnectionDraining.md)

[Set-AzureRmApplicationGatewayConnectionDraining](./Set-AzureRmApplicationGatewayConnectionDraining.md)

