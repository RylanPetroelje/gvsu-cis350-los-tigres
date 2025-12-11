# Overview

The purpose of this document is to outline the software requirements specification (SRS) for Picky Prep. This document defines the systems functional and non-functional requirements to guide development, testing, and evaluation. Picky Prep aims to learn user preferences through simple feedback interactions and generate personalized meals and recommendations based on those preferences

------
# Functional Requirements

1. User Profile Management
   
    1.) The system shall allow users to select whether they like, dislike, are neutral to a food item.

    2.) The system shall record each user's food preference in the database.

    3.) The system shall allow users to update their previous preference at any time.

    4.) The system shall provide at least 50 common food items for initial preference collection.

    5.)The system shall categorize food items as vegan, non-vegan for organization purposes.

2. Meal Recommendation
   
    1.) The system shall create at least 3 personalized meals based on the user preferences

    2.) The system shall exclude any recipes that contain any ingredient the user has disliked.

    3.) The system shall create recipes that focus on the ingredients the user has liked.

    4.) The system shall let the user refresh recommendations to get new options.

    5.) The system shall display the reason why each recommendation was given (ex "Contains chicken")

3. User Profile & Account Management
   
    1.) The system shall allow new users to create an account with their email account.
    
    2.) The system shall allow the users to reset password through email verification.

    3.) The system shall allow dietary restriction (vegan, non-vegan).

    4.) The system shall allow users to select cooking levels.

    5.) The system shall allow users to edit their profile information at any time.
-------
# Non-Functional Requirements

1. Performance
   1. The system shall respond to the user within 2 seconds to ensure user satisfaction.
   
   2. The system shall allow up to 100 concurrent users and maintain efficiency.
   
   3. The system shall record each user's username, password, and preferences in a database.
   
   4. The system shall load the dashboard within 5 seconds.
   
   5. The database shall execute queries to retrieve user preferences in under 5 seconds

2. Security
   1. The system shall encrypt all passwords.
   
   2. The system shall use HTTPS for communication between user and server
   
   3. The system shall not display detailed error messages containing system information.
   4. The system shall validate and prevent SQL injection.
   5. The system shall lockout accounts after 5 failed login attempts within 20 minutes.

3. Usability
   1. The system shall have a simple user interface.
   
   2. The system shall provide clear error messages with suggestion actions when errors occur.
   
   3. The interface shall comply with WCAG 2.1 A standard for accessibility
   
   4. New users shall complete initial preference setup within 10 minutes.
   
   5. The preference selection shall be usable with mouse and keyboard.

----
# Artifacts
1.) [Use Case Diagram](https://github.com/RylanPetroelje/gvsu-cis350-los-tigres/blob/main/artifacts/use_case_diagram.png)




2.)[Class Diagram](https://github.com/RylanPetroelje/gvsu-cis350-los-tigres/blob/3fa71d8d0bb0b77c3d6d03da96bab00a539bf3e2/artifacts/ClassDiagram.png)


3.)[Sequence Diagram](https://github.com/RylanPetroelje/gvsu-cis350-los-tigres/blob/main/artifacts/sequenceDiagram.png)
