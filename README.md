# Yelp Application Deployment

## Overview

This repository contains the source code for the Yelp application, a ReactJS-based web application that leverages GraphQL. The task is to deploy the application to the cloud using AWS Amplify, with a focus on authentication. The provided instructions include information about Yelp and specify the use of AWS technologies such as Amplify and Lambda.

## Project Structure

- **src**: Contains the source code for the ReactJS application.
- **public**: Houses public assets and HTML file.
- **.gitignore**: Removes the `node_modules/` directory from version control.
- **my_yelp_url.txt**: A file to store the hosted URL after deployment.

## Instructions

Follow the steps below to deploy the Yelp application to the cloud using AWS Amplify:

### Prerequisites

- AWS account
- Amplify CLI installed
- Node.js and npm installed

### Deployment Steps

1. **Clone Repository:**
   ```bash
   git clone https://github.com/your-username/your-yelp-repo.git
   cd your-yelp-repo
   ```

2. **Install Dependencies:**
   ```bash
   npm install
   ```

3. **Edit Configuration:**
   - Navigate to the `src` directory and modify the necessary files (e.g., GraphQL queries, components) to meet deployment requirements.

4. **Amplify Init:**
   ```bash
   amplify init
   ```
   Follow the prompts to initialize the Amplify project.

5. **Amplify Add Authentication:**
   ```bash
   amplify add auth
   ```
   Configure authentication settings as needed.

6. **Amplify Push:**
   ```bash
   amplify push
   ```
   Deploy the changes to the cloud.

7. **Access Deployed Application:**
   After successful deployment, the hosted URL will be available in `my_yelp_url.txt`.

8. **View Application:**
   Open the deployed application in your web browser and explore its features.

9. **Cleanup (Optional):**
   If you wish to remove the deployed resources, you can use:
   ```bash
   amplify delete
   ```

## Additional Information

- The provided code is fully editable to meet deployment requirements.
- Ensure that the necessary AWS credentials are set up on your local machine for successful deployment.
- For any issues or questions, refer to the official AWS Amplify documentation: [AWS Amplify Documentation](https://docs.amplify.aws/)

---

