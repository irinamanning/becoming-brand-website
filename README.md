# Run Locally
``rails s``

# Deploy
````
RAILS_ENV=production bundle exec rake assets:precompile
git add --all .
git commit -a -m "Compiled assets for prod"
git push
git push heroku master
````