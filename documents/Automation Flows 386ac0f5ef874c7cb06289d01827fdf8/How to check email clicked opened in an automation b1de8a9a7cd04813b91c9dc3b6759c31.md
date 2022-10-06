# How to check email clicked/opened in an automation flow?

<aside>
💡 [**What is an automation Flow?**](What%20is%20an%20automation%20Flow%208feeb15aee0f4939a902c2a0cf85c7dc.md)

</aside>

<aside>
💡 **[How to create a contact flow?](How%20to%20create%20a%20contact%20flow%20c76f686e2ed2416ba8b8f33c51e5d072.md)**

</aside>

 

<aside>
💡 [How to create an automation flow with a form?](How%20to%20create%20an%20automation%20flow%20with%20a%20form%20cf48e33ccc664e66bba18d0a4d231569.md)

</aside>

<aside>
💡 If you send an email to your client and your user opens that email, the system will consider that email as opened email. And if you send any links in that email and the user clicks on the link, the system will consider the email is clicked.

</aside>

# Steps to check email clicked/opened

### Add the ‘Email Send’ step

Under the ‘Messaging’ section, you will get the ‘Send Email’ step

![Untitled](../IN%20PROCESS%20Product%20FAQ%20Guides%20a986e24138d14caf8156bfe234b2e8fb/How%20to%20create%20an%20email%20template%2051083ee179e24e49a64c603e7355c70e/Untitled.png)

The system will allow you to configure that step

![Untitled](How%20to%20check%20email%20clicked%20opened%20in%20an%20automation%20b1de8a9a7cd04813b91c9dc3b6759c31/Untitled.png)

Please, make the changes as per your requirement.

<aside>
💡 To track email status (opened/clicked), you mush have to use a verified domain email. Otherwise, email tracking will not work. We can only detect emails sent from domain auth, Gmail or SMTP email will not be able to detect

</aside>

<aside>
💡 [Guideline to connect domain with your System](../Website%20Builder%20&%20Domains%20b3c2568e786e46a78bf5a689c73f291f.md)

</aside>

### Update domain URL **Shortener**

Please, navigate to the ‘Settings’ tab of the ‘Email Send’ step. On the ‘**Custom Domain URL Shortener’** dropdown, please select any option except ‘Do not Convert Links to Short Links’

![Untitled](How%20to%20check%20email%20clicked%20opened%20in%20an%20automation%20b1de8a9a7cd04813b91c9dc3b6759c31/Untitled%201.png)

### Add the ‘Wait For Email/SMS Reply/Click/Open’ step

Please add the ‘Wait For Email/SMS Reply/Click/Open’ step to your flow under the Email Send’ step. This step is available under the ‘Logic’ section.

![Untitled](How%20to%20check%20email%20clicked%20opened%20in%20an%20automation%20b1de8a9a7cd04813b91c9dc3b6759c31/Untitled%202.png)

### Configure the ‘Wait For Email/SMS Reply/Click/Open’ step

On the configuration tab, you need to set the monitoring step, waiting time, etc

![Untitled](How%20to%20check%20email%20clicked%20opened%20in%20an%20automation%20b1de8a9a7cd04813b91c9dc3b6759c31/Untitled%203.png)

Here, you can set the step that you want to monitor

![Untitled](How%20to%20check%20email%20clicked%20opened%20in%20an%20automation%20b1de8a9a7cd04813b91c9dc3b6759c31/Untitled%204.png)

Set the event status 

![Untitled](How%20to%20check%20email%20clicked%20opened%20in%20an%20automation%20b1de8a9a7cd04813b91c9dc3b6759c31/Untitled%205.png)

And set the waiting time

![Untitled](How%20to%20check%20email%20clicked%20opened%20in%20an%20automation%20b1de8a9a7cd04813b91c9dc3b6759c31/Untitled%206.png)

Now, please add the necessary steps as per your requirement

![Untitled](How%20to%20check%20email%20clicked%20opened%20in%20an%20automation%20b1de8a9a7cd04813b91c9dc3b6759c31/Untitled%207.png)