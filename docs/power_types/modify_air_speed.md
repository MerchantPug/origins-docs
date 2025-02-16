---
title: Modify Air Speed (Power Type)
date: 2021-10-06
---
# Modify Air Speed

[Power Type](../power_types.md)

Modifies the entity's air speed.

Type ID: `origins:modify_air_speed`

### Fields

Field | Type | Default | Description
------|------|---------|-------------
`modifier` | [Attribute Modifier](../data_types/attribute_modifier.md) | _optional_ | If specified, this modifier will be applied to the entity's air speed.
`modifiers` | [Array](../data_types/array.md) of [Attribute Modifiers](../data_types/attribute_modifier.md) | _optional_ | If specified, these modifiers will be applied to the entity's air speed.

### Example
```json
{
    "type": "origins:modify_air_speed",
    "modifier": {
        "operation": "multiply_total",
        "value": 1.5
    }
}
```
This example increases the entity's air speed by 150%.