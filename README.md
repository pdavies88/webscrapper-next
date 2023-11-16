# Next.js 14 Webscrapper

## Technologies

- Next.js: A React framework for building web applications. It is used for both the frontend and the backend of the application.
- Tailwind CSS: A utility-first CSS framework for rapidly building custom designs. It is used for styling the application.
- TypeScript: A statically typed superset of JavaScript. It is used for writing the code.
- Mongoose: An Object Data Modeling (ODM) library for MongoDB and Node.js. It is used for defining the product schema and interacting with the MongoDB database.
- Nodemailer: A module for Node.js applications to allow easy email sending. It is used for sending email notifications to users.
- Axios: A promise-based HTTP client for the browser and Node.js. It is used for making HTTP requests to scrape product details from Amazon.
- Cheerio: A fast, flexible, and lean implementation of core jQuery designed specifically for the server. It is used for parsing the HTML response from the Amazon product page.
- React Responsive Carousel: A lightweight carousel component for React. It is used for displaying a carousel of images on the home page.
- Google Fonts: A library of free licensed font families. It is used for defining the font styles in the application.

## Getting Started

Install dependencies:

```bash
npm i
```

First, run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Bright Data

- Set up Bright Data's Unblocker tool via https://brightdata.com/cp/zones/unblocker
- Create a configuration and add the username and password to a .env file

## Mongo DB

- Create a new database
- Connect to database
- In MongoDB Drivers copy and paste the connection string into the .env file
- Replace "password" with newly created database password

## Nodemailer

- Create a Hotmail email account
- In `lib/nodemailer` add your email address as `user` in the `auth` and `mailOptions` objects
- Add Hotmail password to .env file

## Cron Job

- Deploy the application
- Create an account via [https://cron-job.org/en/](https://cron-job.org/en/)
- Create a new job pointing at the apps api cron endpoint `/api/cron`
- Schedule job to run at the interval you would like
