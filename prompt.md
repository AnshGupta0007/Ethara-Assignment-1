Prompt

Context and Role
You are full-stack engineer specializing in PERN Stack, you are responsible for designing and implementing a high performance Society Subscription Management website. The website should use animation to make it visually appealing while maintaining the cleanliness and professional appearance of the website.
The website should be accessible by both society manager and residents, it should be simple to use and help residents track their flat details, maintenance payments, pending dues and other relevant information. Additionally, it should help the society manager track all residents, payments and subscriptions using tables, graphs and analytics dashboards. Both society manager and resident data should stay properly synchronized in real time.
The system should also include secure authentication, online payment integration and proper role-based access control.


Objective
Develop a complete full-stack portfolio website that:
Implements both frontend and backend using PERN Stack. 
Implements separate login and dashboard for society manager and residents. 
Uses animation and smooth transitions to make the UI visually appealing. 
Uses JWT, NextAuth, and bcrypt for secure authentication and password encryption. 
Keeps resident and manager data properly synchronized. 
      Allows residents to:
View only their own flat and maintenance details
Track pending and completed payments
View payment history and downloadable receipts
Pay maintenance directly from the portal
Raise complaints or support requests

      Allows society manager to:
View all residents and flat information
Track maintenance collections and pending dues
Manage subscriptions and payment records
Mark payments manually as paid for cash/cheque transactions
Add/Edit/Delete residents and flat details
View reports, graphs and analytics dashboards



UI and Animation Requirements
Use modern animations and transitions using Framer Motion or equivalent animation library. 
Implement:
Scroll animations
Fade-ins and staggered transitions
Hover interactions
Animated cards and dashboard widgets
Smooth modal and page transitions
Ensure animations:
Are responsive and performant
Use GPU-friendly properties like transform and opacity
Do not affect scroll or dashboard performance


Layout Requirements
The website should include:
Public Website:
Hero section
About/Features section
Contact section
Login/Register section
Resident Dashboard:
Profile section
Flat and maintenance details
Payment history
Online payment section
Complaints/support section
Society Manager Dashboard:
Residents management table
Maintenance/payment tracking
Revenue and pending dues analytics
Graphs and charts
Notifications and announcements
The layout should be:
Fully responsive
Accessible
Mobile-friendly
Optimized for performance



Backend Requirements
Implement secure REST APIs using Node.js and Express.
Use PostgreSQL with the pg package for database management.
Implement APIs for:
Authentication
Resident management
Payment handling
Maintenance tracking
Complaints and notifications
Dashboard analytics
Use proper validation and sanitization to prevent:
XSS attacks
Injection attacks
Unauthorized access
Implement:
JWT middleware
Role-based route protection
Rate limiting
Secure environment variables
Payment Integration Requirements 
Integrate secure payment gateway support such as:
Razorpay/Stripe or simulated online payment
Features should include:
Online maintenance payments
Payment verification
Transaction logging
Receipt generation
Failed payment handling
Dashboard and Analytics Requirements
Implement tables and graphs for society manager using:
Chart.js / Recharts
Include:
Monthly revenue tracking
Pending dues summary
Payment trends
Resident statistics
Output Requirements 
Responsive and animated Society Subscription Management website.
Separate dashboards for residents and society managers.
Secure JWT and NextAuth authentication system.
Online maintenance payment integration.
Real-time synchronized resident and manager data.
Functional analytics dashboard with tables and graphs.
Proper error handling and validation.
Production-ready backend and frontend architecture.



Technology Stack 
Frontend:
React.js / Next.js
Tailwind CSS
Framer Motion or CSS transitions
Backend:
Node.js
Express.js
PostgreSQL
JWT
bcrypt
Optional:
Firebase/OneSignal for notifications
Recharts for graphs
jspdf for receipts
