# Example: Blog Site

An example of a blog site, which is generated via a static site generator like Hugo, and deployed using serverless components. The application uses the `static-website` component, which in turn uses the static files generated by Hugo, to deploy the blog site. The application is deployable to AWS.

## Site Generation

Use Hugo or any static site generator to generate the necessary static files in a folder `site` at the root.

## Operations

### Deploy

To deploy the application and create all dependent resources automatically, simply do:

```
$ components deploy
```

### Remove

To remove the application and delete all dependent resources automatically, simply do:

```
$ components remove
```
