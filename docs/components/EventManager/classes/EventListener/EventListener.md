# EventListener
## Syntax

```php
class EventListener
```

## Aliasing

- [app\framework\Component\StdLib\StdLibTrait](../../../StdLib/classes/StdLibTrait.md)

## Variables

| Type | Name | Description |
| --- | --- | --- |
| Private | $handler | |
| Private | $method | |
| Private | $priority | |

## Functions summery

| Type | Returns | Name | Description |
| --- | --- | --- | --- |
| Public | Mixed | [getHandler()](methods/getHandler.md) | |
| Public | String | [getMethod()](methods/getMethod.md) | |
| Public | Int | [getPriority()](methods/getPriority.md) | |
| Public | $this | [handler()](methods/handler.md) | Set handler for event. Can be a callable, class name or class instance. |
| Public | $this | [priority()](methods/priority.md) | Set listener priority between 101 and 999. Default priority is 101. Bigger values mean higher listener priority, and will be executed first. |
| Public | [EventManagerException](../EventManagerException/EventManagerException.md) | [method()](methods/method.md) | Set method to be called on handler. If not set, default method will be called: handle(Event $event) |

