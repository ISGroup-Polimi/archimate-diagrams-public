BancaMI wants to offer a new online service for the disbursement of mortgages to its customers in a fully autonomous manner. The service, provided via the Web, is managed by a dedicated application module called “mortgage application” that offers the functionalities of creating a new request and evaluating the request. Specifically, the evaluation of the request provided by this application module requires invoking the functionalities of an already existing module dedicated to analyzing the applicant's reliability.

The “mortgage application” module is configured in a two-tier mode. The client contains only the presentation logic, while the server distinguishes between the application logic (offered through an application server) and data access logic (offered through a database server). Both the application server and the database server are provided by a cloud provider in PaaS mode.

With reference to the previous text, define the Archimate diagram consisting of the Business Layer, Application Layer, and Technology Layer. The modeling of the customer reliability analysis module at the Technological, Business, and Data object levels is not required.

![Archimate diagram](/images/BancaMI.png)
