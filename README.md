# Cloud-Based File Storage Application

The Cloud-Based File Storage application allows users to securely upload, download, and manage their files from any device with internet access. Built with React for the front end, the application integrates Firebase Authentication for secure user login and AWS S3 for scalable file storage. Each user gets a unique folder in the AWS S3 bucket, ensuring data privacy and security. The application uses AWS CloudFront for fast and secure content delivery, providing an optimized user experience globally.


## Features
- Secure File Storage: Each user’s files are stored in dedicated S3 folders.
- User Authentication: Firebase Authentication ensures secure access.
- File Upload/Download: Users can upload and download files to/from their S3 folders.
- File Management: Sort, view, delete, and generate shareable links for files.
- Fast Access: AWS CloudFront provides fast and reliable content delivery.

## Tech Stack
- **Frontend**: React, HTML, CSS
- **Backend**: Firebase Authentication, AWS SDK
- **File Storage**: AWS S3
- **CDN**: AWS CloudFront

## How It Works
1.  User Authentication: Secure login and registration via Firebase Authentication.
2.  File Storage: After login, each user is assigned a unique folder in AWS S3.
3.  File Management: Users can upload, download, and manage their files, with features like sorting, deleting, and generating shareable links.
4.  Content Delivery: AWS CloudFront ensures efficient, secure file access.

## Installation
To run the Cloud-Based File Storage application locally, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/cloud-file-storage.git
2. Navigate into the project directory:
   ```bash
   cd cloud-file-storage
3. Install dependencies: 
   ```bash
   npm install
4. Set up Firebase Authentication:
    - Create a Firebase project and configure authentication.
    - Copy the Firebase configuration to your app.
5. Configure AWS S3.
    - Set up an S3 bucket and configure IAM permissions for file access.
    - Set up AWS CloudFront for CDN.
6. Run the application. By default, the app will run at http://localhost:3000.
    ```bash    
    npm start

## Deployment
The application is deployed on AWS S3 for hosting and uses AWS CloudFront for content delivery.


