# signapp
Sign Approval Application for guidance and conseling Lecturer

## Requirement
 * heroku account
 * python 3
 * Redis Cloud add-on
 * git
 * heroku cli client
 * Google API for sign in and spreadsheet access
 

### Instalation
Using Heroku
```sh
# heroku create signappname
# git clone https://github.com/awangga/signapp.git
# cd signapp
# heroku git:remote -a signappname
# heroku addons:create rediscloud
# git push heroku master
# heroku logs
# heroku ps -a signappname
```

To generate QRCode please use awangga kepo repository.


