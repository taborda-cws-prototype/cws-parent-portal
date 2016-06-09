Prototype URL: [https://parentportal.tabordasolutions.net](https://parentportal.tabordasolutions.net)

## Taborda - Agile Development Pre-Qualified Vendor Pool Prototype
# Technical Approach *(2)*

Our team utilized an “outside-in” product development approach for the ADPQ prototype application. An “outside-in” approach focuses on end user’s needs and experience to drive features along with supporting application program interfaces (API). Focusing on the end user means that their needs are implemented pervasively throughout the application. This practice promotes end user satisfaction and system adoption through continuous interaction and feedback.  At a high level, our team utilized the following approach for this prototype:

* Conducted user research to understand needs and trends within related industry. Our User Researcher conducted user interviews with a current CPS worker and people acting as the identified personas (parent/guardian) to create the initial application concept (2c).
* Created initial user interface documented as wireframes (Balsamiq) which were presented to both CPS workers and staff members representing the personas associated with the system. Feedback was incorporated into an updated user interface design (InVision) (2g).
* Identified user stories to form the initial product backlog. 
* Developed initially fully interactive prototype web/mobile application. The initial prototype was presented to the same representative user base from the user research phase. The findings from users actually interacting with the application such as usability improvements were re-incorporated into the actual design (2g).
* Developed fully functioning prototype including back-end API for data persistence as a series of “vertical slices” to allow for testing throughout the effort.

The “outside-in” product development approach incorporates the application development aspects of the U.S. Digital Services Playbook (Playbook). 


## Architecture

Our protoype's high level architecture is based on a JavaScript based front end (Angular.js) supported by Java based API (Dropwizard) with a PostgreSQL database.

[Application Architecture](https://github.com/taborda-cws-prototype/cws-parent-portal-documentation/wiki/Application-Architecture)

# Adherence to U.S. Digital Services Playbook *(2)*

Per the RFI, we followed all of the applicable Playbook plays for the prototype. [Details here](https://github.com/taborda-cws-prototype/cws-parent-portal-documentation/blob/master/us-digital-services-playbook/us-digital-services-playbook-details.md).

# Taborda Prototype Team
## Team Leader *(2a)*
Taborda assigned Brendan McGuire as the one leader with authority, responsibility, accountability for quality of prototype.

## Product Development Team *(2b)*
Multi-disciplinary and collaborative team includes eight (8) labor categories:

1. Product Owner – Brendan McGuire, CSM
2. Technical Architect – Rich Bach, CSM
3. Interaction Designer/User Researcher/Usability Tester – Lacy Carter, CSPO
4. Visual Designer – Husam Alrubaye
5. Front End Web Developer – Justin Castillo, Husam Alrubaye
6. Back End Web Developer – Tom Parker
7. DevOps Engineer – Chris O'Meara, CSM
8. Agile Coach – Gregg Hill, CSM

# Understanding of User Needs*(2c)*
We employed Human-Centered Design (HCD) to elicit user requirements that ultimately became the Product Backlog. The section below summarizes our HCD process for the prototype. [Details here](https://github.com/taborda-cws-prototype/cws-parent-portal-documentation/wiki/Human-Centered-Design-Process)

## Human-Centered Design *(2d)*
### Inspiration

* Developed **Design Challenge**: "*How might we implement a modern, convenient app for parents to communicate with case workers and easily access resources?*"
* Conducted 1:1 and Group Interviews with real case worker and several non-participating staff
* Conducted user research to identify target audiences
* Developed personas
* Brainstormed, starting with "_Diverge_" step to get all ideas (no concern for viability/feasibility), then "_Converged_" to reduce ideas list to only viable/feasible.

### Ideation
* Synthesized insights from users (wants):
	* Simple / Intuitive
	* Trustworthy
	* Case worker / children photos
	* Print time-stamped case worker conversations  
* Created [user stories](https://github.com/taborda-cws-prototype/cws-parent-portal-documentation/tree/master/stories)
	* [Create Profile](https://github.com/taborda-cws-prototype/cws-parent-portal-documentation/wiki/User-Story:-Create-Profile)
	* [Log In / Register](https://github.com/taborda-cws-prototype/cws-parent-portal-documentation/wiki/User-Story:-Log-in-or-Register)
	* [Update/View Profile](https://github.com/taborda-cws-prototype/cws-parent-portal-documentation/wiki/User-Story:-View-or-Update-Profile)
	* [View Foster Family Agencies in Zip](https://github.com/taborda-cws-prototype/cws-parent-portal-documentation/wiki/User-Story:-View-Foster-Agencies-in-Zip)
	* [Send/Reply to Message](https://github.com/taborda-cws-prototype/cws-parent-portal-documentation/wiki/User-Story:-Send-or-Reply-to-Message)
	* [Receive Messages](https://github.com/taborda-cws-prototype/cws-parent-portal-documentation/wiki/User-Story:-Receive-Messages)
* Brainstormed designs during internal & user [whiteboard sessions](https://github.com/taborda-cws-prototype/cws-parent-portal-documentation/tree/master/whiteboard) *(2c)*
* Updated user stories elaborations surfaced, including acceptance criteria *(2g)*

### Implementation
* Developed [Balsamiq low-fi wireframes](https://github.com/taborda-cws-prototype/cws-parent-portal-documentation/tree/master/wireframes) - using whiteboard designs & feedback from internal/user testing *(2g)*
* Conducted user tests and gathered feedback *(2f)*
* Developed [PhotoShop/InVision high-fi web mockup prototype](https://github.com/taborda-cws-prototype/cws-parent-portal-documentation/tree/master/hi-fi-mockups) - using wireframes / user testing feedback *(2g)*
* Conducted mockup prototype user tests; gathered feedback *(2f)*
* Developed live [Design Style Guide (DSG)](https://parentportal.tabordasolutions.net/guidelines.html) using bootstrap/SASS/CSS/HTML. DSG elements leveraged from HTML mockup / user testing feedback. *(2g)*
* Conducted responsive design testing on desktop and mobile devices (iOS, Android) *(2h)*
* Design element updates were made to DSG as prototype was elaborated – keeping DSG and prototype pages consistent and synchronized *(2e)*
* Developed prototype HTML using HTML mockup, user testing feedback, and DSG
* Iterated on pages, incorporating user testing feedback between iterations, finally reaching minimal viable product (MVP) *(2g)*

## Prototype Development
### Modern Open Source Technologies *(2i)*
#### All Open Source Solution Components (Build dates in parens) 
* Front end
	* Bootstrap (5/2016)
	* Javascript
	* Angular.js (5/2016)
	* jQuery (5/2016)
	* SASS (5/2016)
	* Font-Awesome (5/2016)
	* JSON Web Token (5/2015)
	* WAVE (3/2016)
	* Web Server – NGINX
* Back end
	* Java (6/2016)
	* Dropwizard (5/2016)
	* Jetty – Web Server (6/2016)
	* Jersey – RESTful web services (6/2016)
	* Jackson – JSON Processor (5/2016)
	* Guava (5/2016)
	* Hibernate ORM (4/2016)
	* Flyway (5/2016)
* Database – PostgreSQL
	
#### Automated Unit Testing *(2k)*
* Front end
	* Protractor (6/2016)
	* Jasmine (3/2016)
* Back end
	* Junit 4 (6/2016)
	* Mockito (6/2016)

#### Continuous Integration *(2i, 2l, 2m)*
Implemented Jenkins inside Docker container on AWS for automated testing as code is checked in to GitHub.

* Configuration Management - GitHub
* Continuous Integration, Automated Testing / Deployment - Jenkins (6/2016)
* Build
	* Front end – Gulp (6/2016)
	* Back end – Gradle (6/2016)
- Deploy
  - Server – Docker (5/2016)
  - Developer – Docker Composer (5/2016)

#### Prototype Deployment Environment *(2j)*
The prototype deployed to AWS (FedRAMP-certified IaaS). 

[Infrastructure Architecture](https://github.com/taborda-cws-prototype/cws-parent-portal-documentation/wiki/Infrastructure-Architecture)


#### Configuration Management *(2m)*
The GitHub Repository is organized as:

* [Taborda CWS Prototype](https://github.com/taborda-cws-prototype/cws-parent-portal-documentation)
	* [Back End API](https://github.com/taborda-cws-prototype/cws-parent-portal-api)
	* [Front End UI](https://github.com/taborda-cws-prototype/cws-parent-portal-ui)
	* [Artifacts](https://github.com/taborda-cws-prototype/cws-parent-portal-documentation)
	* [Containers](https://github.com/taborda-cws-prototype/docker)

### Continuous Monitoring *(2n)*
NodePing validates application availability every 3 minutes from multiple locations in the U.S. and alerts the Taborda operations team if there is any disruption to service availability.
Datadog continuously monitors system resources and alerts the Taborda operations team of potential issues before those issues impact availability.
PagerDuty delivery alerts to the Taborda operations team according to a 24x7 duty schedule.

### Containerization *(2o)*
Deployment in Docker container.

### Deployment Documentation *(2p)*
***Insert one sentence here***

[Deployment Docs](https://github.com/taborda-cws-prototype/cws-parent-portal-documentation/wiki/Deployment-Documentation)

### Prototype / Underlying Platform Licensing *(2q)*
The prototype and underlying platforms are open licensed and free of charge.

# NOTES

* The prototype implemented a simple authentication scheme that stores identity in the application database and passes the user token in response headers. A production-grade application  would implement SAML 2.0 or OATH solution with centralized user store decoupled from the application.

* Some artifacts were checked in later due to infrastructure being built in parallel with the human-centered design process.

* We developed unit tests during test-driven development, but only developed a sampling of unit/integration tests during defect fixes due to time constraints.

