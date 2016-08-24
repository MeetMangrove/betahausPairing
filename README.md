# betalunch
A web app to pairing people randomly with their email adress.

## How to run

- clone this repo
- `meteor npm i` (to install dependencies)
- set environment variables (see below)
- set your timezone and email in settings.json
- `MAIL_URL=YOUR_STMP_URL meteor --settings settings.json` (to run locally)

## Required environment variables

- `MAIL_URL`: URL of your SMTP server (for sending emails), including credentials (https://sendgrid.com/ for the creation of your STMP URL)

## Deployement on Scalingo

- create an account on Scalingo: https://scalingo.com/
- in the repo, install Scalingo: http://doc.scalingo.com/app/command-line-tool.html
- deploy meteor app with mongoDB addons: http://doc.scalingo.com/languages/javascript/nodejs/getting-started-with-meteor/
- setup settings and environment variables: http://doc.scalingo.com/languages/javascript/nodejs/meteor/