# Screening Assignment: User Profiling with Browser Fingerprinting

**Overview**

This is a screening assignment for our developer position. The task involves building and deploying a functional web application that leverages browser fingerprinting data and a Large Language Model (LLM) to generate user profiles and present these findings in a deployed environment. The goal is to demonstrate your ability to build, deploy, and present a complete and functional system.

**Background**

Browser fingerprinting allows us to gather information about a user's browser and device configuration. Analyzing this data with LLMs can help infer user characteristics and preferences. This assignment focuses on creating a full-stack application that automates this process, deploys it, and presents the resulting user profiles in a structured, understandable way.

**Task Description**

Develop a web application that:

1.  **Collects** browser fingerprinting data in the frontend using `fingerprintjs/fingerprintjs`.
2.  **Sends** this data to a backend server.
3.  **Analyzes** the data on the backend server using an LLM to generate user profiles.
4.  **Stores** the generated user profiles.
5.  **Presents** the user profile on the frontend in a clear, structured format.
6.  **Deploys** the application to a publicly accessible platform.

The focus is on end-to-end functionality, deployment, and clear presentation of findings.

**Dataset**

For the initial implementation, you can start with a small, pre-generated dataset (e.g., 2-3 profiles generated manually) to ensure the application flow works correctly. However, the final deployed version should be capable of processing *new* fingerprint data collected through the frontend.

**Technical Requirements**

**Core Features**

*   Frontend implementation for browser fingerprinting data collection.
*   Backend API endpoint for receiving and processing fingerprint data.
*   LLM integration for user profile generation.
*   Data storage for generated user profiles.
*   Frontend display of user profiles.
*   Deployment to a publicly accessible platform (e.g., Netlify, Vercel, Heroku, Render).

**Technical Specifications**

*   Frontend Framework: React, Vue.js, or similar. Choose one you are comfortable with.
*   Backend Framework: Node.js (Express), Python (Flask/FastAPI), or similar. Choose one you are comfortable with.
*   Programming Languages: JavaScript/TypeScript and Python (or equivalent).
*   LLM Integration: Utilize a readily available LLM API.
*   Database: SQLite, MongoDB, or a similar lightweight database solution.
*   Deployment Platform: Netlify, Vercel, Heroku, Render, or similar.
*   Data Format: JSON for fingerprint data and profiles.

**Quality Standards**

*   Write clean, well-documented code (frontend and backend).
*   Include comprehensive type hints where appropriate.
*   Follow standard code style guidelines.
*   Clearly document the LLM prompt used for profile generation.
*   Provide clear explanations for any design choices on the frontend.
*   Ensure the deployed application is functional and accessible.
*   Implement basic error handling on both frontend and backend.

**Evaluation Criteria**

*   **Data Collection and LLM Integration (30%)**
    *   Correct implementation of `fingerprintjs/fingerprintjs` data collection on the frontend.
    *   Successful communication between frontend and backend.
    *   Effective prompt design for user profile generation.
    *   Secure handling of API keys.
*   **Backend Functionality (30%)**
    *   Properly structured API endpoint for receiving fingerprint data.
    *   Successful integration with an LLM API.
    *   Functional database for storing user profiles.
    *   Efficient processing of fingerprint data and profile generation.
*   **Frontend Presentation and User Experience (20%)**
    *   Clear and organized presentation of user profiles.
    *   User-friendly interface for initiating fingerprint data collection.
    *   Responsive design that works well on different devices.
*   **Deployment and Functionality (20%)**
    *   Successful deployment to a publicly accessible platform.
    *   The deployed application is functional and able to collect fingerprint data, generate profiles, and display them correctly.
    *   Clear documentation on how to access and use the deployed application.

**Submission Guidelines**

Your submission should be a ZIP file containing:

*   The entire repository (or a git archive).
*   A README.md file with:
    *   Setup instructions for running the application locally.
    *   API configuration steps (LLM API key, database credentials, etc.).
    *   The URL of the deployed application.
    *   Instructions for using the deployed application.
    *   The LLM prompt used for user profile generation.
    *   A description of the chosen deployment platform and any platform-specific configuration steps.
*   A `requirements.txt` (or similar dependency file) listing all Python dependencies.
*   A `package.json` (or similar dependency file) listing all JavaScript dependencies.

**Submission Process**

Send your submission as a compressed ZIP file to info@alphanome.ai

**Important Notes**

*   Implement appropriate rate limiting for all APIs.
*   Securely store and handle API keys (do NOT commit them to the repository). Use environment variables or a similar secure mechanism.
*   Clearly document the prompt used for LLM analysis of the fingerprint data.
*   Focus on creating a functional and deployed application, even if it's a basic implementation.
*   Ethical considerations: Be mindful of the ethical implications of user profiling and data privacy. Include a brief statement discussing these considerations in your README.

**Time Expectation**

The assignment should take approximately 5-10 days to complete. Focus on core functionality and deployment first, then add improvements if time permits.

**Questions?**

If you have any questions about the assignment, please email info@alphanome.ai
