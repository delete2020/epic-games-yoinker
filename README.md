# epic-games-yoinker
automatically yoink the free games from epic :)

## Instructions

### 1. [Fork](https://github.com/rodeknopje/epic-games-yoinker/fork) this repository.

### 2. Enable and add [github secrets](../../settings/secrets) for this repository

   
   <p align="ceneter"><img src="https://i.imgur.com/wJ5gXaZ.png"></p>
   
   Create the secrets: `USERNAME`, `PASSWORD` and `CAPTCHA`
   Fill you epic email in the `USERNAME` field and your password in the `PASSWORD` field.
   For the `CAPTCHA` field go to this [link](https://dashboard.hcaptcha.com/signup?type=accessibility) and fill sign up for Accessibility Access. After signing up go to your mail, right click the button in the mail and press "copy url adress". Paste the adress in your `CAPTCHA` secret it should look like this https://accounts.hcaptcha.com/verify_email/00000000-1a1a-2b2b-3c3c-1a2b3c4d5e6f
   
   
   


### 3. Enable [github actions](../../actions) for the forked repository.
   Press the green button.
   
### 4. Enjoy your games.
   This repository tries to claim your free games every 12 hours, dont try to shorten the intervall to much, the captcha token can only be used three times a day
