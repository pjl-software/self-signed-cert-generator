# self-signed-cert-generator

"Almost any website you visit today is protected by HTTPS. If yours isn’t yet, it should be. Securing your server with HTTPS also means that you can’t send requests to this server from one that isn’t protected by HTTPS. This poses a problem for developers who use a local development environment because all of them run on http://localhost out-of-the-box." [Ref](https://www.freecodecamp.org/news/how-to-get-https-working-on-your-local-development-environment-in-5-minutes-7af615770eec/)

This repo contains a bash self-signed certificate generator script that you can run locally to generate every file you need to develop locally using HTTPS.

## About the Script

## To Run

From your terminal:

- Run the script directly
  - `$ ./generate-a-self-signed-certificate`
- Run `Make` from within the repo
  - `$ make`

## For Help

From your terminal:

- Run the script directly with the `-h` option
  - `$ ./generate-a-self-signed-certificate -h`

## Expected Output

There will be a new directory in this repo named `generated-files` with ~9 files in it.

## Using the Output

I've used this script to generate files used in a Spring Boot back-end and Angular front-end [here](https://github.com/pjl-software/full-stack-auth-repo)

## Need More Help

Open an Issue
