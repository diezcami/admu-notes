# Introduction to Software Engineering

## Software in General
* **Software**
  * Computer Programs and Associated Documentation
  * Software Products: Generic or Custom, both a Good and a Service
  * Can be created by: developing new programs, configuring generic systems, reusing existing software
  * Can be bought or built by companies depending on needs
  * **Software Activities**: Progressive or Anti-Regressive
  * **Software Engineering**: 
    * SE is a set of methods, standards and procedures applied to the definition, development and maintenance of computer software.
    * SE seeks to bring discipline and rigor to the building and maintenance of software systems.
    * We depend heavility on software, yet SD field lacks discipline: delayed projects, costs and schedules slip.
* **Software Nature**
  * Intangible Production (High Product Costs)
  * Construction is **Intellectual Value Intensive**
  * Non-Consumable (Short Life Time, max 5 years)
  * We sell information and intensive/complex solutions, **An Information Service**
  * Malleable (Difficult to monitor)
  * Dynamic/Adaptable Environment
* **Software Quality**
  * Delivered on time, within budget and functional
  * High quality and performance (Efficient)
  * Usable and Flexible (UX)
  * Understandable and Maintainable (Docs, Long Term)
  * Reliable (Dependable)
  * Portable (Adaptable)
* **Facts about Software**
  * Software costs increase as hardware costs decline (Software Crisis)
  * **Known Software Failures**: Ariane 5, Therac-25, Mars Climate Orbiter
  * Modern aspects are more systematic: methods, languages, processes
  * Ability to produce more complex in general has increased
  * Software Production = Development + Maintenance (>60% of all development costs)

## Software Development Life Cycle
* **Life Cycle Model**: Theoretical phases involved in building software
* **Life Cycle**: Actual steps performed
* **Classical Life Cycle Model**:
  * Definition/Analysis: Planning, Requirements, Design
  * Development: Coding, Testing
  * Maintenance: Bug fixes, Updates (Perfect/Adaptive), Change Requirements => Retire
* **Waterfall Life Cycle Model**: 
  * Requirements: Explore the concept, get client requirements
  * Analysis: "What is the product supposed to do?" (Specification Document, Project Management Plan)
  * Design: "How the product does it" (Architectural design)
  * Implementation: Coding, Integration, Testing
  * Maintenance: Corrective (Bugs), Perfective (Performance/Functionality), Adaptive (Environment)
  * Retirement
* **Relative Costs**: The earlier we detect and correct a fault, the less it costs us
  * Coding: 1/6
  * Analysis&Design: 1/3
  * Testing: 1/2
  * **Of Fixing**: 80% Design, 20% Logic/Syntax
* **Relative Errors**
  * Syntax: 1/6
  * Programming&Logic: 1/3
  * Design: 1/2

## Computation of Costs (Practice Exercises)
* **Requirements**: 1
* **Specification/Analysis**: 2
* **Planning**: 3
* **Design**: 4
* **Implementation**: 10
* **Integration**: 30
* **Maintenance**: 200

## Maintenance
* **Classical Maintenance**: 
  * Develop-then-maintenance
  * Consequence: Development and Maintenance mostly depend on **when** they take place
* **Modern Maintenance**: 
  * "Process that occurs when a software artifact is modified because of a problem or because of a need for improvement or adaptation."
  * **Post-delivery Maintenance**: After delivery/installation
  * **(Modern) Maintenance**: Performed at any time
  * **Pros**: Software is constantly changing, good software is maintained for 10-20 years
  
## Testing and Documentation
* **Testing**
  * **Verification**: Done at the end of each phase
  * **Validation**: Done at the end of the project
  * Must be continual and carried by developers and QA
* **Documentation**
  * If key programmers leave before documenting, we cannot perform a phase, test or maintain a project without documentation
  * Must be performed in parallel with all other development/maintenance activities

# Team Management
## Democratic Team
* Egoless Programming: because programmers can be highly attached to their code
* Group of up to 10 egoless programmers will develop an ethos/group identity and be encouraged to find faults in code
* Characterised by everyone being equal: competence = sum of its parts
* Organizational Structure: Regular Polygon
* **Strengths**
  * Productive and work best when problem is difficult
  * Function well in a research environment and easy to replace members
* **Difficulties**
  * Beginners are treated as experienced programmers
  * Management may have difficulties (no one is in charge or responsible)
  * Communication problems when members > 5 (reaching a consensus)

## Classical Chief Programmer Team
* Made to solve difficulties in terms of communication channels
* Analogy: Chief surgeon directing an operation
* Key Aspects: **Specialization** and **Hierarchy**
* **Chief Programmer**
  * Successful manager and highly skilled programmer
  * Allocates coding and does architectural design
  * Writes and reviews critical parts of the code
  * Personally responsible
* **Back-up Programmer**
  * As competent as the chief programmer
  * Black box test case planning and other tasks independent of design process
* **Programming Secretary**
  * Maintains program production library (documentation) such as source code listings and test data
  * Converts code to machine-readable form - compiled, linking, running test cases, etc
* **Programmers**
  * Do nothing but program
  * All other aspects handled by the programming secretary
* **The New York Times Project**
  * Chief: F. Terry Baker
  * Only success story for chief programmer teams
* **Impracticality**
  * Chief programmer must be a highly skilled programmer and successful manager (difficult to find)
  * Back-up programmer must be as good as the chief programmer, with a lower salary to stay in the back seat
  * Programming secretary does nothing but paperwork all day

## Problems of CP and Democratic Teams
* Make use of democratic and CP teams, and handle more programmers
  * Democratic: Positive attitude in finding faults
  * CPT: Code walkthroughs or inspections
* Chief Programmer Pitfall
  * Personally responsible for code, and must be present at reviews
  * Also the team manager, and must not be present at reviews (**SOLUTION**: Remove managerial role, easier to find a leader than a CP)
* **Solution**
  * Team Leader
    * Responsible for technical management
    * Participates in reviews
  * Team Manager
    * Participates in regular team meetings to appraise technical skills
    * Budgetary and legal issues
  * For Larger Projects: Decentralize the decision-making process where appropriate (Useful where the democratic team is good)

## Synchronize and Stabilize
* Used by Microsoft
* 3-4 Sequential Builds
* Small parallel teams (3-8 devs, 3-8 testers)
* Daily synchronization step, individual components always work together
* **Analogy**: Letting children do what they want with a 9PM deadline
* A way of allowing a group of hackers to develop large products

## Agile Processes
* **Pair Programming**
* **Collective Ownership (Democratic)**: No layers between managers and engineers, centralized computers (egoless programming)
* Programmers should not test their own code (done by pair)

## Open Source
* No meetings, managers, specs/designs, documentation
* Individuals contribute to open source projects for:
  * Sheer enjoyment of accomplishing a worthwhile task
  * Learning experience
* Software professionals contribute to gain new skills for a promotion or better job offers
* Open source project > Additional academic qualifications
* Key individual behind OSP should be a superb motivator, and core group must have good skills
  * Thrive in the unstructured environment of an open source team
* **Key points for success**
  * Nature of the target product
  * Personality of the instigator
  * Talents of the members of the core group

## People Capability Maturity Model
* **CMM Ranking**: Developed by SE Institute to measure the capability of part of an organization to develop software
* Framework for managing and developing an organization's work force
  * No specific approach to team organization (depends on product, leaders and previous experiences)
  * Can have high capability with no accomplishment

## Conclusion
* **Prisoner Dilemma**: People tend to compete even when they gain from cooperation (Lack of Trust)
* Teamwork is essential for software development. As a result, conflict between the contribution to the teamwork and the way in which rewards are shared may intensify
* Management of software development teams and communication among team members are complex issues
* Software developers are usually highly motivated. Their motivation can cause conflicts between personal targets and team goals.

# Software Project Management

# Software Life Cycle
