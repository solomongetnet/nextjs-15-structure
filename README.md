# Next.js 15 Full-Stack Starter with Tailwind CSS and ShadCN UI

Welcome to the **Next.js 15 Full-Stack Starter** project! This template is pre-configured with **Tailwind CSS** for styling, **ShadCN UI** for UI components, and is designed for full-stack development with Next.js. It comes with everything you need to build modern web applications, both on the client and server sides.

## Features
- **Tailwind CSS**: Utility-first CSS framework for fast styling and layout.
- **ShadCN UI**: A collection of customizable UI components for your application.
- **
</br>

## Project Structure

### 1. **`📁src`**: The root directory for your source code, which houses all the other subdirectories.

### 2. **`📁app`**: Contains the main application structure.

- **`📁(client)`**: Client-facing pages and components.
  - **`📁(home)`**: Contains the homepage.
    - `page.tsx`: The main page of your application.
  - **`📁about`**: About page.
    - `page.tsx`: About page content.
  - **`📁contact`**: Contact page.
    - `page.tsx`: Contact form and details.

- **`📁admin`**: Admin-specific pages and logic.
  - **`📁dashboard`**: Dashboard page for administrators.
    - `page.tsx`: Contains the dashboard layout and content.
  - **`📁settings`**: Settings page for the admin section.
    - `page.tsx`: Handles configuration and settings.

- **`📁api`**: API routes for your application (potential for server-side logic).
- **`error.tsx`**: Global error handling or custom error pages.
- **`layout.tsx`**: Global layout used across the app.
- **`not-found.tsx`**: Custom "not found" error page.

### 3. **`📁assets`**: Static assets like images and styles.
- **`📁images`**: Store images or icons here.
- **`📁styles`**: Contains global styles.
  - `globals.css`: Your global CSS styles.

### 4. **`📁components`**: All your React components for both client and admin sections.

- **`📁admin`**: Components specific to the admin area.
  - **`📁footer`**: Admin footer component.
    - `footer.tsx`: The footer for the admin section.
  - **`📁sidebar`**: Sidebar component for the admin dashboard.
    - `sidebar.tsx`: Contains the sidebar layout for the admin section.

- **`📁client`**: Components for the client-facing site.
  - **`📁footer`**: Client footer component.
    - `footer.tsx`: The footer for the client-facing website.
  - **`📁header`**: Client header component.
    - `header.tsx`: The header for the client-facing website.

- **`📁ui`**: ShadCn reusable UI components.
  - `button.tsx`: A ShadCn button component.

### 5. **`📁hooks`**: Custom React hooks for managing logic throughout the app.

### 6. **`📁interface`**: TypeScript interfaces or types for your application’s structure.

### 7. **`📁lib`**: Utility functions and libraries.
- **`utils.ts`**: A file for common utility functions.

### 8. **`middleware.ts`**: Middlewares for handling things like authentication or request filtering.

### 9. **`📁providers`**: Context providers or state management providers.
- **`tanstack.provider.tsx`**: Provider for integrating TanStack (previously React Query) in your app.

### 10. **`📁server`**: Server-side logic and actions.
- **`📁actions`**: Server actions related to business logic or API interactions.
- **`📁config`**: Configuration files for the server, including environment variables.
- **`📁helper`**: Helper functions for server-side operations.

### 11. **`📁utils`**: Any additional utility files or functions.

---

## Getting Started
To get started with this template, follow the steps below:

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/solomongetnet/nextjs-15-starter.git
    ```

2. **Install Dependencies**:
    Navigate to the project directory and install the required packages:
    ```bash
    npm install
    ```

3. **Run the Development Server**:
    Start the development server:
    ```bash
    npm run dev
    ```

4. **Visit the App**:
    Open your browser and go to `http://localhost:3000`.