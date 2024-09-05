# MedConnect - Patient Management System

## Overview

MedConnect is a comprehensive patient management system designed to streamline healthcare operations. It provides an efficient way for healthcare providers to manage patient information, appointments, and medical records.

## Features

- User Authentication
- Patient Registration
- Appointment Scheduling
- Medical Record Management
- Doctor Management

## Tech Stack

- Next.js
- TypeScript
- Tailwind CSS
- Appwrite (Backend as a Service)

## Getting Started

### Prerequisites

- Node.js (v14 or later)
- npm or yarn
- Appwrite account and project set up

### Installation

1. Clone the repository:

   ```
   git clone https://github.com/your-username/medconnect.git
   cd medconnect
   ```

2. Install dependencies:

   ```
   npm install
   ```

3. Set up environment variables:
   Create a `.env.local` file in the root directory and add the following variables:

   ```
   PROJECT_ID=your_project_id
   API_KEY=your_api_key
   DATABASE_ID=your_database_id
   PATIENT_COLLECTION_ID=your_patient_collection_id
   DOCTOR_COLLECTION_ID=your_doctor_collection_id
   APPOINTMENT_COLLECTION_ID=your_appointment_collection_id
   NEXT_PUBLIC_BUCKET_ID=your_bucket_id
   NEXT_PUBLIC_ENDPOINT=your_appwrite_endpoint
   ```

4. Run the development server:

   ```
   npm run dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.

## Project Structure

- `lib/`: Contains utility functions and API calls
- `components/`: Reusable React components
- `pages/`: Next.js pages and API routes
- `styles/`: Global styles and Tailwind CSS configuration

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.
