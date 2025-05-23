# To-Do List App

## Overview

This is a React-based To-Do List application designed to help users organize tasks efficiently. It includes features such as task creation, editing, completion status, and deletion.

## Tech Stack

- **Frontend:** React, CSS  
- **Backend:** Supabase (PostgreSQL database and authentication)  
- **Deployment:** Vercel (frontend)  

## Features

- Add, edit, and delete tasks  
- Mark tasks as completed  
- User authentication (sign up, login) via Supabase  
- Persistent storage of tasks linked to user accounts  

## Architecture & Backend

The backend is built using Supabase, which provides a hosted PostgreSQL database with real-time capabilities and authentication services. The app securely connects to Supabase to store and retrieve tasks per user.

Due to Supabase's free tier limitations, this project’s backend is currently not deployed live. To experience the full functionality:

- Clone the repository  
- Set up your own Supabase project (free tier available)  
- Configure environment variables with your Supabase URL and keys  
- Run the frontend locally using `npm start`  

## Demo

The live frontend is deployed on Vercel: [https://toms-todolist-app-master.vercel.app/](https://toms-todolist-app-master.vercel.app/)  
*Note: Some backend features may be limited in the live demo due to inactive Supabase backend.*

## Getting Started Locally

```bash
git clone https://github.com/yourusername/todo-list-app.git
cd todo-list-app
npm install
# Create a .env file with your Supabase credentials:
# REACT_APP_SUPABASE_URL=your_supabase_url
# REACT_APP_SUPABASE_KEY=your_supabase_anon_key
npm start

# To-Do List App

## Overview

This is a React-based To-Do List application designed to help users organize tasks efficiently. It includes features such as task creation, editing, completion status, and deletion.

## Tech Stack

- **Frontend:** React, CSS  
- **Backend:** Supabase (PostgreSQL database and authentication)  
- **Deployment:** Vercel (frontend)  

## Features

- Add, edit, and delete tasks  
- Mark tasks as completed  
- User authentication (sign up, login) via Supabase  
- Persistent storage of tasks linked to user accounts  

## Architecture & Backend

The backend is built using Supabase, which provides a hosted PostgreSQL database with real-time capabilities and authentication services. The app securely connects to Supabase to store and retrieve tasks per user.

Due to Supabase's free tier limitations, this project’s backend is currently not deployed live. To experience the full functionality:

- Clone the repository  
- Set up your own Supabase project (free tier available)  
- Configure environment variables with your Supabase URL and keys  
- Run the frontend locally using `npm start`  

## Demo

The live frontend is deployed on Vercel: [https://toms-todolist-app-master.vercel.app/](https://toms-todolist-app-master.vercel.app/)  
*Note: Some backend features may be limited in the live demo due to inactive Supabase backend.*

## Getting Started Locally

```bash
git clone https://github.com/yourusername/todo-list-app.git
cd todo-list-app
npm install
# Create a .env file with your Supabase credentials:
# REACT_APP_SUPABASE_URL=your_supabase_url
# REACT_APP_SUPABASE_KEY=your_supabase_anon_key
npm start
