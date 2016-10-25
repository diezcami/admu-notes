#Requirements Engineering

* process of establishing the services that the customer requires
* application domain, services, constaints
* involved users are called stakeholders

## Requirements
* requirements
	* descriptions of the systems's services, constraints and goals
	* client's point of view 

* purpose of requirment
	* basis for the contract - it must be defined in detail

## Risks 
* clients don't know what they want
* requirements are in clients terms
* conflict between stakeholders and client's organization

## User-Centered Design
* understand user's
* understand user's tasks
* user's are involved in decision making 


##Use Case Diagrams
* visualize, specify, construct, document
* communication between domain experts and end-users
* basis for testing 

## Use Case
* specify the desired behavior
* each sequence represent an interaction of actors with the system

##Actors
* actors can be human or automated systems
* actors are not part of the system

##Relationship between Use Cases
1. __Generalization__ - use cases that are specialized versions of other use cases
	* example child may override the behavior of its parent
2. __Include__ - nessesary
	* can never stand alone
3. __Extend__ - additional, option only
	* branching conditions
	* Ex: Exam-grade appeal extends Exam copy request


###STUDY SLIDES HOW TO DRAW


###DATA FLOW DIAGRAM 

* Data-centric - focus on how data flows in the system 
* Process: the actions performed on the data
* Data flow: movement of the data

####DFD Rules
* There must be an input and output
* All flows must go through as datastore (database)
* data must go through a process 
* interactions between external entities are not represented in the DFD
* bidirectional flow represented by 2 arrows
* joined data must refer to the same data 
* cannot flow through itself

####Data Flow
* Dataflow from a process means updae, delete, or change
* Dataflow from store is to retrieve or use
* Dataflow show labels should be noun of phrase


####Functional Decomposition
* iterative process of breaking a system into finer and finer details

####DFD Levels
* Level 0 DFD
	* representation of major processes at high level of abstraction
* Level 1 
* Level n 
	* result from the decomposition of higher level


###Direct observation

* video taping 

#Requirements
* descriptions of the system's services, constraints and goals with client
* follows client's view point
* understandable by both user and dev staff

###Realistic
	* must be possible to meet the requirements

###Verifiability
	* must be possible to test whether requirement is fulfilled
	
##Types of Requirements

###User requirments
	* written for customers
	* operational contraints

###System requirments(specifications)
*  project specs
*  contract between client and contractor 

##Initial Requirements
* based on the init business model
* dynamic - frequent changes 
	
###Functional
* specifies an action that the software must be able to perform
* experessed in terms of inputs and outputs
* describes the systems behaviors - what kind of actions the system does
	* Functions that must be performed
		* Functionality
		* Data
		* User Interfaces

###Non-Functional 
* specifies properties of the software itself
	* platform constraints
	* response times
	* reliability
*describes other desired attributes of the overall system - how it does them 
	* usability, quality assurance
* Product requirements
	* requirements that specify the behavior of the product
* Organizational requirements
	* requirements as a consequence of organizational policies and procedures
* External requirements
	* requirements arising from external factors

###Requirement Documentation
* General
	* Purpose and scope of system
* Description of System
* Requirments of proposed system
	* overview
	* functional requirements
	* non-functional
* System models
	* scenarios
	* use cases

##Requirments Gathering Process
* if requirement is wrong the system is wrong

	###Requirements Gathering Process
	* determine client needs
	* understand domain
	* formulate business model
	* specify initial requirements
	* MUST REALLY DETERMINE CLIENTS NEEDS
	
	###Requirements Workflow
	* understand application domain 
	* build business model
	* use model to determine clients requirements
	* iterate the above steps

	###Business model 
	* description of the business process of an organization

	###Interviewing
	* formal or informal interviewing
	* ask questions to stakeholders about the system to be developed
	
		#####Types of Questions 
			* Close Ended
			* Open Ended
		####Type of interview 
			* structured - pre-planned
			* unstructured - questions posed after response
	* important no preconcieved notions about the requirements
	* remain open minded

	###Other techniques
	* direct observation
	
##Requirements Management
* process of changing the requirements during engineering process
* Inevitably incompete and inconsistent

	###Principal Stages
	* **Problem analysis** - discuss requirments problem and propose changes
	*  **Change analysis costing** - change on other requirements
	*  **Change implementation** - modify requirements document to reflect a change

	###Review checks
	* **Verifiability** - is it realistically testable
	* **Comprehensibility** - is it properly understood?
	* **Traceability** - is the orgin of the requirement clearly stated? 
	* **Adaptability** - can the requirement be changes without a large effect in the other requirements?

	###Requirements Change
	* the priority of the requirements from different view points change
	* system customers may specify requirments from a business perspective
	* the business may change which will affect the system
	
	###Enduring and Volatile Requirements
	* **Enduring Requirements** - Stable requirements 
	* **Volatile Requirements** - change during development or when the system is in use 

	###Requirements Management Planning 
	* **Requirement identification**			- how requirements are individually itentified
	* **a change management process** - process followed when changing the requirement
	* **Traceablility policie** - amount of information about requirement relationship that is maintained 
	* **CAS tool support**- tools to help manage requirement changes
		*  Ex : Trello

	 
	
