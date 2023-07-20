# My Headless Blog with sanity.io, GitHub, Vercel, and Workflows

[The Blog - Frontend](https://sanity.cdaprod.dev)

## Introduction

In this project, I developed a headless blog using sanity.io as a content backend, GitHub for source code versioning, Vercel for deployment, and workflows for continuous integration and deployment.

## Architecture

1. **Sanity.io** - Acts as the content backend, where I create and manage the blog content.
2. **GitHub** - Houses the codebase for the frontend, ensuring version control and collaboration.
3. **Vercel** - Used for automatic deployments, thanks to its seamless integration with GitHub.
4. **Workflows** - Automate various tasks, from code linting and testing to deployment.

## Development Steps

### 1. Setting Up sanity.io

- Initiated a new Sanity project with `sanity init`.
- Created necessary schemas for the blog, e.g., `post`, `author`, and `category`.
- Populated content and made sure the studio is running as expected.

### 2. GitHub Repository Setup

- Initialized a new repository on GitHub.
- Cloned the repository locally and added the frontend codebase (Next.js or any other preferred framework).

### 3. Integrating with Vercel

- Connected my GitHub repository with Vercel for automatic deployments.
- Set up environment variables, like Sanity dataset tokens, on Vercel to securely connect to the Sanity project.

### 4. Developing the Frontend

- Utilized `@sanity/client` to fetch data from Sanity in real-time.
- Implemented dynamic routing for blog posts.
- Designed and styled the components and pages for a cohesive user experience.

### 5. Implementing Workflows

- Created workflows using GitHub Actions or Vercel's in-built tools.
- Implemented continuous integration: Running tests, linting, and building every time code is pushed.
- Enabled continuous deployment: Every push to the main branch triggers an automatic deployment to Vercel.

## Deployment

Each time changes are made:
1. Pushed changes to GitHub.
2. GitHub Actions run tests and other CI tasks.
3. Vercel automatically deploys the new version if all checks pass.

## Conclusion

Building a headless blog using sanity.io, GitHub, Vercel, and workflows has made the content management seamless, and the deployment process more efficient. The architecture ensures scalability, maintainability, and a high-performing frontend.

