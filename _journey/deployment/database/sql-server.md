---
class:
- stop
rel:
- self
properties:
  name: SQL Server
  sort: 4
  level: 2
  description: Providing a connection to SQL Server database that allows for quick
    access to tables and fields, making data available through an API from the backend
    database.
entities:
- class:
  - stop
  rel:
  - self
  properties:
    name: SQL Server
  links:
  - rel:
    - self
    href: deployment/database/sql-server.md
  - rel:
    - parent
    href: deployment/database/
links:
- rel:
  - self
  href: deployment/database/sql-server.md
- rel:
  - parent
  href: deployment/database/
...