# koncrete-gitops-demo

This demo is a simple example of an application that can be easily run on Kubernetes with automatically updating CD.

It contains a basic podinfo app using gitops infrastructure defined through kustomize.

## How to start

For more details, see the getting started guide on Koncrete's official documentation page.

A quick summary of the demo steps below:
- Fork the repository
- Use Koncrete to connect your git repo to a Kubernetes cluster, automatically creating a webhook for automatic syncing
- Create an application using the infrastructure defined in this repo
- Expose a port to view the app
- Make a change in the git repository and see Koncrete immediately sync the change live

At the end of the demo, you'll be able to have a heroku-like flow: Git Push/Pull --> Instantly updated application

