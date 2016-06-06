# heroku-buildpack-multiapp

Run multiple web applications in one container

## Usage

    $ heroku config:add BUILDPACK_URL=https://github.com/Vincit/heroku-buildpack-multiapp.git

    $ cat .apps
    frontend https://github.com/Vincit/heroku-buildpack-nodejs.git
    backend https://github.com/Vincit/heroku-buildpack-java.git

## License

MIT
