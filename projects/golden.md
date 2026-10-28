---
layout: project
type: project
image: img/weekend/mascot.png
title: "Golden Eagle VR Data Visualization Experience"
date: 2026
published: False
labels:
  - Unity
  - Blender
  - C#
  - 3D Animation
  - VR Development
  - GitHub
  - Cesium
summary: "A virtual reality data visualization project I worked on for my ICS 496 Capstone Project that brings GPS-tracked Golden Eagle flight data to life."
---

<!-- <link rel="stylesheet" href="style.css"> -->

<div style="display: flex; justify-content: center; align-items: center; height: 100%; padding: 20px;">
  <img src="https://nwarias003.github.io/img/weekend/WWLogo1.png" style="width: 400px; height: auto; box-shadow: 0px 10px 15px rgba(0, 0, 0, 0.5); border-radius: 8px;" alt="Application Logo">
</div>

## Table of contents

- [Overview](#overview)
- [Project Goals](#project-goals)
- [Technologies Used](#technologies-used)
- [Documentation](#documentation)
- [Project Contributions](#project-contributions)
- [3D Model and Weight Painting](#3d-model-and-weight-painting)
- [Flight Animation and Animation Tree](#flight-animation-and-animation-tree)
- [Lessons Learned](#lessons-learned)
- [Project Gallery](#project-gallery)
- [Project Resources](#project-resources)


## Overview
A virtual reality (VR) experience representing the flight of migrating juvenile Golden Eagles. Using Unity and GPS tracking data collected by University of Wyoming (UWO) ecologists, we have integrated it into a VR data visualization experience for those same researchers. Bridging the gap between raw data and the real world, researchers are able to re-live and experience flying alongside the eagle, thus enabling insights not possible before with simpler data visualization techniques.

## Project Goals

- Visualize real-world Golden Eagle migration data in an immersive 3D environment.
- Represent recorded flight paths using geographic data.
- Develop a 3D Golden Eagle model capable of realistic flight animation.
- Connect the eagle's animations to its recorded flight behavior.
- Provide researchers with an alternative way to explore and understand eagle migration data.

## Technologies Used
- Unity: VR environment, animation integration and real-time visualization.
- Blender: 3D model preparation, weight painting and flight animation.
- C#: Scripting and integration within the Unity project.
- Cesium: Geographic visualization of real-world coordinates.
- GitHub: Version control and team collaboration.
- GPS Tracking Data: Recorded eagle flight data used in the visualization.


## Documentation 
Click <a href="https://drive.google.com/drive/folders/1DBwkojOSYPcGsmRUpERf2d5wzzO058-t?usp=sharing">here</a> to view the Golden Eagle documentation/milestone slideshows.

## Project Contributions

My primary contributions to the Golden Eagle VR Data Visualization Experience focused on 3D model preparation, weight painting, flight animation, and animation integration in Unity. I collaborated with my girlfriend, Ranae Hunter, on the weight painting and animation work, helping prepare the Golden Eagle model and bring its flight behaviors to life.

### 1. 3D Model Weight Painting

I worked on weight painting the Golden Eagle model in Blender to improve how its mesh deformed when controlled by the rig. This involved refining vertex weights across the beak, tongue, body, head, neck, wings, and feet.

Weight painting was an important step in preparing the model for animation, helping its body parts deform more naturally during different flight movements.

### 2. Flight Animation Development

I then worked on creating and refining the Golden Eagle's flight animations in Blender. These animations represented several flight behaviors needed for the VR experience:

- **Flapping:** Wing movements representing active flight.
- **Gliding:** A flight state with the wings extended.
- **Burst Flapping:** A sequence combining flapping and gliding.
- **Ascending and Descending:** Animations representing increases and decreases in altitude.
- **Turning:** Animation for directional changes during flight.

These animations provided the eagle with different flight behaviors that could be integrated into the larger VR experience.

### 3. Unity Model Integration

I successfully ported the updated Golden Eagle model and its animations into Unity. This involved bringing the prepared model into the project and integrating its animation assets into the existing environment.

### 4. Animation Tree and State Transitions

I configured the Unity animation tree and established transitions between the different animation states. This organized the completed animations into a system that could transition between flapping, gliding, burst flapping, altitude changes, and turning.

The animation tree helped connect the individual animations into a unified system for the eagle's flight behaviors.

### 5. Animation Refinement and Visual Polish

During development, I worked on refining the animation tree and addressing visual issues with the model's wing texture in Unity. These adjustments helped improve the consistency and visual presentation of the animated eagle.

Through these contributions, I helped integrate the Golden Eagle's 3D model and flight animations into the larger VR data visualization experience.


## Lessons Learned

Working on this project helped me to learn invaluable lessons in both technical and non-technical aspects of software development. On the technical side, I gained hands-on experience with:

- Next.js Framework: Deepened my understanding of server-side rendering and API integration within the Next.js ecosystem.

- Prisma ORM:  Learned to configure and use Prisma for seamless database interactions, including schema migrations and seeding.

- Continuous Integration: Gained insight into setting up and maintaining CI pipelines using GitHub Actions to ensure a stable and efficient development workflow.

- Documentation Skills: Learned how to structure and create detailed documentation accessible to both users and developers, bridging the gap between technical complexity and usability.

- Milestone Validation: Gained experience in tracking project requirements and verifying deliverables to ensure goals were aligned and met.

On the non-technical side, I learned the importance of:

- Effective Communication: Collaborating with a team required clear and frequent communication to resolve blockers and ensure project goals were aligned and met.

- Time Management: Balancing individual tasks with team responsibilities taught me to prioritize and manage time effectively.

- Issue-Driven Project Management: Adhering to this methodology emphasized the value of breaking down complex tasks into manageable issues, which helped to improve overall productivity.

## User Guide:

### Landing Page

When you first bring up the application, you will see the landing page that provides a brief introduction to Weekend Warrior:

<img src="https://nwarias003.github.io/img/weekend/updated_home_1.png" style="width: 768px; height: auto; box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.4); border-radius: 4px;" alt="Landing Page Screenshot">
 
### Register
If you do not yet have an account on the system, you can register by clicking on “Login,” then “Sign Up.” On the Sign Up page, users can create an account by providing their email, a username, password (with confirmation), full name, phone number, gender, and interests. The interests field allows users to input activities or hobbies, separated by commas, that help personalize their profile. After filling out the form, users can click the Register button to submit their information or the Reset button to clear the form:

<img src="https://nwarias003.github.io/img/weekend/updated_signup.png" style="width: 768px; height: auto; box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.4); border-radius: 4px;" alt="Register Page Screenshot">


### Sign in
Click on the Login link to bring up the Sign In page which allows you to log in:

<img src="https://nwarias003.github.io/img/weekend/updated_signin.png" style="width: 768px; height: auto; box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.4); border-radius: 4px;" alt="Sign In Page Screenshot">

### Edit User Information
In order to change your account's information, click on your email in the top-right corner of the navigation bar and select "Edit Info". This will bring up the Edit User Information page, where you can update your account details, including email, username, full name, phone number, gender, and interests. Once you've made your desired changes, click Save Changes to update your information or Reset to clear the form fields:

<img src="https://nwarias003.github.io/img/weekend/edit_info.png" style="width: 768px; height: auto; box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.4); border-radius: 4px;" alt="List Contacts Page Screenshot">


### User home page
After successfully logging in, the system takes you to your home page. It is just like the landing page, but the NavBar contains links to Activities and Users:

<img src="https://nwarias003.github.io/img/weekend/updated_signin_notadmin_1.png" style="width: 768px; height: auto; box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.4); border-radius: 4px;" alt="User Home Page Screenshot">


### List Activities 
Clicking on the Activities link brings up a page that lists all activities posted by users, along with each activity's description, location, scheduled time, and the total number of registered participants. Users have the option to Sign Up for activities they are interested in, Unregister from activities they have previously joined, or Report activities if necessary. Additionally, creators of an activity are provided options to Edit/Delete their own activity. At the top of the page, users can click on the Create Activity button to add a new activity to the list:

<img src="https://nwarias003.github.io/img/weekend/updated_activities_2.png" style="width: 768px; height: auto; box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.4); border-radius: 4px;" alt="List Contacts Page Screenshot">

### Report Activity
When users click the Report button on an activity card, a Report Activity form appears in a modal window. The form is pre-filled with the Activity Name and the Activity Creator for convenience. Users are required to provide a brief message describing the issue in the Report field, with a maximum limit of 500 characters. After typing their report, users can submit it by clicking Submit Report or close the form without submitting by clicking the Close button. This streamlined process ensures that users can quickly and efficiently report any concerns related to activities:

<img src="https://nwarias003.github.io/img/weekend/report_activity.png" style="width: 768px; height: auto; box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.4); border-radius: 4px;" alt="List Contacts Page Screenshot">

### List Users
Clicking on the Users link brings up a page that lists all users in the system. Each user is displayed in a card format that includes their gender, interests, and role (e.g., USER or ADMIN). This page provides an overview of the user base while keeping personal details, such as email, full name, and phone number, hidden for privacy:

<img src="https://nwarias003.github.io/img/weekend/updated_users_2.png" style="width: 768px; height: auto; box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.4); border-radius: 4px;" alt="List Contacts Page Screenshot">

### Registered Activities
Clicking on the Registered Activities link displays a page that lists all activities you have signed up for. Each activity is presented in a card format, showing its description, location, date, time, duration, activity owner, and the total number of registered users. You can choose to Unregister from an activity, view additional details by clicking "Activity Info", or "Report" an activity if necessary:

<img src="https://nwarias003.github.io/img/weekend/registered_activities.png" style="width: 768px; height: auto; box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.4); border-radius: 4px;" alt="List Contacts Page Screenshot">

### Owned Activities
Clicking on the Owned Activities link displays a page that lists all activities you have created. Each activity is shown in a card format with its description, location, date, time, duration, and total number of registered users. As the creator, you have the option to Edit/Delete the activity, view additional details by clicking Activity Info, or Unregister if needed:

<img src="https://nwarias003.github.io/img/weekend/owned_activities.png" style="width: 768px; height: auto; box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.4); border-radius: 4px;" alt="List Contacts Page Screenshot">

### Edit Activity
Clicking on the Edit/Delete button for an activity brings up the Edit Activity page, where activity creators can modify the details of their activity. This page allows users to update the activity name, description, location, date, time, duration, and a message for registered participants. Once changes are made, users can click Submit to save updates, Reset to clear changes, or Delete Activity to permanently remove the activity:

<img src="https://nwarias003.github.io/img/weekend/edit_activity.png" style="width: 768px; height: auto; box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.4); border-radius: 4px;" alt="List Contacts Page Screenshot">


### Activity Info
Clicking on the Activity Info button displays a detailed view of the selected activity. This page provides additional information, including a welcome message, the list of registered users, and a contact link to the activity organizer for any inquiries. The activity owner can post a message for participants and provide follow-up updates, which are visible only to registered users:

<img src="https://nwarias003.github.io/img/weekend/activity_info.png" style="width: 768px; height: auto; box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.4); border-radius: 4px;" alt="List Contacts Page Screenshot">

### Admin mode
It is possible to designate one or more users as “Admins” through the settings file. When a user has the Admin role, they gain access to a special Admin Panel, which can be found by clicking on their email in the top-right corner of the navigation bar and selecting "Admin" from the dropdown menu. This page displays two main sections: Activities and Users. The Activities section lists all currently created activities with details, including the name, description, location, date, time, duration, owner, registered users, and any messages associated with the activity. Admins can edit each activity by clicking the "Edit" link in the corresponding row. The Users section provides a table with user-specific information, such as email, username, full name, phone number, gender, interests, and role, allowing Admins to view all users in the system:

<img src="https://nwarias003.github.io/img/weekend/updated_admin_3.png" style="width: 768px; height: auto; box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.4); border-radius: 4px;" alt="Admin Page Screenshot 1">

Admins are also able to edit and delete all the currently listed activities:

<img src="https://nwarias003.github.io/img/weekend/admin_activities_2.png" style="width: 768px; height: auto; box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.4); border-radius: 4px;" alt="Admin Page Screenshot 1">

In addition, Admins can access the Report Panel by clicking on their email in the top-right corner of the navigation bar and selecting "Reports" from the dropdown menu. This page displays a table of all activity reports submitted by users. Each report entry includes the ID, Activity ID, Activity Name, Activity Author, and Report Text, which contains details about the issue provided by the user. This panel allows Admins to efficiently review reported activities, investigate user concerns, and take appropriate actions to resolve issues within the system:

<img src="https://nwarias003.github.io/img/weekend/admin_report_panel.png" style="width: 768px; height: auto; box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.4); border-radius: 4px;" alt="Admin Page Screenshot 1">


### Contact & Support
Clicking on the Contact & Support link in the footer opens a page with helpful resources for users needing assistance. The page includes a “Contact Us” section that provides an email address and phone number for support inquiries. It also features a comprehensive FAQ section addressing common questions about account creation, activity participation, managing activities, and reporting issues. Additionally, the page offers links to essential resources, including the Community Guidelines, Privacy Policy, and Terms of Service, ensuring a safe and informed user experience:

<img src="https://nwarias003.github.io/img/weekend/updated_contact_support.png" style="width: 768px; height: auto; box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.4); border-radius: 4px;" alt="Admin Page Screenshot 1">

### Safety Reminders
Clicking on the Safety Reminders link in the footer brings up a page that provides essential safety guidelines for users. The page includes General Safety Tips, such as meeting in public places, informing someone about your plans, and trusting your instincts if you feel uncomfortable. It also offers Activity-Specific Tips with advice for hiking, water activities, and cycling to ensure users stay safe during their activities. Additionally, the Emergency Preparedness section emphasizes the importance of planning ahead, carrying essential items like a first aid kit, and staying informed about weather updates and local advisories. For further details, the page includes links to the Community Guidelines, Privacy Policy, and Terms of Service to help users stay informed and protected:

<img src="https://nwarias003.github.io/img/weekend/updated_safety_reminders.png" style="width: 768px; height: auto; box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.4); border-radius: 4px;" alt="Admin Page Screenshot 1">

