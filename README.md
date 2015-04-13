# Run Locally
1. ``rails s``
2. go to ``localhost:3000``

# Deploy
````
RAILS_ENV=production bundle exec rake assets:precompile
git add --all .
git commit -a -m "Compiled assets for prod"
git push
git remote add heroku https://git.heroku.com/becomingbrand.git
git push heroku master
````