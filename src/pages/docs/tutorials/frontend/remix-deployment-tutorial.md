# How to Deploy Remix Frontends with Gimlet

Remix is a React framework for frontend applications. You can deploy it with Gimlet.

## Step 1: Getting Started with Gimlet

Log in to Gimlet and connect your GitHub or GitLab account. You should see the repositories you have access to listed. If you can't see the repo that contains the Remix application, use the search bar to find it.

Click the Import button next to the repository, then the I'm done importing button to add the repo in Gimlet.

Select the repository by clicking on its card.

## Step 2: Remix Deployment Configuration

Pick the Web Application deployment template, so you're able to select the Dockerfile container image setting. For this method, a Dockerfile is necessary to have in your repo.

If you don't have a Dockerfile, you can get yours [here](https://github.com/gerimate/remix-gimlet-test/blob/main/Dockerfile).

Select the GitHub Container Registry option under Registry settings, and make sure that the port is the same as the `server.js` file specifies.

You can also set a custom domain if you use one, but Gimlet will generate one for you.

## Step 3: Deploy

When you’re done with configuration, you can click the Deploy button. Deployment should start with logs appearing, where you can see the build process taking place.

When the Remix application is successfully deployed, confetti will rain in the browser window and a link will appear next to the deployment status.

## Use Cases

Here are a few examples of why hosting Remix frontend with Gimlet is for you:

- **OAuth & HTTPS/SSL:** Add social authentication and secure your Remix application.   
- **Branch previews:** Test changes and share previews on real environments.
- **Advanced deployment capabilities:** Roll back to previous versions and automate deployments.

## Try Now

> Try Gimlet now with your Remix application for free here.
