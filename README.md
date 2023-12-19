# Kriya- Mindfulness in Motion
_This is an internship task for FlexMoney_


## Introduction
This project aims to build an admission form for monthly yoga classes, allowing participants to enroll within certain age limits, select batches, and get notified about payments. The solution involves a frontend form built with React, styled using Tailwind CSS, and a backend implemented in Node.js to handle data storage and validations.

## Database Design
#### Considerations
- Participants must be between 18 to 65 years old
- Fixed at 500/- Rs INR per month
- Participants pay fees on a month-to-month basis, any time within the month.
- Four batches available daily - 6-7AM, 7-8AM, 8-9AM, and 5-6PM.
- Participants can switch batches monthly but remain in the same batch for the entire month.
- Participants can enroll any day of the month but pay for the entire month.
- Once enrolled for the month, no refunds for any partial attendance or withdrawal.
- Each participant has a unique ID.

#### ER Diagram
![image](https://github.com/abhay-8/kriya/assets/104186531/8b0c0839-d7cc-45ee-ab8f-e7a453ca3818)

![image](https://github.com/abhay-8/kriya/assets/104186531/7f4bb862-d21a-4377-815d-c03732755d89)


## Tech Stack
- ReactJS
- NodeJS
- Tailwind CSS

## Approach
- The frontend hosts a form that collects user data and batch preferences. Frontend validation ensures that only valid data is submitted to the backend. Tailwind CSS is employed for styling and responsiveness.
- Both frontend and backend employ validation checks. Frontend validation ensures that only valid data is sent to the backend, enhancing user experience. Backend validation acts as an additional layer of security to filter out incorrect or malicious data.
- Upon form submission, validated data is sent from the frontend to the backend via RESTful API calls. The backend processes this data, acknowledges successful submission, and responds to the frontend. This response is displayed in a modal on the frontend UI, providing feedback to the user.


## Screenshots
#### 1. Registration Page
![image](https://github.com/abhay-8/kriya/assets/104186531/1ebdc25d-def0-4607-b004-18418d03ceb4)

#### 2. Submitting an Erroneous Form- Frontend Validation
![image](https://github.com/abhay-8/kriya/assets/104186531/e85ff053-aa0b-49b5-8903-8b00b0851a35)

#### 3. Successful Registration
![image](https://github.com/abhay-8/kriya/assets/104186531/1ecbc111-c929-42a7-b510-748f780564d2)




