## UML diagrams

You can render UML diagrams using [Mermaid](https://mermaidjs.github.io/). For example, this will produce a sequence diagram:

```mermaid
sequenceDiagram
Anwar ->> Ali: Hello Ali, how are you?
Ali-->>John: How about you John?
Ali--x Anwar: I am good thanks!
Ali-x John: I am good thanks!
Note right of John: Ali thinks a long<br/>long time, so long<br/>that the text does<br/>not fit on a row.

Ali-->Anwar: Checking with John...
Anwar->John: Yes... John, how are you?
```
---

```mermaid
journey
    title My working day
    section Go to work
      Make tea: 5: Me
      Go upstairs: 3: Me
      Do work: 1: Me, Cat
    section Go home
      Go downstairs: 5: Me
      Sit down: 5: Me

```