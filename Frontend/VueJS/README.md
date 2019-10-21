# VueJS

This template allows you to run a VueJS app on Vapor Cloud 2. This template will build your VueJS code, and setup a plain nginx template.

## Setup

To setup the template in your app, run the following command to download the template

```bash
curl -O https://raw.githubusercontent.com/vapor-cloud/docker/master/Frontend/VueJS/web.Dockerfile
```

## Test locally

To test it and make sure it works locally, you can run the following commands

```bash
docker build -t my-app -f web.Dockerfile .
docker run -p 8500:80 my-app
```

And go to http://127.0.0.1:8500
