# GlobalHack Emailing API
This code will be used to send out mass emails to potential sponsors and participants in GlobalHack.


## Setup
1. Create a Nylas account on [Nylas](https://www.nylas.com/)
2. Follow the setup guide(save your API key and use an email that you can grant access to)
3. Run these commands in the terminal within your project directory
```bash 
  npm init

  npm install
```
4. Create a .env file with the following and fill in each global variable:

NYLAS_CLIENT_ID=<INSERT YOUR CLIENT_ID>
NYLAS_API_KEY=<INSERT YOUR API_KEY>
NYLAS_API_URI=<https://api.us.nylas.com or https://api.eu.nylas.com>
NYLAS_GRANT_ID=<INSERT YOUR GRANT_ID>
EMAIL=<INSERT SENDER EMAIL>

5. Setup a script or run this in the terminal:

```bash 
  node index.js
```


## Documentation
- [GlobalHack](https://www.instagram.com/globalhack.id/)
- [Nylas - Setup](https://developer.nylas.com/docs/v3/quickstart/email/#get-your-application-credentials)
- [Nylas - Nylas Developers](https://developer.nylas.com/)