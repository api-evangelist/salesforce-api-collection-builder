# Salesforce REST API Postman Collection Builder Collection
This is a Postman collection for dynamically building a Postman collection. It uses the Salesforce REST API to pull a list of objects for a specific version of the Salesforce REST API and then builds a Postman collection based upon the list of objects.

The Postman collection has three separate requests:

1. **List of All Versions** - Pulls a list of all available versions of the Salesforce REST API.
2. **List All Objects For Versions** - Pulls a list of all the available objects for the authenticated Salesforce account.
3. **Build Collection** - Pulls a list of all the available objects for the authenticated Salesforce account, and builds requests for each object and available resources.

You will need the environment enclosed in this repository with the base URL of your Salesforce account, as well as your Postman API key to operate. Once run it will add over 1000 individual API requests to a new folder with the collection. It takes 30-60 seconds to finish building all of the individual requests using the Postman API and sync with the local collection.

Here are two blog posts that introduce the work going into this project:

- [Taming The Salesforce API Scope](http://apievangelist.com/2019/12/18/taming-the-salesforce-api-scope/)
- [A Dynamic Salesforce REST API Postman Collection Builder Collection](http://apievangelist.com/2020/01/06/a-dynamic-salesforce-rest-api-postman-collection-builder-collection/)

If you have any questions or comments on this project feel free to leave a GitHub issue for this project. I will be working to add more features and capabilities to the collection, and help reduce friction when it comes to other aspects of on-boarding with the Salesforce API.
