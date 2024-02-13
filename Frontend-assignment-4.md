# Assignment-06 Frontend Path - 4

# **Distribution of Winter Clothes Management Platform - Detailed Project Overview**

## **Technology Stack:**

- React
- Redux
- RTK Query
- React Router DOM

## **Project Overview:**

The project aims to develop a comprehensive **Distribution of Winter Clothes Management Platform** using React, Redux for state management, RTK Query for efficient data fetching, and React Router DOM for navigation. This platform will serve as a vital tool for coordinating and managing the distribution of winter clothes to communities in need, ensuring warmth and comfort during cold seasons.

### **Key Features:**

1. **Home / Landing Page / Root Page [Public]:**
   - **Header / NavBar:**
     - Unauthenticated:
       - **Brand Logo:**
         - A visually appealing logo representing the platform's identity.
       - **All Winter Clothes:**
         - A navigation link to view all winter clothes posts.
       - **Login Button:**
         - Allows users to log in to their accounts.
     - Authenticated:
       - **Brand Logo:**
         - Consistent branding element linking back to the home page.
       - **All Winter Clothes:**
         - Access to view all winter clothes posts.
       - **Dashboard:**
         - Access to the user's dashboard for managing winter clothes.
       - **Logout Button:**
         - Enables users to log out of their accounts.
   - **Banner / Hero Section:**
     - A visually striking section showcasing key information about the platform's mission and goals related to winter clothes distribution.
   - **Winter Clothes Posts:**
     - 6 Winter Clothes Posts displayed in card format, providing a snapshot of each clothing item.
     - Each Card will show:
       - **Image:**
         - Visual representation of the winter clothing item.
       - **Title:**
         - Concise title summarizing the clothing item.
       - **Category:**
         - Categorization of the clothing item (e.g., Jackets, Sweaters, Gloves).
       - **Size:**
         - Available size options for the clothing item.
       - **View Detail Button:**
         - Allows users to explore more details about the clothing item.
   - **View All Button:**
     - Allows users to access the All Winter Clothes Page (/winter-clothes), displaying a comprehensive list of winter clothes posts. (at least 9-12 posts)
   - **Top 6 Donor Testimonials:**
     - Engaging section featuring static data of donor testimonials related to winter clothes contributions, utilizing animations and sliders for enhanced user experience.
   - **Gallery / Carousel:**
     - Dynamic carousel showcasing photos of winter clothes distributions and community outreach efforts, fostering transparency and trust among users.
   - **Summary / About Us / Who Are We / What We Do:**
     - An informative section providing users with detailed insights into the platform's mission, objectives, and impact, focusing on winter clothes distribution management.
   - **2 More Unique Sections:**
     - Addition of two unique sections relevant to the winter clothes distribution niche, such as cold weather safety tips, success stories from beneficiaries, or volunteer opportunities.
   - **Footer:**
     - Inclusive footer section featuring contact information, social media links, and relevant resources for further engagement and support.
2. **All Winter Clothes Page (`/winter-clothes`) [Public Route]:**
   - **Grid of Card View of the Winter Clothes posts:**
     - Organized grid layout presenting winter clothes posts in a visually appealing format.
     - Each Card will show:
       - **Image:**
         - Visual representation of the winter clothing item.
       - **Title:**
         - Concise title summarizing the clothing item.
       - **Category:**
         - Categorization of the clothing item (e.g., Jackets, Sweaters, Gloves).
       - **Size:**
         - Available size options for the clothing item.
       - **View Detail button:**
         - Enables users to navigate to the winter clothes details page (**`/winter-clothes/:id`**).
3. **Winter Clothes Detail Page (`/winter-clothes/:id`) [Public Route]:**
   - **Standardized Winter Clothes Detail Format:**
     - Detailed presentation of a winter clothes post adhering to a standardized format.
     - The information displayed includes:
       - **Image:**
         - Visual representation of the winter clothing item.
       - **Title:**
         - Concise title summarizing the clothing item.
       - **Category:**
         - Categorization of the clothing item (e.g., Jackets, Sweaters, Gloves).
       - **Size:**
         - Available size options for the clothing item.
       - **Description:**
         - A comprehensive description providing additional context and details about the clothing item.
       - **Donate Now Button:**
         - Initiates the donation process, opening a confirmation modal with relevant user information and winter clothes data.
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
     - **All Winter Clothes Page (Nested) (`/dashboard/winter-clothes`):**
       - A comprehensive view of all winter clothes posts in a table format, displaying key details such as:
         - **Title**
         - **Category**
         - **Size**
       - **Action Buttons:**
         - **Edit:**
           - Opens a modal containing the details of the winter clothes post in an editable form for updates.
         - **Delete:**
           - Triggers a confirmation modal for deleting the winter clothes post upon user confirmation.
           - Upon confirmation, the winter clothes post will be permanently removed from the platform.
       - **Add Winter Clothes Post Button:**
         - Directs users to the Create Winter Clothes Post Page (**`/dashboard/create-winter-clothes`**).
         - Enables users to contribute new winter clothes posts for distribution.
   - **Create Winter Clothes Post Page (`/dashboard/create-winter-clothes`):**
     - Interactive form allowing users to create new winter clothes posts with the following data structure:
       - **Image**
       - **Category**
       - **Title**
       - **Size**
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
  - Deploy the application to a suitable hosting platform such as Vercel, Netlify, ensuring seamless accessibility for users.
  - Thoroughly test all functionalities, including authentication, winter clothes management, navigation, responsiveness, and error handling, to guarantee robust performance.

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
