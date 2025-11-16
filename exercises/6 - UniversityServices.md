# University services

To facilitate the use of its spaces, a Swiss university has decided to offer its students a new study room booking service.
The service, accessible by contacting the secretariat, provides the possibility of booking a place in the study room, booking the entire study room, canceling one of the existing reservations, as well as requesting the catering service if the reservation includes a stay during lunchtime.
In particular, this last activity requires the presence of a manager of the catering company.

The secretariat, to satisfy the student needs, relies on two applications: a room booking software and an ERP. While the former offers a Web GUI, the latter has a desktop interface. In turn, the room booking relies on booking catering service which is integrated via API.

Focusing on the ERP this is a three-tiered application, where the node hosting the business logic also hosts the room booking application, that is a standalone one.

A recent innovation at application level has automated the service as also the ERP is able to expose a Web GUI. Now the students can autonomously exploit the offered service by directly accessing to the Web GUIs offered by the two applications.

In this case, the adopted ERP is a SaaS solution offered by a cloud provider, while the room booking remains on-premise.

## Business Layer

![Archimate diagram Business Layer](/images/University-BusinessLayer.png)

## Application Layer

![Archimate diagram Business Layer](/images/University-ApplicationLayer.png)
