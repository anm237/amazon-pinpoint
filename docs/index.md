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
    
    1. Traverse to the <a href="https://console.aws.amazon.com/pinpoint/">Amazon Pinpoint console</a> 

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
     
    3. Return to the Set up email page of the Amazon Pinpoint console. The email address shows as verified
        
        <img src="images/image6.png" class="inline"/>

    4. Once the email address is verified, we are ready to send an email messages.

        <img src="images/image7.png" class="inline"/> 
    
    5. Select Test Messaging from the menu bar on the left hand

        <img src="images/image8.png" class="inline"/> 
    
    6. Choose the Email channel
    
        <img src="images/image9.png" class="inline"/>
    
    7. Provide recipient email address that we verified for Destination type Email address as the recipient and it can be the same as the sender address, or additional email identities that we have verified
    
        <img src="images/image10.png" class="inline"/>
        
    8.  Choose Create a new message and provide details like Email Subject and Message body
    
        <img src="images/image11.png" class="inline"/>
    
    9. Select the Send message button

        <img src="images/image12.png" class="inline"/>
    
    10. Check the inbox
        
        <img src="images/image13.png" class="inline"/>

- **Step 3: Create a Message Template for SMS**
 
  - Message templates is a method to define consistent messages and reuse content more effectively, even across the projects. We can define message templates for email messages, push notifications, SMS messages, and voice messages.

  - Follow the below steps to define a message template
    
    1. Traverse to the <a href="https://console.aws.amazon.com/pinpoint/">Amazon Pinpoint console</a> then Message templates

        <img src="images/image14.png" class="inline"/> 
           
    2. Select Create a template
     
        <img src="images/image15.png" class="inline"/> 
     
    3. Select Email for the channel.
     
        <img src="images/image16.png" class="inline"/> 
     
    4. Provide name for the new template where as Description is an optional 
     
        <img src="images/image17.png" class="inline"/> 
    
    5. Next provide subject and message body
     
        **Email Subject**
          
          <img src="images/image18.png" class="inline"/>
        
        **Message body**

          <img src="images/image19.png" class="inline"/>
     
    6. Select Create to save the message template
      
        <img src="images/image20.png" class="inline"/>


