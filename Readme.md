## Run locally

    ./configure
    make
    foreman start

## Deploy to Heroku

    heroku create -s cedar --buildpack https://github.com/heroku/heroku-buildpack-c
    git push heroku master
    heroku open
    heroku logs

