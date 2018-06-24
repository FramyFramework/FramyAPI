# method
## Syntax

```php
public function method($method);
```

## Remarks

Set method to be called on handler.<br />
If not set, default method will be called:
<code>handle(Event $event)</code>

## Arguments

| DataType | Name | Description |
| --- | --- | --- |
| String | $method | Method to call on handler | 

## Returns

| DataType | Name | Description |
| --- | --- | --- |
| [$this](../EventListener.md) | | |

## Throws

- [EventManagerException](../../EventManagerException/EventManagerException.md)
