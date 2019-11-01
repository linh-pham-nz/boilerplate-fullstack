# Fullstack boilerplate

knex branch has been merged to master already (knex not yet deleted as unsure if any issues as yet)

To get started:

```
git clone https://github.com/dev-academy-challenges/boilerplate-fullstack [your-project-name]
cd [your-project-name]

create new repo on GitHub using [your-project-name]
git remote set-url https://github.com/organisation-name/your-project-name # to set remote url

npm install # to install dependencies
npm run dev # to start the dev server
```

You can find the server running on [http://localhost:3000](http://localhost:3000).

This repo includes:

* a single, simple API endpoint (`/api/v1/fruits`)
* a single React component (`<App />`)
* a fake database module (`db.js`)
* an API client module (`apiClient.js`)
* configuration for Jest and Enzyme (including JSDOM)
* configuration for server-side debugging in VS Code
* a single client-side test (`/tests/client/App.test.js`)
