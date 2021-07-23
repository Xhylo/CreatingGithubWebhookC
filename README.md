# Step 1 - Make a Discord Webhook
1. Find the Discord channel in which you would like to send commits and other updates

2. In the settings for that channel, find the Webhooks option and create a new webhook. Note: Do NOT give this URL out to the public. Anyone or service can post messages to this channel, without even needing to be in the server. Keep it safe!
![WebhookDiscord](https://imgur.com/dbMmvBI.png)

# Step 2 - Set up the webhook on Github
1. Navigate to your repository on Github and open the Settings
![Settings](https://imgur.com/iNpg8PW.png)

2. Select Add Webhook
![Add](https://imgur.com/q7jqBUW.png)

3. Paste in the webhook url and append `/github` to the end. Select "Send me everything", set the type to `application/json`, and then Add Webhook
![WebhookSettings](https://imgur.com/U3lros4.png)

4. Test it by updating something or starring the repository! If any issues occured contact me on Discord-Xyhlo#9766
![Star](https://imgur.com/CNYAxJF.png)
