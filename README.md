# File Sharing WebApp

File sharing web application that allows users to upload files, view real-time upload progress, and share the file via a unique URL or email. Built using pure HTML, CSS, and JavaScript for the front-end with a Node.js/Express back-end.

## Overview

- **Key Features:**  
  - **Drag & Drop File Upload:** Users can either drag and drop or use a custom “Browse” button to select files.
  - **Live Upload Progress:** A progress bar dynamically updates to reflect the file upload status.
  - **Unique File URL:** Upon successful upload, the system generates a shareable link.
  - **Email Integration:** Users can send the file link directly via email.
  - **Automatic File Deletion:** Files are scheduled for deletion after 24 hours to manage storage.

## Technologies

- **Front-End:**  
  HTML, CSS, JavaScript  
  - Responsive design using Flexbox and CSS transitions.
  - Custom file input with drag-and-drop and progress bar updates.

- **Back-End:**  
  Node.js, Express  
  - File uploads managed via middleware (e.g., Multer).
  - Routes for handling uploads, generating unique URLs, and integrating email services.
  - Automated task scheduling for file deletion.
