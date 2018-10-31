# PHP Script to Send OneSignal Push Notifications

<p>Send OneSignal Push Notification via PHP cURL</p>

<p align="center">
<img src="https://raw.githubusercontent.com/mskian/onesignal-php/master/screenshot.png">
</p>

- PHP cuRL
- OneSignal API
- Bootstrap4

## Install

- Clone this Github Respo

```
git clone https://github.com/mskian/onesignal-php
```

- Install Composer dependency packages

```
cd onesignal-php
composer install
```

- Add your OneSingal APP API KEY and APP ID  in `.env` File (You can Find the APP ID and REST API KEY in your APP's Settings page)

```
touch .env
```

File - `.env`  👇 👇 👇 put this on `.env` file

```
APIKEY = "YOUR REST API KEY"
APPID = "YOUR ONESIGNAL APP ID"
```

- If you are going to Run this Script Locally then Execute with PHP CLI Built-in Web server

```
php -S localhost:8080
```

or

```
php -S 127.0.0.1:8080
```

### License

MIT
