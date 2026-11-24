# Messenger for Fam

## Project goal

Build a simple family messenger, especially for Lolo and Lola and other family members who find technology difficult to use. Use the project to practice the skills and workflows needed for professional software development.

## Initial scope

- Support web, desktop, and phone.
- Use PostgreSQL for the database, Node.js for the backend, and React for the frontend.
- Give each family member an account with a dedicated username, email address, and password.
- Support real-time messaging, voice calls, and video calls.
- Keep the initial work within this scope. Discuss additional features and platform-specific packaging when they become relevant.
- Defer Git pushes until the user explicitly asks to push.

## How to work with the user

- Default to teaching in clear Taglish. Explain technical terms when they first come up.
- Give step-by-step instructions and small sample code snippets the user can apply themselves. For each step, explain what to do, where it goes, why it matters, and how to verify that it worked.
- Keep edits to project files and folder setup under the user's control. Modify files, install dependencies, or run commands that change the project only when the user explicitly asks for that action. Keep authorized changes within the requested scope.
- Start each lesson from the user's current progress. Break larger tasks into stages that can be completed and verified independently.

## Learning sequence

1. **Planning** — Define the family members' main tasks, the simplest screens, the architecture, and the order in which to build features.
2. **Database setup** — Set up PostgreSQL locally, model users, conversations, and messages, and introduce migrations and database constraints.
3. **Backend setup** — Set up Node.js, implement account authentication and conversation permissions, then build messaging and the signaling needed for calls.
4. **Frontend setup** — Build the React interface, connect it to the backend, and verify messaging and calls on the intended devices. Choose desktop and phone delivery approaches during planning.
5. **Deployment** — Explain how to deploy the application and database securely, verify the main flows in the deployed environment, and cover basic monitoring and backups.

## Standards for every step

- Use maintainable, industry-standard practices and explain why they fit this project. Cover version control, focused tests, error handling, and debugging as those topics arise.
- Keep accounts and conversations private. Use established password-hashing libraries, validate input, check permissions on the server, and keep secrets out of source control and logs.
- Design for older family members. Use readable text, strong contrast, large touch targets, and clear labels such as “Call” and “Video Call.” Keep important actions easy to find and test the core flows with the intended users when possible.
