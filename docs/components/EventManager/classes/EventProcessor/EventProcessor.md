# EventProcessor
## Syntax
   
```php
class app\framework\Component\EventManager\EventProcessor
```

## Remarks

EventProcessor is a class that takes EventListeners and Event object and processes the event.

## Aliasing

- [app\framework\Component\StdLib\StdLibTrait](../../../StdLib/classes/StdLibTrait.md)
- [app\framework\Component\StdLib\SingletonTrait](../../../StdLib/classes/SingletonTrait.md)

## Functions summery

| Type | Returns | Name | Description |
| --- | --- | --- | --- |
| Public | Array | [process](methods/process.md) | Process given event |
| Private | Mixed | [orderByPriority](methods/orderByPriority.md) | Access internal data as if it was a real object |
