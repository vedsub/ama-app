Anonymous Messaging App


Welcome to the Anonymous Messaging App, an application designed to facilitate secure, anonymous communication between users. This project is built using Next.js, TypeScript, MongoDB, and integrates Google Generative AI APIs for generating messages.

Features




Anonymous Messaging: Users can send and receive messages without revealing their identity.
Secure Authentication: Secure user sessions with JWT and NextAuth.
Schema Validation: Ensures data integrity using Zod for schema validation.
Database: MongoDB for efficient and scalable data storage.
Generative AI: Integration with Vercel SDK AI APIs to enhance messaging capabilities.


Technologies Used



Next.js: A React framework for building server-side rendering and static web applications.
TypeScript: A statically typed superset of JavaScript.
MongoDB: A NoSQL database for storing messages and user data.
JWT: JSON Web Tokens for secure authentication.
NextAuth: Authentication for Next.js applications.
Zod: TypeScript-first schema declaration and validation library.
Google Generative AI APIs: Used to generate messages.
Installation
To run this project locally, follow these steps:

Clone the repository:

git clone https://github.com/your-username/ama-app.git
cd ama-app


Install dependencies:

npm install
Set up environment variables:

Create a .env file in the root of the project and add the following environment variables:

NEXTAUTH_SECRET=""
MONGODB_URI=""
RESEND_API_KEY=""
OPENAI_API_KEY=""
Run the development server:

npm run dev
Open http://localhost:3000 in your browser to see the application in action.

Usage
Sign Up / Log In: Users can sign up or log in using their credentials.
Send Messages: Users can send anonymous messages to other users.
Receive Messages: Users can view messages sent to them anonymously.
AI-Generated Messages: Utilize the Open ai Generative AI API of Vercel to generate messages.
