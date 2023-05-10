# IMPACT
Intelligent Machine for Patient Accrual and Classification Tasks. This is the parent project repository. For specific components and associated setup instructions please visit one of the repositories listed below:

* [API](https://github.com/OHNLP/impact-api) - An API for developers to implement custom IMPACT components. You will need to build this first for both the backend and middleware. This repository also contains commonly used implementations of certain components (e.g., an OHDSI OMOP CDM data connector, and UMLS code resolution service)
* [Backend](https://github.com/OHNLP/impact-backend/) - The Engine that performs clinical phenotyping based on a supplied criteria definition. Jobs are typically launched via Middleware rather than through direct execution
* [Middleware](https://github.com/OHNLP/impact-middleware/) - REST API provider, Phenotying definition management, and retention of query results and adjudication
* [Frontend](https://github.com/OHNLP/impact-webapp) - A frontend web interface for IMPACT

Additionally, general architecture diagrams, REST API documentation, and middleware DDLs can be found in the [Documentation](https://github.com/OHNLP/impact-documentation/) repository
