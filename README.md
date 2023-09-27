# Altudo Rating Review
This Application is build for give the rating for each employee and 

## Technical Stack
- NPM & Node installed
- Git should be installed
- 

git remote set-url origin ssh://git@github.com:RahulYadav-Altudo/strapi.git

## Setup Project 

Clone this repository with command   `git clone https://github.com/RahulYadav-Altudo/AltudoRatingReview.git`

### Backend

Go into the folder run this command/go into this command

`cd backend/`

Copy example environment variable file to `.env` with below command

`cp .env.example .env`

To install all packages run below command

`npm install`

`npm run develop`

Your backend server will run on this URL

`http://localhost:1337/`

### Frontend

For Frontend we have NextJS

Redirect to the fronend

`cd fronend/`

Copy example environment variable file to `.env` with below command

`cp .env.example .env`

### Next Authentication

For NextAuth we have run the command: (To run this command you should have openssl installed on your system)

`openssl rand -base64 32`

Add the value in your .env.local file

`NEXTAUTH_SECRET=<ABOVE_GENERATED_SECRETE>`

`NEXTAUTH_URL=http://localhost:3000`
For Dev you can use base URL for NextAUTH
For more information about the nextAuth you can see [here](https://next-auth.js.org/configuration/options)

To install all packages run below command

`npm install`

`npm run dev`

Your fronend server will run on this URL

`http://localhost:3000/`


For information you can see the documentation of 

Strapi 👉 [Strapi v4 developer documentation](https://docs.strapi.io/developer-docs/latest/getting-started/introduction.html)

NextJS 👉 [Next.js documentation](https://nextjs.org/docs/getting-started)


// api testin tool 
postman
thunder client
insomnia