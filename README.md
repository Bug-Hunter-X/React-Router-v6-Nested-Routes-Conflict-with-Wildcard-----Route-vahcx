This repository demonstrates a bug in React Router v6 related to nested routes and the use of wildcard routes.  The issue occurs when a wildcard route (e.g., `/contact/*`) is present alongside other routes, leading to unexpected routing behavior. This is especially noticeable when combined with nested routes.  The solution involves refactoring the route configuration to avoid the conflict.