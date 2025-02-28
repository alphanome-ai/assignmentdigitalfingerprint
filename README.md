# Screening Assignment: User Profiling with Browser Fingerprinting using Reflex

**Overview**

This is a screening assignment for our developer position. The task involves building and deploying a functional web application using **Reflex** that leverages browser fingerprinting data and a Large Language Model (LLM) to generate user profiles and present these findings in a deployed environment. The goal is to demonstrate your ability to build, deploy, and present a complete and functional system with Reflex.

**Background**

Browser fingerprinting allows us to gather information about a user's browser and device configuration. Analyzing this data with LLMs can help infer user characteristics and preferences. This assignment focuses on creating a full-stack application with Reflex that automates this process, deploys it, and presents the resulting user profiles in a structured, understandable way.

**Task Description**

Develop a web application using **Reflex** that:

1.  **Collects** browser fingerprinting data in the frontend using `fingerprintjs/fingerprintjs`. You'll need to find a way to integrate this with Reflex components, possibly using JavaScript interop.
2.  **Sends** this data to a Reflex state variable.
3.  **Analyzes** the data using a Python backend (within Reflex or a separate API) and an LLM to generate user profiles.
4.  **Stores** the generated user profiles (within Reflex state or an external database).
5.  **Presents** the user profile on the frontend in a clear, structured format, built with Reflex components.
6.  **Deploys** the application to a publicly accessible platform.

The focus is on end-to-end functionality, deployment, and clear presentation of findings, all within the Reflex framework.

**Technical Requirements**

**Core Features**

*   Frontend implementation for browser fingerprinting data collection using `fingerprintjs/fingerprintjs` integrated with Reflex.
*   Backend functionality for receiving and processing fingerprint data within Reflex or a separate API.
*   LLM integration for user profile generation.
*   Data storage for generated user profiles (Reflex state or external database).
*   Frontend display of user profiles using Reflex components.
*   Deployment to a publicly accessible platform (e.g., Netlify, Vercel, Heroku, Render).

**Technical Specifications**

*   Frontend Framework: **Reflex**.
*   Backend Language: Python (within Reflex).
*   LLM Integration: Utilize a readily available LLM API.
*   Data Storage: Reflex state or SQLite, MongoDB, or a similar lightweight database solution.
*   Deployment Platform: Netlify, Vercel, Heroku, Render, or similar.
*   Data Format: JSON for fingerprint data and profiles.

**Quality Standards**

*   Write clean, well-documented Reflex code.
*   Utilize Reflex state management effectively.
*   Clearly document the LLM prompt used for profile generation.
*   Provide clear explanations for any design choices on the frontend.
*   Ensure the deployed application is functional and accessible.
*   Implement basic error handling on both frontend and backend (within Reflex, where applicable).

**Evaluation Criteria**

*   **Data Collection and LLM Integration (30%)**
    *   Correct integration of `fingerprintjs/fingerprintjs` data collection on the frontend within the Reflex framework.
    *   Successful data transfer to the backend (Reflex state or API).
    *   Effective prompt design for user profile generation.
    *   Secure handling of API keys.
*   **Reflex Backend Functionality (30%)**
    *   Properly structured Reflex state and event handlers for receiving fingerprint data.
    *   Successful integration with an LLM API (within Reflex or a separate API).
    *   Functional data storage (Reflex state or external database).
    *   Efficient processing of fingerprint data and profile generation.
*   **Frontend Presentation and User Experience (20%)**
    *   Clear and organized presentation of user profiles using Reflex components.
    *   User-friendly interface for initiating fingerprint data collection.
    *   Responsive design that works well on different devices.
*   **Deployment and Functionality (20%)**
    *   Successful deployment to a publicly accessible platform.
    *   The deployed application is functional and able to collect fingerprint data, generate profiles, and display them correctly using Reflex.
    *   Clear documentation on how to access and use the deployed application.

**Submission Guidelines**

Your submission should be a ZIP file containing:

*   The entire repository (or a git archive).
*   A README.md file with:
    *   Setup instructions for running the application locally (using Reflex).
    *   API configuration steps (LLM API key, database credentials, etc.).
    *   The URL of the deployed application.
    *   Instructions for using the deployed application.
    *   The LLM prompt used for user profile generation.
    *   A description of the chosen deployment platform and any platform-specific configuration steps.
    *   Details on how you integrated `fingerprintjs/fingerprintjs` with Reflex.
*   A `requirements.txt` listing all Python dependencies.
*   A `pyproject.toml` or `poetry.lock` file if you're using Poetry for dependency management with Reflex.

**Submission Process**

Send your submission as a compressed ZIP file to info@alphanome.ai

**Important Notes**

*   Implement appropriate rate limiting for all APIs.
*   Securely store and handle API keys (do NOT commit them to the repository). Use environment variables or a similar secure mechanism.
*   Clearly document the prompt used for LLM analysis of the fingerprint data.
*   Focus on creating a functional and deployed application using Reflex, even if it's a basic implementation.
*   Integrating external JavaScript libraries like `fingerprintjs/fingerprintjs` into Reflex will likely require using `rx.js_code` to execute JavaScript code. Be sure to document how you handle this.
*   Ethical considerations: Be mindful of the ethical implications of user profiling and data privacy. Include a brief statement discussing these considerations in your README.

**Time Expectation**

The assignment should take approximately 5-10 days to complete. Focus on core functionality and deployment using Reflex first, then add improvements if time permits. Pay special attention to the Reflex-specific aspects of the implementation.

**Questions?**

If you have any questions about the assignment, please email info@alphanome.ai
