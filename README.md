# db-balance


Regular **Markdown** here.

<!--
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
-->

![](er.svg)

Some more markdown.
