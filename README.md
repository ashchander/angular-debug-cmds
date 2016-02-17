# Angular Debug Commands

Browser console commands to help with debugging Angular 1.x apps

Inspect the target element first, or replace $0 with a selector for the target element.

### Scope

```
var myScope = angular.element($0).scope()

var myScope = angular.element($0).isolateScope() // for a directive's isolated scope
```

### Controller

```
var myController = angular.element($0).controller()
```

### Factory

```
var myFactory = angular.element($0).injector().get('myFactory')
```
