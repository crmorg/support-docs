# Is there any way to remove contacts that are duplicated in the system?

<aside>
💡 [What's an automation flow?](../Automation%20Flows%20386ac0f5ef874c7cb06289d01827fdf8/What%20is%20an%20automation%20Flow%208feeb15aee0f4939a902c2a0cf85c7dc.md)

</aside>

# Steps to remove duplicate contacts

### Start building a contact flow

<aside>
💡 [**How to create a contact flow?**](../Automation%20Flows%20386ac0f5ef874c7cb06289d01827fdf8/How%20to%20create%20a%20contact%20flow%20c76f686e2ed2416ba8b8f33c51e5d072.md)

</aside>

### Add the ‘Lookup Contact’ step

Please, add the ‘Lookup Contact’ step under the ‘CRM’ section to your flow.

![Untitled](Is%20there%20any%20way%20to%20remove%20contacts%20that%20are%20dupli%203dd864e1009042cd939ff11db0aafd4d/Untitled.png)

### Configure the step

![Untitled](Is%20there%20any%20way%20to%20remove%20contacts%20that%20are%20dupli%203dd864e1009042cd939ff11db0aafd4d/Untitled%201.png)

You can use various contact fields for the lookup condition

![Untitled](Is%20there%20any%20way%20to%20remove%20contacts%20that%20are%20dupli%203dd864e1009042cd939ff11db0aafd4d/Untitled%202.png)

You can set multiple fields as conditions by clicking the ‘Add Field’ icon

![Untitled](Is%20there%20any%20way%20to%20remove%20contacts%20that%20are%20dupli%203dd864e1009042cd939ff11db0aafd4d/Untitled%203.png)

<aside>
💡 Please, don’t use ‘**Contact ID**’ as the lookup option. This field is always unique for each contact.

</aside>

You can set the relation between conditions

![Untitled](Is%20there%20any%20way%20to%20remove%20contacts%20that%20are%20dupli%203dd864e1009042cd939ff11db0aafd4d/Untitled%204.png)

### Set action field’s value

For the dropdown ‘**Action to take when Contact Matched’,** please select the value ‘Delete existing older contact and keep the newest contact’

![Untitled](Is%20there%20any%20way%20to%20remove%20contacts%20that%20are%20dupli%203dd864e1009042cd939ff11db0aafd4d/Untitled%205.png)

Save the settings. Please connect all the steps, and publish the flow

![Untitled](Is%20there%20any%20way%20to%20remove%20contacts%20that%20are%20dupli%203dd864e1009042cd939ff11db0aafd4d/Untitled%206.png)

### Add all contacts to the flow

<aside>
💡 [How to add all contacts to a flow?](../Automation%20Flows%20386ac0f5ef874c7cb06289d01827fdf8/How%20to%20select%20all%20contacts%20and%20add%20them%20to%20a%20flow%20186cdc6245344d7e9da2e3914e404af1.md)

</aside>