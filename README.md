# GitLab Notifications in Discord
Tutorial to send GitLab notifications to discord channel, use this if you are receiving a ``cannot send empty message` error

In discord go to the channel that will receive de notifications and create a new WebHook
- `Right click on the channel` -> `Edit Channel` -> `WebHooks` -> `Create WebHook`

![ss1](https://user-images.githubusercontent.com/14078661/51546634-b9cb4e00-1e4b-11e9-9860-86f08ada3d7f.png)

- Type the bot name and upload an image if you want
- Copy the url provided and save

Now go to your GitLab project

- Go to `Settings` -> `Integrations`
- Scroll down until `Project services` and click on `Discord notifications`
 ![](https://user-images.githubusercontent.com/14078661/51546176-be433700-1e4a-11e9-84aa-8e9b10fea875.png)
 
 - Make sure to check the `Active` box
 - Select the triggers that you want
 - In the Webhook field paste the WebHook url that you have copied before.
 - Save your changes
 
 A test notification will be sent to your Discord channel
 
 ![ss3](https://user-images.githubusercontent.com/14078661/51546519-72dd5880-1e4b-11e9-92ad-817a811304eb.png)
 

