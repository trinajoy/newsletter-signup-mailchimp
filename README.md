project by @trinajoy

## Newsletter Signup

Add a subscriber to a newsletter mailing list using mailchimp API

## Custom Environment Variables

- Use custom environment variables to hide Mailchimp API Key
- see `.env_sample` for how to add api key
- add `.env` to `.gitignore`
- add `dotenv` to project `npm i dotenv`
- require `dotenv` in app.js after requiring `express`
- use in app.js: `process.env.API_KEY`
- see documentation: https://medium.com/@asbillings2007/hide-your-api-keys-71e7bab3af69

## Heroku

- Procfile : tell Heroku how to launch the app
- add Config Vars : API_AUTH, API_KEY, LIST_ID
