---
external help file: PSJobMonitor-help.xml
Module Name: PSJobMonitor
online version: 
schema: 2.0.0
---

# Enable-MonitoredJob

## SYNOPSIS
Habilita un Job para tenerlo en cuenta en los procesos de monitoreo.

## SYNTAX

```
Enable-MonitoredJob [-InputObject] <Object>
```

## DESCRIPTION
Habilita un Job para tenerlo en cuenta en los procesos de monitoreo.
Por defecto los jobs se importan habilitados.

## EXAMPLES

### -------------------------- EXAMPLE 1 --------------------------
```
Get-MonitoredServer | Get-UnMonitoredJob | Enable-MonitoredJob
```

## PARAMETERS

### -InputObject
Información de jobs que no están siendo monitoreados.

```yaml
Type: Object
Parameter Sets: (All)
Aliases: 

Required: True
Position: 1
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

## INPUTS

## OUTPUTS

### System.Void

## NOTES

## RELATED LINKS

[[Get-MonitoredJob](Get-MonitoredJob.md)]()

[[Get-MonitoredServer](Get-MonitoredServer.md)]()

[[Disable-MonitoredJob](Disable-MonitoredJob.md)]()
