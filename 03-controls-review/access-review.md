# User Access Review – BankSecure

## Objective

Ensure only authorized users have access to banking systems.

\## Scope

Core Banking App, Active Directory, Database Systems.

\## Key Risks

\- Orphaned accounts

\- Excessive privileges

\- Shared credentials

\- Lack of access reviews

\## Sample Access Matrix

|User|Role|System|Access Level|Risk|
|-|-|-|-|-|
|Admin01|IT Admin|Core Banking|Full|High|
|Teller02|Cash Officer|Core Banking|Read/Write|Medium|
|HR03|HR Officer|Database|Read|Low|

## Recommended Controls

\- Quarterly access review

\- Role-based access control (RBAC)

\- Multi-factor authentication
