# Golang AI Bot Wit.AI/Wolfram/Slack
This is Golang project building a Slack bot using Wit.ai and Wolfram Alpha. You can ask the bot any question!
![image](https://user-images.githubusercontent.com/96225596/167912639-899c3f43-8587-45f6-b65c-65f819322d27.png)

## Technologies Used
* Golang
* Wit.ai
* Wolfram Alpha
* Slack

## Dependencies

* Install Go - https://go.dev/doc/install
* Get AppID from Wolfram Aplha - https://developer.wolframalpha.com/portal/myapps
* Creat new app on Wit.ai - https://wit.ai
* Creat new app on Slack from scratch - https://api.slack.com/apps
![image](https://user-images.githubusercontent.com/96225596/167914918-63f42fec-3897-421f-b5a0-9deaf3839586.png)


## Executing program

* Create intent on Wit.ai
![image](https://user-images.githubusercontent.com/96225596/167915188-b638d99f-74ec-4560-8a39-d4cf3662c3ee.png)
* Add entity wit/wolfram_search_query
![image](https://user-images.githubusercontent.com/96225596/167914670-f4fe34d6-0695-44ea-b827-3dbf47810e7c.png)
* Enable socket mode on Slack api
![image](https://user-images.githubusercontent.com/96225596/167914383-606e31d1-f313-4677-a197-4440dc9c3375.png)
* Enable subscriptions mode on Slack api
![image](https://user-images.githubusercontent.com/96225596/167915763-f08ae77d-be1b-4822-af1a-cf5059d00601.png)
* Subscribe to couple bot events
![image](https://user-images.githubusercontent.com/96225596/167916245-4f90b770-0020-4333-84f2-6af455a3e8a0.png)
* Go to OAuth & Permissions and add couple scopes
![image](https://user-images.githubusercontent.com/96225596/167916737-807aedc2-0d67-4176-883c-fa55c5f2c871.png)
* Install to workplace
![image](https://user-images.githubusercontent.com/96225596/167916908-7517aabd-bdb4-4d5d-8953-0769194f7538.png)
* Add app to slack
![image](https://user-images.githubusercontent.com/96225596/167917257-da06036c-06a8-4196-a6cc-01d6fe7bb8ea.png)
* Download the repository to your computer and go to project file
```
git clone https://github.com/mobenh/Golang-MongoDB
cd Golang-MongoDB
```
* Create .env file and add theses 4
![image](https://user-images.githubusercontent.com/96225596/167917754-91d962cd-1547-4e60-a2f2-e1e81a0dec04.png)
  * Get SLACK_BOT_TOKEN (should start with xoxb)
![image](https://user-images.githubusercontent.com/96225596/167917995-bed15a9d-99f2-49ad-9636-47ce34cd42c6.png)
  * Get SLACK_APP_TOKEN in Setting >> Basic Information >> App-Level Tockens (should start with xapp)
![image](https://user-images.githubusercontent.com/96225596/167918566-5d451d46-e476-45d3-b52f-872738ae9004.png)
  * Get WIT_AI_TOCKEN
![image](https://user-images.githubusercontent.com/96225596/167919909-2d60de31-0467-41bd-bdbc-721836de2cd3.png)
  * Get WOLFRAM_APP_ID
![image](https://user-images.githubusercontent.com/96225596/167920138-a16708a2-a75e-4372-a2f9-195c2f082a0e.png)
* .env should lokk like this
![image](https://user-images.githubusercontent.com/96225596/167920252-be5cf4e9-f1a2-4f0f-8447-4961e267f607.png)

* Run code
```
go run main.go
```
* Now test on slack

![image](https://user-images.githubusercontent.com/96225596/167912639-899c3f43-8587-45f6-b65c-65f819322d27.png)
