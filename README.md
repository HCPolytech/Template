# How to create a new Project?

## Secrets
### GH_TOKEN - Github Token
### SFDX_AUTH_URL - Auth URL to Prod 
#### sf org login web --alias prod -r https://login.salesforce.com
#### sf org display -o prod --verbose
### SFDX_DEV_AUTH_URL - Auth URL to Dev 
#### sf org login web --alias dev -r https://test.salesforce.com
#### sf org display -o dev --verbose
## Variables
### DISABLE_SCHEDULE - if TRUE actions schedule is turned off
