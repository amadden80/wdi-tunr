
rails new wdi-tunr -d postgresql -T
cd wdi-tunr

git init
git add .
git commit -m "Rails app started"

bin/rake db:create


#### Set up remote repository on github
- github.com
- created new repository
- copied the git@github.com<...........>

git remote add origin git@github.com<...........>
git push origin master

heroku create wdi-tunr-name-you-like
git push heroku master





##Phase 2
- edited gemfile and bundled

rails g rspec:install


rails g model Song

- edited songs migration file

bin/rake db:migrate



