# 🌍 EcoTrack - Community-Based Waste Reporting Platform

[🔗 Live Demo](https://ecotrack-green.vercel.app)

EcoTrack is a full-stack MERN (MongoDB, Express.js, React.js, Node.js) web application that empowers users to report waste issues in their local area, helping drive community-led cleanliness and environmental action. With map-based reporting, role-based access for NGOs and admins, and real-time updates, EcoTrack bridges the gap between citizens and waste management authorities.

## 🚀 Features

- 🧭 **Map-Based Reporting**: Users can report waste issues using geolocation and upload images.
- 🛡️ **Authentication**: Secure login and signup using JWT and Google OAuth.
- 🧑‍🤝‍🧑 **Role-Based Access**:
  - **User**: Report issues and track resolution status.
  - **NGO**: Claim and resolve issues, upload post-resolution images.
  - **Admin**: Manage users, NGOs, and reports.
- 📊 **Dashboard**:
  - View total reports, resolved reports, active NGOs, and more.
- 🔍 **Filter & Search**: Search reports by city, status, and category.
- 🗳️ **Voting**: Users can vote on the importance of issues.
- 🛎️ **Reminders**: Get notified about unresolved reports.
- 📌 **Real-Time Status Updates**: Track the lifecycle of a report.
- 🧭 **Find Recycling Centers**: Locate nearby recycling centers on the map.
- 🌐 **Responsive UI**: Optimized for desktop and mobile devices using Tailwind CSS.

## 🛠️ Tech Stack

**Frontend**  
- React.js  
- Tailwind CSS  
- Axios  
- Google Maps API  

**Backend**  
- Node.js  
- Express.js  
- MongoDB (Atlas)  
- Mongoose  
- JWT & Google OAuth 2.0  
- Multer (for image uploads)  

**Deployment**  
- Frontend: Vercel ([Live](https://ecotrack-green.vercel.app))  
- Backend: Render  
- Database: MongoDB Atlas


## 🧑‍💻 Getting Started

### Prerequisites

- Node.js
- MongoDB Atlas account
- Google Cloud Console project for OAuth

### Clone the Repository

```bash
git clone https://github.com/trupal1211/EcoTrack.git
cd EcoTrack
