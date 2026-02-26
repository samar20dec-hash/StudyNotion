# StudyNotion

StudyNotion is a full-stack EdTech platform that enables users to create, consume, and rate educational content.  
It is built using the MERN stack and is designed to provide an engaging learning experience for students while empowering instructors to showcase their expertise globally.

---

## Features

### For Students
- User authentication with OTP and password recovery
- Browse and enroll in courses
- Wishlist and cart checkout
- Secure payments using Razorpay
- Access video and document-based course content
- Rate courses and manage profile

### For Instructors
- Instructor dashboard
- Create, update, and delete courses
- Manage course content and pricing
- View insights and analytics
- Edit profile details

### Future Admin Scope
- Platform-wide dashboard
- User and instructor management
- Course moderation and analytics

---

## System Architecture

StudyNotion follows a client–server architecture consisting of:

- Frontend: ReactJS
- Backend: NodeJS and ExpressJS (Monolithic Architecture)
- Database: MongoDB
- Media Storage: Cloudinary

---

## Frontend Tech Stack

- ReactJS
- Redux (State Management)
- Tailwind CSS
- CSS
- Figma (UI/UX Design)
- VS Code

### Key Pages
- Home
- Course Listing
- Wishlist
- Cart and Checkout
- Course Content
- Student and Instructor Dashboards

---

## Backend Tech Stack

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT for authentication
- Bcrypt for password hashing
- Razorpay for payments
- Cloudinary for media management

---

## Database Models

- Student
- Instructor
- Course

Each schema stores relevant user details, course data, media references, and ratings.

---

## API Design (REST)

Sample endpoints:

- POST /api/auth/signup – User registration  
- POST /api/auth/login – User login and JWT generation  
- POST /api/auth/verify-otp – OTP verification  
- GET /api/courses – Fetch all courses  
- POST /api/courses – Create a course  
- PUT /api/courses/:id – Update course  
- DELETE /api/courses/:id – Delete course  
- POST /api/courses/:id/rate – Rate a course  

---

## Deployment

- Frontend: Vercel
- Backend: Render or Railway
- Database: MongoDB Atlas
- Media Storage: Cloudinary

The infrastructure ensures scalability, security, and high availability.

---

## Testing

- API testing using REST tools
- Manual testing for frontend flows
- Authentication and payment flow validation

---

## Future Enhancements

- Gamification features such as points and leaderboards
- Personalized learning paths
- Social learning and collaboration
- Mobile application
- Machine learning-based course recommendations
- Virtual and augmented reality integration

---

## Conclusion

StudyNotion is a scalable and secure MERN-based EdTech platform designed to deliver a seamless learning experience.  
The project demonstrates strong full-stack development, REST API design, authentication, payment integration, and cloud deployment practices.

---

## Author

Developed as part of an EdTech project.
