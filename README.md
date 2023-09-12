# test1


```mermaid
flowchart TD
  A[Deploy to Prod] ---> B(Is it Friday?);
  B -- Yes --> C[Don't do it];
  B -- No --> D[Do it!];
  C ----> E[Enjoy];
  D ----> E[Enjoy];
  E --> A;
````

```mermaid
classDiagram
  class Award
  class IssuedAward

  Award -- IssuedAward
```
