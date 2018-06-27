# Event
## Syntax
   
```php
class app\framework\Component\EventManager\Event implements \ArrayAccess, \InteratorAggregate
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

| Type | Returns | Name | Description |
| --- | --- | --- | --- |
| Public | Void | [__construct](methods/construct.md) | | 
| Public | Mixed | [__get](methods/overrideget.md) | Access internal data as if it was a real object | 
| Public | Void | [__set](methods/set.md) | Set internal data as if it was a real object | 
| Public | Bool | [__isset](methods/isset.md) | Override __isset | 
| Public | Void | [__unset](methods/unset.md) | Override __unset | 
| Public | Mixed | [get](methods/get.md) | Get value or return $default if there is no element set. | 
| Public | \Traversable | [getIterator](methods/getIterator.md) | (PHP 5 &gt;= 5.0.0)<br/> Retrieve an external iterator | 
| Public | Bool | [isPropagationStopped](methods/isPropagationStopped.md) | Check if propagation for this event is stopped | 
| Public | Void | [stopPropagation](methods/stopPropagation.md) | Stops the propagation of the event to further event listeners. After stopPropagation() is called, no other listeners will be processed. | 
| Public | Bool | [offsetExists](methods/offsetExists.md) | (PHP 5 &gt;= 5.0.0)<br/> Whether a offset exists | 
| Public | Mixed | [offsetGet](methods/offsetGet.md) | (PHP 5 &gt;= 5.0.0)<br/> Offset to retrieve | 
| Public | Mixed | [offsetSet](methods/offsetSet.md) | (PHP 5 &gt;= 5.0.0)<br/> Offset to set | 
| Public | Mixed | [offsetUnset](methods/offsetUnset.md) | (PHP 5 &gt;= 5.0.0)<br/> Offset to unset | 
| Public | Array | [toArray](methods/toArray.md) | Get event data in form of an array | 