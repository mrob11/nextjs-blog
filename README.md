# Next.js + Contentful + Vercel static generated blog application

This is the code from the tutorial series on building a static generated blog
with Next.js, Contentful, and Vercel, available on my blog at
[https://heymike.dev](https://heymike.dev).

The code for each part is available in branches that will be updated as new
parts to the series are released. The master branch will always represent the
current state of the tutorial.

## Articles

- [Part One](https://heymike.dev/post/build-a-static-blog-with-next-js-and-contentful-part-one-contentful)
- [Part Two](https://heymike.dev/post/build-a-static-blog-with-next-js-and-contentful-part-two-next-js)

## Code Branches

- [01-bootstrap-project](https://github.com/mike360/nextjs-blog/tree/01-bootstrap-project)
- [02-fetching-posts-from-contentful](https://github.com/mike360/nextjs-blog/tree/02-fetching-posts-from-contentful)

## Prerequisites

- [Node.js v12](https://nodejs.org)
- [Vercel CLI](https://vercel.com/download) for running `now dev` locally.
- An account with [Contentful](https://contentful.com)

## Setting up this application locally

Clone the repository:

```
git clone https://github.com/mike360/nextjs-blog.git
cd nextjs-blog
npm install
```

Create a local environment variable file `.env`:

```
CONTENTFUL_SPACE_ID=<your space ID here>
CONTENTFUL_ACCESS_TOKEN=<your contentful access token here>
```

Refer to [Part One](https://heymike.dev/post/build-a-static-blog-with-next-js-and-contentful-part-one-contentful)
for setting up Contentful.
