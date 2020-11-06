# Java/Web Developer Project
This is a project that we use for evaluating the technical skills of potential team members. The expectation is that you will spend a maximum of 2-3 hours working on the project. We don't expect the code to be perfect, but we would expect it to follow good coding patterns and conventions. Our goal is to get a feel for the style of code you write as well as your thought process and problem solving skills.

## Feature Request App
Build a web application that allows the user to manage "feature requests".

A "feature request" is a request for a new feature that will be added onto an existing piece of
software. Assume that the user is an employee who would be entering this information after
having some correspondence with a client that is requesting the feature.  The necessary fields
are:

* **Title:** A short, descriptive name of the feature request.
* **Description:** A long description of the feature request.
* **Client:** A selection list of clients (use "Client A", "Client B", "Client C")
* **Client Priority:** The feature's priority number according to the client (1...n). Client Priority numbers
should not repeat for the given client, so if a priority is set on a new feature as "1", then all
other feature requests for that client should be adjusted.
* **Target Date:** The date that the client is hoping to have the feature.
* **Product Area:** A selection list of product areas (use 'Policies', 'Billing', 'Claims',
'Reports')

## Tech Stack
The following are the tools our team favors.  They are preferred, but not required, for this project.

* Java 8+
* Spring Boot
* JPA/Hibernate
* Angular

## Guidelines

Build your own public repo on github, and call it whatever you like. Build your solution in your
repo, and include a README.md file that contains the detailed instructions for running your web app.
**Please do not commit your target or node-modules directories to the repository.** Email the URL for 
your github repo to your hiring manager once you begin the project so we can review 
your progress. Once your project is completed, please email your hiring manager.

One of the major goals in this project is to see how you fill in ambiguities in your own creative
way. There is no such thing as a perfect project here, just interpretations of the instructions
above, so be creative in your approach.

We want to be respectful of your time and set realistic expectations for submission. To help guide you, we 
have included the list below which details common practices in the best projects we receive. It is rare for 
a project to match every item in this list, but the candidates we hire typically showcase several of 
these features in their work.

## Technology

1. *Open Source*. We have a strong affinity for open source technology. If your go-to technology stack includes
proprietary software, you won't be helping yourself to use it in this project.

2. *Decoupled Backend*. We are looking for candidates with a strong understanding of the entire web application stack. The best projects will have a completely decoupled backend and front end (though not necessarily separate repositories). They will communciate via API.

3. *Test Suites with Continuous Integration*. Enterprise production requires rock solid stability. All code submitted into WCF repos must contain unit and regressions tests, so we favor candidates with experience writing quality tests.

4. *Usable, Responsive Interface*. There are many accessible CSS frameworks out there such as Bootstrap. All modern web applications should be responsive and these frameworks make it very easy to create a modern interface that adheres to established design principles and formats well on all devices.

Thank you for your time. We are excited to review your project!
