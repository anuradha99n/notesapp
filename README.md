# Notes App with AWS Amplify and GraphQL

This is a simple and fully functional Notes App built using [AWS Amplify](https://aws.amazon.com/amplify/) and [GraphQL](https://graphql.org/) as per the hands-on tutorial from AWS. The app provides users with the ability to create, read, update, and delete notes, with secure authentication and serverless backend support.

## Project Overview

The Notes App allows users to:

- **Create Notes**: Add new notes to the application.
- **List Notes**: View all the notes saved by the authenticated user.
- **Update Notes**: Edit existing notes.
- **Delete Notes**: Remove notes that are no longer needed.
- **User Authentication**: Secure login and registration powered by AWS Cognito.
- **GraphQL API**: Backend powered by a GraphQL API for performing CRUD operations on notes.
- **Deployment**: The app is deployed using AWS Amplify's hosting service with global distribution and scaling.

## Features

- **Amplify Authentication**: Provides user sign-up, sign-in, and secure access to the application.
- **GraphQL API**: Built using AWS AppSync with auto-generated resolvers for managing notes.
- **DynamoDB Integration**: Serverless NoSQL database to store user notes.
- **S3 Storage**: AWS S3 for optional media or file attachments with notes.
- **CloudFront CDN**: Ensures global delivery of your app with minimal latency.

