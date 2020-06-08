# S.1.0 Learning Application establishes relationship with Sales Agent

This is a process that occurs only once, when a Learning Platform provider establishes a commercial relationship with a [Marketplace](../services/marketplace.md). The [Marketplace](../services/marketplace.md) will identify itself and request catalogue information from the Learning Platform, with the Catlaogue response products can be sold through the [Marketplace](../services/marketplace.md).

## Roles Involved

  - [Administrator](../roles/administrator.md) [of [Marketplace](../services/marketplace.md)]
  - [Administrator](../roles/administrator) [of Learning Platform]

## Preconditions

  - A commercial agreement is in place between the learning application and the [Marketplace](../services/marketplace.md) owner

## Basic Flow of Events

### Scenario:  Marketplace initiated

 1. The use case begins when administrator, initiates the setup from within the [Marketplace](../services/marketplace.md) to add a new learning platform
 2.	The administrator creates an entry for the the Learning Platform
 3.	The administrator adds API credentials provided by the Learning Platform
 4.	The [Marketplace](../services/marketplace.md) can now request catalogue information from the Learning Application.

## Post-conditions

  - Learning Application products are available in [Marketplace](../services/marketplace.md) for sale
  - [Marketplace](../services/marketplace.md) can send a fulfilment request to the Learning Application
