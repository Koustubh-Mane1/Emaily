# Emaily

Emaily is an application which is lets you send surveys (via email) to thousands of people at one time. It allows you to customise the content of the email, and tracks each response to the surveys in the dashboard.

### Logging In

When you first access the application, you will be prompted to login with your Google account. This is done securely and externally via Passport's Google OAuth 2.0. 

### Sending Surveys

Once you're all set up with some credits on your account, you can begin to send surveys. This is done by clicking the circular red "+" button in the bottom right of the page. This will redirect you to the Survey Form page, where you can insert all of the relevant data you wish to add to your surveys. You need to add all of the recipients in the "Recipients Lists" by inputting comma separated values. You will be alerted to any errors in the recipients list below the text box. Once you are happy with all of the values, you can click the green "Next" button to go to the reviewing page. Double check all fields here, and if you are happy with them, you can click the green "Send Survey" button to send the survey to all recipients.

### Getting Feedback

When the survey recipient responds to your email, either positively or negatively, then the dashboard will visually update with these responses. Every few minutes the dashboard will update these values, and the end result can be something like this:

## Technologies

### Front-End

- React 16
- Reactstrap
- Redux


### Back-End


- Express (Node.JS)
- Mongoose
- Nodemon
- Passport (Google OAuth 2.0)
- Stripe
