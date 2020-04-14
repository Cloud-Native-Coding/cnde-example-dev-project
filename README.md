# Example Application

In this tutorial, we are going to build a simple CRUD application to show how typical development with cloud- native-coding works.

I am using the following quite simple example [Build a simple app using Node JS and MySQL](https://dev.to/achowba/build-a-simple-app-using-node-js-and-mysql-19me)

## Preparation Steps

1. Clone the demo repository with `git clone https://github.com/Cloud-Native-Coding/cnde-example-dev-project.git`
2. In folder config execute `k apply -k .` to install required Kubernetes resources
3. install MySQL extension [VS-Code MySQL Extension](https://marketplace.visualstudio.com/items?itemName=formulahendry.vscode-mysql)
4. create a new connection to host `stage-mysql`, user `root` and password `UyH2EccNqK`
5. create DB and Table as written in the extension documentation

### Install NodeJS and NPM

```bash
sudo apt update
sudo apt install nodejs
sudo apt install npm
```

1. Install nodemon with `npm install nodemon -g`
2. execute `npm install`
3. Start application with `nodemon app.js`
4. point your browser to `players.norbert.kubeplatform.ch.innoq.io`
5. edit code to review live changes