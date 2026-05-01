# Aura Hair & Beauty Booking System

## Overview
This project is a cloud-based hair salon appointment booking system built using Amazon Web Services (AWS). It allows users to book appointments online and stores the data in a cloud database.

---

## Features
- Online appointment booking form
- Real-time data storage using DynamoDB
- Serverless backend using AWS Lambda
- API integration using API Gateway
- Ability to retrieve and delete bookings
- Hosted as a static website using Amazon S3

---

## Technologies Used
- HTML, CSS, JavaScript (Frontend)
- Amazon S3 (Website Hosting)
- Amazon API Gateway (API Management)
- AWS Lambda (Serverless Backend)
- Amazon DynamoDB (Database)

---

## System Architecture

User → S3 Website → API Gateway → Lambda → DynamoDB

- The user submits a booking form
- API Gateway receives the request
- Lambda processes the request
- DynamoDB stores or retrieves the data

---

## API Endpoints

- POST /bookings → Save booking
- GET /bookings → Retrieve bookings
- DELETE /bookings/{bookingID} → Delete booking

---

## How to Run

1. Open the hosted website:
   http://salon-booking-app-sema-2026.s3-website.eu-north-1.amazonaws.com/index.html

2. Fill out the booking form
3. Submit booking
4. Data will be stored in DynamoDB

---

## Author
Sema Burcak
