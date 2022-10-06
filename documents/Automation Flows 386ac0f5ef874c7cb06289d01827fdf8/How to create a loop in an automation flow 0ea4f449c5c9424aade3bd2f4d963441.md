# How to create a loop in an automation flow?

<aside>
💡 **[What is an automation Flow?](What%20is%20an%20automation%20Flow%208feeb15aee0f4939a902c2a0cf85c7dc.md)**

</aside>

<aside>
💡 [How to create a contact flow?](How%20to%20create%20a%20contact%20flow%20c76f686e2ed2416ba8b8f33c51e5d072.md)

</aside>

 

<aside>
💡 [How to create an automation flow with a form?](How%20to%20create%20an%20automation%20flow%20with%20a%20form%20cf48e33ccc664e66bba18d0a4d231569.md)

</aside>

<aside>
💡 For some cases, you might need to create a loop in your flow like you want to send the same email every 7 days. The system allows you to create this type of flow also.

</aside>

# Steps to create a loop

For example, you have a flow that you are using for sending emails.

![Untitled](How%20to%20create%20a%20loop%20in%20an%20automation%20flow%200ea4f449c5c9424aade3bd2f4d963441/Untitled.png)

### Add the ‘Wait For Amount of Time’ step

Under the 'Logic' section, you will have the 'Wait For Amount of Time' step. Please, add this step to your flow before the last step.

![Untitled](How%20to%20create%20a%20loop%20in%20an%20automation%20flow%200ea4f449c5c9424aade3bd2f4d963441/Untitled%201.png)

### Set loop time

You can set the waiting time as per your requirement. Such as you might want want to loop the flow in every three minutes. We can even choose the days.

![Untitled](How%20to%20create%20a%20loop%20in%20an%20automation%20flow%200ea4f449c5c9424aade3bd2f4d963441/Untitled%202.png)

### Add the ‘GoTo Another Step’

Under the 'Logic' section, we have another step 'GoTo Another Step'. Please, add this step to your flow.

![Untitled](How%20to%20create%20a%20loop%20in%20an%20automation%20flow%200ea4f449c5c9424aade3bd2f4d963441/Untitled%203.png)

### Configure the loop starting point

On the configuration, the system will allow you to choose the step which you want to set as a loop starting point.

![Untitled](How%20to%20create%20a%20loop%20in%20an%20automation%20flow%200ea4f449c5c9424aade3bd2f4d963441/Untitled%204.png)

Finally, save the setting, and ‘Save and Publish’’ the flow.

Now, you can remove this step from the flow

![Untitled](How%20to%20create%20a%20loop%20in%20an%20automation%20flow%200ea4f449c5c9424aade3bd2f4d963441/Untitled%205.png)

Finally, save and publish the flow.

![Untitled](How%20to%20create%20a%20loop%20in%20an%20automation%20flow%200ea4f449c5c9424aade3bd2f4d963441/Untitled%206.png)