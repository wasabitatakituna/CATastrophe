# CATastrophe
A social media platform where you can share your purr-fect memes with fellow Cat Lovers!

## What CATastrophe does:
CATastrophe is an app where Cat Lovers can share cat memes with each other and enjoy other people's cat memes.

## To Update your Username or Delete your Account:
Please click on the profile tab and scroll to the bottom.
- Please note that changing your username will not update the username on previous posts you've made.
- Also note that deleting your account will not delete previous posts you've made.
Thank you!!

## Setup:
frontend setup:
```
cd frontend
npm i
```


backend setup:
```
cd frontend
npm i
```
create an environment file and then:
- put in a link to your mongodb database under the name ```MONGODB_URI```
- run ```openssl rand -base64 64``` in terminal and then paste the output under the name ```JWT_SECRET```

```
# .env format
MONGODB_URI=(your_mongodb_link)
JWT_SECRET=(your_jwt_secret_key)
```

## Links:
frontend: 

backend: 

## API Routes:
- /home
- /signup
- /login
- /logout
- /update
- /delete
- /profile
- /create-post

## Credits to the images:
All images I'm using are taken by myself or they are from friends (taken with permission) (and then turned into memes).