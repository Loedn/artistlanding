# README

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.0.8.

## Meaning

this repo serves as a reminder on how to deploy angular apps to heroku using a revised method from [this article](https://medium.com/@hellotunmbi/how-to-deploy-angular-application-to-heroku-1d56e09c5147)

## CHANGES FROM ARTICLE

`"postinstall":"ng build --aot=prod"`

in server.js
`app.use(express.static('./dist/yourappname'));`

`res.sendFile(path.join('./dist/yourappname/index.html'));`

yourappname can be found by looking at the dist subfolder that will appear when you run `ng build`
