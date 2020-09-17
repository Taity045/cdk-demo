# BUILDING AND ECS CLUSTER WITH CDK

Configuration files for this repo can found in 'app.py'

Configuration should work out of the box

##Deploy

```
$ npm install -g aws-cdk
$ cdk synth
$ cdk deploy -c domain=mystaticsite.com -c subdomain=www
