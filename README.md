# Kriya- Mindfulness in Motion
_This is an internship task for FlexMoney_


## Introduction
This project aims to build an admission form for monthly yoga classes, allowing participants to enroll within certain age limits, select batches, and get notified about payments. The solution involves a frontend form built with React, styled using Tailwind CSS, and a backend implemented in Node.js to handle data storage and validations.

## Database Design

## Tech Stack
- ReactJS
- NodeJS
- Tailwind CSS

## Approach
- The frontend hosts a form that collects user data and batch preferences. Frontend validation ensures that only valid data is submitted to the backend. Tailwind CSS is employed for styling and responsiveness.
- Both frontend and backend employ validation checks. Frontend validation ensures that only valid data is sent to the backend, enhancing user experience. Backend validation acts as an additional layer of security to filter out incorrect or malicious data.
- Upon form submission, validated data is sent from the frontend to the backend via RESTful API calls. The backend processes this data, acknowledges successful submission, and responds to the frontend. This response is displayed in a modal on the frontend UI, providing feedback to the user.







