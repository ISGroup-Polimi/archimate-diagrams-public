# Taxy Service

A company provides a taxi service to its customers. The taxi service is carried out by a process executed by the taxi driver, who accesses the city map. The process consists of three successive phases: picking up the customer, defining the destination, and driving to the arrival point.

As for the application side, the third phase of the process is supported by a map viewing service through the GUI of a map software. This offers the routing function and accesses the city maps. The first phase of the process is instead supported by a customer management service and customer management features, which are made available to the taxi driver through a CRM and its related GUI.

This application setting is supported a cockpit (running on Linux) that hosts the two applications (maps and CRM). Both are offered as desktop applications which communicates with their respective databases, both installed on the same DBMS.

### Business Layer

![Archimate diagram](/images/Taxi-BusinessLayer.png)

## Variant 
As a variant of the previous solution, let assume that the first activity in the process uses the map service which is able to offer information about the customers by calling the CRM which exposes an API.

With this alternative, the technology layer is revised. Notably, the CRM is a two tiered application exposing an API used by the map application. The DB node remains the same.

### Business Layer

![Archimate diagram](/images/Taxi-BusinessLayer-variant.png)
