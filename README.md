# Team 4: Care Management and Review

## Team Roster
- Christopher Carson, _Product Manager/Business Analyst_
- Matthew Morena, _Data Architect_
- Himanshu Tomar, _UI/UX Development_
- Devansh Guduri, _Quality & Dev Ops_
- Sanjana Kancharla, _Microservices Developer_  

## Product Vision
### Far Vision
1. Create a feature to review the progress of individuals and to make changes in existing progress. 
2. Make a web view which will contain the following:
    * Demographic Information (Travel History, past medical records, family medical conditions). 
    * Recent and Scheduled appointments.
    * Information about case notes, problem list,recent activity.
    * Display progress notes of recent visits with a single click.
3. View different kinds of documents 
4. View for Consumers to see details/information about their prior visits.
5. Add Accessibility for disabled, and user-friendly web applications that reach a wider audience.(voice recognition, Free text option, etc)
6. A Single view which will contain the following:
    * Social and Family health history.
    * Clinical quality management measures.
7. Create a View for viewing or tracking all the donations received from any sources so far.

### Near Vision
1. Designing Database Architecture. Identify Entities, Relations, design a ER Diagram and Normalizing database structure.
2. Environment setup for Frontend and Backend.
3. Implement Micro Frontend architecture for modular, conflict-free frontend development & enhanced collaboration among team members.
4. Establish GitHub best practices for minimal merge conflicts and enhanced security.
5. Implementing Agile Methodologies , CI/CD. CI Service to automate builds and testing on code commits. Configuring CD Service to deploy tested code changes to a staging environment.
6. Coordinating and implementing a similar data schema with other team members so as to have data reliability and consistency.
7. Individual Patients progress notes access.
8. Develop a prototype feature that allows the care Manager to access full progress from recent  visits of a patient with a single click. Care Manager, Nurse should be able to create, read, update and delete the progress details of an individual. This should contain social ,family health history and clinical quality management measures.
9. Unit Testing of the component, Patients progress notes View. It should include Test planning, Test Case Development and Test Execution.

## Stakeholders
Internal | External
--- | ---
Agency Management | Patients
Case Manager | Patients with Special Needs (Accessibility)
Front Office (Receptionist) | Donors
Doctor | Service Providers
Nurse | Software Product Manager
Backoffice (Reporting) | Caregiver

## User Personas

### User Persona for Care Management and Review Stakeholder

**Name:** Emily Davis

**Role:** Case Manager

**Background:**
Emily Davis is an experienced case manager at an Independent Living Center (ILC). She has been in the healthcare industry for over 10 years and is dedicated to helping individuals with disabilities lead independent lives. Emily is responsible for overseeing the care and progress of consumers at the ILC. She plays a vital role in coordinating services, setting goals, and ensuring that consumers receive the support they need to achieve their objectives.

**Goals and Needs:**
* Efficient Progress Monitoring: Emily needs a tool that allows her to quickly review the progress of individual consumers. She wants to see a snapshot of each patient's demographic information, upcoming appointments, case notes, and recent activity to efficiently assess their current status.
* Access to Detailed Records: Emily requires access to detailed progress notes from recent visits. She needs the ability to view these notes easily, including social and family health history, and clinical quality management measures. This access is critical for making informed decisions about consumer care plans.
* Streamlined Documentation: Emily values a system that offers multiple means of documentation, such as point-and-click, free text, and voice recognition. This variety helps her and her team efficiently record information, ensuring comprehensive and accurate consumer records.
* User-Friendly Interface: Emily is not a technical expert, so she needs a user-friendly interface that doesn't require extensive training. A system with an intuitive design would enable her to navigate and use the tool effectively.
* Time Efficiency: As a care manager, Emily has a busy schAs edule. She needs a tool that saves her time and allows her to focus on providing quality care to consumers rather than getting bogged down in administrative tasks.

**Challenges:**
* Complex Consumer Profiles: Managing consumers with various disabilities and unique needs can be challenging. Emily needs a system that can handle the complexity of consumer profiles and adapt to different care requirements.
* Compliance and Reporting: ILCs must meet regulatory requirements. Emily needs a system that can help her ensure compliance and streamline reporting processes.
* Expectations from the System: Emily expects the Care Management and Review system to provide her with a comprehensive view of consumer progress, facilitate efficient documentation, and support her in delivering the best possible care to consumers with disabilities. She values a system that is user-friendly, adaptable, and helps her meet compliance standards effortlessly.

## Product Backlog
### Link
https://www.pivotaltracker.com/n/projects/2678447
### Ordering
The stories were ordered as they were because the databases needed to be set up first which explains the need for developing the entities and ER diagram first. Then the REST APIs need to be set up before any other features can be added to either the front or back end. The progress panel then will be next because the progress panel is the most essential aspect of the case management / review team. We then put an emphasis and priority on the Case Manager before anything appears on the agency manager side dashboard because the case managers need to be able to access and set anything up before assisting patients.
### Defintion of Ready
1. Define Entities, Capture Relationships, and Design ER Diagram
    * As a Data Architect, I want to define the relevant entities and capture their relationships so that I can design an Entity-Relationship (ER) diagram for the system.
    * The ER diagram is complete and accurate, reflecting the entities, attributes, and relationships. The ER diagram is reviewed and validated by relevant stakeholders. Documentation is updated to include the ER diagram. Any feedback or necessary revisions are addressed.
    * 1 Story Point
2. Develop REST API and Connection From Front-End to Back-End
    * As a Microservices Developer, I should be able to share the data stored to other parts of the applications and to streamline the connection between front-end and back-end.
    * All API Functions are complete and usable by other services.
    * Functions are able to access data stored in the database (Create, Read, Update, Delete).
    * API Documentation is available to other services.
    * 3 Story Points
3. Develop Patient Selection Page for Case Manager
   * As a Case Manager, I should be able to view a list of active patients under my care and select one to view and update their progress.
   * Case managers should see a list of their active patients to select from.
   * There should be also be filtering options (alphabebital, most recently viewed, etc.).
   * Upon selecting a patient, the case manager should be redirected to the progress dashboard for the selected patient.
   * 1 Story Point
4. Develop Case Manager Selection Page for Agency Staff
   * As an Agency Manager, I should be able to view a list of active case managers and select one to view their patients.
   * Agency managers should see a list of active case managers to select from.
   * There should be also be filtering options (alphabebital, most recently viewed, etc.).
   * Upon selecting a case manager, the agency manager should be redirected to the patient selection page.
   * 1 Story Point
5. Develop Patient Selection Page for Agency Staff
   * As an Agency Manager, I should be able to view a list of active patient’s under a selected case manager’s care and select one to view their progress.
   * Upon selecting a case manager, the agency manager should be able to select from that case manager's active patients.
   * There should be also be filtering options (alphabebital, most recently viewed, etc.).
   * Upon selecting a patient, the agency manager should be redirected to the progress dashboard for the selected patient.
   * 1 Story Point
6. Develop Progress Panel on User Dashboard
    * As a Case Manager, I should be able to access progress from recent visits of a patient with a single click.
    * It should have a visits panel and have a clear way of accessing progress from patients.
    * All patient progress is stored in the progress panel on the user dashboard.
    * 3 Story Points
7. Develop Progress Details Chart / Case Manager Form on User Dashboard
    * As a Case Manager, I should be able to create, read, update and delete the progress details of an individual.
    * Chart and Form is available on the Case Manager page with fields detailing progress for patients.
    * Case Managers should be able to click on individual patients to bring up progress charts and forms.
    * Fields include: Patient Name, Demographic info, referrals, past visits, upcoming visits, dates, locations and time spent on all individual case management activities.
    * 3 Story Points
8. Develop Prescription Update Form for Case Manager
    * As a Case Manager, I should be able to update prescription information for patients.
    *  The case manager should be able to update a prescriptions name, label# and date and should also be able to view any comments from the patients about their reaction to the drug.
    * 1 Story Point
9. Develop Exit Plan Form for Case Manager
    * As a Case Manager, I should be able to create and update exit plans for patients.
    * Exit plan form is available to the case manager for each individual patient under their care.
    * Case managers should be able to click on a particular patient to bring up their exit plan information.
    * Case manager should be able to update the fields in the form for each patient and submit the form to the database.
    * Fields include: participant objectives and goals, resources such as further referrals or prescriptions
    * Any past exit plan information should be able to be viewed and updated by the case manager.
    * 2 Story Points
10. Create Billing Chart / Table for Case Manager Side
    * As a Case Manager, I should be able to update billing information for patients for their recent visits.
    * The case manager should be able to access the billing chart and update it with the proper amount due, along with a pay by date.
    * 2 Story Points
11. Create Visits Calendar for Agency Staff
    * As an Agency Manager, I should be able to view progress from recent visits and view upcoming visits for a patient.
    * The agenecy manager should have a calendar where they can see every visit in the previous days / months and they can also see upcoming visits for the selected patient.
    * They should also be able to click on the previous visits for any new information and they should be able to click on the future visits for information such as doctor, time, etc.
    * 3 Story Points
12. Develop Prescription View for Agency Staff
    * As an Agency Manager, I should be able to view a patient's prescription information.
    * There should be a prescription chart with the drug’s date, label # and name and expiration date easily accessible to the agency manager.
    * 1 Story Point
13. Develop Exit Plan View for Agency Staff
    * As an Agency Manager, I should be able to view a patient's exit plan information.
    * The agency manager should see an option on their dashboard labeled exit plan information.
    * The agency manager should be able to click on this and access a new view that displays the exit plan information laid out by the case manager.
    * 1 Story Point
14. Create General Account View for Patient Dashboard
    * As an Agency Manager, I should be able to view social, family, health history, and clinical quality management measures for a patient.
    * The patient view dashboard should include a section for a general account view that the agency manager can click on to view more details.
    * When clicked, the agency manager should be redirected to a new panel displaying the following: social, family, health history, and clinical quality management measures.
    * 3 Story Points
15. Create Billing View/Page on Patient Dashboard
    * As an Agency Manager, I should be able to view billing information from recent visits in my dashboard.
    * The agency manager should be able to go to the dashboard and view billing information based on the corresponding dates from the calendar.
    * 2 Story Points

## Relative Size Estimating
We conducted relative size estimating as a team using the three-point method.
