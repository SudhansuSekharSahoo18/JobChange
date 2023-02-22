## Requirments

- A pen is anything that can write.

## Pen as the God class

```mermaid
classDiagram
    class Pen {
        -String brand
        -String name
        -PenType type
        -double price
    }

    class PenType {
        <<enumeration>>
        GEL
        BALL
        FOUNTAIN
        THROW_AWAY
    }
```
