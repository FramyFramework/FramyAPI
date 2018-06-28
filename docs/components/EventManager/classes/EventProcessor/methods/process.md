# process
## Syntax

```php
public function process($eventListeners, Event $event, $resultType = null, $limit = null);
```

## Remarks

Set handler for event. Can be a callable, class name or class instance.

## Arguments

| DataType | Name | Description |
| --- | --- | --- |
| Array/ArrayObject | $eventListeners | EventListeners that are subscribed to this event |
| Event | $event | Event data object |
| Null/String | $resultType | Type of event result to enforce (can be any class or interface name) |
| Null/Int | $limit | Number of results to return |

## Returns

| DataType | Name | Description |
| --- | --- | --- |
| Array | | |