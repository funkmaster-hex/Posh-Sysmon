---
external help file: Posh-SysMon-help.xml
online version: 
schema: 2.0.0
---

# New-SysmonFileCreateStreamHashFilter

## SYNOPSIS
Create a new filter for the logging of the saving of data on a file stream.

## SYNTAX

### Path (Default)
```
New-SysmonFileCreateStreamHashFilter [-Path] <Object> [-OnMatch] <String> [-Condition] <String>
 [-EventField] <String> [-Value] <String[]>
```

### LiteralPath
```
New-SysmonFileCreateStreamHashFilter [-LiteralPath] <Object> [-OnMatch] <String> [-Condition] <String>
 [-EventField] <String> [-Value] <String[]>
```

## DESCRIPTION
Create a new filter for the logging of the saving of data on a file stream.

## EXAMPLES

### Example 1
```
PS C:\> {{ Add example code here }}
```

{{ Add example description here }}

## PARAMETERS

### -Path
Path to XML config file.

```yaml
Type: Object
Parameter Sets: Path
Aliases: 

Required: True
Position: 1
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -LiteralPath
Path to XML config file.

```yaml
Type: Object
Parameter Sets: LiteralPath
Aliases: PSPath

Required: True
Position: 1
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -OnMatch
Event type on match action.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 2
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Condition
Condition for filtering against and event field.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 3
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -EventField
Event field to filter on.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 4
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Value
Value of Event Field to filter on.

```yaml
Type: String[]
Parameter Sets: (All)
Aliases: 

Required: True
Position: 5
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

