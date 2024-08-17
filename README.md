# Instagram_Clone

## Objective:

The objective of this project is to create a fully functional Instagram clone that allows users to register, create profiles, upload photos, follow other users, like and comment on posts, and explore a feed of content. The project will serve as a hands-on learning experience, allowing the team to gain practical skills in full-stack development, including frontend and backend technologies, user authentication, cloud deployment, and responsive design.

## Features:

### **User Registration and Authentication:**

- Implement user registration
- Allow users to log in and log out securely.
- Handle authentication using JWT
- Set up password reset functionality.*

### **User Profiles:**

- Allow users to create and update their profiles, including a profile picture, bio, and username.
- Implement a public profile page where other users can view the profile, including a list of photos and follower/following counts.
- Include an edit profile option for users to update their information.

### **Photo Upload and Sharing:**

- Enable users to upload photos with captions.
- Implement image processing (e.g., resizing, cropping) using libraries like Pillow.
- Store uploaded photos securely using AWS S3.
- Display photos in a user’s profile and feed.

### **Follow and Unfollow:**

- Allow users to follow and unfollow other users.
- Implement a following system where users can see posts from the users they follow in their feed.
- Include follower and following counts on user profiles.

### **Like and Comment:**

- Enable users to like and unlike photos.
- Implement a commenting system where users can add comments to photos.
- Display the number of likes and comments on each photo.
- Implement real-time updates for likes and comments.

### **Feed and Discover:**

- Create a personalized feed showing photos from followed users.
- Optimize the feed with infinite scrolling for a smooth user experience.
- Implement a "Discover" page where users can find new content based on trending tags, popular posts, or suggested users.*

### **Responsive UI:**

- Design a responsive user interface that works seamlessly on desktops, tablets, and mobile devices.
- Use Tailwind CSS to create a modern, mobile-friendly design.
- Ensure that all pages, including profiles, feeds, and photo uploads, are responsive.

## Tech Stack

### **Frontend:** React/JS

- Build the user interface using React.
- Use React Router for navigation between different pages.
- Implement state management using React hooks or Redux.
- Integrate Axios or Fetch API for communication with the backend.

### **Backend:** Python/Django

- Use Django for handling the backend logic and database management.
- Set up Django REST Framework (DRF) to create RESTful APIs for frontend-backend communication.
- Implement user authentication and authorization using Django’s built-in features and JWT for token-based authentication.
- Use PostgreSQL as the database to store user information, photos, comments, likes, and other relevant data.

### **Cloud:** AWS

- Deploy the application on AWS using services like EC2, RDS (for PostgreSQL), and S3 (for photo storage).
- Set up an AWS S3 bucket for securely storing uploaded images.
- Implement CI/CD pipelines using AWS CodePipeline or other tools for automated testing and deployment.
- Monitor application performance and errors using AWS CloudWatch.
