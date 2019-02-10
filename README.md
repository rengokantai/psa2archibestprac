# psa2archibestprac
## 4. Organizing Features and Modules
### 5 Core and Shared in Action
```
@SkipSelf(): A constructor parameter decorator that tells the DI framework
that dependency resolution should start from the parent injector
```


## 6. Component Communication
### 2 Component Communication
##### Event Bus vs. Observable Service
Event Bus | Observable Service
---|---
Mediator pattern | Observer pattern
Angular service acts as the middlema between components|Angular service exposes observable directly to components
Components don't know where data is coming from by default|Components know where data is coming from
Loosely coupled|Not as loosely coupled as event bus
Relies on subject/observvable | Relies on subject/observable
