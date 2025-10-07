# Introduction to React Router

## Question
What is React Router and why is it important in React applications?
-Emmanuel

## Answer
React Router is a standard library for routing in React. It enables navigation between different components or pages in a single-page application (SPA) without reloading the entire page. This improves user experience by making transitions faster and smoother.
-Emmanuel

# Core Router Components

## Question
What are the core components of React Router and how do they work together to enable navigation in a React app?
-Emmanuel

## Answer
React Router provides several key components that work together to manage navigation in single-page React applications like BrowserRouter, Routes, Route, Link, NavLink, and many more. Together, these components allow developers to build seamless, dynamic navigation experiences in React apps without full page reloads.
-Emmanuel


# Navigation Techniques

## Question
What are the main navigation techniques in React Router, and when should you use each one?
-Emmanuel

## Answer
React Router offers two primary navigation techniques: declarative and imperative navigation.
Declarative Navigation
- Uses components like <Link> and <NavLink> to define navigation in JSX.
- Ideal for menus, buttons, and static links.
 Imperative Navigation
- Uses the useNavigate() hook to programmatically change routes.
- Ideal for redirects after actions like form submissions or authentication.
Both techniques work seamlessly with <Routes> and <Route> to render the correct component based on the URL. Choosing the right one depends on whether the navigation is user-driven or logic-driven.
-Emmanuel

# Dynamic Routes & Parameters

## Question
What are dynamic routes and URL parameters in React Router, and how do they enhance navigation in single-page applications?
-Emmanuel

## Answer
Dynamic routes in React Router allow you to define paths that include variable segments, making your app more flexible and data-driven. These segments are called URL parameters, and they’re commonly used to display content based on user-specific or item-specific data.
-Emmanuel

# Nested Routes & Layouts

## Question
What are nested routes and layouts in React Router, and how do they help structure complex applications?
-Emmanuel

## Answer
-Nested routes in React Router allow you to define routes inside other routes, enabling hierarchical navigation and shared layouts across multiple pages.Nested routes and layouts are essential for building scalable, professional-grade apps—especially when your app has sections like dashboards, profiles, or admin panels.
-Emmanuel