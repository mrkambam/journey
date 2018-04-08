---
class:
- stop
rel:
- self
properties:
  name: Phone
  sort: 3
  level: 2
  description: Allow notifications to be received by Phone.
entities:
- class:
  - stop
  rel:
  - self
  properties:
    name: Phone
  links:
  - rel:
    - self
    href: monitoring/notification/phone.md
  - rel:
    - parent
    href: monitoring/notification/
links:
- rel:
  - self
  href: monitoring/notification/phone.md
- rel:
  - parent
  href: monitoring/notification/
...