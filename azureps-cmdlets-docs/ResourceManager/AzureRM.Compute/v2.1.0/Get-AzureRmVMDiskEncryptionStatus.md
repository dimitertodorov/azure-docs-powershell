---
external help file: Microsoft.Azure.Commands.Compute.dll-Help.xml
ms.assetid: 3B246240-D905-4125-8E8F-B700BD04044A
online version: 
schema: 2.0.0
---

# Get-AzureRmVMDiskEncryptionStatus

## SYNOPSIS
Gets the encryption status of the virtual machine.

## SYNTAX

```
Get-AzureRmVMDiskEncryptionStatus [-ResourceGroupName] <String> [-VMName] <String>
 [-InformationAction <ActionPreference>] [-InformationVariable <String>] [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureRmVMDiskEncryptionStatus** cmdlet gets the encryption status of the virtual machine.
It displays the encryption status of the operating system and data volumes.
In addition to encryption status, it also displays the encryption secret URL, key encryption key URL, resource IDs of the **KeyVaults** where the encryption key and key encryption key for operating system volume are present.

## EXAMPLES

### Example 1: Get the encryption status of a virtual machine
```
PS C:\>Get-AzureRmVmDiskEncryptionStatus -ResourceGroupName "MyResourceGroup001" -VMName "VM001"
```

This command gets the encryption status of the virtual machine named VM001.

## PARAMETERS

### -ResourceGroupName
Specifies the name of the resource group of the virtual machine.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 0
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -VMName
Specifies the name of the virtual machine.

```yaml
Type: String
Parameter Sets: (All)
Aliases: ResourceName

Required: True
Position: 1
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -InformationAction
@{Text=}```yaml
Type: ActionPreference
Parameter Sets: (All)
Aliases: infa

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -InformationVariable
@{Text=}```yaml
Type: String
Parameter Sets: (All)
Aliases: iv

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

[Remove-AzureRmVMDiskEncryptionExtension](./Remove-AzureRmVMDiskEncryptionExtension.md)

[Set-AzureRmVMDiskEncryptionExtension](./Set-AzureRmVMDiskEncryptionExtension.md)


