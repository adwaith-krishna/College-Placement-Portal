# College-Placement-Portal
The College Placement Portal is a web-based application designed to facilitate the placement process in a college.Through the protal students can create their profile and the placement officer can review the profile and filter the students based on the criteria for each interview and can email the students who are eligible for attending a interview.



## Features

### Student Dashboard:
* View and manage student profile.
* Can access various resources for interview preperations.
* Can generate resume.(Currently not functional)
* Receive notifications about upcoming interviews and placement events.

### Admin Panel:
* Manage student details.
* Monitor placement activities.
* Can filter eligible students based on the requirements for interview.
* Can notify students through email after the filtering about the interviews.
* Can verify the student details.



## Getting Started
1. Clone the repository:
```console
git clone https://github.com/your-username/college-placement-portal.git
```


2. Go to [firebase](https://firebase.google.com/) and choose firestore and authentication.Then copy the config and update it in the code.
```js
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_AUTH_DOMAIN",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_STORAGE_BUCKET",
  messagingSenderId: "YOUR_SENDER_ID",
  appId: "YOUR_APP_ID"
};
```

3. Then go to [EmailJs](https://dashboard.emailjs.com/) and create a new account.Then create a new service and template and update the service ID,template ID and public key in the code.
```js
  emailjs.init("YOUR_EMAILJS_USER_ID");
  var serviceID = 'YOUR_EMAILJS_SERVICE_ID';
  var templateID = 'YOUR_EMAILJS_TEMPLATE_ID';
  var userID = 'YOUR_EMAILJS_PUBLIC_KEY';
```

4. Then run the index.html in localhost.



## Tech Stack
* Frontend: HTML, CSS, JavaScript
* Backend: JavaScript
* Database: Firestore
* Authentication: Firebase Authentication
* Email Services: EmailJS


> [!IMPORTANT]
> Do note that it should be running in localhost for the EMail service to work.



## Contributing
Contributions to the College Placement Portal are welcome! If you find any bugs or have suggestions for new features, please open an issue or submit a pull request.



## Acknowledgements
* This project was developed as a college mini project.
* I do understand that it is a basic one and may have many flaws in it.



**Kudos to @rahu1mane for working on the design and frontend.**
