# Overview

An assignment on CICD involving the creation of a workflow.yaml file to incorporate **Github Actions** that:

1. Automatically creates a Docker image of the project whenever a new version is published and
2. Sends a notification to a Slack Channel via its Webhook URL

Original randnum project was provided by the lecturer. 

# Github Actions Used
1. docker/login-action@v2
2. docker/build-push-action@v3
3. slackapi/slack-github-action@v1.18.0

# Related Links
Docker Image Link: [Docker Hub](https://hub.docker.com/r/e0834739/randnum)