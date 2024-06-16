# yibPhotography
# 📸 Photographic Portfolio Platform

Welcome to YibPhotography a photographic web Portfolio! This project is a web-based application designed to allow users to explore, purchase, and book photographic services. The site is divided into several sections, including photo galleries, blog, photographic services, and dashboards for both users and administrators.

## 🌟 Main Features

### 1. Registration and Authentication
- **Description**: Users can register and log in to the site using Firebase Authentication.
- **Technology**: Firebase Authentication

### 2. Payment Gateways
- **Description**: Implement two payment gateways, PayPal and Mercado Pago, for users to purchase images or book photographic services.
- **Technology**: PayPal SDK and Mercado Pago SDK

### 3. Administration and User Dashboard
- **Description**:
  - **Admin Dashboard**: Panel where the admin can manage photos, categories, users, and blog content.
  - **User Dashboard**: Panel where users can view their purchases, booked services, and edit their profile.
- **Technology**: React for the interface, Apollo Client for server communication with GraphQL

### 4. Cloud Image Storage
- **Description**: Cloud-based image storage service to allow the upload of high-quality photos.
- **Technology**: Firebase Storage

### 5. Photo Organization by Categories
- **Description**: Allow the admin to create categories and group photos within these categories. Photos can be organized in "folders" on the web.
- **Technology**: MongoDB for storing categories and Firebase Storage for images

### 6. Photography Blog
- **Description**: Section where the admin can post blog entries related to photography, experiences, and tips.
- **Technology**: CRUD with Apollo Server and MongoDB

### 7. Comment and Review System
- **Description**: Allow users to leave comments on photos and reviews on photographic services.
- **Technology**: Apollo Server and MongoDB for storing comments and reviews

### 8. Interactive High-Resolution Gallery
- **Description**: Implement an interactive gallery where users can view high-resolution photos with zoom functionalities.
- **Technology**: Lightbox or similar technology

### 9. Social Media Sharing
- **Description**: Add buttons for users to share photos or blog entries on their social media.
- **Technology**: Social media API integration (Facebook, Twitter, Instagram)

### 10. SEO and Analytics
- **Description**: Implement best SEO practices to improve visibility in search engines and Google Analytics to monitor site traffic.
- **Technology**: Meta tags, proper descriptions, and Google Analytics

### 11. Newsletter
- **Description**: Offer users the option to subscribe to a newsletter to receive updates, new photos, and service offers.
- **Technology**: Mailchimp Integration

### 12. Advanced Filter and Search
- **Description**: Implement an advanced filter and search system for users to find photos by categories, dates, events, etc.
- **Technology**: Advanced queries in Apollo Server and MongoDB

## 🛠️ Technology Stack

### Frontend
- **Framework**: React
- **CSS**: TailwindCSS
- **State Management**: Redux
- **Routing**: React Router

### Backend
- **GraphQL Server**: Apollo Server
- **Database**: MongoDB
- **Authentication**: Firebase Authentication
- **Image Storage**: Firebase Storage
- **Cloud Functions**: Firebase Cloud Functions

### Payment Gateways
- **PayPal**: Integrate PayPal SDK
- **Mercado Pago**: Integrate Mercado Pago SDK

### Deployment
- **Hosting**: Firebase Hosting

## 🏗️ Project Architecture
- **Frontend**: React + TailwindCSS
- **Backend**: Apollo Server + MongoDB + Firebase Functions
- **Authentication**: Firebase Authentication
- **Storage**: Firebase Storage
- **Payment**: PayPal and Mercado Pago SDKs
- **Deployment**: Firebase Hosting
