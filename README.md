# React-Django Boilerplate App

## Foreword

Thank you for using this repository for your own projects. This is a pre-configured repository with most of the setup done to allow you to focus on building the application. It uses `antd` for the front end components but feel free to modify it as per your usage.

## Contributing

There are still many pieces that are missing such as a fully functioning user sign up and email verification process on the backend. Please feel free to create pull requests for any features that you would like to see. Please also keep them as generic as possible so that it is applicable to a variety of usages.

## Setup

### Local

Fork and then clone this repository with

```bash
git clone --recurse-submodules git@github.com:majulahsingapuri/React-Django-App.git 
```

to initialise all the submodules together with the parent repository.

Refer to the individual sub-folders for setup relating to the front and back ends. Set up the backend before the front.

Replace all instances of `sample` with the name of your application to enable this repository to function correctly, including foldernames.

### Docker

This application has been containerised for easy deployment to various online platforms. There are 2 compose files, `production` and `development` respectively. Each of them use the respective `env.*` environment files to get the containers up and running. Developers will only be able to use the `development` container as the credentials of the `production` are with the repository owner.

#### Development

Run the development containers locally with:

```bash
docker-compose -f docker-compose-development.yml up
```

#### Production

Run the production containers locally with:

```bash
docker-compose -f docker-compose-development.yml up
```
