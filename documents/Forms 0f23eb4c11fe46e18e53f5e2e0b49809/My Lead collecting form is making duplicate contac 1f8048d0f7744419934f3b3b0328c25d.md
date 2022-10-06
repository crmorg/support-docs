# My Lead collecting form is making duplicate contacts.

<aside>
💡 When you build a form inside the system with standard fields like Firstname, Lastname, Email, Phone to collect your users/clients information, this form is called a lead collecting form. And you are also allowed to add more fields as per your requirements.

</aside>

<aside>
💡 When your users submit this form, the System will automatically create a contact/lead under your account. Sometimes, if your users submit this form multiple times, the system will duplicate contacts for each submission event. To prevent this duplication, you need to create a flow attached to your lead collecting form.

</aside>

<aside>
💡 [How to create an automation flow with a form?](../Automation%20Flows%20386ac0f5ef874c7cb06289d01827fdf8/How%20to%20create%20an%20automation%20flow%20with%20a%20form%20cf48e33ccc664e66bba18d0a4d231569.md)

</aside>

 

# Steps to stop making duplicate contact

### Add the ‘Lookup Contact’ step

Please, add the ‘Lookup Contact’ step under the ‘CRM’ section to your flow.

![Untitled](../Database%200e0a7e883e94414dba09548f5db29dd3/Is%20there%20any%20way%20to%20remove%20contacts%20that%20are%20dupli%203dd864e1009042cd939ff11db0aafd4d/Untitled.png)

### Configure the step

![Untitled](../Database%200e0a7e883e94414dba09548f5db29dd3/Is%20there%20any%20way%20to%20remove%20contacts%20that%20are%20dupli%203dd864e1009042cd939ff11db0aafd4d/Untitled%201.png)

You can use various contact fields for the lookup condition

![Untitled](../Database%200e0a7e883e94414dba09548f5db29dd3/Is%20there%20any%20way%20to%20remove%20contacts%20that%20are%20dupli%203dd864e1009042cd939ff11db0aafd4d/Untitled%202.png)

You can set multiple fields as conditions by clicking the ‘Add Field’ icon

![Untitled](../Database%200e0a7e883e94414dba09548f5db29dd3/Is%20there%20any%20way%20to%20remove%20contacts%20that%20are%20dupli%203dd864e1009042cd939ff11db0aafd4d/Untitled%203.png)

<aside>
💡 Please, don’t use ‘**Contact ID**’ as the lookup option. This field is always unique for each contact.

</aside>

You can set the relation between conditions

![Untitled](../Database%200e0a7e883e94414dba09548f5db29dd3/Is%20there%20any%20way%20to%20remove%20contacts%20that%20are%20dupli%203dd864e1009042cd939ff11db0aafd4d/Untitled%204.png)

Finally, save the step settings, connect all the steps, and publish the flow.