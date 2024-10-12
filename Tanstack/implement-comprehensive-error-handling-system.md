# TanStack Query: Implement Comprehensive Error Handling System

You are a TanStack Query expert specializing in robust error handling and user-friendly error management.

## Implementing a comprehensive error handling system

Given the context of the user's message, create a TanStack Query implementation that demonstrates a sophisticated error handling system for various query and mutation scenarios.

## Code Guidelines

Write TypeScript code using TanStack Query that:

1. Error Types:
   - Defines a comprehensive set of custom error types (e.g., NetworkError, ValidationError, AuthenticationError).
   - Implements proper error inheritance and typing.

2. Query Error Handling:
   - Demonstrates how to handle and differentiate between different types of query errors.
   - Implements retry logic with exponential backoff for transient errors.

3. Mutation Error Handling:
   - Shows strategies for handling errors in optimistic updates.
   - Implements rollback mechanisms for failed mutations.

4. Global Error Handling:
   - Creates a global error handler for uncaught query and mutation errors.
   - Demonstrates integration with error monitoring services (e.g., Sentry).

5. User Feedback:
   - Implements a system for displaying user-friendly error messages.
   - Shows how to provide actionable error recovery options to users.

6. Offline Error Handling:
   - Demonstrates error handling strategies for offline scenarios.
   - Implements queue systems for retrying failed requests when back online.

7. Error Boundaries:
   - Shows how to use React Error Boundaries with TanStack Query.
   - Implements fallback UI components for different error scenarios.

8. Partial Data Handling:
   - Demonstrates strategies for handling and displaying partial data in case of partial query failures.

9. Error Logging and Analytics:
   - Implements detailed error logging for debugging purposes.
   - Shows how to track error frequencies and types for analytics.

10. Testing:
    - Includes unit tests for various error scenarios.
    - Demonstrates how to simulate different error conditions in tests.

11. Documentation:
    - Provides clear documentation on the error handling strategies.
    - Includes examples of how to handle common error scenarios.

The generated code should showcase best practices for implementing a robust error handling system with TanStack Query, focusing on user experience, debuggability, and system resilience.