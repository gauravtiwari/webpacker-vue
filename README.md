## Development
```bash
  bundle install
  yarn install
  bundle exec  foreman start -f Procfile.dev
```

## Deployment
```bash
  heroku create app-name
  heroku buildpacks:set heroku/nodejs --index 1
  heroku buildpacks:set heroku/ruby --index 2
  git push heroku master
```
