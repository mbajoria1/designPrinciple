# OOO DESIGN PRINCIPLES(SOLID):
#### Single Responsibility Principle(SRP)

Single responsibility principle says a class/module/microservice should only have one single responsibility. In other words it should have only one reason to change. 
In business/technical world things are always changing. We should always design our classes in a way that are highly cohesive which means they are dealing with highly related tasks. This increases code maintainability and readability. Also makes unit testing easy and codes are less error prone. 

We can take a small example and see how we can apply SRP: 

```
@RestController
Class OrderController

```

