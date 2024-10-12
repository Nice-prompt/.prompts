## Implement Tanstack Mutations

As a Tanstack Query expert, implement mutations for our application using the latest version of Tanstack Query (React Query). Cover the following cases and best practices:

1. Basic Mutation:
   - Create a simple mutation to add a new item to a list.
   - Implement proper error handling and loading states.
   - Show how to use the mutation in a React component.

2. Optimistic Updates:
   - Implement a mutation with optimistic updates for instant UI feedback.
   - Handle rollback in case of failure.
   - Demonstrate how to update the cache optimistically.

3. Invalidation and Refetching:
   - Create a mutation that invalidates and refetches related queries upon success.
   - Show how to use `queryClient.invalidateQueries()` effectively.

4. Complex Mutation with Variables:
   - Implement a mutation that takes multiple variables (e.g., updating user profile).
   - Demonstrate how to pass and use these variables in the mutation function.

5. File Upload Mutation:
   - Create a mutation for file uploads, showing how to handle multipart/form-data.
   - Implement progress tracking for the upload.

6. Mutation with Side Effects:
   - Implement a mutation that performs additional side effects upon success (e.g., showing a toast notification, navigating to a different page).

7. Batch Mutations:
   - Demonstrate how to perform multiple mutations in sequence or parallel.
   - Handle dependencies between mutations if necessary.

8. Retry Logic:
   - Implement custom retry logic for failed mutations.
   - Show how to configure retry attempts and intervals.

9. Cancellation:
   - Create a mutation that can be cancelled mid-flight.
   - Demonstrate proper cleanup and state management for cancelled mutations.

10. Global Mutation Settings:
    - Show how to configure global settings for mutations in the QueryClient.
    - Implement default error handling or success callbacks.

11. TypeScript Integration:
    - Ensure all mutation implementations use proper TypeScript types.
    - Demonstrate type inference and custom type definitions for mutation results and variables.

12. Testing Mutations:
    - Write unit tests for a mutation, including mocking the API call.
    - Show how to test different mutation states (loading, success, error).

For each case, provide:
- A brief explanation of the use case and its importance.
- The implementation code, including the mutation definition and its usage in a component.
- Any necessary TypeScript interfaces or types.
- Best practices and potential pitfalls to avoid.
- How to integrate with Tanstack Query DevTools for debugging.

Use the latest Tanstack Query syntax and hooks, and ensure all code follows React and TypeScript best practices. Provide comments where necessary to explain complex logic or important concepts.