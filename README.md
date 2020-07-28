### Jotting down some notes:

This application lives on https://agreeable-mud-0c21e7f03.azurestaticapps.net, using Azure Static Web Apps.
Commits to master branch on this repo will automatically update the website.

1. Created azure static webapp with ci/cd from github chrfrenning/msaltest
1. Application is registered in Active Directory on tenant christopherfrenning.onmicrosoft.com
1. Enable CORS on storage account
1. Very simple index.html page with js calling msal.js, opens popup for auth (works!)