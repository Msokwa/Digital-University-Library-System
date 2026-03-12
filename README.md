# Digital-University-Library-System
Project Overview
The Digital University Library System is a comprehensive, web-based platform designed to modernize academic resource access. By replacing traditional library hurdles with automated processes, the system enables students, faculty, and researchers to search, borrow, and manage digital materials—including books, journals, and research papers—from any location at any time.

Core Features
User Authentication & RBAC: Secure login with Role-Based Access Control for Students, Faculty, and Administrators.
Digital Borrowing System: Automated check-outs, return processing, and automatic due date reminders.
Advanced Search: Efficient information retrieval using filters for titles, authors, or categories.
Content Management: Administrative tools to add, edit, or remove digital resources and categorize materials.
Resource Requesting: Faculty-specific functionality to request new academic additions to the collection.

Development Methodology: The 8-Phases Model
This project follows a standardized 8-Phases Model (Verify - Design - Validate) to ensure systematic tracking and quality.
Phase 1: Project Kickoff: Defining project objectives, scope, and stakeholder roles to establish accountability.
Phase 2: Requirement Gathering and Analysis: Identifying functional and non-functional requirements and documenting them in a Software Requirements Specification (SRS).
Phase 3: System Architecture and Design: Developing architectural diagrams and recording design decisions in a Design Specification Document (DSD).
Phase 4: Development and Implementation: Writing modular code, conducting peer reviews, and utilizing version control systems like Git.
Phase 5: Verification and Testing: Performing unit and integration testing and recording results in a Test Summary Report (TSR).
Phase 6: Validation and User Acceptance Testing: Validating the software against user expectations and preparing a final Validation Report (VR).
Phase 7: Deployment: Preparing deployment scripts, conducting pre-launch checks, and moving the system to production.
Phase 8: Maintenance and Continuous Improvement: Monitoring performance, fixing bugs, and tracking updates in a Maintenance Log.System Design & ArchitectureThe system architecture is documented through several UML models to ensure scalability:Class Diagram: Illustrates the static structure, including the User class, the Student subclass, and the Book and BorrowRecord components .Activity Diagram: Visualizes the flow of actions a user follows when interacting with the system to borrow a book.Sequence Diagram: Captures the real-time interactions and message exchanges between the user, Authentication Service, Book Catalog, and Database.Finite State Diagram: Represents the system's behavior through discrete states such as LoggedOut, SearchingBook, and BorrowConfirmed.

Technical Specifications & Management
Data Structure: The system maintains structured data using three key tables: Users, Books, and BorrowedRecord .
Source Code Management: Utilizes branching strategies, including feature-specific branches for isolated development and release branches for production-ready code .
Commit Standards: Developers follow a standardized commit message convention: <type>(<scope>): <description>.Automation: Incorporates continuous integration/continuous deployment (CI/CD) pipelines and deployment checklists for reliability.Future 
EnhancementsAI-Based Book Recommendations: Implementing machine learning algorithms to suggest materials based on user history.Global Integration: Connecting with external university networks or global digital libraries for inter-library borrowing.
Advanced Security: Enhancing data encryption and implementing multi-factor authentication (MFA).
Project Contributors
Saniya (67168510) 
Abhijith (32777150)
Anibal (27857066) 
Beatrice (38548252)
University: University Europe for Applied Science, Potsdam Date: 19.01.2025
