# How to create an SMS flow and send messages until there is a response from the client?

?

# Steps to send messages until there is a response from the client

### Create an SMS flow

<aside>
💡 [How to create an SMS flow?](How%20to%20build%20a%20SMS%20flow%20835cf36826e6410b810207b1a68fd414.md)

</aside>

### Add the ‘Wait For SMS Reply’ step.

Please, drag the Wait For SMS Reply step and you will have this step under the login section.

![Untitled](How%20to%20create%20an%20SMS%20flow%20and%20send%20messages%20until%20%2050867404c5c5425e98b638b82ec3985b/Untitled.png)

On the settings page, you can set the time that how long you want to wait for the reply.

![Untitled](How%20to%20create%20an%20SMS%20flow%20and%20send%20messages%20until%20%2050867404c5c5425e98b638b82ec3985b/Untitled%201.png)

And create at least on response lookup condition

![Untitled](How%20to%20create%20an%20SMS%20flow%20and%20send%20messages%20until%20%2050867404c5c5425e98b638b82ec3985b/Untitled%202.png)

Now, we have three branches 

![Untitled](How%20to%20create%20an%20SMS%20flow%20and%20send%20messages%20until%20%2050867404c5c5425e98b638b82ec3985b/Untitled%203.png)

**Timeout:** If there is no reply within the specified time

**No Match:** It means, the user replied, but the response lookup condition didn’t match

**Lookup Condition 1:** It means the user replied, and the response lookup condition also matched

As per our requirement, repeat the ‘Send SMS’ and ‘Wait for SMS Reply’ steps

![Untitled](How%20to%20create%20an%20SMS%20flow%20and%20send%20messages%20until%20%2050867404c5c5425e98b638b82ec3985b/Untitled%204.png)