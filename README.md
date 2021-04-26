# Ignews

![Home](./public/home.png)  

![Posts](./public/posts.png)  

![Post](./public/post.png)  

![Post Preview](./public/post-preview.png)  

This project was created for study.
Designed by Rocketseat.

Ignews is a blog that uses integrations with Stripe, Prismic, FaunaDB and Github.
An only frontend application that users can subscribe to read some news using the Stripe payments infrastructure, 
all data are saved using FaunaDB and the posts are created using Prismic CMS.

The code can show:
- NextAuth to authenticate the user using only the Github integration
- API routes to create a "backend" inside the frontend
- The best practices to make the blog accessible search engines and return just part of the content and to the subscribed users the full content
- Many integrations and the best practices to do it using Next.js

### Technologies

- Next.js
- React.Js
- Typescript
- SASS
- Stripe
- Prismic
- FaunaDB

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
