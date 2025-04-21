# Influencer Engagement and Sponsorship Coordination Platform (IESCP)

> A dynamic web platform to connect influencers and sponsors for campaign collaboration, powered by Flask and SQLite.

---

## Author

**Sirimilla Karthik Balaji**  
B.Tech in CSE (AI & ML), MGIT  
BS in Data Science & Applications, IIT Madras (Diploma Level)  
Email: [karthiksirimilla@gmail.com](mailto:karthiksirimilla@gmail.com)

---


## Project Overview

**IESCP** is a full-stack web application designed to facilitate seamless collaboration between **influencers** and **sponsors**. It enables sponsors to create, manage, and monitor ad campaigns while providing influencers with a platform to accept, reject, or negotiate ad requests. The application also includes an **admin dashboard** to moderate users and view platform statistics.

With a user-centric design, secure authentication, and real-time negotiation features, IESCP provides a comprehensive and efficient solution for digital marketing collaborations.

---

## Key Features

### User Authentication & Roles
- **Admin Login** with moderation controls
- **Separate Signup** for Sponsors and Influencers
- **Unified Login Portal** for all users
- Secure password handling using `Werkzeug`

### Admin Dashboard
- View & manage flagged users and campaigns
- Platform-wide statistics and usage insights
- Technologies: Flask, SQLAlchemy, Bootstrap, Matplotlib

### Campaign Management (Sponsors)
- Create, update, and delete campaigns
- Define campaign objectives, budgets, and timelines

### Ad Request System
- Sponsors can send ad requests for campaigns
- Influencers can:
  - View, Accept, or Reject ad requests
  - **Negotiate payments** within the app

### Advanced Search
- **Sponsor View**: Search influencers by niche, reach, and followers
- **Influencer View**: Discover relevant campaigns

### Data Visualization
- Campaign and user statistics presented via:
  - Line charts
  - Pie charts
  - Histograms
- Visualization powered by `Matplotlib`

---

## Technologies Used

| Technology         | Purpose                                   |
|--------------------|--------------------------------------------|
| **Flask**          | Backend framework & routing                |
| **Jinja2**         | HTML templating engine                     |
| **SQLite**         | Lightweight embedded database              |
| **Flask-SQLAlchemy** | ORM for database operations             |
| **Werkzeug**       | Password hashing and security              |
| **Matplotlib**     | Graphs and charts for visual stats         |
| **HTML + Bootstrap** | UI and responsive design                |

---
## How to Run the Application

1. Open the `app.py` Python file.
2. Ensure all required packages are installed. Use the following command to install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the Python file:
    ```bash
    python app.py
    ```
4. The application will be deployed on a local server.
5. Navigate to the server address displayed in the terminal (e.g., `http://127.0.0.1:5000`).
6. Welcome! You can now use the web application to explore its features.

## Demo Video

Check out the demo video of the application to see it in action:  
[Watch Demo Video](https://drive.google.com/file/d/18iBzrww7pKGFNaX1Fz1pbYzJamaMlach/view?usp=drive_link)
