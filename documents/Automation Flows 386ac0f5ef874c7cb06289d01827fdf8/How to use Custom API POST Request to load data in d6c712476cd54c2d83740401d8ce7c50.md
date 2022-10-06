# How to use Custom API POST Request to load data into your Flow?

# What is Custom API?

API is the acronym for Application Programming Interface, which is a software intermediary that allows two applications to talk to each other. Each time you use an app like Facebook, send an instant message, or check the Bitcoin price on your phone, you’re using an API.

# How to use POST method to send data into your system from third party software?

Most of the time if you are sending data to an API you will use 'POST' to send the data. If you are pulling data from an API into your flow you will use 'GET'.

1. Inside your Flow: Select Custom API from Data Services
2. Paste your third party API link to perform your operation
*This is provided by the third party API or service you are using. For example; If your trying to post a webhook to Zapier you would use the URL Zapier provides to receive the webhook*
3. Select your HTTP Method: POST / GET
4. From Body Data Choose 
- You can choose **“No Code”**
or
- You can choose **“Custom Body”** 

## No Code (POST REQUEST with JSON)

- Select Data Type: JSON
- Select Body Type: No Code
- Add Headers for which you want to catch and store values as mentioned in below image

![Untitled](How%20to%20use%20Custom%20API%20POST%20Request%20to%20load%20data%20in%20d6c712476cd54c2d83740401d8ce7c50/Untitled.png)

## No Code (POST REQUEST with Custom Body)

- Select Data Type: JSON
- Select Body Type: Custom Body
- Add Headers for which you want to catch and store values as mentioned in below image

![Untitled](How%20to%20use%20Custom%20API%20POST%20Request%20to%20load%20data%20in%20d6c712476cd54c2d83740401d8ce7c50/Untitled%201.png)

**Below is the Example Format you can copy and use for JSON custom body:**

*{*

*“fname”:“${form.firstName.value}“,*

*“lname”:“${form.lastName.value}“,*

*“email”:{$form.email.value.value}*

*}*

Click on Save button and you are ready to send requests in your third party API that is going to be received in your Flow via Custom API.