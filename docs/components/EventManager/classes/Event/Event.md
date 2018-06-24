# Event
## Syntax
   
```php
class Event implements \ArrayAccess, \InteratorAggregate
```

## Remarks

Event class holds event data. Data can be accessed using array keys or as object
properties. Each time an event is fired, an instance of Event class in passed to handlers.
By extending this class you can implement your own event class and expand it with
whatever functionality you might need.

## Aliasing

- [app\framework\Component\StdLib\StdLibTrait](../../../StdLib/classes/StdLibTrait.md)

## Variables

| Type | Name | Description |
| --- | --- | --- |
| Private | Boolean | $propagationStoped | |
| Private | [ArrayObject](../../../StdLib/classes/ArrayObject.md) | $eventData | |

## Functions summery
### Constructors

| Type | Returns | Name | Description |
| --- | --- | --- | --- |
| Public | throw [EventManagerException](../EventManagerException/EventManagerException.md) | [__construct]() | |


