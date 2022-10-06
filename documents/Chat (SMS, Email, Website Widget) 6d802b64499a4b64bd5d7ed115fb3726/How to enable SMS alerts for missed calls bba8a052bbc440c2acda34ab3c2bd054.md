# How to enable SMS alerts for missed calls?

# Steps to enable the SMS alters for missed calls

### Add a phone number

The system offers the VoIP service. You can buy a number inside the system or port any existing number to the system.

<aside>
💡 [How to buy a phone number?](../VoIP%20Phone%209848cf9f667649a98f764a746ae5abb2/How%20to%20buy%20a%20phone%20number%20e2b786f9da78440eafb7eb7a3b4b4b17.md)

</aside>

 

### Create a call flow

<aside>
💡 [How to create a call flow?](../Automation%20Flows%20386ac0f5ef874c7cb06289d01827fdf8/How%20to%20create%20a%20call%20flow%20f57fd5df42ba47539f77949f05355cf5.md)

</aside>

### Add the ‘Transfer Call’ step

Please, add the ‘Transfer Call’ step under the ‘Phone’ section.

![Untitled](../IN%20PROCESS%20Product%20FAQ%20Guides%20a986e24138d14caf8156bfe234b2e8fb/How%20to%20create%20a%20simple%20call%20flow%20for%20inbound%20calls%201e5d0b6cfd3548f6ba7d8e2ec94fac62/Untitled%203.png)

And configure it as per your requirements.

![Untitled](../IN%20PROCESS%20Product%20FAQ%20Guides%20a986e24138d14caf8156bfe234b2e8fb/How%20to%20create%20a%20simple%20call%20flow%20for%20inbound%20calls%201e5d0b6cfd3548f6ba7d8e2ec94fac62/Untitled%204.png)

Please, make sure you have selected your extension to transfer the calls

![Untitled](How%20to%20enable%20SMS%20alerts%20for%20missed%20calls%20bba8a052bbc440c2acda34ab3c2bd054/Untitled.png)

Now, we have two options for the transfer call step 

![Untitled](How%20to%20enable%20SMS%20alerts%20for%20missed%20calls%20bba8a052bbc440c2acda34ab3c2bd054/Untitled%201.png)

Once the call is transferred, you can simply connect that option to the ‘Hangup Call’ step if you don’t need any other steps.

![Untitled](How%20to%20enable%20SMS%20alerts%20for%20missed%20calls%20bba8a052bbc440c2acda34ab3c2bd054/Untitled%202.png)

### Add The SMS Send step

For the ‘No Answer’ Step, you need to add the ‘SMS Send’ step to get SMS notification

![Untitled](How%20to%20enable%20SMS%20alerts%20for%20missed%20calls%20bba8a052bbc440c2acda34ab3c2bd054/Untitled%203.png)

To use this step, you need to enable SMS service for the VoIP numbers

<aside>
💡 [How to enable SMS service?](How%20to%20create%20an%20SMS%20plan%2013a104b417774c86bc15f633a8ab35b7.md)

</aside>

Here you will get the option to configure the SMS step

![Untitled](How%20to%20enable%20SMS%20alerts%20for%20missed%20calls%20bba8a052bbc440c2acda34ab3c2bd054/Untitled%204.png)

You can choose the ‘Custom Phone Number’ option to send a notification to any number

![Untitled](How%20to%20enable%20SMS%20alerts%20for%20missed%20calls%20bba8a052bbc440c2acda34ab3c2bd054/Untitled%205.png)

Now, save and publish the flow if you don’t need any other steps

![Untitled](How%20to%20enable%20SMS%20alerts%20for%20missed%20calls%20bba8a052bbc440c2acda34ab3c2bd054/Untitled%206.png)