CivicLink - AI-Powered Issue Tracking Web Application

License: MIT

CivicLink is a modern, AI-enhanced web application designed to empower communities by providing a platform for reporting, tracking, and resolving local issues. From potholes and broken streetlights to public safety concerns, CivicLink streamlines the process of civic engagement.

✨ Key Features

👤 User Authentication: Secure sign-up and login functionality for citizens.
📝 Issue Reporting: An intuitive form for submitting new issue reports, complete with title, description, image uploads, and precise location marking.
🗺️ Interactive Map View: A dynamic map that visualizes the geographic distribution of all reported issues, providing a clear overview of problem areas in the community.
📋 Real-time Issue Feed: A live-updating feed of all reported issues, allowing users to stay informed about what's happening in their area.
👑 Admin Dashboard: A comprehensive dashboard for municipal administrators to manage, categorize, prioritize, and update the status of reported issues.
🤖 AI-Powered Assistance:
Image-to-Category Suggestions: Automatically suggests an issue category based on user-uploaded images.
Automated Priority Assignment: Intelligently predicts and assigns a priority level (Low, Medium, High) to new reports based on their content.
🚀 Technology Stack

This project is built with a modern, robust, and scalable technology stack.

Core Framework

Next.js (App Router): The foundation of the application, enabling server-centric rendering, file-based routing, and API-less data mutations.
React: The core UI library for building a component-based user interface.
UI & Styling

ShadCN/UI: A collection of beautifully designed, accessible, and customizable UI components.
Tailwind CSS: A utility-first CSS framework for rapid and consistent styling.
Lucide React: A clean and lightweight icon set.
Language

TypeScript: Ensures type safety and improves code quality.
Artificial Intelligence

Genkit (by Google): An open-source framework for building and orchestrating AI-powered features.
Google Gemini: The underlying large language model used for AI tasks.
Backend & Data

Next.js Server Actions: For handling form submissions and data mutations securely on the server.
File-Based Data Storage: A lightweight approach using .json files for data persistence in this prototype.
🧠 AI-Powered Features in Detail

CivicLink leverages Genkit and the Gemini model to provide intelligent assistance:

Image Categorization: When a user uploads an image while reporting an issue, a multi-modal AI model analyzes the image content. It then suggests the most relevant category for the issue (e.g., "Pothole," "Broken Streetlight"), simplifying the reporting process for the user.

Priority Prediction: To help administrators efficiently address the most critical problems, Genkit analyzes the title, description, and category of each new report. Based on this analysis, it predicts the urgency of the issue and automatically assigns a priority level (Low, Medium, or High).

🏁 Getting Started

Prerequisites

Node.js (v20 or later)
npm
Installation

Clone the repository:

git clone https://github.com/Dhruvivakharia/civicsense
Navigate to the project directory:

cd CivicLink
Install dependencies:

npm install
Running the Development Server

To run the application in development mode:

npm run dev
The application will be available at http://localhost:9002.

📜 Available Scripts

npm run dev: Starts the Next.js development server.
npm run build: Builds the application for production.
npm run start: Starts the production server.
npm run lint: Lints the code using Next.js's built-in linter.
npm run typecheck: Runs the TypeScript compiler to check for type errors.
npm run genkit:dev: Starts the Genkit development server.
npm run genkit:watch: Starts the Genkit development server in watch mode.
📁 Project Structure

The project follows a standard Next.js App Router structure:

/
├── src/
│   ├── app/              # Main application pages and layouts
│   ├── components/       # Reusable React components (UI, layout, etc.)
│   ├── lib/              # Utility functions, data fetching, and type definitions
│   ├── ai/               # Genkit flows for AI features
│   └── data/             # JSON files for data storage
├── public/               # Static assets (images, fonts, etc.)
└── package.json          # Project dependencies and scripts
🚀 Deployment

This project is configured for deployment to Google App Engine using the apphosting.yaml file.

🤝 Contributing

Contributions are welcome! Please feel free to open an issue or submit a pull request.

Fork the Project
Create your Feature Branch (git checkout -b feature/AmazingFeature)
Commit your Changes (git commit -m 'Add some AmazingFeature')
Push to the Branch (git push origin feature/AmazingFeature)
Open a Pull Request
📄 License

This project is licensed under the MIT License - see the LICENSE.md file for details (if available).
