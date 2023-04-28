![Eleventy](https://user-images.githubusercontent.com/2342458/230336594-86e2311a-3080-4d1c-9a01-03999a12136b.png)

# Kinsta - Hello World - Eleventy

An example of how to deploy an **Eleventy** application on Kinsta.

---
Kinsta is a developer-centric cloud host / PaaS. We’re striving to make it easier for you to share your web projects with your users. Focus on coding and building, and we’ll take care of deployment and provide fast, scalable hosting. + 24/7 expert-only support.

- [Start your free trial](https://kinsta.com/signup/?product_type=app-db)
- [Application Hosting](https://kinsta.com/application-hosting)
- [Database Hosting](https://kinsta.com/database-hosting)

## Dependency Management

Kinsta automatically installs dependencies defined in your `package.json` file during the deployment process.

## Web Server Setup

### Port

Kinsta automatically sets the `PORT` environment variable. You should **not** define it yourself and you should **not** hard-code it into the application.

### Start Command

When deploying an application, Kinsta automatically creates a web process with `npm start` as the entry point. Make sure to use this command to run your server.

## Deployment Lifecycle

Whenever a deployment is initiated (through creating an application or re-deploying due to an incoming commit) the `npm build` command is run, followed by the `npm start` command.

## What is Eleventy
Eleventy is a JavaScript-based static site generator that makes it easy for developers to create fast, modern, and customizable websites. More information is available on the [11ty.dev](https://www.11ty.dev/) website.
