---
class:
- stop
rel:
- self
properties:
  name: Security
  sort: 3
  level: 2
  description: Establish what the security practices are for scanning, auditing, and
    executing after deploying APIs within container, as well as on a regular schedule.
entities:
- class:
  - stop
  rel:
  - self
  properties:
    name: Security
  links:
  - rel:
    - self
    href: deployment/containers/security.md
  - rel:
    - parent
    href: deployment/containers/
links:
- rel:
  - self
  href: deployment/containers/security.md
- rel:
  - parent
  href: deployment/containers/
...