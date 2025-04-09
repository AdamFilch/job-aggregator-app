# Welcome to your Expo app 👋

This is an [Expo](https://expo.dev) project created with [`create-expo-app`](https://www.npmjs.com/package/create-expo-app).

## Get started

1. Install dependencies

   ```bash
   npm install
   ```

2. Start the app

   ```bash
    npx expo start
   ```

In the output, you'll find options to open the app in a

- [development build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go), a limited sandbox for trying out app development with Expo

You can start developing by editing the files inside the **app** directory. This project uses [file-based routing](https://docs.expo.dev/router/introduction).

## Get a fresh project

When you're ready, run:

```bash
npm run reset-project
```

This command will move the starter code to the **app-example** directory and create a blank **app** directory where you can start developing.

## Learn more

To learn more about developing your project with Expo, look at the following resources:

- [Expo documentation](https://docs.expo.dev/): Learn fundamentals, or go into advanced topics with our [guides](https://docs.expo.dev/guides).
- [Learn Expo tutorial](https://docs.expo.dev/tutorial/introduction/): Follow a step-by-step tutorial where you'll create a project that runs on Android, iOS, and the web.

## Join the community

Join our community of developers creating universal apps.

- [Expo on GitHub](https://github.com/expo/expo): View our open source platform and contribute.
- [Discord community](https://chat.expo.dev): Chat with Expo users and ask questions.
# job-aggregator-app


# References

https://www.reddit.com/r/webdev/comments/1ewb7wt/api_vs_rss_feeds_for_pulling_job_listings_for_a/
https://jobdataapi.com/
https://rapidapi.com/
https://theirstack.com/en/job-posting-api
https://remotive.com/remote-jobs/rss-feed
https://fantastic.jobs/
https://publicapis.dev/category/jobs
https://rapidapi.com/collection/job-search-apis



look into rss feeds
look into adzuna API

Last resort is to use something like selenium to scrape the website html instead of the data
Remotive
Tecnoemploe
y combinator
infojobs



# Flow

[Your App]
   ↓
[Background fetcher (runs every X mins)]
   ↓
[Call job board APIs or RSS feeds]
   ↓
[Store result in SQLite DB on phone]
   ↓
[User browses listings in the app]



# Possible issue 

how to get push notification?