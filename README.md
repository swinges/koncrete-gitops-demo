# koncrete-gitops-demo

This demo is a simple example of an application that can be easily run on Kubernetes with automatically updating CD.

It contains a basic [podinfo](https://github.com/stefanprodan/podinfo) app using gitops infrastructure defined through [kustomize](https://kustomize.io/).

![image](https://user-images.githubusercontent.com/30635282/124979225-9f6b9780-dfe7-11eb-95a5-ee1bc66b6afb.png)


## How to start

For more details, see the [getting started guide](https://docs.koncrete.dev/Getting-Started-0e835a43c944493ea5a591dea5dc804d) on Koncrete's [official documentation page](https://docs.koncrete.dev/).

A quick summary of the demo steps below:
- Fork the repository
- Use [Koncrete](https://www.koncrete.dev/) to connect your git repo to a Kubernetes cluster, automatically creating a webhook for automatic syncing
- Create an application using the infrastructure defined in this repo
- Expose a port to view the app
- Make a change in the git repository and see Koncrete immediately sync the change live

At the end of the demo, you'll be able to have a heroku-like flow: Git Push/Pull --> Instantly updated application

