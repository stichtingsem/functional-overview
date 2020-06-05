
# S.2.0 Administrator establishes relationship between SIS, LMS and Marketplace

Establish the connections between the LAS, the Marketplace and the LMS used within a school (done only when these systems change or new services are added).  Note this is three separate processes grouped together below for simplicity.

## Roles Involved

  - [Administrator](../roles/administrator.md) [of [Marketplace](../services/marketplace.md)]
  - [Administrator](../roles/administrator) [of Learning Platform]

## Preconditions

  - A commercial agreement is in place between the learning application and the [Marketplace](../services/marketplace.md) owner

## Basic Flow of Events - new SIS

 1. The use case begins when administrator, initiates the setup from within the [Marketplace](../services/marketplace.md) to add a new learning platform
 2.	The administrator creates an entry for the the Learning Platform
 3.	The administrator adds API credentials provided by the Learning Platform
 4.	The [Marketplace](../services/marketplace.md) sends:
    - Catalogue Request
 5.	The learning platform responds:
    - Catalogue Response
 6.	The use case ends.

## Post-conditions

  - Learning Application products are available in [Marketplace](../services/marketplace.md) for sale
  - [Marketplace](../services/marketplace.md) can send a fulfilment request to the Learning Application
