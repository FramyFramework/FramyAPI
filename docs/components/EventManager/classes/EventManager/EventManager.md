# EventManager
## Syntax

```php
class EventManager
```

## Aliasing

- [app\framework\Component\StdLib\StdLibTrait](../../../StdLib/classes/StdLibTrait.md)
- [app\framework\Component\StdLib\SingletonTrait](../../../StdLib/classes/SingletonTrait.md)

## Variables

| Type | Returns | Name | Description |
| --- | --- | ---| --- |
| Private | Bool | $suppressEvents | Suppress EventManager events |
| Private | [EventProcessor](../EventProcessor/EventProcessor.md) | $eventProcessor | |
| Private | [ArrayObject]() | $events | Registered events and event subscribers |

## Functions summery

| Type | Returns | Name | Description |
| --- | --- | --- | --- |
| Public | [EventListener](../EventListener/EventListener.md) | [listen()](methods/listen.md) | Subscribe to event |
| Public | $this | [subscribe()](methods/subscribe.md) | Subscribe to events using event subscriber |
| Public | Array | [fire()](methods/fire.md) | Fire event |
| Public | $this | [enable()](methods/enable.md) | Enable event handling. After calling this method EventManager will process all fired events. |
| Public | $this | [disable()](methods/disable.md) | Disable event handling. After calling this method EventManager will ignore all fired events. |
| Public | Array | [getEventListeners()](methods/getEventListeners.md) | Get array of event listeners |
| Public | Void | [init()](methods/init.md) | Singleton constructor |
| Private | null/array | [fireWildcardEvents()](methods/fireWildcardEvents.md) | Process events starting with given prefix (ex: framy.* will process all events starting with 'framy.') |
