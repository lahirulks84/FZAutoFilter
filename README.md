<p align="center">
  <img src="assets/LOGO.jpg">
</p>
<h1 align="center">
  <b>FZAutoFilterBot</b>
</h1>


### Features

- [x] Indexes Files above 2GB
- [x] Force Subscription
- [x] Automatic File Filtering
- [x] Double Filter Button
- [x] Single Filter Button
- [x] Forward Restriction
- [x] File Protect
- [x] Manual File Filtering
- [x] Global File Filtering
- [x] IMDB
- [x] Admin Commands
- [x] User Broadcast
- [x] Group Broadcast
- [x] Index
- [x] IMDB search
- [x] Inline Search
- [x] Random pics
- [x] ids and User info 
- [x] Stats
- [x] Users
- [x] Chats
- [x] User Ban
- [x] User Unban
- [x] Chat Leave
- [x] Chat Disable
- [x] Channel
- [x] Spelling Check Feature
- [x] File Store
- [x] Auto Delete
- [x] And More....


### Required Variables
* `BOT_TOKEN`: Create a bot using [@BotFather](https://telegram.dog/BotFather), and get the Telegram API token.
* `API_ID`: Get this value from [telegram.org](https://my.telegram.org/apps)
* `API_HASH`: Get this value from [telegram.org](https://my.telegram.org/apps)
* `CHANNELS`: Username or ID of channel or group. Separate multiple IDs by space
* `ADMINS`: Username or ID of Admin. Separate multiple Admins by space
* `DATABASE_URI`: [mongoDB](https://www.mongodb.com) URI. Get this value from [mongoDB](https://www.mongodb.com). 
* `DATABASE_NAME`: Name of the database in [mongoDB](https://www.mongodb.com). 
* `LOG_CHANNEL` : A channel to log the activities of bot. Make sure bot is an admin in the channel.
### Optional Variables
* `PICS`: Telegraph links of images to show in start message.( Multiple images can be used separated by space )
* `FILE_STORE_CHANNEL`: Channel from were file store links of posts should be made.Separate multiple IDs by space
* Check [info.py] 




### Commands
```
alive - check bot alive  
ping - pong  
gfilter - to add a global filter 
delg - to delete a global filter 
broadcast - to broadcast a message to all users 
group_broadcast - to broadcast a message to all groups 
settings - get settings   
logs - to get the rescent errors  
stats - to get status of files in db 
filter - add manual filters 
filters - view filters  
connect - connect to PM 
disconnect - disconnect from PM  
del - delete a filter  
delall - delete all filters    
id - get tg ids 
imdb - fetch info from imdb  
users - to get list of my users and ids 
chats - to get list of the my chats and ids   
leave  - to leave from a chat 
disable  -  do disable a chat 
enable - re-enable chat 
ban  - to ban a user  
unban  - to unban a use
```


