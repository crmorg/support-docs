# NameCheap - How to connect your  Domain for Website Hosting & Email

<aside>
💡 **[What is a domain?](What%20is%20a%20Domain%2072eb36b2d10048a2b5c06c6de4786def.md)**

</aside>

# Steps to connect the domain with System

### Open the domain panel

Navigate to the domain panel by clicking the “Sites” on the left side menu. Then when you have that page open you will see a link to “Connected Domains” on the top of your page, please click that. 

![Screenshot_16.png](NameCheap%20-%20How%20to%20connect%20your%20Domain%20for%20Website%20fee5b104b86d46a1a50908ff260de58a/Screenshot_16.png)

Now, click on the ‘Add Domain’ button to add your domain with System

![Screenshot_17.png](NameCheap%20-%20How%20to%20connect%20your%20Domain%20for%20Website%20fee5b104b86d46a1a50908ff260de58a/Screenshot_17.png)

### Select domain type

The system will allow you to add a free domain or custom domain. For our case, we will select the second option, and put your domain name.

<aside>
💡 **[What is the difference between a Free Domain and a Custom domain?](../What%20is%20the%20difference%20between%20a%20free%20domain%20and%20a%20f780a7c8ac044541ae2172ad2589df77.md)**

</aside>

![Screenshot_18.png](NameCheap%20-%20How%20to%20connect%20your%20Domain%20for%20Website%20fee5b104b86d46a1a50908ff260de58a/Screenshot_18.png)

Click on the ‘Next’ button. 

### Select services

<aside>
💡 [System Services](What%20is%20a%20Domain%2072eb36b2d10048a2b5c06c6de4786def.md)

</aside>

Now, the system will offer you System services. By default, the Website Hosting service will be enabled.

<aside>
💡 **When to use email sending?**
If you also need the Email service, please, click on the checkbox of the second tab, and add the email address that you want to add with System for email services.

</aside>

![Screenshot_19.png](NameCheap%20-%20How%20to%20connect%20your%20Domain%20for%20Website%20fee5b104b86d46a1a50908ff260de58a/Screenshot_19.png)

<aside>
💡 Enabling email services with System will not hamper your existing email services.

</aside>

![Screenshot_20.png](NameCheap%20-%20How%20to%20connect%20your%20Domain%20for%20Website%20fee5b104b86d46a1a50908ff260de58a/Screenshot_20.png)

Please, click on the ‘Next’ button. 

### Choose faster CDN (optional)

Now, the system will offer you the option to choose a faster CDN for a better web service experience for your users. Please, click on the ‘No, Thank You’ button unless you want a faster CDN for $5/month.

![Screenshot_30.png](NameCheap%20-%20How%20to%20connect%20your%20Domain%20for%20Website%20fee5b104b86d46a1a50908ff260de58a/Screenshot_30.png)

### Collect DNS records

Please, wait for a while, the system will provide you with the required DNS records that you need to add to your Godaddy registrar.

![Screenshot_23.png](NameCheap%20-%20How%20to%20connect%20your%20Domain%20for%20Website%20fee5b104b86d46a1a50908ff260de58a/Screenshot_23.png)

# Separating DNS record

### DNS record for Web Hosting

As per the screenshot, the first two records are the DNS record for the web hosting service. Among them, first one is an ‘A’ type DNS record

![Untitled](How%20to%20connect%20Domain%20with%20System%209cba3b5055774ff48d089f03590a9c97/Untitled%202.png)

### DNS record for Email Service

As per the screenshot, the last three records are related to the email services. All of these records are CNAME records.

![Untitled](How%20to%20connect%20Domain%20with%20System%209cba3b5055774ff48d089f03590a9c97/Untitled%203.png)

<aside>
💡 If you need only one specific service, then you can ignore DNS records related to other services.

</aside>

<aside>
💡 **[Differences Between A and CNAME Records](Differences%20Between%20A%20and%20CNAME%20Records%20452c277d4cba48c3aaea5ad9cc7cb1fe.md).**

</aside>

# Steps to add DNS record to NameCheap Account

### Select domain

After signing in to your NeamCheap account, Select **Domain List** from the left sidebar and click on the **Manage** button next to your domain

![https://namecheap.simplekb.com/SiteContents/2-7C22D5236A4543EB827F3BD8936E153E/media/nctutmanage.png](https://namecheap.simplekb.com/SiteContents/2-7C22D5236A4543EB827F3BD8936E153E/media/nctutmanage.png)

### Open DNS manager

Navigate to the **Advanced DNS** tab at the top of the page:

![https://namecheap.simplekb.com/SiteContents/2-7C22D5236A4543EB827F3BD8936E153E/media/advanced_dns.png](https://namecheap.simplekb.com/SiteContents/2-7C22D5236A4543EB827F3BD8936E153E/media/advanced_dns.png)

Find the **Host records** section and click on the **Add New Record** button:

![https://namecheap.simplekb.com/SiteContents/2-7C22D5236A4543EB827F3BD8936E153E/media/addnewrecord.png](https://namecheap.simplekb.com/SiteContents/2-7C22D5236A4543EB827F3BD8936E153E/media/addnewrecord.png)

### Select record type

To select the proper type of DNS record, you can define that from System-provided DNS records. Please, check the screenshot

![Untitled](Afrihost%20-%20How%20to%20connect%20your%20Domain%20for%20Website%20%203e25ff1f614044f78542f8bf452d40d1/Untitled%205.png)

### Sample format of DNS record

![Untitled](NameCheap%20-%20How%20to%20connect%20your%20Domain%20for%20Website%20fee5b104b86d46a1a50908ff260de58a/Untitled.png)

**‘A’ type of record**

Host -> @

Value-> 185.93.1.243

There is no need to change any other default values. Please click on the 'Add record' button to save the record.

**‘CNAME’ type of record**

You will have to add the CNAME records in the following way.

Host -> em3206

Value -> [u22813504.wl005.sendgrid.net](http://u22813504.wl005.sendgrid.net/)

TTL -> 24 hour

# Check the nameservers

Sign in to your **Namecheap account.** Select **Domain List** from the left sidebar and click the **Manage** button next to your domain:

![https://namecheap.simplekb.com/SiteContents/2-7C22D5236A4543EB827F3BD8936E153E/media/PDNS_enable2.png](https://namecheap.simplekb.com/SiteContents/2-7C22D5236A4543EB827F3BD8936E153E/media/PDNS_enable2.png)

Find the **Nameservers** section and make sure **Namecheap BasicDNS/Namecheap Web Hosting DNS**  is selected.

![https://namecheap.simplekb.com/SiteContents/2-7C22D5236A4543EB827F3BD8936E153E/media/selectNSs.png](https://namecheap.simplekb.com/SiteContents/2-7C22D5236A4543EB827F3BD8936E153E/media/selectNSs.png)