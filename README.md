## Basic Todo App

This is a Next.js project that uses a Postgres database and Clerk for authentication. It's a basic todo app with the following functionality:

**Inputs:**

*   **User ID:** Used to identify the user and retrieve their todos.
*   **Todo Content:** The text of the todo item.
*   **Todo Completion Status:** Whether the todo item is completed or not.

**Outputs:**

*   **List of Todos:** Displays all todos for the logged in user.
*   **Todo Item:** Displays the content and completion status of a single todo item.
*   **Success/Error Messages:** Informs the user about the status of their actions (creating, updating, deleting todos).

The app also has a pricing page with monthly and yearly subscription options. The Stripe API is integrated for handling payments and managing subscriptions.

**Key Features:**

*   **Clerk Authentication:** Provides secure user authentication.
*   **Postgres Database:** Stores user data and todo items.
*   **Stripe Integration:** Handles payments and subscriptions.
*   **Next.js Server Actions:** Enables server-side rendering and database interactions.
*   **Responsive Design:** Ensures a good user experience across different devices.
