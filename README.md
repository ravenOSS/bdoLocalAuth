# bdoLocalAuth

- app
    ------ models
    ---------- user.js  <!-- our user model -->
    ------ routes.js    <!-- all the routes for our application -->
    - config
    ------ auth.js      <!-- Social login credentials (facebook, twitter, google) -->
    ------ database.js  <!-- will hold our database connection settings -->
    ------ passport.js  <!-- configuring the strategies for passport -->
    - views
    ------ index.ejs    <!-- show our home page with login & sign-up links -->
    ------ login.ejs    <!-- show our login form -->
    ------ signup.ejs   <!-- show our signup form -->
    ------ profile.ejs  <!-- after a user logs in, they will see their profile -->
    - package.json      <!-- handle our npm packages -->
    - server.js         <!-- core file used to launch application -->

Based upon Scotch.io tutorial

https://github.com/scotch-io/easy-node-authentication/tree/local

github repo bdoLocalAuth maps to mbp/bdoSimpleAuth
