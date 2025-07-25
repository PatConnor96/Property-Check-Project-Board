# 🏡 NSW Planning Advisor Platform

## Overview

This platform provides planning advice for individuals looking to purchase property in New South Wales (NSW), Australia. It helps users understand planning controls, zoning, overlays, and restrictions relevant to any parcel of land in NSW.

## 🎯 Purpose

This tool is designed to support:
- Everyday property buyers
- Small developers
- Homeowners navigating the NSW planning system

## 💼 Services

1. **Free Property Planning Report Tool**  
   A self-service viewer that provides zoning, overlays, and planning info for any NSW parcel, similar to the NSW Planning Portal.

2. **$100 “Do It Yourself” Planning Pack**  
   Step-by-step videos and instructions to teach users how to research and analyse planning issues themselves.

3. **$200 “Done For You” Report Service**  
   A professional planning report delivered within 48 hours. Add-ons include:
   - $100 for each additional property
   - $50 to expedite to 24-hour delivery

## 🧱 Tech Stack

- **Frontend**: React
- **Backend**: Express.js
- **Database**: PostgreSQL
- **Authentication**: OAuth (Google, Facebook)
- **Hosting**: Vercel, Railway (TBC)

## 🔐 Security

- OAuth login ensures secure authentication via trusted third-party providers
- Sensitive configuration data is excluded using `.gitignore` and stored securely in environment variables

## 🛠 Local Setup

### 1. Clone the repo
```bash
git clone https://github.com/yourusername/nsw-planning-advisor.git
cd nsw-planning-advisor
```

### 2. Install dependencies
```bash
npm install
```

### 3. Create your `.env` file
```bash
cp .env.example .env
```
Fill in your database and API credentials.

### 4. Run locally
```bash
npm run dev
```

## 📁 Project Structure
```
.env.example         # Template for environment variables
.gitignore           # Prevents sensitive files from being committed
README.md            # Project overview and setup instructions
```

## 🚧 Work in Progress

This project is under active development. The roadmap and features are managed in the [GitHub Project Board](https://github.com/yourusername/nsw-planning-advisor/projects).

## 📬 Contact

For feedback, reach out to [Your Name] or open an issue in this repository.
