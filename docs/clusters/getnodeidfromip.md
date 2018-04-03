# Get Node ID from IP
Returns the ID of a node for a specified management or storage IP.

## Example

{% codetabs name="Golang", type="go" -%}
nodeId, err := m.GetNodeIdFromIp(someIp)
if err != nil {
    return nil
}
{%- language name="Python", type="py" -%}
TBD
{%- endcodetabs %}

## Reference