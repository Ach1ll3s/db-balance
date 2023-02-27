# db-balance


Regular **Markdown** here.

<div hidden>
```
@startuml er

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

![](er.svg)

Some more markdown.
