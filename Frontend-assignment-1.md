# Assignment-06 Frontend Path - 1

# **Post-Disaster Relief Donation Platform - Comprehensive Project Overview**

## **Technology Stack:**

- React
- Redux
- RTK Query
- React Router DOM

## **Project Overview:**

The project aims to develop a comprehensive **Disaster Relief Donation Platform** using React, Redux for state management, RTK Query for efficient data fetching, and React Router DOM for navigation. This platform will facilitate post-disaster relief efforts by providing a centralized hub for donations, donor testimonials, and relevant information.

### **Key Features:**

1. **Home / Landing Page / Root Page [Public]:**
   - **Header / Navbar:**
     - Unauthenticated:
       - **Brand Logo:**
         - A visually appealing logo representing the platform's identity.
       - **All Donations:**
         - A navigation link to view all donation posts.
       - **Login Button:**
         - Allows users to log in to their accounts.
     - Authenticated:
       - **Brand Logo:**
         - Consistent branding element linking back to the home page.
       - **All Donations:**
         - Access to view all donation posts.
       - **Dashboard:**
         - Access to the user's dashboard for managing donations.
       - **Logout Button:**
         - Enables users to log out of their accounts.
   - **Banner / Hero Section:**
     - A visually striking section showcasing key information about the platform's mission and goals.
   - **Donation Posts:**
     - 6 Donation Posts displayed in card format, providing a snapshot of each donation.
     - Each Card will show:
       - **Image:**
         - Visual representation of the donation.
       - **Title:**
         - Concise title summarizing the donation post.
       - **Category:**
         - Categorization of the donation (e.g., Food, Clothing, Shelter).
       - **Amount:**
         - The monetary value or quantity of the donation.
       - **View Detail Button:**
         - Allows users to explore more details about the donation.
   - **View All Button:**
     - The platform allows users to access the All Donations Page (/donations), where they can view a comprehensive list featuring a minimum of 9-12 donation posts.
   - **Top 6 Donor Testimonials:**
     - Engaging section featuring static data of donor testimonials with animations and sliders for enhanced user experience.
   - **Gallery / Carousel:**
     - Dynamic carousel showcasing photos of donations and humanitarian works, fostering transparency and trust among users.
   - **Summary / About Us / Who are we / What we do:**
     - Informative section providing users with detailed insights into the platform's mission, objectives, and impact.
   - **2 More Unique Sections:**
     - Addition of two unique sections relevant to the post-disaster relief niche, such as success stories, impact metrics, or volunteer opportunities.
   - **Footer:**
     - Inclusive footer section featuring contact information, social media links, and relevant resources for further engagement and support.
2. **All Donations Page (`/donations`) [Public Route]:**
   - **Grid of Card View of the Donation posts:**
     - Organized grid layout presenting donation posts in a visually appealing format.
     - Each Card will show:
       - **Image:**
         - Visual representation of the donation.
       - **Title:**
         - Concise title summarizing the donation post.
       - **Category:**
         - Categorization of the donation.
       - **Amount:**
         - The monetary value or quantity of the donation.
       - **View Detail button:**
         - Enables users to navigate to the donation details page (**`/donations/:id`**).
3. **Donation Detail Page (`/donations/:id`) [Public Route]:**
   - **Standardized Donation Detail Format:**
     - Detailed presentation of a donation post, adhering to a standardized format.
     - The information displayed includes:
       - **Image:**
         - Visual representation of the donation.
       - **Title:**
         - Concise title summarizing the donation.
       - **Category:**
         - Categorization of the donation.
       - **Amount:**
         - The monetary value or quantity of the donation.
       - **Description:**
         - A comprehensive description providing additional context and details about the donation.
   - **Donate Now Button:**
     - Triggering a confirmation modal with relevant user information and donation data upon click.
     - Upon confirmation, redirects users to the dashboard homepage to visualize donation statistics via a pie chart.
4. **Login / Register Page: [Public Routes]**
   - **Register Page (`/register`):**
     - User-friendly registration page allowing users to create an account with essential information:
       - **User Name**
       - **Email**
       - **Password**
   - **Login Page (`/login`):**
     - Secure login page enabling users to access their accounts with email and password credentials.
5. **Dashboard: [Private Routes]**
   - **Dashboard Home Page (`/dashboard`):**
     - **PieChart on Donations Calculations:**
       - Visualization of donation statistics utilizing a pie chart.
       - Data is sourced from the backend, reflecting either static or dynamic information for enhanced insights.
   - **All Donation Posts Page (Nested) (`/dashboard/donations`):**
     - **Table View of Donation Posts:**
       - Tabular representation of donation posts, offering a structured overview for easy management.
       - The information displayed includes:
         - **Title**
         - **Category**
         - **Amount**
       - **Action Buttons:**
         - **Edit:**
           - Opens a modal containing the details of the selected donation post in a form for editing purposes.
         - **Delete:**
           - Triggers a confirmation modal for deleting the donation post.
           - Upon confirmation, the donation post will be permanently removed.
       - **Add Donation Post Button:**
         - Directs users to the Create Donation Post Page (**`/dashboard/create-donation`**).
   - **Create Donation Post Page:**
     - **Form-based Interface for Donation Post Creation:**
       - Intuitive form allowing users to input relevant details for creating a new donation post.
       - Donation Post Data Structure includes:
         - **Image**
         - **Category**
         - **Title**
         - **Amount**
         - **Description**
       - **Animations:**
         - Implementation of 3-4 animations using the Framer Motion library to enhance the visual appeal and interactivity of the platform.

## **Additional Information:**

- **Code Implementation:**
  - Utilize React components for modular UI development, ensuring reusability and maintainability.
  - Implement Redux for efficient state management, enabling seamless data flow throughout the application.
  - Leverage RTK Query for optimized data fetching, minimizing network requests, and enhancing performance.
  - Utilize React Router DOM for smooth navigation and routing within the application.
- **Database Management:**
  - Choose MongoDB as the backend database, leveraging their capabilities for efficient data storage and retrieval.
  - Optionally, integrate Mongoose for defining database schemas and interacting with the database.
- **UI/UX Design:**
  - Ensure responsiveness across devices, focusing on mobile-first development for broad accessibility.
- **Deployment & Testing:**
  - Deploy the application to a suitable hosting platform such as Vercel, ensuring seamless accessibility for users.
  - Thoroughly test all functionalities, including authentication, donations, navigation, responsiveness, and error handling, to guarantee robust performance.

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
