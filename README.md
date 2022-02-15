# Pager bot for Discord
A more complex pager bot featuring role requests, multiple channels, etc.

## Set up

### Prerequisites
* A MongoDB Database (Free Atlas database offered by MongoDB works perfectly.)
* Python 3.10
* A MongoDB Collection named `roles` (Will be changed in the future to be named in environments)
* A channel named `role-requests`
* A channel group named `role queue` (This is where the command approval channels will be placed).

### Installing
* Create a virtual environment.
* Install requirements.txt file in the virtual environment.
* Create a file named `environment.env` at the folder's root.
* Export the environment variables and run the `main.py` script.

### Alternative: Docker install
* Create the docker image using `docker build -t image_name .`
* Run the docker image using `docker --restart always --env-file ./environment.env -d image_name`

### .env file
The `.env` file should look like this:
```
BOT_TOKEN=<BOT_TOKEN>
DISPATCH_DB_CONN=<MONGO-CONNECTION-STRING-WITH-USERNAME-AND-PASSWORD>
DISPATCH_DB_NAME=<DB-NAME>
```

### Final words
If you wish to use this, the bot messages and embeds are written in Romanian, so you need to translate them.

LICENSED UNDER GNU General Public License v3.0.
