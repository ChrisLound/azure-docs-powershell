---
external help file: Microsoft.Azure.Commands.Automation.dll-Help.xml
ms.assetid: 5A7761DE-2D9C-4217-9B8D-6E38DAF2820F
online version: 
schema: 2.0.0
---

# Publish-AzureAutomationRunbook

## SYNOPSIS
Publishes a runbook.

## SYNTAX

```
Publish-AzureAutomationRunbook [-Name] <String> [-AutomationAccountName] <String> [-Profile <AzureSMProfile>]
 [-InformationAction <ActionPreference>] [-InformationVariable <String>] [<CommonParameters>]
```

## DESCRIPTION
The **Publish-AzureAutomationRunbook** cmdlet publishes a runbook for use in the production environment of Microsoft Azure Automation.

## EXAMPLES

### Example 1: Publish a runbook
```
PS C:\>Publish-AzureAutomationRunbook -AutomationAccountName "Contoso17" -Name "Runbk01"
```

This command publishes the runbook named Runbk01 in the Automation account named Contoso17.

## PARAMETERS

### -Name
Specifies the name of the runbook.

```yaml
Type: String
Parameter Sets: (All)
Aliases: RunbookName

Required: True
Position: 1
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -AutomationAccountName
Specifies the name of the Automation account.

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

### -Profile
Specifies the Azure profile from which this cmdlet reads.
If you do not specify a profile, this cmdlet reads from the local default profile.

```yaml
Type: AzureSMProfile
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -InformationAction
Specifies how this cmdlet responds to an information event.

The acceptable values for this parameter are:

- Continue
- Ignore
- Inquire
- SilentlyContinue
- Stop
- Suspend

```yaml
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
Specifies an information variable.

```yaml
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

[Get-AzureAutomationRunbook](./Get-AzureAutomationRunbook.md)

[New-AzureAutomationRunbook](./New-AzureAutomationRunbook.md)

[Remove-AzureAutomationRunbook](./Remove-AzureAutomationRunbook.md)

[Set-AzureAutomationRunbook](./Set-AzureAutomationRunbook.md)

[Start-AzureAutomationRunbook](./Start-AzureAutomationRunbook.md)

