# Back-End boiler plate

Back end boiler plate for interns.

## Getting Started

```
npm i
npm run server
```

### Routes

All api endpoints that are available

Post endpoints:
```
users/signup - register a user
users/signin - login user
users/oauth/google - login with google
users/oauth/facebook - login with facebook (doesn't work in dev env)
users/forgot - forgot password (will receive token to entered email)
users/reset/:token - change password with token that was received in email

```
Get endpoints:
```
users/get/:id - get user by id
users/reset/:token - required for pass reset
```

### More info
In order to use social logins easily use these npm's in ur front end:

https://www.npmjs.com/package/react-google-login

https://www.npmjs.com/package/react-facebook-login

Also check configuration/index.js file for social login config.

There are some validations and some are missing. So make by urself :)


