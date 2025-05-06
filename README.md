# Stockify Vercel Deploymnet

I used vercel to deploy this project as that is what our team is currently focusing on. 

## Vercel.json

This is not a neccesarry part for the deployment as vercel itself gives the option to do it on their website. However, for you to see the settings that I put, this is included.
It shows basic deployment settings: The root folder is frontend/ and that the framework used is next.js. This helps vercel know how to build the app, as well as give is instructions
to what the source of the page should be

## Github Secrets

Git hub secrets were created for the token, projectID, and userID

## Martin_Vercel_Deployment.yml 

This file is for automated deployment. It helps vercel know when pushes are made so that the site can update along with the changes rather than having to deploy a new version everytime. It also helps with testing purposes. 

## Backend
This project uses Supabase as the backend service. Supabase provides:
- Authentication
- Database
- Real-time subscriptions
- Storage
- Edge Functions

## Testing Setup

This project uses:
- Frontend: Jest + React Testing Library
- Continuous Integration via GitHub Actions

### Quick Start

```bash
# Frontend Tests
cd frontend
npm test

# Run tests in watch mode
npm run test:watch
```

For detailed testing information, see [TESTING.md](TESTING.md)

# Install the new dependencies
npm install

# Run tests once
npm test

# Run tests in watch mode
npm run test:watch

#jhp3RDrXH12RdXeoHjADYNDd


