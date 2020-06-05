
# S.2.0 Administrator establishes relationship between SIS, LMS and Marketplace

Establish the connections between the [SIS](../services/school-information-system.md), the [Marketplace](../services/marketplace.md) and the [LMS](../services/learning-management-system.md) used within a school (done only when these systems change or new services are added).  Note this is three separate processes grouped together below for simplicity.

## Roles Involved

  - [Administrator](../roles/administrator.md) [of [Marketplace](../services/marketplace.md)]
  - [Sales agent administrator](../roles/sales-agent.md)

## Preconditions

  - A commercial agreement is in place between the school and the [Marketplace](../services/marketplace.md) 

## Basic Flow of Events 

1. The use case begins when [Administrator](../roles/administrator.md), initiates the setup from within the [Marketplace](../services/marketplace.md) to add a new [SIS](../services/school-information-system.md) 
2. [Marketplace](../services/marketplace.md) allows a [Sales agent administrator](../roles/sales-agent.md) to create a connection to a [SIS](../services/school-information-system.md).
3. 					Request access from [Marketplace](../services/marketplace.md) to [LMS](../services/learning-management-system.md)
4. 					The [Marketplace](../services/marketplace.md) sends: 
 - API Token Request
5. [SIS](../services/school-information-system.md) allows an [Administrator](../roles/administrator.md) to approve a request for API access.
- API Token Request
6. Approve access re	quest to [Marketplace](../services/marketplace.md)
7. The [SIS](../services/school-information-system.md) responds:
- API Token
8. [Marketplace](../services/marketplace.md) can retrieve data from [SIS](../services/school-information-system.md).
9. Synchronize data from [SIS](../services/school-information-system.md) to [Marketplace](../services/marketplace.md)
- Groups
- Streams
- Subjects
10. [Marketplace](../services/marketplace.md) allows a [Sales agent](../roles/sales-agent.md) to create a connection to a schools [LMS](../services/learning-management-system.md)
11. 	Request access from [Marketplace](../services/marketplace.md) to [LMS](../services/learning-management-system.md)
12. The [Marketplace](../services/marketplace.md) sends: 
- API Token Request
13. [LMS](../services/learning-management-system.md) allows an [Administrator](../roles/administrator.md) to approve a request for API access.
- API Token Request
14. Approve access re	quest to LMS
15. The [LMS](../services/learning-management-system.md) responds:
- API Token
13. [LMS](../services/learning-management-system.md) allows an [Administrator](../roles/administrator.md) to create a connection to a [SIS](../services/school-information-system.md).
14. 			Request access from LMS to [SIS](../services/school-information-system.md)
15. 			The [LMS](../services/learning-management-system.md) sends:
- API Token Request
16. [SIS](../services/school-information-system.md) allows an [Administrator](../roles/administrator.md) to approve a request for API access.
- API Token Request
17. 	Approve access re	quest to [SIS](../services/school-information-system.md) data
- API Token
19. [LMS](../services/learning-management-system.md) can retrieve data from [SIS](../services/school-information-system.md)
20. 		Synchronize data from [SIS](../services/school-information-system.md) to [LMS](../services/learning-management-system.md)
- Groups
- Streams
- Subjects
- Teachers
- Students
21. The use case ends

## Post-conditions

  - Connections are made between [SIS](../services/school-information-system.md), [Marketplace](../services/marketplace.md) and [LMS](../services/learning-management-system.md)
  - [Marketplace](../services/marketplace.md) and [LMS](../services/learning-management-system.md) can pull data from [SIS](../services/school-information-system.md) to synchronize