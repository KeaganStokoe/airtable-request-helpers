# airtable-request-helpers

Helper functions to access data via the Airtable API. 

Makes a request to Airtable for all records from a single table and returns data in dictionary format. These helpers are extensible and can be used for any table in an Airtable database.  

# Required variables

  -  table: set to table name
      ◦ see: https://support.airtable.com/hc/en-us/articles/360021333094#table
  -  params_dict: desired parameters in dictionary format {parameter : value}
      ◦ example: {"maxRecords" : 20, "view" : "Grid view"}
      ◦ see "List Records" in API Documentation (airtable.com/api)
  -  api_key: retrievable at https://airtable.com/account
      ◦ looks like "key●●●●●●●●●●●●●●"
  -  base_id: retrievable at https://airtable.com/api for specific base
      ◦ looks like "app●●●●●●●●●●●●●●"
  -  record_id: optional for single record lookups
      ◦ looks like "rec●●●●●●●●●●●●●●"
      """
