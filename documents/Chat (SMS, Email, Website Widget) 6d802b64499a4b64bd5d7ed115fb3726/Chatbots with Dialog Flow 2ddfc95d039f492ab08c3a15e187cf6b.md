# Chatbots with Dialog Flow

# Create a Google DialogFlow Bot

Your DialogFlow bot is going to process the Chat messages via an “Agent” and then return a response in the Chat. To do this we first need to define an “Agent” with Google.

## Create a New Agent

Please navigate to [https://dialogflow.cloud.google.com/](https://dialogflow.cloud.google.com/) and click “Create New Agent”.

<aside>
✅ You can also start from one of Google Pre-built Agents here [https://dialogflow.cloud.google.com/#/agent/food-delivery-qewk/prebuiltAgents/](https://dialogflow.cloud.google.com/#/agent/food-delivery-qewk/prebuiltAgents/)

</aside>

![Screenshot 2022-09-01 at 01.09.23@2x.png](Chatbots%20with%20Dialog%20Flow%202ddfc95d039f492ab08c3a15e187cf6b/Screenshot_2022-09-01_at_01.09.232x.png)

## Create New Intent

Create “Intents” with DialogFlow that tells your Bot what to listen for and how to respond.

![Screenshot 2022-08-31 at 21.29.44@2x.png](Chatbots%20with%20Dialog%20Flow%202ddfc95d039f492ab08c3a15e187cf6b/Screenshot_2022-08-31_at_21.29.442x.png)

Create a “Handoff” intent that will route route the chat from the bot to an agent

![Screenshot 2022-08-31 at 21.34.43@2x.png](Chatbots%20with%20Dialog%20Flow%202ddfc95d039f492ab08c3a15e187cf6b/Screenshot_2022-08-31_at_21.34.432x.png)

<aside>
✅ In this example we just created one “Talk to a human” intent that will pass the conversation to a human. Normally you would add more intents here to create many types of Bots from FAQ bots, order taking bots, and more

</aside>

## Create a Google Service Account

To connect your Chat with DialogFlow you need to create a “Service Account” with Google here 

[https://console.cloud.google.com/home/dashboard](https://console.cloud.google.com/home/dashboard) 

 

![Screenshot 2022-08-31 at 21.24.58@2x.png](Chatbots%20with%20Dialog%20Flow%202ddfc95d039f492ab08c3a15e187cf6b/Screenshot_2022-08-31_at_21.24.582x.png)

Click the “Create Service Account” Button

![Screenshot 2022-08-31 at 21.25.26@2x.png](Chatbots%20with%20Dialog%20Flow%202ddfc95d039f492ab08c3a15e187cf6b/Screenshot_2022-08-31_at_21.25.262x.png)

Name your Service Account and give it an ID (you can name it anything)

![Screenshot 2022-08-31 at 21.26.02@2x.png](Chatbots%20with%20Dialog%20Flow%202ddfc95d039f492ab08c3a15e187cf6b/Screenshot_2022-08-31_at_21.26.022x.png)

Now select the Role of  “DialogFlow API Client” for this Service Account 

![Screenshot 2022-08-31 at 21.27.06@2x.png](Chatbots%20with%20Dialog%20Flow%202ddfc95d039f492ab08c3a15e187cf6b/Screenshot_2022-08-31_at_21.27.062x.png)

## Create Security Access Keys For your Service Account

For the Chat system to connect to your new Google Service Account we need to generate an access Key. Inside your new Service Account [https://console.cloud.google.com/home/dashboard](https://console.cloud.google.com/home/dashboard)  you will will need to click to open the setting for you new Service Account first

![Screenshot 2022-08-31 at 21.27.45@2x.png](Chatbots%20with%20Dialog%20Flow%202ddfc95d039f492ab08c3a15e187cf6b/Screenshot_2022-08-31_at_21.27.452x.png)

Then click the “Keys” tab

![Screenshot 2022-08-31 at 21.27.56@2x.png](Chatbots%20with%20Dialog%20Flow%202ddfc95d039f492ab08c3a15e187cf6b/Screenshot_2022-08-31_at_21.27.562x.png)

Then click “Create New Key”

![Screenshot 2022-08-31 at 21.28.30@2x.png](Chatbots%20with%20Dialog%20Flow%202ddfc95d039f492ab08c3a15e187cf6b/Screenshot_2022-08-31_at_21.28.302x.png)

On the next popup you will make sure the “JSON” option is selected and then click “Create”

![Screenshot 2022-08-31 at 21.28.59@2x.png](Chatbots%20with%20Dialog%20Flow%202ddfc95d039f492ab08c3a15e187cf6b/Screenshot_2022-08-31_at_21.28.592x.png)

# Enable the DialogFlow Integration

Now that you have a new Chatbot created in DialogFlow and a ServiceUser to connect to that Chatbot you need to enable the DialogFlow Chatbot integration. For this we need to know the Google “Project ID” and the contents of the “JSON” file from the previous step

Navigate to “Integrations” > “AI” > “Dialog Flow”

![Screenshot 2022-09-01 at 01.34.05@2x.png](Chatbots%20with%20Dialog%20Flow%202ddfc95d039f492ab08c3a15e187cf6b/Screenshot_2022-09-01_at_01.34.052x.png)

Next enter the;
Project ID
JSON Key File Contents
And Select the Inbox you want to use the Bot with in the Dropdown

![Screenshot 2022-09-01 at 01.37.17@2x.png](Chatbots%20with%20Dialog%20Flow%202ddfc95d039f492ab08c3a15e187cf6b/Screenshot_2022-09-01_at_01.37.172x.png)

Congratulations! You have successfully connected your ChatBot!
Make sure the Chat widget is installed on your website and start chatting to test it

<aside>
✅ Please note when testing your Chatbots that only NEW conversations will trigger the bot. After a “Handoff” occurs to a human the bot will never be triggered again for that contact and conversation

</aside>