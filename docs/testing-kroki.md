#some markdown

## some puml
```kroki-puml
@startuml
Alice -> Bob: Authentication Request
Bob --> Alice: Authentication Response

Alice -> Bob: Another authentication Request
Alice <-- Bob: Another authentication Response
@enduml
```

## some mermaid
```kroki-mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```
