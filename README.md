# hophacksappengineworkshop
Code for the HopHacks Spring 2016 App Engine Demo

## Prereqs to run locally:
* Python 2.7
* git
* Download App Engine Python SDK for your OS: http://goo.gl/kLIuF9
* Sign up for the free trial of AppEngine: http://goo.gl/oH6CEY [optional]
    * Only required if you want to push you app to production. Running it locally doesn't require a trial
    * Credit Card is required for verification. You won’t be billed unless you explicitly upgrade to a paid account
* Clone this repo:
```
git clone https://github.com/ch33zer/hophacks-app-engine-workshop.git
```

## Important commands:
Run the dev server:
```
dev_appserver.py .
```
Run the dev server, deleting all persistent database entries:
```
dev_appserver.py --clear_datastore=yes .
```
Launch to production (only available if you signed up for the free trial and created a project ID):
```
appcfg.py -A YOUR_PROJECT_ID update .
```
