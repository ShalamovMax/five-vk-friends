# five VK Friends

## Usage

Running this project locally involves a lot of steps and I don't recommend it.

Required conditions:

- Download Heroku and ngrok
- set `VK_CLIENT_ID` and `VK_CLIENT_SECRET` environment variables in Heroku
- you can't run this project using `localhost` because VK API needs a url
- set `SERVER_DOMAIN` to your domain (I used `ngrok` to get a temporary domain)
- add your domain in VK App Settings
- set `SERVER_SECRET_KEY` to anything long and secure
- remove lines `32` and `136` in `five_friends/settings.py` (I decided not to make a special branch)

Launch the server:

- run `python manage.py runserver`
