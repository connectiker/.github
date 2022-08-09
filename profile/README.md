`Connectiker` is a concept for building micro-services as a lego architecture, meaning that any component is a building block to fast ship a microservice. Each `Connectiker` component does do one thing only and one thing well.

```
+-----------+           +---------+
| xConnect  | ------>   | xAddons |
+----+------+           +-----+---+
     |                        |
     |                        |
     +------------+-----------+
                  |
                  |
                  V
             +-----------+ 
             | xService  | 
             +-----------+

```

## xConnect

`xConnect` provides the abstraction layers & managers for pluggable `xAddons` used in a microservice architecture, the basic interfaces & managers to define expectations and vocabulary.

## xAddons

`xAddons` are pluggable components built on top of `xConnect`. They are the core components that make up the `xServices`. They provide an essential foundation for your incoming projects, the core components needed to start a new service. `xAddons` provide the core "building blocks" required to build out your application.

## xService

`xService` is a framework for distributed system development, everything that is needed to fast start a new project (a server, a client, a message broker,... etc)
