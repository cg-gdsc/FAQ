# Frequently Asked Questions

- [Where do I find the videos for the Tutorials?](#where-do-i-find-the-videos-for-the-tutorials)
- [How can I access my AWS account?](#how-can-i-access-my-aws-account)
- [The Sagemaker studio error states: Failed to change instance; what should I do?](#the-sagemaker-studio-error-states-failed-to-change-instance-what-should-i-do)


## Where do I find the videos for the Tutorials?

- You can find the videos on our Capgemini Stream. Click [here](TODO: add link).

## How can I access my AWS account? 

- After your teams registration, you should have received an confirmation e-mail. The e-mail looks like this 
> TODO: add mail screenshot 
- After your confirmation, you will receive an e-mail from AWS (no-reply@login.awsapps.com) with the subject: 'Invitation to join AWS Single Sign-On'. This e-mail looks like this:
![](./screenshots/AWS_invite_mail.png)
- Click on the button 'Accept Invitation' and enter your username from the invitation e-mail. You will be prompted to set a new password. 
- You can now login using the link in the invitation e-mail under 'User portal URL'. The portal looks like this:
![](./screenshots/aws_apps_portal.png)
- You will see your AWS Account after you logged in. Now you can click on 'Management Console' to access it.  

## The Sagemaker studio error states: Failed to change instance; what should I do?

Error message:

![](./screenshots/failed_to_change_instace.png)

- What a few minutes. The instance is currently starting or stopping. After around 5-10 min, you should be able to either use it or start it again. 
- Please check the resources tab in the left pane of Sagemaker Studio for more information of your current instances.
- If you see the instance there, please make sure to select the kernel image first and afterwards the instance, if necessary.  
