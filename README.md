# API Documentation

## User Registration
- URL: `/register/`
- Method: `POST`
- Payload: 
  ```json
  {
    "username": "string",
    "password": "string"
  }

Profile Management:
URL: /profile/<id>/
Method: GET, PUT, DELETE
Payload:
json
Copy code
{
  "user": "id",
  "photo": "file",
  "contact_info": "string"
}

Course Management
URL: /courses/
Method: GET, POST
Payload:
json
Copy code
{
  "title": "string",
  "description": "string",
  "prerequisites": "string"
}

Document the deployment process in docs/deployment_guide.md.

markdown
Copy code
# Deployment Guide

## Prerequisites
- Git
- Python 3.x
- Virtualenv
- Gunicorn
- Nginx

# Internship Review

## Overview
This document summarizes the tasks completed, challenges faced, and skills acquired during the internship.

## Tasks Completed
- Project Planning
- Requirements Gathering
- Database Design
- User Authentication
- API Development (Profile, Course, Enrollment, Feedback, Notification)
- LMS Integration
- Testing and Debugging
- Documentation Preparation
- Deployment Preparation
