Day 6: Marketplace Deployment and Staging Environment Setup
This document outlines the steps and progress for Day 6: Deployment Preparation and Staging Environment Setup for the marketplace project.



Deployment Setup
1. Hosting Platform Selection
I choose Vercel for hosting because of its seamless integration with Next.js projects.

Platform: Vercel
GitHub Repository: https://github.com/AnoushaBaig/Q2Hackhathon.git 
2. GitHub Repository Integration
The repository was linked to the Vercel project for continuous integration and deployment.
3. Environment Variables
Environment variables required for the project were securely configured in the Vercel dashboard:

NEXT_PUBLIC_SANITY_PROJECT_ID=your_project_id

NEXT_PUBLIC_SANITY_DATASET=production

API_KEY=your_api_key

Deployment Process
Step 1: Configure Vercel Project
Connected GitHub repository to Vercel.
Configured build settings for Next.js.
Step 2: Deploy to Staging Environment
Successfully deployed the application to the staging environment.
URL: https://q2-hackhathon-21ia.vercel.app/
Step 3: Validate Deployment
Verified the app functionality in the staging environment.
Ensured all content fetched correctly from Sanity CMS.
Step 4: Sanity CORS Configuration
To connect Sanity with Vercel, the CORS origin was added to the Sanity dashboard to allow communication between the two platforms.
This configuration ensures that Vercel can securely fetch content from Sanity CMS without encountering any cross-origin issues.