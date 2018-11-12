# himinds-iot-project-cloud-gcp-cloud-functions
Several different GCP cloud functions to handle data from IoT devices and work with Firebase solution

```bash
npm install -g firebase-tools
```

```bash
npm install -g firebase-tools
```

```bash
firebase login
```

or first 
```bash
firebase logout
```
If you need to switch accounts.

```bash
firebase init
```

Select:
* Functions: Configure and deploy Cloud Functions
* Default Firebase project 
* What language would you like to use to write Cloud Functions? JavaScript
* Do you want to use ESLint to catch probable bugs and enforce style? Yes
* Do you want to install dependencies with npm now? Yes

Edit your package.json and add

```json
 "engines": {
    "node": "8"
  }

```
