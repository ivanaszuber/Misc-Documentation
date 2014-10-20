1. Tracking and Control Mechanisms

The quality of the final product, in our case the OMS application, is perhaps the most relevant factor that

determines whether the project was successfully completed or not. The project manager is the only person who is

directly responsible for the success of the project, and since that success is directly related to the quality of

software, we may conclude that there is a strong link between software quality and the project manager.

According to Juran (n.d.), it is absolutely necessary that the highest level of the organization’s management be

willing to implement quality, because from them the quality moves towards the lower levels of management, and

finally towards developers. That being said, we may constitute that the OMS project should have no obstacles in

fully adhering to high-quality.

The information on the desired level of quality will be obtained from the client, and the project manager will be in

charge of communicating that information to other members of the project team. When everyone fully

understands and work towards developing a high-quality software, then the project manager has promoted the

quality in the appropriate way.

In that regards, the following section of the OMS project plan contains a detailed description of quality assurance

planning, implementation and controlling techniques that will be used in the OMS project.


1.1. Quality assurance and control

Quality assurance system is a mechanism that applies the principles of quality management in the organization.

The system involves activities that have an impact on the quality of the end product, including the organizational

structure, procedures, responsibilities, resources, and processes required to implement quality management. We

can categorize these activities into quality planning, assurance, and control, as described in the following sub-

sections.

1.1.1. Quality planning

Software quality planning is the initial activity in the quality management process in which the project manager

identifies the quality standards that are relevant for the project. Identified quality standards derive from existing

international standards, as well as direct and indirect user requirements. Unlike other project activities, quality

planning involves the most intensive communication with the customer, due to the fact that it is necessary to

clearly and unambiguously define the desired level of software quality in an understandable and final form. The

documents that arise from the planning process need to describe what factors or processes, methods, and tools

will impact the establishment of the desired level of quality (Schwalbe, 2006: 295). The basic documents include

the quality management plan and the quality checklist used by the project team to focus on the most important

activities in the course of the project.

Our organization adheres to ISO 9126 standards in the software development, therefore the OMS system will be

developed and implemented in accordance with these standards. The ISO 9126 standard defines specified

software characteristics, as well as the process of evaluating software quality (Abran, 2003). According to these

standards, there are six general characteristics of quality software: Functionality (the existence of software

functions or their designated properties), Reliability (ability of the software to maintain the level of performance

under defined conditions, during the specified period), Usability (sustainability for use, or complexity for the end

user), Efficiency (the relationship between the level of performance of the software and the amount of resources

that are used under named conditions), Sustainability (the ability of the software to easily support future

modifications), Portability (the ability of software to be transferred from one workplace to another).


In addition to named software characteristics, the OMS system will have to fully adhere to the defined user

requirements. The user requirement specification will be developed as a separate document and delivered to all

members of the team. The document will be fully evaluated and discussed on the initial team meeting, and

appropriate evaluation, verification and testing of these requirements will be done by the project manager and the

testing team thought the life cycle of the project.

The complete list of quality standards, policies, tools and methods which will be used in the OMS project will be

specified in the OMS project SQA plan. The SQA plan will be delivered as a separate document, together with the

specification requirements document, and discussed on the team meeting. It is the responsibility of the project

manager to explain and emphasize the importance of these documents and adherence to the requirements,

standards, and policies contained within them.

1.1.2. Quality assurance

After defining the quality management plan, the project manager has the responsibility of ensuring that his team

follows the quality specification. This phase is called quality assurance, and its main functions are to ensure the

monitoring of quality standards and continuous improvement of the quality.

The process of quality assurance in the OMS project can be structured as follows:

- The project manager is in charge of daily reviewing and reporting the project quality status (Project

manager will conduct daily project measurements in order to develop a repository of performance data

and generate software quality assurance reports for the stakeholders and senior management).

- The project testing team is in charge of continuously conducting integration and system testing and

reporting errors or deviations from defined quality standards and/or user requirements (as outlined in

section 6.1.3.)

- The development team is in charge of fully adhering to the Test Driven Development principles and

developing unit tests for all application logic

- The documentation team is in charge of continuously developing the user documentation, translating the

localization files, and ensuring that all newly implemented application strings are fully lectured


One of the most important tools for ensuring the quality is audit. Quality audit, as explained by Galin (2004),

implies a structured review of all activities in the field of quality management and proposed amendments to

standards, procedures and practices, in order to improve the quality and performance of the project team. In that

regard, after the completion of each project phase (design, development and implementation) a formal quality

audit will be conducted in order to benchmark the defined quality standards against the developed quality of the

OMS system. Any deviations found during the audit will be reported back to the project manager, and the final

report signed by the OMS steering committee. Recommendations on quality improvements that result from PM’s

daily reviews and quality audits will be discussed on team meetings and infiltrated into the project plan and

development iterations. In addition, all errors, deviations and recommendations will be documented and uploaded

to our Team Foundation Server (together with the rest of the project documentation) in order to provide a

‘Lessons Learned’ resource for future projects.


1.1.3. Quality control

The process of software quality control involves detection of errors that may occur in the processing of user

requirements, analysis, design and implementation. Given that the results can be positive and negative, there are

three basic outcomes of quality control (Schwalbe, 2006: 299):

1. Acceptance decisions – which determine whether the product is acceptable of not

2. Rework – activity that occurs in case the product or an element of the product is not accepted (due to

non-compliance with quality standards or business requirements)

3. Process adjustments – correction or prevention of future problems in the quality of the product, based on

measurements done during the quality control

The most significant part of OMS project quality control will be dedicated to software testing, whose main purpose

is the assurance of software quality through detection of errors. As Kaner et.al (2002) claims, there are two main

goals of the testing process: detection of errors and creation of confidence in the level of software quality.

Schwalbe (2006: 313) separates the process of software testing in several categories: unit testing (in which

developers ensure that a certain part of the program code or element does not contain any critical errors),

integration testing (in which developers ensure that the main software components (modules) do not contain any

critical errors), system testing (where development team leaders test the software as a whole (system) and ensure

that as the final product does not contain any critical errors), acceptance testing (related to the business

requirements, allowing project managers to ensure that the final product conforms to all, or most of the business

requirements).


Most of the testing in the OMS project will be done by developers, who will be responsible for objectively

evaluating the quality of the software. The level of quality that is expected form the software evolves through the

life time of the project development, therefore the testing needs to evolve with it. The project manager will

perform the smallest, but the most important part of testing, which ensures that the product is in accordance with

the defined project requirements.

One of the problems that is solved by continuous testing is the reduction of error elimination costs. As explained

by McConnell (1997), errors are most simply and economically corrected in the same phase as they occur.

However, the use of testing is not enough to guarantee software quality, and is therefore used in combination with

the processes for ensuring software quality, outlined in the previous section. Graham (2006) and Mihnea (2008:

241 -253) confirm this through well-accepted principles of software testing:

- Testing shows the existence of errors, and not their absence

- Testing of all software components is impossible or unprofitable

- Testing should be done early in the software development process

- Testing must evolve with the software

- Testing is done in different ways, depending on the type of software

In addition to named quality control aspects, it is important to outline the relationship between the desired level

of quality and the costs related to achieving this quality. Software development tends towards zero-defect quality,

however, in practice, a logical and practical attitude must be created. Testing of all software modules and the

desire to eliminate every significant error can disrupt the balance of the project and take the ROI index towards a

negative area.


1.1.4. Quality metrics

In order to objectively evaluate software quality and control the quality implementation process, it is necessary to

measure software and project characteristics using predefined metrics. In that regard, the first obligation of

software measurement activity is to determine the entities and attributes of interest that we want to measure. For

software, there are three classes of entities whose attributes should be measured: Processes (that relate to the

activities of software development and include the time factor), Products (results of the processes), Resources

(process inputs). In addition, we can distinguish two types of attributes: Internal (attributes that can be measured

according to their relationship with their environment), and External (attributes that can be measured from the

processes, products, or resources).

Table 10 shows the processes, products and resources that will be evaluated and measured in the OMS project.

Some of the metrics used to measure the named attributes will involve LOC (Lines of code), function points, Mean

Time before Failure (MTBF), Scrum velocity, Work item effort, etc. The complete list of the metrics and techniques

used in the OMS project quality control will be outlined in the SQA plan.

Based on these metrics and the use of Seven Basic Tools of Quality (Cause and effect diagrams, Control charts, Run

Charts, Scatter diagrams, Histograms, Pareto charts, and Flowcharts) (Schwalbe, 2013), the project manager will

conduct continuous evaluation and control of the OMS system quality, discuss the findings with the project team

on each Sprint meeting, include the recommended improvements in the project plan and subsequent iterations,

and report the process to the steering committee. In addition, the SQA audit will perform their quality evaluations

after each major project life cycle phase. This will ensure that the appropriate level of software quality is

implemented in all phases of the development, in addition to the rigorous testing done by the developers, the

integration testing team and the project manager himself.



1.2. Change management and control

1.2.1. Software Configuration Management

Software Configuration Management (SCM) is the process which monitors all configuration entities of the system.

The full SCM plan will be delivered as a separate document. The following section provides only a brief description

of the SCM activities and definitions used in the OMS project.

The SCM process involves creating a list of system entities, defining relationships between them, monitoring each

entity during its lifecycle, tracking all change requests, and verifying and insuring the correctness of the defined list

of entities. As a part of this process it is possible to define five basic activities: Planning (development of detailed

plans for configuration management which contains strategies, policies, goals, roles, responsibilities, activities and

procedures), Entity identification (selection, identification and labeling of all configuration entities), Control

(ensuring that only the identified configuration entities get accepted or rejected from the system), Monitoring

(making regular reports on all current and past data related to configuration entities throughout their life cycle),

and Verification (verification of physical existence of the configuration entity, adherence to the Central

Management Database, and existence of proper documentation) (Galin, 2004).


1.2.2. Software Change Management

The purpose of change management is to define standard methods and procedures that will be used in order to

efficiently and promptly handle all changes. In this way, we will minimize the impact of security incidents which are

caused by changes, in order to improve the daily operations within the organization. System entities which may be

subject to change include hardware, software, documentation and procedures associated with the system.

Every change, or request for change, has to be approved through the change management process. The body

responsible for change management decisions is the Change Advisory Board (CAB) (Galin, 2004) composed out of

the OMS Project Steering Committee members. The main activities involved in the change management process

include: filtering change requests, managing change, auditing and closing RFCs (Requests for Change), and

reporting to management. Filtering change requests is a very important activity, since the implementation of the

desired or requested change is usually not beneficial. CAB should approve only those changes that are necessary

for normal functioning of the system or ensuring the system’s promotion in accordance with the organizational

strategy.

The following section provides detailed description of the change management activities that will be taken in the

OMS project.

Communication

Before implementing requested changes it is necessary to communicate the intentions that accompany them.

Communication should cover all implementing changes, their associated risks, and everyone involved in their

execution. Simply put, it is necessary to communicate with both the users and the project team. Communication is

considered a key to success in performing changes, as it identifies potential conflicts and avoids confusion within

the system. Communication will allow the user to understand the efforts that need to be taken in order to

maintain efficient infrastructure, and help him feel as a part of the change management team.