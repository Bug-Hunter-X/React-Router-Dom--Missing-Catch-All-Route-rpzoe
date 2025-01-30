# React Router Dom: Missing Catch-All Route
This example demonstrates an uncommon error in React Router Dom v6 and above related to missing catch-all routes.  Without a catch-all route, unexpected behavior can occur when navigating to a non-existent path.

## Problem

The `App.js` file is missing a catch-all route (`/*`). This means that if a user tries to navigate to a route that doesn't explicitly exist (e.g., `/invalid-route`), the application will either show nothing, or if strict mode is enabled may throw an error.

## Solution

The `AppSolution.js` file demonstrates how to add a catch-all route that will handle any unexpected route. This provides a better user experience and prevents potential errors.
