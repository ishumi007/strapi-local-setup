# Strapi Local Setup – Internship Task 1

## Overview
This repository contains my local setup and exploration of the Strapi CMS as part of the DevOps Internship Task 1.

The goal of this task was to:
- Clone the Strapi repository
- Run Strapi locally
- Explore the project structure
- Start the Admin Panel
- Create a sample content type
- Push the setup to GitHub

---

## Tech Stack
- Node.js v18.20.8
- npm / npx
- Strapi v5
- SQLite (default local database)
- OS: Windows

---

## Project Setup

### 1. Clone Repository
```bash
git clone https://github.com/strapi/strapi.git
```
## Create Strapi App (Quickstart)
```
npx create-strapi-app my-strapi-app --quickstart
```
## Install Dependencies
```
npm install
```

## Run Strapi Locally
```
npm run develop
```

## Strapi runs at:
Admin Panel: http://localhost:1337/admin

## Admin Panel Setup
- Created admin user
- Logged into Strapi Admin Dashboard
- Verified Strapi running successfully
- Content Type Creation
- Created a sample Article collection type with:
   - title (Text)
   - description (Rich Text)
   - publishedAt (Date)
   - Added and published sample entries using Content Manager.

## Project Structure Overview
## Key folders explored:
**src/ – application source code**
**config/ – environment and database configuration**
**database/ – SQLite database**
**public/ – static assets**
**node_modules/ – dependencies**

## Screenshots / Demo
Screenshots and demo are recorded in the Loom video (linked in PR).

## Loom Video
<ADD YOUR LOOM VIDEO LINK HERE>

## Author
## Ishu Mishra