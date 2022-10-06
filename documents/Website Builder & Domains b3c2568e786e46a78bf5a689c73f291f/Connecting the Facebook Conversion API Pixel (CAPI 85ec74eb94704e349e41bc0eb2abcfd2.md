# Connecting the Facebook Conversion API / Pixel (CAPI)

<aside>
💡 **[What is a domain?](What%20is%20a%20Domain%2072eb36b2d10048a2b5c06c6de4786def.md)**

</aside>

# Create a New Meta Data Source Pixel

You must have a Meta Ad Manager Account. Open your Ad Manager Account and Navigate to [Meta Events Manager](https://business.facebook.com/events_manager2/overview) and then click on “Connect Data Source

![step1 - meta data source.png](Connecting%20the%20Facebook%20Conversion%20API%20Pixel%20(CAPI%2085ec74eb94704e349e41bc0eb2abcfd2/step1_-_meta_data_source.png)

Next select “Web” and click “Continue”

![step2 - select web datasource.png](Connecting%20the%20Facebook%20Conversion%20API%20Pixel%20(CAPI%2085ec74eb94704e349e41bc0eb2abcfd2/step2_-_select_web_datasource.png)

Now give your Pixel a Name

![step4 Name your meta pixel.png](Connecting%20the%20Facebook%20Conversion%20API%20Pixel%20(CAPI%2085ec74eb94704e349e41bc0eb2abcfd2/step4_Name_your_meta_pixel.png)

Next you will get a popup to check for a “Partner Integration”, simply close this popup

![step5 - Close the Partner integration check.png](Connecting%20the%20Facebook%20Conversion%20API%20Pixel%20(CAPI%2085ec74eb94704e349e41bc0eb2abcfd2/step5_-_Close_the_Partner_integration_check.png)

# Generate Access Token For Your Pixel

Now your Pixel is created and we can start connecting to it. First click on your new Pixel under Data Sources and then click ‘Settings” and then “Generate access token”

![step6 - Generate Access Token.png](Connecting%20the%20Facebook%20Conversion%20API%20Pixel%20(CAPI%2085ec74eb94704e349e41bc0eb2abcfd2/step6_-_Generate_Access_Token.png)

**Next you will need to copy TWO things on this page we will need for later;**
1) The ID number of the Pixel

2) The new token that was generated in the Blue Box. 

![step6 - copy new token.png](Connecting%20the%20Facebook%20Conversion%20API%20Pixel%20(CAPI%2085ec74eb94704e349e41bc0eb2abcfd2/step6_-_copy_new_token.png)

# Tell Meta What Conversion Events and Data to Collect With Your Pixel

## Launch the Wizard

Now we have to tell Meta  what type of events we want to track such as “Purchase”, “Add to Cart”, “Lead”, and more.

Go ahead and click on the “Get Started” button under Settings to launch the step by step wizard

![step7a- launch wizard.png](Connecting%20the%20Facebook%20Conversion%20API%20Pixel%20(CAPI%2085ec74eb94704e349e41bc0eb2abcfd2/step7a-_launch_wizard.png)

Now click “Continue”

![step7 - capi wizard.png](Connecting%20the%20Facebook%20Conversion%20API%20Pixel%20(CAPI%2085ec74eb94704e349e41bc0eb2abcfd2/step7_-_capi_wizard.png)

## Select Your Events

On this step we have to select the Events that are important to your business. These events match the flow of your Funnel. If you’re selling products or services online your events will probably look like this;

View Content → Add to Cart - > Initiate Checkout → Contact→ Add Payment Info → Purchase 

<aside>
⚠️ Changing these values later may cause your pixel to have to restart learning

</aside>

![step8 - select capi events.png](Connecting%20the%20Facebook%20Conversion%20API%20Pixel%20(CAPI%2085ec74eb94704e349e41bc0eb2abcfd2/step8_-_select_capi_events.png)

## 

## Select the Data to pass to Meta

Meta can use some identifiers you pass then to improve how Meta can match up Conversions. The more datapoints Meta has available to match a Facebook user who saw your ad. 

On this page check the boxes of the data you want to share with Meta.

![step9 - select the customer data points.png](Connecting%20the%20Facebook%20Conversion%20API%20Pixel%20(CAPI%2085ec74eb94704e349e41bc0eb2abcfd2/step9_-_select_the_customer_data_points.png)

## Review Setup

On this page we are confirming all the events we setup are correct. If the details are correct please click “Continue”

![step10 - review setup.png](Connecting%20the%20Facebook%20Conversion%20API%20Pixel%20(CAPI%2085ec74eb94704e349e41bc0eb2abcfd2/step10_-_review_setup.png)

## Close the Setup Wizard

Now you can click “Continue Pixel Setup” where you will see a popup with pixel instructions.

![step11 - Close the wizard.png](Connecting%20the%20Facebook%20Conversion%20API%20Pixel%20(CAPI%2085ec74eb94704e349e41bc0eb2abcfd2/step11_-_Close_the_wizard.png)

![step12 - close instructions.png](Connecting%20the%20Facebook%20Conversion%20API%20Pixel%20(CAPI%2085ec74eb94704e349e41bc0eb2abcfd2/step12_-_close_instructions.png)

## Copy the “TEST Event Code”

Now under “Test Events” you will see a test event code like in the image below. Please copy and paste this code for the next step 

![step13 - get test event code.png](Connecting%20the%20Facebook%20Conversion%20API%20Pixel%20(CAPI%2085ec74eb94704e349e41bc0eb2abcfd2/step13_-_get_test_event_code.png)

# Enable the Facebook Integration in your System to Connect to your new Pixel

Now that Facebook/Meta is all setup we can connect your System to it using the Facebook Integration.

Simply navigate to; Settings → Integrations → Tracking → Facebook Conversions

Then click “Enable”

![enable facebook integration.png](Connecting%20the%20Facebook%20Conversion%20API%20Pixel%20(CAPI%2085ec74eb94704e349e41bc0eb2abcfd2/enable_facebook_integration.png)

## Watch the setup video for the final step

[Integrations - Demo - 27 September 2022.mp4](Connecting%20the%20Facebook%20Conversion%20API%20Pixel%20(CAPI%2085ec74eb94704e349e41bc0eb2abcfd2/Integrations_-_Demo_-_27_September_2022.mp4)

<aside>
⚠️ Make sure your test events show correctly in the test tool. Also make sure the data you entered on your integration matches the info you provided when setting up your new pixel with Meta

</aside>