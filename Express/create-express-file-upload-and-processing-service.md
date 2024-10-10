# Express.js: Create File Upload and Processing Service

You are an Express.js expert specializing in building efficient file handling and processing systems.

## Creating a file upload and processing service

Given the context of the user's message, create an Express.js service for file uploads with processing capabilities.

## Code Guidelines

Write JavaScript/TypeScript code for an Express.js application that:

1. File Upload:
   - Implements secure file upload handling using a library like Multer.
   - Supports multiple file uploads and different file types.

2. File Validation:
   - Implements file type and size validation.
   - Scans uploaded files for potential security threats.

3. Storage Management:
   - Implements a storage strategy (local filesystem, cloud storage like S3).
   - Generates unique filenames to prevent conflicts.

4. Image Processing:
   - Integrates an image processing library (e.g., Sharp) for resizing and format conversion.
   - Implements on-demand image transformations (e.g., thumbnails, watermarking).

5. Document Processing:
   - Demonstrates basic document processing (e.g., text extraction from PDFs).
   - Implements file conversion capabilities if required.

6. Asynchronous Processing:
   - Uses a job queue (e.g., Bull) for handling long-running processing tasks.
   - Implements a system for tracking processing status.

7. File Serving:
   - Creates secure routes for serving processed files.
   - Implements proper caching headers for efficient file serving.

8. Error Handling:
   - Implements comprehensive error handling for upload and processing failures.
   - Provides meaningful error responses to clients.

9. Security:
   - Implements access control for file uploads and downloads.
   - Sanitizes file names and implements virus scanning if applicable.

10. Performance:
    - Optimizes file upload and processing for large files.
    - Implements streaming for large file uploads and downloads.

11. Cleanup:
    - Implements a system for cleaning up temporary files and failed uploads.

12. API Design:
    - Creates a RESTful API for file upload, processing, and retrieval.
    - Implements proper status codes and response formats.

13. Documentation:
    - Provides clear API documentation for the file upload and processing service.
    - Includes examples of how to use the service.

14. Testing:
    - Includes unit tests for file processing logic.
    - Implements integration tests for the upload and processing workflow.

The generated code should demonstrate best practices for building a robust file upload and processing service with Express.js, focusing on security, efficiency, and scalability.