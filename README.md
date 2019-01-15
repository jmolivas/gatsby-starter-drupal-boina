# Gatsby Starter Drupal Boina

A Gatsby Starter for the Drupal Boina Distribution

## Install
```shell
gatsby new [SITE_DIRECTORY_NAME] https://github.com/weknowinc/gatsby-starter-drupal-boina
$ cd [SITE_DIRECTORY_NAME]
$ gatsby develop
```

## Setup your enviroment variables
Copy `.env.dist` to `.env.development`, 
you can use `.env.production` for production deployments

Here you can point to your drupal site.
```shell
# drupal
DRUPAL_HOST=http://blog-drupal.weknowinc.develop/
```

## Replacing a component (shadowing)
Create a js component in the starting with the path
```
/src/components/@weknow/gatsby-theme-drupal-boina/
```
and follow the path to the component you want to replace.