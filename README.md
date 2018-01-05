# Software development project checklist

What is the name of the project?
What is the project metaphor?

Project investor (pays the bills)
What is their name and position?
What is their project vision?
Do they have a project business case?
Does the business case cover the development needs realistically?
Is the revenues side of the business case realistic?

Domain expert (knows what is now being done and why)
What are their names and positions?
What are their domains of expertise?
Do they express what is being done now (before the new system) concisely?
Do they explain the business reasons behind the tasks performed?

Product owner (defines the product)
What is their name and position?
Do they have complete authority to define the product (no interventions)?
Do they express feature requirements concisely?
Are the requirements consistent (between features and over time - no changes)?
Do they prioritize requirements by business value?

Analyst (achieves agreement between product owners and developers, keeps the system functionality consistent)
What is their name?
Do they write functional specification?

Analytical / Functional specification
Is there a written FS?
Do product owners read and understand FS?
Do product owners confirm that the FS is correct and complete?
Do testers produce acceptance test cases based on the FS and nothing else?
Do developers implement the system based on the FS and nothing else?
Does the FS provide a clear and comprehensive specification of the UI (screen mockups)?
Does the FS specify the APIs provided (inbound operations, data structures)?
Does the FS specify the functionality (algorithms, validations)?
Does the FS specify the data model?
Does the FS specify the APIs called (outbound operations, data structures)?
Does the analysis specify volumes of data stored and increments per time interval for each significant system entity?

Development
Is a new version available for testing at least monthly?
Is there a fixed time interval in which new versions are released? Which one?
Do developers decide the time required to implement the features?
Is source code kept in a version control system?
Are changes to source code reviewed?
Is all system functionality covered with programmers’ tests?
Is technical debt resolved right away?
Is all source code shared by all developers?
Do developers only work standard hours?
Do developers share their progress at least daily?
When developers become stuck do they receive help to overcome it?
Are developers given an opportunity to raise issues with project setup, organization and process?
Are these issues addressed and resolved in a timely manner?

Testing
What are the names of testers?
Do testers write explicit acceptance test scenarios?
Do product owners read and understand acceptance test scenarios?
Do product owners confirm that the acceptance test scenarios are correct and complete?
Do product owners accept releases based on acceptance tests?
Do product owners always accept the release when it passes the acceptance tests?
Do product owners participate in writing acceptance test scenarios?
Is there a dedicated environment for acceptance testing?
Is each new version subjected to acceptance tests?
Are issues identified in testing resolved in the next version?
Do acceptance tests cover load testing?
Are acceptance test scenarios for provided APIs automated?

If there are system interfaces (either inbound or outbound):
Do testers write explicit system integration test scenarios?
Is there a dedicated environment for system integration testing?
Is a new version subjected to system integration test at least monthly?

Deployment
Is deployment to production environment automated?
Is the same automated deployment process used to deploy all versions being deployed on all environments?

Data migration
Is there a legacy system to be replaced?
Is the migration automated?
Create a separate project checklist for development of the migration software.
