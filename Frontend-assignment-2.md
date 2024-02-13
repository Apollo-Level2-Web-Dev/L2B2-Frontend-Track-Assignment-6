# Assignment-06 Frontend Path - 2

# **Post-Disaster Community Health and Medical Supply Chain Platform - Comprehensive Project Overview**

## **Technology Stack:**

- React
- Redux
- RTK Query
- React Router DOM

## **Project Overview:**

The project aims to develop a comprehensive **Post-Disaster Community Health and Medical Supply Chain Platform** using React, and Redux for state management, RTK Query for efficient data fetching, and React Router DOM for navigation. This platform will serve as a vital hub for coordinating and managing health and medical supplies in post-disaster scenarios, ensuring efficient distribution and accessibility.

### **Key Features:**

1. **Home / Landing Page / Root Page [Public]:**
   - **Header / Navbar:**
     - Unauthenticated:
       - **Brand Logo:**
         - A visually appealing logo representing the platform's identity.
       - **All Supplies:**
         - A navigation link to view all supply posts.
       - **Login Button:**
         - Allows users to log in to their accounts.
     - Authenticated:
       - **Brand Logo:**
         - Consistent branding element linking back to the home page.
       - **All Supplies:**
         - Access to view all supply posts.
       - **Dashboard:**
         - Access to the user's dashboard for managing supplies.
       - **Logout Button:**
         - Enables users to log out of their accounts.
   - **Banner / Hero Section:**
     - A visually striking section showcasing key information about the platform's mission and goals.
   - **Supply Posts:**
     - 6 Supply Posts displayed in card format, providing a snapshot of each supply.
     - Each Card will show:
       - **Image:**
         - Visual representation of the supply.
       - **Title:**
         - Concise title summarizing the supply post.
       - **Category:**
         - Categorization of the supply (e.g., Medical Supplies, First Aid Kits, Medications).
       - **Amount:**
         - The quantity or monetary value of the supply.
       - **View Detail Button:**
         - Allows users to explore more details about the supply.
   - **View All Button:**
     - Allows users to access the All Supplies Page (/supplies), displaying a comprehensive list of supply posts related to health and medical supplies. (at least 9-12 posts)
   - **Top 6 Provider Testimonials:**
     - Engaging section featuring static data of provider testimonials with animations and sliders for enhanced user experience.
   - **Gallery / Carousel:**
     - Dynamic carousel showcasing photos of health and medical supplies donations and humanitarian works, fostering transparency and trust among users.
   - **Summary / About Us / Who are we / What we do:**
     - An informative section providing users with detailed insights into the platform's mission, objectives, and impact, focusing on post-disaster community health and medical supply chain management.
   - **2 More Unique Sections:**
     - Addition of two unique sections relevant to the post-disaster health and medical supply chain niche, such as emergency response protocols, healthcare provider testimonials, or disaster preparedness resources.
   - **Footer:**
     - Inclusive footer section featuring contact information, social media links, and relevant resources for further engagement and support.
2. **All Supplies Page (`/supplies`) [Public Route]:**
   - **Grid of Card View of the Supply posts:**
     - Organized grid layout presenting supply posts related to health and medical supplies in a visually appealing format.
     - Each Card will show:
       - **Image:**
         - Visual representation of the supply.
       - **Title:**
         - Concise title summarizing the supply post.
       - **Category:**
         - Categorization of the supply (e.g., Medical Supplies, First Aid Kits, Medications).
       - **Amount:**
         - The quantity or monetary value of the supply.
       - **View Detail button:**
         - Enables users to navigate to the supply details page (**`/supplies/:id`**).
3. **Supply Detail Page (`/supplies/:id`) [Public Route]:**
   - **Standardized Supply Detail Format:**
     - Detailed presentation of a supply post related to health and medical supplies, adhering to a standardized format.
     - The information displayed includes:
       - **Image:**
         - Visual representation of the supply.
       - **Title:**
         - Concise title summarizing the supply.
       - **Category:**
         - Categorization of the supply (e.g., Medical Supplies, First Aid Kits, Medications).
       - **Amount:**
         - The quantity or monetary value of the supply.
       - **Description:**
         - A comprehensive description providing additional context and details about the supply.
       - **Donate Now Button:**
         - Initiates the donation process, opening a confirmation modal with relevant user information and supply data.
         - Upon confirmation, redirects users to the dashboard homepage to display the pie chart statistics.
4. **Login / Register Page [Public Routes]:**
   - **Register Page (`/register`):**
     - User-friendly registration form enabling users to create new accounts with essential information such as:
       - **User Name**
       - **Email**
       - **Password**
   - **Login Page (`/login`):**
     - Secure login interface allowing users to access their accounts by providing valid credentials (email and password).
5. **Dashboard [Private Routes]:**
   - **Dashboard Home Page (`/dashboard`):**
     - Dynamic dashboard interface featuring essential elements for managing user supplies and accessing statistical insights.
     - **PieChart on Supplies Calculations:**
       - Visual representation of supply statistics with dynamic data retrieved from the backend, facilitating informed decision-making and strategic planning.
     - **All Supply Posts Page (Nested) (`/dashboard/supplies`):**
       - A comprehensive view of all supply posts in a table format, displaying key details such as:
         - **Title**
         - **Category**
         - **Amount**
       - **Action Buttons:**
         - **Edit:**
           - Opens a modal containing the details of the supply in an editable form for updates.
         - **Delete:**
           - Triggers a confirmation modal for deleting the supply post upon user confirmation.
           - Upon confirmation, the supply post will be permanently removed from the platform.
       - **Add Supply Post Button:**
         - Directs users to the Create Supply Post Page (**`/dashboard/create-supply`**).
         - Enables users to contribute new supply posts related to health and medical supplies.
   - **Create Supply Post Page (`/dashboard/create-supply`):**
     - Interactive form allowing users to create new supply posts with the following data structure:
       - **Image**
       - **Category**
       - **Title**
       - **Amount**
       - **Description**
   - **Animations:**
     - Implementation of 3-4 animations using the Framer Motion library to enhance the visual appeal and interactivity of the platform.

### **Detailed Implementation Guidelines:**

- **Database Management:**
  - Choose MongoDB as the backend database, leveraging their capabilities for efficient data storage and retrieval.
  - Optionally, integrate Mongoose for defining database schemas and interacting with the database.
- **UI/UX Design:**
  - Ensure responsiveness across devices, focusing on mobile-first development for broad accessibility.
- **Deployment & Testing:**
  - Deploy the application to a suitable hosting platform such as Vercel, ensuring seamless accessibility for users.
  - Thoroughly test all functionalities, including authentication, supply management, navigation, responsiveness, and error handling, to guarantee robust performance.

## **Submission Guidelines:**

- Submit a well-documented codebase with clear comments.
- Make sure to add a README file that explains how to set up and use the application. In the README, include details like the project name, live URL, features, technology used, and other important information. Try to make it look professional by doing some research and making it appealing.

## What you need to submit:

- Provide the Private GitHub repository (in GitHub Classroom) links of the front-end and back-end and ensure there is a README file with explicit instructions for running the application locally.
- Live deployment link
- Submit a demo video showcasing the functionality of your project.

## Github Private Repo (Github ClassRoom):

- For Client(Frontend): https://classroom.github.com/a/ugYcKW_q
- For Server(Backed): https://classroom.github.com/a/EfrfvbCd

## **Deadline:**

- 60 marks: February 17, 2024 11.59 PM
- 50 marks: February 18, 2024 11.59 PM
- 30 marks: After February 18, 2024

## Important Note:

Plagiarism will not be tolerated. Ensure that the code you submit is your work. Any instances of plagiarism will result in 0 Marks.

Good luck with your assignment! If you have any questions, feel free to reach out for clarification.
