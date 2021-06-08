## Quick References:

# Heroku Deployment

1. heroku login -i
2. heroku create app-name
3. git init
4. heroku git:remote -a app-name
5. git add .
6. git commit -am "initial deployment"
7. git push heroku master

# Make requirements.txt
  pip freeze > requirements.txt
