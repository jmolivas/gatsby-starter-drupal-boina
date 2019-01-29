# Gatsby Starter Drupal Boina

The Gatsby Starter for the Drupal Boina Distribution

## Install

```shell
gatsby new boina https://github.com/weknowinc/gatsby-starter-drupal-boina
cd boina
```

## Copy enviroment file

```shell
cp .env.dist .env.development
```

> NOTE: You should use `.env.production` for production enviroment.

## Update enviroment variables

 ```shell
# drupal
DRUPAL_HOST=http://drupal-boina.develop/
```

## Start Gatsby in development mode

```shell
gatsby develop
```

## Replacing a component (shadowing)

Create a js component in the starting with the path:

```shell
/src/components/@weknow/gatsby-theme-drupal-boina/
```

And follow the path to the component you want to replace.
