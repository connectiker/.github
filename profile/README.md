#Conectiker
Connectiker is a concept for building micro-services as a lego architecture, meaning that any component is a building block to fast ship a microservice. Each Connectiker component does do one thing only and one thing well.

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
