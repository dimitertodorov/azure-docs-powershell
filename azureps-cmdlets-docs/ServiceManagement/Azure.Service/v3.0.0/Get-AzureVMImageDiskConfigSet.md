---
external help file: Microsoft.WindowsAzure.Commands.ServiceManagement.dll-Help.xml
online version: 
schema: 2.0.0
ms.assetid: 8AFE5531-9968-4777-AED1-68ED28F1FB4B
---

# Get-AzureVMImageDiskConfigSet

## SYNOPSIS
Gets a disk configuration set object from the input image context.

## SYNTAX

```
Get-AzureVMImageDiskConfigSet [[-ImageContext] <OSImageContext>] [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureVMImageDiskConfigSet** cmdlet gets a disk configuration set object from the input image context.

## EXAMPLES

### Example 1: Get a disk configuration set object from a virtual machine
```
PS C:\> Get-AzureVMImage -ImageName $Img | Get-AzureVMImageDiskConfigSet
```

This command gets a disk configuration set object from a virtual machine.

## PARAMETERS

### -ImageContext
Specifies the virtual machine image context.

```yaml
Type: OSImageContext
Parameter Sets: (All)
Aliases: 

Required: False
Position: 1
Default value: None
Accept pipeline input: True (ByPropertyName, ByValue)
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

### Microsoft.WindowsAzure.Commands.ServiceManagement.Model.VirtualMachineImageDiskConfigSet

## NOTES

## RELATED LINKS

[New-AzureVMImageDiskConfigSet](./New-AzureVMImageDiskConfigSet.md)

[Get-AzureVMImage](./Get-AzureVMImage.md)


