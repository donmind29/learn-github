## UML diagrams

You can render UML diagrams using [Mermaid](https://mermaidjs.github.io/). For example, this will produce a sequence diagram:

```mermaid
sequenceDiagram
Yovi Pratama ->> Afrizal: Hello Afrizal, how are you?
Afrizal-->>Apri: How about you Apri?
Afrizal--x Yovi Pratama: I am good thanks!
Afrizal-x Apri: I am good thanks!
Note right of Apri: Afrizal thinks a long<br/>long time, so long<br/>that the text does<br/>not fit on a row.

Apri-->Yovi Pratama: Checking with Apri...
Yovi Pratama->Apri: Yes... Apri, how are you?
```

And this will produce a flow chart:

```mermaid
graph LR
A[Square Rect] -- Link text --> B((Circle))
A --> C(Round Rect)
B --> D{Rhombus}
C --> D

journey
    title My working day
    section Go to work
      Make tea: 5: Me
      Go upstairs: 3: Me
      Do work: 1: Me, Cat
    section Go home
      Go downstairs: 5: Me
      Sit down: 5: Me