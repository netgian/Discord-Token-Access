Discord User API
================

Simple Python script that automates requests to a Discord account via its token.

## Requirements
First of all install the libraries at requirements.txt
```
pip3 install -r requirements.txt
```

## Usage
Put the user's token on the instance of the class.
```
user = DiscordApi(token="YOUR-TOKEN")
```
Now you are able to use all the methods.
```
dump_info()
join_server()
set_typing()
send_message()
send_mass_messages()
set_bio()
set_custom_status()
change_status()
change_language()
change_theme()
create_threads()
create_guilds()
clear_messages()
delete_guilds()
delete_channels()
delete_friends()
raid()
```

**NOTE:** If you change your password your token will change.

## Tested on:

- Windows 10
