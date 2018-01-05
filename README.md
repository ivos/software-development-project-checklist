# Software development project checklist

1. What is the name of the project?
1. What is the project metaphor?


## Project investor
`Pays the bills, expecting to turn the project into profit.`

1. What is their name and position?
1. What is their project vision?
1. Do they have a project business case?
1. Does the business case cover the development needs realistically?
1. Is the revenues side of the business case realistic?


## Domain expert
`Knows what is now being done and why.`

1. What are their names and positions?
1. What are their domains of expertise?
1. Do they express what is being done now (before the new system) concisely?
1. Do they explain the business reasons behind the tasks performed?


## Product owner
`Defines the product.`

1. What is their name and position?
1. Do they have complete authority to define the product (no interventions)?
1. Do they express feature requirements concisely?
1. Are the requirements consistent (between features and over time - no changes)?
1. Do they prioritize requirements by business value?


## Analyst
`Achieves agreement between product owners and developers.` \
`Keeps the system functionality consistent.`

1. What is their name?
1. Do they write functional specification?


## Analytical / Functional specification
`Defines what the system does.`

1. Is there a written FS?
1. Do product owners read and understand FS?
1. Do product owners confirm that the FS is correct and complete?
1. Do testers produce acceptance test cases based on the FS and nothing else?
1. Do developers implement the system based on the FS and nothing else?
1. Does the FS provide a clear and comprehensive specification of the UI (screen mockups)?
1. Does the FS specify the APIs provided (inbound operations, data structures)?
1. Does the FS specify the functionality (algorithms, validations)?
1. Does the FS specify the data model?
1. Does the FS specify the APIs called (outbound operations, data structures)?
1. Does the analysis specify volumes of data stored and increments per time interval for each significant system entity?


## Developers
`Turn the FS into a working system.`

1. Is a new version available for testing at least monthly?
1. Is there a fixed time interval in which new versions are released? Which one?
1. Do developers decide the time required to implement the features?
1. Is source code kept in a version control system?
1. Are changes to source code reviewed?
1. Is all system functionality covered with programmers’ tests?
1. Is technical debt resolved right away?
1. Is all source code shared by all developers?
1. Do developers only work standard hours?
1. Do developers share their progress at least daily?
1. When developers become stuck do they receive help to overcome it?
1. Are developers given an opportunity to raise issues with project setup, organization and process?
1. Are these issues addressed and resolved in a timely manner?


## Testers
`Verify that the system fulfills the FS.`

1. What are the names of testers?
1. Do testers write explicit acceptance test scenarios?
1. Do product owners read and understand acceptance test scenarios?
1. Do product owners confirm that the acceptance test scenarios are correct and complete?
1. Do product owners accept releases based on acceptance tests?
1. Do product owners always accept the release when it passes the acceptance tests?
1. Do product owners participate in writing acceptance test scenarios?
1. Is there a dedicated environment for acceptance testing?
1. Is each new version subjected to acceptance tests?
1. Are issues identified in testing resolved in the next version?
1. Do acceptance tests cover load testing?
1. Are acceptance test scenarios for provided APIs automated?

If there are system interfaces (either inbound or outbound):
1. Do testers write explicit system integration test scenarios?
1. Is there a dedicated environment for system integration testing?
1. Is a new version subjected to system integration test at least monthly?


## Deployers
`Deploy the system to all environments.`

1. Is deployment to production environment automated?
1. Is the same automated deployment process used to deploy all versions to all environments?


## Migration
`Enable seamless transition from the legacy system to the new one.`

1. Is there a legacy system to be replaced?
1. Is the migration automated?
1. Create a separate project checklist for development of the migration software.
