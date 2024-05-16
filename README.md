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

![Screenshot (226)](https://github.com/RishabhJain2404/taskify-app/assets/127675963/c9dc786b-db60-42b3-abcf-92f5f3f6d8cd)

### 3. Organization Creation:

- A popup guides users through creating their initial organization upon first sign up or whenever user wants to create one.

![Screenshot (227)](https://github.com/RishabhJain2404/taskify-app/assets/127675963/e75c2e8b-99fb-468d-9b4c-f38ef27733b2)

### 4. Organization Page:

- Displays the organization name and account type (free/pro).
- Sidebar lists all associated workspaces.
- Displays boards within the current organization.

![org page](https://github.com/RishabhJain2404/taskify-app/assets/127675963/513fd907-ed6a-4fa4-90e1-045639465513)

### 5. Workspaces:

- Provides a central hub for managing projects within the workspace.
- Offers tabs for:
  - **Boards:** Lists all boards associated with the workspace. ![Screenshot (230)](https://github.com/RishabhJain2404/taskify-app/assets/127675963/8decdae6-6f5f-4bcf-80b9-e65a661284ae)
  - **Activity:** Displays activity logs for the workspace. ![Screenshot (231)](https://github.com/RishabhJain2404/taskify-app/assets/127675963/e2897a41-3aa1-4391-a63b-8c08d9646dd3)
  - **Settings:**
    - Allows viewing and managing organization members.
    - Enables inviting new members and managing invitations.
    - Provides options to leave or delete the organization. ![Screenshot (232)](https://github.com/RishabhJain2404/taskify-app/assets/127675963/6df5d521-9b70-4f37-b531-64f37149074a)
  - **Billing:**
    - For free accounts (limited to 5 boards), offers an upgrade option to unlock unlimited boards.
    - For pro accounts, allows managing subscriptions and payment details using Stripe. ![Screenshot (233)](https://github.com/RishabhJain2404/taskify-app/assets/127675963/bebb08a6-f694-42b2-adcb-077bea202dfb)

### 6. Create Board Popup:

- Appears when users create a new board.
- Offers options to select a cover image (powered by Unsplash API) and name the board.

![Screenshot (234)](https://github.com/RishabhJain2404/taskify-app/assets/127675963/f64e631d-a0de-4ee7-b763-67fd0b1d87a0)

### 7. Board Page:

- Displays the board title, cover image, and associated lists with cards.
- Enables users to:
  - Rename the board title.
  - Delete the board.
  - Create new lists.
  - Create cards within lists.

![Screenshot (235)](https://github.com/RishabhJain2404/taskify-app/assets/127675963/f55ca24b-9585-470a-83d8-e13c7f2be057)

### 8. List Management:
- Create, copy, or delete lists.
- Drag and drop lists to reorder them.

![Screenshot (236)](https://github.com/RishabhJain2404/taskify-app/assets/127675963/f7aed1ec-4de1-4e9f-b45a-7fc5567db5ea)

### 9. Card Management:
- Create cards within a list.
- Delete cards.
- Copy cards for duplication.
- Rename cards.
- Drag and drop cards within a list or across lists.
- View and manage individual card details (description, audit logs).

![Screenshot (237)](https://github.com/RishabhJain2404/taskify-app/assets/127675963/69ad7c92-bc07-4a26-a6e1-ab68b4889390)

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
