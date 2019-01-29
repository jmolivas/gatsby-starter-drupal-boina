# Gatsby Starter Drupal Boina

A Gatsby Starter for the Drupal Boina Distribution

## Install
```shell
gatsby new boina https://github.com/weknowinc/gatsby-starter-drupal-boina
cd boina
```

## Setup your enviroment variables
```
cp `.env.dist` to `.env.development`
```
> NOTE: You should use `.env.production` for production enviroment.

Update enviroment variables
```shell
# drupal
DRUPAL_HOST=http://drupal-boina.develop/
```

Start developing
```
gatsby develop
```

## Replacing a component (shadowing)
Create a js component in the starting with the path
```
/src/components/@weknow/gatsby-theme-drupal-boina/
```
and follow the path to the component you want to replace.