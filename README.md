# Next.js-React-Foundations
 This project demonstrates the core concepts of building a web application with React and Next.js, evolving from vanilla JavaScript/DOM manipulation to a modern Next.js app.

## Project Evolution

1.  **Vanilla JS & DOM:** Started with explicit DOM manipulation methods (`createElement`, `appendChild`).
2.  **React & JSX:** Transitioned to declarative UI with React and JSX.
3.  **Components & Props:** Refactored into reusable functional components (`Header`, `HomePage`) and learned efficient data passing with props.
4.  **Interactivity & State:** Implemented state using the `useState` hook for a dynamic "Like" button.
5.  **Next.js Migration:** Moved off CDN scripts to a local development environment using Next.js.
6.  **Server vs. Client Components:** Solved hydration errors by splitting interactive logic into a separate Client Component (`LikeButton`) marked with `'use client'`, while keeping the main page as a Server Component.

## Getting Started

1.  **Install dependencies:**
    ```bash
    npm install
    ```

2.  **Run the development server:**
    ```bash
    npm run dev
    ```

3.  **View the application:**
    Open [http://localhost:3000](http://localhost:3000) with your browser.

## File Structure

-   `app/page.js`: Main Server Component acting as the homepage.
-   `app/like-button.js`: Client Component handling the interactive "Like" functionality.
-   `app/layout.js`: Root layout definition.


