# 🤝 VolunteerConnect – Volunteer Availability Platform

### Connecting NGOs with Volunteers Through Smart Availability Matching

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen?style=for-the-badge)](https://volunteer-availability-platform.vercel.app/register)
![Next.js](https://img.shields.io/badge/Next.js-14-black?style=for-the-badge&logo=next.js)
![React](https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-47A248?style=for-the-badge&logo=mongodb)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-CSS-38B2AC?style=for-the-badge&logo=tailwind-css)

## 🌐 Live Demo

**Try the application:** https://volunteer-availability-platform.vercel.app/register

---

## 📌 About the Project

**VolunteerConnect** is a full-stack web application designed to connect NGOs and organizations with volunteers based on their availability.

Many NGOs organize activities such as cleanliness drives, tree plantation campaigns, educational programs, and community services. However, finding volunteers who are actually available at the required date and time can be challenging.

Similarly, people who want to volunteer often struggle to find opportunities that fit their schedules.

VolunteerConnect solves this problem through a smart availability-based matching system that connects volunteers with suitable opportunities.

## 🎯 Key Features

### 👤 1. Volunteer Portal
- Secure volunteer registration and login.
- Create and manage volunteer profiles.
- Set weekly availability schedules.
- Discover volunteering opportunities.
- Find opportunities matching available time slots.
- Apply for volunteering opportunities.
- Track application status.

### 🏢 2. NGO Portal
- Dedicated NGO registration and login.
- Submit organization details for verification.
- Create and publish volunteering opportunities.
- Specify event dates, timings, locations, and required volunteers.
- View volunteer applications.
- Accept or reject applications.
- Track volunteer requirements and application progress.

### 🛡️ 3. Super Admin Portal
- Dedicated administrator dashboard.
- View registered NGOs and volunteers.
- Review NGO registration details.
- Approve or reject NGO verification requests.
- Manage and monitor platform activities.
- Access platform reports.

### ⚡ 4. Smart Availability Matching
- Matches volunteer schedules with NGO event timings.
- Identifies suitable volunteering opportunities.
- Calculates schedule compatibility.
- Helps NGOs find volunteers who are available when needed.

### 🌙 5. Additional Features
- Modern and responsive user interface.
- Dark Mode and Light Mode.
- Role-based dashboards.
- Secure authentication.
- Interactive application management.
- MongoDB database integration.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Next.js 14 | Full-stack framework |
| React.js 18 | Frontend development |
| JavaScript | Application logic |
| Tailwind CSS | Styling and responsive UI |
| MongoDB Atlas | Cloud database |
| Mongoose | Database modeling |
| Node.js | Server-side runtime |
| JWT | Authentication |
| bcryptjs | Password hashing |
| Lucide React | Icons |
| Vercel | Deployment |

---

## 🔄 How It Works

1. **Register:** Volunteers and NGOs create their respective accounts.
2. **Set Availability:** Volunteers specify their available days and time slots.
3. **Post Opportunities:** NGOs create volunteering events with specific dates and timings.
4. **Smart Matching:** The platform identifies opportunities that match volunteer availability.
5. **Apply:** Volunteers apply for suitable opportunities.
6. **Review Applications:** NGOs review applications and accept or reject volunteers.
7. **Manage Activities:** Volunteers and NGOs track their application progress through their dashboards.

---

## 🖥️ User Roles

| Role | Responsibilities |
|---|---|
| Volunteer | Set availability, discover opportunities, and apply |
| NGO | Publish opportunities and manage volunteers |
| Super Admin | Verify NGOs and monitor platform activities |

---

## 📂 Project Structure

```text
volunteerconnect/
│
├── app/
│   ├── actions/
│   ├── admin/
│   ├── api/
│   │   ├── admin/
│   │   ├── applications/
│   │   ├── auth/
│   │   ├── opportunities/
│   │   └── volunteer/
│   ├── login/
│   ├── register/
│   ├── ngo/
│   │   ├── dashboard/
│   │   └── create-opportunity/
│   └── volunteer/
│       ├── dashboard/
│       ├── availability/
│       └── applications/
│
├── components/
│   ├── AuthProvider.jsx
│   ├── Navbar.jsx
│   ├── Footer.jsx
│   └── ThemeProvider.jsx
│
├── lib/
│   ├── auth.js
│   ├── matching.js
│   └── mongodb.js
│
├── models/
│   ├── User.js
│   ├── NgoProfile.js
│   ├── Opportunity.js
│   ├── Application.js
│   └── VolunteerAvailability.js
│
├── public/
├── .env.example
├── package.json
└── README.md
```

---

## ⚙️ Installation & Setup

Follow these steps to run the project locally.

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Navigate to the Project Folder

```bash
cd volunteerconnect
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Configure Environment Variables

Create a `.env.local` file in the root directory.

```env
MONGODB_URI=your_mongodb_connection_string

JWT_SECRET=your_secure_jwt_secret

NEXT_PUBLIC_APP_URL=http://localhost:3001
```

Replace the MongoDB connection string with your MongoDB Atlas connection string.

### 5. Start the Development Server

```bash
npm run dev
```

### 6. Open in Browser

```text
http://localhost:3001
```

---

## 🔐 Security Features

- Password hashing using bcryptjs.
- JWT-based authentication.
- HTTP-only authentication cookies.
- Role-based access control.
- Protected application routes.
- MongoDB database integration.

---

## 🚀 Deployment

The application is deployed using **Vercel**, with MongoDB Atlas used for cloud database management.

**Live Application:**  
https://volunteer-availability-platform.vercel.app/register

---

## 🔮 Future Enhancements

- Email notifications for application updates.
- Advanced volunteer recommendation system.
- Google Maps integration for nearby opportunities.
- Volunteer certificates and achievement tracking.
- Real-time notifications.
- Analytics dashboard for NGOs.
- Mobile application integration.

---

## 💡 Project Objective

The main objective of VolunteerConnect is to make volunteering more accessible, organized, and efficient by connecting people who want to help with organizations that need help.

It aims to reduce scheduling conflicts, improve volunteer coordination, and encourage more people to participate in social activities.

---

## 👨‍💻 Developer

**Developed as a Full-Stack Web Development Project.**

If you find this project useful, consider giving it a ⭐ on GitHub!

**Made with ❤️ using Next.js, React, MongoDB, and Tailwind CSS.**
