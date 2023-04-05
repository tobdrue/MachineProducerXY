# Architecture / Coding Challenge - Engineering Org

### Story

We have the new customer 'Engineering Org'. This customer is a giant machine producer and operator. Right now he has about 50 k Machine in production and the plans are to scale up to 300k.

The customer contracted us to develop a platform to work centrally with the machine data and has many visions of how this could develop further (remote services, ML, IIOT,...).



At the current state, the machines already collect operating data and can make it available via an API. ([schema](machine-data.schema.json), [example data](machine-data.json))



In addition, master data for the machines could be made available from SAP. ([schema](machine.schema.json), [example data](machine.json))

So in a first step the customer wants to visualize the machine data for the technicians. 
For this we have identified some feature that we need to archive:
1. The user needs to find a machine (name, location, current counter and current status are important). Options are:
   2. Search
   3. Machine List view
2. Machine Events are displayed
3. The User can Search for the data Id, as it can be matched with the produced parts

So there are a lot of different things to do. (UI, Algorithms, Architecture, ...)

### Coding Challenge

For this coding challenge we want to imagine that we are at sprint 1 of our project

* Please invest about 2h to create a solution for any part of the application
* focus on the parts where you feel the strongest
* you can use the test data (or modify it how you need it) as fake inputs at any level
* create a pull request



status, error