# turborepo-remote-cache on Render

This is a template repository for running [turborepo-remote-cache](https://hub.docker.com/r/fox1t/turborepo-remote-cache) on Render. 

## Deployment

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy?repo=https://github.com/nullnull/turborepo-remote-cache-by-render)

See https://render.com/docs.

## After Deployment
```sh
$ turbo run build --team=teamname --api="https://your-render-hostname.onrender.com" --token="<check TURBO_TOKEN env on render>"
```