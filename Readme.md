# 📊 Instagram Database Analysis

This repository contains SQL queries used to analyze an Instagram-like database. The queries help in deriving insights about user behavior, engagement, and activity patterns.

## 📌 Features & Queries Implemented

### 1️⃣ **User Analysis**
- Identified the **oldest 5 users** in the database.
- Analyzed the **most common day of user registrations** to help in scheduling ad campaigns.
- Found **inactive users** (users who have never posted a photo).
- Calculated the **average number of posts per user**.

### 2️⃣ **Engagement Analysis**
- Identified the **user with the most likes on a single photo** (contest winner).
- Ranked users by **total posts** (from highest to lowest).
- Found the **top 5 most commonly used hashtags** for better branding.

### 3️⃣ **Bot & Celebrity Detection**
- Detected **users who have liked every single photo** (potential bot activity).
- Found **users who have never commented on a photo** (potential celebrities or inactive users).
- Calculated the **percentage of users who either never commented or commented on every photo**.

### 4️⃣ **User Posting Behavior**
- Identified the **total number of users who have posted at least once**.
- Determined the **total number of posts made by all users**.

## 📂 Database Schema
The database consists of the following tables:
- **users** (id, username, created_at, etc.)
- **photos** (id, user_id, image_url, etc.)
- **likes** (id, user_id, photo_id, etc.)
- **comments** (id, user_id, photo_id, comment_text, etc.)
- **tags** (id, tag_name, etc.)
- **photo_tags** (id, photo_id, tag_id, etc.)

## 🛠 Technologies Used
- SQL (MySQL )
- Database Management & Optimization

## 📜 How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/hars310/insta-db-project.git
   ```
2. Navigate to the project folder:
   ```bash
   cd insta-db-project
   ```
3. Run the SQL queries using your preferred database client.
