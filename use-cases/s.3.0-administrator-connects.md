Administrator connects Learning Application, SIS and LMS
# S.3.0 Administrator connects Learning Application, SIS and LMS

Establish the connections between the [SIS](../services/school-information-system.md), the [Marketplace](../services/marketplace.md) and the [LMS](../services/learning-management-system.md) used within a school (done only when these systems change or new services are added).  Note this is three separate processes grouped together below for simplicity.

![Process Diagram](../diagrams/process-diagrams-S.3.0.svg)

## Roles Involved

  - [Administrator](../roles/administrator.md) 
  
## Preconditions

  - The school has a configured [SIS](../services/school-information-system.md) and [LMS](../services/learning-management-system.md)

## Basic Flow of Events

1. The use case begins when [Administrator](../roles/administrator.md), initiates the setup from within the [Learning Application](../services/learning-application.md) to add a new [SIS](../services/school-information-system.md)
2. [Learning Application](../services/learning-application.md) allows a [Administrator](../roles/administrator.md) to create a connection to a [SIS](../services/school-information-system.md).
3. Request access from [Learning Application](../services/learning-application.md)  to [LMS](../services/learning-management-system.md)
4. The [Learning Application](../services/learning-application.md) sends:
   - API Token Request
5. [SIS](../services/school-information-system.md) allows an [Administrator](../roles/administrator.md) to approve a request for API access.
   - API Token Request
6. Approve access re	quest to [Learning Application](../services/learning-application.md)
7. The [SIS](../services/school-information-system.md) responds:
   - API Token
8. [Learning Application](../services/learning-application.md) can retrieve data from [SIS](../services/school-information-system.md).
9. Synchronize data from [SIS](../services/school-information-system.md) to [Marketplace](../services/marketplace.md)
   - Groups
   - Classes
   - Streams
   - Teachers
   - Students
10. [Learning Application](../services/learning-application.md) allows a [Administrator](../roles/administrator.md) to create a connection to a schools [LMS](../services/learning-management-system.md)
11. Request access from [Learning Application](../services/learning-application.md) to [LMS](../services/learning-management-system.md)
12. The [Learning Application](../services/learning-application.md) sends:
    - API Token Request
13. [LMS](../services/learning-management-system.md) allows an [Administrator](../roles/administrator.md) to approve a request for API access.
    - API Token Request
14. Approve access re	quest to [LMS](../services/learning-management-system.md)
15. The [LMS](../services/learning-management-system.md) responds:
    - API Token
16. The use case ends

## Post-conditions

  - Connections are made between [SIS](../services/school-information-system.md), [LMS](../services/learning-management-system.md) and [Learning Application](../services/learning-application.md)
  - [Learning Application](../services/learning-application.md) can pull data from [SIS](../services/school-information-system.md) to synchronize
  - [Learning Application](../services/learning-application.md) can push updates to [LMS](../services/learning-management-system.md)
