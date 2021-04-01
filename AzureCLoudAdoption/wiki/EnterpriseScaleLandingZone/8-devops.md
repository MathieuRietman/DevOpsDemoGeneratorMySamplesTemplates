# Platform automation and DevOps

## List of related features and user stories in the backlog

- #6573
- #6574
- #6575
- #6576
- #6577
- #6578
- #6579
- #6580
- #6581
- #6584
- #6586

Improvement  

- #6613
- #6622

## Central vs Application responsibilities

The following list presents a recommended distribution of responsibilities between the central IT team and application teams. You're striving to empower migration and transformation activities with minimal central dependencies. At the same time, you want to support the centralized governance of security and operability across the entire estate.

Application functions (AppDevOps)
- Application migration and transformation.
- Application management and monitoring (application resources).
- Key management (application keys).
- Azure RBAC (application resources).
- Security monitoring and audit (application resources).
- Cost management (application resources).
- Network management (application resources).

Central functions (Platform Ops)
- Architecture governance.
- Subscription management.
- Platform as code (management of templates, scripts, and other assets).
- Policy management and enforcement (holistic).
- Platform management and monitoring (holistic).
- Azure RBAC (holistic).
- Key management (central services).
- Network management (including networks and network virtual appliances).
- Security monitoring and audit (holistic).
- Cost management (holistic).