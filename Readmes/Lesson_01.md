# Lesson 1: Getting Started with Gatsby

1. To get started with gatsby we install gatsby cli globally using npm
```
npm install -g gatsby-cli
```
2. after that we can create gatsby project with any of the starter provided by gatsby or we can choose from tons of starters provided by 3rd party(programmers). I chose simple hello world starter provided by gatsby as :
```
gatsby new gatsby-bootcamp https://github.com/gatsbyjs/gatsby-starter-hello-world.git
```
where gatsby-bootcamp is the folder where the project will be stored.Generalised command for starter is:
```
gatsby new [SITE_DIRECTORY] [URL_OF_STARTER_GIT_REPO]
```
3. with this we get starter project to run the project in development mode we may type:
```
gatsby develop(or npm run develop)
```
And we get a page powered by react which contains character "Hello World!". Now we have initial startup so that we can do things with gatsby.