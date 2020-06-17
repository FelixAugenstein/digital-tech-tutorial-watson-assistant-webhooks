<h1 align="center" style="border-bottom: none;">:rocket: IBM Digital Tech Tutorial: Cloud Functions</h1>
<h3 align="center">In this hands-on tutorial you will create a Watson Assistant that is able to send you a reminder via e-mail. You can tell Watson to "add a reminder to buy milk", Watson confirms the reminder, and the reminder is sent via e-mail to the destination email you provided.</h3>

## Prerequisites

1. Sign up for an [IBM Cloud account](https://cloud.ibm.com/registration).
2. Fill in the required information and press the „Create Account“ button.
3. After you submit your registration, you will receive an e-mail from the IBM Cloud team with details about your account. In this e-mail, you will need to click the link provided to confirm your registration.
4. Now you should be able to login to your new IBM Cloud account ;-)

## Set up the cloud function

After the login you will see your IBM Cloud Dashboard. Click the Cloud Functions button, then go to Actions and click create, to create a new action.

![Cloud Functions Button](readme_images/cloud-functions-button.png)

Give your action a name, keep the Default Package and choose Node.js as your runtime. Click create.

![Create Cloud Function Action](readme_images/create-cloud-function.png)

Copy and paste the `send-email-from-watson-assistant.js` code and configure `smtpConfig` with your host - for instance `smtp.gmail.com` if you use Gmail and your email and password.

![Configure smtpConfig](readme_images/configure-smtpConfig.png)

If you use Gmail you have to allow less secure apps and also enable the required functionality with the Captcha Enable. Without this, unfortunately the email reminder will not work. You can find detailed instructions [here](https://community.nodemailer.com/using-gmail/).

## Set up the Watson Assistant on the IBM Cloud


## If you have any questions just contact me
Felix Augenstein<br>
Digital Tech Ecosystem & Developer Representative @IBM<br>
Twitter: [@F_Augenstein](https://twitter.com/F_Augenstein)<br>
LinkedIn: [linkedin.com/in/felixaugenstein](https://www.linkedin.com/in/felixaugenstein/)
