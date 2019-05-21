# dockercism
Use Docker for exercism.io tracks

## requirements:
- Exercism account (https://exercism.io)
- Docker
- Docker Compose

## usage:
- FORK this repo, and clone your fork, so you can commit your own code solutions.  ( ͡° ͜ʖ ͡°)
- create a new file in the config directory named `user.json`
- copy the contents of the sample file into it (or from below, for your convenience)
```
{
  "apibaseurl": "https://api.exercism.io/v1",
  "token": "YOUR_TOKEN_HERE",
  "workspace": "/root/exercism"
}
```
- get your exercism token at this url: https://exercism.io/my/settings
- in your new `user.json` file, replace `YOUR_TOKEN_HERE` with your exercism token
- run `docker-compose build elixir` , for example, if you want to do the elixir course
- run `docker-compose run --rm` elixir
- you should now be at a bash prompt inside of the docker container
- start using the exercism commands as instructed, example: `exercism download --exercise=hello-world --track=elixir` if you've just joined the elixir track
- (∩ ͡° ͜ʖ ͡°)⊃━☆ﾟ. * ･ ｡ﾟ,

I suggest an alias for docker-compose run --rm.  I use `dcrm='docker-compose run --rm'`
