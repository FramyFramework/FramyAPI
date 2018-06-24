# priority
## Syntax

```php
public function priority($priority);
```

## Remarks

Set listener priority between 101 and 999.<br />
Default priority is 101.<br />
Bigger values mean higher listener priority, and will be executed first.

## Arguments

| DataType | Name | Description |
| --- | --- | --- |
| Mixed | $priority | |

## Returns

| DataType | Name | Description |
| --- | --- | --- |
| [$this](../EventListener.md) | | |

## Throws

- [EventManagerException](../../EventManagerException/EventManagerException.md)
