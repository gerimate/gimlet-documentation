# vLLM Deployment Tutorial

vLLM is an inference for large language models (LLMs) that you can deploy with Gimlet. It's worth noting that this tutorial only describes how to set up vLLM on CUDA-capable resources, therefore you won't be able to test vLLM deployment with Gimlet's trial version.

## Step 1: Log In To Gimlet

Connect your GitHub or GitLab account with Gimlet. Upon successful connection, your repositories should be listed. If you can't find the vLLM repo, you can use the search bar to find it.

## Step 2: Deployment Settings for vLLM

There are multiple ways to deploy with Gimlet. For vLLM deployments select the Web Application template, then choose Static image tag for container image.

Then enter the following:

- **Repository:** `vllm/vllm-openai`.
- **Tag:** `latest`- but it can be any valid tag available [here](https://hub.docker.com/r/vllm/vllm-openai/tags).

You can see it all in the screenshot below:

![Deployment settings for vLLM, an inference for large language models (LLMs).](/src/pages/docs/screenshots/vllm-deployment/vllm-deployment-configuration.png)

## Step 3: Deploy

When you're ready with making the changes in settings, you can click the Deploy button.

The image should be pulled, and the container should be started in a few moments.

## Step 4: Try vLLM

???

## Use Cases

- **Remote Nvidia GPUs:** You can deploy vLLM to nodes with CUDA-capable Nvidia GPUs.
- **File Syncing:** Sync code across your team's environments.
- **Share Your Project:** Set up social authetentication and HTTPS to share your project securely with your teammates.

## Deploy vLLM with Gimlet

> Try Gimlet and deploy vLLM now.