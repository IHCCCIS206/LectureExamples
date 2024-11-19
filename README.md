# Lecture Examples

This is the repository for IHCC CIS 206 Web Scripting.
In this course we will learn to use Next.js 

## Instructions

You will want to fork this repo so you can commit changes as you follow along. Make sure to commit changes before changing branches. 

## Branches

This repository has branches for each of the lectures in the course. The branches are structured to correspond to the videos in the course. The naming convention is `LU99#Lecture#`. As an example, the branch named `02_03` corresponds to the second unit and the third lecture in that unit. 
Some branches will have a beginning and an end state. These are marked with the letters `b` for "beginning" and `e` for "end". The `b` branch contains the code as it is at the beginning of the lecture. The `e` branch contains the code as it is at the end of the lecture. The `main` branch holds....

When switching from one exercise files branch to the next after making changes to the files, you may get a message like this:

```
error: Your local changes to the following files would be overwritten by checkout:        [files]
Please commit your changes or stash them before you switch branches.
Aborting
```

To resolve this issue:

```
Add changes to git using this command: git add .
Commit changes using this command: git commit -m "some message"
```

## Running the App

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.tsx`. The page auto-updates as you edit the file.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn-pages-router) - an interactive Next.js tutorial.

