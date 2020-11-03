# CommsDAO
Decentralised DAO aggregator for curated and highly productive DAO-to-DAO communication 

# How to contribute
To add a DAO to the current list, fork this repo and submit a pull request, adding the DAO to the `/daos` folder, following the template below.
Feel free to suggest changes to the current template.


## Template

```javascript
{
  "name" : "dOrg",
  
  "description" : "A self-service web3 development agency",
  
  "address" : {
    "mainnet": "0x15344ecdc2c4edfcb092e284d93c20f0529fd8a6",
    "xdai": "0x94a587478c83491b13291265581cb983e7feb540"
  },
  
  "homepage" : "https://dorg.tech",
  
  "email" : "dao@email.here",
  
  "social" : {
    // Public communication channels
    "Twitter" : "https://twitter.com/dOrg_tech",
    "LinkedIn" : "https://www.linkedin.com/company/dorg-tech/",
    "Medium" : "https://medium.com/dorg-tech",
  },
  
  "spaces" : {
     // Collaboration spaces used by this specific DAO
    "Keybase" : "https://keybase.io/team/dorg",
    "Github" : "https://github.com/dOrgTech",
    "Airtable" : "" ,
    "Zoho" : "",
  },
  
  "legal" : {
    "name" : "dOrg, LLC",
    "address" : {
      "street": "76 St. Paul St, 7th Floor, P.O. Box 369",
      "city" : "Burlington",
      "region" : "VT",
      "postal" : "05402",
      "country" : "USA"
    },
    "business-id" : "0357139",
    "tax-id" :"84-2930500"
  },
  
  "dependencies" : {
    "@daostack/arc" : "0.0.1-rc.33",
  },
  
  "config" : {
    // arbitraty configuration variables for each DAO
    "rep-rate" : 1.00, // Rep received per USD earned
    "interest-rate" : .00, // Annual compounding rate for DORG Tokens
    "admin-thresh" : 30000, // Rep needed for administrator permissions to spaces
    "deactivation-thresh" : 90, // Days of inactivity to trigger deactivation
  },
}
```
