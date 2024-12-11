# React Router v6 Catch-All Route Conflict

This repository demonstrates a common issue encountered when using catch-all routes (`/*`) in React Router v6.  The problem arises when the catch-all route is placed before other routes, preventing those routes from being matched correctly.  The solution involves simply reordering the routes within the `<Routes>` component.