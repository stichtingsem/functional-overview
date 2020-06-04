# Use-Case: Marketplace Setup
##  1	Brief Description
This is a process that occurs only once, when a Learning Platform provider establishes a commercial relationship with a Marketplace. The Marketplace will identify itself and request catalogue information from the Learning Platform, with the Catlaogue response products can be sold through the Marketplace.
## 2	Actor Brief Descriptions
2.1	Administrator/owner of Marketplace
## 3	Preconditions
3.1 A commercial agreement is in place with the marketplace owner (distributor)
## 4	Basic Flow of Events
    1.	The use case begins when administrator, initiates the setup from the marketplace.
    2.	The administrator selects the Learning Platform to establish a connection with
    3.	The adminsitrator sets up an API credential exchange
    4.	The marketplace sends: 
        System metadata
        Commercial metadata
    Requests [Catalogue]
    5.	The learning platform responds:
    [Catalogue] 
    Commercial metadata
    7.	The use case ends.
## 5	Post-conditions
5.1	Learning Platforms catalogue products are available in Marketplace for sale
