# App Class
## Syntax

```php
class \app\framework\Component\App
```

## Remarks

This class is there to easily call methods. It self can easily accessed via the `app()` helper
function:

## Variables

| Type | Returns | Name | Description |
| --- | --- | --- | --- |
| Private | Array | `$defaultNamespaces` | Contains the default Namespaces where it shall search in. |
| Private | Array | `$Instances` | The already used Classes are saved here for quicker access in further calls. |

## Functions summery

| Type | Returns | Name | Description |
| --- | --- | --- | --- |
| Public | [callMethod()]() | [call](methods/call.md) | To actually call an Method of an class. |
| Public | $Instance | [getClassInstance](methods/getClassInstance.md) | Some strange shit| 
| Private | Boolean | [CheckIfClassIsRegistered](methods/CheckIfClassIsRegistered.md) | Returns boolean if the class is already registered or not |
| Private | Void | [registerNewClass](methods/registerNewClass.md) | Registers a new class |
| Private | Mixed | [callMethod](methods/callMethod.md) | Call a user function of defined class with given parameter |