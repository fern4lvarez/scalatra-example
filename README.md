This is a sample of scalatra on cloudControl

# Deploy to cloudControl

```
cctrlapp APP_NAME create custom --buildpack git://github.com/heroku/heroku-buildpack-scala.git
cctrlapp APP_NAME/default push
cctrlapp APP_NAME/default deploy
```

# Other deplying

See http://www.scalatra.org/2.0/book/#Production_Deployment
