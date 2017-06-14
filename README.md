# Node.js Loginapp

This is a user login and registration app using Node.js, Express, Passport and Mongoose. It is part of the YouTube series [here](https://www.youtube.com/watch?v=Z1ktxiqyiLA)

### Version
1.1.0

### Usage


### Installation

Loginapp requires [Node.js](https://nodejs.org/) v4+ to run.

```sh
$ npm install
```

```sh
$ npm start
```


##### Adding Pages #####

*loginapp/routes/users.js
*add pages info under the correct area (labeled at top of page)


TODO: 
- Fix "Checkbox" validation on registration page. Not currently validating
	* is tied to routes/user.js where validation occurs
	* setup email
	* when user digitally signs waiver, send email to user,admin email
		* consider parsing waiver with signature into pdf file for email

