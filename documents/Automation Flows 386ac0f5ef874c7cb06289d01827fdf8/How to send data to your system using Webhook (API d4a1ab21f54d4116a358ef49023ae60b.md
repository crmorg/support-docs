# How to send data to your system using Webhook (API)?

<aside>
💡 Webhooks are "user-defined HTTP callbacks". They are usually triggered by some event, such as pushing code to a repository or a comment being create a contact. When that event occurs, the source site makes an HTTP request to the URL configured for the webhook. Users can configure them to cause events on one site to invoke behavior on another. Common uses are to trigger builds with continuous integration systems or to notify bug tracking systems. Because webhooks use HTTP, they can be integrated into web services without adding new infrastructure.

</aside>

# Steps to send data via webhook(API)

## Create API endpoint

### Create a form

**For example, we have a form name ‘API  Form’** 

Please, create a form with necessary fields like FirstName, LastName, Email, Phone, etc. You can choose fields as per your requirements.

<aside>
<img src="How%20to%20send%20data%20to%20your%20system%20using%20Webhook%20(API%20d4a1ab21f54d4116a358ef49023ae60b/video-tutorial.png" alt="How%20to%20send%20data%20to%20your%20system%20using%20Webhook%20(API%20d4a1ab21f54d4116a358ef49023ae60b/video-tutorial.png" width="40px" /> [**Video tutorial on creating a form**](../The%20Database%20(Contacts,%20Companies,%20and%20Forms)%206aefbd9211a24aa08147be762ac649b6.md)

</aside>

## Get the API info

After saving the form, please, navigate to the ‘Tacks’ on the left menu bar. Here you will have all the tracks. You will also get the same form on the track list.

![Untitled](How%20to%20send%20data%20to%20your%20system%20using%20Webhook%20(API%20d4a1ab21f54d4116a358ef49023ae60b/Untitled.png)

Please, select the track and click on the ‘Edit Track’ button

![Untitled](How%20to%20send%20data%20to%20your%20system%20using%20Webhook%20(API%20d4a1ab21f54d4116a358ef49023ae60b/Untitled%201.png)

You will have the API key and track ID on the' Edit Track' page. You will get all these information under the ‘API Permission’ tab

![Untitled](How%20to%20send%20data%20to%20your%20system%20using%20Webhook%20(API%20d4a1ab21f54d4116a358ef49023ae60b/Untitled%202.png)

You can also control the API permission from here 

![Untitled](How%20to%20send%20data%20to%20your%20system%20using%20Webhook%20(API%20d4a1ab21f54d4116a358ef49023ae60b/Untitled%203.png)

### Get API documentation for this end point

Please, go back to the tack list. You see, each tack has a link icon on the left side.

![Untitled](How%20to%20send%20data%20to%20your%20system%20using%20Webhook%20(API%20d4a1ab21f54d4116a358ef49023ae60b/Untitled%204.png)

Please, click on the link icon and you will have the integration guideline under the ‘API Integration’ tab

![Screenshot_27.png](How%20to%20send%20data%20to%20your%20system%20using%20Webhook%20(API%20d4a1ab21f54d4116a358ef49023ae60b/Screenshot_27.png)

### Sample API post request using POSTMAN

![Screenshot_28.png](How%20to%20send%20data%20to%20your%20system%20using%20Webhook%20(API%20d4a1ab21f54d4116a358ef49023ae60b/Screenshot_28.png)