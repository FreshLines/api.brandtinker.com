# Brandtinker API

Brandtinker.com API is a Rails application that searches various websites for branding information. Some information is only accessible through scraping.

Thanks to Mechanize, we can automate the scraping of a few sites.

Our current build only supports acquiring information from Florida's SunBiz.

# Initial Setup
1. `bundle install`
2. `cp ./config/secrets.yml.example/ ./config/secrets.yml`
3. `Generate a secret token via 'rake secret'. Change the secret token.


## API Setup

Visit [markerapi.com](http://markerapi.com) and register. Use their username and password
to add to the secrets.yml