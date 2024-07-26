# Mystery Message

**Mystery Message** is an anonymous messaging platform designed to facilitate secure and private communication. Users can provide feedback, send messages anonymously, and utilize AI-powered message suggestions. The platform also features a comprehensive dashboard for managing messages and feedback.

## Features

- **Anonymous Messaging:** Send and receive messages anonymously.
- **Secure Authentication:** Use NextAuth.js for secure login and registration.
- **AI-Powered Suggestions:** Get intelligent message suggestions from OpenAI.
- **Dashboard Management:** View, accept, and manage messages via a user-friendly dashboard.
- **Feedback System:** Provide feedback anonymously.
- **Public Messages:** Display public messages on a responsive landing page.

## Tech Stack

- **Frontend:** Next.js, TypeScript
- **Backend:** MongoDB, NextAuth.js
- **APIs & Libraries:** Resend (for OTP verification), Zod (for validation), OpenAI (for AI-based suggestions)

## Getting Started

To get started with the project locally:

### Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/) 
- [MongoDB](https://www.mongodb.com/)

### Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/reetjain01/Mystery-Message.git
    cd Mystery-Message
    ```

2. **Install dependencies:**

    ```bash
    npm install
    ```

3. **Set up environment variables:**

    Create a `.env` file in the root directory and add the following variables:

    ```env
    MONGODB_URI=your-mongodb-atlas-url
    NEXTAUTH_SECRET=your-nextauth-secret
    RESEND_API_KEY=your-resend-api-key
    OPENAI_API_KEY=your-openai-api-key
    ```

4. **Run the development server:**

    ```bash
    npm run dev
    ```

    Open [http://localhost:3000](http://localhost:3000) in your browser to see the application in action.

## Usage

- **Login/Signup:** Navigate to the login/register page and authenticate using NextAuth.js.
- **OTP Verification:** Verify your account using OTP sent via email (powered by Resend).
- **Anonymous Messaging:** Send messages and provide feedback anonymously.
- **Dashboard:** Manage your messages and view public messages through your personalized dashboard.
- **AI Suggestions:** Get suggested messages using the AI functionality.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.


## Contact

For any inquiries or feedback, please contact:

- **Email:** [jainreet112@gmail.com](mailto:jainreet112@gmail.com)

