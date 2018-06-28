# fire
## Syntax

```php
public function fire($eventName, $data = null, $resultType = null, $limit = null);
```

## Remarks

Fire event

## Arguments

| DataType | Name | Description |
| --- | --- | --- |
| String | $eventName | Event to fire. You can also use wildcards to fire multiple events at once, ex: 'event.*' | 
| Array/Event | $data | Array or Event object |
| null | $resultType | If specified, the event results will be filtered using given class/interface name |
| null/int | $limit | Number of results to return |

## Returns

| DataType | Name | Description |
| --- | --- | --- |
| Array | | Array of results from EventListeners |
