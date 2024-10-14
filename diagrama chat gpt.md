```mermaid
classDiagram
    Animal <|-- Mammal
    Animal <|-- Bird
    Animal : +int age
    Animal : +String name
    Animal : +eat()
    class Mammal{
        +int legCount
        +run()
    }
    class Bird{
        +fly()
    }
