# Gravatar
Yet another library for generating gravatar urls.

## Why?
Because the other ones depend on jQuery or make assumptions I don't want like returning an image tag instead of a url.

## Usage
gravatarjs is based on the standard Gravatar API, learn more here: https://en.gravatar.com/site/implement/images/

### Generate a gravatar url
```
gravatar("me@me.com");
```

### Specify options
 - size: Size of the image (Default 50)
 - rating: Rating of the image (Default 'g', Options: g, pg, r, x)
 - secure: Use https or http (Default false)
 - backup: Backup image if gravatar doesn't exist (Default: default)
 - - You can see backup options here: https://en.gravatar.com/site/implement/images/

```
gravatar("me@me.com", {size: 200, rating: "pg", backup: "retro", secure: true});
```