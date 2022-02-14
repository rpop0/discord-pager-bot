# Pager bot for Discord
Simple pager bot for discord using python.

### Installing
* Create a virtual environment.
* Install requirements.txt file using `python3 -m pip install -r requirements.txt`.
* Create a file named `.env` at the folder's root.
* Create a `roles` collection in your MongoDB database.
* Make sure you have a `role_requests' channel on your server.
* Make sure you have a category named `role queue`.

More information about building with docker soon.

### .env file
The `.env` file should look like this:
```
BOT_TOKEN=<BOT_TOKEN>
DISPATCH_DB_CONN=<MONGO-CONNECTION-STRING-WITH-USERNAME-AND-PASSWORD>
DISPATCH_DB_NAME=<DB-NAME>
```
