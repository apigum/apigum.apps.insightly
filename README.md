# Insightly Connector

apigum.com utilizes the Insightly connector for building integrations with other popular cloud applications. We would love to get your code contribution for existing applications or for new ones you'd like to be using.

 For available Insightly integrations please visit this [page](https://www.apigum.com/apps/insightly).


## Setup

### App Fields:
- Name - name of application (e.g.: Stripe)
- Url - url of application (e.g.: https://www.stripe.com)
- ApiHelp - user instructions to obtaining api keys/credentials
- About - genernal description of the app
- Features - feature highlights in bullets
- Variables - array of variables used for api access (e.g.: apikey, accesstoken etc.)
- Tags - array of tags used to categorize the application (e.g.: CRM, Billing, E-Commerce etc.)
- GitUrl - repository url


### Action Fields:
 - Title - action title (e.g.: "Create Client")
 - Descripton - action description (e.g.: "Creates a new client")
 - Endpoint - endpoint url
 - HttpVerb - http method (e.g.: GET, POST etc.)
 - Body - sample escaped request payload in JSON format


### Trigger Fields:
 - Title - action title (e.g.: "Create Client")
 - Descripton - action description (e.g.: "Creates a new client")
 - Endpoint - endpoint url
 - HttpVerb - http method (e.g.: GET, POST etc.)
 - Body - sample escaped request payload in JSON format
 - Response - sample escaped response body in JSON array format
 - KeyField - name of property used to identify record key (for example "Id" or "ContactId")
 - PathToJsonArray - for use only when the Respose is an object that wraps your JSON array. For example enter 'data' if your JSON contains a property named data that holds the JSON array

