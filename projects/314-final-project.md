---
layout: project
type: project
image: img/weekend/mascot.png
title: "Software Engineering Final Project"
date: 2024
published: True
labels:
  - HTML
  - CSS
  - Typescript
  - Next.js
  - React
summary: "An application I worked on for my ICS 314 Final Project."
---

<!-- <link rel="stylesheet" href="style.css"> -->

<div style="display: flex; justify-content: center; align-items: center; height: 100%; padding: 20px;">
  <img src="https://nwarias003.github.io/img/weekend/WWLogo1.png" style="width: 300px; height: auto; box-shadow: 0px 10px 15px rgba(0, 0, 0, 0.5); border-radius: 8px;" alt="Application Logo">
</div>

## Table of contents

- [Overview](#overview)
- [Project Goals](#project-goals)
- [Technologies Used](#technologies-used)
- [Group Contract](#group-contract)
- [GitHub Organization ](#github-organization)
- [Web Application](#web-application)
- [Project Contributions](#project-contributions)
- [Lessons Learned](#lessons-learned)
- [User Guide](#user-guide)


## Overview
Many UH Manoa students and locals have a hard time finding people with similar interests to join them in outdoor activities and hobbies. Whether it’s hiking, beach outings, surfing, or just hanging out, it’s not always easy to find partners or groups that align with specific plans or schedules.

Weekend Warrior is a platform that allows users to post their upcoming weekend plans or desired activities and connect with others interested in joining them. This app would serve as a local meetup spot for casual and activity-based connections. It will also make it easier to find activity buddies and plan for fun weekends.

## Project Goals

- Users can create or find activities to join.
- Admins ensure content safety and platform use.

## Technologies Used
- Frontend: Typescript, Bootstrap, React, Next.js
- Backend: Node.js, Prisma ORM
- Database: PostgreSQL
- Deployment: Vercel
- Version Control: GitHub

## Group Contract
Click <a href="https://docs.google.com/document/d/11WCz0wKi_EQwpVjwTQwwox7MkSHgHivBXGg_-en4Drg/edit?usp=sharing">here</a> to view our group contract.

## GitHub Organization 
Click <a href="https://github.com/weekend-warrior-uhm">here</a> to view the Weekend Warrior project repository.

## Web Application 
Click <a href="https://weekend-warrior-code-sigma.vercel.app">here</a> to view Weekend Warrior deployed on Vercel.

## Project Contributions

I contributed significantly to the Weekend Warrior project across several key areas. My primary responsibility was developing and finalizing the documentation page, and ensuring it provided clear, comprehensive and user-friendly information about the project. This involved structuring sections for features, usage instructions and visuals. Plus, ensuring consistency and clarity to effectively communicate the app's purpose and functionality. The documentation highlights key features, such as activity posting, user registration and admin controls. In addition, it includes a detailed user guide supported by screenshots to enhance usability. 

I also set up GitHub Actions for continuous integration to automate testing and linting processes. This streamlined the development workflow, maintained code quality and ensured a stable and efficient development process. 

Furthermore, I contributed to the design and implementation of the application, focusing on creating a seamless and visually appealing user experience while prioritizing user safety. My efforts included helping to develop the landing, activities listing and user profile pages while integrating responsive design principles using Next.js and React. In addition, I focused on user safety by ensuring that suspicious individuals would not have easy access to users' personal information, which was a critical consideration in the application's design.

Beyond technical contributions, I played a key role in milestone validation, ensuring the project met all specified requirements. By reviewing progress and verifying deliverables, I helped the team stay aligned with project goals. These efforts underscored the importance of meeting project expectations and delivering a high-quality final product.

Overall, my contributions to the project demonstrated a balance between technical expertise, user-centered design and a commitment to fulfilling project milestones, ensuring the success of the Weekend Warrior application.

## Lessons Learned

This project provided me with invaluable lessons in both technical and non-technical aspects of software development. On the technical side, I gained hands-on experience with:

- Next.js Framework: Deepened my understanding of server-side rendering and API integration within the Next.js ecosystem.

- Prisma ORM: Learned to configure and use Prisma for seamless database interactions, including schema migrations and seeding.

- Continuous Integration: Gained insight into setting up and maintaining CI pipelines using GitHub Actions to ensure a stable and efficient development workflow.

- Documentation Skills: Learned how to structure and create detailed documentation that is accessible to both users and developers, bridging the gap between technical complexity and usability.

- Milestone Validation: Gained experience in tracking project requirements and verifying deliverables to ensure alignment with goals.

On the non-technical side, I learned the importance of:

- Effective Communication: Collaborating with a team required clear and frequent communication to resolve blockers and ensure alignment on project goals.

- Time Management: Balancing individual tasks with team responsibilities taught me to prioritize and manage time effectively.

- Issue-Driven Project Management: Adhering to this methodology emphasized the value of breaking down complex tasks into manageable issues, which improved overall productivity.

## User Guide:

### Landing Page

When you first bring up the application, you will see the landing page that provides a brief introduction to Weekend Warrior:

<img src="https://nwarias003.github.io/img/weekend/updated_home_1.png" style=" width: 768px; height: auto; box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.4); border-radius: 4px;" alt="Landing Page Screenshot">
 
### Register
If you do not yet have an account on the system, you can register by clicking on “Login,” then “Sign Up.” On the Sign Up page, users can create an account by providing their email, a username, password (with confirmation), full name, phone number, gender, and interests. The interests field allows users to input activities or hobbies, separated by commas, that help personalize their profile. After filling out the form, users can click the Register button to submit their information or the Reset button to clear the form:

<img src="https://nwarias003.github.io/img/weekend/updated_signup.png" style="box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.4); border-radius: 4px;" alt="Register Page Screenshot">


### Sign in
Click on the Login link to bring up the Sign In page which allows you to log in:

<img src="https://nwarias003.github.io/img/weekend/updated_signin.png" style="box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.4); border-radius: 4px;" alt="Sign In Page Screenshot">

### Edit User Information
In order to change your account's information, click on your email in the top-right corner of the navigation bar and select "Edit Info". This will bring up the Edit User Information page, where you can update your account details, including email, username, full name, phone number, gender, and interests. Once you've made your desired changes, click Save Changes to update your information or Reset to clear the form fields:

<img src="https://nwarias003.github.io/img/weekend/edit_info.png" style="box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.4); border-radius: 4px;" alt="List Contacts Page Screenshot">


### User home page
After successfully logging in, the system takes you to your home page. It is just like the landing page, but the NavBar contains links to Activities and Users:

<img src="https://nwarias003.github.io/img/weekend/updated_signin_notadmin_1.png" style="box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.4); border-radius: 4px;" alt="User Home Page Screenshot">


### List Activities 
Clicking on the Activities link brings up a page that lists all activities posted by users, along with each activity's description, location, scheduled time, and the total number of registered participants. Users have the option to Sign Up for activities they are interested in, Unregister from activities they have previously joined, or Report activities if necessary. Additionally, creators of an activity are provided options to Edit/Delete their own activity. At the top of the page, users can click on the Create Activity button to add a new activity to the list:

<img src="https://nwarias003.github.io/img/weekend/updated_activities_2.png" style="box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.4); border-radius: 4px;" alt="List Contacts Page Screenshot">

### Report Activity
When users click the Report button on an activity card, a Report Activity form appears in a modal window. The form is pre-filled with the Activity Name and the Activity Creator for convenience. Users are required to provide a brief message describing the issue in the Report field, with a maximum limit of 500 characters. After typing their report, users can submit it by clicking Submit Report or close the form without submitting by clicking the Close button. This streamlined process ensures that users can quickly and efficiently report any concerns related to activities:

<img src="https://nwarias003.github.io/img/weekend/report_activity.png" style="box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.4); border-radius: 4px;" alt="List Contacts Page Screenshot">

### List Users
Clicking on the Users link brings up a page that lists all users in the system. Each user is displayed in a card format that includes their gender, interests, and role (e.g., USER or ADMIN). This page provides an overview of the user base while keeping personal details, such as email, full name, and phone number, hidden for privacy:

<img src="https://nwarias003.github.io/img/weekend/updated_users_2.png" style="box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.4); border-radius: 4px;" alt="List Contacts Page Screenshot">

### Registered Activities
Clicking on the Registered Activities link displays a page that lists all activities you have signed up for. Each activity is presented in a card format, showing its description, location, date, time, duration, activity owner, and the total number of registered users. You can choose to Unregister from an activity, view additional details by clicking "Activity Info", or "Report" an activity if necessary:

<img src="https://nwarias003.github.io/img/weekend/registered_activities.png" style="box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.4); border-radius: 4px;" alt="List Contacts Page Screenshot">

### Owned Activities
Clicking on the Owned Activities link displays a page that lists all activities you have created. Each activity is shown in a card format with its description, location, date, time, duration, and total number of registered users. As the creator, you have the option to Edit/Delete the activity, view additional details by clicking Activity Info, or Unregister if needed:

<img src="https://nwarias003.github.io/img/weekend/owned_activities.png" style="box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.4); border-radius: 4px;" alt="List Contacts Page Screenshot">

### Edit Activity
Clicking on the Edit/Delete button for an activity brings up the Edit Activity page, where activity creators can modify the details of their activity. This page allows users to update the activity name, description, location, date, time, duration, and a message for registered participants. Once changes are made, users can click Submit to save updates, Reset to clear changes, or Delete Activity to permanently remove the activity:

<img src="https://nwarias003.github.io/img/weekend/edit_activity.png" style="box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.4); border-radius: 4px;" alt="List Contacts Page Screenshot">


### Activity Info
Clicking on the Activity Info button displays a detailed view of the selected activity. This page provides additional information, including a welcome message, the list of registered users, and a contact link to the activity organizer for any inquiries. The activity owner can post a message for participants and provide follow-up updates, which are visible only to registered users:

<img src="https://nwarias003.github.io/img/weekend/activity_info.png" style="box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.4); border-radius: 4px;" alt="List Contacts Page Screenshot">

### Admin mode
It is possible to designate one or more users as “Admins” through the settings file. When a user has the Admin role, they gain access to a special Admin Panel, which can be found by clicking on their email in the top-right corner of the navigation bar and selecting "Admin" from the dropdown menu. This page displays two main sections: Activities and Users. The Activities section lists all currently created activities with details, including the name, description, location, date, time, duration, owner, registered users, and any messages associated with the activity. Admins can edit each activity by clicking the "Edit" link in the corresponding row. The Users section provides a table with user-specific information, such as email, username, full name, phone number, gender, interests, and role, allowing Admins to view all users in the system:

<img src="https://nwarias003.github.io/img/weekend/updated_admin_3.png" style="box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.4); border-radius: 4px;" alt="Admin Page Screenshot 1">

Admins are also able to edit and delete all the currently listed activities:

<img src="https://nwarias003.github.io/img/weekend/admin_activities_2.png" style="box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.4); border-radius: 4px;" alt="Admin Page Screenshot 1">

In addition, Admins can access the Report Panel by clicking on their email in the top-right corner of the navigation bar and selecting "Reports" from the dropdown menu. This page displays a table of all activity reports submitted by users. Each report entry includes the ID, Activity ID, Activity Name, Activity Author, and Report Text, which contains details about the issue provided by the user. This panel allows Admins to efficiently review reported activities, investigate user concerns, and take appropriate actions to resolve issues within the system:

<img src="https://nwarias003.github.io/img/weekend/admin_report_panel.png" style="box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.4); border-radius: 4px;" alt="Admin Page Screenshot 1">


### Contact & Support
Clicking on the Contact & Support link in the footer opens a page with helpful resources for users needing assistance. The page includes a “Contact Us” section that provides an email address and phone number for support inquiries. It also features a comprehensive FAQ section addressing common questions about account creation, activity participation, managing activities, and reporting issues. Additionally, the page offers links to essential resources, including the Community Guidelines, Privacy Policy, and Terms of Service, ensuring a safe and informed user experience:

<img src="https://nwarias003.github.io/img/weekend/updated_contact_support.png" style="box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.4); border-radius: 4px;" alt="Admin Page Screenshot 1">

### Safety Reminders
Clicking on the Safety Reminders link in the footer brings up a page that provides essential safety guidelines for users. The page includes General Safety Tips, such as meeting in public places, informing someone about your plans, and trusting your instincts if you feel uncomfortable. It also offers Activity-Specific Tips with advice for hiking, water activities, and cycling to ensure users stay safe during their activities. Additionally, the Emergency Preparedness section emphasizes the importance of planning ahead, carrying essential items like a first aid kit, and staying informed about weather updates and local advisories. For further details, the page includes links to the Community Guidelines, Privacy Policy, and Terms of Service to help users stay informed and protected:

<img src="https://nwarias003.github.io/img/weekend/updated_safety_reminders.png" style="box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.4); border-radius: 4px;" alt="Admin Page Screenshot 1">


