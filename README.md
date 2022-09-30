# DEMO  
### A flight reviews app built with Ruby on Rails and React.js
<img  align="center" alt="Coding" src="https://raw.githubusercontent.com/prashant54singh/Ruby_flight-/main/app/assets/images/openflights-demo.gif">  

## HOME PAGE  

![OpenFlights Home](https://github.com/zayneio/open-flights/blob/master/app/assets/images/index-demo.png)  
## REVIEW PAGE  

![OpenFlights Show](https://github.com/zayneio/open-flights/blob/master/app/assets/images/show-demo.png?raw=true)


---

This app uses:

* Ruby version: `2.7`
* Rails version: `6.0.3.4`
* Database: `postgresql`
* React version: `16.12.0`
* React Hooks API
* React Context API

## Running it locally
- run `bundle exec rails db:prepare`
- run `npm install` or `yarn install`
- run `bundle exec rails s`
- in another tab run `./bin/webpack-dev-server` (optional) 
- in another tab run `sidekiq` (optional, but necessary for things like password reset emails)
- navigate to `http://localhost:3000`

## Environment Variables
If you want functionality like password reset emails to work locally, you'll need to set the following environment variables in `config/application.yml` with your own unique values:
```
ROOT_URL: http://localhost:3000
SENDGRID_API_KEY: xxxxxxxxxxxxxx
SENDGRID_USERNAME: xxxxxxxxxxxxxx
SENDGRID_PASSWORD: xxxxxxxxxxxxxx
DEFAULT_FROM_EMAIL: you@example.com
```


