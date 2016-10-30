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
  * Classical Maintainance is done after installation, if not it is considered Classical Development
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
* Proper time and budget estimation
* **Planning and the Software Process**
  * Accuracy of estimation increases as the process proceeds (Earliest appropriate time: End of analysis)
  * Cone of Uncertainty (RADI)
* **Break Even Point**
  * Fixed Cost vs Variable Cost, where revenue = total cost
  * Reduce fixed cost and change to variable cost (Overall profit, productivity based wages)
* **Estimating Duration and Cost**
  * Internal Cost: Developer team, personnel, hardware/software, utilities, etc
  * External Cost: Price client will pay
  * **Size Metrics**:
    * **Lines of Code**: Not really practical
    * **FFP**: Files (Transaction Records), Flows (Data Interfaces eg. Screen, Report) and Processes (Logical/Arithmetic Maniplation of Data)
      * Size = Sum of everything
      * Cost = b (constant of efficiency)
      * Problem: Never extended to include databases
    * **Function Point**
      * FP = (4Inp)+(5Out)+(4Inq)+(10Maf)+(7Inf)
      * Input, Output, Inquiry Types, Master Files, Interfaces
      * Problem: Maintenance can be inaccurately measured
    * **Techniques of Cost Estimation**
      * **Delphi Technique**: Compare target to completed products, result of estimation by a broad group of experts
        * Ask a series of questions, aggregate results fed back
        * Each individual asked if they wish to change their forecast
          * Iterative until no one changes their forecast or consensus is reached
      * **Bottom-up Approach**
        * Process-level costing, can be done using object-oriented paradigm
        * Weakness: A product is worth more than the sum of its components
* **Components of a Software Project Management Plan**
  * **Work to be done**
    * **Work Categories**
      * Project Function (Work carried throughout project)
      * Activity (Major units of work eg. budget, design schedules, source code)
      * Task (Minor units of work; activity that comprises a set of tasks)
    * **Milestone**: The date on which work product is to be completed (Becomes a baseline after review)
    * Work Package: Product + Staffing requirements, acceptance criteria, detailed budget, etc
  * **Resources with which to do it**
    * Rayleigh Curves
      * Effort = 0.3945K
      * K = total manpower required or area under Rayleigh Curve
      * 40% development, 60% maintenance
  * **The money to pay for it**
* **Software Project Management Plan Framework**
  * eg. **IEEE Standard 1058.1**: Ideal for Unified Process and supports process improvement
* **Project Scheduling**
  * Identify Activities (Software Requirements)
  * Identify Activity Dependencies
  * Estimate resources for activities
  * Allocate people to activities
  * Create project charts
  * **Critical Path Method**: Refer to other notes
* **Planning Testing**
  * Traceability, must state what testing is to be done
  * Black box test cases must be drawn as soon as specs are complete
* **Planning OO Projects**
  * Whole > Sum of its parts
  * Reuse induces errors in cost and duration estimates
* **Training Requirements**
  * Users and members of the development group need training, even in software planning
    * Introduction to hardware/software tools
    * Training in OS or implementation language
    * Documentation Preparation
  * Train computer operators
* **Documentation Standards**
  * For every 100hrs spent on coding, 150-200 were spent on documentation activities
    * Planning, Control, Financial, Technical, Source Code, Comments
  * Standards assist maintenance programmers
  * The product is the documentation
* **CASE tools for planning and estimating**
  * Management tools to assist with planning and monitoring
  * Word processor and Spreadsheet
* **Testing SPMP**
  * Check the SPMP as a whole
  * Most important: **Duration and Cost Estimates**

# Software Life Cycle
* **Types of SLC Activities**
  * Feasibility and Market Analysis
  * Requirements Engineering
  * Project Planning
  * Design
  * Implementation
  * Testing
  * Delivery
  * Maintenance

##Code and Fix
  * Implement first version
  * Modify until client is satisfied
  * Postdelivery Maintenance
  * Retire

## Waterfall
* **One phase after another**: Documentation approved by SQA group
* Feedback loops, documentation driven, DFD/UML
* **Steps**
  * Requirements: Explore the concept, get client requirements
  * Analysis: "What is the product supposed to do?" (Specification Document, Project Management Plan)
  * Design: "How the product does it" (Architectural design)
  * Implementation: Coding, Integration, Testing
  * Maintenance: Corrective (Bugs), Perfective (Performance/Functionality), Adaptive (Environment)
  * Retirement* **Rapid Prototyping**
* **Advantages**
  * Standardised series of steps (no important aread overlooked)
  * Formal contract: Evidence to arbitrate disputes
  * Suitable for large projects
  * Documentation and Maintenance are easier
* **Disadvantages**
  * Difficult to change user requirements
  * Poor communication between user and developer = wrong specification = RIP
  * Very low user involvement; Users sign documents they don't understand

## Rapid Prototyping Model
* Emphasises User Involvement, Protoype, Reuse and Automated Tools
* Literally the waterfall model applied successively
* **SWAT**: Skilled With Advanced Tools Team (Builds prototypes rapidly)
* Mostly GUI, no real functionality: Users get to try it out
* **Advantages**
  * Improves flexibility (User involvement and communication)
  * Suitable for in-house development (paid by time)
  * Prototype gives insight to design team
  * Requirements and problems are clearer/earlier detected
* **Disadvantages**
  * Extensions of devleopment schedules
  * Building a prototype quickly requirs an experienced team
  * Users may make unnecessary cchanges
* **Iterative and Incremental**
* Miller's Law: Can only retain ~7 chunks of information
* **Stepwise Refinement**: Philosophy of continuous improvement
* Doing 7 requirements after sorting them in order of importance 
* **Iteration**: Continuous improvement; each version is closer to the target
* **Increment**: Piece by piece construction. Each increment goes through multiple versions
* **Strengths**:
  * Multiple opportunities to check if the product's correct
  * Robustness of architecture determined early
  * Resolve risks early
  * Working version of software from the start
  * Empirical evidence that it works

## Agile
* **User Stories**
* Pair Programming
* Stand-Up Meetings: Stand in a circle, last no more than 15 minutes
  * Aim: Raise problems, not solve them
* Agile: Ability to respond to change
* **Manifesto of Principles**
  * Individuals&Interactions > Processes&Tools
  * Working Software > Comprehensive Documentation
  * Customer Collaboration > Contract Negotiation
  * Responding to Change > Following a Plan
* Deliver software ideally every 2-3 weeks using **timeboxing** as a time-management technique
* **Properties**
  * Iterative Development
  * Adaptable: Evolves with each iteration
  * People-Centric: Developers and Management Equal
* Successful for small-scale software development
  * Key decider: Impact of agile processes on post-delivery maintenance

## Extreme Programming
* Specific instantiation of an agile process
* Addresses the problems of quickly delivering software and evolving it to meet changing needs
* Emphasisses team work, customer participation and concentration in the essential 
* Not a complete framework, but has some principles/features to follow
  * A client representative is always present
  * Refactoring
* Turn up the knob to 10 on each practice (eg. continous code reviews, testing, integration, refactoring, refinement)
* **Activities**
  * **Product**: Requirements and Priorities (Stories)
  * **Release**: Stories are analysed and prioritised, Developer determines technical approach & estimates (Release Plan)
  * **Iteration**: Task Breakdowns (Iteration Plan and Deployable System)
  * **Task** Developers sign up for tasks and begins to implement, Acceptance Tests, Evaluate how full iteration is
  * **Episodes**: Pair partners do daily devel
* **YAGNI**: You aren't gonna need it
* **DTSTTCPW**: Do the simplest thing that could possibly work

## Open Source
* **Two Informal Phases**
  * Individual builds an initial version
  * If there's sufficient interests, users become co-developers
    * Reporting an correcting defects
    * Adding additional functionality
    * Porting the program to a new environment
    * **Post-delivery maintenance**
* Failure reports (behaviour), but also fault reports (incorrect source code)
* Maintained by unpaid volunteers

## Synchronize and Stabilize
* Divide project into 3-4 builds carried out by small teams working in parallel
* **Synchronize**: Integrate component, test and debug
* **Stabilize**: Freeze the build, fix bugs
* Components always work together: Flexible modifications and early insights into operation of the product

## Spiral
* Rapid prototyping model plus (alternatives and) risk analysis before each phase, and evaluation/planning of the next phase afterwards [Full Spiral]
* Risk Analysis: Identify the sub-problem with the highest associated risk, find a solution
* **Advantages**
  * No distinction between development and maintenance
  * Easy to judge how much to test
* **Disadvantages**
  * For large scale software only
  * Early termination

## Risks in Software Development
* We want to minimize risks
  * Possible solutions: Prototypes, Proofs of concept
