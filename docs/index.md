## Amazon Pinpoint

**Introduction**

- Amazon Pinpoint is an AWS service which allow to occupy the customers across multiple messaging channels. We can leverage Amazon Pinpoint to send push notifications, emails, SMS text messages, and voice messages. 

- Amazon Pinpoint allows to send customer oriented messages with better experiences which strengths the association with the customers and reduce the agitate.

- Amazon Pinpoint provides functionalities such as:

  - Marketing campaigns and journeys
  - Transactional messages
  - Analytics tools
  - Generate predictions

- In this tutorial we will focus on first creating a Pinpoint project and then configuring an email and a SMS based notification to send personalized messages

- **Step 1: Create an Amazon Pinpoint project**
  
  - A project in Amazon Pinpoint is a batch of configurations, customer information, segments, and campaigns
  - Follow the below steps to deploy project in Amazon Pinpoint
    
    1. Traverse to the <a href="https://console.aws.amazon.com/pinpoint/">Amazon Kendra console</a> 

        <img src="images/image1.png" class="inline"/> 
           
    2. Enter project name and select Create a project 
     
        <img src="images/image2.png" class="inline"/> 
     
    3. Once the project is created, we are ready to add features to the project
     
        <img src="images/image3.png" class="inline"/> 

- **Step 2: Configure & Send Email message**
    
    1. On the Configure features page, traverse to Project features > Email/Configure to Set up email.

        <img src="images/image3.png" class="inline"/> 
           
    2. Next we will verify an email identity, an identity can be either an email address or a domain. Once the domain is verified, we can send email from any email address on that domain.
     
        <img src="images/image4.png" class="inline"/> 
        
        **Verification email**
        
        <img src="images/image5.png" class="inline"/> 
        
        **Post verification**
        
        <img src="images/image6.png" class="inline"/> 
     
    3. Return to the Set up email page of the Amazon Pinpoint console. Your email address shows as verified. Click the Save button.

    4. Your email address is now verified. You are ready to send email messages.


     
        <img src="images/image3.png" class="inline"/> 


- **Step 3: Configure & Send SMS message**
