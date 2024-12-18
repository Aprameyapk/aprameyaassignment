This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

Problem Statement
Create a user-friendly Login Page using Next.js that validates user input for email and password. The page should provide feedback for missing fields and support smooth interactions.

Approach
Framework Used: Next.js (App Router)
Features:
User input validation (email and password).
Error handling for empty fields.
Responsive design using CSS Modules.
Styling: CSS Modules (Login.module.css) for modular, scoped styles.
State Management: React hooks (useState).
Requirements
Node.js (>= 16.x)
npm (>= 7.x) or yarn
Install Dependencies
bash
Copy code
npm install
Run the Project
Start the development server:
bash
Copy code
npm run dev
Open http://localhost:3000 in your browser.
File Structure
plaintext
Copy code
├── app/
│   ├── page.js        # Login Page Component
├── styles/
│   ├── Login.module.css  # Styling for Login Page
├── package.json
└── README.md
How to Use
Email Field: Enter a valid email address.
Password Field: Enter your password.
Submit the form and view the console for the output.
![alt text](<Screenshot 2024-12-18 at 9.43.40 AM.png>)