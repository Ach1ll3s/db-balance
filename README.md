# db-balance


Regular **Markdown** here.

<div hidden>
```
@startuml firstDiagram

Clients   |o..|{ Accounts
Clients   ||..|{ Contracts
Contracts |o..|{ Accounts
Accounts  }|..|{ Currency
Currency  ||..|{ Rate
Rate      }|..|| TypeRate   
Accounts  ||..|{ Saldo
Accounts  ||..|{ BaseSaldo
Accounts  ||--|{ Documents
Accounts  ||--|{ Documents
@enduml
```
</div>

![](firstDiagram.svg)

Some more markdown.
