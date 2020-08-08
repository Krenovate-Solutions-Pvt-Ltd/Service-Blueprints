# **Domain Name Systems**
DNS is the control panel for the domain names you buy on websites like Godaddy. All websites run on different servers. Your domain name is linked and attached to a particular server through the DNS.


Every server has a public IP address by which it is identified. For example the server IP address for Krenovate.com is 64.90.44.34. It is difficult to remember an IP Address, and that is why it becomes necessary to attach this IP address to the domain name of your organisation. Humans are inclined to remember names rather than numbers.


DNS system allows you to manage multiple things through the different set of records available in the DNS system. We will discuss the most important records in the DNS, which are as follows:

>**1. Nameservers**

>**2. A records**

>**3. CNAME Records** 

>**4. MX Records**

>**5. TXT Records**

You can access the DNS records of your domain by logging into your domain management account. I generally use Godaddy to buy domains, the below image is a snapshot of the account I have at Godaddy to manage the domains I own.

It has various domains bought by my organisation. If you look closely, in front of every domain name you will find a prominent button with the CTA ‘DNS’. By clicking this you will reach the DNS records of the respective domain name. 
## Reminder: pdf2-image1 to be added
### **1. Nameservers**
Nameservers help you identify the hosting service for the particular domain name. For example, if i have to host my domain on Dreamhost which is a web hosting service, I have to point my domain to Dreamhost using the Dreamhost nameservers.

Each domain is pointed to a minimum of two nameservers. Nameservers are always managed from the domain management account. Look at the following image, which is a snapshot of the nameservers of Krenovate.com.
## Reminder: pdf2-image2 to be added
As you can see in the above image nameservers of Krenovate.com point to Dreamhost,
making it clear that www.krenovate.com is hosted on Dreamhost.
Nameservers are generally written in the format ‘ns1.servername.com’. Also the particular nameservers help you identify the place from where you can manage the DNS records. DNS records are always available and can be modified from the hosting service provider of your website. If I have to make any changes to the DNS records of Krenovate.com, I will have to do the same in my Dreamhost Hosting Account.
To help you understand better, let me give you possible two scenarios. 
>**Scenario 1** - Domain Provider and Hosting Provider are the same.This simply means that you bought a *domain on Godaddy* and have also bought *hosting services from Godaddy* itself.

>**Scenario 2**- Domain Provider and Hosting Provider are different This is the scenario of Krenovate.com, the *domain name Krenovate.com has been bought and managed on Godaddy*, while the *website Krenovate.com is hosted on Dreamhost*.

The following table will help you understand where you will manage your DNS records
and nameservers in the aforementioned scenarios.

| Domain Management| Scenario 1 | Scenario 2
| -------- | ----------- | -----------|
| **Nameservers**<br>The nameservers<br>are always managed<br>through domain<br>provider account.  | Godaddy |Godaddy |
| **DNS Records**<br>The DNS records are<br>always managed through<br>hosting provider account. | Goddady | Dreamhost |


#### **Scenario 1**
 The following image will show you that you can see and manage both nameservers and DNS records from your Godaddy account
## Reminder: pdf2-image3 to be added

#### **Scenario 2**
The following image will show you that you can only see and manage nameservers from your Godaddy account and it says DNS records cannot be displayed as nameservers are pointed to Dreamhost.

## Reminder: pdf2-image4 to be added
### **2. A Records**
The A Record is the most important record as it connects your domain name to the
relevant IP address of your hosting server. The following image will show you how to add or edit an A Record in your DNS Records.
## Reminder: pdf2-image5 to be added
 A Record has the following elements:

- **Type of Record** - A Record
- **Host** - @ The host name for the record, without the domain name.
- **Points to** - The IP address of hosting server
- **TTL** - Time to go live

### **3. CNAME Records**
CNAME Records are used for managing the subdomains of a website. The following image will show you how to add or edit a CNAME Record in your DNS Records.

## Reminder: pdf2-image6 to be added
A typical CNAME Record has the following elements:

- **Type of Record** - CNAME Record

- **Host** - The name you want to keep for your subdomain

- **Points to** - The IP Address of your hosting server of the subdomain

 - **TTL** - Time to go live
### **4. MX Records**
MX Records are used for managing the email services of a domain. For example, email ID sharmapuneet@krenovate.com has been running on GSuite, the business version of Gmail. The following image will show you how to add or edit an MX Record in your DNS Records.


## Reminder: pdf2-image7 to be added
A typical MX Record has the following elements:

- **Type of Record** - MX Record

- **Host** - @ (This means that you are running email services on your domain name)

- **Points to** - The hosting address of email provider (In this case the hosting provider is
Google)

- **Priority** - Generally email providers will share multiple MX records with you, and a
priority for each of them as well.

- **TTL** - Time to go live
### **4. TXT Records**
The TXT Records are text records and generally used for verifying ownership of a domain name. Many online service providers to activate their services on your domain name, instruct you to add a custom and unique TXT Record. For example to activate Gsuite on my domain for emailing, I had to add the following TXT Record. 

## Reminder: pdf2-image8 to be added
A typical TXT Record has the following elements:


- **Type of Record** - TXT Record

- **Host** - @ (This means that you are pointing to your own domain name)

- **TXT Value** - The unique text record shared by some other organisation

- **TTL** - Time to go live
