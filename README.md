# Run Locally
1. ``rails s``
2. go to ``localhost:3000``

# Deploy
````
RAILS_ENV=production bundle exec rake assets:precompile
git add --all .
git commit -a -m "Compiled assets for prod"
git push
git push heroku master
````