# **Taskify: A Trello-Inspired Project Management App**
**Built with:** Next.js, React, TypeScript, Prisma, Supabase, PostgreSQL, Tailwind CSS, Clerk, and Stripe (for optional premium features)

**Live Demo:** [Link to my deployed project](https://taskify-app-virid.vercel.app/)

![Screenshot (225)](https://github.com/RishabhJain2404/taskify-app/assets/127675963/393c1e36-273d-4b22-822d-44eb46973fa1)

## Features:

- **Collaboration:** Organize projects with teammates in dedicated workspaces.
- **Boards & Lists:** Create and manage boards for different project stages. Organize tasks within boards using customizable lists with drag-and-drop functionality.
- **Task Management:** Create, edit, delete, and reorder individual tasks within lists.
- **Visual Appeal:** Enhance your project boards with beautiful cover images powered by the Unsplash API.
- **Activity Tracking:** Maintain transparency with comprehensive activity logs for workspaces and individual boards.
- **Member Roles:** Manage user permissions within workspaces by assigning member roles.
- **Subscription-based Upgrades:** Offer premium features like unlimited boards through Stripe integration.

## Getting Started:

1. **Clone the repository:**

   ```bash
   git clone [https://github.com/](https://github.com/)<your-username>/taskify.git


2. **Install dependencies:**

   ```bash
   cd taskify
   npm install

   
3. **Set Up Environment Variables:**

- Create a .env.local file in the project root.
- Add any environment variables your project requires (e.g., database connection details, API keys).


4. **Run the Development Server:**

    ```bash
    npm start

This will start the development server on `http://localhost:3000` by default.

## Walkthrough:


### 1. Landing Page:

- **Effortless Project Management:** Introducing Taskify, your one-stop app for organizing projects and boosting teamwork.
- **Streamline Workflows:** Create boards, lists, and manage tasks with ease, all in a user-friendly interface.
- **Get Started Now:** Sign up for free and experience the power of organized collaboration.

![Screenshot (225)](https://github.com/RishabhJain2404/taskify-app/assets/127675963/393c1e36-273d-4b22-822d-44eb46973fa1)

### 2. Sign Up/Login:

- Allow users to create new accounts or log in with existing credentials using Clerk.
- Implement secure authentication practices.

### 3. Organization Creation:

- A popup guides users through creating their initial organization upon first sign up.

### 4. Organization Page:

- Displays the organization name and account type (free/pro).
- Sidebar lists all associated workspaces.
- Displays boards within the current organization.
[Image Placeholder for Organization Page]

### 5. Workspaces:

- Provides a central hub for managing projects within the workspace.
- Offers tabs for:
  - **Boards:** Lists all boards associated with the workspace. [Image Placeholder for Workspace Boards Tab]
  - **Activity:** Displays activity logs for the workspace.
  - **Settings:**
    - Allows viewing and managing organization members.
    - Enables inviting new members and managing invitations.
    - Provides options to leave or delete the organization.
  - **Billing:**
    - For free accounts (limited to 5 boards), offers an upgrade option to unlock unlimited boards.
    - For pro accounts, allows managing subscriptions and payment details using Stripe. [Image Placeholder for Workspace Billing Tab]

### 6. Create Board Popup:

- Appears when users create a new board.
- Offers options to select a cover image (powered by Unsplash API) and name the board.

### 7. Board Page:

- Displays the board title, cover image, and associated lists with cards.
- Enables users to:
  - Rename the board title.
  - Delete the board.
  - Create new lists.
  - Create cards within lists.
[Image Placeholder for Board Page]

### 8. List Management:
- Create, copy, or delete lists.
- Drag and drop lists to reorder them.

### 9. Card Management:
- Create cards within a list.
- Delete cards.
- Copy cards for duplication.
- Rename cards.
- Drag and drop cards within a list or across lists.
- View and manage individual card details (description, audit logs).

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
