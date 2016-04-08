---
layout: page
title: Get started
---

This section will explain you how to set up a new instance of Muffin on your own device. From there, you can then start building your own site even and deploying it.

## Requirements

As the first step, you need to make sure that the latest version of those things is installed on your computer:

- [Node.js](https://nodejs.org)
- [MongoDB](https://www.mongodb.org)
- [Muffin](https://www.npmjs.com/package/muffin)

After installing all of the above dependencies, please make sure that your npm permissions are [fixed](https://docs.npmjs.com/getting-started/fixing-npm-permissions).

## Usage

If you want to set up a new site with Muffin, please firstly make sure that your database is running. This is required because the site generator will directly insert some sample data into it.

On your local machine, the easiest way to start MongoDB is by running the following command:

```
mongod
```

After that, simply use our neat Yeoman generator (which you've already installed previously) to generate a new boilerplate within the current directory:

```
muffin new
```

You'll then be asked to enter a few details about your site and the database connection. After you've answered all questions, your new site will be prepared.

As soon as the setup is finished, use the following command to run a server for your site:

```
npm start
```

## To be continued...

That was all! 📢🐢

Now we suggest you to learn more about the actual idea behind this project and how you can proceed with building your own site.