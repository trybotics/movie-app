## Create a small application that supports the following: (complete it in 48 hours (2 days) max)

### User Registration
- User registration should create an OTP request to confirm the account
### User Login - login should use a database of user information to validate the login
- If you are using the AWS standard cognito/IAM registration, please style it differently to mask the normal implementation and include more advanced functionality such as social login with at least one social provider (e.g. gmail or facebook)
### Homepage - the homepage must display something interesting / useful with at least two integrations and should format for larger screen and phone.
- One integration should display the results from an internal database query using a GraphQL API request that is displayed back to the user
- The second integration should be to a third party API that shows you can complete an external integration.
- It would be good to see any 'additional' elements such as a webhook or other real-time response to a change in the application state.
- Well laid out / thought through application components is good too see.
### We want to also see that you can support use of APIs, GraphQL and Lambda functions to make the registration, login and app functional.
### We expect to see some simple / lightweight documentation around the app / code that shows what you intend and how to deploy it.
### The app should be deployed on AWS so we can see it running in the cloud.
### You can use your preferred frameworks, but we want to see evidence of use of our core stack elements:
- React.js
- Node.js
- DynamoDB
- GraphQL
- APIs
- Lambda
- If you use other frameworks / tools, please note them - so we can understand where / how e.g. typescript, bootstrap etc.
  
### Questions to think about
This will test your ability to:
- Think and develop creatively and create a small, but complete application
- Show a range of full stack skills
- Show how you approach problem solving with a bit of 'uncertainty' (i.e. you don't have all the requirements / design).

GO FOR IT!

---

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
