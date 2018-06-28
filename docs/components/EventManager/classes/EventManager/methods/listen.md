# listen
## Syntax

```php
public function listen($eventName, EventListener $eventListener = null);
```

## Remarks

Subscribe to event

## Arguments

| DataType | Name | Description |
| --- | --- | --- |
| String | $eventName | Event name you want to listen | 
| EventListener | $eventListener | (Optional) If specified, given EventListener will be used for this event |

## Returns

| DataType | Name | Description |
| --- | --- | --- |
| [EventListener](../../EventListener/EventListener.md) | | Return instance of EventListener |

## Throws

- [EventManagerException](../../EventManagerException/EventManagerException.md)
