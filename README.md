# College Placement Management System

A web-based College Placement Management System developed using React, Material UI, Axios, React Router, and JWT authentication. The system provides separate dashboards and role-based access for Admin and Student users.

## Features

### Admin Dashboard

* Student management
* Company management
* Placement drive management
* Application management
* Interview management
* Placement reports

### Student Dashboard

* Student profile
* Available placement drives
* Job applications
* Interview status tracking

### Eligibility Checking

Implemented an eligibility-checking engine based on:

* CGPA
* 10th percentage
* 12th percentage
* Branch
* Graduation year
* Backlogs
* Application deadline

Students receive clear reasons when they are not eligible for a placement drive.

### Authentication & Security

* JWT-based authentication
* Role-based protected routes
* Axios interceptors for authentication
* Automatic logout when sessions expire

### Interview Tracking

Built an interview-stage tracker using Material UI Stepper to help students track their progress through different placement stages.

## Tech Stack

* React.js
* Material UI
* Axios
* React Router
* JWT
* JavaScript

## Modules

**Admin:** Students, Companies, Drives, Applications, Interviews, Reports

**Student:** Profile, Drives, Applications, Interview Status
