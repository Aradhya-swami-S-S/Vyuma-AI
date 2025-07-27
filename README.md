# VYUMA-AI

Vyuma-AI is a full-stack web application designed for resort listing, booking, and review management. It enables users to sign up, log in, view available resorts, make bookings, and leave reviews. Admins and hosts can manage resort listings and view customer interactions.

![Banner](https://img.shields.io/github/license/Aradhya-swami-S-S/Vyuma-AI?style=default\&logo=opensourceinitiative\&logoColor=white\&color=0080ff)
![Last Commit](https://img.shields.io/github/last-commit/Aradhya-swami-S-S/Vyuma-AI?style=default\&logo=git\&logoColor=white\&color=0080ff)
![Top Language](https://img.shields.io/github/languages/top/Aradhya-swami-S-S/Vyuma-AI?style=default\&color=0080ff)

---

## 📦 Tech Stack

* **Frontend:** HTML, CSS, JavaScript (Vanilla), EJS Templates
* **Backend:** Node.js, Express.js
* **Database:** MongoDB Atlas


---

## 🚀 Features

* User registration and login (authentication)
* Create, update, delete resort listings (CRUD)
* Book resorts and manage bookings
* Leave reviews on resort listings
* Error handling with custom error pages
* User dashboard for managing own bookings

---

## 📁 Project Structure

```
Vyuma-AI/
├── app.js
├── cloudConfig.js
├── controllers/
│   ├── booking.js
│   ├── listings.js
│   ├── reviews.js
│   └── users.js
├── init/
│   ├── data.js
│   └── index.js
├── middleware.js
├── models/
│   ├── booking.js
│   ├── listing.js
│   ├── review.js
│   └── user.js
├── public/
│   ├── css/
│   ├── html/
│   ├── js/
│   └── images/
├── routes/
│   ├── auth.js
│   ├── bookings.js
│   ├── listing.js
│   ├── review.js
│   ├── user.js
│   └── userRoutes.js
├── utils/
│   ├── ExpressError.js
│   └── wrapAsync.js
├── views/
│   ├── error.ejs
│   ├── includes/
│   ├── layouts/
│   ├── listings/
│   └── users/
├── schema.js
├── package.json
└── README.md
```

---

## 🛠️ Getting Started

### Prerequisites

* Node.js (v14 or higher)
* npm

### Installation

```bash
git clone https://github.com/Aradhya-swami-S-S/Vyuma-AI.git
cd Vyuma-AI
npm install
```

### Environment Variables

Create a `.env` file in the root directory with the following:

```env
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_KEY=your_key
CLOUDINARY_SECRET=your_secret
DB_URL=your_mongodb_connection_url
SESSION_SECRET=your_session_secret
```

### Running the App

```bash
node app.js
```

Visit: `http://localhost:<your port>`

---

## 🧪 Testing

No formal tests implemented. Manual test by simulating various user flows (sign up, book, review, etc.)

---

## 📌 Roadmap

* [x] Implement authentication
* [x] Cloudinary integration for images
* [x] Basic user dashboard
* [ ] Admin panel for managing users and listings
* [ ] Stripe integration for payments


