# Rudder: A BLE Social App

## Start screen

### Before you begin...

Listed below are some important details that need special attention.

**IMPORTANT:** The app must be hosted on a server (local or not) for the OAUTH to work.

### Firebase Hosting

>firebase init

**Optional:** You may need to manually select the public root folder by editing the "firebase.json" file.

**Optional:** You may need to manually add project

Once you have all your files in the public root directory, you're ready to serve/deploy your app.
>firebase serve

### Firebase UI

There are several methods of including Firebase UI in our project. I've chosen to use the CDN method as it's the simplest of them all.

Step 1
Add FirebaseUI using CDN
Step 2
Add '#firebase-auth-container' to the element
Step 3
Run the start code

**NOTE:** You can configure the UI by passing an object with your custom configs.

