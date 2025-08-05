# Fortnox API

**Source:** https://api.fortnox.se/apidocs#tag/FinanceInvoicesResource  
**Scraped:** 2025-08-05 15:05:25

---

  * Documentation
    * Rate limits
    * Query parameters
  * integration-developer
    * Integration Sales
      * getResolves sales information of an integration
  * warehouse
    * Custom Document Type
      * getList custom document types
      * postCreate custom document type
      * getGet custom document type
    * Custom Inbound Document
      * getGet custom inbound document
      * putSave custom inbound document
      * putRelease custom inbound document
      * putVoid custom inbound document
    * Custom Outbound Document
      * getGet custom outbound document
      * putSave a custom outbound document
      * putRelease custom outbound document
      * putVoid custom outbound document
    * Incoming Goods
      * getList Incoming Goods Documents
      * postCreate Incoming Goods document
      * getGet Incoming Goods document
      * patchPartial update Incoming Goods document
      * putUpdate Incoming Goods document
      * putComplete Incoming Goods document
      * putRelease Incoming Goods document
      * putVoid Incoming Goods document
    * Manual Document
      * getList manual documents
    * Manual Inbound Document
      * postCreate manual inbound document
      * getGet manual inbound document
      * patchUpdate note on manual inbound document
      * putUpdate manual inbound document
      * putRelease manual inbound document
      * putVoid manual inbound document
    * Manual Outbound Document
      * postCreate manual outbound document
      * getGet manual outbound document
      * patchUpdate note on manual outbound document
      * putUpdate manual outbound document
      * putRelease manual outbound document
      * putVoid manual outbound document
    * Production Order
      * getList production orders
      * postCreate a new production order
      * getGet the package items (Bill Of Materials, BOMs) for a production article
      * putRelease a production order document
      * putVoid a production order
      * getGet Production Order document
      * patchUpdate the note of a production order
      * putUpdate a production order
    * Purchase Order
      * getList Purchase Orders
      * postCreate Purchase Order
      * getGet CSV list of Purchase Orders
      * putUpdate response states
      * postSends multiple purchase orders via email
      * getGet Purchase Order
      * putUpdate Purchase Order
      * putManually complete Purchase Order
      * putManually complete dropship order
      * getList matched documents
      * getGet notes
      * patchPartial update Purchase Order
      * putUpdate response state
      * postSend purchase order via email
      * putVoid Purchase Order
    * Stock Point
      * getList stock points
      * postCreate stock point
      * getGet stock points
      * delDelete stock point
      * getGet stock point
      * postAppend stock locations
      * putUpdate stock point
      * getGet stock locations
    * Stock Status
      * getGet stock balance
    * Stock Taking
      * getList stock takings
      * postCreate stock taking
      * delDelete Stock Taking document
      * getGet Stock Taking document
      * putUpdate a stock taking
      * postAdd rows by filter
      * getGet candidate rows
      * putRelease Stock Taking document
      * delDelete rows by filter
      * getGet Stock Taking Rows
      * postAdd rows
      * delDelete row
      * putVoid Stock Taking document
    * Stock Transfer
      * postCreate a stock transfer document
      * getGet stock transfer document
      * putUpdate a stock transfer document
      * putRelease a stock transfer document
      * putVoid a stock transfer document
    * Tenant
      * getGet Warehouse activation status
  * time-reporting
    * Articles
      * getGet full article registrations that match filter
    * Registrations
      * getGet time/absence registrations that match filter
  * fortnox
    * Absence Transactions
      * getLists all absence transactions
      * postCreate a new absence transaction
      * delDelete an absence transaction
      * getRetrieve a specific absence transaction
      * putUpdate a single absence transaction
      * getRetrieve absence transactions
    * Account Charts
      * getList all account charts
    * Accounts
      * getList all accounts
      * postCreate an account
      * delDeletes an account
      * getRetrieve an account
      * putUpdate an account
    * Archive
      * delRemove files
      * getRetrieve folder or file
      * postUpload a file to a specific subdirectory
      * delDelete a single file
      * getRetrieve a single file
    * Article File Connections
      * getRetrieve a list of article file connections
      * postCreate an article file connection
      * delRemove an article file connection
      * getRetrieve a single article file connection
    * Article Url Connections
      * getRetrieve a list of article url connections
      * postCreate an article url connection
      * delRemove an article url connection
      * getRetrieve a single article url connection
      * putUpdate an article url connection
    * Articles
      * getRetrieve a list of articles
      * postCreate an article
      * delDelete an article
      * getRetrieve an article
      * putUpdate an article
    * Asset File Connection
      * getRetrieve a list of asset file connections
      * postCreate an asset file connection
      * delRemove an asset file connection
    * Asset Types
      * getRetrieve a list of asset types
      * delDelete an asset type
      * getRetrieve an asset type
      * postCreate an asset type
      * putUpdate an asset type
    * Assets
      * getRetrieve a list of assets
      * postCreate an Asset
      * putChange manual OB value of an Asset
      * postPerform a Depreciation of an Asset
      * getAssets depreciation list
      * putScrap an Asset
      * putSell an Asset
      * putWrite down an Asset
      * putWrite up an Asset
      * delDelete or Void an Asset
      * getRetrieve a single asset
      * putUpdate an Asset
    * Attendance Transactions
      * getLists all attendance transactions
      * postCreate a new attendance transaction
      * delDelete an attendance transaction
      * getRetrieve a specific attendance transaction
      * putUpdate a single attendance transaction
      * getRetrieve attendance transactions
    * Company Information
      * getRetrieve the Company Information
    * Company Settings
      * getRetrieve the company settings
    * Contract Accruals
      * getRetrieve a list of contract accruals
      * postCreate a contract accrual
      * delRemove a contract accrual
      * getRetrieve a single contract accrual
      * putUpdate a contract accrual
    * Contract Templates
      * getRetrieve a list of contract templates
      * postCreate a contract template
      * getRetrieve a single contract template
      * putUpdate a contract template
    * Contracts
      * getRetrieve a list of contracts
      * postCreate a contract
      * getRetrieve a single contract
      * putUpdate a contract
      * putCreate invoice from contract
      * putSet a contract as finished
      * putIncreases the invoice count without creating an invoice
    * Cost Centers
      * getRetrieve a list of cost centers
      * postCreate a cost center
      * delRemove a cost center
      * getRetrieve a single cost center
      * putUpdate a cost center
    * Currencies
      * getRetrieve a list of currencies
      * postCreate a currency
      * delRemove a currency
      * getRetrieve a single currency
      * putUpdate a currency
    * Customer References
      * getRetrieve a list of customers reference rows
      * postCreate a customer reference row
      * delDelete a customer reference row
      * getRetrieve a customer reference row
      * putUpdate a customer reference row
    * Customers
      * getRetrieve a list of customers
      * postCreate a customer
      * delDelete a customer
      * getRetrieve a customer
      * putUpdate a customer
    * EU Vat Limit Regulation
      * getRetrieve details about eu vat limit
    * Employees
      * getRetrieve a list of employees
      * postCreate a new employee
      * getRetrieve a specific employee
      * putUpdate employee
    * Expenses
      * getRetrieve expenses
      * postCreate an expense
      * getRetrieve an expense
    * Finance Invoices
      * postSend an invoice with Fortnox Finans
      * getRetrieve a single invoice payment
      * putAction Pause
      * putAction Report Payment
      * putAction Stop
      * putAction Take Fees
      * putAction Unpause
    * Financial Years
      * getRetrieve a list of financial years
      * postCreate a financial year
      * getRetrieve financial year by id
    * Inbox
      * getRetrieve the root folder containing files and folders
      * postUpload a file
      * delRemove a file or folder
      * getRetrieve a single file
    * Invoice Accruals
      * getRetrieve a list of invoice accruals
      * postCreate an invoice accrual
      * delRemove an invoice accrual
      * getRetrieve a single invoice accrual
      * putUpdate an invoice accrual
    * Invoice Payments
      * getRetrieve a list of invoice payments
      * postCreate an invoice payment
      * delRemove an invoice payment
      * getRetrieve a single invoice payment
      * putUpdate an invoice payment
      * putBookkeep an invoice payment
    * Invoices
      * getRetrieve a list of invoices
      * postCreate an invoice
      * getRetrieve a single invoice
      * putUpdate an invoice
      * putBookkeep an invoice
      * putCancel an invoice
      * putCredit an invoice
      * getSend an invoice as e-invoice
      * getSend an invoice as email
      * getSend an invoice as e-print
      * putSet an invoice as sent
      * getPreview an invoice
      * getPrint an invoice
      * getPrint an invoice as reminder
      * putSet an invoice as done
    * Labels
      * getRetrieve a list of labels
      * postCreate a label
      * delDelete a label
      * putUpdate a label
    * Locked Period
      * getRetrieve the locked period
    * Me
      * getRetrieve user information Use this endpoint to retrieve user information related to the used access token
    * Modes Of Payments
      * getRetrieve a list of modes of payments
      * postCreate a mode of payment
      * delRemove a mode of payment
      * getRetrieve a single mode of payment
      * putUpdate a mode of payment
    * Offers
      * getRetrieve a list of offers
      * postCreate an offer
      * getRetrieve a single offer
      * putUpdate an offer
      * putCancels given offer
      * putCreate invoice out of given offer
      * putCreate order out of given offer
      * getSend given offer as email
      * putSet given offer as sent
      * getPreview given offer
      * getPrint given offer
    * Orders
      * getRetrieve a list of orders
      * postCreate a new order
      * getRetrieve a single order
      * putUpdate an order
      * putCancels given order
      * putCreate invoice out of given order
      * getSend given order as email
      * putSet given order as sent
      * getPreview given offer
      * getPrint given order
    * Predefined Accounts
      * getRetrieve a list of all predefined accounts
      * getRetrieve information for a specific account type
      * putUpdate a Predefined Account
    * Predefined Voucher Series
      * getRetrieve a list of predefined voucher series
      * getRetrieve a specific predefined voucher series
      * putUpdate a predefined voucher series
    * Price Lists
      * getRetrieve a list of price lists
      * postCreate a price list
      * getRetrieve a single price list
      * putUpdate a price list
    * Prices
      * getRetrieve a list of prices
      * postCreate a price
      * getRetrieve a list of articles with all their prices in the specified price list
      * getRetrieve the first price for the specified article
      * putUpdate the first price in the specified article
      * delDelete a single price
      * getRetrieve a price for a specified article
      * putUpdate a price
    * Print Templates
      * getRetrieve a list of print templates
    * Projects
      * getRetrieve a list of projects
      * postCreate a project
      * delRemove a project
      * getRetrieve a single project
      * putUpdate a project
    * Salary Transactions
      * getList all salary transactions for all employees
      * postCreate a new salary transaction for an employee
      * delDelete a single salary transaction
      * getRetrieve a single salary transaction
      * putUpdate a salary transaction
    * Schedule Times
      * getRetrieve a specific schedule time
      * putUpdate a schedule time
      * putReset schedule time
    * Sie
      * getRetrieve a SIE file
    * Supplier Invoice Accruals
      * getRetrieve a list of supplier invoice accruals
      * postCreate a supplier invoice accrual
      * delRemove a supplier invoice accrual
      * getRetrieve a single supplier invoice accrual
      * putUpdate a supplier invoice accrual
    * Supplier Invoice External Url Connections
      * postCreate a supplier invoice external URL connection
      * delRemove a supplier invoice external URL connection
      * getRetrieve a single supplier invoice external URL connection
      * putUpdate a supplier invoice external URL connection
    * Supplier Invoice File Connections
      * getRetrieve a list of supplier invoice file connections
      * postCreate an supplier invoice file connection
      * delRemove an supplier invoice file connection
      * getRetrieve a single supplier invoice file connection
    * Supplier Invoice Payments
      * getRetrieve a list of supplier invoice payments
      * postCreate a supplier invoice payment
      * delRemove a supplier invoice payment
      * getRetrieve a single supplier invoice payment
      * putUpdate a supplier invoice payment
      * putBookkeep a supplier invoice payment
    * Supplier Invoices
      * getRetrieve a list of supplier invoices
      * postCreate a supplier invoice
      * getRetrieve a single supplier invoice
      * putUpdate a supplier invoice
      * putApproval of bookkeep of given supplier invoice
      * putApproval of payment of given supplier invoice
      * putBookkeep given supplier invoice
      * putCancels given supplier invoice
      * putCredit given supplier invoice
    * Suppliers
      * getRetrieve a list of suppliers
      * postCreate a supplier
      * getRetrieve a single supplier
      * putUpdate a supplier
    * Tax Reductions
      * getRetrieve a list of tax reductions
      * postCreate a Tax Reduction
      * delRemove a tax reduction
      * getRetrieve a single tax reduction
      * putUpdate a tax reduction
    * Terms Of Deliveries
      * getRetrieve a list of terms of deliveries
      * postCreate a terms of delivery
      * getRetrieve a single terms of delivery
      * putUpdate a terms of delivery
    * Terms Of Payments
      * getRetrieve a list of all terms of payments
      * postCreate a term of payment
      * delRemove a term of payment
      * getRetrieve a single terms of payment
      * putUpdate a term of payment
    * Trusted Email Senders
      * getRetrieve a list of all trusted and rejected senders
      * postAdd a new email address as trusted
      * delDelete an email address from the trusted senders list
    * Units
      * getRetrieve a list of units
      * postCreate a unit
      * delRemove a unit
      * getRetrieve a single unit
      * putUpdate a unit
    * Vacation Debt Basis
      * getRetrieve a specific vacation debt basis for a posted voucher
    * Voucher File Connections
      * getRetrieve a list of voucher file connections
      * postCreate a voucher file connection
      * delRemove a voucher file connection
      * getRetrieve a single voucher file connection
    * Voucher Series
      * getRetrieve a list of voucher series
      * postCreate a voucher series
      * getRetrieve a single voucher series
      * putUpdate a voucher series
    * Vouchers
      * getRetrieve all vouchers
      * postCreate a voucher
      * getRetrieve all vouchers for the current financial year
      * getRetrieve a list of vouchers for a specific series
      * getRetrieve a specific voucher
    * Way Of Deliveries
      * getRetrieve a list of way of deliveries
      * postCreate a way of delivery
      * delRemove a way of delivery
      * getRetrieve a single way of delivery
      * putUpdate a way of delivery
  * fileattachments
    * Attachment
      * getGet attached files on an entity
      * postAttach files to one or more entities
      * getList number of attachments
      * postValidates a list of attachments that will be included on send
      * delDetach file
      * putUpdate attachment
  * Developer
    * Integration Ratings
      * getList rating and reviews for integrations that you own
    * Integration Sales
      * getResolves sales information and active users of an integration
      * getResolves sales information and active users of an integration


[![redocly logo](https://cdn.redoc.ly/redoc/logo-mini.svg)API docs by Redocly](https://redocly.com/redoc/)
# Fortnox API 
Download OpenAPI specification:Download
# [](https://api.fortnox.se/apidocs#section/Documentation)Documentation
The Fortnox API is organized around REST. This means that we’ve designed it to have resource-oriented URLs and be as predictable as possible for you as developer.
It also means that we use HTTP status codes when something goes wrong and HTTP verbs understod by many API clients around the web.
We use a modified version of OAuth2 for authentication to offer a secure way for both you and our users to interact.
The API is generally built to support both XML and JSON but in this documentation all the examples will be in JSON.
We encourage you to read all the articles in the [Guides & Good to Know section](https://www.fortnox.se/developer/guides-and-good-to-know/) first, before going forward and learning about the different resources.
This to ensure you get an understanding of some of the shared components of the API such as parameters and error handling.
## [](https://api.fortnox.se/apidocs#section/Documentation/Rate-limits)Rate limits
The limit per access-token is 25 requests per 5 seconds. This equals to 300 requests per minute.
[Read more about this here.](https://www.fortnox.se/developer/guides-and-good-to-know/rate-limits-for-fortnox-api/)
## [](https://api.fortnox.se/apidocs#section/Documentation/Query-parameters)Query parameters
Use query parameters with the ?-character and separate parameters with the &-character. 
**Example:** GET - [https://api.fortnox.se/3/invoices?accountnumberfrom=3000&accountnumberto=4000](https://api.fortnox.se/3/invoices?accountnumberfrom=3000&accountnumberto=4000) Read more about our parameters [here](https://www.fortnox.se/developer/guides-and-good-to-know/parameters/)
Search the documentation using the search field in the top left corner.
# [](https://api.fortnox.se/apidocs#tag/integration-developer_IntegrationSales)Integration Sales
IntegrationSalesResource
## [](https://api.fortnox.se/apidocs#tag/integration-developer_IntegrationSales/operation/getSalesForSingleIntegration)Resolves sales information of an integration 
Prerequisites The partner has an active developer account and a published integration that is purchased through Fortnox.
##### path Parameters
integrationIdrequired| integer <int64> of the integration to look up sales information for  
---|---  
### Responses
**200**
**default**
WebException
get/api/integration-developer/sales-v1/{integrationId}
Default server
https://api.fortnox.se/api/integration-developer/sales-v1/{integrationId}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`[
  * {
    * "amount": 0,
    * "date": "2019-08-24T14:15:22Z",
    * "orderId": "string",
    * "tenantId": "string",
    * "type": "string"
}

]`
# [](https://api.fortnox.se/apidocs#tag/warehouse_CustomDocumentType)Custom Document Type
Handles types for custom documents.
A custom document is identified by its type and id. Each type belongs to a category, either INBOUND or OUTBOUND.
Note that custom document types are created automatically if necessary when you create custom documents.
The following `referenceTypes` are not allowed for custom document types. Variants of these containing dashes, underscores, lower case, upper case etc are not allowed either.
  * ARTICLEPRODUCTION
  * ARTIKELPRODUKTION
  * CUSTOMERINVOICE
  * CUSTOMERORDER
  * DELIVERYNOTE
  * FAKTURA
  * FÖLJESEDEL
  * INGÅENDESALDO
  * INKÖP
  * INKÖPSORDER
  * INVENTERING
  * INVENTORY
  * INVOICE
  * ITEMPRODUCTION
  * KREDITFAKTURA
  * KREDITORDER
  * KUNDFAKTURA
  * KUNDORDER
  * LAGERFLYTT
  * LEGACYINTEGRATIONIN
  * LEGACYINTEGRATIONOUT
  * LEVERANTÖRSFAKTURA
  * LEVFAKTURA
  * MANUALDELIVERY
  * MANUALINBOUND
  * MANUALINBOUNDDELIVERY
  * MANUALOUTBOUND
  * MANUALOUTBOUNDDELIVERY
  * MANUELLINLEVERANS
  * MANUELLLEVERANS
  * MANUELLUTLEVERANS
  * NEGATIVEOPENINGBALANCES
  * NEGATIVTINGÅENDESALDO
  * ORDER
  * PLOCKLISTA
  * POSITIVEOPENINGBALANCES
  * PRODUCTION
  * PRODUKTION
  * PURCHASE
  * PURCHASEORDER
  * STOCKTAKING
  * STOCKTAKINGDEVIATION
  * STOCKTRANSFER
  * SUPINVOICE
  * SUPPLIERINVOICE


## [](https://api.fortnox.se/apidocs#tag/warehouse_CustomDocumentType/operation/getAll_6)List custom document types 
### Responses
**200**
A list of `CustomDocumentTypes`
**default**
WebException
get/api/warehouse/documentdeliveries/custom/documenttypes-v1
Default server
https://api.fortnox.se/api/warehouse/documentdeliveries/custom/documenttypes-v1
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
`{
  * "category": "INBOUND",
  * "referenceType": "a"

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_CustomDocumentType/operation/1_create_8)Create custom document type 
Create type, if it doesn't already exists. Note that new custom document types are created automatically when you create custom documents, so normally you do not need to call this method.
Throws HTTP 400 `referenceTypeNotAllowed` if the name of the type is not allowed.
##### Request Body schema: application/json
The `CustomDocumentType`.
categoryrequired| string Enum: "INBOUND" "OUTBOUND"  
---|---  
referenceTyperequired| string [ 1 .. 25 ] characters [a-zA-Z0-9_-]+  
### Responses
**201**
`1` if created, else `0` if type already exists.
**default**
WebException
post/api/warehouse/documentdeliveries/custom/documenttypes-v1
Default server
https://api.fortnox.se/api/warehouse/documentdeliveries/custom/documenttypes-v1
###  Request samples 
  * Payload


Content type
application/json
Copy
`{
  * "category": "INBOUND",
  * "referenceType": "a"

}`
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
0
`0`
## [](https://api.fortnox.se/apidocs#tag/warehouse_CustomDocumentType/operation/get_11)Get custom document type 
##### path Parameters
typerequired| string the name of the reference type  
---|---  
### Responses
**200**
A `CustomDocumentType`
**default**
WebException
get/api/warehouse/documentdeliveries/custom/documenttypes-v1/{type}
Default server
https://api.fortnox.se/api/warehouse/documentdeliveries/custom/documenttypes-v1/{type}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
`{
  * "category": "INBOUND",
  * "referenceType": "a"

}`
# [](https://api.fortnox.se/apidocs#tag/warehouse_CustomInboundDocument)Custom Inbound Document
Handles Custom Inbound Documents.
A Custom Inbound Document is an externally created document for registering inbound deliveries to warehouse.
## [](https://api.fortnox.se/apidocs#tag/warehouse_CustomInboundDocument/operation/get_12)Get custom inbound document 
##### path Parameters
typerequired| string Document type.  
---|---  
idrequired| string Document id.  
### Responses
**200**
The `CustomInboundDocument`.
**default**
WebException
get/api/warehouse/documentdeliveries/custom/inbound-v1/{type}/{id}
Default server
https://api.fortnox.se/api/warehouse/documentdeliveries/custom/inbound-v1/{type}/{id}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "currency": {
    * "currency": "str",
    * "rate": 0.000001,
    * "unit": 1
},
  * "date": "2019-08-24",
  * "id": "^0",
  * "note": "string",
  * "rows": [
    * {
      * "batch": "string",
      * "costCenterCode": "string",
      * "directCost": 0,
      * "freightCost": 0,
      * "itemDescription": "string",
      * "itemId": "string",
      * "itemUnit": "string",
      * "otherCost": 0,
      * "projectId": "string",
      * "quantity": 0,
      * "rowId": 1,
      * "stockLocationCode": "string",
      * "stockLocationId": "c039ed46-ada4-4486-8700-89747e000395",
      * "stockPointCode": "string",
      * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c"
}
],
  * "type": "a",
  * "voided": true,
  * "warehouseReady": true

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_CustomInboundDocument/operation/save)Save custom inbound document 
##### path Parameters
typerequired| string min 1 character, max 25 characters, may contain letters A-Z, digits 0-9, underscore (_), and dash (-), type is case-insensitive 
> ```
   Type is a custom name/reference of the document that will be used to reference the document type 
   * If type is not known, it will be registered as belonging to the INBOUND category. 
   * If type is an existing custom document type of category OUTBOUND an error is thrown. 
   * If type is invalid an error is thrown. 
 
```
  
---|---  
idrequired| string min 1 character, max 25 characters, may only contain digits 0-9  
##### Request Body schema: application/json
the `CustomInboundDocument` to create
currency| object (warehouse_Currency)   
---|---  
daterequired| string <date>  
id| string [ 1 .. 25 ] characters ^[0-9]+  
note| string <= 1000 characters   
rowsrequired| Array of objects (warehouse_CustomInboundDocumentRow)   
type| string [ 1 .. 25 ] characters [a-zA-Z0-9_-]+  
voided| boolean  
warehouseReady| boolean  
### Responses
**200**
the stored `CustomInboundDocument`
**default**
WebException
put/api/warehouse/documentdeliveries/custom/inbound-v1/{type}/{id}
Default server
https://api.fortnox.se/api/warehouse/documentdeliveries/custom/inbound-v1/{type}/{id}
###  Request samples 
  * Payload


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "currency": {
    * "currency": "str",
    * "rate": 0.000001,
    * "unit": 1
},
  * "date": "2019-08-24",
  * "id": "^0",
  * "note": "string",
  * "rows": [
    * {
      * "batch": "string",
      * "costCenterCode": "string",
      * "directCost": 0,
      * "freightCost": 0,
      * "itemDescription": "string",
      * "itemId": "string",
      * "itemUnit": "string",
      * "otherCost": 0,
      * "projectId": "string",
      * "quantity": 0,
      * "rowId": 1,
      * "stockLocationCode": "string",
      * "stockLocationId": "c039ed46-ada4-4486-8700-89747e000395",
      * "stockPointCode": "string",
      * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c"
}
],
  * "type": "a",
  * "voided": true,
  * "warehouseReady": true

}`
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "currency": {
    * "currency": "str",
    * "rate": 0.000001,
    * "unit": 1
},
  * "date": "2019-08-24",
  * "id": "^0",
  * "note": "string",
  * "rows": [
    * {
      * "batch": "string",
      * "costCenterCode": "string",
      * "directCost": 0,
      * "freightCost": 0,
      * "itemDescription": "string",
      * "itemId": "string",
      * "itemUnit": "string",
      * "otherCost": 0,
      * "projectId": "string",
      * "quantity": 0,
      * "rowId": 1,
      * "stockLocationCode": "string",
      * "stockLocationId": "c039ed46-ada4-4486-8700-89747e000395",
      * "stockPointCode": "string",
      * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c"
}
],
  * "type": "a",
  * "voided": true,
  * "warehouseReady": true

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_CustomInboundDocument/operation/release_4)Release custom inbound document 
The document will be locked and bookkept. The inbound deliveries will affect available stock.
##### path Parameters
typerequired| string document type  
---|---  
idrequired| string document id  
### Responses
**204**
Successfully updated the specified resource.
**default**
WebException
put/api/warehouse/documentdeliveries/custom/inbound-v1/{type}/{id}/release
Default server
https://api.fortnox.se/api/warehouse/documentdeliveries/custom/inbound-v1/{type}/{id}/release
###  Response samples 
  * default


Content type
application/json
Copy
`{
  * "error": "string",
  * "id": "string",
  * "message": "string"

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_CustomInboundDocument/operation/voidDocument_2)Void custom inbound document 
Voiding a document will undo the possible stock changes that the document had made, note that the document and the transactions created are not deleted. Some limitations apply, see below.
##### path Parameters
typerequired| string document type  
---|---  
idrequired| string document id  
##### query Parameters
force| boolean true if the document should be voided even if the document has connected outbounds, defaults to false.  
---|---  
### Responses
**204**
Successfully updated the specified resource.
**default**
WebException
put/api/warehouse/documentdeliveries/custom/inbound-v1/{type}/{id}/void
Default server
https://api.fortnox.se/api/warehouse/documentdeliveries/custom/inbound-v1/{type}/{id}/void
###  Response samples 
  * default


Content type
application/json
Copy
`{
  * "error": "string",
  * "id": "string",
  * "message": "string"

}`
# [](https://api.fortnox.se/apidocs#tag/warehouse_CustomOutboundDocument)Custom Outbound Document
Handles Custom Outbound Documents.
A Custom Outbound Document is an externally created document for registering outbound deliveries to warehouse.
## [](https://api.fortnox.se/apidocs#tag/warehouse_CustomOutboundDocument/operation/1_get_13)Get custom outbound document 
##### path Parameters
typerequired| string document type  
---|---  
idrequired| string document id  
### Responses
**200**
the fetched `CustomOutboundDocument`
**default**
WebException
get/api/warehouse/documentdeliveries/custom/outbound-v1/{type}/{id}
Default server
https://api.fortnox.se/api/warehouse/documentdeliveries/custom/outbound-v1/{type}/{id}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "averageCosts": [
    * {
      * "averageCostInSEK": 0,
      * "itemId": "string",
      * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c"
}
],
  * "date": "2019-08-24",
  * "deliveryState": "registration",
  * "forcedDelivery": true,
  * "id": "^0",
  * "note": "string",
  * "referenceType": "a",
  * "rows": [
    * {
      * "costCenterCode": "string",
      * "deliveredQuantity": 0,
      * "forcedQuantity": 0,
      * "itemDescription": "string",
      * "itemId": "string",
      * "itemUnit": "string",
      * "projectId": "string",
      * "quantity": 0,
      * "reservedQuantity": 0,
      * "rowId": 1,
      * "stockLocationId": "c039ed46-ada4-4486-8700-89747e000395",
      * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c"
}
],
  * "voided": true,
  * "warehouseReady": true

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_CustomOutboundDocument/operation/save_1)Save a custom outbound document 
If type is not known, it will be registered as belonging to the OUTBOUND category. If type is an existing custom document type of category INBOUND an error is thrown. If type is invalid an error is thrown.
##### path Parameters
typerequired| string the type of the custom outbound document, min 1 character, max 25 characters, may contain letters A-Z, digits 0-9, underscore (_), and dash (-). Always stored as upper case.  
---|---  
idrequired| string the id of the custom outbound document, min 1 character, max 25 characters, may only contain digits 0-9  
##### Request Body schema: application/json
the `CustomOutboundDocument` to create
averageCosts| Array of objects (warehouse_AverageCost)   
---|---  
daterequired| string <date>  
deliveryStaterequired| string Enum: "registration" "reservation" "delivery"  
forcedDelivery| boolean  
id| string [ 1 .. 25 ] characters ^[0-9]+  
note| string <= 1000 characters   
referenceType| string [ 1 .. 25 ] characters [a-zA-Z0-9_-]+  
rowsrequired| Array of objects (warehouse_CustomOutboundDocumentRow)   
voided| boolean  
warehouseReady| boolean  
### Responses
**200**
the stored `CustomOutboundDocument`
**default**
WebException
put/api/warehouse/documentdeliveries/custom/outbound-v1/{type}/{id}
Default server
https://api.fortnox.se/api/warehouse/documentdeliveries/custom/outbound-v1/{type}/{id}
###  Request samples 
  * Payload


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "averageCosts": [
    * {
      * "averageCostInSEK": 0,
      * "itemId": "string",
      * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c"
}
],
  * "date": "2019-08-24",
  * "deliveryState": "registration",
  * "forcedDelivery": true,
  * "id": "^0",
  * "note": "string",
  * "referenceType": "a",
  * "rows": [
    * {
      * "costCenterCode": "string",
      * "deliveredQuantity": 0,
      * "forcedQuantity": 0,
      * "itemDescription": "string",
      * "itemId": "string",
      * "itemUnit": "string",
      * "projectId": "string",
      * "quantity": 0,
      * "reservedQuantity": 0,
      * "rowId": 1,
      * "stockLocationId": "c039ed46-ada4-4486-8700-89747e000395",
      * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c"
}
],
  * "voided": true,
  * "warehouseReady": true

}`
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "averageCosts": [
    * {
      * "averageCostInSEK": 0,
      * "itemId": "string",
      * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c"
}
],
  * "date": "2019-08-24",
  * "deliveryState": "registration",
  * "forcedDelivery": true,
  * "id": "^0",
  * "note": "string",
  * "referenceType": "a",
  * "rows": [
    * {
      * "costCenterCode": "string",
      * "deliveredQuantity": 0,
      * "forcedQuantity": 0,
      * "itemDescription": "string",
      * "itemId": "string",
      * "itemUnit": "string",
      * "projectId": "string",
      * "quantity": 0,
      * "reservedQuantity": 0,
      * "rowId": 1,
      * "stockLocationId": "c039ed46-ada4-4486-8700-89747e000395",
      * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c"
}
],
  * "voided": true,
  * "warehouseReady": true

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_CustomOutboundDocument/operation/release_5)Release custom outbound document 
##### path Parameters
typerequired| string document type  
---|---  
idrequired| string document id  
### Responses
**204**
Successfully updated the specified resource.
**default**
WebException
put/api/warehouse/documentdeliveries/custom/outbound-v1/{type}/{id}/release
Default server
https://api.fortnox.se/api/warehouse/documentdeliveries/custom/outbound-v1/{type}/{id}/release
###  Response samples 
  * default


Content type
application/json
Copy
`{
  * "error": "string",
  * "id": "string",
  * "message": "string"

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_CustomOutboundDocument/operation/voidDocument_3)Void custom outbound document 
##### path Parameters
typerequired| string document type  
---|---  
idrequired| string document id  
##### query Parameters
force| boolean true if the document should be voided even if the document has connected outbounds, defaults to false.  
---|---  
### Responses
**204**
Successfully updated the specified resource.
**default**
WebException
put/api/warehouse/documentdeliveries/custom/outbound-v1/{type}/{id}/void
Default server
https://api.fortnox.se/api/warehouse/documentdeliveries/custom/outbound-v1/{type}/{id}/void
###  Response samples 
  * default


Content type
application/json
Copy
`{
  * "error": "string",
  * "id": "string",
  * "message": "string"

}`
# [](https://api.fortnox.se/apidocs#tag/warehouse_IncomingGoods)Incoming Goods
General resource for incoming goods.
## [](https://api.fortnox.se/apidocs#tag/warehouse_IncomingGoods/operation/getAll_7)List Incoming Goods Documents 
List incoming goods documents matching the given parameters. 
Sortable fields: `id`, `has_delivery_note`, `delivery_note_id`, `supplier_number`, `date`
##### query Parameters
released| boolean `true` to include only released documents. `false` to include only non-released documents.  
---|---  
completed| boolean `true` to include only completed documents. `false` to include only non-completed documents.  
voided| boolean `true` to include only voided documents. `false` to include only non-voided documents.  
supplierNumber| string Include only documents with the given `supplierNumber`.  
itemId| string Include only documents with the given `itemId`.  
note| string Include only documents where `note`-field contains the given text (case-insensitive).  
deliveryNote| string Include only documents where `deliveryNote`-field contains the given text (case-insensitive).  
q| string Include only documents where `id` or `deliveryNote`-field contains the given text (case-insensitive).  
### Responses
**200**
A list of `IncomingGoods` documents.
**default**
WebException
get/api/warehouse/incominggoods-v1
Default server
https://api.fortnox.se/api/warehouse/incominggoods-v1
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`[
  * {
    * "completed": true,
    * "date": "2019-08-24",
    * "deliveryNoteId": "string",
    * "hasDeliveryNote": true,
    * "id": 0,
    * "note": "string",
    * "released": true,
    * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c",
    * "supplierName": "string",
    * "supplierNumber": "string",
    * "unmatchedValue": 0,
    * "voided": true
}

]`
## [](https://api.fortnox.se/apidocs#tag/warehouse_IncomingGoods/operation/1_create_9)Create Incoming Goods document 
##### Request Body schema: */*
The `IncomingGoods` document.
completed| boolean  
---|---  
costCenterCode| string  
date| string <date>  
deliveryNoteIdrequired| string [ 1 .. 50 ] characters   
hasDeliveryNote| boolean  
id| integer <int64>  
note| string <= 1000 characters   
projectId| string  
released| boolean  
rows| Array of objects (warehouse_IncomingGoodsRow)   
stockPointCode| string  
stockPointId| string <uuid>  
stockPointName| string  
supplierName| string <= 1024 characters   
supplierNumber| string <= 1024 characters   
voided| boolean  
### Responses
**201**
The created `IncomingGoods` document.
**default**
WebException
post/api/warehouse/incominggoods-v1
Default server
https://api.fortnox.se/api/warehouse/incominggoods-v1
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "completed": true,
  * "costCenterCode": "string",
  * "date": "2019-08-24",
  * "deliveryNoteId": "string",
  * "hasDeliveryNote": true,
  * "id": 0,
  * "note": "string",
  * "projectId": "string",
  * "released": true,
  * "rows": [
    * {
      * "backOrderQuantity": 0,
      * "batch": "string",
      * "costCenterCode": "string",
      * "directCost": 0,
      * "id": "497f6eca-6276-4993-bfeb-53cbbbba6f08",
      * "invoicedQuantity": 0,
      * "isStockItem": true,
      * "itemDescription": "string",
      * "itemId": "string",
      * "itemUnit": "string",
      * "orderedQuantity": 0,
      * "projectId": "string",
      * "purchaseOrderId": 0,
      * "purchaseOrderRowId": "ba867b0e-f326-42c4-9f43-58bde9b319da",
      * "receivedQuantity": 0,
      * "remainingOrderedQuantity": 0,
      * "rowOrder": 0,
      * "stockLocationCode": "string",
      * "stockLocationId": "c039ed46-ada4-4486-8700-89747e000395",
      * "stockLocationName": "string",
      * "stockPointCode": "string",
      * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c",
      * "stockPointName": "string",
      * "takenQuantity": 0
}
],
  * "stockPointCode": "string",
  * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c",
  * "stockPointName": "string",
  * "supplierName": "string",
  * "supplierNumber": "string",
  * "voided": true

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_IncomingGoods/operation/get_15)Get Incoming Goods document 
##### path Parameters
idrequired| integer <int64> Incoming goods document id.  
---|---  
##### query Parameters
ignoreSupplierInvoiceId| integer <int64> This Supplier Invoice id will be excluded when calculating the takenQuantity.  
---|---  
### Responses
**200**
The `IncomingGoods` document.
**default**
WebException
get/api/warehouse/incominggoods-v1/{id}
Default server
https://api.fortnox.se/api/warehouse/incominggoods-v1/{id}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "completed": true,
  * "costCenterCode": "string",
  * "date": "2019-08-24",
  * "deliveryNoteId": "string",
  * "hasDeliveryNote": true,
  * "id": 0,
  * "note": "string",
  * "projectId": "string",
  * "released": true,
  * "rows": [
    * {
      * "backOrderQuantity": 0,
      * "batch": "string",
      * "costCenterCode": "string",
      * "directCost": 0,
      * "id": "497f6eca-6276-4993-bfeb-53cbbbba6f08",
      * "invoicedQuantity": 0,
      * "isStockItem": true,
      * "itemDescription": "string",
      * "itemId": "string",
      * "itemUnit": "string",
      * "orderedQuantity": 0,
      * "projectId": "string",
      * "purchaseOrderId": 0,
      * "purchaseOrderRowId": "ba867b0e-f326-42c4-9f43-58bde9b319da",
      * "receivedQuantity": 0,
      * "remainingOrderedQuantity": 0,
      * "rowOrder": 0,
      * "stockLocationCode": "string",
      * "stockLocationId": "c039ed46-ada4-4486-8700-89747e000395",
      * "stockLocationName": "string",
      * "stockPointCode": "string",
      * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c",
      * "stockPointName": "string",
      * "takenQuantity": 0
}
],
  * "stockPointCode": "string",
  * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c",
  * "stockPointName": "string",
  * "supplierName": "string",
  * "supplierNumber": "string",
  * "voided": true

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_IncomingGoods/operation/patch)Partial update Incoming Goods document 
Perform a partial update of an `IncomingGoods` document. The partial update will update `note`, `deliveryNoteId`, `supplierName` and `hasDeliveryNote` It is possible to perform a partial update of a released/completed (TODO: ?) document.
##### path Parameters
idrequired| integer <int64> Incoming goods document id.  
---|---  
##### Request Body schema: */*
the incoming goods document to update. The partial update updates `note`, `deliveryNoteId`, `supplierName` and `hasDeliveryNote`
completed| boolean  
---|---  
costCenterCode| string  
date| string <date>  
deliveryNoteIdrequired| string [ 1 .. 50 ] characters   
hasDeliveryNote| boolean  
id| integer <int64>  
note| string <= 1000 characters   
projectId| string  
released| boolean  
rows| Array of objects (warehouse_IncomingGoodsRow)   
stockPointCode| string  
stockPointId| string <uuid>  
stockPointName| string  
supplierName| string <= 1024 characters   
supplierNumber| string <= 1024 characters   
voided| boolean  
### Responses
**200**
The updated `IncomingGoods` document.
**default**
WebException
patch/api/warehouse/incominggoods-v1/{id}
Default server
https://api.fortnox.se/api/warehouse/incominggoods-v1/{id}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "completed": true,
  * "costCenterCode": "string",
  * "date": "2019-08-24",
  * "deliveryNoteId": "string",
  * "hasDeliveryNote": true,
  * "id": 0,
  * "note": "string",
  * "projectId": "string",
  * "released": true,
  * "rows": [
    * {
      * "backOrderQuantity": 0,
      * "batch": "string",
      * "costCenterCode": "string",
      * "directCost": 0,
      * "id": "497f6eca-6276-4993-bfeb-53cbbbba6f08",
      * "invoicedQuantity": 0,
      * "isStockItem": true,
      * "itemDescription": "string",
      * "itemId": "string",
      * "itemUnit": "string",
      * "orderedQuantity": 0,
      * "projectId": "string",
      * "purchaseOrderId": 0,
      * "purchaseOrderRowId": "ba867b0e-f326-42c4-9f43-58bde9b319da",
      * "receivedQuantity": 0,
      * "remainingOrderedQuantity": 0,
      * "rowOrder": 0,
      * "stockLocationCode": "string",
      * "stockLocationId": "c039ed46-ada4-4486-8700-89747e000395",
      * "stockLocationName": "string",
      * "stockPointCode": "string",
      * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c",
      * "stockPointName": "string",
      * "takenQuantity": 0
}
],
  * "stockPointCode": "string",
  * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c",
  * "stockPointName": "string",
  * "supplierName": "string",
  * "supplierNumber": "string",
  * "voided": true

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_IncomingGoods/operation/save_2)Update Incoming Goods document 
##### path Parameters
idrequired| integer <int64> Incoming goods document id.  
---|---  
##### Request Body schema: */*
The `IncomingGoods` document.
completed| boolean  
---|---  
costCenterCode| string  
date| string <date>  
deliveryNoteIdrequired| string [ 1 .. 50 ] characters   
hasDeliveryNote| boolean  
id| integer <int64>  
note| string <= 1000 characters   
projectId| string  
released| boolean  
rows| Array of objects (warehouse_IncomingGoodsRow)   
stockPointCode| string  
stockPointId| string <uuid>  
stockPointName| string  
supplierName| string <= 1024 characters   
supplierNumber| string <= 1024 characters   
voided| boolean  
### Responses
**200**
The updated `IncomingGoods` document.
**default**
WebException
put/api/warehouse/incominggoods-v1/{id}
Default server
https://api.fortnox.se/api/warehouse/incominggoods-v1/{id}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "completed": true,
  * "costCenterCode": "string",
  * "date": "2019-08-24",
  * "deliveryNoteId": "string",
  * "hasDeliveryNote": true,
  * "id": 0,
  * "note": "string",
  * "projectId": "string",
  * "released": true,
  * "rows": [
    * {
      * "backOrderQuantity": 0,
      * "batch": "string",
      * "costCenterCode": "string",
      * "directCost": 0,
      * "id": "497f6eca-6276-4993-bfeb-53cbbbba6f08",
      * "invoicedQuantity": 0,
      * "isStockItem": true,
      * "itemDescription": "string",
      * "itemId": "string",
      * "itemUnit": "string",
      * "orderedQuantity": 0,
      * "projectId": "string",
      * "purchaseOrderId": 0,
      * "purchaseOrderRowId": "ba867b0e-f326-42c4-9f43-58bde9b319da",
      * "receivedQuantity": 0,
      * "remainingOrderedQuantity": 0,
      * "rowOrder": 0,
      * "stockLocationCode": "string",
      * "stockLocationId": "c039ed46-ada4-4486-8700-89747e000395",
      * "stockLocationName": "string",
      * "stockPointCode": "string",
      * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c",
      * "stockPointName": "string",
      * "takenQuantity": 0
}
],
  * "stockPointCode": "string",
  * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c",
  * "stockPointName": "string",
  * "supplierName": "string",
  * "supplierNumber": "string",
  * "voided": true

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_IncomingGoods/operation/completed)Complete Incoming Goods document 
Mark a released Incoming Goods document as Completed. Bookkeeping will be finalized. A Completed Incoming Goods document cannot be matched against any more Supplier Invoices.
##### path Parameters
idrequired| integer <int64> Incoming goods document id.  
---|---  
##### Request Body schema: */*
Date for bookkeeping in format `"YYYY-MM-DD"`. Must be between document's release date (inclusive) and today's date (inclusive).
string
### Responses
**204**
Successfully updated the specified resource.
**default**
WebException
put/api/warehouse/incominggoods-v1/{id}/completed
Default server
https://api.fortnox.se/api/warehouse/incominggoods-v1/{id}/completed
###  Response samples 
  * default


Content type
application/json
Copy
`{
  * "error": "string",
  * "id": "string",
  * "message": "string"

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_IncomingGoods/operation/release_6)Release Incoming Goods document 
The document will be locked and bookkept. The inbound deliveries will affect available stock.
##### path Parameters
idrequired| integer <int64> Incoming goods document id.  
---|---  
### Responses
**204**
Successfully updated the specified resource.
**default**
WebException
put/api/warehouse/incominggoods-v1/{id}/release
Default server
https://api.fortnox.se/api/warehouse/incominggoods-v1/{id}/release
###  Response samples 
  * default


Content type
application/json
Copy
`{
  * "error": "string",
  * "id": "string",
  * "message": "string"

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_IncomingGoods/operation/voidDocument_4)Void Incoming Goods document 
Void a document. If an Incoming Goods document has been Completed, or matched against Supplier Invoice, it cannot be voided.
##### path Parameters
idrequired| integer <int64> Incoming goods document id.  
---|---  
### Responses
**204**
Successfully updated the specified resource.
**default**
WebException
put/api/warehouse/incominggoods-v1/{id}/void
Default server
https://api.fortnox.se/api/warehouse/incominggoods-v1/{id}/void
###  Response samples 
  * default


Content type
application/json
Copy
`{
  * "error": "string",
  * "id": "string",
  * "message": "string"

}`
# [](https://api.fortnox.se/apidocs#tag/warehouse_ManualDocument)Manual Document
Handles listing of `ManualDocument`s. 
There are three types of Manual Documents in Warehouse: 
  * Manual Inbound Documents, 
  * Manual Outbound Documents, and 
  * Stock Transfer Documents 


## [](https://api.fortnox.se/apidocs#tag/warehouse_ManualDocument/operation/getAll)List manual documents 
##### query Parameters
state| string Enum: "all" "unreleased" "released" "voided" Include only documents with given state.  
---|---  
type| string Enum: "all" "inbound" "outbound" "stocktransfer" Include only documents with given type.  
itemId| string Include only documents containing the given item.  
### Responses
**200**
A list of manual documents.
**default**
WebException
get/api/warehouse/deliveries-v1
Default server
https://api.fortnox.se/api/warehouse/deliveries-v1
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
`{
  * "date": "2019-08-24",
  * "deliveryId": 0,
  * "entityId": "string",
  * "note": "string",
  * "released": true,
  * "type": "Inbound",
  * "voided": true

}`
# [](https://api.fortnox.se/apidocs#tag/warehouse_ManualInboundDocument)Manual Inbound Document
Handles `ManualInboundDocument`s
## [](https://api.fortnox.se/apidocs#tag/warehouse_ManualInboundDocument/operation/create)Create manual inbound document 
The `id` is set automatically.
##### Request Body schema: application/json
manual inbound document
currencyrequired| string = 3 characters   
---|---  
currencyRaterequired| number >= 0.000001   
currencyUnit| integer <int32> >= 1   
daterequired| string <date>  
id| integer <int64>  
note| string <= 1000 characters   
released| boolean  
rowsrequired| Array of objects (warehouse_ManualInboundDocumentRow)  [ 1 .. 2147483647 ] items   
stockPointCode| string  
stockPointId| string <uuid>  
stockPointName| string  
voided| boolean  
### Responses
**201**
the `ManualInboundDocument` document.
**default**
WebException
post/api/warehouse/deliveries-v1/inbounddeliveries
Default server
https://api.fortnox.se/api/warehouse/deliveries-v1/inbounddeliveries
###  Request samples 
  * Payload


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "currency": "str",
  * "currencyRate": 0.000001,
  * "currencyUnit": 1,
  * "date": "2019-08-24",
  * "id": 0,
  * "note": "string",
  * "released": true,
  * "rows": [
    * {
      * "batch": "string",
      * "costCenterCode": "string",
      * "directCost": 0,
      * "freightCost": 0,
      * "itemDescription": "string",
      * "itemId": "string",
      * "itemUnit": "string",
      * "otherCost": 0,
      * "projectId": "string",
      * "quantity": 0.01,
      * "rowId": 0,
      * "stockLocationCode": "string",
      * "stockLocationId": "c039ed46-ada4-4486-8700-89747e000395",
      * "stockLocationName": "string",
      * "stockPointCode": "string",
      * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c",
      * "stockPointName": "string"
}
],
  * "stockPointCode": "string",
  * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c",
  * "stockPointName": "string",
  * "voided": true

}`
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "currency": "str",
  * "currencyRate": 0.000001,
  * "currencyUnit": 1,
  * "date": "2019-08-24",
  * "id": 0,
  * "note": "string",
  * "released": true,
  * "rows": [
    * {
      * "batch": "string",
      * "costCenterCode": "string",
      * "directCost": 0,
      * "freightCost": 0,
      * "itemDescription": "string",
      * "itemId": "string",
      * "itemUnit": "string",
      * "otherCost": 0,
      * "projectId": "string",
      * "quantity": 0.01,
      * "rowId": 0,
      * "stockLocationCode": "string",
      * "stockLocationId": "c039ed46-ada4-4486-8700-89747e000395",
      * "stockLocationName": "string",
      * "stockPointCode": "string",
      * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c",
      * "stockPointName": "string"
}
],
  * "stockPointCode": "string",
  * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c",
  * "stockPointName": "string",
  * "voided": true

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_ManualInboundDocument/operation/1_get)Get manual inbound document 
##### path Parameters
idrequired| integer <int64> Manual Inbound document id.  
---|---  
### Responses
**200**
the `ManualInboundDocument` document.
**default**
WebException
get/api/warehouse/deliveries-v1/inbounddeliveries/{id}
Default server
https://api.fortnox.se/api/warehouse/deliveries-v1/inbounddeliveries/{id}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "currency": "str",
  * "currencyRate": 0.000001,
  * "currencyUnit": 1,
  * "date": "2019-08-24",
  * "id": 0,
  * "note": "string",
  * "released": true,
  * "rows": [
    * {
      * "batch": "string",
      * "costCenterCode": "string",
      * "directCost": 0,
      * "freightCost": 0,
      * "itemDescription": "string",
      * "itemId": "string",
      * "itemUnit": "string",
      * "otherCost": 0,
      * "projectId": "string",
      * "quantity": 0.01,
      * "rowId": 0,
      * "stockLocationCode": "string",
      * "stockLocationId": "c039ed46-ada4-4486-8700-89747e000395",
      * "stockLocationName": "string",
      * "stockPointCode": "string",
      * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c",
      * "stockPointName": "string"
}
],
  * "stockPointCode": "string",
  * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c",
  * "stockPointName": "string",
  * "voided": true

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_ManualInboundDocument/operation/updateNote)Update note on manual inbound document 
When a Manual Inbound has been released, it is locked. The `note` field can still be updated using this endpoint.
##### path Parameters
idrequired| integer <int64> Manual Inbound document id.  
---|---  
##### Request Body schema: application/json
Note.
note| string <= 1000 characters   
---|---  
### Responses
**204**
Successfully applied partial modifications to the resource.
**default**
WebException
patch/api/warehouse/deliveries-v1/inbounddeliveries/{id}
Default server
https://api.fortnox.se/api/warehouse/deliveries-v1/inbounddeliveries/{id}
###  Request samples 
  * Payload


Content type
application/json
Copy
`{
  * "note": "string"

}`
###  Response samples 
  * default


Content type
application/json
Copy
`{
  * "error": "string",
  * "id": "string",
  * "message": "string"

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_ManualInboundDocument/operation/1_update)Update manual inbound document 
##### path Parameters
idrequired| integer <int64> Manual Inbound document id.  
---|---  
##### Request Body schema: application/json
Manual Inbound document
currencyrequired| string = 3 characters   
---|---  
currencyRaterequired| number >= 0.000001   
currencyUnit| integer <int32> >= 1   
daterequired| string <date>  
id| integer <int64>  
note| string <= 1000 characters   
released| boolean  
rowsrequired| Array of objects (warehouse_ManualInboundDocumentRow)  [ 1 .. 2147483647 ] items   
stockPointCode| string  
stockPointId| string <uuid>  
stockPointName| string  
voided| boolean  
### Responses
**200**
the `ManualInboundDocument` document.
**default**
WebException
put/api/warehouse/deliveries-v1/inbounddeliveries/{id}
Default server
https://api.fortnox.se/api/warehouse/deliveries-v1/inbounddeliveries/{id}
###  Request samples 
  * Payload


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "currency": "str",
  * "currencyRate": 0.000001,
  * "currencyUnit": 1,
  * "date": "2019-08-24",
  * "id": 0,
  * "note": "string",
  * "released": true,
  * "rows": [
    * {
      * "batch": "string",
      * "costCenterCode": "string",
      * "directCost": 0,
      * "freightCost": 0,
      * "itemDescription": "string",
      * "itemId": "string",
      * "itemUnit": "string",
      * "otherCost": 0,
      * "projectId": "string",
      * "quantity": 0.01,
      * "rowId": 0,
      * "stockLocationCode": "string",
      * "stockLocationId": "c039ed46-ada4-4486-8700-89747e000395",
      * "stockLocationName": "string",
      * "stockPointCode": "string",
      * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c",
      * "stockPointName": "string"
}
],
  * "stockPointCode": "string",
  * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c",
  * "stockPointName": "string",
  * "voided": true

}`
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "currency": "str",
  * "currencyRate": 0.000001,
  * "currencyUnit": 1,
  * "date": "2019-08-24",
  * "id": 0,
  * "note": "string",
  * "released": true,
  * "rows": [
    * {
      * "batch": "string",
      * "costCenterCode": "string",
      * "directCost": 0,
      * "freightCost": 0,
      * "itemDescription": "string",
      * "itemId": "string",
      * "itemUnit": "string",
      * "otherCost": 0,
      * "projectId": "string",
      * "quantity": 0.01,
      * "rowId": 0,
      * "stockLocationCode": "string",
      * "stockLocationId": "c039ed46-ada4-4486-8700-89747e000395",
      * "stockLocationName": "string",
      * "stockPointCode": "string",
      * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c",
      * "stockPointName": "string"
}
],
  * "stockPointCode": "string",
  * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c",
  * "stockPointName": "string",
  * "voided": true

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_ManualInboundDocument/operation/release)Release manual inbound document 
The document will be locked and bookkept. 
The following error codes might be thrown:  

cannot_release_later_than_current_date
    Document date cannot be in the future. 

document_is_voided
    Document is voided. 

period_locked
    Document date is within a locked bookkeeping period.
##### path Parameters
idrequired| integer <int64> Manual Inbound document id.  
---|---  
### Responses
**204**
Successfully updated the specified resource.
**default**
WebException
put/api/warehouse/deliveries-v1/inbounddeliveries/{id}/release
Default server
https://api.fortnox.se/api/warehouse/deliveries-v1/inbounddeliveries/{id}/release
###  Response samples 
  * default


Content type
application/json
Copy
`{
  * "error": "string",
  * "id": "string",
  * "message": "string"

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_ManualInboundDocument/operation/voidDocument)Void manual inbound document 
A released manual inbound document might have connected outbounds, and can only be force voided. Note that a force void operation might cause a negative stock. 
The following error codes might be thrown:  

void_linked_outbound
    If this document has any outbounds transactions connected to it.
##### path Parameters
idrequired| integer <int64> Manual Inbound document id.  
---|---  
##### query Parameters
force| boolean true if we should force void, defaults to false  
---|---  
customVoidDate| string <date> date the void operation should be bookkeept on  
### Responses
**204**
Successfully updated the specified resource.
**default**
WebException
put/api/warehouse/deliveries-v1/inbounddeliveries/{id}/void
Default server
https://api.fortnox.se/api/warehouse/deliveries-v1/inbounddeliveries/{id}/void
###  Response samples 
  * default


Content type
application/json
Copy
`{
  * "error": "string",
  * "id": "string",
  * "message": "string"

}`
# [](https://api.fortnox.se/apidocs#tag/warehouse_ManualOutboundDocument)Manual Outbound Document
Handles `ManualOutboundDocument`s
## [](https://api.fortnox.se/apidocs#tag/warehouse_ManualOutboundDocument/operation/1_create_1)Create manual outbound document 
The `id` is set automatically.
##### Request Body schema: application/json
manual outbound document
daterequired| string <date>  
---|---  
id| integer <int64>  
note| string <= 1000 characters   
released| boolean  
rowsrequired| Array of objects (warehouse_ManualOutboundDocumentRow)  <= 2147483647 items   
stockPointCode| string  
stockPointId| string <uuid>  
stockPointName| string  
voided| boolean  
### Responses
**201**
the `ManualOutboundDocument` document.
**default**
WebException
post/api/warehouse/deliveries-v1/outbounddeliveries
Default server
https://api.fortnox.se/api/warehouse/deliveries-v1/outbounddeliveries
###  Request samples 
  * Payload


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "date": "2019-08-24",
  * "id": 0,
  * "note": "string",
  * "released": true,
  * "rows": [
    * {
      * "costCenterCode": "string",
      * "deliveredQuantity": 0,
      * "forcedQuantity": 0,
      * "itemDescription": "string",
      * "itemId": "string",
      * "itemUnit": "string",
      * "projectId": "string",
      * "quantity": 0.01,
      * "stockLocationCode": "string",
      * "stockLocationId": "c039ed46-ada4-4486-8700-89747e000395",
      * "stockLocationName": "string",
      * "stockPointCode": "string",
      * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c",
      * "stockPointName": "string"
}
],
  * "stockPointCode": "string",
  * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c",
  * "stockPointName": "string",
  * "voided": true

}`
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "date": "2019-08-24",
  * "id": 0,
  * "note": "string",
  * "released": true,
  * "rows": [
    * {
      * "costCenterCode": "string",
      * "deliveredQuantity": 0,
      * "forcedQuantity": 0,
      * "itemDescription": "string",
      * "itemId": "string",
      * "itemUnit": "string",
      * "projectId": "string",
      * "quantity": 0.01,
      * "stockLocationCode": "string",
      * "stockLocationId": "c039ed46-ada4-4486-8700-89747e000395",
      * "stockLocationName": "string",
      * "stockPointCode": "string",
      * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c",
      * "stockPointName": "string"
}
],
  * "stockPointCode": "string",
  * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c",
  * "stockPointName": "string",
  * "voided": true

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_ManualOutboundDocument/operation/get_1)Get manual outbound document 
##### path Parameters
idrequired| integer <int64> Manual Outbound document id.  
---|---  
### Responses
**200**
the `ManualOutboundDocument` document.
**default**
WebException
get/api/warehouse/deliveries-v1/outbounddeliveries/{id}
Default server
https://api.fortnox.se/api/warehouse/deliveries-v1/outbounddeliveries/{id}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "date": "2019-08-24",
  * "id": 0,
  * "note": "string",
  * "released": true,
  * "rows": [
    * {
      * "costCenterCode": "string",
      * "deliveredQuantity": 0,
      * "forcedQuantity": 0,
      * "itemDescription": "string",
      * "itemId": "string",
      * "itemUnit": "string",
      * "projectId": "string",
      * "quantity": 0.01,
      * "stockLocationCode": "string",
      * "stockLocationId": "c039ed46-ada4-4486-8700-89747e000395",
      * "stockLocationName": "string",
      * "stockPointCode": "string",
      * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c",
      * "stockPointName": "string"
}
],
  * "stockPointCode": "string",
  * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c",
  * "stockPointName": "string",
  * "voided": true

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_ManualOutboundDocument/operation/updateNote_1)Update note on manual outbound document 
When a Manual Outbound has been released, it is locked. The `note` field can still be updated using this endpoint.
##### path Parameters
idrequired| integer <int64> Manual Outbound document id  
---|---  
##### Request Body schema: application/json
Note.
note| string <= 1000 characters   
---|---  
### Responses
**204**
Successfully applied partial modifications to the resource.
**default**
WebException
patch/api/warehouse/deliveries-v1/outbounddeliveries/{id}
Default server
https://api.fortnox.se/api/warehouse/deliveries-v1/outbounddeliveries/{id}
###  Request samples 
  * Payload


Content type
application/json
Copy
`{
  * "note": "string"

}`
###  Response samples 
  * default


Content type
application/json
Copy
`{
  * "error": "string",
  * "id": "string",
  * "message": "string"

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_ManualOutboundDocument/operation/1_update_1)Update manual outbound document 
HTTP code 400 cannot_modify_released_document HTTP code 400 document_is_voided Document is voided. HTTP code 404 not found
##### path Parameters
idrequired| integer <int64> Manual Outbound document id.  
---|---  
##### Request Body schema: application/json
Manual Outbound document.
daterequired| string <date>  
---|---  
id| integer <int64>  
note| string <= 1000 characters   
released| boolean  
rowsrequired| Array of objects (warehouse_ManualOutboundDocumentRow)  <= 2147483647 items   
stockPointCode| string  
stockPointId| string <uuid>  
stockPointName| string  
voided| boolean  
### Responses
**200**
the `ManualOutboundDocument` document.
**default**
WebException
put/api/warehouse/deliveries-v1/outbounddeliveries/{id}
Default server
https://api.fortnox.se/api/warehouse/deliveries-v1/outbounddeliveries/{id}
###  Request samples 
  * Payload


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "date": "2019-08-24",
  * "id": 0,
  * "note": "string",
  * "released": true,
  * "rows": [
    * {
      * "costCenterCode": "string",
      * "deliveredQuantity": 0,
      * "forcedQuantity": 0,
      * "itemDescription": "string",
      * "itemId": "string",
      * "itemUnit": "string",
      * "projectId": "string",
      * "quantity": 0.01,
      * "stockLocationCode": "string",
      * "stockLocationId": "c039ed46-ada4-4486-8700-89747e000395",
      * "stockLocationName": "string",
      * "stockPointCode": "string",
      * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c",
      * "stockPointName": "string"
}
],
  * "stockPointCode": "string",
  * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c",
  * "stockPointName": "string",
  * "voided": true

}`
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "date": "2019-08-24",
  * "id": 0,
  * "note": "string",
  * "released": true,
  * "rows": [
    * {
      * "costCenterCode": "string",
      * "deliveredQuantity": 0,
      * "forcedQuantity": 0,
      * "itemDescription": "string",
      * "itemId": "string",
      * "itemUnit": "string",
      * "projectId": "string",
      * "quantity": 0.01,
      * "stockLocationCode": "string",
      * "stockLocationId": "c039ed46-ada4-4486-8700-89747e000395",
      * "stockLocationName": "string",
      * "stockPointCode": "string",
      * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c",
      * "stockPointName": "string"
}
],
  * "stockPointCode": "string",
  * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c",
  * "stockPointName": "string",
  * "voided": true

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_ManualOutboundDocument/operation/release_1)Release manual outbound document 
The document will be locked and bookkept. 
The following error codes might be thrown:  

cannot_release_later_than_current_date
    Document date cannot be in the future. 

document_is_voided
    Document is voided. 

period_locked
    Document date is within a locked bookkeeping period.
##### path Parameters
idrequired| integer <int64> Manual Outbound document id.  
---|---  
### Responses
**204**
Successfully updated the specified resource.
**default**
WebException
put/api/warehouse/deliveries-v1/outbounddeliveries/{id}/release
Default server
https://api.fortnox.se/api/warehouse/deliveries-v1/outbounddeliveries/{id}/release
###  Response samples 
  * default


Content type
application/json
Copy
`{
  * "error": "string",
  * "id": "string",
  * "message": "string"

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_ManualOutboundDocument/operation/voidDocument_1)Void manual outbound document 
##### path Parameters
idrequired| integer <int64> Manual Outbound document id.  
---|---  
##### query Parameters
customVoidDate| string <date> if provided this date will be used as the voided date instead of the document date  
---|---  
### Responses
**204**
Successfully updated the specified resource.
**default**
WebException
put/api/warehouse/deliveries-v1/outbounddeliveries/{id}/void
Default server
https://api.fortnox.se/api/warehouse/deliveries-v1/outbounddeliveries/{id}/void
###  Response samples 
  * default


Content type
application/json
Copy
`{
  * "error": "string",
  * "id": "string",
  * "message": "string"

}`
# [](https://api.fortnox.se/apidocs#tag/warehouse_ProductionOrder)Production Order
Handles Production Orders.
## [](https://api.fortnox.se/apidocs#tag/warehouse_ProductionOrder/operation/getAll_8)List production orders 
##### query Parameters
state| string Enum: "all" "incomplete" "delayed" "completed" "voided" Include only production orders with the given state. Allowed states: all, incomplete, delayed, completed, voided. (Default is incomplete)  
---|---  
itemId| string Include only production orders with the given production item.  
### Responses
**200**
A list of `ProductionOrders`.
**default**
WebException
get/api/warehouse/productionorders-v1
Default server
https://api.fortnox.se/api/warehouse/productionorders-v1
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "batch": "string",
  * "costCenterCode": "string",
  * "documentState": "completed",
  * "id": 0,
  * "inboundStockLocationId": "58a8b17c-cfb8-461c-a5b0-3bae5ca14b26",
  * "inboundStockPointId": "4d7045de-5283-430b-ab64-206c14d83d8a",
  * "itemDescription": "string",
  * "itemId": "string",
  * "itemUnit": "string",
  * "note": "string",
  * "outboundStockPointId": "70dbd7e7-8fb3-4fdd-9672-e1bd6ebda1f9",
  * "packageItems": [
    * {
      * "itemDescription": "string",
      * "itemId": "string",
      * "itemUnit": "string",
      * "quantityRequired": 0,
      * "quantityReserved": 0,
      * "totalQuantityRequired": 0
}
],
  * "productionDate": "2019-08-24",
  * "productionState": "registered",
  * "projectId": "string",
  * "quantity": 0.01,
  * "startDate": "2019-08-24"

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_ProductionOrder/operation/1_create_10)Create a new production order 
Set `itemId` to the item to be produced. 
Set `quantity` to number of units to produce. 
Set `startDate` to production start state. 
ProductionState is set to `reserved` by default. It can also be `registered`. Then no reservations will be made (no quantities will be assigned to the `packageItems` yet). 
Setting `outboundStockPointId` (where the `packageItems` will be taken from), and `inboundStockPointId` (where the produced item will be put) is mandatory multiple stockpoints has been activated in the warehouse settings. 
Before the document is released, the `productionDate` must be set. 
The `packageItems` to include is easiest to get by calling the method `getRequiredProductionParts`.
##### Request Body schema: */*
the production order to create `ProductionOrder`
batch| string  
---|---  
costCenterCode| string  
documentState| string Enum: "completed" "voided"  
id| integer <int64>  
inboundStockLocationId| string <uuid>  
inboundStockPointId| string <uuid>  
itemDescription| string  
itemId| string  
itemUnit| string  
note| string <= 1000 characters   
outboundStockPointId| string <uuid>  
packageItems| Array of objects (warehouse_PackageItem)   
productionDate| string <date>  
productionStaterequired| string Enum: "registered" "reserved" "ongoing"  
projectId| string  
quantityrequired| number >= 0.01   
startDaterequired| string <date>  
### Responses
**201**
the `ProductionOrder` document.
**default**
WebException
post/api/warehouse/productionorders-v1
Default server
https://api.fortnox.se/api/warehouse/productionorders-v1
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "batch": "string",
  * "costCenterCode": "string",
  * "documentState": "completed",
  * "id": 0,
  * "inboundStockLocationId": "58a8b17c-cfb8-461c-a5b0-3bae5ca14b26",
  * "inboundStockPointId": "4d7045de-5283-430b-ab64-206c14d83d8a",
  * "itemDescription": "string",
  * "itemId": "string",
  * "itemUnit": "string",
  * "note": "string",
  * "outboundStockPointId": "70dbd7e7-8fb3-4fdd-9672-e1bd6ebda1f9",
  * "packageItems": [
    * {
      * "itemDescription": "string",
      * "itemId": "string",
      * "itemUnit": "string",
      * "quantityRequired": 0,
      * "quantityReserved": 0,
      * "totalQuantityRequired": 0
}
],
  * "productionDate": "2019-08-24",
  * "productionState": "registered",
  * "projectId": "string",
  * "quantity": 0.01,
  * "startDate": "2019-08-24"

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_ProductionOrder/operation/getRequiredProductionParts)Get the package items (Bill Of Materials, BOMs) for a production article 
If no parameters are supplied, the `totalQuantityRequired` for producing 1 unit is returned. 
Query parameter `quantity` can optionally be supplied, which will calculate `totalQuantityRequired`. 
If query parameter `id` is supplied, it will get the quantity from that Production Order (the `quantity` query parameter is ignored if `id` is included).
##### path Parameters
itemIdrequired| string Production Article id  
---|---  
##### query Parameters
id| integer <int64> the id of the production order (optional)  
---|---  
quantity| string the quantity of the production order (assumed 1 if left empty)  
### Responses
**200**
A list of `PackageItems`.
**default**
WebException
get/api/warehouse/productionorders-v1/billofmaterials/{itemId}
Default server
https://api.fortnox.se/api/warehouse/productionorders-v1/billofmaterials/{itemId}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
`{
  * "itemDescription": "string",
  * "itemId": "string",
  * "itemUnit": "string",
  * "quantityRequired": 0,
  * "quantityReserved": 0,
  * "totalQuantityRequired": 0

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_ProductionOrder/operation/release_7)Release a production order document 
The document will be locked and bookkept. 
The following error codes might be thrown:  

PRODUCTION_DATE_IS_EMPTY
    Production date cannot be empty. 

CANNOT_RELEASE_AFTER_CURRENT_DATE
    Document date cannot be in the future. 

DOCUMENT_IS_VOIDED
     The document has been voided and can no longer be modified. 

DOCUMENT_IS_RELEASED
    The document has already been released and can no longer be modified. 

DOCUMENT_NOT_FULLY_RESERVED
    The documents package items (BOMs, Bill Of Materials) has not been fully reserved (reserved quantity is not equal to total required quantity for one or more package item).
##### path Parameters
idrequired| integer <int64> Production Order document id.  
---|---  
### Responses
**200**
the `ProductionOrder` document.
**default**
WebException
put/api/warehouse/productionorders-v1/release/{id}
Default server
https://api.fortnox.se/api/warehouse/productionorders-v1/release/{id}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "batch": "string",
  * "costCenterCode": "string",
  * "documentState": "completed",
  * "id": 0,
  * "inboundStockLocationId": "58a8b17c-cfb8-461c-a5b0-3bae5ca14b26",
  * "inboundStockPointId": "4d7045de-5283-430b-ab64-206c14d83d8a",
  * "itemDescription": "string",
  * "itemId": "string",
  * "itemUnit": "string",
  * "note": "string",
  * "outboundStockPointId": "70dbd7e7-8fb3-4fdd-9672-e1bd6ebda1f9",
  * "packageItems": [
    * {
      * "itemDescription": "string",
      * "itemId": "string",
      * "itemUnit": "string",
      * "quantityRequired": 0,
      * "quantityReserved": 0,
      * "totalQuantityRequired": 0
}
],
  * "productionDate": "2019-08-24",
  * "productionState": "registered",
  * "projectId": "string",
  * "quantity": 0.01,
  * "startDate": "2019-08-24"

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_ProductionOrder/operation/voidProductionOrder)Void a production order 
A released production order might have connected outbounds, and can only be force voided. Note that a force void operation might cause a negative stock.
##### path Parameters
idrequired| integer <int64> Production Order document id.  
---|---  
##### query Parameters
force| boolean true to force void a released document, default false  
---|---  
### Responses
**204**
Successfully updated the specified resource.
**default**
WebException
put/api/warehouse/productionorders-v1/void/{id}
Default server
https://api.fortnox.se/api/warehouse/productionorders-v1/void/{id}
###  Response samples 
  * default


Content type
application/json
Copy
`{
  * "error": "string",
  * "id": "string",
  * "message": "string"

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_ProductionOrder/operation/1_get_16)Get Production Order document 
##### path Parameters
idrequired| integer <int64> Production Order document id.  
---|---  
### Responses
**200**
the `ProductionOrder` document.
**default**
WebException
get/api/warehouse/productionorders-v1/{id}
Default server
https://api.fortnox.se/api/warehouse/productionorders-v1/{id}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "batch": "string",
  * "costCenterCode": "string",
  * "documentState": "completed",
  * "id": 0,
  * "inboundStockLocationId": "58a8b17c-cfb8-461c-a5b0-3bae5ca14b26",
  * "inboundStockPointId": "4d7045de-5283-430b-ab64-206c14d83d8a",
  * "itemDescription": "string",
  * "itemId": "string",
  * "itemUnit": "string",
  * "note": "string",
  * "outboundStockPointId": "70dbd7e7-8fb3-4fdd-9672-e1bd6ebda1f9",
  * "packageItems": [
    * {
      * "itemDescription": "string",
      * "itemId": "string",
      * "itemUnit": "string",
      * "quantityRequired": 0,
      * "quantityReserved": 0,
      * "totalQuantityRequired": 0
}
],
  * "productionDate": "2019-08-24",
  * "productionState": "registered",
  * "projectId": "string",
  * "quantity": 0.01,
  * "startDate": "2019-08-24"

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_ProductionOrder/operation/updateNote_2)Update the note of a production order 
When a Production Order has been released it is locked. However, the `note` field can still be updated using this endpoint.
##### path Parameters
idrequired| integer <int64> Production Order document id.  
---|---  
##### Request Body schema: */*
contains data to be patched onto the production order
note| string <= 1000 characters   
---|---  
### Responses
**200**
the `ProductionOrder` document.
**default**
WebException
patch/api/warehouse/productionorders-v1/{id}
Default server
https://api.fortnox.se/api/warehouse/productionorders-v1/{id}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "batch": "string",
  * "costCenterCode": "string",
  * "documentState": "completed",
  * "id": 0,
  * "inboundStockLocationId": "58a8b17c-cfb8-461c-a5b0-3bae5ca14b26",
  * "inboundStockPointId": "4d7045de-5283-430b-ab64-206c14d83d8a",
  * "itemDescription": "string",
  * "itemId": "string",
  * "itemUnit": "string",
  * "note": "string",
  * "outboundStockPointId": "70dbd7e7-8fb3-4fdd-9672-e1bd6ebda1f9",
  * "packageItems": [
    * {
      * "itemDescription": "string",
      * "itemId": "string",
      * "itemUnit": "string",
      * "quantityRequired": 0,
      * "quantityReserved": 0,
      * "totalQuantityRequired": 0
}
],
  * "productionDate": "2019-08-24",
  * "productionState": "registered",
  * "projectId": "string",
  * "quantity": 0.01,
  * "startDate": "2019-08-24"

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_ProductionOrder/operation/1_update_5)Update a production order 
Note that you must submit the full Production Order document when updating.
##### path Parameters
idrequired| integer <int64> Production Order document id.  
---|---  
##### Request Body schema: */*
the production order data see `ProductionOrder`
batch| string  
---|---  
costCenterCode| string  
documentState| string Enum: "completed" "voided"  
id| integer <int64>  
inboundStockLocationId| string <uuid>  
inboundStockPointId| string <uuid>  
itemDescription| string  
itemId| string  
itemUnit| string  
note| string <= 1000 characters   
outboundStockPointId| string <uuid>  
packageItems| Array of objects (warehouse_PackageItem)   
productionDate| string <date>  
productionStaterequired| string Enum: "registered" "reserved" "ongoing"  
projectId| string  
quantityrequired| number >= 0.01   
startDaterequired| string <date>  
### Responses
**200**
the `ProductionOrder` document.
**default**
WebException
put/api/warehouse/productionorders-v1/{id}
Default server
https://api.fortnox.se/api/warehouse/productionorders-v1/{id}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "batch": "string",
  * "costCenterCode": "string",
  * "documentState": "completed",
  * "id": 0,
  * "inboundStockLocationId": "58a8b17c-cfb8-461c-a5b0-3bae5ca14b26",
  * "inboundStockPointId": "4d7045de-5283-430b-ab64-206c14d83d8a",
  * "itemDescription": "string",
  * "itemId": "string",
  * "itemUnit": "string",
  * "note": "string",
  * "outboundStockPointId": "70dbd7e7-8fb3-4fdd-9672-e1bd6ebda1f9",
  * "packageItems": [
    * {
      * "itemDescription": "string",
      * "itemId": "string",
      * "itemUnit": "string",
      * "quantityRequired": 0,
      * "quantityReserved": 0,
      * "totalQuantityRequired": 0
}
],
  * "productionDate": "2019-08-24",
  * "productionState": "registered",
  * "projectId": "string",
  * "quantity": 0.01,
  * "startDate": "2019-08-24"

}`
# [](https://api.fortnox.se/apidocs#tag/warehouse_PurchaseOrder)Purchase Order
Handles Purchase Orders
## [](https://api.fortnox.se/apidocs#tag/warehouse_PurchaseOrder/operation/getAll_9)List Purchase Orders 
List purchase orders matching the given parameters. 
Sortable fields: `id`, `supplier_number`, `order_date`, `internal_reference`, `response_state`, `delivery_date`
##### query Parameters
q| string Include only documents where `id` or `internalReference`-field contains the given text (case-insensitive).  
---|---  
supplierNumber| string Include only documents with the given `supplierNumber`.  
state| string Enum: "NOT_SENT" "SENT" "SENT_NOT_REJECTED" "DELAYED" "RECEIVED" "VOIDED" "CURRENT" "ALL" Include only documents with the given `purchaseOrderState`.  
itemId| string Include only documents with the given `itemId`.  
purchaseType| string Enum: "WAREHOUSE" "DROPSHIP" Include only documents with the given `purchaseType`  
internalReference| string Include only documents where `internalReference' contains the given text (case-insensitive).  
note| string Include only documents where `note`-field contains the given text (case-insensitive).  
### Responses
**200**
A list of `PurchaseOrders`.
**default**
WebException
get/api/warehouse/purchaseorders-v1
Default server
https://api.fortnox.se/api/warehouse/purchaseorders-v1
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "confirmationEmail": "string",
  * "costCenterCode": "string",
  * "currencyCode": "str",
  * "currencyRate": 0,
  * "currencyUnit": 1,
  * "customerId": "string",
  * "customerName": "string",
  * "customerNumber": "string",
  * "deliveryAddress": "string",
  * "deliveryAddress2": "string",
  * "deliveryCity": "string",
  * "deliveryCountryCode": "str",
  * "deliveryDate": "2019-08-24",
  * "deliveryName": "string",
  * "deliveryZipCode": "string",
  * "dropship": true,
  * "id": 0,
  * "internalReference": "string",
  * "languageCode": "str",
  * "manuallyCompleted": true,
  * "messageToSupplier": "string",
  * "note": "string",
  * "orderDate": "2019-08-24",
  * "orderValue": 0,
  * "orderValueInSEK": 0,
  * "ourReference": "string",
  * "outboundDocumentReference": {
    * "id": "string",
    * "type": "string"
},
  * "paymentTermsCode": "string",
  * "projectId": "string",
  * "purchaseOrderState": "NOT_SENT",
  * "purchaseType": "WAREHOUSE",
  * "responseState": "NOT_SENT",
  * "rows": [
    * {
      * "backOrderQuantity": 0,
      * "costCenterCode": "string",
      * "currencyCode": "str",
      * "id": "497f6eca-6276-4993-bfeb-53cbbbba6f08",
      * "isStockItem": true,
      * "itemDescription": "string",
      * "itemId": "string",
      * "itemUnit": "string",
      * "notes": [
        * {
          * "note": "string",
          * "purchaseOrderId": 0,
          * "purchaseOrderRowId": "ba867b0e-f326-42c4-9f43-58bde9b319da",
          * "rowNum": 0
}
],
      * "orderedQuantity": 0,
      * "price": 0,
      * "projectId": "string",
      * "purchaseOrderId": 0,
      * "receivedQuantity": 0,
      * "remainingOrderedQuantity": 0,
      * "rowNum": 0,
      * "stockLocationCode": "string",
      * "stockLocationId": "c039ed46-ada4-4486-8700-89747e000395",
      * "stockLocationName": "string",
      * "stockPointCode": "string",
      * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c",
      * "stockPointName": "string"
}
],
  * "stockPointCode": "string",
  * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c",
  * "supplier": "string",
  * "supplierAddress": "string",
  * "supplierAddress2": "string",
  * "supplierCity": "string",
  * "supplierCountryCode": "str",
  * "supplierEmail": "string",
  * "supplierName": "string",
  * "supplierNumber": "string",
  * "supplierPostCode": "string",
  * "totalReceivedQuantity": 0,
  * "translatedResponseState": "string",
  * "voided": true,
  * "yourReference": "string"

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_PurchaseOrder/operation/create_11)Create Purchase Order 
##### Request Body schema: */*
`PurchaseOrder` document.
confirmationEmail| string <= 100 characters   
---|---  
costCenterCode| string <= 25 characters   
currencyCoderequired| string <= 3 characters   
currencyRaterequired| number  
currencyUnit| integer <int32> >= 1   
customerId| string <= 25 characters   
customerName| string <= 1024 characters   
customerNumber| string <= 1024 characters   
deliveryAddressrequired| string [ 1 .. 1024 ] characters   
deliveryAddress2| string <= 1024 characters   
deliveryCityrequired| string [ 1 .. 50 ] characters   
deliveryCountryCode| string <= 3 characters   
deliveryDate| string <date>  
deliveryNamerequired| string [ 1 .. 50 ] characters   
deliveryZipCoderequired| string [ 1 .. 10 ] characters   
dropship| boolean  
id| integer <int64>  
internalReference| string <= 50 characters   
languageCode| string <= 3 characters   
manuallyCompleted| boolean  
messageToSupplier| string <= 1000 characters   
note| string <= 1000 characters   
orderDaterequired| string <date>  
orderValue| number  
orderValueInSEK| number  
ourReference| string <= 50 characters   
outboundDocumentReference| object (warehouse_DocumentReference)   
paymentTermsCoderequired| string <= 20 characters   
projectId| string <= 25 characters   
purchaseOrderState| string Enum: "NOT_SENT" "SENT" "SENT_NOT_REJECTED" "DELAYED" "RECEIVED" "VOIDED" "CURRENT" "ALL"  
purchaseType| string Enum: "WAREHOUSE" "DROPSHIP"  
responseState| string Enum: "NOT_SENT" "SENT" "ACCEPTED_WITH_REQ_DLV_DATE" "ACCEPTED_WITH_CHANGED_DLV_DATE" "PARTLY_ACCEPTED_WITH_REQ_DLV_DATE" "PARTLY_ACCEPTED_WITH_CHANGED_DLV_DATE" "REJECTED"  
rows| Array of objects (warehouse_PurchaseOrderRow)   
stockPointCode| string  
stockPointId| string <uuid>  
supplier| string  
supplierAddress| string <= 1024 characters   
supplierAddress2| string <= 1024 characters   
supplierCity| string <= 1024 characters   
supplierCountryCode| string <= 3 characters   
supplierEmail| string <= 100 characters   
supplierName| string <= 1024 characters   
supplierNumberrequired| string <= 1024 characters   
supplierPostCode| string <= 1024 characters   
totalReceivedQuantity| number  
translatedResponseState| string  
voided| boolean  
yourReference| string <= 50 characters   
### Responses
**201**
The created `PurchaseOrder` document.
**default**
WebException
post/api/warehouse/purchaseorders-v1
Default server
https://api.fortnox.se/api/warehouse/purchaseorders-v1
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "confirmationEmail": "string",
  * "costCenterCode": "string",
  * "currencyCode": "str",
  * "currencyRate": 0,
  * "currencyUnit": 1,
  * "customerId": "string",
  * "customerName": "string",
  * "customerNumber": "string",
  * "deliveryAddress": "string",
  * "deliveryAddress2": "string",
  * "deliveryCity": "string",
  * "deliveryCountryCode": "str",
  * "deliveryDate": "2019-08-24",
  * "deliveryName": "string",
  * "deliveryZipCode": "string",
  * "dropship": true,
  * "id": 0,
  * "internalReference": "string",
  * "languageCode": "str",
  * "manuallyCompleted": true,
  * "messageToSupplier": "string",
  * "note": "string",
  * "orderDate": "2019-08-24",
  * "orderValue": 0,
  * "orderValueInSEK": 0,
  * "ourReference": "string",
  * "outboundDocumentReference": {
    * "id": "string",
    * "type": "string"
},
  * "paymentTermsCode": "string",
  * "projectId": "string",
  * "purchaseOrderState": "NOT_SENT",
  * "purchaseType": "WAREHOUSE",
  * "responseState": "NOT_SENT",
  * "rows": [
    * {
      * "backOrderQuantity": 0,
      * "costCenterCode": "string",
      * "currencyCode": "str",
      * "id": "497f6eca-6276-4993-bfeb-53cbbbba6f08",
      * "isStockItem": true,
      * "itemDescription": "string",
      * "itemId": "string",
      * "itemUnit": "string",
      * "notes": [
        * {
          * "note": "string",
          * "purchaseOrderId": 0,
          * "purchaseOrderRowId": "ba867b0e-f326-42c4-9f43-58bde9b319da",
          * "rowNum": 0
}
],
      * "orderedQuantity": 0,
      * "price": 0,
      * "projectId": "string",
      * "purchaseOrderId": 0,
      * "receivedQuantity": 0,
      * "remainingOrderedQuantity": 0,
      * "rowNum": 0,
      * "stockLocationCode": "string",
      * "stockLocationId": "c039ed46-ada4-4486-8700-89747e000395",
      * "stockLocationName": "string",
      * "stockPointCode": "string",
      * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c",
      * "stockPointName": "string"
}
],
  * "stockPointCode": "string",
  * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c",
  * "supplier": "string",
  * "supplierAddress": "string",
  * "supplierAddress2": "string",
  * "supplierCity": "string",
  * "supplierCountryCode": "str",
  * "supplierEmail": "string",
  * "supplierName": "string",
  * "supplierNumber": "string",
  * "supplierPostCode": "string",
  * "totalReceivedQuantity": 0,
  * "translatedResponseState": "string",
  * "voided": true,
  * "yourReference": "string"

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_PurchaseOrder/operation/getCsvReport)Get CSV list of Purchase Orders 
##### query Parameters
q| string Include only documents where `id` or `internalReference`-field contains the given text (case-insensitive).  
---|---  
supplierNumber| string Include only documents with the given `supplierNumber`.  
state| string Enum: "NOT_SENT" "SENT" "SENT_NOT_REJECTED" "DELAYED" "RECEIVED" "VOIDED" "CURRENT" "ALL" Include only documents with the given `purchaseOrderState`.  
itemId| string Include only documents with the given `itemId`.  
purchaseType| string Enum: "WAREHOUSE" "DROPSHIP" Include only documents with the given `purchaseType`  
internalReference| string Include only documents where `internalReference' contains the given text (case-insensitive).  
note| string Include only documents where `note`-field contains the given text (case-insensitive).  
showPurchaseTypeColumn| boolean True to include the purchase type column, default is false.  
### Responses
**200**
A list of `PurchaseOrders`.
**default**
WebException
get/api/warehouse/purchaseorders-v1/csv
Default server
https://api.fortnox.se/api/warehouse/purchaseorders-v1/csv
## [](https://api.fortnox.se/apidocs#tag/warehouse_PurchaseOrder/operation/batchUpdateResponseState)Update response states 
##### query Parameters
ids| Array of integers <int64> [ items <int64 > ] List of purchase order ids.  
---|---  
##### Request Body schema: */*
The new response state.
responseState| string Enum: "NOT_SENT" "SENT" "ACCEPTED_WITH_REQ_DLV_DATE" "ACCEPTED_WITH_CHANGED_DLV_DATE" "PARTLY_ACCEPTED_WITH_REQ_DLV_DATE" "PARTLY_ACCEPTED_WITH_CHANGED_DLV_DATE" "REJECTED"  
---|---  
### Responses
**200**
a list of the updated `PurchaseOrders`
**default**
WebException
put/api/warehouse/purchaseorders-v1/response
Default server
https://api.fortnox.se/api/warehouse/purchaseorders-v1/response
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "confirmationEmail": "string",
  * "costCenterCode": "string",
  * "currencyCode": "str",
  * "currencyRate": 0,
  * "currencyUnit": 1,
  * "customerId": "string",
  * "customerName": "string",
  * "customerNumber": "string",
  * "deliveryAddress": "string",
  * "deliveryAddress2": "string",
  * "deliveryCity": "string",
  * "deliveryCountryCode": "str",
  * "deliveryDate": "2019-08-24",
  * "deliveryName": "string",
  * "deliveryZipCode": "string",
  * "dropship": true,
  * "id": 0,
  * "internalReference": "string",
  * "languageCode": "str",
  * "manuallyCompleted": true,
  * "messageToSupplier": "string",
  * "note": "string",
  * "orderDate": "2019-08-24",
  * "orderValue": 0,
  * "orderValueInSEK": 0,
  * "ourReference": "string",
  * "outboundDocumentReference": {
    * "id": "string",
    * "type": "string"
},
  * "paymentTermsCode": "string",
  * "projectId": "string",
  * "purchaseOrderState": "NOT_SENT",
  * "purchaseType": "WAREHOUSE",
  * "responseState": "NOT_SENT",
  * "rows": [
    * {
      * "backOrderQuantity": 0,
      * "costCenterCode": "string",
      * "currencyCode": "str",
      * "id": "497f6eca-6276-4993-bfeb-53cbbbba6f08",
      * "isStockItem": true,
      * "itemDescription": "string",
      * "itemId": "string",
      * "itemUnit": "string",
      * "notes": [
        * {
          * "note": "string",
          * "purchaseOrderId": 0,
          * "purchaseOrderRowId": "ba867b0e-f326-42c4-9f43-58bde9b319da",
          * "rowNum": 0
}
],
      * "orderedQuantity": 0,
      * "price": 0,
      * "projectId": "string",
      * "purchaseOrderId": 0,
      * "receivedQuantity": 0,
      * "remainingOrderedQuantity": 0,
      * "rowNum": 0,
      * "stockLocationCode": "string",
      * "stockLocationId": "c039ed46-ada4-4486-8700-89747e000395",
      * "stockLocationName": "string",
      * "stockPointCode": "string",
      * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c",
      * "stockPointName": "string"
}
],
  * "stockPointCode": "string",
  * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c",
  * "supplier": "string",
  * "supplierAddress": "string",
  * "supplierAddress2": "string",
  * "supplierCity": "string",
  * "supplierCountryCode": "str",
  * "supplierEmail": "string",
  * "supplierName": "string",
  * "supplierNumber": "string",
  * "supplierPostCode": "string",
  * "totalReceivedQuantity": 0,
  * "translatedResponseState": "string",
  * "voided": true,
  * "yourReference": "string"

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_PurchaseOrder/operation/sendPurchaseOrders)Sends multiple purchase orders via email 
##### Request Body schema: */*
List of Purchase order ids.
Array 
integer <int64>
### Responses
**204**
Successfully created a new resource.
**default**
WebException
post/api/warehouse/purchaseorders-v1/sendpurchaseorders
Default server
https://api.fortnox.se/api/warehouse/purchaseorders-v1/sendpurchaseorders
###  Response samples 
  * default


Content type
application/json
Copy
`{
  * "error": "string",
  * "id": "string",
  * "message": "string"

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_PurchaseOrder/operation/1_get_17)Get Purchase Order 
##### path Parameters
idrequired| integer <int64> Purchase order id.  
---|---  
##### query Parameters
ignoreIncomingGoodsId| integer <int64> used for calculating the remaining ordered quantity. null will take the received quantity from all incoming goods  
---|---  
### Responses
**200**
The `PurchaseOrder`.
**default**
WebException
get/api/warehouse/purchaseorders-v1/{id}
Default server
https://api.fortnox.se/api/warehouse/purchaseorders-v1/{id}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "confirmationEmail": "string",
  * "costCenterCode": "string",
  * "currencyCode": "str",
  * "currencyRate": 0,
  * "currencyUnit": 1,
  * "customerId": "string",
  * "customerName": "string",
  * "customerNumber": "string",
  * "deliveryAddress": "string",
  * "deliveryAddress2": "string",
  * "deliveryCity": "string",
  * "deliveryCountryCode": "str",
  * "deliveryDate": "2019-08-24",
  * "deliveryName": "string",
  * "deliveryZipCode": "string",
  * "dropship": true,
  * "id": 0,
  * "internalReference": "string",
  * "languageCode": "str",
  * "manuallyCompleted": true,
  * "messageToSupplier": "string",
  * "note": "string",
  * "orderDate": "2019-08-24",
  * "orderValue": 0,
  * "orderValueInSEK": 0,
  * "ourReference": "string",
  * "outboundDocumentReference": {
    * "id": "string",
    * "type": "string"
},
  * "paymentTermsCode": "string",
  * "projectId": "string",
  * "purchaseOrderState": "NOT_SENT",
  * "purchaseType": "WAREHOUSE",
  * "responseState": "NOT_SENT",
  * "rows": [
    * {
      * "backOrderQuantity": 0,
      * "costCenterCode": "string",
      * "currencyCode": "str",
      * "id": "497f6eca-6276-4993-bfeb-53cbbbba6f08",
      * "isStockItem": true,
      * "itemDescription": "string",
      * "itemId": "string",
      * "itemUnit": "string",
      * "notes": [
        * {
          * "note": "string",
          * "purchaseOrderId": 0,
          * "purchaseOrderRowId": "ba867b0e-f326-42c4-9f43-58bde9b319da",
          * "rowNum": 0
}
],
      * "orderedQuantity": 0,
      * "price": 0,
      * "projectId": "string",
      * "purchaseOrderId": 0,
      * "receivedQuantity": 0,
      * "remainingOrderedQuantity": 0,
      * "rowNum": 0,
      * "stockLocationCode": "string",
      * "stockLocationId": "c039ed46-ada4-4486-8700-89747e000395",
      * "stockLocationName": "string",
      * "stockPointCode": "string",
      * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c",
      * "stockPointName": "string"
}
],
  * "stockPointCode": "string",
  * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c",
  * "supplier": "string",
  * "supplierAddress": "string",
  * "supplierAddress2": "string",
  * "supplierCity": "string",
  * "supplierCountryCode": "str",
  * "supplierEmail": "string",
  * "supplierName": "string",
  * "supplierNumber": "string",
  * "supplierPostCode": "string",
  * "totalReceivedQuantity": 0,
  * "translatedResponseState": "string",
  * "voided": true,
  * "yourReference": "string"

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_PurchaseOrder/operation/1_update_6)Update Purchase Order 
##### path Parameters
idrequired| integer <int64> Purchase order id.  
---|---  
##### Request Body schema: */*
The `PurchaseOrder` document.
confirmationEmail| string <= 100 characters   
---|---  
costCenterCode| string <= 25 characters   
currencyCoderequired| string <= 3 characters   
currencyRaterequired| number  
currencyUnit| integer <int32> >= 1   
customerId| string <= 25 characters   
customerName| string <= 1024 characters   
customerNumber| string <= 1024 characters   
deliveryAddressrequired| string [ 1 .. 1024 ] characters   
deliveryAddress2| string <= 1024 characters   
deliveryCityrequired| string [ 1 .. 50 ] characters   
deliveryCountryCode| string <= 3 characters   
deliveryDate| string <date>  
deliveryNamerequired| string [ 1 .. 50 ] characters   
deliveryZipCoderequired| string [ 1 .. 10 ] characters   
dropship| boolean  
id| integer <int64>  
internalReference| string <= 50 characters   
languageCode| string <= 3 characters   
manuallyCompleted| boolean  
messageToSupplier| string <= 1000 characters   
note| string <= 1000 characters   
orderDaterequired| string <date>  
orderValue| number  
orderValueInSEK| number  
ourReference| string <= 50 characters   
outboundDocumentReference| object (warehouse_DocumentReference)   
paymentTermsCoderequired| string <= 20 characters   
projectId| string <= 25 characters   
purchaseOrderState| string Enum: "NOT_SENT" "SENT" "SENT_NOT_REJECTED" "DELAYED" "RECEIVED" "VOIDED" "CURRENT" "ALL"  
purchaseType| string Enum: "WAREHOUSE" "DROPSHIP"  
responseState| string Enum: "NOT_SENT" "SENT" "ACCEPTED_WITH_REQ_DLV_DATE" "ACCEPTED_WITH_CHANGED_DLV_DATE" "PARTLY_ACCEPTED_WITH_REQ_DLV_DATE" "PARTLY_ACCEPTED_WITH_CHANGED_DLV_DATE" "REJECTED"  
rows| Array of objects (warehouse_PurchaseOrderRow)   
stockPointCode| string  
stockPointId| string <uuid>  
supplier| string  
supplierAddress| string <= 1024 characters   
supplierAddress2| string <= 1024 characters   
supplierCity| string <= 1024 characters   
supplierCountryCode| string <= 3 characters   
supplierEmail| string <= 100 characters   
supplierName| string <= 1024 characters   
supplierNumberrequired| string <= 1024 characters   
supplierPostCode| string <= 1024 characters   
totalReceivedQuantity| number  
translatedResponseState| string  
voided| boolean  
yourReference| string <= 50 characters   
### Responses
**200**
The updated `PurchaseOrder`.
**default**
WebException
put/api/warehouse/purchaseorders-v1/{id}
Default server
https://api.fortnox.se/api/warehouse/purchaseorders-v1/{id}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "confirmationEmail": "string",
  * "costCenterCode": "string",
  * "currencyCode": "str",
  * "currencyRate": 0,
  * "currencyUnit": 1,
  * "customerId": "string",
  * "customerName": "string",
  * "customerNumber": "string",
  * "deliveryAddress": "string",
  * "deliveryAddress2": "string",
  * "deliveryCity": "string",
  * "deliveryCountryCode": "str",
  * "deliveryDate": "2019-08-24",
  * "deliveryName": "string",
  * "deliveryZipCode": "string",
  * "dropship": true,
  * "id": 0,
  * "internalReference": "string",
  * "languageCode": "str",
  * "manuallyCompleted": true,
  * "messageToSupplier": "string",
  * "note": "string",
  * "orderDate": "2019-08-24",
  * "orderValue": 0,
  * "orderValueInSEK": 0,
  * "ourReference": "string",
  * "outboundDocumentReference": {
    * "id": "string",
    * "type": "string"
},
  * "paymentTermsCode": "string",
  * "projectId": "string",
  * "purchaseOrderState": "NOT_SENT",
  * "purchaseType": "WAREHOUSE",
  * "responseState": "NOT_SENT",
  * "rows": [
    * {
      * "backOrderQuantity": 0,
      * "costCenterCode": "string",
      * "currencyCode": "str",
      * "id": "497f6eca-6276-4993-bfeb-53cbbbba6f08",
      * "isStockItem": true,
      * "itemDescription": "string",
      * "itemId": "string",
      * "itemUnit": "string",
      * "notes": [
        * {
          * "note": "string",
          * "purchaseOrderId": 0,
          * "purchaseOrderRowId": "ba867b0e-f326-42c4-9f43-58bde9b319da",
          * "rowNum": 0
}
],
      * "orderedQuantity": 0,
      * "price": 0,
      * "projectId": "string",
      * "purchaseOrderId": 0,
      * "receivedQuantity": 0,
      * "remainingOrderedQuantity": 0,
      * "rowNum": 0,
      * "stockLocationCode": "string",
      * "stockLocationId": "c039ed46-ada4-4486-8700-89747e000395",
      * "stockLocationName": "string",
      * "stockPointCode": "string",
      * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c",
      * "stockPointName": "string"
}
],
  * "stockPointCode": "string",
  * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c",
  * "supplier": "string",
  * "supplierAddress": "string",
  * "supplierAddress2": "string",
  * "supplierCity": "string",
  * "supplierCountryCode": "str",
  * "supplierEmail": "string",
  * "supplierName": "string",
  * "supplierNumber": "string",
  * "supplierPostCode": "string",
  * "totalReceivedQuantity": 0,
  * "translatedResponseState": "string",
  * "voided": true,
  * "yourReference": "string"

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_PurchaseOrder/operation/setManuallyCompleted)Manually complete Purchase Order 
The purchase order will be treated as fully received. Any remaining quantity will be ignored.
##### path Parameters
idrequired| integer <int64> Purchase order id.  
---|---  
### Responses
**204**
Successfully updated the specified resource.
**default**
WebException
put/api/warehouse/purchaseorders-v1/{id}/complete
Default server
https://api.fortnox.se/api/warehouse/purchaseorders-v1/{id}/complete
###  Response samples 
  * default


Content type
application/json
Copy
`{
  * "error": "string",
  * "id": "string",
  * "message": "string"

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_PurchaseOrder/operation/setDropshipManuallyCompleted)Manually complete dropship order 
The dropship order will be treated as fully received. Any remaining quantity will be ignored.
##### path Parameters
idrequired| integer <int64> Purchase order id.  
---|---  
### Responses
**200**
`ReleaseParentOrder` status for release of parent order
**default**
WebException
put/api/warehouse/purchaseorders-v1/{id}/dropshipcomplete
Default server
https://api.fortnox.se/api/warehouse/purchaseorders-v1/{id}/dropshipcomplete
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
`{
  * "releasedParentOrder": true

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_PurchaseOrder/operation/getMatchedDocuments_1)List matched documents 
Get a list of `DocumentReference` of linked/connected purchase orders to incoming goods and/or invoice document.
##### path Parameters
idrequired| integer <int64> Purchase order id.  
---|---  
### Responses
**200**
list of document references
**default**
WebException
get/api/warehouse/purchaseorders-v1/{id}/matches
Default server
https://api.fortnox.se/api/warehouse/purchaseorders-v1/{id}/matches
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
`{
  * "id": "string",
  * "type": "string"

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_PurchaseOrder/operation/getAttachedNotes)Get notes 
Get notes for a purchase order.
##### path Parameters
idrequired| integer <int64> Purchase order id.  
---|---  
### Responses
**200**
A list of `PurchaseOrderRowNotes`.
**default**
WebException
get/api/warehouse/purchaseorders-v1/{id}/notes
Default server
https://api.fortnox.se/api/warehouse/purchaseorders-v1/{id}/notes
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
`{
  * "note": "string",
  * "purchaseOrderId": 0,
  * "purchaseOrderRowId": "ba867b0e-f326-42c4-9f43-58bde9b319da",
  * "rowNum": 0

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_PurchaseOrder/operation/updatePartial)Partial update Purchase Order 
Perform a partial update of a purchase order, see `PartialPurchaseOrder` for possible fields that are updateable.
##### path Parameters
idrequired| integer <int64> Purchase order id.  
---|---  
##### Request Body schema: */*
the changes for the purchase order, see `PartialPurchaseOrder`
deliveryDate| string <date>  
---|---  
internalReference| string <= 50 characters   
messageToSupplier| string <= 1000 characters   
note| string <= 1000 characters   
supplierName| string <= 1024 characters   
### Responses
**200**
the updated `PartialPurchaseOrder`
**default**
WebException
patch/api/warehouse/purchaseorders-v1/{id}/partial
Default server
https://api.fortnox.se/api/warehouse/purchaseorders-v1/{id}/partial
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
`{
  * "deliveryDate": "2019-08-24",
  * "internalReference": "string",
  * "messageToSupplier": "string",
  * "note": "string",
  * "supplierName": "string"

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_PurchaseOrder/operation/updateResponseState)Update response state 
##### path Parameters
idrequired| integer <int64> Purchase order id.  
---|---  
##### Request Body schema: */*
The new response state.
responseState| string Enum: "NOT_SENT" "SENT" "ACCEPTED_WITH_REQ_DLV_DATE" "ACCEPTED_WITH_CHANGED_DLV_DATE" "PARTLY_ACCEPTED_WITH_REQ_DLV_DATE" "PARTLY_ACCEPTED_WITH_CHANGED_DLV_DATE" "REJECTED"  
---|---  
### Responses
**200**
The updated `PurchaseOrder`
**default**
WebException
put/api/warehouse/purchaseorders-v1/{id}/response
Default server
https://api.fortnox.se/api/warehouse/purchaseorders-v1/{id}/response
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "confirmationEmail": "string",
  * "costCenterCode": "string",
  * "currencyCode": "str",
  * "currencyRate": 0,
  * "currencyUnit": 1,
  * "customerId": "string",
  * "customerName": "string",
  * "customerNumber": "string",
  * "deliveryAddress": "string",
  * "deliveryAddress2": "string",
  * "deliveryCity": "string",
  * "deliveryCountryCode": "str",
  * "deliveryDate": "2019-08-24",
  * "deliveryName": "string",
  * "deliveryZipCode": "string",
  * "dropship": true,
  * "id": 0,
  * "internalReference": "string",
  * "languageCode": "str",
  * "manuallyCompleted": true,
  * "messageToSupplier": "string",
  * "note": "string",
  * "orderDate": "2019-08-24",
  * "orderValue": 0,
  * "orderValueInSEK": 0,
  * "ourReference": "string",
  * "outboundDocumentReference": {
    * "id": "string",
    * "type": "string"
},
  * "paymentTermsCode": "string",
  * "projectId": "string",
  * "purchaseOrderState": "NOT_SENT",
  * "purchaseType": "WAREHOUSE",
  * "responseState": "NOT_SENT",
  * "rows": [
    * {
      * "backOrderQuantity": 0,
      * "costCenterCode": "string",
      * "currencyCode": "str",
      * "id": "497f6eca-6276-4993-bfeb-53cbbbba6f08",
      * "isStockItem": true,
      * "itemDescription": "string",
      * "itemId": "string",
      * "itemUnit": "string",
      * "notes": [
        * {
          * "note": "string",
          * "purchaseOrderId": 0,
          * "purchaseOrderRowId": "ba867b0e-f326-42c4-9f43-58bde9b319da",
          * "rowNum": 0
}
],
      * "orderedQuantity": 0,
      * "price": 0,
      * "projectId": "string",
      * "purchaseOrderId": 0,
      * "receivedQuantity": 0,
      * "remainingOrderedQuantity": 0,
      * "rowNum": 0,
      * "stockLocationCode": "string",
      * "stockLocationId": "c039ed46-ada4-4486-8700-89747e000395",
      * "stockLocationName": "string",
      * "stockPointCode": "string",
      * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c",
      * "stockPointName": "string"
}
],
  * "stockPointCode": "string",
  * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c",
  * "supplier": "string",
  * "supplierAddress": "string",
  * "supplierAddress2": "string",
  * "supplierCity": "string",
  * "supplierCountryCode": "str",
  * "supplierEmail": "string",
  * "supplierName": "string",
  * "supplierNumber": "string",
  * "supplierPostCode": "string",
  * "totalReceivedQuantity": 0,
  * "translatedResponseState": "string",
  * "voided": true,
  * "yourReference": "string"

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_PurchaseOrder/operation/sendPurchaseOrder)Send purchase order via email 
Sends the purchase order with the specified `id` to the recipient and sets the purchase order state to SENT
##### path Parameters
idrequired| integer <int64> Purchase order id.  
---|---  
##### Request Body schema: */*
see `PurchaseOrderMailSettings`
bodyrequired| string  
---|---  
bodyAsHtml| string  
receiverrequired| string  
receiverCopy| string  
receiverSecretCopy| string  
replyTorequired| string  
senderName| string  
subjectrequired| string  
### Responses
**204**
Successfully created a new resource.
**default**
WebException
post/api/warehouse/purchaseorders-v1/{id}/send
Default server
https://api.fortnox.se/api/warehouse/purchaseorders-v1/{id}/send
###  Response samples 
  * default


Content type
application/json
Copy
`{
  * "error": "string",
  * "id": "string",
  * "message": "string"

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_PurchaseOrder/operation/voidDocument_5)Void Purchase Order 
##### path Parameters
idrequired| integer <int64> Purchase order id.  
---|---  
### Responses
**204**
Successfully updated the specified resource.
**default**
WebException
put/api/warehouse/purchaseorders-v1/{id}/void
Default server
https://api.fortnox.se/api/warehouse/purchaseorders-v1/{id}/void
###  Response samples 
  * default


Content type
application/json
Copy
`{
  * "error": "string",
  * "id": "string",
  * "message": "string"

}`
# [](https://api.fortnox.se/apidocs#tag/warehouse_StockPoint)Stock Point
Resource to handle `StockPoint`s.
## [](https://api.fortnox.se/apidocs#tag/warehouse_StockPoint/operation/getAll_2)List stock points 
List stock points, optionally include a query parameter `q` to filter on stock point code or name. 
Use query param `state` to filter on ACTIVE, INACTIVE or ALL (default is to include only ACTIVE stock points). 
Stock locations are NOT included in the response.
##### query Parameters
q| string filters on stock point code or name.  
---|---  
state| string Enum: "ALL" "ACTIVE" "INACTIVE" filter on stock point state  
### Responses
**200**
A list of `StockPoints`.
**default**
WebException
get/api/warehouse/stockpoints-v1
Default server
https://api.fortnox.se/api/warehouse/stockpoints-v1
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "active": true,
  * "code": "string",
  * "deliveryAddress": "string",
  * "deliveryAddress2": "string",
  * "deliveryCity": "string",
  * "deliveryCountryCode": "str",
  * "deliveryName": "string",
  * "deliveryPhone": "string",
  * "deliveryZipCode": "string",
  * "id": "497f6eca-6276-4993-bfeb-53cbbbba6f08",
  * "name": "string",
  * "stockLocations": [
    * {
      * "code": "string",
      * "id": "497f6eca-6276-4993-bfeb-53cbbbba6f08",
      * "name": "string",
      * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c"
}
],
  * "usingCompanyAddress": true

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_StockPoint/operation/create_3)Create stock point 
Both `code` and `name` are mandatory. 
If you want to set a custom delivery address for this stock point, you must remember to set `usingCompanyAddress` to `false`. 
Returns 400 `alreadyexists` if a stock point with same code already exists. 
Returns 400 `duplicatestocklocations` if two or more stock locations have the same code.
##### Request Body schema: application/json
stock point
active| boolean  
---|---  
coderequired| string [ 1 .. 10 ] characters   
deliveryAddress| string <= 50 characters   
deliveryAddress2| string <= 50 characters   
deliveryCity| string <= 50 characters   
deliveryCountryCode| string <= 3 characters   
deliveryName| string <= 50 characters   
deliveryPhone| string <= 50 characters   
deliveryZipCode| string <= 10 characters   
id| string <uuid>  
namerequired| string [ 1 .. 25 ] characters   
stockLocations| Array of objects (warehouse_StockLocation)   
usingCompanyAddress| boolean  
### Responses
**201**
The created `StockPoint`.
**default**
WebException
post/api/warehouse/stockpoints-v1
Default server
https://api.fortnox.se/api/warehouse/stockpoints-v1
###  Request samples 
  * Payload


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "active": true,
  * "code": "string",
  * "deliveryAddress": "string",
  * "deliveryAddress2": "string",
  * "deliveryCity": "string",
  * "deliveryCountryCode": "str",
  * "deliveryName": "string",
  * "deliveryPhone": "string",
  * "deliveryZipCode": "string",
  * "id": "497f6eca-6276-4993-bfeb-53cbbbba6f08",
  * "name": "string",
  * "stockLocations": [
    * {
      * "code": "string",
      * "id": "497f6eca-6276-4993-bfeb-53cbbbba6f08",
      * "name": "string",
      * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c"
}
],
  * "usingCompanyAddress": true

}`
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "active": true,
  * "code": "string",
  * "deliveryAddress": "string",
  * "deliveryAddress2": "string",
  * "deliveryCity": "string",
  * "deliveryCountryCode": "str",
  * "deliveryName": "string",
  * "deliveryPhone": "string",
  * "deliveryZipCode": "string",
  * "id": "497f6eca-6276-4993-bfeb-53cbbbba6f08",
  * "name": "string",
  * "stockLocations": [
    * {
      * "code": "string",
      * "id": "497f6eca-6276-4993-bfeb-53cbbbba6f08",
      * "name": "string",
      * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c"
}
],
  * "usingCompanyAddress": true

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_StockPoint/operation/getMany_3)Get stock points 
Get stock points by IDs. 
Use query param `state` to filter on ACTIVE, INACTIVE or ALL (default is to include ALL stock points). 
Stock locations are NOT included in the response.
##### query Parameters
ids| Array of strings <uuid> [ items <uuid > ] stock point ids (comma separated list of UUIDs)  
---|---  
state| string Enum: "ALL" "ACTIVE" "INACTIVE" filter on `StockPointState`, default is to include ALL stock points.  
### Responses
**200**
A list of `StockPoints`.
**default**
WebException
get/api/warehouse/stockpoints-v1/multi
Default server
https://api.fortnox.se/api/warehouse/stockpoints-v1/multi
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "active": true,
  * "code": "string",
  * "deliveryAddress": "string",
  * "deliveryAddress2": "string",
  * "deliveryCity": "string",
  * "deliveryCountryCode": "str",
  * "deliveryName": "string",
  * "deliveryPhone": "string",
  * "deliveryZipCode": "string",
  * "id": "497f6eca-6276-4993-bfeb-53cbbbba6f08",
  * "name": "string",
  * "stockLocations": [
    * {
      * "code": "string",
      * "id": "497f6eca-6276-4993-bfeb-53cbbbba6f08",
      * "name": "string",
      * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c"
}
],
  * "usingCompanyAddress": true

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_StockPoint/operation/1_delete)Delete stock point 
Note that it is not allowed to delete a stock point that is in use.
##### path Parameters
idrequired| string <uuid> id  
---|---  
### Responses
**200**
The deleted `StockPoint`.
**default**
WebException
delete/api/warehouse/stockpoints-v1/{id}
Default server
https://api.fortnox.se/api/warehouse/stockpoints-v1/{id}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "active": true,
  * "code": "string",
  * "deliveryAddress": "string",
  * "deliveryAddress2": "string",
  * "deliveryCity": "string",
  * "deliveryCountryCode": "str",
  * "deliveryName": "string",
  * "deliveryPhone": "string",
  * "deliveryZipCode": "string",
  * "id": "497f6eca-6276-4993-bfeb-53cbbbba6f08",
  * "name": "string",
  * "stockLocations": [
    * {
      * "code": "string",
      * "id": "497f6eca-6276-4993-bfeb-53cbbbba6f08",
      * "name": "string",
      * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c"
}
],
  * "usingCompanyAddress": true

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_StockPoint/operation/getByAmbiguousId)Get stock point 
Get stock point by id or code.
##### path Parameters
idrequired| string stock point code, or stock point id  
---|---  
### Responses
**200**
stock point
**default**
WebException
get/api/warehouse/stockpoints-v1/{id}
Default server
https://api.fortnox.se/api/warehouse/stockpoints-v1/{id}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "active": true,
  * "code": "string",
  * "deliveryAddress": "string",
  * "deliveryAddress2": "string",
  * "deliveryCity": "string",
  * "deliveryCountryCode": "str",
  * "deliveryName": "string",
  * "deliveryPhone": "string",
  * "deliveryZipCode": "string",
  * "id": "497f6eca-6276-4993-bfeb-53cbbbba6f08",
  * "name": "string",
  * "stockLocations": [
    * {
      * "code": "string",
      * "id": "497f6eca-6276-4993-bfeb-53cbbbba6f08",
      * "name": "string",
      * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c"
}
],
  * "usingCompanyAddress": true

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_StockPoint/operation/appendStockLocations)Append stock locations 
Add new stock locations to specific `StockPoint`. 
If you include an already existing stock location code, it will be ignored.
##### path Parameters
idrequired| string <uuid> stock point id  
---|---  
##### Request Body schema: application/json
A list of `StockLocations` to append.
Array 
coderequired| string [ 1 .. 20 ] characters   
---|---  
id| string <uuid>  
name| string <= 25 characters   
stockPointId| string <uuid>  
### Responses
**201**
A list of appended `StockLocations`.
**default**
WebException
post/api/warehouse/stockpoints-v1/{id}
Default server
https://api.fortnox.se/api/warehouse/stockpoints-v1/{id}
###  Request samples 
  * Payload


Content type
application/json
Copy
Expand all  Collapse all 
`[
  * {
    * "code": "string",
    * "id": "497f6eca-6276-4993-bfeb-53cbbbba6f08",
    * "name": "string",
    * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c"
}

]`
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
`{
  * "code": "string",
  * "id": "497f6eca-6276-4993-bfeb-53cbbbba6f08",
  * "name": "string",
  * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c"

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_StockPoint/operation/update_3)Update stock point 
Remember to supply the complete representation of stock point including stock locations.
##### path Parameters
idrequired| string <uuid> id  
---|---  
##### Request Body schema: application/json
complete representation of stock point including stock locations.
active| boolean  
---|---  
coderequired| string [ 1 .. 10 ] characters   
deliveryAddress| string <= 50 characters   
deliveryAddress2| string <= 50 characters   
deliveryCity| string <= 50 characters   
deliveryCountryCode| string <= 3 characters   
deliveryName| string <= 50 characters   
deliveryPhone| string <= 50 characters   
deliveryZipCode| string <= 10 characters   
id| string <uuid>  
namerequired| string [ 1 .. 25 ] characters   
stockLocations| Array of objects (warehouse_StockLocation)   
usingCompanyAddress| boolean  
### Responses
**200**
The updated `StockPoint`.
**default**
WebException
put/api/warehouse/stockpoints-v1/{id}
Default server
https://api.fortnox.se/api/warehouse/stockpoints-v1/{id}
###  Request samples 
  * Payload


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "active": true,
  * "code": "string",
  * "deliveryAddress": "string",
  * "deliveryAddress2": "string",
  * "deliveryCity": "string",
  * "deliveryCountryCode": "str",
  * "deliveryName": "string",
  * "deliveryPhone": "string",
  * "deliveryZipCode": "string",
  * "id": "497f6eca-6276-4993-bfeb-53cbbbba6f08",
  * "name": "string",
  * "stockLocations": [
    * {
      * "code": "string",
      * "id": "497f6eca-6276-4993-bfeb-53cbbbba6f08",
      * "name": "string",
      * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c"
}
],
  * "usingCompanyAddress": true

}`
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "active": true,
  * "code": "string",
  * "deliveryAddress": "string",
  * "deliveryAddress2": "string",
  * "deliveryCity": "string",
  * "deliveryCountryCode": "str",
  * "deliveryName": "string",
  * "deliveryPhone": "string",
  * "deliveryZipCode": "string",
  * "id": "497f6eca-6276-4993-bfeb-53cbbbba6f08",
  * "name": "string",
  * "stockLocations": [
    * {
      * "code": "string",
      * "id": "497f6eca-6276-4993-bfeb-53cbbbba6f08",
      * "name": "string",
      * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c"
}
],
  * "usingCompanyAddress": true

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_StockPoint/operation/getStockLocationsByAmbiguousId)Get stock locations 
List stock locations for a specific stock point. 
Optionally include a query parameter `q` to filter on stock location code or name.
##### path Parameters
idrequired| string stock point id or code  
---|---  
##### query Parameters
q| string filters on stock location code or name.  
---|---  
### Responses
**200**
A list of`StockLocations`.
**default**
WebException
get/api/warehouse/stockpoints-v1/{id}/stocklocations
Default server
https://api.fortnox.se/api/warehouse/stockpoints-v1/{id}/stocklocations
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
`{
  * "code": "string",
  * "id": "497f6eca-6276-4993-bfeb-53cbbbba6f08",
  * "name": "string",
  * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c"

}`
# [](https://api.fortnox.se/apidocs#tag/warehouse_StockStatus)Stock Status
Handles stock status.
## [](https://api.fortnox.se/apidocs#tag/warehouse_StockStatus/operation/getStockBalance)Get stock balance 
Get stock balance for each stockpoint. 
Returns a list of `itemId`, `stockPointCode`, `availableStock`, `inStock`. 
(The difference between `availableStock` and `inStock` is the reserved amount.)
##### query Parameters
itemIds| Array of strings Optional filter on itemIds (comma-separated)  
---|---  
stockPointCodes| Array of strings Optional filter on stock point codes (comma-separated).  
### Responses
**200**
A list of `StockBalances`.
**default**
WebException
get/api/warehouse/status-v1/stockbalance
Default server
https://api.fortnox.se/api/warehouse/status-v1/stockbalance
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
`{
  * "availableStock": 0,
  * "inStock": 0,
  * "itemId": "string",
  * "stockPointCode": "string"

}`
# [](https://api.fortnox.se/apidocs#tag/warehouse_StockTaking)Stock Taking
Handles stock taking.
A Stock Taking document is created in state "planning". Rows, containing item-stockpoint-stocklocation combinations to be counted, are added to the Stock Taking document.
When the planning is done, the Stock Taking document is updated to state "started", and the stock taking begins.
Setting the stock taken quantity is done by updating the Stock Taking document, and supplying the counted rows. This can be done in "batches", i.e. not all rows needs to be updated at once.
When the stock taking is done, the document is released. The release process will adjust the stock for the stock taking date, and prepare the warehouse bookkeeping data.
## [](https://api.fortnox.se/apidocs#tag/warehouse_StockTaking/operation/getAll_1)List stock takings 
Sortable fields: `id`, `name`, `date`, `responsible`, `state`
##### query Parameters
state| string Enum: "all" "planning" "started" "completed" "voided" Include only stock takings with the given state.  
---|---  
itemId| string Include only stock takings with the given item.  
### Responses
**200**
A list of `StockTakings`.
**default**
WebException
get/api/warehouse/stocktaking-v1
Default server
https://api.fortnox.se/api/warehouse/stocktaking-v1
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "costCenterCode": "string",
  * "date": "2019-08-24",
  * "id": 0,
  * "name": "string",
  * "projectId": "string",
  * "responsible": "string",
  * "rows": [
    * {
      * "countedBy": "string",
      * "currentRowNo": 0,
      * "hasPostReleaseStockChanges": true,
      * "id": "string",
      * "itemId": "string",
      * "stockLocationId": "c039ed46-ada4-4486-8700-89747e000395",
      * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c",
      * "stockTakenQuantity": 0,
      * "stockTakingId": 0,
      * "stockTakingRowId": "string",
      * "totalQuantityInStock": 0
}
],
  * "sortParams": {
    * "primarySort": "string",
    * "primarySortOrder": "string",
    * "secondarySort": "string",
    * "secondarySortOrder": "string"
},
  * "sortingId": 0,
  * "state": "planning|started|completed|voided",
  * "usingStockPoints": true

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_StockTaking/operation/create_2)Create stock taking 
Create a new Stock Taking document. The only mandatory fields are `name` and `responsible`. `state` will be set to `planning` for a newly created document. 
The `date`-field is not mandatory for documents in state `planning`. However, when you update the state to `started` you have to provide a date. 
`name` is a descriptive name of the stock taking.
`responsible` is the name of the responsible for the stock taking.
`rows` are added after creation by using the addRows-method.
`projectId` and `costCenterCode` are used for book-keeping, when the Stock Taking document is released. 
The field `usingStockPoints` is set from Warehouse system settings upon creation. If multiple stockpoints is used, then the rows will be per item-stockPoint-stockLocation. If multiple stockpoints is NOT used, then the rows will be per item-stockLocation.
##### Request Body schema: */*
stock taking
costCenterCode| string  
---|---  
date| string <date>  
id| integer <int64>  
namerequired| string [ 1 .. 50 ] characters   
projectId| string  
responsiblerequired| string [ 1 .. 50 ] characters   
rows| Array of objects (warehouse_StockTakingRow)   
sortParams| object (warehouse_StockTakingSortParams)   
sortingId| integer <int32>  
staterequired| stringplanning|started|completed|voided  
usingStockPoints| boolean  
### Responses
**201**
the created stock taking
**default**
WebException
post/api/warehouse/stocktaking-v1
Default server
https://api.fortnox.se/api/warehouse/stocktaking-v1
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "costCenterCode": "string",
  * "date": "2019-08-24",
  * "id": 0,
  * "name": "string",
  * "projectId": "string",
  * "responsible": "string",
  * "rows": [
    * {
      * "countedBy": "string",
      * "currentRowNo": 0,
      * "hasPostReleaseStockChanges": true,
      * "id": "string",
      * "itemId": "string",
      * "stockLocationId": "c039ed46-ada4-4486-8700-89747e000395",
      * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c",
      * "stockTakenQuantity": 0,
      * "stockTakingId": 0,
      * "stockTakingRowId": "string",
      * "totalQuantityInStock": 0
}
],
  * "sortParams": {
    * "primarySort": "string",
    * "primarySortOrder": "string",
    * "secondarySort": "string",
    * "secondarySortOrder": "string"
},
  * "sortingId": 0,
  * "state": "planning|started|completed|voided",
  * "usingStockPoints": true

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_StockTaking/operation/deleteStockTaking)Delete Stock Taking document 
Permanently deletes a Stock Taking document and its rows. 
Only for documents in state `planning` and `started`.
##### path Parameters
idrequired| integer <int64> Stock Taking document id.  
---|---  
### Responses
**204**
Successfully removed the specified resource.
**default**
WebException
delete/api/warehouse/stocktaking-v1/{id}
Default server
https://api.fortnox.se/api/warehouse/stocktaking-v1/{id}
###  Response samples 
  * default


Content type
application/json
Copy
`{
  * "error": "string",
  * "id": "string",
  * "message": "string"

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_StockTaking/operation/1_get_2)Get Stock Taking document 
##### path Parameters
idrequired| integer <int64> Stock Taking document id.  
---|---  
### Responses
**200**
The `StockTaking` document.
**default**
WebException
get/api/warehouse/stocktaking-v1/{id}
Default server
https://api.fortnox.se/api/warehouse/stocktaking-v1/{id}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "costCenterCode": "string",
  * "date": "2019-08-24",
  * "id": 0,
  * "name": "string",
  * "projectId": "string",
  * "responsible": "string",
  * "rows": [
    * {
      * "countedBy": "string",
      * "currentRowNo": 0,
      * "hasPostReleaseStockChanges": true,
      * "id": "string",
      * "itemId": "string",
      * "stockLocationId": "c039ed46-ada4-4486-8700-89747e000395",
      * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c",
      * "stockTakenQuantity": 0,
      * "stockTakingId": 0,
      * "stockTakingRowId": "string",
      * "totalQuantityInStock": 0
}
],
  * "sortParams": {
    * "primarySort": "string",
    * "primarySortOrder": "string",
    * "secondarySort": "string",
    * "secondarySortOrder": "string"
},
  * "sortingId": 0,
  * "state": "planning|started|completed|voided",
  * "usingStockPoints": true

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_StockTaking/operation/1_update_2)Update a stock taking 
Updates can only be done when state is `planning` or `started`. 
All updatable fields (`date`, `name`, `responsible`, `state`, `sortingId`, `costCenterCode`, `projectId`) in the document head are set to supplied values. 
You cannot set `state` to `completed` or `voided`. Use endpoints release or void for this. 
The `date`-field is mandatory for documents in state `started`. 
When state is `started` you use this endpoint for setting the stock taken quantity. Only existing rows can be updated - no new rows will be created (use the addRows endpoint for this). Only the supplied rows will be updated. I.e. you don't have to send in **all** document rows - just supply the rows you want to set stockTakenQuantity for. Just make sure to always include all the fields from the document head as mentioned above. 
The mandatory fields on the (optionally supplied) rows are: `itemId`, `stockPointId`, `stockLocationId`. Fields `countedBy` and `stockTakenQuantity` are technically not mandatory, but will be set to null if you don't supply them.
##### path Parameters
idrequired| integer <int64> Stock Taking document id.  
---|---  
##### Request Body schema: */*
stock taking
costCenterCode| string  
---|---  
date| string <date>  
id| integer <int64>  
namerequired| string [ 1 .. 50 ] characters   
projectId| string  
responsiblerequired| string [ 1 .. 50 ] characters   
rows| Array of objects (warehouse_StockTakingRow)   
sortParams| object (warehouse_StockTakingSortParams)   
sortingId| integer <int32>  
staterequired| stringplanning|started|completed|voided  
usingStockPoints| boolean  
### Responses
**200**
The `StockTaking` document.
**default**
WebException
put/api/warehouse/stocktaking-v1/{id}
Default server
https://api.fortnox.se/api/warehouse/stocktaking-v1/{id}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "costCenterCode": "string",
  * "date": "2019-08-24",
  * "id": 0,
  * "name": "string",
  * "projectId": "string",
  * "responsible": "string",
  * "rows": [
    * {
      * "countedBy": "string",
      * "currentRowNo": 0,
      * "hasPostReleaseStockChanges": true,
      * "id": "string",
      * "itemId": "string",
      * "stockLocationId": "c039ed46-ada4-4486-8700-89747e000395",
      * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c",
      * "stockTakenQuantity": 0,
      * "stockTakingId": 0,
      * "stockTakingRowId": "string",
      * "totalQuantityInStock": 0
}
],
  * "sortParams": {
    * "primarySort": "string",
    * "primarySortOrder": "string",
    * "secondarySort": "string",
    * "secondarySortOrder": "string"
},
  * "sortingId": 0,
  * "state": "planning|started|completed|voided",
  * "usingStockPoints": true

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_StockTaking/operation/addStockTakingRowsByFilter)Add rows by filter 
Add all matching candidate rows to a stock taking, as specified by filters.
##### path Parameters
idrequired| integer <int64> Stock Taking document id.  
---|---  
##### query Parameters
itemIds| Array of strings  
---|---  
supplierNumbers| Array of strings  
stockPointIds| Array of strings  
stockLocationIds| Array of strings  
transactionDate| string <date>  
itemIdSearch| string  
itemDescriptionSearch| string  
excludeZeroBalanceItems| boolean  
excludeNonInboundItems| boolean  
### Responses
**201**
Number of added rows.
**default**
WebException
post/api/warehouse/stocktaking-v1/{id}/addrows
Default server
https://api.fortnox.se/api/warehouse/stocktaking-v1/{id}/addrows
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
0
`0`
## [](https://api.fortnox.se/apidocs#tag/warehouse_StockTaking/operation/getCandidateRows)Get candidate rows 
A candidate row is a combination of itemId, stockPointId and stockLocationId that can be added to the Stock Taking document. 
Rows already added to the Stock Taking are excluded from this list.
##### path Parameters
idrequired| integer <int64> Stock Taking document id.  
---|---  
##### query Parameters
itemIds| Array of strings  
---|---  
supplierNumbers| Array of strings  
stockPointIds| Array of strings  
stockLocationIds| Array of strings  
transactionDate| string <date>  
itemIdSearch| string  
itemDescriptionSearch| string  
excludeZeroBalanceItems| boolean  
includeNonInboundItems| boolean Include items that do not exist on inbound deliveries.  
### Responses
**200**
A list of `StockTakingRows`.
**default**
WebException
get/api/warehouse/stocktaking-v1/{id}/candidates
Default server
https://api.fortnox.se/api/warehouse/stocktaking-v1/{id}/candidates
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
`{
  * "countedBy": "string",
  * "currentRowNo": 0,
  * "hasPostReleaseStockChanges": true,
  * "id": "string",
  * "itemId": "string",
  * "stockLocationId": "c039ed46-ada4-4486-8700-89747e000395",
  * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c",
  * "stockTakenQuantity": 0,
  * "stockTakingId": 0,
  * "stockTakingRowId": "string",
  * "totalQuantityInStock": 0

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_StockTaking/operation/release_2)Release Stock Taking document 
The document will be locked and bookkept. The Stock Taking document state will be set to `completed`. The stock amount will be adjusted according to the stock taken quantity.
##### path Parameters
idrequired| integer <int64> Stock Taking document id.  
---|---  
### Responses
**204**
Successfully updated the specified resource.
**default**
WebException
put/api/warehouse/stocktaking-v1/{id}/release
Default server
https://api.fortnox.se/api/warehouse/stocktaking-v1/{id}/release
###  Response samples 
  * default


Content type
application/json
Copy
`{
  * "error": "string",
  * "id": "string",
  * "message": "string"

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_StockTaking/operation/deleteStockTakingRowByFilter)Delete rows by filter 
Remove all rows matching the filter parameters from the Stock Taking document.
##### path Parameters
idrequired| integer <int64> Stock Taking document id.  
---|---  
##### query Parameters
itemIds| Array of strings  
---|---  
supplierNumbers| Array of strings  
stockPointIds| Array of strings  
stockLocationIds| Array of strings  
transactionDate| string <date>  
itemIdSearch| string  
itemDescriptionSearch| string  
excludeZeroBalanceItems| boolean  
### Responses
**200**
number of deleted rows
**default**
WebException
delete/api/warehouse/stocktaking-v1/{id}/rows
Default server
https://api.fortnox.se/api/warehouse/stocktaking-v1/{id}/rows
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
0
`0`
## [](https://api.fortnox.se/apidocs#tag/warehouse_StockTaking/operation/getRows)Get Stock Taking Rows 
##### path Parameters
idrequired| integer <int64> Stock Taking document id.  
---|---  
##### query Parameters
itemIds| Array of strings  
---|---  
supplierNumbers| Array of strings  
stockPointIds| Array of strings  
stockLocationIds| Array of strings  
transactionDate| string <date>  
itemIdSearch| string  
itemDescriptionSearch| string  
excludeZeroBalanceItems| boolean  
secondarysortby| string Secondary sorting column  
secondaryorder| string Secondary sorting order  
stateFilter| string Enum: "all" "notStockTaken" "stockTakenNoDeviation" "stockTakenWithDeviation"  
startingRowNo| integer <int32> the row number to start the search from, used with startingItemId to jump to specific rows, can be empty  
startingItemId| string the itemId that should be on top of the rows list (used to jump to specific row), can be empty  
### Responses
**200**
A list of `StockTakingRows`.
**default**
WebException
get/api/warehouse/stocktaking-v1/{id}/rows
Default server
https://api.fortnox.se/api/warehouse/stocktaking-v1/{id}/rows
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
`{
  * "countedBy": "string",
  * "currentRowNo": 0,
  * "hasPostReleaseStockChanges": true,
  * "id": "string",
  * "itemId": "string",
  * "stockLocationId": "c039ed46-ada4-4486-8700-89747e000395",
  * "stockPointId": "7dcf5601-6c82-49ce-8b36-2dd2c353c71c",
  * "stockTakenQuantity": 0,
  * "stockTakingId": 0,
  * "stockTakingRowId": "string",
  * "totalQuantityInStock": 0

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_StockTaking/operation/addStockTakingRows)Add rows 
Add rows to a stock taking. If you add an already existing row noting happens.
##### path Parameters
idrequired| integer <int64> Stock Taking document id.  
---|---  
##### Request Body schema: */*
A list of `StockTakingRows`.
Array 
countedBy| string <= 100 characters   
---|---  
currentRowNo| integer <int32>  
hasPostReleaseStockChanges| boolean  
id| string  
itemId| string <= 50 characters   
stockLocationId| string <uuid>  
stockPointId| string <uuid>  
stockTakenQuantity| number  
stockTakingId| integer <int64>  
stockTakingRowId| string  
totalQuantityInStock| number  
### Responses
**204**
Successfully created a new resource.
**default**
WebException
post/api/warehouse/stocktaking-v1/{id}/rows
Default server
https://api.fortnox.se/api/warehouse/stocktaking-v1/{id}/rows
###  Response samples 
  * default


Content type
application/json
Copy
`{
  * "error": "string",
  * "id": "string",
  * "message": "string"

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_StockTaking/operation/deleteStockTakingRow)Delete row 
Remove single row by id from the Stock Taking document.
##### path Parameters
idrequired| integer <int64> Stock Taking document id.  
---|---  
rowIdrequired| string row id  
### Responses
**200**
Number of deleted rows (1)
**default**
WebException
delete/api/warehouse/stocktaking-v1/{id}/rows/{rowId}
Default server
https://api.fortnox.se/api/warehouse/stocktaking-v1/{id}/rows/{rowId}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
0
`0`
## [](https://api.fortnox.se/apidocs#tag/warehouse_StockTaking/operation/voidStockTaking)Void Stock Taking document 
Sets the Stock Taking document state to `voided`. 
Only documents in state `planning` and `started` can be voided. A `completed` document may not be voided.
##### path Parameters
idrequired| integer <int64> Stock Taking document id.  
---|---  
### Responses
**204**
Successfully updated the specified resource.
**default**
WebException
put/api/warehouse/stocktaking-v1/{id}/void
Default server
https://api.fortnox.se/api/warehouse/stocktaking-v1/{id}/void
###  Response samples 
  * default


Content type
application/json
Copy
`{
  * "error": "string",
  * "id": "string",
  * "message": "string"

}`
# [](https://api.fortnox.se/apidocs#tag/warehouse_StockTransfer)Stock Transfer
Handles `StockTransferDocument`s. 
A Stock Transfer moves stock from one location to another. You request a quantity to be moved. The quantity is reserved, and delivered upon release of the Stock Transfer document. The "delivery" makes an inbound delivery to the new location.
## [](https://api.fortnox.se/apidocs#tag/warehouse_StockTransfer/operation/create_5)Create a stock transfer document 
Outbounds will be reserved in the from-place. Inbounds are created upon release of the stock transfer document.
##### Request Body schema: application/json
stock transfer document
id| integer <int64> >= 1   
---|---  
note| string <= 1000 characters   
released| boolean  
rowsrequired| Array of objects (warehouse_StockTransferRow)   
transferDate| string <date>  
version| integer <int64>  
voided| boolean  
### Responses
**201**
The `StockTransferDocument` document.
**default**
WebException
post/api/warehouse/stocktransfer-v1
Default server
https://api.fortnox.se/api/warehouse/stocktransfer-v1
###  Request samples 
  * Payload


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "id": 1,
  * "note": "string",
  * "released": true,
  * "rows": [
    * {
      * "fromStockLocationCode": "string",
      * "fromStockLocationId": "c00aef40-027a-4fa7-b15b-4c621a0c3ac9",
      * "fromStockLocationName": "string",
      * "fromStockPointCode": "string",
      * "fromStockPointId": "be01ff43-f0a0-4da1-a244-ff5f60f64cf2",
      * "fromStockPointName": "string",
      * "itemDescription": "string",
      * "itemId": "string",
      * "itemUnit": "string",
      * "quantity": 0,
      * "requestedQuantity": 0.01,
      * "rowNum": 0,
      * "toStockLocationCode": "string",
      * "toStockLocationId": "366d1d35-777f-4868-8f42-62f0e59d958f",
      * "toStockLocationName": "string",
      * "toStockPointCode": "string",
      * "toStockPointId": "3eb65cd6-b3ed-4dac-87a4-8d2c4ae4bd51",
      * "toStockPointName": "string"
}
],
  * "transferDate": "2019-08-24",
  * "version": 0,
  * "voided": true

}`
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "id": 1,
  * "note": "string",
  * "released": true,
  * "rows": [
    * {
      * "fromStockLocationCode": "string",
      * "fromStockLocationId": "c00aef40-027a-4fa7-b15b-4c621a0c3ac9",
      * "fromStockLocationName": "string",
      * "fromStockPointCode": "string",
      * "fromStockPointId": "be01ff43-f0a0-4da1-a244-ff5f60f64cf2",
      * "fromStockPointName": "string",
      * "itemDescription": "string",
      * "itemId": "string",
      * "itemUnit": "string",
      * "quantity": 0,
      * "requestedQuantity": 0.01,
      * "rowNum": 0,
      * "toStockLocationCode": "string",
      * "toStockLocationId": "366d1d35-777f-4868-8f42-62f0e59d958f",
      * "toStockLocationName": "string",
      * "toStockPointCode": "string",
      * "toStockPointId": "3eb65cd6-b3ed-4dac-87a4-8d2c4ae4bd51",
      * "toStockPointName": "string"
}
],
  * "transferDate": "2019-08-24",
  * "version": 0,
  * "voided": true

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_StockTransfer/operation/1_get_4)Get stock transfer document 
##### path Parameters
idrequired| integer <int64> Stock Transfer document id.  
---|---  
### Responses
**200**
The `StockTransferDocument` document.
**default**
WebException
get/api/warehouse/stocktransfer-v1/{id}
Default server
https://api.fortnox.se/api/warehouse/stocktransfer-v1/{id}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "id": 1,
  * "note": "string",
  * "released": true,
  * "rows": [
    * {
      * "fromStockLocationCode": "string",
      * "fromStockLocationId": "c00aef40-027a-4fa7-b15b-4c621a0c3ac9",
      * "fromStockLocationName": "string",
      * "fromStockPointCode": "string",
      * "fromStockPointId": "be01ff43-f0a0-4da1-a244-ff5f60f64cf2",
      * "fromStockPointName": "string",
      * "itemDescription": "string",
      * "itemId": "string",
      * "itemUnit": "string",
      * "quantity": 0,
      * "requestedQuantity": 0.01,
      * "rowNum": 0,
      * "toStockLocationCode": "string",
      * "toStockLocationId": "366d1d35-777f-4868-8f42-62f0e59d958f",
      * "toStockLocationName": "string",
      * "toStockPointCode": "string",
      * "toStockPointId": "3eb65cd6-b3ed-4dac-87a4-8d2c4ae4bd51",
      * "toStockPointName": "string"
}
],
  * "transferDate": "2019-08-24",
  * "version": 0,
  * "voided": true

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_StockTransfer/operation/update_4)Update a stock transfer document 
##### path Parameters
idrequired| integer <int64> Stock Transfer document id.  
---|---  
##### Request Body schema: application/json
The `StockTransferDocument` document.
id| integer <int64> >= 1   
---|---  
note| string <= 1000 characters   
released| boolean  
rowsrequired| Array of objects (warehouse_StockTransferRow)   
transferDate| string <date>  
version| integer <int64>  
voided| boolean  
### Responses
**200**
The `StockTransferDocument` document.
**default**
WebException
put/api/warehouse/stocktransfer-v1/{id}
Default server
https://api.fortnox.se/api/warehouse/stocktransfer-v1/{id}
###  Request samples 
  * Payload


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "id": 1,
  * "note": "string",
  * "released": true,
  * "rows": [
    * {
      * "fromStockLocationCode": "string",
      * "fromStockLocationId": "c00aef40-027a-4fa7-b15b-4c621a0c3ac9",
      * "fromStockLocationName": "string",
      * "fromStockPointCode": "string",
      * "fromStockPointId": "be01ff43-f0a0-4da1-a244-ff5f60f64cf2",
      * "fromStockPointName": "string",
      * "itemDescription": "string",
      * "itemId": "string",
      * "itemUnit": "string",
      * "quantity": 0,
      * "requestedQuantity": 0.01,
      * "rowNum": 0,
      * "toStockLocationCode": "string",
      * "toStockLocationId": "366d1d35-777f-4868-8f42-62f0e59d958f",
      * "toStockLocationName": "string",
      * "toStockPointCode": "string",
      * "toStockPointId": "3eb65cd6-b3ed-4dac-87a4-8d2c4ae4bd51",
      * "toStockPointName": "string"
}
],
  * "transferDate": "2019-08-24",
  * "version": 0,
  * "voided": true

}`
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "id": 1,
  * "note": "string",
  * "released": true,
  * "rows": [
    * {
      * "fromStockLocationCode": "string",
      * "fromStockLocationId": "c00aef40-027a-4fa7-b15b-4c621a0c3ac9",
      * "fromStockLocationName": "string",
      * "fromStockPointCode": "string",
      * "fromStockPointId": "be01ff43-f0a0-4da1-a244-ff5f60f64cf2",
      * "fromStockPointName": "string",
      * "itemDescription": "string",
      * "itemId": "string",
      * "itemUnit": "string",
      * "quantity": 0,
      * "requestedQuantity": 0.01,
      * "rowNum": 0,
      * "toStockLocationCode": "string",
      * "toStockLocationId": "366d1d35-777f-4868-8f42-62f0e59d958f",
      * "toStockLocationName": "string",
      * "toStockPointCode": "string",
      * "toStockPointId": "3eb65cd6-b3ed-4dac-87a4-8d2c4ae4bd51",
      * "toStockPointName": "string"
}
],
  * "transferDate": "2019-08-24",
  * "version": 0,
  * "voided": true

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_StockTransfer/operation/release_3)Release a stock transfer document 
This will deliver all outbounds which are reserved in from-place, and create inbounds in the to-place. Nothing happens if you releasr an already released stock transfer document. 
Returns `document_is_voided` if document is voided.
##### path Parameters
idrequired| integer <int64> Stock Transfer document id.  
---|---  
### Responses
**204**
Successfully updated the specified resource.
**default**
WebException
put/api/warehouse/stocktransfer-v1/{id}/release
Default server
https://api.fortnox.se/api/warehouse/stocktransfer-v1/{id}/release
###  Response samples 
  * default


Content type
application/json
Copy
`{
  * "error": "string",
  * "id": "string",
  * "message": "string"

}`
## [](https://api.fortnox.se/apidocs#tag/warehouse_StockTransfer/operation/voidStockTransfer)Void a stock transfer document 
Voiding a released stock transfer document is not allowed, and will return `cannot_modify_released_document`
##### path Parameters
idrequired| integer <int64> Stock Transfer document id.  
---|---  
##### query Parameters
force| boolean  
---|---  
### Responses
**204**
Successfully updated the specified resource.
**default**
WebException
put/api/warehouse/stocktransfer-v1/{id}/void
Default server
https://api.fortnox.se/api/warehouse/stocktransfer-v1/{id}/void
###  Response samples 
  * default


Content type
application/json
Copy
`{
  * "error": "string",
  * "id": "string",
  * "message": "string"

}`
# [](https://api.fortnox.se/apidocs#tag/warehouse_Tenant)Tenant
Return Warehouse activation status for a tenant.
## [](https://api.fortnox.se/apidocs#tag/warehouse_Tenant/operation/getTenant)Get Warehouse activation status 
Check if current tenant has activated Fortnox Warehouse.
### Responses
**200**
Warehouse activation status for the current tenant
**default**
WebException
get/api/warehouse/tenants-v4
Default server
https://api.fortnox.se/api/warehouse/tenants-v4
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
`{
  * "activated": true,
  * "tenantId": 0

}`
# [](https://api.fortnox.se/apidocs#tag/time-reporting_Articles)Articles
Provides information on the status (presence of cost/price) of articles
## [](https://api.fortnox.se/apidocs#tag/time-reporting_Articles/operation/list_8)Get full article registrations that match filter 
**Response property descriptions:** **_id_** - The unique id of a basic common combination of article registrations. (The basic common combination means "user/purchase date/customer/project/cost center", which leads to a dialog with several article registrations.) **_purchaseDate_** - The date on which the article is purchased or registered for charging. **_ownerId_** - The user ID who creates the basic common combination. **_version_** - The version of the basic common combination (article dialog) being updated, which is used for handling the concurrency issue. **_registrationType_** - It is always "ARTICLE" for article list endpoint. **Sub-Class - ArticleRegistration:** **_id_** - The unique id of an article registration. **_registrationId_** - The id of the basic common combination. **_orderIndex_** - the order index for the article registration in regard of the common combination. **_ownerId_** - The user ID who owns the article registration. **_totalQuantity_** - The quantity of the article. **_unitPrice_** - The unit price connected to the article registration, which might be locked on an invoice/order basis or for non-invoiceable. **_unitCost_** - The unit cost connected to the article registration, which might be locked on an invoice/order basis. **_invoiceBasisId_** - The ID of invoice/order basis which is used for creating an invoice/order. **_nonInvoiceable_** - If the article registration would be ignored for charging or not. **_note_** - The note on the article registration. **_documentId_** - The document ID which includes the article registration and is created in Invoicing application. **_documentType_** - The document type which could be "invoice" or "order". 
##### query Parameters
fromDate| string <date> The start date of the search span, the max of which should be 1 year to the end date ("toDate"). Example: 2022-11-01  
---|---  
toDate| string <date> The end date of the search span, the max of which should be 1 year back to the start date ("fromDate"). Example: 2022-11-30  
customerIds| Array of strings An array of customer IDs which are being used in database and in one-to-one relation with customer numbers. Example: 100,101,102  
projectIds| Array of strings An array of project IDs. Example: p1,p2,p3  
includeRegistrationsWithoutProject| boolean If the article registration without project is included, or not.  
itemIds| Array of strings An array of article IDs. Example: s1,s2,s3  
costCenterIds| Array of strings An array of cost center IDs. Example: cc1,cc2,cc3  
ownerIds| Array of strings An array of user ids who own the article registrations. Example: 1,2,3  
invoiced| boolean If a document is created with the article registration, or not.  
inInvoiceBasis| boolean If the article registration is locked on an invoice basis, or not.  
internalArticles| boolean If the article registration is internal, which is registered on an internal customer, or not.  
nonInvoiceable| boolean If the article registration has been moved to non-invoiceable, or not.  
includeNonInvoiceablePrice| boolean If the price of the non-invoiceable article registration is included, or not.  
### Responses
**200**
list of article registrations `BaseArticleRegistration`
**default**
WebException
get/api/time/articles-v1
Default server
https://api.fortnox.se/api/time/articles-v1
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`[
  * {
    * "articleRegistrations": [
      * {
        * "createdBy": "string",
        * "createdTime": "2019-08-24T14:15:22Z",
        * "documentId": 0,
        * "documentType": "order",
        * "id": "497f6eca-6276-4993-bfeb-53cbbbba6f08",
        * "invoiceBasisId": 0,
        * "invoiceText": "string",
        * "item": {
          * "active": true,
          * "description": "string",
          * "id": "string",
          * "isStock": true,
          * "purchasePrice": 0,
          * "salesPrices": [
            * {
              * "list": "string",
              * "price": 0
}
],
          * "type": "SERVICE",
          * "unit": "string"
},
        * "nonInvoiceable": true,
        * "note": "string",
        * "orderIndex": 0,
        * "ownerId": "string",
        * "timeLocked": true,
        * "totalQuantity": 0,
        * "unitCost": 0,
        * "unitPrice": 0
}
],
    * "costCenter": {
      * "active": "string",
      * "id": "string",
      * "name": "string"
},
    * "createdTime": "2019-08-24T14:15:22Z",
    * "customer": {
      * "accountManager": "string",
      * "active": true,
      * "defaultProjectId": "string",
      * "deleted": true,
      * "id": "string",
      * "invoiceCity": "string",
      * "invoiceZipCode": "string",
      * "isBusiness": 0,
      * "name": "string",
      * "number": "string",
      * "priceList": "string",
      * "propertyDesignation": "string"
},
    * "id": "497f6eca-6276-4993-bfeb-53cbbbba6f08",
    * "ownerId": "string",
    * "project": {
      * "description": "string",
      * "endDate": "2019-08-24",
      * "id": "string",
      * "invoicedAmount": 0.1,
      * "orderAmount": 0.1,
      * "orderTime": 0.1,
      * "projectLeader": "string",
      * "startDate": "2019-08-24",
      * "status": 0,
      * "totalAmountInInvoices": 0.1
},
    * "purchaseDate": "2019-08-24",
    * "registeredArticle": {
      * "createdBy": "string",
      * "createdTime": "2019-08-24T14:15:22Z",
      * "documentId": 0,
      * "documentType": "order",
      * "id": "497f6eca-6276-4993-bfeb-53cbbbba6f08",
      * "invoiceBasisId": 0,
      * "invoiceText": "string",
      * "item": {
        * "active": true,
        * "description": "string",
        * "id": "string",
        * "isStock": true,
        * "purchasePrice": 0,
        * "salesPrices": [
          * {
            * "list": "string",
            * "price": 0
}
],
        * "type": "SERVICE",
        * "unit": "string"
},
      * "nonInvoiceable": true,
      * "note": "string",
      * "orderIndex": 0,
      * "ownerId": "string",
      * "timeLocked": true,
      * "totalQuantity": 0,
      * "unitCost": 0,
      * "unitPrice": 0
},
    * "registrationType": "WORK",
    * "version": 0
}

]`
# [](https://api.fortnox.se/apidocs#tag/time-reporting_Registrations)Registrations
Register and manage working or absence time
## [](https://api.fortnox.se/apidocs#tag/time-reporting_Registrations/operation/list_2)Get time/absence registrations that match filter 
**Response property descriptions:** **_id_** - The unique id of the registration. **_userId_** - The user ID who owns the registration. **_workedDate_** - The date for which the registration is created. **_workedHours_** - The time spent, or the time of absence. **_startTime_** - The start of clock time. **_stopTime_** - The end of clock time. **_invoiceText_** - The text to be included in the invoice/order basis which would be used to create an invoice/order. **_note_** - The note on the registration. **_chargeHours_** - The time to be invoiced, or 0 for the absence, or locked for non-invoiceable. **_childId_** - The child ID related to the absence registration of parental leave (FPE), which comes from Payroll application. **_nonInvoiceable_** - If the registration would be ignored for charging or not. **_invoiceBasisId_** - The ID of invoice/order basis which is used for creating an invoice/order. **_documentId_** - The document ID which includes the registration and is created in Invoicing application. **_documentType_** - The document type which could be "invoice" or "order". **_unitCost_** - The unit cost from the registration owner who takes the work. **_unitPrice_** - The unit price for the service on the registration, which comes in priority from "invoice/order basis", "price group" or "service". 
##### query Parameters
fromDate| string <date> The start date of the search span, the max of which should be 1 year to the end date ("toDate"). Example: 2022-11-01  
---|---  
toDate| string <date> The end date of the search span, the max of which should be 1 year back to the start date ("fromDate"). Example: 2022-11-30  
customerIds| Array of strings An array of customer IDs which are being used in database and in one-to-one relation with customer numbers. Example: 100,101,102  
projectIds| Array of strings An array of project IDs. Example: p1,p2,p3  
serviceIds| Array of strings An array of service IDs. Example: s1,s2,s3  
costCenterIds| Array of strings An array of cost center IDs. Example: cc1,cc2,cc3  
regCodes| Array of strings An array of registration codes. Example: TID,SEM,FPE  
userIds| Array of strings An array of user IDs that time/absence registrations belong to. Example: 1,2,3  
includeRegistrationsWithoutProject| boolean If the time/absence registration without project is included, or not.  
invoiced| boolean If a document is created with the time/absence registration, or not.  
inInvoiceBasis| boolean If the time/absence registration is locked on an invoice basis, or not.  
internalTime| boolean If the time/absence registration is internal, which is registered on an internal customer, or not.  
nonInvoiceable| boolean If the time/absence registration has been moved to non-invoiceable, or not.  
includeNonInvoiceableChargeHours| boolean If the price of the non-invoiceable time/absence registration is included, or not.  
### Responses
**200**
list of registrations `DetailedRegistration` **Note** : used by mobile client and in detailed chargeable units
**default**
WebException
get/api/time/registrations-v2
Default server
https://api.fortnox.se/api/time/registrations-v2
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`[
  * {
    * "chargeHours": 0.1,
    * "childId": "da54978f-5a21-4efd-948e-3959f61b037a",
    * "costCenter": {
      * "active": "string",
      * "id": "string",
      * "name": "string"
},
    * "createdBy": "string",
    * "createdTime": "2019-08-24T14:15:22Z",
    * "customer": {
      * "accountManager": "string",
      * "active": true,
      * "defaultProjectId": "string",
      * "deleted": true,
      * "id": "string",
      * "invoiceCity": "string",
      * "invoiceZipCode": "string",
      * "isBusiness": 0,
      * "name": "string",
      * "number": "string",
      * "priceList": "string",
      * "propertyDesignation": "string"
},
    * "documentId": 0,
    * "documentType": "order",
    * "id": "497f6eca-6276-4993-bfeb-53cbbbba6f08",
    * "invoiceBasisId": 0,
    * "invoiceText": "string",
    * "nonInvoiceable": true,
    * "note": "string",
    * "project": {
      * "description": "string",
      * "endDate": "2019-08-24",
      * "id": "string",
      * "invoicedAmount": 0.1,
      * "orderAmount": 0.1,
      * "orderTime": 0.1,
      * "projectLeader": "string",
      * "startDate": "2019-08-24",
      * "status": 0,
      * "totalAmountInInvoices": 0.1
},
    * "registrationCode": {
      * "active": true,
      * "code": "str",
      * "costMultiplier": 0.1,
      * "id": "string",
      * "name": "string",
      * "priceMultiplier": 0.1,
      * "type": "WORK"
},
    * "service": {
      * "active": true,
      * "description": "string",
      * "id": "string",
      * "isStock": true,
      * "purchasePrice": 0,
      * "salesPrices": [
        * {
          * "list": "string",
          * "price": 0
}
],
      * "type": "SERVICE",
      * "unit": "string"
},
    * "startTime": "2019-08-24T14:15:22Z",
    * "stopTime": "2019-08-24T14:15:22Z",
    * "unitCost": 0,
    * "unitPrice": 0,
    * "updatedBy": "string",
    * "userId": "string",
    * "workedDate": "2019-08-24",
    * "workedHours": 0.1
}

]`
# [](https://api.fortnox.se/apidocs#tag/fortnox_AbsenceTransactions)Absence Transactions
Absence transactions resources. 
Usable "CauseCodes" **Code**| **Description**  
---|---  
ASK| Arbetsskada  
ATF| Arbetstidsförkortning  
FPE| Föräldraledig  
FRA or FR1| Frånvaro övrigt (FR1 is used in PAXml)  
HAV| Graviditetspenning  
KOM| Kompledig  
MIL| Militärtjänst (max 60 dagar)  
NAR or NÄR| Närståendevård (NÄR is used in PAXml)  
OS1| Sjuk-OB 1  
OS2| Sjuk-OB 2  
OS3| Sjuk-OB 3  
OS4| Sjuk-OB 4  
OS5| Sjuk-OB 5  
PAP| Pappadagar  
PEM| Permission  
PER| Permitterad  
SEM| Semester  
SJK| Sjukfrånvaro  
SMB| Smittbärare  
SVE| Svenska för invandrare  
TJL| Tjänstledig  
UTB or FAC| Facklig utbildning (FAC is used in PAXml)  
VAB| Vård av barn  
## [](https://api.fortnox.se/apidocs#tag/fortnox_AbsenceTransactions/operation/list)Lists all absence transactions 
Supports query-string parameters **employeeid** and **date** for filtering the result.
##### query Parameters
employeeid| string filter by employee id  
---|---  
date| string filter by date  
### Responses
**200**
a list of absence transactions
**default**
Error information if the request did not succeed
get/3/absencetransactions
Default server
https://api.fortnox.se/3/absencetransactions
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "AbsenceTransactions": [
    * {
      * "@url": "string",
      * "CauseCode": "ASK",
      * "CostCenter": "string",
      * "Date": "2019-08-24",
      * "EmployeeId": "string",
      * "Extent": 0.1,
      * "HolidayEntitling": true,
      * "Hours": 0.1,
      * "Project": "string",
      * "id": "497f6eca-6276-4993-bfeb-53cbbbba6f08"
}
]

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_AbsenceTransactions/operation/1_create)Create a new absence transaction 
##### Request Body schema: */*
to create
AbsenceTransaction| object (fortnox_AbsenceTransactionPayload)   
---|---  
### Responses
**201**
the created absence transaction
**default**
Error information if the request did not succeed
post/3/absencetransactions
Default server
https://api.fortnox.se/3/absencetransactions
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "AbsenceTransaction": {
    * "@url": "string",
    * "CauseCode": "ASK",
    * "CostCenter": "string",
    * "Date": "2019-08-24",
    * "EmployeeId": "string",
    * "Extent": 0.1,
    * "HolidayEntitling": true,
    * "Hours": 0.1,
    * "Project": "string",
    * "id": "497f6eca-6276-4993-bfeb-53cbbbba6f08"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_AbsenceTransactions/operation/remove)Delete an absence transaction 
##### path Parameters
idrequired| string <uuid> identifies the transaction  
---|---  
### Responses
**200**
empty
**default**
Error information if the request did not succeed
delete/3/absencetransactions/{id}
Default server
https://api.fortnox.se/3/absencetransactions/{id}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "AbsenceTransaction": {
    * "@url": "string",
    * "CauseCode": "ASK",
    * "CostCenter": "string",
    * "Date": "2019-08-24",
    * "EmployeeId": "string",
    * "Extent": 0.1,
    * "HolidayEntitling": true,
    * "Hours": 0.1,
    * "Project": "string",
    * "id": "497f6eca-6276-4993-bfeb-53cbbbba6f08"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_AbsenceTransactions/operation/get)Retrieve a specific absence transaction 
Retrieves a specific transaction
##### path Parameters
idrequired| string <uuid> identifies the transaction  
---|---  
### Responses
**200**
the absence transaction
**default**
Error information if the request did not succeed
get/3/absencetransactions/{id}
Default server
https://api.fortnox.se/3/absencetransactions/{id}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "AbsenceTransaction": {
    * "@url": "string",
    * "CauseCode": "ASK",
    * "CostCenter": "string",
    * "Date": "2019-08-24",
    * "EmployeeId": "string",
    * "Extent": 0.1,
    * "HolidayEntitling": true,
    * "Hours": 0.1,
    * "Project": "string",
    * "id": "497f6eca-6276-4993-bfeb-53cbbbba6f08"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_AbsenceTransactions/operation/update)Update a single absence transaction 
##### path Parameters
idrequired| string <uuid> identifies the transaction  
---|---  
##### Request Body schema: */*
to update
AbsenceTransaction| object (fortnox_AbsenceTransactionPayload)   
---|---  
### Responses
**200**
the updated absence transaction
**default**
Error information if the request did not succeed
put/3/absencetransactions/{id}
Default server
https://api.fortnox.se/3/absencetransactions/{id}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "AbsenceTransaction": {
    * "@url": "string",
    * "CauseCode": "ASK",
    * "CostCenter": "string",
    * "Date": "2019-08-24",
    * "EmployeeId": "string",
    * "Extent": 0.1,
    * "HolidayEntitling": true,
    * "Hours": 0.1,
    * "Project": "string",
    * "id": "497f6eca-6276-4993-bfeb-53cbbbba6f08"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_AbsenceTransactions/operation/1_get_1)Retrieve absence transactions 
Retrieves a list of absence transactions for an employee on a specific date and cause code.
##### path Parameters
idrequired| string identifies the employee  
---|---  
Daterequired| string <date> of the absence transaction  
Coderequired| string Enum: "ASK" "FPE" "FRA" "HAV" "KOM" "MIL" "NAR" "OS1" "OS2" "OS3" "OS4" "OS5" "PAP" "PEM" "PER" "SEM" "SJK" "SMB" "SVE" "TJL" "UTB" "VAB" status code of the absence transaction  
### Responses
**200**
a list of absence transactions
**default**
Error information if the request did not succeed
get/3/absencetransactions/{id}/{Date}/{Code}
Default server
https://api.fortnox.se/3/absencetransactions/{id}/{Date}/{Code}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "AbsenceTransactions": [
    * {
      * "@url": "string",
      * "CauseCode": "ASK",
      * "CostCenter": "string",
      * "Date": "2019-08-24",
      * "EmployeeId": "string",
      * "Extent": 0.1,
      * "HolidayEntitling": true,
      * "Hours": 0.1,
      * "Project": "string",
      * "id": "497f6eca-6276-4993-bfeb-53cbbbba6f08"
}
]

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_AccountCharts)Account Charts
Account charts resources
## [](https://api.fortnox.se/apidocs#tag/fortnox_AccountCharts/operation/list_1)List all account charts 
Retrieves a list of all the available account charts.
### Responses
**200**
a list of account charts
**default**
Error information if the request did not succeed
get/3/accountcharts
Default server
https://api.fortnox.se/3/accountcharts
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "AccountCharts": [
    * {
      * "Name": "string"
}
]

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_Accounts)Accounts
Accounts resources
## [](https://api.fortnox.se/apidocs#tag/fortnox_Accounts/operation/1_list_2)List all accounts 
The accounts are returned sorted by account number with the lowest number appearing first.
##### query Parameters
lastmodified| string  
---|---  
sru| integer <int32>  
sortby| string Value: "number" field to sort returned list on  
### Responses
**200**
list of accounts
**default**
Error information if the request did not succeed
get/3/accounts
Default server
https://api.fortnox.se/3/accounts
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Accounts": [
    * {
      * "@url": "string",
      * "Active": true,
      * "BalanceBroughtForward": 0.1,
      * "CostCenter": "string",
      * "CostCenterSettings": "ALLOWED",
      * "Description": "string",
      * "Number": 1000,
      * "Project": "string",
      * "ProjectSettings": "ALLOWED",
      * "SRU": 0,
      * "VATCode": "string",
      * "Year": 0
}
]

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Accounts/operation/create_1)Create an account 
The created account will be returned if everything succeeded, if there was any problems an error will be returned.
##### query Parameters
financialyear| integer <int32> financial year to create account against  
---|---  
##### Request Body schema: */*
account to create
Account| object (fortnox_AccountPayload)   
---|---  
### Responses
**201**
the created account
**default**
Error information if the request did not succeed
post/3/accounts
Default server
https://api.fortnox.se/3/accounts
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Account": {
    * "@url": "string",
    * "Active": true,
    * "BalanceBroughtForward": 0.1,
    * "BalanceCarriedForward": 0.1,
    * "CostCenter": "string",
    * "CostCenterSettings": "ALLOWED",
    * "Description": "string",
    * "Number": 1000,
    * "OpeningQuantities": [
      * {
        * "Balance": 0,
        * "Project": "string"
}
],
    * "Project": "string",
    * "ProjectSettings": "ALLOWED",
    * "QuantitySettings": "ALLOWED",
    * "QuantityUnit": "string",
    * "SRU": 0,
    * "TransactionInformation": "string",
    * "TransactionInformationSettings": "ALLOWED",
    * "VATCode": "string",
    * "Year": 0
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Accounts/operation/removeById)Deletes an account 
Deletes the specified account in the users current year
##### path Parameters
Numberrequired| integer <int32> account to delete  
---|---  
### Responses
**204**
Successfully removed the specified resource.
**default**
Error information if the request did not succeed
delete/3/accounts/{Number}
Default server
https://api.fortnox.se/3/accounts/{Number}
###  Response samples 
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ErrorInformation": {
    * "Code": 0,
    * "Error": 0,
    * "Message": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Accounts/operation/get_2)Retrieve an account 
Retrieves the details of an account. You need to supply the unique account number that was returned when the account was created or retrieved from the list of accounts.
##### path Parameters
Numberrequired| integer <int32> identifies the account  
---|---  
### Responses
**200**
the existing account
**default**
Error information if the request did not succeed
get/3/accounts/{Number}
Default server
https://api.fortnox.se/3/accounts/{Number}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Account": {
    * "@url": "string",
    * "Active": true,
    * "BalanceBroughtForward": 0.1,
    * "BalanceCarriedForward": 0.1,
    * "CostCenter": "string",
    * "CostCenterSettings": "ALLOWED",
    * "Description": "string",
    * "Number": 1000,
    * "OpeningQuantities": [
      * {
        * "Balance": 0,
        * "Project": "string"
}
],
    * "Project": "string",
    * "ProjectSettings": "ALLOWED",
    * "QuantitySettings": "ALLOWED",
    * "QuantityUnit": "string",
    * "SRU": 0,
    * "TransactionInformation": "string",
    * "TransactionInformationSettings": "ALLOWED",
    * "VATCode": "string",
    * "Year": 0
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Accounts/operation/update_1)Update an account 
Updates the specified account with the values provided in the properties. Any property not provided will be left unchanged. Note that even though the account number is writeable you can´t change the number of an existing account.
##### path Parameters
Numberrequired| integer <int32> identifies the account  
---|---  
##### query Parameters
financialyear| integer <int32> financial year to update account against  
---|---  
##### Request Body schema: */*
account to update
Account| object (fortnox_AccountPayload)   
---|---  
### Responses
**200**
the updated account
**default**
Error information if the request did not succeed
put/3/accounts/{Number}
Default server
https://api.fortnox.se/3/accounts/{Number}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Account": {
    * "@url": "string",
    * "Active": true,
    * "BalanceBroughtForward": 0.1,
    * "BalanceCarriedForward": 0.1,
    * "CostCenter": "string",
    * "CostCenterSettings": "ALLOWED",
    * "Description": "string",
    * "Number": 1000,
    * "OpeningQuantities": [
      * {
        * "Balance": 0,
        * "Project": "string"
}
],
    * "Project": "string",
    * "ProjectSettings": "ALLOWED",
    * "QuantitySettings": "ALLOWED",
    * "QuantityUnit": "string",
    * "SRU": 0,
    * "TransactionInformation": "string",
    * "TransactionInformationSettings": "ALLOWED",
    * "VATCode": "string",
    * "Year": 0
}

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_Archive)Archive
Archive resources
## [](https://api.fortnox.se/apidocs#tag/fortnox_Archive/operation/removeByPath)Remove files 
Please note that removing a folder will also resulting in removal of all the contents within!
##### query Parameters
path| string identifies file/folder to remove  
---|---  
### Responses
**204**
Successfully removed the specified resource.
**default**
Error information if the request did not succeed
delete/3/archive
Default server
https://api.fortnox.se/3/archive
###  Response samples 
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ErrorInformation": {
    * "Code": 0,
    * "Error": 0,
    * "Message": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Archive/operation/getFolder)Retrieve folder or file 
If no path is provided the root will be returned. Providing fileId will return given file from fileattachments.
##### query Parameters
path| string name of folder  
---|---  
fileid| string fileId from fileattachments  
### Responses
**200**
a single folder
**default**
Error information if the request did not succeed
get/3/archive
Default server
https://api.fortnox.se/3/archive
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Folder": {
    * "@url": "string",
    * "Email": "string",
    * "Files": [
      * {
        * "@url": "string",
        * "ArchiveFileId": "string",
        * "Comments": "string",
        * "Id": "string",
        * "Name": "string",
        * "Path": "string",
        * "Size": 0
}
],
    * "Folders": [
      * {
        * "@url": "string",
        * "Id": "string",
        * "Name": "string"
}
],
    * "Id": "string",
    * "Name": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Archive/operation/uploadFile)Upload a file to a specific subdirectory 
If not path or folderId is provided, the file will be uploaded to the root directory.
##### query Parameters
path| string name of folder  
---|---  
folderid| string id of folder  
##### Request Body schema: multipart/form-data
file| object file to uplad  
---|---  
### Responses
**201**
the uploaded file
**default**
Error information if the request did not succeed
post/3/archive
Default server
https://api.fortnox.se/3/archive
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "File": {
    * "@url": "string",
    * "ArchiveFileId": "string",
    * "Comments": "string",
    * "Id": "string",
    * "Name": "string",
    * "Path": "string",
    * "Size": 0
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Archive/operation/removeById_1)Delete a single file 
##### path Parameters
idrequired| string identifies file/folder to remove  
---|---  
### Responses
**204**
Successfully removed the specified resource.
**default**
Error information if the request did not succeed
delete/3/archive/{id}
Default server
https://api.fortnox.se/3/archive/{id}
###  Response samples 
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ErrorInformation": {
    * "Code": 0,
    * "Error": 0,
    * "Message": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Archive/operation/getFileById)Retrieve a single file 
Providing fileId will return given file from fileattachments.
##### path Parameters
idrequired| string identifies the file  
---|---  
##### query Parameters
fileid| string fileId from fileattachments  
---|---  
### Responses
**200**
a single file
**default**
Error information if the request did not succeed
get/3/archive/{id}
Default server
https://api.fortnox.se/3/archive/{id}
# [](https://api.fortnox.se/apidocs#tag/fortnox_ArticleFileConnections)Article File Connections
Article file connections resources
## [](https://api.fortnox.se/apidocs#tag/fortnox_ArticleFileConnections/operation/list_3)Retrieve a list of article file connections 
The article file connections register can return a list of records or a single record. By specifying a FileId in the URL, a single record will be returned. Not specifying a FileId will return a list of records.
### Responses
**200**
a list of article file connections.
**default**
Error information if the request did not succeed
get/3/articlefileconnections
Default server
https://api.fortnox.se/3/articlefileconnections
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ArticleFileConnections": [
    * {
      * "@url": "string",
      * "ArticleNumber": "string",
      * "FileId": "string"
}
]

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_ArticleFileConnections/operation/1_create_2)Create an article file connection 
##### Request Body schema: */*
to create
ArticleFileConnectionrequired| object (fortnox_ArticleFileConnection)   
---|---  
### Responses
**201**
the created article file connection
**default**
Error information if the request did not succeed
post/3/articlefileconnections
Default server
https://api.fortnox.se/3/articlefileconnections
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ArticleFileConnection": {
    * "@url": "string",
    * "ArticleNumber": "string",
    * "FileId": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_ArticleFileConnections/operation/remove_1)Remove an article file connection 
##### path Parameters
FileIdrequired| string identifies the article file connection  
---|---  
### Responses
**204**
Successfully removed the specified resource.
**default**
Error information if the request did not succeed
delete/3/articlefileconnections/{FileId}
Default server
https://api.fortnox.se/3/articlefileconnections/{FileId}
###  Response samples 
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ErrorInformation": {
    * "Code": 0,
    * "Error": 0,
    * "Message": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_ArticleFileConnections/operation/get_3)Retrieve a single article file connection 
##### path Parameters
FileIdrequired| string identifies the article file connection  
---|---  
### Responses
**200**
the existing article file connection
**default**
Error information if the request did not succeed
get/3/articlefileconnections/{FileId}
Default server
https://api.fortnox.se/3/articlefileconnections/{FileId}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ArticleFileConnection": {
    * "@url": "string",
    * "ArticleNumber": "string",
    * "FileId": "string"
}

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_ArticleUrlConnections)Article Url Connections
Article url connections resources
## [](https://api.fortnox.se/apidocs#tag/fortnox_ArticleUrlConnections/operation/list_6)Retrieve a list of article url connections 
The article url connections register can return a list of records or a single record. By specifying an id in the URL, a single record will be returned. Not specifying an id will return a list of records.
### Responses
**200**
a list of article url connections
**default**
Error information if the request did not succeed
get/3/articleurlconnections
Default server
https://api.fortnox.se/3/articleurlconnections
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ArticleUrlConnections": [
    * {
      * "@url": "string",
      * "ArticleNumber": "string",
      * "Id": 0,
      * "URLConnection": "string"
}
]

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_ArticleUrlConnections/operation/1_create_5)Create an article url connection 
##### Request Body schema: */*
to create
ArticleUrlConnectionrequired| object (fortnox_ArticleUrlConnection)   
---|---  
### Responses
**201**
the created article url connection
**default**
Error information if the request did not succeed
post/3/articleurlconnections
Default server
https://api.fortnox.se/3/articleurlconnections
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ArticleUrlConnection": {
    * "@url": "string",
    * "ArticleNumber": "string",
    * "Id": 0,
    * "URLConnection": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_ArticleUrlConnections/operation/remove_4)Remove an article url connection 
##### path Parameters
idrequired| string identifies the article url connection  
---|---  
### Responses
**204**
Successfully removed the specified resource.
**default**
Error information if the request did not succeed
delete/3/articleurlconnections/{id}
Default server
https://api.fortnox.se/3/articleurlconnections/{id}
###  Response samples 
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ErrorInformation": {
    * "Code": 0,
    * "Error": 0,
    * "Message": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_ArticleUrlConnections/operation/get_6)Retrieve a single article url connection 
##### path Parameters
idrequired| string identifies the article url connection  
---|---  
### Responses
**200**
the existing article url connection
**default**
Error information if the request did not succeed
get/3/articleurlconnections/{id}
Default server
https://api.fortnox.se/3/articleurlconnections/{id}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ArticleUrlConnection": {
    * "@url": "string",
    * "ArticleNumber": "string",
    * "Id": 0,
    * "URLConnection": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_ArticleUrlConnections/operation/1_update_4)Update an article url connection 
##### path Parameters
idrequired| string  
---|---  
##### Request Body schema: */*
to update
ArticleUrlConnectionrequired| object (fortnox_ArticleUrlConnection)   
---|---  
### Responses
**200**
the updated article url connection
**default**
Error information if the request did not succeed
put/3/articleurlconnections/{id}
Default server
https://api.fortnox.se/3/articleurlconnections/{id}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ArticleUrlConnection": {
    * "@url": "string",
    * "ArticleNumber": "string",
    * "Id": 0,
    * "URLConnection": "string"
}

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_Articles)Articles
Articles resources
## [](https://api.fortnox.se/apidocs#tag/fortnox_Articles/operation/list_4)Retrieve a list of articles 
Retrieves a list of articles. The articles are returned sorted by article number with the lowest number appearing first.
##### query Parameters
filter| string Enum: "active" "inactive" possibility to filter supplier invoices  
---|---  
articlenumber| string filter by article number  
description| string filter by description  
ean| string filter by ean  
suppliernumber| string filter by supplier number  
manufacturer| string filter by manufacturer  
manufacturerarticlenumber| string filter by manufacturerarticlenumber  
webshop| string filter by web shop  
lastmodified| string filter by lastmodified  
sortby| string Enum: "articlenumber" "quantityinstock" "reservedquantity" "stockvalue" field to sort returned list  
### Responses
**200**
list of articles
**default**
Error information if the request did not succeed
get/3/articles
Default server
https://api.fortnox.se/3/articles
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Articles": [
    * {
      * "@url": "string",
      * "ArticleNumber": "string",
      * "Description": "string",
      * "DisposableQuantity": "string",
      * "EAN": "string",
      * "Housework": true,
      * "PurchasePrice": "string",
      * "QuantityInStock": 0.1,
      * "ReservedQuantity": "string",
      * "SalesPrice": "string",
      * "StockPlace": "string",
      * "StockValue": "string",
      * "Unit": "string",
      * "VAT": "string",
      * "WebshopArticle": true
}
]

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Articles/operation/1_create_3)Create an article 
The created article will be returned if everything succeeded, if there was any problems an error will be returned.
##### Request Body schema: */*
to create
Article| object (fortnox_Article)   
---|---  
### Responses
**201**
the created article
**default**
Error information if the request did not succeed
post/3/articles
Default server
https://api.fortnox.se/3/articles
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Article": {
    * "@url": "string",
    * "Active": true,
    * "ArticleNumber": "string",
    * "Bulky": true,
    * "ConstructionAccount": 1000,
    * "CostCalculationMethod": "string",
    * "DefaultStockLocation": "string",
    * "DefaultStockPoint": "string",
    * "Depth": 999999999,
    * "Description": "string",
    * "DirectCost": 0.1,
    * "DisposableQuantity": 0.1,
    * "EAN": "string",
    * "EUAccount": 1000,
    * "EUVATAccount": 1000,
    * "Expired": true,
    * "ExportAccount": 1000,
    * "FreightCost": 0.1,
    * "Height": 999999999,
    * "Housework": true,
    * "HouseworkType": "CONSTRUCTION",
    * "Manufacturer": "string",
    * "ManufacturerArticleNumber": "string",
    * "Note": "string",
    * "OtherCost": 0.1,
    * "PurchaseAccount": 1000,
    * "PurchasePrice": 0.1,
    * "QuantityInStock": 0.1,
    * "ReservedQuantity": 0.1,
    * "SalesAccount": 1000,
    * "SalesPrice": 0.1,
    * "StockAccount": 0,
    * "StockChangeAccount": 0,
    * "StockGoods": true,
    * "StockPlace": "string",
    * "StockValue": 0.1,
    * "StockWarning": 0.1,
    * "SupplierName": "string",
    * "SupplierNumber": "string",
    * "Type": "STOCK",
    * "Unit": "string",
    * "VAT": 0.1,
    * "WebshopArticle": true,
    * "Weight": 999999999,
    * "Width": 999999999
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Articles/operation/remove_2)Delete an article 
Deletes the article permanently.
You need to supply the unique article number that was returned when the article was created or retrieved from the list of articles.
##### path Parameters
ArticleNumberrequired| integer <int32> identifies the article  
---|---  
### Responses
**204**
Successfully removed the specified resource.
**default**
Error information if the request did not succeed
delete/3/articles/{ArticleNumber}
Default server
https://api.fortnox.se/3/articles/{ArticleNumber}
###  Response samples 
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ErrorInformation": {
    * "Code": 0,
    * "Error": 0,
    * "Message": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Articles/operation/get_4)Retrieve an article 
Retrieves the details of an article. You need to supply the unique article number that was returned when the article was created or retrieved from the list of articles.
##### path Parameters
ArticleNumberrequired| integer <int32> identifies the article  
---|---  
### Responses
**200**
the existing article
**default**
Error information if the request did not succeed
get/3/articles/{ArticleNumber}
Default server
https://api.fortnox.se/3/articles/{ArticleNumber}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Article": {
    * "@url": "string",
    * "Active": true,
    * "ArticleNumber": "string",
    * "Bulky": true,
    * "ConstructionAccount": 1000,
    * "CostCalculationMethod": "string",
    * "DefaultStockLocation": "string",
    * "DefaultStockPoint": "string",
    * "Depth": 999999999,
    * "Description": "string",
    * "DirectCost": 0.1,
    * "DisposableQuantity": 0.1,
    * "EAN": "string",
    * "EUAccount": 1000,
    * "EUVATAccount": 1000,
    * "Expired": true,
    * "ExportAccount": 1000,
    * "FreightCost": 0.1,
    * "Height": 999999999,
    * "Housework": true,
    * "HouseworkType": "CONSTRUCTION",
    * "Manufacturer": "string",
    * "ManufacturerArticleNumber": "string",
    * "Note": "string",
    * "OtherCost": 0.1,
    * "PurchaseAccount": 1000,
    * "PurchasePrice": 0.1,
    * "QuantityInStock": 0.1,
    * "ReservedQuantity": 0.1,
    * "SalesAccount": 1000,
    * "SalesPrice": 0.1,
    * "StockAccount": 0,
    * "StockChangeAccount": 0,
    * "StockGoods": true,
    * "StockPlace": "string",
    * "StockValue": 0.1,
    * "StockWarning": 0.1,
    * "SupplierName": "string",
    * "SupplierNumber": "string",
    * "Type": "STOCK",
    * "Unit": "string",
    * "VAT": 0.1,
    * "WebshopArticle": true,
    * "Weight": 999999999,
    * "Width": 999999999
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Articles/operation/update_2)Update an article 
Updates the specified article with the values provided in the properties. Any property not provided will be left unchanged. You need to supply the unique article number that was returned when the article was created or retrieved from the list of articles. Note that even though the article number is writeable you can not change the number of an existing article.
##### path Parameters
ArticleNumberrequired| integer <int32> identifies the article  
---|---  
##### Request Body schema: */*
to update
Article| object (fortnox_Article)   
---|---  
### Responses
**200**
the updated article
**default**
Error information if the request did not succeed
put/3/articles/{ArticleNumber}
Default server
https://api.fortnox.se/3/articles/{ArticleNumber}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Article": {
    * "@url": "string",
    * "Active": true,
    * "ArticleNumber": "string",
    * "Bulky": true,
    * "ConstructionAccount": 1000,
    * "CostCalculationMethod": "string",
    * "DefaultStockLocation": "string",
    * "DefaultStockPoint": "string",
    * "Depth": 999999999,
    * "Description": "string",
    * "DirectCost": 0.1,
    * "DisposableQuantity": 0.1,
    * "EAN": "string",
    * "EUAccount": 1000,
    * "EUVATAccount": 1000,
    * "Expired": true,
    * "ExportAccount": 1000,
    * "FreightCost": 0.1,
    * "Height": 999999999,
    * "Housework": true,
    * "HouseworkType": "CONSTRUCTION",
    * "Manufacturer": "string",
    * "ManufacturerArticleNumber": "string",
    * "Note": "string",
    * "OtherCost": 0.1,
    * "PurchaseAccount": 1000,
    * "PurchasePrice": 0.1,
    * "QuantityInStock": 0.1,
    * "ReservedQuantity": 0.1,
    * "SalesAccount": 1000,
    * "SalesPrice": 0.1,
    * "StockAccount": 0,
    * "StockChangeAccount": 0,
    * "StockGoods": true,
    * "StockPlace": "string",
    * "StockValue": 0.1,
    * "StockWarning": 0.1,
    * "SupplierName": "string",
    * "SupplierNumber": "string",
    * "Type": "STOCK",
    * "Unit": "string",
    * "VAT": 0.1,
    * "WebshopArticle": true,
    * "Weight": 999999999,
    * "Width": 999999999
}

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_AssetFileConnection)Asset File Connection
Asset file connections resources
## [](https://api.fortnox.se/apidocs#tag/fortnox_AssetFileConnection/operation/1_getAll)Retrieve a list of asset file connections 
The asset register can return a list of assets or a single asset. By specifying a FileId in the URL, a single asset will be returned. Not specifying a FileId will return a list of records.
### Responses
**200**
list of asset file connections
**default**
Error information if the request did not succeed
get/3/assetfileconnections
Default server
https://api.fortnox.se/3/assetfileconnections
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "AssetFileConnections": [
    * {
      * "@url": "string",
      * "AssetId": "string",
      * "FileId": "string",
      * "Name": "string"
}
],
  * "MetaInformation": {
    * "@CurrentPage": 0,
    * "@TotalPages": 0,
    * "@TotalResources": 0
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_AssetFileConnection/operation/create_6)Create an asset file connection 
##### Request Body schema: */*
asset file connection
AssetId| string  
---|---  
FileId| string  
### Responses
**201**
asset file connection
**default**
Error information if the request did not succeed
post/3/assetfileconnections
Default server
https://api.fortnox.se/3/assetfileconnections
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
`{
  * "@url": "string",
  * "AssetId": "string",
  * "FileId": "string",
  * "Name": "string"

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_AssetFileConnection/operation/delete)Remove an asset file connection 
##### path Parameters
fileIdrequired| string fileId  
---|---  
### Responses
**204**
Successfully removed the specified resource.
**default**
Error information if the request did not succeed
delete/3/assetfileconnections/{fileId}
Default server
https://api.fortnox.se/3/assetfileconnections/{fileId}
###  Response samples 
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ErrorInformation": {
    * "Code": 0,
    * "Error": 0,
    * "Message": "string"
}

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_AssetTypes)Asset Types
Asset types resource
## [](https://api.fortnox.se/apidocs#tag/fortnox_AssetTypes/operation/1_getAll_1)Retrieve a list of asset types 
### Responses
**200**
asset types
**default**
Error information if the request did not succeed
get/3/assets/types
Default server
https://api.fortnox.se/3/assets/types
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "MetaInformation": {
    * "@CurrentPage": 0,
    * "@TotalPages": 0,
    * "@TotalResources": 0
},
  * "Types": [
    * {
      * "@url": "string",
      * "AccountAsset": 0,
      * "AccountAssetId": 0,
      * "AccountDepreciation": 0,
      * "AccountDepreciationId": 0,
      * "AccountRevaluation": 0,
      * "AccountRevaluationId": 0,
      * "AccountSaleLoss": 0,
      * "AccountSaleLossId": 0,
      * "AccountSaleWin": 0,
      * "AccountSaleWinId": 0,
      * "AccountValueLoss": 0,
      * "AccountValueLossId": 0,
      * "AccountWriteDown": 0,
      * "AccountWriteDownAck": 0,
      * "AccountWriteDownAckId": 0,
      * "AccountWriteDownId": 0,
      * "Description": "string",
      * "Id": 0,
      * "InUse": true,
      * "Notes": "string",
      * "Number": "string",
      * "Type": 0
}
]

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_AssetTypes/operation/delete_2)Delete an asset type 
##### path Parameters
idrequired| integer <int32> id  
---|---  
### Responses
**204**
Successfully removed the specified resource.
**default**
Error information if the request did not succeed
delete/3/assets/types/{id}
Default server
https://api.fortnox.se/3/assets/types/{id}
###  Response samples 
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ErrorInformation": {
    * "Code": 0,
    * "Error": 0,
    * "Message": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_AssetTypes/operation/get_8)Retrieve an asset type 
##### path Parameters
idrequired| integer <int32> id  
---|---  
### Responses
**200**
asset type
**default**
Error information if the request did not succeed
get/3/assets/types/{id}
Default server
https://api.fortnox.se/3/assets/types/{id}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Type": {
    * "@url": "string",
    * "AccountAsset": 0,
    * "AccountAssetId": 0,
    * "AccountDepreciation": 0,
    * "AccountDepreciationId": 0,
    * "AccountRevaluation": 0,
    * "AccountRevaluationId": 0,
    * "AccountSaleLoss": 0,
    * "AccountSaleLossId": 0,
    * "AccountSaleWin": 0,
    * "AccountSaleWinId": 0,
    * "AccountValueLoss": 0,
    * "AccountValueLossId": 0,
    * "AccountWriteDown": 0,
    * "AccountWriteDownAck": 0,
    * "AccountWriteDownAckId": 0,
    * "AccountWriteDownId": 0,
    * "Description": "string",
    * "Id": 0,
    * "InUse": true,
    * "Notes": "string",
    * "Number": "string",
    * "Type": 0
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_AssetTypes/operation/create_8)Create an asset type 
##### path Parameters
idrequired| integer <int32> id  
---|---  
##### Request Body schema: */*
request
AssetType| object (fortnox_CreateAsset)   
---|---  
### Responses
**201**
response
**default**
Error information if the request did not succeed
post/3/assets/types/{id}
Default server
https://api.fortnox.se/3/assets/types/{id}
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Type": {
    * "@url": "string",
    * "AccountAsset": 0,
    * "AccountAssetId": 0,
    * "AccountDepreciation": 0,
    * "AccountDepreciationId": 0,
    * "AccountRevaluation": 0,
    * "AccountRevaluationId": 0,
    * "AccountSaleLoss": 0,
    * "AccountSaleLossId": 0,
    * "AccountSaleWin": 0,
    * "AccountSaleWinId": 0,
    * "AccountValueLoss": 0,
    * "AccountValueLossId": 0,
    * "AccountWriteDown": 0,
    * "AccountWriteDownAck": 0,
    * "AccountWriteDownAckId": 0,
    * "AccountWriteDownId": 0,
    * "Description": "string",
    * "Id": 0,
    * "InUse": true,
    * "Notes": "string",
    * "Number": "string",
    * "Type": 0
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_AssetTypes/operation/update_6)Update an asset type 
##### path Parameters
idrequired| integer <int32> id  
---|---  
##### Request Body schema: */*
request
AssetType| object (fortnox_UpdateAsset)   
---|---  
### Responses
**200**
response
**default**
Error information if the request did not succeed
put/3/assets/types/{id}
Default server
https://api.fortnox.se/3/assets/types/{id}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Type": {
    * "@url": "string",
    * "AccountAsset": 0,
    * "AccountAssetId": 0,
    * "AccountDepreciation": 0,
    * "AccountDepreciationId": 0,
    * "AccountRevaluation": 0,
    * "AccountRevaluationId": 0,
    * "AccountSaleLoss": 0,
    * "AccountSaleLossId": 0,
    * "AccountSaleWin": 0,
    * "AccountSaleWinId": 0,
    * "AccountValueLoss": 0,
    * "AccountValueLossId": 0,
    * "AccountWriteDown": 0,
    * "AccountWriteDownAck": 0,
    * "AccountWriteDownAckId": 0,
    * "AccountWriteDownId": 0,
    * "Description": "string",
    * "Id": 0,
    * "InUse": true,
    * "Notes": "string",
    * "Number": "string",
    * "Type": 0
}

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_Assets)Assets
Assets resources 
Possible filters on Assets endpoint **Name** | **Description**  
---|---  
active | Retrieves all active assets  
inactive | Retrieves all inactive assets  
fully_depreciated | Retrieves all fully depreciated assets  
sold | Retrieves all sold assets  
scrapped | Retrieves all scrapped assets  
voided | Retrieves all voided assets  
## [](https://api.fortnox.se/apidocs#tag/fortnox_Assets/operation/list_7)Retrieve a list of assets 
### Responses
**200**
list of assets
**default**
Error information if the request did not succeed
get/3/assets
Default server
https://api.fortnox.se/3/assets
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Assets": [
    * {
      * "@url": "string",
      * "AcquisitionDate": "string",
      * "AcquisitionValue": 0,
      * "DepreciatedTo": "string",
      * "DepreciationFinal": "string",
      * "Description": "string",
      * "Id": 0,
      * "Number": "string",
      * "Status": "string",
      * "StatusId": "string",
      * "Type": "string",
      * "TypeId": 0
}
]

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Assets/operation/create_7)Create an Asset 
The created asset will be returned if everything succeeded, if there was any problems an error will be returned.
##### Request Body schema: */*
asset
AssetType| object (fortnox_CreateAsset)   
---|---  
### Responses
**201**
asset
**default**
Error information if the request did not succeed
post/3/assets
Default server
https://api.fortnox.se/3/assets
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Assets": {
    * "@url": "string",
    * "AcquisitionDate": "string",
    * "AcquisitionStart": "string",
    * "AcquisitionValue": 0,
    * "Brand": "string",
    * "CostCenter": "string",
    * "Department": "string",
    * "DepreciateToResidualValue": 0,
    * "DepreciatedTo": "string",
    * "DepreciationFinal": "string",
    * "DepreciationMethod": 0,
    * "Description": "string",
    * "Group": "string",
    * "History": [
      * {
        * "Amount": "string",
        * "Date": "string",
        * "EventId": 0,
        * "Id": 0,
        * "Notes": "string",
        * "SupplierInvoice": 0,
        * "UserId": 0,
        * "UserName": "string",
        * "VoucherNumber": 0,
        * "VoucherSeries": "string",
        * "VoucherYear": 0
}
],
    * "Id": 0,
    * "InsuredNumber": "string",
    * "InsuredWith": "string",
    * "ManualOb": 0,
    * "Notes": "string",
    * "Number": "string",
    * "Placement": "string",
    * "Project": "string",
    * "Reference": "string",
    * "Room": "string",
    * "Status": "string",
    * "StatusId": "string",
    * "Type": "string",
    * "TypeId": 0
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Assets/operation/changeOb)Change manual OB value of an Asset 
The updated asset will be returned if everything succeeded, if there was any problems an error will be returned.
##### path Parameters
GivenNumberrequired| string Asset number  
---|---  
##### Request Body schema: */*
asset
Amount| integer <int32>  
---|---  
Comment| string  
### Responses
**200**
asset
**default**
Error information if the request did not succeed
put/3/assets/changeob/{GivenNumber}
Default server
https://api.fortnox.se/3/assets/changeob/{GivenNumber}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Assets": {
    * "@url": "string",
    * "AcquisitionDate": "string",
    * "AcquisitionStart": "string",
    * "AcquisitionValue": 0,
    * "Brand": "string",
    * "CostCenter": "string",
    * "Department": "string",
    * "DepreciateToResidualValue": 0,
    * "DepreciatedTo": "string",
    * "DepreciationFinal": "string",
    * "DepreciationMethod": 0,
    * "Description": "string",
    * "Group": "string",
    * "History": [
      * {
        * "Amount": "string",
        * "Date": "string",
        * "EventId": 0,
        * "Id": 0,
        * "Notes": "string",
        * "SupplierInvoice": 0,
        * "UserId": 0,
        * "UserName": "string",
        * "VoucherNumber": 0,
        * "VoucherSeries": "string",
        * "VoucherYear": 0
}
],
    * "Id": 0,
    * "InsuredNumber": "string",
    * "InsuredWith": "string",
    * "ManualOb": 0,
    * "Notes": "string",
    * "Number": "string",
    * "Placement": "string",
    * "Project": "string",
    * "Reference": "string",
    * "Room": "string",
    * "Status": "string",
    * "StatusId": "string",
    * "Type": "string",
    * "TypeId": 0
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Assets/operation/depreciate)Perform a Depreciation of an Asset 
The created vouchers list will be returned if everything succeeded, if there was any problems an error will be returned.
##### Request Body schema: */*
body
Asset| object (fortnox_Depreciation)   
---|---  
### Responses
**201**
response
**default**
Error information if the request did not succeed
post/3/assets/depreciate
Default server
https://api.fortnox.se/3/assets/depreciate
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "AssetsDepreciation": [
    * {
      * "@url": "string",
      * "FinancialYear": 0,
      * "VoucherNumber": 0,
      * "VoucherSeries": "string"
}
]

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Assets/operation/getDeprecationList)Assets depreciation list 
Retrieves a list of assets to depreciate.
##### path Parameters
ToDaterequired| string toDate  
---|---  
### Responses
**200**
list of assets
**default**
Error information if the request did not succeed
get/3/assets/depreciations/{ToDate}
Default server
https://api.fortnox.se/3/assets/depreciations/{ToDate}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Assets": [
    * {
      * "@url": "string",
      * "AcquisitionDate": "string",
      * "AcquisitionValue": 0,
      * "DepreciatedTo": "string",
      * "DepreciationFinal": "string",
      * "Description": "string",
      * "Id": 0,
      * "Number": "string",
      * "Status": "string",
      * "StatusId": "string",
      * "Type": "string",
      * "TypeId": 0
}
]

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Assets/operation/scrap)Scrap an Asset 
The updated asset will be returned if everything succeeded, if there was any problems an error will be returned.
##### path Parameters
GivenNumberrequired| string Asset number  
---|---  
##### Request Body schema: */*
asset
Asset| object (fortnox_Scrap)   
---|---  
### Responses
**200**
asset
**default**
Error information if the request did not succeed
put/3/assets/scrap/{GivenNumber}
Default server
https://api.fortnox.se/3/assets/scrap/{GivenNumber}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Assets": {
    * "@url": "string",
    * "AcquisitionDate": "string",
    * "AcquisitionStart": "string",
    * "AcquisitionValue": 0,
    * "Brand": "string",
    * "CostCenter": "string",
    * "Department": "string",
    * "DepreciateToResidualValue": 0,
    * "DepreciatedTo": "string",
    * "DepreciationFinal": "string",
    * "DepreciationMethod": 0,
    * "Description": "string",
    * "Group": "string",
    * "History": [
      * {
        * "Amount": "string",
        * "Date": "string",
        * "EventId": 0,
        * "Id": 0,
        * "Notes": "string",
        * "SupplierInvoice": 0,
        * "UserId": 0,
        * "UserName": "string",
        * "VoucherNumber": 0,
        * "VoucherSeries": "string",
        * "VoucherYear": 0
}
],
    * "Id": 0,
    * "InsuredNumber": "string",
    * "InsuredWith": "string",
    * "ManualOb": 0,
    * "Notes": "string",
    * "Number": "string",
    * "Placement": "string",
    * "Project": "string",
    * "Reference": "string",
    * "Room": "string",
    * "Status": "string",
    * "StatusId": "string",
    * "Type": "string",
    * "TypeId": 0
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Assets/operation/sell)Sell an Asset 
Partial sell or full sell of an asset.
##### path Parameters
GivenNumberrequired| string Asset number  
---|---  
##### Request Body schema: */*
asset
Asset| object (fortnox_Sell)   
---|---  
### Responses
**200**
asset
**default**
Error information if the request did not succeed
put/3/assets/sell/{GivenNumber}
Default server
https://api.fortnox.se/3/assets/sell/{GivenNumber}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Assets": {
    * "@url": "string",
    * "AcquisitionDate": "string",
    * "AcquisitionStart": "string",
    * "AcquisitionValue": 0,
    * "Brand": "string",
    * "CostCenter": "string",
    * "Department": "string",
    * "DepreciateToResidualValue": 0,
    * "DepreciatedTo": "string",
    * "DepreciationFinal": "string",
    * "DepreciationMethod": 0,
    * "Description": "string",
    * "Group": "string",
    * "History": [
      * {
        * "Amount": "string",
        * "Date": "string",
        * "EventId": 0,
        * "Id": 0,
        * "Notes": "string",
        * "SupplierInvoice": 0,
        * "UserId": 0,
        * "UserName": "string",
        * "VoucherNumber": 0,
        * "VoucherSeries": "string",
        * "VoucherYear": 0
}
],
    * "Id": 0,
    * "InsuredNumber": "string",
    * "InsuredWith": "string",
    * "ManualOb": 0,
    * "Notes": "string",
    * "Number": "string",
    * "Placement": "string",
    * "Project": "string",
    * "Reference": "string",
    * "Room": "string",
    * "Status": "string",
    * "StatusId": "string",
    * "Type": "string",
    * "TypeId": 0
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Assets/operation/writeDown)Write down an Asset 
The updated asset will be returned if everything succeeded, if there was any problems an error will be returned.
##### path Parameters
GivenNumberrequired| string Asset number  
---|---  
##### Request Body schema: */*
asset
Asset| object (fortnox_WriteDown)   
---|---  
### Responses
**200**
asset
**default**
Error information if the request did not succeed
put/3/assets/writedown/{GivenNumber}
Default server
https://api.fortnox.se/3/assets/writedown/{GivenNumber}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Assets": {
    * "@url": "string",
    * "AcquisitionDate": "string",
    * "AcquisitionStart": "string",
    * "AcquisitionValue": 0,
    * "Brand": "string",
    * "CostCenter": "string",
    * "Department": "string",
    * "DepreciateToResidualValue": 0,
    * "DepreciatedTo": "string",
    * "DepreciationFinal": "string",
    * "DepreciationMethod": 0,
    * "Description": "string",
    * "Group": "string",
    * "History": [
      * {
        * "Amount": "string",
        * "Date": "string",
        * "EventId": 0,
        * "Id": 0,
        * "Notes": "string",
        * "SupplierInvoice": 0,
        * "UserId": 0,
        * "UserName": "string",
        * "VoucherNumber": 0,
        * "VoucherSeries": "string",
        * "VoucherYear": 0
}
],
    * "Id": 0,
    * "InsuredNumber": "string",
    * "InsuredWith": "string",
    * "ManualOb": 0,
    * "Notes": "string",
    * "Number": "string",
    * "Placement": "string",
    * "Project": "string",
    * "Reference": "string",
    * "Room": "string",
    * "Status": "string",
    * "StatusId": "string",
    * "Type": "string",
    * "TypeId": 0
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Assets/operation/writeUp)Write up an Asset 
The updated asset will be returned if everything succeeded, if there was any problems an error will be returned.
##### path Parameters
GivenNumberrequired| string Asset number  
---|---  
##### Request Body schema: */*
asset
Asset| object (fortnox_WriteUp)   
---|---  
### Responses
**200**
asset
**default**
Error information if the request did not succeed
put/3/assets/writeup/{GivenNumber}
Default server
https://api.fortnox.se/3/assets/writeup/{GivenNumber}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Assets": {
    * "@url": "string",
    * "AcquisitionDate": "string",
    * "AcquisitionStart": "string",
    * "AcquisitionValue": 0,
    * "Brand": "string",
    * "CostCenter": "string",
    * "Department": "string",
    * "DepreciateToResidualValue": 0,
    * "DepreciatedTo": "string",
    * "DepreciationFinal": "string",
    * "DepreciationMethod": 0,
    * "Description": "string",
    * "Group": "string",
    * "History": [
      * {
        * "Amount": "string",
        * "Date": "string",
        * "EventId": 0,
        * "Id": 0,
        * "Notes": "string",
        * "SupplierInvoice": 0,
        * "UserId": 0,
        * "UserName": "string",
        * "VoucherNumber": 0,
        * "VoucherSeries": "string",
        * "VoucherYear": 0
}
],
    * "Id": 0,
    * "InsuredNumber": "string",
    * "InsuredWith": "string",
    * "ManualOb": 0,
    * "Notes": "string",
    * "Number": "string",
    * "Placement": "string",
    * "Project": "string",
    * "Reference": "string",
    * "Room": "string",
    * "Status": "string",
    * "StatusId": "string",
    * "Type": "string",
    * "TypeId": 0
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Assets/operation/delete_1)Delete or Void an Asset 
By specifying a {GivenNumber} in the URL a single "Not active" asset or asset with a type "Not depreciable" can be deleted. By specifying a {GivenNumber} in the URL a single "Active" or "Fully depreciated" assets can be voided and in this case in request body voiddate should be provided, otherwise it will use todays date.
##### path Parameters
GivenNumberrequired| string Asset number  
---|---  
##### Request Body schema: */*
request
Asset| object (fortnox_Delete)   
---|---  
### Responses
**204**
Successfully removed the specified resource.
**default**
Error information if the request did not succeed
delete/3/assets/{GivenNumber}
Default server
https://api.fortnox.se/3/assets/{GivenNumber}
###  Response samples 
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ErrorInformation": {
    * "Code": 0,
    * "Error": 0,
    * "Message": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Assets/operation/get_7)Retrieve a single asset 
##### path Parameters
GivenNumberrequired| string Asset number  
---|---  
### Responses
**200**
asset
**default**
Error information if the request did not succeed
get/3/assets/{GivenNumber}
Default server
https://api.fortnox.se/3/assets/{GivenNumber}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Assets": {
    * "@url": "string",
    * "AcquisitionDate": "string",
    * "AcquisitionStart": "string",
    * "AcquisitionValue": 0,
    * "Brand": "string",
    * "CostCenter": "string",
    * "Department": "string",
    * "DepreciateToResidualValue": 0,
    * "DepreciatedTo": "string",
    * "DepreciationFinal": "string",
    * "DepreciationMethod": 0,
    * "Description": "string",
    * "Group": "string",
    * "History": [
      * {
        * "Amount": "string",
        * "Date": "string",
        * "EventId": 0,
        * "Id": 0,
        * "Notes": "string",
        * "SupplierInvoice": 0,
        * "UserId": 0,
        * "UserName": "string",
        * "VoucherNumber": 0,
        * "VoucherSeries": "string",
        * "VoucherYear": 0
}
],
    * "Id": 0,
    * "InsuredNumber": "string",
    * "InsuredWith": "string",
    * "ManualOb": 0,
    * "Notes": "string",
    * "Number": "string",
    * "Placement": "string",
    * "Project": "string",
    * "Reference": "string",
    * "Room": "string",
    * "Status": "string",
    * "StatusId": "string",
    * "Type": "string",
    * "TypeId": 0
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Assets/operation/update_5)Update an Asset 
The updated asset will be returned if everything succeeded, if there were any problems an error will be returned.
##### path Parameters
GivenNumberrequired| string Asset number  
---|---  
##### Request Body schema: */*
asset
Asset| object (fortnox_UpdateAsset)   
---|---  
### Responses
**200**
asset
**default**
Error information if the request did not succeed
put/3/assets/{GivenNumber}
Default server
https://api.fortnox.se/3/assets/{GivenNumber}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Assets": {
    * "@url": "string",
    * "AcquisitionDate": "string",
    * "AcquisitionStart": "string",
    * "AcquisitionValue": 0,
    * "Brand": "string",
    * "CostCenter": "string",
    * "Department": "string",
    * "DepreciateToResidualValue": 0,
    * "DepreciatedTo": "string",
    * "DepreciationFinal": "string",
    * "DepreciationMethod": 0,
    * "Description": "string",
    * "Group": "string",
    * "History": [
      * {
        * "Amount": "string",
        * "Date": "string",
        * "EventId": 0,
        * "Id": 0,
        * "Notes": "string",
        * "SupplierInvoice": 0,
        * "UserId": 0,
        * "UserName": "string",
        * "VoucherNumber": 0,
        * "VoucherSeries": "string",
        * "VoucherYear": 0
}
],
    * "Id": 0,
    * "InsuredNumber": "string",
    * "InsuredWith": "string",
    * "ManualOb": 0,
    * "Notes": "string",
    * "Number": "string",
    * "Placement": "string",
    * "Project": "string",
    * "Reference": "string",
    * "Room": "string",
    * "Status": "string",
    * "StatusId": "string",
    * "Type": "string",
    * "TypeId": 0
}

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_AttendanceTransactions)Attendance Transactions
Attendance transactions resources 
Usable "CauseCodes" **Code**| **Description**  
---|---  
ARB| Timlön  
BE2| Beredskapstid 2  
BER or BE1| Beredskapstid (BE1 is used in PAXml)  
FLX| Flextid +/-  
HLG| Helglön  
JO2 or JR2| Jourtid 2 (JR2 is used in PAXml)  
JOR or JR1| Jourtid (JR1 is used in PAXml)  
MER| Mertid  
OB1| OB-ersättning 1  
OB2| OB-ersättning 2  
OB3| OB-ersättning 3  
OB4| OB-ersättning 4  
OB5| OB-ersättning 5  
OK0 or NV9| Extratid \u2013 Komptid (NV9 is used in PAXml)  
OK1 or ÖK1| Övertid 1 \u2013 Komptid (ÖK1 is used in PAXml)  
OK2 or ÖK2| Övertid 2 \u2013 Komptid (ÖK2 is used in PAXml)  
OK3 or ÖK3| Övertid 3 \u2013 Komptid (ÖK3 is used in PAXml)  
OK4 or ÖK4| Övertid 4 \u2013 Komptid (ÖK4 is used in PAXml)  
OK5 or ÖK5| Övertid 5 \u2013 Komptid (ÖK5 is used in PAXml)  
OT1 or ÖT1| Övertid 1 \u2013 Betalning (ÖT1 is used in PAXml)  
OT2 or ÖT2| Övertid 2 \u2013 Betalning (ÖT2 is used in PAXml)  
OT3 or ÖT3| Övertid 3 \u2013 Betalning (ÖT3 is used in PAXml)  
OT4 or ÖT4| Övertid 4 \u2013 Betalning (ÖT4 is used in PAXml)  
OT5 or ÖT5| Övertid 5 \u2013 Betalning (ÖT5 is used in PAXml)  
RES or RE1| Restid (RE1 is used in PAXml)  
TID| Arbetstid  
## [](https://api.fortnox.se/apidocs#tag/fortnox_AttendanceTransactions/operation/1_list_8)Lists all attendance transactions 
Supports query-string parameters **employeeid** and **date** for filtering the result.
##### query Parameters
employeeid| string filter by employee id  
---|---  
date| string filter by date  
### Responses
**200**
a list of attendance transactions
**default**
Error information if the request did not succeed
get/3/attendancetransactions
Default server
https://api.fortnox.se/3/attendancetransactions
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "AttendanceTransactions": [
    * {
      * "@url": "string",
      * "CauseCode": "ARB",
      * "CostCenter": "string",
      * "Date": "2019-08-24",
      * "EmployeeId": "string",
      * "Hours": "string",
      * "Project": "string",
      * "id": "497f6eca-6276-4993-bfeb-53cbbbba6f08"
}
]

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_AttendanceTransactions/operation/create_9)Create a new attendance transaction 
##### Request Body schema: */*
attendance transaction to create
AttendanceTransaction| object (fortnox_AttendanceTransaction)   
---|---  
### Responses
**201**
the created attendance transaction
**default**
Error information if the request did not succeed
post/3/attendancetransactions
Default server
https://api.fortnox.se/3/attendancetransactions
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "AttendanceTransaction": {
    * "CauseCode": "ARB",
    * "CostCenter": "string",
    * "Date": "2019-08-24",
    * "EmployeeId": "string",
    * "Hours": "string",
    * "Project": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_AttendanceTransactions/operation/remove_5)Delete an attendance transaction 
##### path Parameters
idrequired| string <uuid> identifies the transaction  
---|---  
### Responses
**200**
empty
**default**
Error information if the request did not succeed
delete/3/attendancetransactions/{id}
Default server
https://api.fortnox.se/3/attendancetransactions/{id}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "AttendanceTransaction": {
    * "CauseCode": "ARB",
    * "CostCenter": "string",
    * "Date": "2019-08-24",
    * "EmployeeId": "string",
    * "Hours": "string",
    * "Project": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_AttendanceTransactions/operation/get_9)Retrieve a specific attendance transaction 
Retrieves a specific transaction
##### path Parameters
idrequired| string <uuid> identifies the transaction  
---|---  
### Responses
**200**
the attendance transaction
**default**
Error information if the request did not succeed
get/3/attendancetransactions/{id}
Default server
https://api.fortnox.se/3/attendancetransactions/{id}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "AttendanceTransaction": {
    * "CauseCode": "ARB",
    * "CostCenter": "string",
    * "Date": "2019-08-24",
    * "EmployeeId": "string",
    * "Hours": "string",
    * "Project": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_AttendanceTransactions/operation/update_7)Update a single attendance transaction 
##### path Parameters
idrequired| string <uuid> identifies the transaction  
---|---  
##### Request Body schema: */*
to update
AttendanceTransaction| object (fortnox_AttendanceTransaction)   
---|---  
### Responses
**200**
the updated attendance transaction
**default**
Error information if the request did not succeed
put/3/attendancetransactions/{id}
Default server
https://api.fortnox.se/3/attendancetransactions/{id}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "AttendanceTransaction": {
    * "CauseCode": "ARB",
    * "CostCenter": "string",
    * "Date": "2019-08-24",
    * "EmployeeId": "string",
    * "Hours": "string",
    * "Project": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_AttendanceTransactions/operation/get_10)Retrieve attendance transactions 
Retrieves a list of attendance transaction for an employee on a specific date and cause code.
##### path Parameters
idrequired| string identifies the employee  
---|---  
Daterequired| string <date> date of the attendance  
Coderequired| string Enum: "ARB" "BE2" "BER" "FLX" "HLG" "JO2" "JOR" "MER" "OB1" "OB2" "OB3" "OB4" "OB5" "OK0" "OK1" "OK2" "OK3" "OK4" "OK5" "OT1" "OT2" "OT3" "OT4" "OT5" "RES" "TID" status code of the attendance transaction  
### Responses
**200**
a list of attendance transactions
**default**
Error information if the request did not succeed
get/3/attendancetransactions/{id}/{Date}/{Code}
Default server
https://api.fortnox.se/3/attendancetransactions/{id}/{Date}/{Code}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "AttendanceTransactions": [
    * {
      * "@url": "string",
      * "CauseCode": "ARB",
      * "CostCenter": "string",
      * "Date": "2019-08-24",
      * "EmployeeId": "string",
      * "Hours": "string",
      * "Project": "string",
      * "id": "497f6eca-6276-4993-bfeb-53cbbbba6f08"
}
]

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_CompanyInformation)Company Information
Company information resource
## [](https://api.fortnox.se/apidocs#tag/fortnox_CompanyInformation/operation/1_get_11)Retrieve the Company Information 
### Responses
**200**
company information
**default**
Error information if the request did not succeed
get/3/companyinformation
Default server
https://api.fortnox.se/3/companyinformation
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "CompanyInformation": {
    * "Address": "string",
    * "City": "string",
    * "CompanyName": "string",
    * "CountryCode": "string",
    * "DatabaseNumber": 0,
    * "OrganizationNumber": "string",
    * "VisitAddress": "string",
    * "VisitCity": "string",
    * "VisitCountryCode": "string",
    * "VisitZipCode": "string",
    * "ZipCode": "string"
}

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_CompanySettings)Company Settings
Company settings resource
## [](https://api.fortnox.se/apidocs#tag/fortnox_CompanySettings/operation/1_get_12)Retrieve the company settings 
### Responses
**200**
company settings
**default**
Error information if the request did not succeed
get/3/settings/company
Default server
https://api.fortnox.se/3/settings/company
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "CompanySettings": {
    * "Address": "string",
    * "BG": "string",
    * "BIC": "string",
    * "BranchCode": "string",
    * "City": "string",
    * "ContactFirstName": "string",
    * "ContactLastName": "string",
    * "Country": "string",
    * "CountryCode": "string",
    * "DatabaseNumber": "string",
    * "Domicile": "string",
    * "Email": "string",
    * "Fax": "string",
    * "IBAN": "string",
    * "Name": "string",
    * "OrganizationNumber": "string",
    * "PG": "string",
    * "Phone1": "string",
    * "Phone2": "string",
    * "TaxEnabled": true,
    * "VATNumber": "string",
    * "VisitAddress": "string",
    * "VisitCity": "string",
    * "VisitCountry": "string",
    * "VisitCountryCode": "string",
    * "VisitName": "string",
    * "VisitZipCode": "string",
    * "WWW": "string",
    * "ZipCode": "string"
}

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_ContractAccruals)Contract Accruals
Contract accruals resources
## [](https://api.fortnox.se/apidocs#tag/fortnox_ContractAccruals/operation/list_9)Retrieve a list of contract accruals 
The contract accruals register can return a list of records or a single record. By specifying a DocumentNumber in the URL, a single record will be returned. Not specifying a DocumentNumber will return a list of records.
### Responses
**200**
list of contract accruals
**default**
Error information if the request did not succeed
get/3/contractaccruals
Default server
https://api.fortnox.se/3/contractaccruals
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ContractAccruals": [
    * {
      * "@url": "string",
      * "Description": "string",
      * "DocumentNumber": 0,
      * "Period": "MONTHLY"
}
]

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_ContractAccruals/operation/create_10)Create a contract accrual 
##### Request Body schema: */*
contract accrual to create
ContractAccrual| object (fortnox_ContractAccrual)   
---|---  
### Responses
**201**
the created contract accrual
**default**
Error information if the request did not succeed
post/3/contractaccruals
Default server
https://api.fortnox.se/3/contractaccruals
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ContractAccrual": {
    * "@url": "string",
    * "AccrualAccount": 1000,
    * "AccrualRows": [
      * {
        * "Account": 0,
        * "CostCenter": "string",
        * "Credit": 0.1,
        * "Debit": 0.1,
        * "Project": "string",
        * "TransactionInformation": "string"
},
      * {
        * "Account": 0,
        * "CostCenter": "string",
        * "Credit": 0.1,
        * "Debit": 0.1,
        * "Project": "string",
        * "TransactionInformation": "string"
}
],
    * "CostAccount": 1000,
    * "Description": "string",
    * "DocumentNumber": 0,
    * "Period": "MONTHLY",
    * "Times": 0,
    * "Total": 0.1,
    * "VATIncluded": true
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_ContractAccruals/operation/remove_6)Remove a contract accrual 
##### path Parameters
DocumentNumberrequired| integer <int32> identifies the contract accrual  
---|---  
### Responses
**204**
Successfully removed the specified resource.
**default**
Error information if the request did not succeed
delete/3/contractaccruals/{DocumentNumber}
Default server
https://api.fortnox.se/3/contractaccruals/{DocumentNumber}
###  Response samples 
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ErrorInformation": {
    * "Code": 0,
    * "Error": 0,
    * "Message": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_ContractAccruals/operation/get_13)Retrieve a single contract accrual 
##### path Parameters
DocumentNumberrequired| integer <int32> identifies the contract accrual  
---|---  
### Responses
**200**
the existing contract accrual
**default**
Error information if the request did not succeed
get/3/contractaccruals/{DocumentNumber}
Default server
https://api.fortnox.se/3/contractaccruals/{DocumentNumber}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ContractAccrual": {
    * "@url": "string",
    * "AccrualAccount": 1000,
    * "AccrualRows": [
      * {
        * "Account": 0,
        * "CostCenter": "string",
        * "Credit": 0.1,
        * "Debit": 0.1,
        * "Project": "string",
        * "TransactionInformation": "string"
},
      * {
        * "Account": 0,
        * "CostCenter": "string",
        * "Credit": 0.1,
        * "Debit": 0.1,
        * "Project": "string",
        * "TransactionInformation": "string"
}
],
    * "CostAccount": 1000,
    * "Description": "string",
    * "DocumentNumber": 0,
    * "Period": "MONTHLY",
    * "Times": 0,
    * "Total": 0.1,
    * "VATIncluded": true
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_ContractAccruals/operation/update_8)Update a contract accrual 
##### path Parameters
DocumentNumberrequired| integer <int32> identifies the contract accrual  
---|---  
##### Request Body schema: */*
contract accrual to update
ContractAccrual| object (fortnox_ContractAccrual)   
---|---  
### Responses
**200**
the updated contract accrual
**default**
Error information if the request did not succeed
put/3/contractaccruals/{DocumentNumber}
Default server
https://api.fortnox.se/3/contractaccruals/{DocumentNumber}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ContractAccrual": {
    * "@url": "string",
    * "AccrualAccount": 1000,
    * "AccrualRows": [
      * {
        * "Account": 0,
        * "CostCenter": "string",
        * "Credit": 0.1,
        * "Debit": 0.1,
        * "Project": "string",
        * "TransactionInformation": "string"
},
      * {
        * "Account": 0,
        * "CostCenter": "string",
        * "Credit": 0.1,
        * "Debit": 0.1,
        * "Project": "string",
        * "TransactionInformation": "string"
}
],
    * "CostAccount": 1000,
    * "Description": "string",
    * "DocumentNumber": 0,
    * "Period": "MONTHLY",
    * "Times": 0,
    * "Total": 0.1,
    * "VATIncluded": true
}

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_ContractTemplates)Contract Templates
Contract templates resources
## [](https://api.fortnox.se/apidocs#tag/fortnox_ContractTemplates/operation/list_11)Retrieve a list of contract templates 
The contract template resource can return a list of records or a single record. By specifying a TemplateNumber in the URL, a single record will be returned. Not specifying a TemplateNumber will return a list of records.
### Responses
**200**
list of contract templates
**default**
Error information if the request did not succeed
get/3/contracttemplates
Default server
https://api.fortnox.se/3/contracttemplates
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ContractTemplates": [
    * {
      * "@url": "string",
      * "ContractLength": 1,
      * "ContractTemplate": 0,
      * "ContractTemplateName": "string",
      * "InvoiceInterval": 1
}
]

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_ContractTemplates/operation/create_12)Create a contract template 
##### Request Body schema: */*
contract template to create
ContractTemplate| object (fortnox_ContractTemplate)   
---|---  
### Responses
**201**
the created contract template
**default**
Error information if the request did not succeed
post/3/contracttemplates
Default server
https://api.fortnox.se/3/contracttemplates
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ContractTemplate": {
    * "@url": "string",
    * "AdministrationFee": 0.1,
    * "Continuous": true,
    * "ContractLength": 1,
    * "Freight": 0.1,
    * "InvoiceInterval": 1,
    * "InvoiceRows": [
      * {
        * "AccountNumber": 0,
        * "ArticleNumber": "string",
        * "CostCenter": "string",
        * "DeliveredQuantity": "string",
        * "Description": "string",
        * "Discount": 0.1,
        * "DiscountType": "PERCENT",
        * "Price": 0.1,
        * "Project": "string",
        * "Unit": "string"
}
],
    * "OurReference": "string",
    * "PrintTemplate": "string",
    * "Remarks": "string",
    * "TemplateName": "string",
    * "TemplateNumber": 0,
    * "TermsOfDelivery": "string",
    * "TermsOfPayment": "string",
    * "WayOfDelivery": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_ContractTemplates/operation/1_get_15)Retrieve a single contract template 
##### path Parameters
TemplateNumberrequired| integer <int32> identifies the contract template  
---|---  
### Responses
**200**
the existing contract template
**default**
Error information if the request did not succeed
get/3/contracttemplates/{TemplateNumber}
Default server
https://api.fortnox.se/3/contracttemplates/{TemplateNumber}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ContractTemplate": {
    * "@url": "string",
    * "AdministrationFee": 0.1,
    * "Continuous": true,
    * "ContractLength": 1,
    * "Freight": 0.1,
    * "InvoiceInterval": 1,
    * "InvoiceRows": [
      * {
        * "AccountNumber": 0,
        * "ArticleNumber": "string",
        * "CostCenter": "string",
        * "DeliveredQuantity": "string",
        * "Description": "string",
        * "Discount": 0.1,
        * "DiscountType": "PERCENT",
        * "Price": 0.1,
        * "Project": "string",
        * "Unit": "string"
}
],
    * "OurReference": "string",
    * "PrintTemplate": "string",
    * "Remarks": "string",
    * "TemplateName": "string",
    * "TemplateNumber": 0,
    * "TermsOfDelivery": "string",
    * "TermsOfPayment": "string",
    * "WayOfDelivery": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_ContractTemplates/operation/update_10)Update a contract template 
##### path Parameters
TemplateNumberrequired| integer <int32> identifies the contract template  
---|---  
##### Request Body schema: */*
contract template to update
ContractTemplate| object (fortnox_ContractTemplate)   
---|---  
### Responses
**200**
the updated contract template
**default**
Error information if the request did not succeed
put/3/contracttemplates/{TemplateNumber}
Default server
https://api.fortnox.se/3/contracttemplates/{TemplateNumber}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ContractTemplate": {
    * "@url": "string",
    * "AdministrationFee": 0.1,
    * "Continuous": true,
    * "ContractLength": 1,
    * "Freight": 0.1,
    * "InvoiceInterval": 1,
    * "InvoiceRows": [
      * {
        * "AccountNumber": 0,
        * "ArticleNumber": "string",
        * "CostCenter": "string",
        * "DeliveredQuantity": "string",
        * "Description": "string",
        * "Discount": 0.1,
        * "DiscountType": "PERCENT",
        * "Price": 0.1,
        * "Project": "string",
        * "Unit": "string"
}
],
    * "OurReference": "string",
    * "PrintTemplate": "string",
    * "Remarks": "string",
    * "TemplateName": "string",
    * "TemplateNumber": 0,
    * "TermsOfDelivery": "string",
    * "TermsOfPayment": "string",
    * "WayOfDelivery": "string"
}

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_Contracts)Contracts
Contracts resources 
Possible filters on Contracts endpoint **Filter** | **Description**  
---|---  
active | Retrieves all active contracts  
inactive | Retrieves all inactive contracts  
finished | Retrieves all finished contracts  
Possible values for filter 
## [](https://api.fortnox.se/apidocs#tag/fortnox_Contracts/operation/list_10)Retrieve a list of contracts 
##### query Parameters
filter| string Enum: "active" "inactive" "finished" possibility to filter contracts  
---|---  
### Responses
**200**
list of contracts
**default**
Error information if the request did not succeed
get/3/contracts
Default server
https://api.fortnox.se/3/contracts
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Contracts": [
    * {
      * "@url": "string",
      * "Continuous": true,
      * "ContractLength": 0,
      * "Currency": "string",
      * "CustomerName": "string",
      * "CustomerNumber": "string",
      * "DocumentNumber": "string",
      * "Invoiceinterval": 0,
      * "InvoicesRemaining": 0,
      * "LastInvoiceDate": "string",
      * "PeriodEnd": "2019-08-24",
      * "PeriodStart": "2019-08-24",
      * "Status": "string",
      * "TemplateNumber": 0,
      * "Total": 0.1
}
]

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Contracts/operation/1_create_11)Create a contract 
##### Request Body schema: */*
contract to create
Contract| object (fortnox_Contract)   
---|---  
### Responses
**201**
the created contract
**default**
Error information if the request did not succeed
post/3/contracts
Default server
https://api.fortnox.se/3/contracts
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Contract": {
    * "@url": "string",
    * "@urlTaxReductionList": "string",
    * "Active": true,
    * "AdministrationFee": 0.1,
    * "BasisTaxReduction": 0.1,
    * "Comments": "string",
    * "Continuous": true,
    * "ContractDate": "2019-08-24",
    * "ContractLength": 0,
    * "ContributionPercent": 0.1,
    * "ContributionValue": 0.1,
    * "CostCenter": "string",
    * "Currency": "string",
    * "CustomerName": "string",
    * "CustomerNumber": "string",
    * "DocumentNumber": "string",
    * "EmailInformation": {
      * "EmailAddressBCC": "string",
      * "EmailAddressCC": "string",
      * "EmailAddressFrom": "string",
      * "EmailAddressTo": "string",
      * "EmailBody": "string",
      * "EmailSubject": "string"
},
    * "ExternalInvoiceReference1": "string",
    * "ExternalInvoiceReference2": "string",
    * "Freight": 0.1,
    * "Gross": 0.1,
    * "HouseWork": true,
    * "InvoiceDiscount": 0.1,
    * "InvoiceInterval": 0,
    * "InvoiceRows": [
      * {
        * "AccountNumber": 1000,
        * "ArticleNumber": "string",
        * "ContributionPercent": "string",
        * "ContributionValue": "string",
        * "CostCenter": "string",
        * "DeliveredQuantity": "string",
        * "Description": "string",
        * "Discount": 0.1,
        * "DiscountType": "AMOUNT",
        * "HouseWork": true,
        * "HouseWorkHoursToReport": 0,
        * "HouseWorkType": "string",
        * "Price": 0.1,
        * "PriceExcludingVAT": 0.1,
        * "Project": "string",
        * "RowId": 0,
        * "Total": 0.1,
        * "TotalExcludingVAT": 0.1,
        * "Unit": "string",
        * "VAT": 0.1
}
],
    * "InvoicesRemaining": "string",
    * "Language": "SV",
    * "LastInvoiceDate": "string",
    * "Net": 0.1,
    * "OurReference": "string",
    * "PeriodEnd": "2019-08-24",
    * "PeriodStart": "2019-08-24",
    * "PriceList": "string",
    * "PrintTemplate": "string",
    * "Project": "string",
    * "Remarks": "string",
    * "RoundOff": 0.1,
    * "TaxReduction": 0.1,
    * "TaxReductionType": "none",
    * "TemplateName": "string",
    * "TemplateNumber": 0,
    * "TermsOfDelivery": "string",
    * "TermsOfPayment": "string",
    * "Total": 0.1,
    * "TotalToPay": 0.1,
    * "TotalVAT": 0.1,
    * "VatIncluded": true,
    * "WayOfDelivery": "string",
    * "YourOrderNumber": "string",
    * "YourReference": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Contracts/operation/get_14)Retrieve a single contract 
##### path Parameters
DocumentNumberrequired| string identifies the contract  
---|---  
### Responses
**200**
the existing contract
**default**
Error information if the request did not succeed
get/3/contracts/{DocumentNumber}
Default server
https://api.fortnox.se/3/contracts/{DocumentNumber}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Contract": {
    * "@url": "string",
    * "@urlTaxReductionList": "string",
    * "Active": true,
    * "AdministrationFee": 0.1,
    * "BasisTaxReduction": 0.1,
    * "Comments": "string",
    * "Continuous": true,
    * "ContractDate": "2019-08-24",
    * "ContractLength": 0,
    * "ContributionPercent": 0.1,
    * "ContributionValue": 0.1,
    * "CostCenter": "string",
    * "Currency": "string",
    * "CustomerName": "string",
    * "CustomerNumber": "string",
    * "DocumentNumber": "string",
    * "EmailInformation": {
      * "EmailAddressBCC": "string",
      * "EmailAddressCC": "string",
      * "EmailAddressFrom": "string",
      * "EmailAddressTo": "string",
      * "EmailBody": "string",
      * "EmailSubject": "string"
},
    * "ExternalInvoiceReference1": "string",
    * "ExternalInvoiceReference2": "string",
    * "Freight": 0.1,
    * "Gross": 0.1,
    * "HouseWork": true,
    * "InvoiceDiscount": 0.1,
    * "InvoiceInterval": 0,
    * "InvoiceRows": [
      * {
        * "AccountNumber": 1000,
        * "ArticleNumber": "string",
        * "ContributionPercent": "string",
        * "ContributionValue": "string",
        * "CostCenter": "string",
        * "DeliveredQuantity": "string",
        * "Description": "string",
        * "Discount": 0.1,
        * "DiscountType": "AMOUNT",
        * "HouseWork": true,
        * "HouseWorkHoursToReport": 0,
        * "HouseWorkType": "string",
        * "Price": 0.1,
        * "PriceExcludingVAT": 0.1,
        * "Project": "string",
        * "RowId": 0,
        * "Total": 0.1,
        * "TotalExcludingVAT": 0.1,
        * "Unit": "string",
        * "VAT": 0.1
}
],
    * "InvoicesRemaining": "string",
    * "Language": "SV",
    * "LastInvoiceDate": "string",
    * "Net": 0.1,
    * "OurReference": "string",
    * "PeriodEnd": "2019-08-24",
    * "PeriodStart": "2019-08-24",
    * "PriceList": "string",
    * "PrintTemplate": "string",
    * "Project": "string",
    * "Remarks": "string",
    * "RoundOff": 0.1,
    * "TaxReduction": 0.1,
    * "TaxReductionType": "none",
    * "TemplateName": "string",
    * "TemplateNumber": 0,
    * "TermsOfDelivery": "string",
    * "TermsOfPayment": "string",
    * "Total": 0.1,
    * "TotalToPay": 0.1,
    * "TotalVAT": 0.1,
    * "VatIncluded": true,
    * "WayOfDelivery": "string",
    * "YourOrderNumber": "string",
    * "YourReference": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Contracts/operation/update_9)Update a contract 
Note that there are two approaches for updating the rows on a contract.
If RowId is not specified on any row, the rows will be mapped and updated in the order in which they are set in the array. All rows that should remain on the contract needs to be provided.
If RowId is specified on one or more rows the following goes: Corresponding row with that id will be updated. The rows without RowId will be interpreted as new rows. If a row should not be updated but remain on the contract then specify only RowId like { "RowId": 123 }, otherwise it will be removed. Note that new RowIds are generated for all rows every time a contract is updated.
When the InvoiceDiscount value is set on the rows and the Contract, the value set on the Contract takes precedence over the row-level InvoiceDiscount.
##### path Parameters
DocumentNumberrequired| string identifies the contract  
---|---  
##### Request Body schema: */*
contract to update
Contract| object (fortnox_Contract)   
---|---  
### Responses
**200**
the updated contract
**default**
Error information if the request did not succeed
put/3/contracts/{DocumentNumber}
Default server
https://api.fortnox.se/3/contracts/{DocumentNumber}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Contract": {
    * "@url": "string",
    * "@urlTaxReductionList": "string",
    * "Active": true,
    * "AdministrationFee": 0.1,
    * "BasisTaxReduction": 0.1,
    * "Comments": "string",
    * "Continuous": true,
    * "ContractDate": "2019-08-24",
    * "ContractLength": 0,
    * "ContributionPercent": 0.1,
    * "ContributionValue": 0.1,
    * "CostCenter": "string",
    * "Currency": "string",
    * "CustomerName": "string",
    * "CustomerNumber": "string",
    * "DocumentNumber": "string",
    * "EmailInformation": {
      * "EmailAddressBCC": "string",
      * "EmailAddressCC": "string",
      * "EmailAddressFrom": "string",
      * "EmailAddressTo": "string",
      * "EmailBody": "string",
      * "EmailSubject": "string"
},
    * "ExternalInvoiceReference1": "string",
    * "ExternalInvoiceReference2": "string",
    * "Freight": 0.1,
    * "Gross": 0.1,
    * "HouseWork": true,
    * "InvoiceDiscount": 0.1,
    * "InvoiceInterval": 0,
    * "InvoiceRows": [
      * {
        * "AccountNumber": 1000,
        * "ArticleNumber": "string",
        * "ContributionPercent": "string",
        * "ContributionValue": "string",
        * "CostCenter": "string",
        * "DeliveredQuantity": "string",
        * "Description": "string",
        * "Discount": 0.1,
        * "DiscountType": "AMOUNT",
        * "HouseWork": true,
        * "HouseWorkHoursToReport": 0,
        * "HouseWorkType": "string",
        * "Price": 0.1,
        * "PriceExcludingVAT": 0.1,
        * "Project": "string",
        * "RowId": 0,
        * "Total": 0.1,
        * "TotalExcludingVAT": 0.1,
        * "Unit": "string",
        * "VAT": 0.1
}
],
    * "InvoicesRemaining": "string",
    * "Language": "SV",
    * "LastInvoiceDate": "string",
    * "Net": 0.1,
    * "OurReference": "string",
    * "PeriodEnd": "2019-08-24",
    * "PeriodStart": "2019-08-24",
    * "PriceList": "string",
    * "PrintTemplate": "string",
    * "Project": "string",
    * "Remarks": "string",
    * "RoundOff": 0.1,
    * "TaxReduction": 0.1,
    * "TaxReductionType": "none",
    * "TemplateName": "string",
    * "TemplateNumber": 0,
    * "TermsOfDelivery": "string",
    * "TermsOfPayment": "string",
    * "Total": 0.1,
    * "TotalToPay": 0.1,
    * "TotalVAT": 0.1,
    * "VatIncluded": true,
    * "WayOfDelivery": "string",
    * "YourOrderNumber": "string",
    * "YourReference": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Contracts/operation/createinvoice)Create invoice from contract 
##### path Parameters
DocumentNumberrequired| string identifies the contract  
---|---  
### Responses
**200**
created invoice
**default**
Error information if the request did not succeed
put/3/contracts/{DocumentNumber}/createinvoice
Default server
https://api.fortnox.se/3/contracts/{DocumentNumber}/createinvoice
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Invoice": {
    * "@url": "string",
    * "@urlTaxReductionList": "string",
    * "AccountingMethod": "ACCRUAL",
    * "Address1": "string",
    * "Address2": "string",
    * "AdministrationFee": 0.1,
    * "AdministrationFeeVAT": 0.1,
    * "Balance": 0.1,
    * "BasisTaxReduction": 0.1,
    * "Booked": true,
    * "Cancelled": true,
    * "City": "string",
    * "Comments": "string",
    * "ContractReference": 0,
    * "ContributionPercent": 0.1,
    * "ContributionValue": 0.1,
    * "CostCenter": "string",
    * "Country": "string",
    * "Credit": "string",
    * "CreditInvoiceReference": "string",
    * "Currency": "string",
    * "CurrencyRate": 0.1,
    * "CurrencyUnit": 0,
    * "CustomerName": "string",
    * "CustomerNumber": "string",
    * "DeliveryAddress1": "string",
    * "DeliveryAddress2": "string",
    * "DeliveryCity": "string",
    * "DeliveryCountry": "string",
    * "DeliveryDate": "2019-08-24",
    * "DeliveryName": "string",
    * "DeliveryZipCode": "string",
    * "DocumentNumber": "string",
    * "DueDate": "2019-08-24",
    * "EDIInformation": {
      * "EDIGlobalLocationNumber": "string",
      * "EDIGlobalLocationNumberDelivery": "string",
      * "EDIInvoiceExtra1": "string",
      * "EDIInvoiceExtra2": "string",
      * "EDIOurElectronicReference": "string",
      * "EDIStatus": "string",
      * "EDIYourElectronicReference": "string"
},
    * "EUQuarterlyReport": true,
    * "EmailInformation": {
      * "EmailAddressBCC": "string",
      * "EmailAddressCC": "string",
      * "EmailAddressFrom": "string",
      * "EmailAddressTo": "string",
      * "EmailBody": "string",
      * "EmailSubject": "string"
},
    * "ExternalInvoiceReference1": "string",
    * "ExternalInvoiceReference2": "string",
    * "FinalPayDate": "2019-08-24",
    * "Freight": 0.1,
    * "FreightVAT": 0.1,
    * "Gross": 0.1,
    * "HouseWork": true,
    * "InvoiceDate": "2019-08-24",
    * "InvoicePeriodEnd": "2019-08-24",
    * "InvoicePeriodReference": "string",
    * "InvoicePeriodStart": "2019-08-24",
    * "InvoiceRows": [
      * {
        * "AccountNumber": 1000,
        * "ArticleNumber": "string",
        * "ContributionPercent": "string",
        * "ContributionValue": "string",
        * "CostCenter": "string",
        * "DeliveredQuantity": "string",
        * "Description": "string",
        * "Discount": 0.1,
        * "DiscountType": "AMOUNT",
        * "HouseWork": true,
        * "HouseWorkHoursToReport": 999,
        * "HouseWorkType": "CONSTRUCTION",
        * "Price": 0.1,
        * "PriceExcludingVAT": 0.1,
        * "Project": "string",
        * "RowId": 0,
        * "StockPointCode": "string",
        * "Total": 0.1,
        * "TotalExcludingVAT": 0.1,
        * "Unit": "string",
        * "VAT": 0,
        * "VATCode": "string"
}
],
    * "InvoiceType": "INVOICE",
    * "Labels": [
      * {
        * "Id": 0
}
],
    * "Language": "SV",
    * "LastRemindDate": "2019-08-24",
    * "Net": 0.1,
    * "NotCompleted": true,
    * "NoxFinans": true,
    * "OCR": "string",
    * "OfferReference": "string",
    * "OrderReference": "string",
    * "OrganisationNumber": "string",
    * "OurReference": "string",
    * "OutboundDate": "2019-08-24",
    * "PaymentWay": "CASH",
    * "Phone1": "string",
    * "Phone2": "string",
    * "PriceList": "string",
    * "PrintTemplate": "string",
    * "Project": "string",
    * "Remarks": "string",
    * "Reminders": 0,
    * "RoundOff": 0.1,
    * "Sent": true,
    * "TaxReduction": 0,
    * "TaxReductionType": "none",
    * "TermsOfDelivery": "string",
    * "TermsOfPayment": "string",
    * "TimeBasisReference": 0,
    * "Total": 0.1,
    * "TotalToPay": 0.1,
    * "TotalVAT": 0.1,
    * "VATIncluded": true,
    * "VoucherNumber": 0,
    * "VoucherSeries": "string",
    * "VoucherYear": 0,
    * "WarehouseReady": true,
    * "WayOfDelivery": "string",
    * "YourOrderNumber": "string",
    * "YourReference": "string",
    * "ZipCode": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Contracts/operation/finish)Set a contract as finished 
##### path Parameters
DocumentNumberrequired| string identifies the contract  
---|---  
### Responses
**200**
the updated contract
**default**
Error information if the request did not succeed
put/3/contracts/{DocumentNumber}/finish
Default server
https://api.fortnox.se/3/contracts/{DocumentNumber}/finish
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Contract": {
    * "@url": "string",
    * "@urlTaxReductionList": "string",
    * "Active": true,
    * "AdministrationFee": 0.1,
    * "BasisTaxReduction": 0.1,
    * "Comments": "string",
    * "Continuous": true,
    * "ContractDate": "2019-08-24",
    * "ContractLength": 0,
    * "ContributionPercent": 0.1,
    * "ContributionValue": 0.1,
    * "CostCenter": "string",
    * "Currency": "string",
    * "CustomerName": "string",
    * "CustomerNumber": "string",
    * "DocumentNumber": "string",
    * "EmailInformation": {
      * "EmailAddressBCC": "string",
      * "EmailAddressCC": "string",
      * "EmailAddressFrom": "string",
      * "EmailAddressTo": "string",
      * "EmailBody": "string",
      * "EmailSubject": "string"
},
    * "ExternalInvoiceReference1": "string",
    * "ExternalInvoiceReference2": "string",
    * "Freight": 0.1,
    * "Gross": 0.1,
    * "HouseWork": true,
    * "InvoiceDiscount": 0.1,
    * "InvoiceInterval": 0,
    * "InvoiceRows": [
      * {
        * "AccountNumber": 1000,
        * "ArticleNumber": "string",
        * "ContributionPercent": "string",
        * "ContributionValue": "string",
        * "CostCenter": "string",
        * "DeliveredQuantity": "string",
        * "Description": "string",
        * "Discount": 0.1,
        * "DiscountType": "AMOUNT",
        * "HouseWork": true,
        * "HouseWorkHoursToReport": 0,
        * "HouseWorkType": "string",
        * "Price": 0.1,
        * "PriceExcludingVAT": 0.1,
        * "Project": "string",
        * "RowId": 0,
        * "Total": 0.1,
        * "TotalExcludingVAT": 0.1,
        * "Unit": "string",
        * "VAT": 0.1
}
],
    * "InvoicesRemaining": "string",
    * "Language": "SV",
    * "LastInvoiceDate": "string",
    * "Net": 0.1,
    * "OurReference": "string",
    * "PeriodEnd": "2019-08-24",
    * "PeriodStart": "2019-08-24",
    * "PriceList": "string",
    * "PrintTemplate": "string",
    * "Project": "string",
    * "Remarks": "string",
    * "RoundOff": 0.1,
    * "TaxReduction": 0.1,
    * "TaxReductionType": "none",
    * "TemplateName": "string",
    * "TemplateNumber": 0,
    * "TermsOfDelivery": "string",
    * "TermsOfPayment": "string",
    * "Total": 0.1,
    * "TotalToPay": 0.1,
    * "TotalVAT": 0.1,
    * "VatIncluded": true,
    * "WayOfDelivery": "string",
    * "YourOrderNumber": "string",
    * "YourReference": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Contracts/operation/increaseinvoicecount)Increases the invoice count without creating an invoice 
##### path Parameters
DocumentNumberrequired| string identifies the contract  
---|---  
### Responses
**200**
the updated contract
**default**
Error information if the request did not succeed
put/3/contracts/{DocumentNumber}/increaseinvoicecount
Default server
https://api.fortnox.se/3/contracts/{DocumentNumber}/increaseinvoicecount
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Contract": {
    * "@url": "string",
    * "@urlTaxReductionList": "string",
    * "Active": true,
    * "AdministrationFee": 0.1,
    * "BasisTaxReduction": 0.1,
    * "Comments": "string",
    * "Continuous": true,
    * "ContractDate": "2019-08-24",
    * "ContractLength": 0,
    * "ContributionPercent": 0.1,
    * "ContributionValue": 0.1,
    * "CostCenter": "string",
    * "Currency": "string",
    * "CustomerName": "string",
    * "CustomerNumber": "string",
    * "DocumentNumber": "string",
    * "EmailInformation": {
      * "EmailAddressBCC": "string",
      * "EmailAddressCC": "string",
      * "EmailAddressFrom": "string",
      * "EmailAddressTo": "string",
      * "EmailBody": "string",
      * "EmailSubject": "string"
},
    * "ExternalInvoiceReference1": "string",
    * "ExternalInvoiceReference2": "string",
    * "Freight": 0.1,
    * "Gross": 0.1,
    * "HouseWork": true,
    * "InvoiceDiscount": 0.1,
    * "InvoiceInterval": 0,
    * "InvoiceRows": [
      * {
        * "AccountNumber": 1000,
        * "ArticleNumber": "string",
        * "ContributionPercent": "string",
        * "ContributionValue": "string",
        * "CostCenter": "string",
        * "DeliveredQuantity": "string",
        * "Description": "string",
        * "Discount": 0.1,
        * "DiscountType": "AMOUNT",
        * "HouseWork": true,
        * "HouseWorkHoursToReport": 0,
        * "HouseWorkType": "string",
        * "Price": 0.1,
        * "PriceExcludingVAT": 0.1,
        * "Project": "string",
        * "RowId": 0,
        * "Total": 0.1,
        * "TotalExcludingVAT": 0.1,
        * "Unit": "string",
        * "VAT": 0.1
}
],
    * "InvoicesRemaining": "string",
    * "Language": "SV",
    * "LastInvoiceDate": "string",
    * "Net": 0.1,
    * "OurReference": "string",
    * "PeriodEnd": "2019-08-24",
    * "PeriodStart": "2019-08-24",
    * "PriceList": "string",
    * "PrintTemplate": "string",
    * "Project": "string",
    * "Remarks": "string",
    * "RoundOff": 0.1,
    * "TaxReduction": 0.1,
    * "TaxReductionType": "none",
    * "TemplateName": "string",
    * "TemplateNumber": 0,
    * "TermsOfDelivery": "string",
    * "TermsOfPayment": "string",
    * "Total": 0.1,
    * "TotalToPay": 0.1,
    * "TotalVAT": 0.1,
    * "VatIncluded": true,
    * "WayOfDelivery": "string",
    * "YourOrderNumber": "string",
    * "YourReference": "string"
}

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_CostCenters)Cost Centers
Cost centers resources 
Possible search params on Cost Centers endpoint **Search** | **Description**  
---|---  
lastmodified | Retrives costcenters modified after provided date and time  
Possible sort params on Cost Centers endpoint **Sort** | **Description**  
---|---  
code | Sorts cost centers according to code  
## [](https://api.fortnox.se/apidocs#tag/fortnox_CostCenters/operation/list_12)Retrieve a list of cost centers 
The cost centers register can return a list of records or a single record. By specifying a Code in the URL, a single record will be returned. Not specifying a Code will return a list of records.
### Responses
**200**
a list of cost centers
**default**
Error information if the request did not succeed
get/3/costcenters
Default server
https://api.fortnox.se/3/costcenters
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "CostCenters": [
    * {
      * "@url": "string",
      * "Active": true,
      * "Code": "string",
      * "Description": "string",
      * "Note": "string"
}
]

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_CostCenters/operation/create_13)Create a cost center 
##### Request Body schema: */*
cost center to create
CostCenter| object (fortnox_CostCenter)   
---|---  
### Responses
**201**
the created cost center
**default**
Error information if the request did not succeed
post/3/costcenters
Default server
https://api.fortnox.se/3/costcenters
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "CostCenter": {
    * "@url": "string",
    * "Active": true,
    * "Code": "string",
    * "Description": "string",
    * "Note": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_CostCenters/operation/remove_7)Remove a cost center 
##### path Parameters
Coderequired| string identifies the cost center to remove  
---|---  
### Responses
**204**
Successfully removed the specified resource.
**default**
Error information if the request did not succeed
delete/3/costcenters/{Code}
Default server
https://api.fortnox.se/3/costcenters/{Code}
###  Response samples 
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ErrorInformation": {
    * "Code": 0,
    * "Error": 0,
    * "Message": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_CostCenters/operation/get_16)Retrieve a single cost center 
##### path Parameters
Coderequired| string identifies the cost center  
---|---  
### Responses
**200**
the existing cost center
**default**
Error information if the request did not succeed
get/3/costcenters/{Code}
Default server
https://api.fortnox.se/3/costcenters/{Code}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "CostCenter": {
    * "@url": "string",
    * "Active": true,
    * "Code": "string",
    * "Description": "string",
    * "Note": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_CostCenters/operation/update_11)Update a cost center 
##### path Parameters
Coderequired| string identifies the cost center  
---|---  
##### Request Body schema: */*
cost center to update
CostCenter| object (fortnox_CostCenter)   
---|---  
### Responses
**200**
the updated cost center
**default**
Error information if the request did not succeed
put/3/costcenters/{Code}
Default server
https://api.fortnox.se/3/costcenters/{Code}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "CostCenter": {
    * "@url": "string",
    * "Active": true,
    * "Code": "string",
    * "Description": "string",
    * "Note": "string"
}

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_Currencies)Currencies
Currencies resources
## [](https://api.fortnox.se/apidocs#tag/fortnox_Currencies/operation/list_13)Retrieve a list of currencies 
The currency register can return a list of records or a single record. By specifying a Code in the URL, a single record will be returned. Not specifying a Code will return a list of records.
### Responses
**200**
a list of currencies
**default**
Error information if the request did not succeed
get/3/currencies
Default server
https://api.fortnox.se/3/currencies
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Currencies": [
    * {
      * "@url": "string",
      * "BuyRate": 0.1,
      * "Code": "string",
      * "Date": "2019-08-24",
      * "Description": "string",
      * "IsAutomatic": true,
      * "SellRate": 0.1,
      * "Unit": 0.1
}
],
  * "MetaInformation": {
    * "@CurrentPage": 0,
    * "@TotalPages": 0,
    * "@TotalResources": 0
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Currencies/operation/create_14)Create a currency 
##### Request Body schema: */*
currency to create
Currencyrequired| object (fortnox_Currency)   
---|---  
### Responses
**201**
the created currency
**default**
Error information if the request did not succeed
post/3/currencies
Default server
https://api.fortnox.se/3/currencies
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Currency": {
    * "@url": "string",
    * "BuyRate": 0.1,
    * "Code": "string",
    * "Date": "2019-08-24",
    * "Description": "string",
    * "IsAutomatic": true,
    * "SellRate": 0.1,
    * "Unit": 0.1
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Currencies/operation/remove_8)Remove a currency 
##### path Parameters
Coderequired| string identifies the currency  
---|---  
### Responses
**204**
Successfully removed the specified resource.
**default**
Error information if the request did not succeed
delete/3/currencies/{Code}
Default server
https://api.fortnox.se/3/currencies/{Code}
###  Response samples 
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ErrorInformation": {
    * "Code": 0,
    * "Error": 0,
    * "Message": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Currencies/operation/get_17)Retrieve a single currency 
##### path Parameters
Coderequired| string identifies currency  
---|---  
### Responses
**200**
the existing currency
**default**
Error information if the request did not succeed
get/3/currencies/{Code}
Default server
https://api.fortnox.se/3/currencies/{Code}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Currency": {
    * "@url": "string",
    * "BuyRate": 0.1,
    * "Code": "string",
    * "Date": "2019-08-24",
    * "Description": "string",
    * "IsAutomatic": true,
    * "SellRate": 0.1,
    * "Unit": 0.1
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Currencies/operation/update_12)Update a currency 
##### path Parameters
Coderequired| string identifies the currency  
---|---  
##### Request Body schema: */*
to update
Currencyrequired| object (fortnox_Currency)   
---|---  
### Responses
**200**
the updated currency
**default**
Error information if the request did not succeed
put/3/currencies/{Code}
Default server
https://api.fortnox.se/3/currencies/{Code}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Currency": {
    * "@url": "string",
    * "BuyRate": 0.1,
    * "Code": "string",
    * "Date": "2019-08-24",
    * "Description": "string",
    * "IsAutomatic": true,
    * "SellRate": 0.1,
    * "Unit": 0.1
}

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_CustomerReferences)Customer References
Customer references resource.
## [](https://api.fortnox.se/apidocs#tag/fortnox_CustomerReferences/operation/list_14)Retrieve a list of customers reference rows 
##### query Parameters
customer| string possibility to filter by customer number  
---|---  
### Responses
**200**
list of customers reference rows
**default**
Error information if the request did not succeed
get/3/customerreferences
Default server
https://api.fortnox.se/3/customerreferences
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "CustomerReference": {
    * "CustomerReferenceRows": [
      * {
        * "CustomerNumber": "string",
        * "Id": 0,
        * "Reference": "string"
}
]
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_CustomerReferences/operation/create_15)Create a customer reference row 
The created customer reference row will be returned if everything succeeded, if there was any problems an error will be returned.
##### Request Body schema: */*
customer reference row to create
CustomerReferenceRow| object (fortnox_CustomerReference_CustomerReferenceRow)   
---|---  
### Responses
**201**
the created customer reference row
**default**
Error information if the request did not succeed
post/3/customerreferences
Default server
https://api.fortnox.se/3/customerreferences
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "CustomerReference": {
    * "CustomerReferenceRows": [
      * {
        * "CustomerNumber": "string",
        * "Id": 0,
        * "Reference": "string"
}
]
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_CustomerReferences/operation/remove_9)Delete a customer reference row 
Deletes the customer reference row permanently. If everything succeeded the response will be of the type 204, No content and the response body will be empty.
If there was any problems an error will be returned.
You need to supply the unique customer reference row id of the customer reference row that you want to delete.
##### path Parameters
CustomerReferenceRowIdrequired| string identifies the customer reference row  
---|---  
### Responses
**204**
Successfully removed the specified resource.
**default**
Error information if the request did not succeed
delete/3/customerreferences/{CustomerReferenceRowId}
Default server
https://api.fortnox.se/3/customerreferences/{CustomerReferenceRowId}
###  Response samples 
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ErrorInformation": {
    * "Code": 0,
    * "Error": 0,
    * "Message": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_CustomerReferences/operation/get_18)Retrieve a customer reference row 
You need to supply the unique customer reference row id that was returned when the customer reference row was created or retrieved from the list of customer reference rows.
##### path Parameters
CustomerReferenceRowIdrequired| string identifies the customer reference row  
---|---  
### Responses
**200**
the existing customer reference row
**default**
Error information if the request did not succeed
get/3/customerreferences/{CustomerReferenceRowId}
Default server
https://api.fortnox.se/3/customerreferences/{CustomerReferenceRowId}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "CustomerReference": {
    * "CustomerReferenceRows": [
      * {
        * "CustomerNumber": "string",
        * "Id": 0,
        * "Reference": "string"
}
]
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_CustomerReferences/operation/update_13)Update a customer reference row 
The updated customer reference row will be returned if everything succeeded, if there was any problems an error will be returned.
You need to supply the unique customer reference row id of the customer reference row that you want to update.
Only the properties provided in the request body will be updated, properties not provided will be left unchanged.
CustomerNumber cannot be changed by this request.
##### path Parameters
CustomerReferenceRowIdrequired| string identifies the customer reference row  
---|---  
##### Request Body schema: */*
customer reference row to update
CustomerReferenceRow| object (fortnox_CustomerReference_CustomerReferenceRow)   
---|---  
### Responses
**200**
the updated customer reference row
**default**
Error information if the request did not succeed
put/3/customerreferences/{CustomerReferenceRowId}
Default server
https://api.fortnox.se/3/customerreferences/{CustomerReferenceRowId}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Customer": {
    * "@url": "string",
    * "Active": true,
    * "Address1": "string",
    * "Address2": "string",
    * "City": "string",
    * "Comments": "string",
    * "CostCenter": "string",
    * "Country": "string",
    * "CountryCode": "st",
    * "Currency": "str",
    * "CustomerNumber": "string",
    * "DefaultDeliveryTypes": {
      * "Invoice": "PRINT",
      * "Offer": "PRINT",
      * "Order": "PRINT"
},
    * "DefaultTemplates": {
      * "CashInvoice": "string",
      * "Invoice": "string",
      * "Offer": "string",
      * "Order": "string"
},
    * "DeliveryAddress1": "string",
    * "DeliveryAddress2": "string",
    * "DeliveryCity": "string",
    * "DeliveryCountry": "string",
    * "DeliveryCountryCode": "st",
    * "DeliveryFax": "string",
    * "DeliveryName": "string",
    * "DeliveryPhone1": "string",
    * "DeliveryPhone2": "string",
    * "DeliveryZipCode": "string",
    * "Email": "string",
    * "EmailInvoice": "string",
    * "EmailInvoiceBCC": "string",
    * "EmailInvoiceCC": "string",
    * "EmailOffer": "string",
    * "EmailOfferBCC": "string",
    * "EmailOfferCC": "string",
    * "EmailOrder": "string",
    * "EmailOrderBCC": "string",
    * "EmailOrderCC": "string",
    * "ExternalReference": "string",
    * "Fax": "string",
    * "GLN": "stringstrings",
    * "GLNDelivery": "stringstrings",
    * "InvoiceAdministrationFee": "string",
    * "InvoiceDiscount": 0.1,
    * "InvoiceFreight": "string",
    * "InvoiceRemark": "string",
    * "Name": "string",
    * "OrganisationNumber": "string",
    * "OurReference": "string",
    * "Phone1": "string",
    * "Phone2": "string",
    * "PriceList": "string",
    * "Project": "string",
    * "SalesAccount": "stri",
    * "ShowPriceVATIncluded": true,
    * "TermsOfDelivery": "string",
    * "TermsOfPayment": "string",
    * "Type": "PRIVATE",
    * "VATNumber": "string",
    * "VATType": "SEVAT",
    * "VisitingAddress": "string",
    * "VisitingCity": "string",
    * "VisitingCountry": "string",
    * "VisitingCountryCode": "st",
    * "VisitingZipCode": "string",
    * "WWW": "string",
    * "WayOfDelivery": "string",
    * "YourReference": "string",
    * "ZipCode": "string"
}

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_Customers)Customers
Customers resources
## [](https://api.fortnox.se/apidocs#tag/fortnox_Customers/operation/list_15)Retrieve a list of customers 
The customers are returned sorted by customer number with the lowest number appearing first.
##### query Parameters
filter| string Enum: "active" "inactive" possibility to filter customers  
---|---  
customernumber| string filter by customer number  
name| string filter by name  
zipcode| string filter by zip code  
city| string filter by city  
email| string filter by email  
phone| string filter by phone  
organisationnumber| string filter by organisation number  
gln| string filter by gln  
glndelivery| string filter by gln delivery  
lastmodified| string filter by last modified  
sortby| string Enum: "customernumber" "name" field to sort returned list  
### Responses
**200**
list of customers
**default**
Error information if the request did not succeed
get/3/customers
Default server
https://api.fortnox.se/3/customers
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Customers": [
    * {
      * "@url": "string",
      * "Address1": "string",
      * "Address2": "string",
      * "City": "string",
      * "CustomerNumber": "string",
      * "Email": "string",
      * "Name": "string",
      * "OrganisationNumber": "string",
      * "Phone": "string",
      * "ZipCode": "string"
}
]

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Customers/operation/create_16)Create a customer 
The created customer will be returned if everything succeeded, if there was any problems an error will be returned.
##### Request Body schema: */*
customer to create
Customer| object (fortnox_Customer)   
---|---  
### Responses
**201**
the created customer
**default**
Error information if the request did not succeed
post/3/customers
Default server
https://api.fortnox.se/3/customers
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Customer": {
    * "@url": "string",
    * "Active": true,
    * "Address1": "string",
    * "Address2": "string",
    * "City": "string",
    * "Comments": "string",
    * "CostCenter": "string",
    * "Country": "string",
    * "CountryCode": "st",
    * "Currency": "str",
    * "CustomerNumber": "string",
    * "DefaultDeliveryTypes": {
      * "Invoice": "PRINT",
      * "Offer": "PRINT",
      * "Order": "PRINT"
},
    * "DefaultTemplates": {
      * "CashInvoice": "string",
      * "Invoice": "string",
      * "Offer": "string",
      * "Order": "string"
},
    * "DeliveryAddress1": "string",
    * "DeliveryAddress2": "string",
    * "DeliveryCity": "string",
    * "DeliveryCountry": "string",
    * "DeliveryCountryCode": "st",
    * "DeliveryFax": "string",
    * "DeliveryName": "string",
    * "DeliveryPhone1": "string",
    * "DeliveryPhone2": "string",
    * "DeliveryZipCode": "string",
    * "Email": "string",
    * "EmailInvoice": "string",
    * "EmailInvoiceBCC": "string",
    * "EmailInvoiceCC": "string",
    * "EmailOffer": "string",
    * "EmailOfferBCC": "string",
    * "EmailOfferCC": "string",
    * "EmailOrder": "string",
    * "EmailOrderBCC": "string",
    * "EmailOrderCC": "string",
    * "ExternalReference": "string",
    * "Fax": "string",
    * "GLN": "stringstrings",
    * "GLNDelivery": "stringstrings",
    * "InvoiceAdministrationFee": "string",
    * "InvoiceDiscount": 0.1,
    * "InvoiceFreight": "string",
    * "InvoiceRemark": "string",
    * "Name": "string",
    * "OrganisationNumber": "string",
    * "OurReference": "string",
    * "Phone1": "string",
    * "Phone2": "string",
    * "PriceList": "string",
    * "Project": "string",
    * "SalesAccount": "stri",
    * "ShowPriceVATIncluded": true,
    * "TermsOfDelivery": "string",
    * "TermsOfPayment": "string",
    * "Type": "PRIVATE",
    * "VATNumber": "string",
    * "VATType": "SEVAT",
    * "VisitingAddress": "string",
    * "VisitingCity": "string",
    * "VisitingCountry": "string",
    * "VisitingCountryCode": "st",
    * "VisitingZipCode": "string",
    * "WWW": "string",
    * "WayOfDelivery": "string",
    * "YourReference": "string",
    * "ZipCode": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Customers/operation/remove_10)Delete a customer 
Deletes the customer permanently. If everything succeeded the response will be of the type 204 \u2013 No content and the response body will be empty. If there was any problems an error will be returned. You need to supply the unique customer number of the customer that you want to delete.
##### path Parameters
CustomerNumberrequired| string identifies the customer  
---|---  
### Responses
**204**
Successfully removed the specified resource.
**default**
Error information if the request did not succeed
delete/3/customers/{CustomerNumber}
Default server
https://api.fortnox.se/3/customers/{CustomerNumber}
###  Response samples 
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ErrorInformation": {
    * "Code": 0,
    * "Error": 0,
    * "Message": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Customers/operation/get_19)Retrieve a customer 
You need to supply the unique customer number that was returned when the customer was created or retrieved from the list of customers.
##### path Parameters
CustomerNumberrequired| string identifies the customer  
---|---  
### Responses
**200**
the existing customer
**default**
Error information if the request did not succeed
get/3/customers/{CustomerNumber}
Default server
https://api.fortnox.se/3/customers/{CustomerNumber}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Customer": {
    * "@url": "string",
    * "Active": true,
    * "Address1": "string",
    * "Address2": "string",
    * "City": "string",
    * "Comments": "string",
    * "CostCenter": "string",
    * "Country": "string",
    * "CountryCode": "st",
    * "Currency": "str",
    * "CustomerNumber": "string",
    * "DefaultDeliveryTypes": {
      * "Invoice": "PRINT",
      * "Offer": "PRINT",
      * "Order": "PRINT"
},
    * "DefaultTemplates": {
      * "CashInvoice": "string",
      * "Invoice": "string",
      * "Offer": "string",
      * "Order": "string"
},
    * "DeliveryAddress1": "string",
    * "DeliveryAddress2": "string",
    * "DeliveryCity": "string",
    * "DeliveryCountry": "string",
    * "DeliveryCountryCode": "st",
    * "DeliveryFax": "string",
    * "DeliveryName": "string",
    * "DeliveryPhone1": "string",
    * "DeliveryPhone2": "string",
    * "DeliveryZipCode": "string",
    * "Email": "string",
    * "EmailInvoice": "string",
    * "EmailInvoiceBCC": "string",
    * "EmailInvoiceCC": "string",
    * "EmailOffer": "string",
    * "EmailOfferBCC": "string",
    * "EmailOfferCC": "string",
    * "EmailOrder": "string",
    * "EmailOrderBCC": "string",
    * "EmailOrderCC": "string",
    * "ExternalReference": "string",
    * "Fax": "string",
    * "GLN": "stringstrings",
    * "GLNDelivery": "stringstrings",
    * "InvoiceAdministrationFee": "string",
    * "InvoiceDiscount": 0.1,
    * "InvoiceFreight": "string",
    * "InvoiceRemark": "string",
    * "Name": "string",
    * "OrganisationNumber": "string",
    * "OurReference": "string",
    * "Phone1": "string",
    * "Phone2": "string",
    * "PriceList": "string",
    * "Project": "string",
    * "SalesAccount": "stri",
    * "ShowPriceVATIncluded": true,
    * "TermsOfDelivery": "string",
    * "TermsOfPayment": "string",
    * "Type": "PRIVATE",
    * "VATNumber": "string",
    * "VATType": "SEVAT",
    * "VisitingAddress": "string",
    * "VisitingCity": "string",
    * "VisitingCountry": "string",
    * "VisitingCountryCode": "st",
    * "VisitingZipCode": "string",
    * "WWW": "string",
    * "WayOfDelivery": "string",
    * "YourReference": "string",
    * "ZipCode": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Customers/operation/update_14)Update a customer 
The updated customer will be returned if everything succeeded, if there was any problems an error will be returned.
You need to supply the unique customer number of the customer that you want to update.
Only the properties provided in the request body will be updated, properties not provided will left unchanged.
##### path Parameters
CustomerNumberrequired| string identifies the customer  
---|---  
##### Request Body schema: */*
customer to update
Customer| object (fortnox_Customer)   
---|---  
### Responses
**200**
the updated customer
**default**
Error information if the request did not succeed
put/3/customers/{CustomerNumber}
Default server
https://api.fortnox.se/3/customers/{CustomerNumber}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Customer": {
    * "@url": "string",
    * "Active": true,
    * "Address1": "string",
    * "Address2": "string",
    * "City": "string",
    * "Comments": "string",
    * "CostCenter": "string",
    * "Country": "string",
    * "CountryCode": "st",
    * "Currency": "str",
    * "CustomerNumber": "string",
    * "DefaultDeliveryTypes": {
      * "Invoice": "PRINT",
      * "Offer": "PRINT",
      * "Order": "PRINT"
},
    * "DefaultTemplates": {
      * "CashInvoice": "string",
      * "Invoice": "string",
      * "Offer": "string",
      * "Order": "string"
},
    * "DeliveryAddress1": "string",
    * "DeliveryAddress2": "string",
    * "DeliveryCity": "string",
    * "DeliveryCountry": "string",
    * "DeliveryCountryCode": "st",
    * "DeliveryFax": "string",
    * "DeliveryName": "string",
    * "DeliveryPhone1": "string",
    * "DeliveryPhone2": "string",
    * "DeliveryZipCode": "string",
    * "Email": "string",
    * "EmailInvoice": "string",
    * "EmailInvoiceBCC": "string",
    * "EmailInvoiceCC": "string",
    * "EmailOffer": "string",
    * "EmailOfferBCC": "string",
    * "EmailOfferCC": "string",
    * "EmailOrder": "string",
    * "EmailOrderBCC": "string",
    * "EmailOrderCC": "string",
    * "ExternalReference": "string",
    * "Fax": "string",
    * "GLN": "stringstrings",
    * "GLNDelivery": "stringstrings",
    * "InvoiceAdministrationFee": "string",
    * "InvoiceDiscount": 0.1,
    * "InvoiceFreight": "string",
    * "InvoiceRemark": "string",
    * "Name": "string",
    * "OrganisationNumber": "string",
    * "OurReference": "string",
    * "Phone1": "string",
    * "Phone2": "string",
    * "PriceList": "string",
    * "Project": "string",
    * "SalesAccount": "stri",
    * "ShowPriceVATIncluded": true,
    * "TermsOfDelivery": "string",
    * "TermsOfPayment": "string",
    * "Type": "PRIVATE",
    * "VATNumber": "string",
    * "VATType": "SEVAT",
    * "VisitingAddress": "string",
    * "VisitingCity": "string",
    * "VisitingCountry": "string",
    * "VisitingCountryCode": "st",
    * "VisitingZipCode": "string",
    * "WWW": "string",
    * "WayOfDelivery": "string",
    * "YourReference": "string",
    * "ZipCode": "string"
}

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_EUVatLimitRegulation)EU Vat Limit Regulation
EU vat limit regulation resources
## [](https://api.fortnox.se/apidocs#tag/fortnox_EUVatLimitRegulation/operation/get_21)Retrieve details about eu vat limit 
##### query Parameters
year| integer <int32> eu vat limit regulation for year, if not provided than this will be set to current year  
---|---  
### Responses
**200**
eu vat limit regulation entry
**default**
Error information if the request did not succeed
get/3/euvatlimitregulation
Default server
https://api.fortnox.se/3/euvatlimitregulation
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "EUVatLimitRegulation": {
    * "IsOverLimit": true,
    * "Limit": 0,
    * "TotalExclVat": 0.1,
    * "Year": "string"
}

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_Employees)Employees
Employees resources
## [](https://api.fortnox.se/apidocs#tag/fortnox_Employees/operation/list_16)Retrieve a list of employees 
ScheduleId, MonthlySalary and HourlyPay reflect current values, all ScheduleIds are returned in DatedSchedules and all MonthlySalary and HourlyPay pairs are returned in DatedWages.
### Responses
**200**
list of employees
**default**
Error information if the request did not succeed
get/3/employees
Default server
https://api.fortnox.se/3/employees
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Employees": [
    * {
      * "@url": "string",
      * "Address1": "string",
      * "Address2": "string",
      * "AutoNonRecurringTax": true,
      * "AverageHourlyWage": "string",
      * "AverageWeeklyHours": "string",
      * "BankAccountNo": "string",
      * "City": "string",
      * "ClearingNo": "string",
      * "CostCenter": "string",
      * "Country": "string",
      * "DatedSchedules": [
        * {
          * "EmployeeId": "string",
          * "FirstDay": "2019-08-24",
          * "ScheduleId": "string"
}
],
      * "DatedWages": [
        * {
          * "EmployeeId": "string",
          * "FirstDay": "2019-08-24",
          * "HourlyPay": "string",
          * "MonthlySalary": "string"
}
],
      * "Email": "string",
      * "EmployedTo": "2019-08-24",
      * "EmployeeChildren": [
        * {
          * "ApprovedDays": 0,
          * "Child": "string",
          * "EmployeeId": "string",
          * "Id": "string",
          * "IngoingWithdrawnDays": 0,
          * "WithdrawnDays": 0.1
}
],
      * "EmployeeId": "string",
      * "EmploymentDate": "2019-08-24",
      * "EmploymentForm": "TV",
      * "FirstName": "string",
      * "ForaType": "A",
      * "FullName": "string",
      * "HourlyPay": "string",
      * "Inactive": true,
      * "JobTitle": "string",
      * "LastName": "string",
      * "MonthlySalary": "string",
      * "NonRecurringTax": "string",
      * "PersonalIdentityNumber": "string",
      * "PersonelType": "TJM",
      * "Phone1": "string",
      * "Phone2": "string",
      * "PostCode": "string",
      * "Project": "string",
      * "SalaryForm": "MAN",
      * "ScheduleId": "string",
      * "TaxAllowance": "HUV",
      * "TaxColumn": 1,
      * "TaxTable": "string",
      * "VacationDaysPaid": 0.1,
      * "VacationDaysPendingPaid": 0.1,
      * "VacationDaysPendingPrepaid": 0.1,
      * "VacationDaysPendingSaved": 0.1,
      * "VacationDaysPendingSavedYear1": 0.1,
      * "VacationDaysPendingSavedYear2": 0.1,
      * "VacationDaysPendingSavedYear3": 0.1,
      * "VacationDaysPendingSavedYear4": 0.1,
      * "VacationDaysPendingSavedYear5": 0.1,
      * "VacationDaysPendingSavedYear6Plus": 0.1,
      * "VacationDaysPendingUnpaid": 0.1,
      * "VacationDaysPrepaid": 0.1,
      * "VacationDaysRegisteredPaid": 0.1,
      * "VacationDaysRegisteredPrepaid": 0.1,
      * "VacationDaysRegisteredSaved": 0.1,
      * "VacationDaysRegisteredSavedYear1": 0.1,
      * "VacationDaysRegisteredSavedYear2": 0.1,
      * "VacationDaysRegisteredSavedYear3": 0.1,
      * "VacationDaysRegisteredSavedYear4": 0.1,
      * "VacationDaysRegisteredSavedYear5": 0.1,
      * "VacationDaysRegisteredSavedYear6Plus": 0.1,
      * "VacationDaysRegisteredUnpaid": 0.1,
      * "VacationDaysSaved": 0.1,
      * "VacationDaysSavedEmploymentRateYear1": 0.1,
      * "VacationDaysSavedEmploymentRateYear2": 0.1,
      * "VacationDaysSavedEmploymentRateYear3": 0.1,
      * "VacationDaysSavedEmploymentRateYear4": 0.1,
      * "VacationDaysSavedEmploymentRateYear5": 0.1,
      * "VacationDaysSavedEmploymentRateYear6Plus": 0.1,
      * "VacationDaysSavedYear1": 0.1,
      * "VacationDaysSavedYear2": 0.1,
      * "VacationDaysSavedYear3": 0.1,
      * "VacationDaysSavedYear4": 0.1,
      * "VacationDaysSavedYear5": 0.1,
      * "VacationDaysSavedYear6Plus": 0.1,
      * "VacationDaysUnpaid": 0.1
}
]

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Employees/operation/create_17)Create a new employee 
EmployeeId is optional. If not supplied the program will generate a unique id.
VacationDaysSaved and all registered and pending vacationdays are read only.
Only one of DatedSchedules and ScheduleId may be supplied. If DatedSchedules are supplied it must have one and only one record where FirstDay = '1970-01-01'. All FirstDay values must greater or equal to '1970-01-01' and unique.
If DatedWages is supplied neither MonthlySalary nor HourlyPay may be supplied. If MonthlySalary or HourlyPay are supplied, DatedWages may not be supplied. If DatedWages are supplied it must have one and only one record where FirstDay = '1970-01-01'. All FirstDay values must greater or equal to '1970-01-01' and unique.
##### Request Body schema: */*
employee to create
Employee| object (fortnox_Employee)   
---|---  
### Responses
**201**
the created employee
**default**
Error information if the request did not succeed
post/3/employees
Default server
https://api.fortnox.se/3/employees
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Employee": {
    * "Address1": "string",
    * "Address2": "string",
    * "AutoNonRecurringTax": true,
    * "AverageHourlyWage": "string",
    * "AverageWeeklyHours": "string",
    * "BankAccountNo": "string",
    * "City": "string",
    * "ClearingNo": "string",
    * "CostCenter": "string",
    * "Country": "string",
    * "DatedSchedules": [
      * {
        * "EmployeeId": "string",
        * "FirstDay": "2019-08-24",
        * "ScheduleId": "string"
}
],
    * "DatedWages": [
      * {
        * "EmployeeId": "string",
        * "FirstDay": "2019-08-24",
        * "HourlyPay": "string",
        * "MonthlySalary": "string"
}
],
    * "Email": "string",
    * "EmployedTo": "2019-08-24",
    * "EmployeeChildren": [
      * {
        * "ApprovedDays": 0,
        * "Child": "string",
        * "EmployeeId": "string",
        * "Id": "string",
        * "IngoingWithdrawnDays": 0,
        * "WithdrawnDays": 0.1
}
],
    * "EmployeeId": "string",
    * "EmploymentDate": "2019-08-24",
    * "EmploymentForm": "TV",
    * "FirstName": "string",
    * "ForaType": "A",
    * "FullName": "string",
    * "HourlyPay": "string",
    * "Inactive": true,
    * "JobTitle": "string",
    * "LastName": "string",
    * "MonthlySalary": "string",
    * "NonRecurringTax": "string",
    * "PersonalIdentityNumber": "string",
    * "PersonelType": "TJM",
    * "Phone1": "string",
    * "Phone2": "string",
    * "PostCode": "string",
    * "Project": "string",
    * "SalaryForm": "MAN",
    * "ScheduleId": "string",
    * "TaxAllowance": "HUV",
    * "TaxColumn": 1,
    * "TaxTable": "string",
    * "VacationDaysPaid": 0.1,
    * "VacationDaysPendingPaid": 0.1,
    * "VacationDaysPendingPrepaid": 0.1,
    * "VacationDaysPendingSaved": 0.1,
    * "VacationDaysPendingSavedYear1": 0.1,
    * "VacationDaysPendingSavedYear2": 0.1,
    * "VacationDaysPendingSavedYear3": 0.1,
    * "VacationDaysPendingSavedYear4": 0.1,
    * "VacationDaysPendingSavedYear5": 0.1,
    * "VacationDaysPendingSavedYear6Plus": 0.1,
    * "VacationDaysPendingUnpaid": 0.1,
    * "VacationDaysPrepaid": 0.1,
    * "VacationDaysRegisteredPaid": 0.1,
    * "VacationDaysRegisteredPrepaid": 0.1,
    * "VacationDaysRegisteredSaved": 0.1,
    * "VacationDaysRegisteredSavedYear1": 0.1,
    * "VacationDaysRegisteredSavedYear2": 0.1,
    * "VacationDaysRegisteredSavedYear3": 0.1,
    * "VacationDaysRegisteredSavedYear4": 0.1,
    * "VacationDaysRegisteredSavedYear5": 0.1,
    * "VacationDaysRegisteredSavedYear6Plus": 0.1,
    * "VacationDaysRegisteredUnpaid": 0.1,
    * "VacationDaysSaved": 0.1,
    * "VacationDaysSavedEmploymentRateYear1": 0.1,
    * "VacationDaysSavedEmploymentRateYear2": 0.1,
    * "VacationDaysSavedEmploymentRateYear3": 0.1,
    * "VacationDaysSavedEmploymentRateYear4": 0.1,
    * "VacationDaysSavedEmploymentRateYear5": 0.1,
    * "VacationDaysSavedEmploymentRateYear6Plus": 0.1,
    * "VacationDaysSavedYear1": 0.1,
    * "VacationDaysSavedYear2": 0.1,
    * "VacationDaysSavedYear3": 0.1,
    * "VacationDaysSavedYear4": 0.1,
    * "VacationDaysSavedYear5": 0.1,
    * "VacationDaysSavedYear6Plus": 0.1,
    * "VacationDaysUnpaid": 0.1
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Employees/operation/get_20)Retrieve a specific employee 
ScheduleId, MonthlySalary and HourlyPay reflect current values, all ScheduleIds are returned in DatedSchedules and all MonthlySalary and HourlyPay pairs are returned in DatedWages.
##### path Parameters
EmployeeIdrequired| string identifies the employee  
---|---  
### Responses
**200**
the existing employee
**default**
Error information if the request did not succeed
get/3/employees/{EmployeeId}
Default server
https://api.fortnox.se/3/employees/{EmployeeId}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Employee": {
    * "Address1": "string",
    * "Address2": "string",
    * "AutoNonRecurringTax": true,
    * "AverageHourlyWage": "string",
    * "AverageWeeklyHours": "string",
    * "BankAccountNo": "string",
    * "City": "string",
    * "ClearingNo": "string",
    * "CostCenter": "string",
    * "Country": "string",
    * "DatedSchedules": [
      * {
        * "EmployeeId": "string",
        * "FirstDay": "2019-08-24",
        * "ScheduleId": "string"
}
],
    * "DatedWages": [
      * {
        * "EmployeeId": "string",
        * "FirstDay": "2019-08-24",
        * "HourlyPay": "string",
        * "MonthlySalary": "string"
}
],
    * "Email": "string",
    * "EmployedTo": "2019-08-24",
    * "EmployeeChildren": [
      * {
        * "ApprovedDays": 0,
        * "Child": "string",
        * "EmployeeId": "string",
        * "Id": "string",
        * "IngoingWithdrawnDays": 0,
        * "WithdrawnDays": 0.1
}
],
    * "EmployeeId": "string",
    * "EmploymentDate": "2019-08-24",
    * "EmploymentForm": "TV",
    * "FirstName": "string",
    * "ForaType": "A",
    * "FullName": "string",
    * "HourlyPay": "string",
    * "Inactive": true,
    * "JobTitle": "string",
    * "LastName": "string",
    * "MonthlySalary": "string",
    * "NonRecurringTax": "string",
    * "PersonalIdentityNumber": "string",
    * "PersonelType": "TJM",
    * "Phone1": "string",
    * "Phone2": "string",
    * "PostCode": "string",
    * "Project": "string",
    * "SalaryForm": "MAN",
    * "ScheduleId": "string",
    * "TaxAllowance": "HUV",
    * "TaxColumn": 1,
    * "TaxTable": "string",
    * "VacationDaysPaid": 0.1,
    * "VacationDaysPendingPaid": 0.1,
    * "VacationDaysPendingPrepaid": 0.1,
    * "VacationDaysPendingSaved": 0.1,
    * "VacationDaysPendingSavedYear1": 0.1,
    * "VacationDaysPendingSavedYear2": 0.1,
    * "VacationDaysPendingSavedYear3": 0.1,
    * "VacationDaysPendingSavedYear4": 0.1,
    * "VacationDaysPendingSavedYear5": 0.1,
    * "VacationDaysPendingSavedYear6Plus": 0.1,
    * "VacationDaysPendingUnpaid": 0.1,
    * "VacationDaysPrepaid": 0.1,
    * "VacationDaysRegisteredPaid": 0.1,
    * "VacationDaysRegisteredPrepaid": 0.1,
    * "VacationDaysRegisteredSaved": 0.1,
    * "VacationDaysRegisteredSavedYear1": 0.1,
    * "VacationDaysRegisteredSavedYear2": 0.1,
    * "VacationDaysRegisteredSavedYear3": 0.1,
    * "VacationDaysRegisteredSavedYear4": 0.1,
    * "VacationDaysRegisteredSavedYear5": 0.1,
    * "VacationDaysRegisteredSavedYear6Plus": 0.1,
    * "VacationDaysRegisteredUnpaid": 0.1,
    * "VacationDaysSaved": 0.1,
    * "VacationDaysSavedEmploymentRateYear1": 0.1,
    * "VacationDaysSavedEmploymentRateYear2": 0.1,
    * "VacationDaysSavedEmploymentRateYear3": 0.1,
    * "VacationDaysSavedEmploymentRateYear4": 0.1,
    * "VacationDaysSavedEmploymentRateYear5": 0.1,
    * "VacationDaysSavedEmploymentRateYear6Plus": 0.1,
    * "VacationDaysSavedYear1": 0.1,
    * "VacationDaysSavedYear2": 0.1,
    * "VacationDaysSavedYear3": 0.1,
    * "VacationDaysSavedYear4": 0.1,
    * "VacationDaysSavedYear5": 0.1,
    * "VacationDaysSavedYear6Plus": 0.1,
    * "VacationDaysUnpaid": 0.1
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Employees/operation/update_15)Update employee 
Only one of DatedSchedules and ScheduleId may be supplied. If DatedSchedules are supplied it must have one and only one record where FirstDay = '1970-01-01'. All FirstDay values must greater or equal to '1970-01-01' and unique.
VacationDaysSaved and all registered and pending vacationdays are read only.
If DatedWages is supplied neither MonthlySalary nor HourlyPay may be supplied. If MonthlySalary or HourlyPay are supplied, DatedWages may not be supplied. If DatedWages are supplied it must have one and only one record where FirstDay = '1970-01-01'. All FirstDay values must greater or equal to '1970-01-01' and unique.
##### path Parameters
EmployeeIdrequired| string identifies the employee  
---|---  
##### Request Body schema: */*
employee to update
Employee| object (fortnox_Employee)   
---|---  
### Responses
**200**
the updated employee
**default**
Error information if the request did not succeed
put/3/employees/{EmployeeId}
Default server
https://api.fortnox.se/3/employees/{EmployeeId}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Employee": {
    * "Address1": "string",
    * "Address2": "string",
    * "AutoNonRecurringTax": true,
    * "AverageHourlyWage": "string",
    * "AverageWeeklyHours": "string",
    * "BankAccountNo": "string",
    * "City": "string",
    * "ClearingNo": "string",
    * "CostCenter": "string",
    * "Country": "string",
    * "DatedSchedules": [
      * {
        * "EmployeeId": "string",
        * "FirstDay": "2019-08-24",
        * "ScheduleId": "string"
}
],
    * "DatedWages": [
      * {
        * "EmployeeId": "string",
        * "FirstDay": "2019-08-24",
        * "HourlyPay": "string",
        * "MonthlySalary": "string"
}
],
    * "Email": "string",
    * "EmployedTo": "2019-08-24",
    * "EmployeeChildren": [
      * {
        * "ApprovedDays": 0,
        * "Child": "string",
        * "EmployeeId": "string",
        * "Id": "string",
        * "IngoingWithdrawnDays": 0,
        * "WithdrawnDays": 0.1
}
],
    * "EmployeeId": "string",
    * "EmploymentDate": "2019-08-24",
    * "EmploymentForm": "TV",
    * "FirstName": "string",
    * "ForaType": "A",
    * "FullName": "string",
    * "HourlyPay": "string",
    * "Inactive": true,
    * "JobTitle": "string",
    * "LastName": "string",
    * "MonthlySalary": "string",
    * "NonRecurringTax": "string",
    * "PersonalIdentityNumber": "string",
    * "PersonelType": "TJM",
    * "Phone1": "string",
    * "Phone2": "string",
    * "PostCode": "string",
    * "Project": "string",
    * "SalaryForm": "MAN",
    * "ScheduleId": "string",
    * "TaxAllowance": "HUV",
    * "TaxColumn": 1,
    * "TaxTable": "string",
    * "VacationDaysPaid": 0.1,
    * "VacationDaysPendingPaid": 0.1,
    * "VacationDaysPendingPrepaid": 0.1,
    * "VacationDaysPendingSaved": 0.1,
    * "VacationDaysPendingSavedYear1": 0.1,
    * "VacationDaysPendingSavedYear2": 0.1,
    * "VacationDaysPendingSavedYear3": 0.1,
    * "VacationDaysPendingSavedYear4": 0.1,
    * "VacationDaysPendingSavedYear5": 0.1,
    * "VacationDaysPendingSavedYear6Plus": 0.1,
    * "VacationDaysPendingUnpaid": 0.1,
    * "VacationDaysPrepaid": 0.1,
    * "VacationDaysRegisteredPaid": 0.1,
    * "VacationDaysRegisteredPrepaid": 0.1,
    * "VacationDaysRegisteredSaved": 0.1,
    * "VacationDaysRegisteredSavedYear1": 0.1,
    * "VacationDaysRegisteredSavedYear2": 0.1,
    * "VacationDaysRegisteredSavedYear3": 0.1,
    * "VacationDaysRegisteredSavedYear4": 0.1,
    * "VacationDaysRegisteredSavedYear5": 0.1,
    * "VacationDaysRegisteredSavedYear6Plus": 0.1,
    * "VacationDaysRegisteredUnpaid": 0.1,
    * "VacationDaysSaved": 0.1,
    * "VacationDaysSavedEmploymentRateYear1": 0.1,
    * "VacationDaysSavedEmploymentRateYear2": 0.1,
    * "VacationDaysSavedEmploymentRateYear3": 0.1,
    * "VacationDaysSavedEmploymentRateYear4": 0.1,
    * "VacationDaysSavedEmploymentRateYear5": 0.1,
    * "VacationDaysSavedEmploymentRateYear6Plus": 0.1,
    * "VacationDaysSavedYear1": 0.1,
    * "VacationDaysSavedYear2": 0.1,
    * "VacationDaysSavedYear3": 0.1,
    * "VacationDaysSavedYear4": 0.1,
    * "VacationDaysSavedYear5": 0.1,
    * "VacationDaysSavedYear6Plus": 0.1,
    * "VacationDaysUnpaid": 0.1
}

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_Expenses)Expenses
Expenses resources
## [](https://api.fortnox.se/apidocs#tag/fortnox_Expenses/operation/list_17)Retrieve expenses 
Retrieve expense codes.
### Responses
**200**
expense
**default**
Error information if the request did not succeed
get/3/expenses
Default server
https://api.fortnox.se/3/expenses
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Expenses": [
    * {
      * "@url": "string",
      * "Account": 0,
      * "Code": "string",
      * "Text": "string"
}
]

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Expenses/operation/create_18)Create an expense 
##### Request Body schema: */*
expense to create
Expense| object (fortnox_Expense)   
---|---  
### Responses
**201**
expense
**default**
Error information if the request did not succeed
post/3/expenses
Default server
https://api.fortnox.se/3/expenses
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Expense": {
    * "Account": 0,
    * "Code": "string",
    * "Text": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Expenses/operation/get_22)Retrieve an expense 
Retrieves expense information for specified expense.
##### path Parameters
ExpenseCoderequired| string expenseCode  
---|---  
### Responses
**200**
list of expenses
**default**
Error information if the request did not succeed
get/3/expenses/{ExpenseCode}
Default server
https://api.fortnox.se/3/expenses/{ExpenseCode}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Expense": {
    * "Account": 0,
    * "Code": "string",
    * "Text": "string"
}

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_FinanceInvoices)Finance Invoices
Fortnox Finans Invoice resources 
These endpoints are useful when transferring an invoice to Fortnox Finans factoring service. When Fortnox Finans has taken over the responsibility for collecting the invoice - the actual invoice, reminders, collections etc (depending on settings) are automatically sent to the customer on the selected media. 
**Important before you start** Please note that you need to get a special sandbox instance of Fortnox to test Fortnox Finans services, if you are using a production sandbox, it will send out invoices and start the reminder process and charge you for the service. 
**Also note** that older invoices (typically dated before 2020-04) might be handled in "Noxbox", a platform previously used for administering invoices sent using Fortnox Finans' services. If this platform has been used for an invoice, some endpoints described below will not be available. In the "Retrieve a Fortnox Finans invoice" section it’s described how to determine if the old "Noxbox" platform was used. 
**Type of services**
A Fortnox user can let Fortnox Finans handle their customer ledger. Fortnox Finans currently offers two types of services 
_Ledgerbase_
Depending on customer settings, two subtypes of the service are available: 
  * Invoice service _with_ automatic reminders: this means that Fortnox Finans is sending invoices to end-customers and handling the customer ledger with reminders and collection. This service is also referred to as "Service Full"
  * Invoice service _without_ automatic reminders: this means that Fortnox Finans is sending invoices to end-customers and handling the customer ledger. No reminders or collections are sent. This service is also referred to as "Service Light"

_Reminder_
  * Reminder service: this means that Fortnox Finans is sending reminders and collections on invoices already sent from Fortnox (without any Fortnox Finans services). The invoice is transferred to Fortnox Finans, and from now on reminders etc will automatically be sent to the customer. The invoice has to be unpaid, and the due date must be passed. An invoice sent by Ledgerbase (without automatic reminders) could be transferred to Reminder service.


**Preconditions**
_General_
Scope of your application registered to Fortnox must contain "Invoice Noxfinans" Fortnox Finans services must have been activated in the client database 
_Invoices_
  * Invoice must have been created in Fortnox (Manually or by API)
  * Invoice must have an open balance >0
  * Invoice date is not allowed to be older than two years
  * Currency of Invoice must be in SEK
  * Invoice contains at least name, address, zip and city
  * Invoice must contain at least one invoice record
  * Interest invoices are not permitted to be sent to Fortnox Finans


_Credit Invoices_
Credit Invoice in Fortnox must have a connection to a debit invoice Debit invoice must have a open balance >= credit invoice amount 
_Authentication_
To be able to use the endpoints, valid authentication must be provided. These are provided by Fortnox Finans when setting up the external api connection. 
An **access token** (in the examples below stated as my_access_token) must be provided in the header of the request. 
A **client secret** (in the examples below stated as my_client_secret) must be provided in the header of the request. 
**Example**
_Request_ curl -X "GET" "<https://api.fortnox.se/3/noxfinansinvoices/7201>" -H "Access-Token: **my_access_token** " -H "Client-Secret: **my_client_secret** " -H "Content-Type: application/json" -H "Accept: application/json"
## [](https://api.fortnox.se/apidocs#tag/fortnox_FinanceInvoices/operation/create_19)Send an invoice with Fortnox Finans 
When sending an invoice with Fortnox Finans you will get the invoice status returned if everything succeeded, if there were any problems, an error will be returned. 
Please note that it can take 1 min to several hours before you will get back status, OCR number and link to PDF document, meanwhile the invoice will have status UNKNOWN or NOT_AUTHORIZED. 
Fortnox Finans is currently only accepting invoices in SEK 
_Parameters in the body:_
  * **InvoiceNumber** : the invoice number for the invoice which should be sent with Fortnox Finans
  * **SendMethod** : how to send the invoice; EMAIL, LETTER, EINVOICE or NONE
  * **Service** : which service to use; LEDGERBASE or REMINDER


##### Request Body schema: */*
The payload for sending an invoice with Fortnox Finans
NoxFinansInvoice| object (fortnox_CreatePayload)   
---|---  
### Responses
**201**
The current status of the invoice _Response parameters:_
  * @url: the URL used to retrieve the invoice status
  * BalanceIncludeFees: the current balance of the invoice, fees included (in SEK)
  * BalanceIncludeFeesCurrency: the current balance of the invoice, fees included, in other currency (currently only SEK is available)
  * CurrentCapitalBalance: capital amount balance (in SEK)
  * CurrentCapitalBalanceCurrency: capital amount balance in other currency (currently only SEK is available)
  * InvoiceDocumentURL: URL to PDF document for invoice
  * InvoiceNumber: invoice number in Fortnox
  * NextEvent: the next event for the invoice
  * NextEventDate: the date when the next event for the invoice will occur
  * OCRNumber: the OCR number of the invoice
  * Service: the service used for the invoice (LEDGERBASE or REMINDER)
  * ServiceName: the detailed service name used for the invoice (SERVICE_FULL, SERVICE_LIGHT or REMINDER_SERVICE, this field is omitted if the invoice is sent with the old Noxbox service)
  * Status: the current status of the invoice

_status_ can be one of the following: 
  * UNKNOWN: Not yet confirmed by Fortnox Finans
  * NOT_AUTHORIZED: Factoring invoice waiting approval
  * OPEN: invoice is open, and not fully paid yet
  * PAUSED: invoice is paused
  * CLOSED: invoice is closed (fully paid, credited or cancelled)


**default**
Error information if the request did not succeed
post/3/noxfinansinvoices
Default server
https://api.fortnox.se/3/noxfinansinvoices
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "NoxFinansInvoice": {
    * "@url": "string",
    * "BalanceIncludeFees": 0.1,
    * "BalanceIncludeFeesCurrency": 0.1,
    * "CurrentCapitalBalance": 0.1,
    * "CurrentCapitalBalanceCurrency": 0.1,
    * "InvoiceDocumentURL": "string",
    * "InvoiceNumber": 0,
    * "NextEvent": "string",
    * "NextEventDate": "2019-08-24",
    * "OCRNumber": "string",
    * "Service": "string",
    * "ServiceName": "string",
    * "Status": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_FinanceInvoices/operation/get_23)Retrieve a single invoice payment 
Retrieves the status and balance of an invoice sent to Fortnox Finans. You need to supply the invoice number in Fortox to retrieve the invoice. 
**Note that** invoices sent with the old "Noxbox" platform will not have the "ServiceName" property in the response. This new property is added to the response if the invoice is sent with the new finance service. 
Response explanation for **Service** and **ServiceName**
**Service:**
  * **LEDGERBASE** : if the invoice is sent by using the old "Noxbox" platform, or the new finance service with the subtypes "Service Full" or "Service Light". These services are explained above in the "Fortnox Finans services" section
  * **REMINDER** : If the invoice is sent by the new finance service, with the service Reminder Service


**ServiceName** (only provided for _new finance service_ invoices): 
  * **SERVICE_FULL** : Ledgerbase service _with_ automatic reminders is used
  * **SERVICE_LIGHT** : Ledgerbase service _without_ automatic reminders is used.
  * **REMINDER_SERVICE** : Reminder service is used


##### path Parameters
Numberrequired| string The Fortnox invoice number  
---|---  
### Responses
**200**
The current status of the invoice _Response parameters:_
  * @url: the URL used to retrieve the invoice status
  * BalanceIncludeFees: the current balance of the invoice, fees included (in SEK)
  * BalanceIncludeFeesCurrency: the current balance of the invoice, fees included, in other currency (currently only SEK is available)
  * CurrentCapitalBalance: capital amount balance (in SEK)
  * CurrentCapitalBalanceCurrency: capital amount balance in other currency (currently only SEK is available)
  * InvoiceDocumentURL: URL to PDF document for invoice
  * InvoiceNumber: invoice number in Fortnox
  * NextEvent: the next event for the invoice
  * NextEventDate: the date when the next event for the invoice will occur
  * OCRNumber: the OCR number of the invoice
  * Service: the service used for the invoice (LEDGERBASE or REMINDER)
  * ServiceName: the detailed service name used for the invoice (SERVICE_FULL, SERVICE_LIGHT or REMINDER_SERVICE, this field is omitted if the invoice is sent with the old Noxbox service)
  * Status: the current status of the invoice

_status_ can be one of the following: 
  * UNKNOWN: Not yet confirmed by Fortnox Finans
  * NOT_AUTHORIZED: Factoring invoice waiting approval
  * OPEN: invoice is open, and not fully paid yet
  * PAUSED: invoice is paused
  * CLOSED: invoice is closed (fully paid, credited or cancelled)


**default**
Error information if the request did not succeed
get/3/noxfinansinvoices/{Number}
Default server
https://api.fortnox.se/3/noxfinansinvoices/{Number}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "NoxFinansInvoice": {
    * "@url": "string",
    * "BalanceIncludeFees": 0.1,
    * "BalanceIncludeFeesCurrency": 0.1,
    * "CurrentCapitalBalance": 0.1,
    * "CurrentCapitalBalanceCurrency": 0.1,
    * "InvoiceDocumentURL": "string",
    * "InvoiceNumber": 0,
    * "NextEvent": "string",
    * "NextEventDate": "2019-08-24",
    * "OCRNumber": "string",
    * "Service": "string",
    * "ServiceName": "string",
    * "Status": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_FinanceInvoices/operation/pause)Action Pause 
Pauses an invoice for up to 60 days. Pause means that Fortnox Finans reminder process will stop for the invoice. All invoices which have the status OPEN can be paused. 
**Note:** this action is **not** available for invoices sent by the old Noxbox platform 
_Parameters in the body:_
  * **PausedUntilDate** : the invoice will be paused to and including this date.


##### path Parameters
Numberrequired| string The Fortnox invoice number  
---|---  
##### Request Body schema: */*
The payload for sending an invoice with Fortnox Finans
NoxFinansInvoice| object (fortnox_PausePayload)   
---|---  
### Responses
**200**
The current status of the invoice _Response parameters:_
  * @url: the URL used to retrieve the invoice status
  * BalanceIncludeFees: the current balance of the invoice, fees included (in SEK)
  * BalanceIncludeFeesCurrency: the current balance of the invoice, fees included, in other currency (currently only SEK is available)
  * CurrentCapitalBalance: capital amount balance (in SEK)
  * CurrentCapitalBalanceCurrency: capital amount balance in other currency (currently only SEK is available)
  * InvoiceDocumentURL: URL to PDF document for invoice
  * InvoiceNumber: invoice number in Fortnox
  * NextEvent: the next event for the invoice
  * NextEventDate: the date when the next event for the invoice will occur
  * OCRNumber: the OCR number of the invoice
  * Service: the service used for the invoice (LEDGERBASE or REMINDER)
  * ServiceName: the detailed service name used for the invoice (SERVICE_FULL, SERVICE_LIGHT or REMINDER_SERVICE, this field is omitted if the invoice is sent with the old Noxbox service)
  * Status: the current status of the invoice

_status_ can be one of the following: 
  * UNKNOWN: Not yet confirmed by Fortnox Finans
  * NOT_AUTHORIZED: Factoring invoice waiting approval
  * OPEN: invoice is open, and not fully paid yet
  * PAUSED: invoice is paused
  * CLOSED: invoice is closed (fully paid, credited or cancelled)


**default**
Error information if the request did not succeed
put/3/noxfinansinvoices/{Number}/pause
Default server
https://api.fortnox.se/3/noxfinansinvoices/{Number}/pause
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "NoxFinansInvoice": {
    * "@url": "string",
    * "BalanceIncludeFees": 0.1,
    * "BalanceIncludeFeesCurrency": 0.1,
    * "CurrentCapitalBalance": 0.1,
    * "CurrentCapitalBalanceCurrency": 0.1,
    * "InvoiceDocumentURL": "string",
    * "InvoiceNumber": 0,
    * "NextEvent": "string",
    * "NextEventDate": "2019-08-24",
    * "OCRNumber": "string",
    * "Service": "string",
    * "ServiceName": "string",
    * "Status": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_FinanceInvoices/operation/reportPayment)Action Report Payment 
If a customer has paid some or all of the capital on an invoice directly to the client, this can be reported for bookkeeping purposes and reported to Fortnox Finans to actually deduct the paid amount from the invoice. 
**Note:** this action is **not** available for invoices sent by the old Noxbox platform 
_Parameters in the body:_
  * **PaymentAmount** : a decimal field with the amount to report.
  * **PaymentMethodCode** : a string with the method code (e.g. BG, PG or other). Could be omitted if BookkeepPaymentInFortnox is false.
  * **PaymentMethodAccount** : an integer with the account number to bookkeep the payment on (e.g. 1920 or other). Could be omitted if BookkeepPaymentInFortnox is false.
  * **ClientTakesFees** : a boolean indicating if the client should take the customer fees or not.
  * **BookkeepPaymentInFortnox** : a boolean indicating if the payment should be bookkept in Fortnox or not. Usually the payment should be bookkept.
  * **ReportToFinance** : a boolean indicating if the payment should be reported to Fortnox Finans or not. Usually the payment should be reported.


##### path Parameters
Numberrequired| string The Fortnox invoice number  
---|---  
##### Request Body schema: */*
The payload for sending an invoice with Fortnox Finans
NoxFinansInvoice| object (fortnox_ReportPaymentPayload)   
---|---  
### Responses
**200**
The current status of the invoice _Response parameters:_
  * @url: the URL used to retrieve the invoice status
  * BalanceIncludeFees: the current balance of the invoice, fees included (in SEK)
  * BalanceIncludeFeesCurrency: the current balance of the invoice, fees included, in other currency (currently only SEK is available)
  * CurrentCapitalBalance: capital amount balance (in SEK)
  * CurrentCapitalBalanceCurrency: capital amount balance in other currency (currently only SEK is available)
  * InvoiceDocumentURL: URL to PDF document for invoice
  * InvoiceNumber: invoice number in Fortnox
  * NextEvent: the next event for the invoice
  * NextEventDate: the date when the next event for the invoice will occur
  * OCRNumber: the OCR number of the invoice
  * Service: the service used for the invoice (LEDGERBASE or REMINDER)
  * ServiceName: the detailed service name used for the invoice (SERVICE_FULL, SERVICE_LIGHT or REMINDER_SERVICE, this field is omitted if the invoice is sent with the old Noxbox service)
  * Status: the current status of the invoice

_status_ can be one of the following: 
  * UNKNOWN: Not yet confirmed by Fortnox Finans
  * NOT_AUTHORIZED: Factoring invoice waiting approval
  * OPEN: invoice is open, and not fully paid yet
  * PAUSED: invoice is paused
  * CLOSED: invoice is closed (fully paid, credited or cancelled)


**default**
Error information if the request did not succeed
put/3/noxfinansinvoices/{Number}/report-payment
Default server
https://api.fortnox.se/3/noxfinansinvoices/{Number}/report-payment
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "NoxFinansInvoice": {
    * "@url": "string",
    * "BalanceIncludeFees": 0.1,
    * "BalanceIncludeFeesCurrency": 0.1,
    * "CurrentCapitalBalance": 0.1,
    * "CurrentCapitalBalanceCurrency": 0.1,
    * "InvoiceDocumentURL": "string",
    * "InvoiceNumber": 0,
    * "NextEvent": "string",
    * "NextEventDate": "2019-08-24",
    * "OCRNumber": "string",
    * "Service": "string",
    * "ServiceName": "string",
    * "Status": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_FinanceInvoices/operation/stop)Action Stop 
Removes the invoice from Fortnox Finans process. The invoice can still be handled manually, but no further automatic process will be applied 
**Note:** this action is **not** available for invoices sent by the old Noxbox platform
##### path Parameters
Numberrequired| string The Fortnox invoice number  
---|---  
### Responses
**200**
The current status of the invoice
**default**
Error information if the request did not succeed
put/3/noxfinansinvoices/{Number}/stop
Default server
https://api.fortnox.se/3/noxfinansinvoices/{Number}/stop
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "NoxFinansInvoice": {
    * "@url": "string",
    * "BalanceIncludeFees": 0.1,
    * "BalanceIncludeFeesCurrency": 0.1,
    * "CurrentCapitalBalance": 0.1,
    * "CurrentCapitalBalanceCurrency": 0.1,
    * "InvoiceDocumentURL": "string",
    * "InvoiceNumber": 0,
    * "NextEvent": "string",
    * "NextEventDate": "2019-08-24",
    * "OCRNumber": "string",
    * "Service": "string",
    * "ServiceName": "string",
    * "Status": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_FinanceInvoices/operation/takeFees)Action Take Fees 
If fees have been added to an invoice, e.g. reminder fees, the client can choose to pay those fees instead of letting the customer pay. 
**Note:** this action is **not** available for invoices sent by the old Noxbox platform
##### path Parameters
Numberrequired| string The Fortnox invoice number  
---|---  
### Responses
**200**
The current status of the invoice _Response parameters:_
  * @url: the URL used to retrieve the invoice status
  * BalanceIncludeFees: the current balance of the invoice, fees included (in SEK)
  * BalanceIncludeFeesCurrency: the current balance of the invoice, fees included, in other currency (currently only SEK is available)
  * CurrentCapitalBalance: capital amount balance (in SEK)
  * CurrentCapitalBalanceCurrency: capital amount balance in other currency (currently only SEK is available)
  * InvoiceDocumentURL: URL to PDF document for invoice
  * InvoiceNumber: invoice number in Fortnox
  * NextEvent: the next event for the invoice
  * NextEventDate: the date when the next event for the invoice will occur
  * OCRNumber: the OCR number of the invoice
  * Service: the service used for the invoice (LEDGERBASE or REMINDER)
  * ServiceName: the detailed service name used for the invoice (SERVICE_FULL, SERVICE_LIGHT or REMINDER_SERVICE, this field is omitted if the invoice is sent with the old Noxbox service)
  * Status: the current status of the invoice

_status_ can be one of the following: 
  * UNKNOWN: Not yet confirmed by Fortnox Finans
  * NOT_AUTHORIZED: Factoring invoice waiting approval
  * OPEN: invoice is open, and not fully paid yet
  * PAUSED: invoice is paused
  * CLOSED: invoice is closed (fully paid, credited or cancelled)


**default**
Error information if the request did not succeed
put/3/noxfinansinvoices/{Number}/take-fees
Default server
https://api.fortnox.se/3/noxfinansinvoices/{Number}/take-fees
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "NoxFinansInvoice": {
    * "@url": "string",
    * "BalanceIncludeFees": 0.1,
    * "BalanceIncludeFeesCurrency": 0.1,
    * "CurrentCapitalBalance": 0.1,
    * "CurrentCapitalBalanceCurrency": 0.1,
    * "InvoiceDocumentURL": "string",
    * "InvoiceNumber": 0,
    * "NextEvent": "string",
    * "NextEventDate": "2019-08-24",
    * "OCRNumber": "string",
    * "Service": "string",
    * "ServiceName": "string",
    * "Status": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_FinanceInvoices/operation/unpause)Action Unpause 
Unpauses a paused invoice. If the invoice is manually paused, then this action will remove the pause status immediately. Invoices which are paused by the system cannot be unpaused. 
**Note:** this action is **not** available for invoices sent by the old Noxbox platform
##### path Parameters
Numberrequired| string The Fortnox invoice number  
---|---  
### Responses
**200**
The current status of the invoice _Response parameters:_
  * @url: the URL used to retrieve the invoice status
  * BalanceIncludeFees: the current balance of the invoice, fees included (in SEK)
  * BalanceIncludeFeesCurrency: the current balance of the invoice, fees included, in other currency (currently only SEK is available)
  * CurrentCapitalBalance: capital amount balance (in SEK)
  * CurrentCapitalBalanceCurrency: capital amount balance in other currency (currently only SEK is available)
  * InvoiceDocumentURL: URL to PDF document for invoice
  * InvoiceNumber: invoice number in Fortnox
  * NextEvent: the next event for the invoice
  * NextEventDate: the date when the next event for the invoice will occur
  * OCRNumber: the OCR number of the invoice
  * Service: the service used for the invoice (LEDGERBASE or REMINDER)
  * ServiceName: the detailed service name used for the invoice (SERVICE_FULL, SERVICE_LIGHT or REMINDER_SERVICE, this field is omitted if the invoice is sent with the old Noxbox service)
  * Status: the current status of the invoice

_status_ can be one of the following: 
  * UNKNOWN: Not yet confirmed by Fortnox Finans
  * NOT_AUTHORIZED: Factoring invoice waiting approval
  * OPEN: invoice is open, and not fully paid yet
  * PAUSED: invoice is paused
  * CLOSED: invoice is closed (fully paid, credited or cancelled)


**default**
Error information if the request did not succeed
put/3/noxfinansinvoices/{Number}/unpause
Default server
https://api.fortnox.se/3/noxfinansinvoices/{Number}/unpause
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "NoxFinansInvoice": {
    * "@url": "string",
    * "BalanceIncludeFees": 0.1,
    * "BalanceIncludeFeesCurrency": 0.1,
    * "CurrentCapitalBalance": 0.1,
    * "CurrentCapitalBalanceCurrency": 0.1,
    * "InvoiceDocumentURL": "string",
    * "InvoiceNumber": 0,
    * "NextEvent": "string",
    * "NextEventDate": "2019-08-24",
    * "OCRNumber": "string",
    * "Service": "string",
    * "ServiceName": "string",
    * "Status": "string"
}

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_FinancialYears)Financial Years
Financial years resources
## [](https://api.fortnox.se/apidocs#tag/fortnox_FinancialYears/operation/getByDate)Retrieve a list of financial years 
Add the query param to filter on specific date.
##### query Parameters
Date| string <date> date to filter on, for example 2020-06-30  
---|---  
### Responses
**200**
the existing financial year
**default**
Error information if the request did not succeed
get/3/financialyears
Default server
https://api.fortnox.se/3/financialyears
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "FinancialYears": [
    * {
      * "@url": "string",
      * "AccountChartType": "string",
      * "AccountingMethod": "ACCRUAL",
      * "FromDate": "2019-08-24",
      * "Id": 0,
      * "ToDate": "2019-08-24"
}
]

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_FinancialYears/operation/create_20)Create a financial year 
##### Request Body schema: */*
to create
FinancialYearrequired| object (fortnox_FinancialYear)   
---|---  
### Responses
**201**
the created year
**default**
Error information if the request did not succeed
post/3/financialyears
Default server
https://api.fortnox.se/3/financialyears
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "FinancialYear": {
    * "@url": "string",
    * "AccountChartType": "string",
    * "AccountingMethod": "ACCRUAL",
    * "FromDate": "2019-08-24",
    * "Id": 0,
    * "ToDate": "2019-08-24"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_FinancialYears/operation/getById)Retrieve financial year by id 
##### path Parameters
Idrequired| integer <int32> identifies the year  
---|---  
### Responses
**200**
the existing financial year
**default**
Error information if the request did not succeed
get/3/financialyears/{Id}
Default server
https://api.fortnox.se/3/financialyears/{Id}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "FinancialYear": {
    * "@url": "string",
    * "AccountChartType": "string",
    * "AccountingMethod": "ACCRUAL",
    * "FromDate": "2019-08-24",
    * "Id": 0,
    * "ToDate": "2019-08-24"
}

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_Inbox)Inbox
Note that Inbox has nine static folders in the root directory. **Path**| **Description**  
---|---  
Inbox_a| Asset register  
Inbox_d| Daily takings  
Inbox_s| Supplier invoices  
Inbox_v| Vouchers  
Inbox_b| Bank files  
Inbox_l| Payroll files  
Inbox_kf| Customer invoices  
Inbox_o| Orders  
Inbox_of| Offers  
## [](https://api.fortnox.se/apidocs#tag/fortnox_Inbox/operation/get_24)Retrieve the root folder containing files and folders 
### Responses
**200**
the root folder
**default**
Error information if the request did not succeed
get/3/inbox
Default server
https://api.fortnox.se/3/inbox
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Folder": {
    * "@url": "string",
    * "Email": "string",
    * "Files": [
      * {
        * "@url": "string",
        * "ArchiveFileId": "string",
        * "Comments": "string",
        * "Id": "string",
        * "Name": "string",
        * "Path": "string",
        * "Size": 0
}
],
    * "Folders": [
      * {
        * "@url": "string",
        * "Id": "string",
        * "Name": "string"
}
],
    * "Id": "string",
    * "Name": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Inbox/operation/upload)Upload a file 
Upload a file to a specific subdirectory.
##### query Parameters
folderId| string folder id  
---|---  
path| string path  
##### Request Body schema: multipart/form-data
file| object file  
---|---  
### Responses
**201**
file file
**default**
Error information if the request did not succeed
post/3/inbox
Default server
https://api.fortnox.se/3/inbox
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "File": {
    * "@url": "string",
    * "ArchiveFileId": "string",
    * "Comments": "string",
    * "Id": "string",
    * "Name": "string",
    * "Path": "string",
    * "Size": 0
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Inbox/operation/remove_11)Remove a file or folder 
##### path Parameters
Idrequired| string identifies the file to remove  
---|---  
### Responses
**204**
Successfully removed the specified resource.
**default**
Error information if the request did not succeed
delete/3/inbox/{Id}
Default server
https://api.fortnox.se/3/inbox/{Id}
###  Response samples 
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ErrorInformation": {
    * "Code": 0,
    * "Error": 0,
    * "Message": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Inbox/operation/getFileById_1)Retrieve a single file 
##### path Parameters
Idrequired| string identifies the folder  
---|---  
### Responses
**200**
a single file
**default**
Error information if the request did not succeed
get/3/inbox/{Id}
Default server
https://api.fortnox.se/3/inbox/{Id}
# [](https://api.fortnox.se/apidocs#tag/fortnox_InvoiceAccruals)Invoice Accruals
Resource for CRUD operations on Invoice Accruals
## [](https://api.fortnox.se/apidocs#tag/fortnox_InvoiceAccruals/operation/list_18)Retrieve a list of invoice accruals 
The invoice accruals register can return a list of records or a single record. By specifying a InvoiceNumber in the URL, a single record will be returned. Not specifying a InvoiceNumber will return a list of records.
### Responses
**200**
list of invoice accruals
**default**
Error information if the request did not succeed
get/3/invoiceaccruals
Default server
https://api.fortnox.se/3/invoiceaccruals
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "InvoiceAccruals": [
    * {
      * "@url": "string",
      * "Description": "string",
      * "InvoiceNumber": 0,
      * "Period": "MONTHLY"
}
]

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_InvoiceAccruals/operation/create_21)Create an invoice accrual 
##### Request Body schema: */*
invoice accrual to create
InvoiceAccrual| object (fortnox_InvoiceAccrual)   
---|---  
### Responses
**201**
the created invoice accrual
**default**
Error information if the request did not succeed
post/3/invoiceaccruals
Default server
https://api.fortnox.se/3/invoiceaccruals
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "InvoiceAccrual": {
    * "@url": "string",
    * "AccrualAccount": 1000,
    * "Description": "string",
    * "EndDate": "2019-08-24",
    * "InvoiceAccrualRows": [
      * {
        * "Account": 0,
        * "CostCenter": "string",
        * "Credit": 0.1,
        * "Debit": 0.1,
        * "Project": "string",
        * "TransactionInformation": "string"
},
      * {
        * "Account": 0,
        * "CostCenter": "string",
        * "Credit": 0.1,
        * "Debit": 0.1,
        * "Project": "string",
        * "TransactionInformation": "string"
}
],
    * "InvoiceNumber": 0,
    * "Period": "MONTHLY",
    * "RevenueAccount": 1000,
    * "StartDate": "2019-08-24",
    * "Times": 0,
    * "Total": 0.1,
    * "VATIncluded": true
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_InvoiceAccruals/operation/remove_12)Remove an invoice accrual 
##### path Parameters
InvoiceNumberrequired| integer <int32> identifies the invoice accrual  
---|---  
### Responses
**204**
Successfully removed the specified resource.
**default**
Error information if the request did not succeed
delete/3/invoiceaccruals/{InvoiceNumber}
Default server
https://api.fortnox.se/3/invoiceaccruals/{InvoiceNumber}
###  Response samples 
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ErrorInformation": {
    * "Code": 0,
    * "Error": 0,
    * "Message": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_InvoiceAccruals/operation/get_25)Retrieve a single invoice accrual 
##### path Parameters
InvoiceNumberrequired| integer <int32> identifies the invoice accrual  
---|---  
### Responses
**200**
the existing invoice accrual
**default**
Error information if the request did not succeed
get/3/invoiceaccruals/{InvoiceNumber}
Default server
https://api.fortnox.se/3/invoiceaccruals/{InvoiceNumber}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "InvoiceAccrual": {
    * "@url": "string",
    * "AccrualAccount": 1000,
    * "Description": "string",
    * "EndDate": "2019-08-24",
    * "InvoiceAccrualRows": [
      * {
        * "Account": 0,
        * "CostCenter": "string",
        * "Credit": 0.1,
        * "Debit": 0.1,
        * "Project": "string",
        * "TransactionInformation": "string"
},
      * {
        * "Account": 0,
        * "CostCenter": "string",
        * "Credit": 0.1,
        * "Debit": 0.1,
        * "Project": "string",
        * "TransactionInformation": "string"
}
],
    * "InvoiceNumber": 0,
    * "Period": "MONTHLY",
    * "RevenueAccount": 1000,
    * "StartDate": "2019-08-24",
    * "Times": 0,
    * "Total": 0.1,
    * "VATIncluded": true
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_InvoiceAccruals/operation/update_16)Update an invoice accrual 
##### path Parameters
InvoiceNumberrequired| integer <int32> identifies the invoice accrual  
---|---  
##### Request Body schema: */*
invoice accrual to update
InvoiceAccrual| object (fortnox_InvoiceAccrual)   
---|---  
### Responses
**200**
the updated invoice accrual
**default**
Error information if the request did not succeed
put/3/invoiceaccruals/{InvoiceNumber}
Default server
https://api.fortnox.se/3/invoiceaccruals/{InvoiceNumber}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "InvoiceAccrual": {
    * "@url": "string",
    * "AccrualAccount": 1000,
    * "Description": "string",
    * "EndDate": "2019-08-24",
    * "InvoiceAccrualRows": [
      * {
        * "Account": 0,
        * "CostCenter": "string",
        * "Credit": 0.1,
        * "Debit": 0.1,
        * "Project": "string",
        * "TransactionInformation": "string"
},
      * {
        * "Account": 0,
        * "CostCenter": "string",
        * "Credit": 0.1,
        * "Debit": 0.1,
        * "Project": "string",
        * "TransactionInformation": "string"
}
],
    * "InvoiceNumber": 0,
    * "Period": "MONTHLY",
    * "RevenueAccount": 1000,
    * "StartDate": "2019-08-24",
    * "Times": 0,
    * "Total": 0.1,
    * "VATIncluded": true
}

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_InvoicePayments)Invoice Payments
Invoice payments resources
## [](https://api.fortnox.se/apidocs#tag/fortnox_InvoicePayments/operation/list_19)Retrieve a list of invoice payments 
##### query Parameters
invoicenumber| integer <int32> filter by invoice number  
---|---  
lastmodified| string filter by last modified  
sortby| string Value: "paymentdate" field to sort returned list on  
### Responses
**200**
list of invoice payments
**default**
Error information if the request did not succeed
get/3/invoicepayments
Default server
https://api.fortnox.se/3/invoicepayments
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "InvoicePayments": [
    * {
      * "@url": "string",
      * "Amount": 0.1,
      * "Booked": true,
      * "Currency": "str",
      * "CurrencyRate": 0.1,
      * "CurrencyUnit": 0.1,
      * "InvoiceNumber": 0,
      * "Number": "string",
      * "PaymentDate": "2019-08-24",
      * "Source": "string",
      * "WriteOffExist": true
}
]

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_InvoicePayments/operation/create_22)Create an invoice payment 
##### Request Body schema: */*
invoice payment to create
InvoicePayment| object (fortnox_InvoicePayment)   
---|---  
### Responses
**201**
the created invoice payment
**default**
Error information if the request did not succeed
post/3/invoicepayments
Default server
https://api.fortnox.se/3/invoicepayments
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "InvoicePayment": {
    * "@url": "string",
    * "Amount": 0.1,
    * "AmountCurrency": 0.1,
    * "Booked": true,
    * "Currency": "str",
    * "CurrencyRate": 0.1,
    * "CurrencyUnit": 0.1,
    * "ExternalInvoiceReference1": "string",
    * "ExternalInvoiceReference2": "string",
    * "InvoiceCustomerName": "string",
    * "InvoiceCustomerNumber": "string",
    * "InvoiceDueDate": "2019-08-24",
    * "InvoiceNumber": 0,
    * "InvoiceOCR": "string",
    * "InvoiceTotal": "string",
    * "ModeOfPayment": "string",
    * "ModeOfPaymentAccount": 1000,
    * "Number": "string",
    * "PaymentDate": "2019-08-24",
    * "Source": "string",
    * "VoucherNumber": 0,
    * "VoucherSeries": "string",
    * "VoucherYear": 0,
    * "WriteOffs": [
      * {
        * "AccountNumber": 1000,
        * "Amount": 0.1,
        * "CostCenter": "string",
        * "Currency": "str",
        * "Description": "string",
        * "Project": "string",
        * "TransactionInformation": "string"
}
]
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_InvoicePayments/operation/remove_13)Remove an invoice payment 
##### path Parameters
Numberrequired| string identifies the invoice payment  
---|---  
### Responses
**204**
Successfully removed the specified resource.
**default**
Error information if the request did not succeed
delete/3/invoicepayments/{Number}
Default server
https://api.fortnox.se/3/invoicepayments/{Number}
###  Response samples 
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ErrorInformation": {
    * "Code": 0,
    * "Error": 0,
    * "Message": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_InvoicePayments/operation/get_26)Retrieve a single invoice payment 
##### path Parameters
Numberrequired| string identifies the invoice payment  
---|---  
### Responses
**200**
the existing invoice payment
**default**
Error information if the request did not succeed
get/3/invoicepayments/{Number}
Default server
https://api.fortnox.se/3/invoicepayments/{Number}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "InvoicePayment": {
    * "@url": "string",
    * "Amount": 0.1,
    * "AmountCurrency": 0.1,
    * "Booked": true,
    * "Currency": "str",
    * "CurrencyRate": 0.1,
    * "CurrencyUnit": 0.1,
    * "ExternalInvoiceReference1": "string",
    * "ExternalInvoiceReference2": "string",
    * "InvoiceCustomerName": "string",
    * "InvoiceCustomerNumber": "string",
    * "InvoiceDueDate": "2019-08-24",
    * "InvoiceNumber": 0,
    * "InvoiceOCR": "string",
    * "InvoiceTotal": "string",
    * "ModeOfPayment": "string",
    * "ModeOfPaymentAccount": 1000,
    * "Number": "string",
    * "PaymentDate": "2019-08-24",
    * "Source": "string",
    * "VoucherNumber": 0,
    * "VoucherSeries": "string",
    * "VoucherYear": 0,
    * "WriteOffs": [
      * {
        * "AccountNumber": 1000,
        * "Amount": 0.1,
        * "CostCenter": "string",
        * "Currency": "str",
        * "Description": "string",
        * "Project": "string",
        * "TransactionInformation": "string"
}
]
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_InvoicePayments/operation/update_17)Update an invoice payment 
##### path Parameters
Numberrequired| string identifies the invoice payment  
---|---  
##### Request Body schema: */*
invoice payment to update
InvoicePayment| object (fortnox_InvoicePayment)   
---|---  
### Responses
**200**
the updated invoice payment
**default**
Error information if the request did not succeed
put/3/invoicepayments/{Number}
Default server
https://api.fortnox.se/3/invoicepayments/{Number}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "InvoicePayment": {
    * "@url": "string",
    * "Amount": 0.1,
    * "AmountCurrency": 0.1,
    * "Booked": true,
    * "Currency": "str",
    * "CurrencyRate": 0.1,
    * "CurrencyUnit": 0.1,
    * "ExternalInvoiceReference1": "string",
    * "ExternalInvoiceReference2": "string",
    * "InvoiceCustomerName": "string",
    * "InvoiceCustomerNumber": "string",
    * "InvoiceDueDate": "2019-08-24",
    * "InvoiceNumber": 0,
    * "InvoiceOCR": "string",
    * "InvoiceTotal": "string",
    * "ModeOfPayment": "string",
    * "ModeOfPaymentAccount": 1000,
    * "Number": "string",
    * "PaymentDate": "2019-08-24",
    * "Source": "string",
    * "VoucherNumber": 0,
    * "VoucherSeries": "string",
    * "VoucherYear": 0,
    * "WriteOffs": [
      * {
        * "AccountNumber": 1000,
        * "Amount": 0.1,
        * "CostCenter": "string",
        * "Currency": "str",
        * "Description": "string",
        * "Project": "string",
        * "TransactionInformation": "string"
}
]
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_InvoicePayments/operation/bookkeep)Bookkeep an invoice payment 
##### path Parameters
Numberrequired| string identifies the invoice payment  
---|---  
##### Request Body schema: */*
invoice payment to update
InvoicePayment| object (fortnox_InvoicePayment)   
---|---  
### Responses
**200**
the updated invoice payment
**default**
Error information if the request did not succeed
put/3/invoicepayments/{Number}/bookkeep
Default server
https://api.fortnox.se/3/invoicepayments/{Number}/bookkeep
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "InvoicePayment": {
    * "@url": "string",
    * "Amount": 0.1,
    * "AmountCurrency": 0.1,
    * "Booked": true,
    * "Currency": "str",
    * "CurrencyRate": 0.1,
    * "CurrencyUnit": 0.1,
    * "ExternalInvoiceReference1": "string",
    * "ExternalInvoiceReference2": "string",
    * "InvoiceCustomerName": "string",
    * "InvoiceCustomerNumber": "string",
    * "InvoiceDueDate": "2019-08-24",
    * "InvoiceNumber": 0,
    * "InvoiceOCR": "string",
    * "InvoiceTotal": "string",
    * "ModeOfPayment": "string",
    * "ModeOfPaymentAccount": 1000,
    * "Number": "string",
    * "PaymentDate": "2019-08-24",
    * "Source": "string",
    * "VoucherNumber": 0,
    * "VoucherSeries": "string",
    * "VoucherYear": 0,
    * "WriteOffs": [
      * {
        * "AccountNumber": 1000,
        * "Amount": 0.1,
        * "CostCenter": "string",
        * "Currency": "str",
        * "Description": "string",
        * "Project": "string",
        * "TransactionInformation": "string"
}
]
}

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_Invoices)Invoices
**Note!** if you are sending the invoice with Fortnox Finans, check out the [Finance Invoices](https://api.fortnox.se/apidocs#tag/FinanceInvoicesResource) section
Possible filters on Invoice endpoint **Filter** | **Description**  
---|---  
cancelled | Retrieves all invoices with the status "cancelled".  
fullypaid | Retrieves all invoices that has been fully paid.  
unpaid | Retrieves all invoices that is unpaid.  
unpaidoverdue | Retrieves all invoices that is unpaid and overdue.  
unbooked | Retrieves all invoices that is unbooked.  
## [](https://api.fortnox.se/apidocs#tag/fortnox_Invoices/operation/list_20)Retrieve a list of invoices 
##### query Parameters
filter| string Enum: "cancelled" "fullypaid" "unpaid" "unpaidoverdue" "unbooked" possibility to filter invoices  
---|---  
costcenter| string  
customername| string  
customernumber| string  
label| string  
documentnumber| string  
fromdate| string  
todate| string  
fromfinalpaydate| string  
tofinalpaydate| string  
lastmodified| string  
notcompleted| string  
ocr| string  
ourreference| string  
project| string  
sent| string  
externalinvoicereference1| string  
externalinvoicereference2| string  
yourreference| string  
invoicetype| string  
articlenumber| string  
articledescription| string  
currency| string  
accountnumberfrom| string  
accountnumberto| string  
yourordernumber| string  
credit| string  
sortby| string Enum: "customername" "customernumber" "documentnumber" "invoicedate" "ocr" "total" field to sort returned list on  
### Responses
**200**
list of invoices
**default**
Error information if the request did not succeed
get/3/invoices
Default server
https://api.fortnox.se/3/invoices
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Invoices": [
    * {
      * "@url": "string",
      * "Balance": 0.1,
      * "Booked": true,
      * "Cancelled": true,
      * "CostCenter": "string",
      * "Currency": "string",
      * "CurrencyRate": 0.1,
      * "CurrencyUnit": 0.1,
      * "CustomerName": "string",
      * "CustomerNumber": "string",
      * "DocumentNumber": "string",
      * "DueDate": "2019-08-24",
      * "ExternalInvoiceReference1": "string",
      * "ExternalInvoiceReference2": "string",
      * "FinalPayDate": "2019-08-24",
      * "InvoiceDate": "2019-08-24",
      * "InvoiceType": "INVOICE",
      * "NoxFinans": true,
      * "OCR": "string",
      * "Project": "string",
      * "Sent": true,
      * "TermsOfPayment": "string",
      * "Total": 0.1,
      * "VoucherNumber": 0,
      * "VoucherSeries": "string",
      * "VoucherYear": 0,
      * "WayOfDelivery": "string"
}
]

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Invoices/operation/create_23)Create an invoice 
An endpoint for creating an invoice. While it is possible to create an invoice without rows, we encourage you to add them if you can. Omitted values in the payload will be supplied by Predefined values which can be edited in the Fortnox account settings. Note that Predefined values will always be overwritten by values provided through the API.
Should you have EasyVat enabled, it is mandatory to provide an account in the request should you use a custom VAT rate.
This endpoint can produce errors, some of which may only be relevant for EasyVat. Refer to the table below. 
Errors that can be raised by this endpoint. Error Code | HTTP Code | Description | Solution  
---|---|---|---  
2004167 | 400 | An account must be provided when using a custom VAT rate and EasyVat has been enabled. | Supply each row which has a custom VAT rate with an account.  
Note: The **EuQuarterlyReport** property will become obsolete at 2021-12-01. This property is currently used by the **Quarterly** report as one of the conditions that determine if an invoice should be included in the report or not. A new version of the **Quarterly** report is released at 2021-12-01. In the new report, this property will not be used when determining if an invoice should be included in the report or not, with one exception: if the invoice is created before 2021-12-01, and this property is false, the invoice will be excluded from the report. For invoices created 2021-12-01 and later, this property will have no effect.
##### Request Body schema: */*
payload
Invoice| object (fortnox_InvoicePayload)   
---|---  
### Responses
**201**
the created invoice
**default**
Error information if the request did not succeed
post/3/invoices
Default server
https://api.fortnox.se/3/invoices
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Invoice": {
    * "@url": "string",
    * "@urlTaxReductionList": "string",
    * "AccountingMethod": "ACCRUAL",
    * "Address1": "string",
    * "Address2": "string",
    * "AdministrationFee": 0.1,
    * "AdministrationFeeVAT": 0.1,
    * "Balance": 0.1,
    * "BasisTaxReduction": 0.1,
    * "Booked": true,
    * "Cancelled": true,
    * "City": "string",
    * "Comments": "string",
    * "ContractReference": 0,
    * "ContributionPercent": 0.1,
    * "ContributionValue": 0.1,
    * "CostCenter": "string",
    * "Country": "string",
    * "Credit": "string",
    * "CreditInvoiceReference": "string",
    * "Currency": "string",
    * "CurrencyRate": 0.1,
    * "CurrencyUnit": 0,
    * "CustomerName": "string",
    * "CustomerNumber": "string",
    * "DeliveryAddress1": "string",
    * "DeliveryAddress2": "string",
    * "DeliveryCity": "string",
    * "DeliveryCountry": "string",
    * "DeliveryDate": "2019-08-24",
    * "DeliveryName": "string",
    * "DeliveryZipCode": "string",
    * "DocumentNumber": "string",
    * "DueDate": "2019-08-24",
    * "EDIInformation": {
      * "EDIGlobalLocationNumber": "string",
      * "EDIGlobalLocationNumberDelivery": "string",
      * "EDIInvoiceExtra1": "string",
      * "EDIInvoiceExtra2": "string",
      * "EDIOurElectronicReference": "string",
      * "EDIStatus": "string",
      * "EDIYourElectronicReference": "string"
},
    * "EUQuarterlyReport": true,
    * "EmailInformation": {
      * "EmailAddressBCC": "string",
      * "EmailAddressCC": "string",
      * "EmailAddressFrom": "string",
      * "EmailAddressTo": "string",
      * "EmailBody": "string",
      * "EmailSubject": "string"
},
    * "ExternalInvoiceReference1": "string",
    * "ExternalInvoiceReference2": "string",
    * "FinalPayDate": "2019-08-24",
    * "Freight": 0.1,
    * "FreightVAT": 0.1,
    * "Gross": 0.1,
    * "HouseWork": true,
    * "InvoiceDate": "2019-08-24",
    * "InvoicePeriodEnd": "2019-08-24",
    * "InvoicePeriodReference": "string",
    * "InvoicePeriodStart": "2019-08-24",
    * "InvoiceRows": [
      * {
        * "AccountNumber": 1000,
        * "ArticleNumber": "string",
        * "ContributionPercent": "string",
        * "ContributionValue": "string",
        * "CostCenter": "string",
        * "DeliveredQuantity": "string",
        * "Description": "string",
        * "Discount": 0.1,
        * "DiscountType": "AMOUNT",
        * "HouseWork": true,
        * "HouseWorkHoursToReport": 999,
        * "HouseWorkType": "CONSTRUCTION",
        * "Price": 0.1,
        * "PriceExcludingVAT": 0.1,
        * "Project": "string",
        * "RowId": 0,
        * "StockPointCode": "string",
        * "Total": 0.1,
        * "TotalExcludingVAT": 0.1,
        * "Unit": "string",
        * "VAT": 0,
        * "VATCode": "string"
}
],
    * "InvoiceType": "INVOICE",
    * "Labels": [
      * {
        * "Id": 0
}
],
    * "Language": "SV",
    * "LastRemindDate": "2019-08-24",
    * "Net": 0.1,
    * "NotCompleted": true,
    * "NoxFinans": true,
    * "OCR": "string",
    * "OfferReference": "string",
    * "OrderReference": "string",
    * "OrganisationNumber": "string",
    * "OurReference": "string",
    * "OutboundDate": "2019-08-24",
    * "PaymentWay": "CASH",
    * "Phone1": "string",
    * "Phone2": "string",
    * "PriceList": "string",
    * "PrintTemplate": "string",
    * "Project": "string",
    * "Remarks": "string",
    * "Reminders": 0,
    * "RoundOff": 0.1,
    * "Sent": true,
    * "TaxReduction": 0,
    * "TaxReductionType": "none",
    * "TermsOfDelivery": "string",
    * "TermsOfPayment": "string",
    * "TimeBasisReference": 0,
    * "Total": 0.1,
    * "TotalToPay": 0.1,
    * "TotalVAT": 0.1,
    * "VATIncluded": true,
    * "VoucherNumber": 0,
    * "VoucherSeries": "string",
    * "VoucherYear": 0,
    * "WarehouseReady": true,
    * "WayOfDelivery": "string",
    * "YourOrderNumber": "string",
    * "YourReference": "string",
    * "ZipCode": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Invoices/operation/get_27)Retrieve a single invoice 
##### path Parameters
DocumentNumberrequired| string identifies the invoice  
---|---  
### Responses
**200**
the existing invoice
**default**
Error information if the request did not succeed
get/3/invoices/{DocumentNumber}
Default server
https://api.fortnox.se/3/invoices/{DocumentNumber}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Invoice": {
    * "@url": "string",
    * "@urlTaxReductionList": "string",
    * "AccountingMethod": "ACCRUAL",
    * "Address1": "string",
    * "Address2": "string",
    * "AdministrationFee": 0.1,
    * "AdministrationFeeVAT": 0.1,
    * "Balance": 0.1,
    * "BasisTaxReduction": 0.1,
    * "Booked": true,
    * "Cancelled": true,
    * "City": "string",
    * "Comments": "string",
    * "ContractReference": 0,
    * "ContributionPercent": 0.1,
    * "ContributionValue": 0.1,
    * "CostCenter": "string",
    * "Country": "string",
    * "Credit": "string",
    * "CreditInvoiceReference": "string",
    * "Currency": "string",
    * "CurrencyRate": 0.1,
    * "CurrencyUnit": 0,
    * "CustomerName": "string",
    * "CustomerNumber": "string",
    * "DeliveryAddress1": "string",
    * "DeliveryAddress2": "string",
    * "DeliveryCity": "string",
    * "DeliveryCountry": "string",
    * "DeliveryDate": "2019-08-24",
    * "DeliveryName": "string",
    * "DeliveryZipCode": "string",
    * "DocumentNumber": "string",
    * "DueDate": "2019-08-24",
    * "EDIInformation": {
      * "EDIGlobalLocationNumber": "string",
      * "EDIGlobalLocationNumberDelivery": "string",
      * "EDIInvoiceExtra1": "string",
      * "EDIInvoiceExtra2": "string",
      * "EDIOurElectronicReference": "string",
      * "EDIStatus": "string",
      * "EDIYourElectronicReference": "string"
},
    * "EUQuarterlyReport": true,
    * "EmailInformation": {
      * "EmailAddressBCC": "string",
      * "EmailAddressCC": "string",
      * "EmailAddressFrom": "string",
      * "EmailAddressTo": "string",
      * "EmailBody": "string",
      * "EmailSubject": "string"
},
    * "ExternalInvoiceReference1": "string",
    * "ExternalInvoiceReference2": "string",
    * "FinalPayDate": "2019-08-24",
    * "Freight": 0.1,
    * "FreightVAT": 0.1,
    * "Gross": 0.1,
    * "HouseWork": true,
    * "InvoiceDate": "2019-08-24",
    * "InvoicePeriodEnd": "2019-08-24",
    * "InvoicePeriodReference": "string",
    * "InvoicePeriodStart": "2019-08-24",
    * "InvoiceRows": [
      * {
        * "AccountNumber": 1000,
        * "ArticleNumber": "string",
        * "ContributionPercent": "string",
        * "ContributionValue": "string",
        * "CostCenter": "string",
        * "DeliveredQuantity": "string",
        * "Description": "string",
        * "Discount": 0.1,
        * "DiscountType": "AMOUNT",
        * "HouseWork": true,
        * "HouseWorkHoursToReport": 999,
        * "HouseWorkType": "CONSTRUCTION",
        * "Price": 0.1,
        * "PriceExcludingVAT": 0.1,
        * "Project": "string",
        * "RowId": 0,
        * "StockPointCode": "string",
        * "Total": 0.1,
        * "TotalExcludingVAT": 0.1,
        * "Unit": "string",
        * "VAT": 0,
        * "VATCode": "string"
}
],
    * "InvoiceType": "INVOICE",
    * "Labels": [
      * {
        * "Id": 0
}
],
    * "Language": "SV",
    * "LastRemindDate": "2019-08-24",
    * "Net": 0.1,
    * "NotCompleted": true,
    * "NoxFinans": true,
    * "OCR": "string",
    * "OfferReference": "string",
    * "OrderReference": "string",
    * "OrganisationNumber": "string",
    * "OurReference": "string",
    * "OutboundDate": "2019-08-24",
    * "PaymentWay": "CASH",
    * "Phone1": "string",
    * "Phone2": "string",
    * "PriceList": "string",
    * "PrintTemplate": "string",
    * "Project": "string",
    * "Remarks": "string",
    * "Reminders": 0,
    * "RoundOff": 0.1,
    * "Sent": true,
    * "TaxReduction": 0,
    * "TaxReductionType": "none",
    * "TermsOfDelivery": "string",
    * "TermsOfPayment": "string",
    * "TimeBasisReference": 0,
    * "Total": 0.1,
    * "TotalToPay": 0.1,
    * "TotalVAT": 0.1,
    * "VATIncluded": true,
    * "VoucherNumber": 0,
    * "VoucherSeries": "string",
    * "VoucherYear": 0,
    * "WarehouseReady": true,
    * "WayOfDelivery": "string",
    * "YourOrderNumber": "string",
    * "YourReference": "string",
    * "ZipCode": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Invoices/operation/update_18)Update an invoice 
Note that there are two approaches for updating the rows on an invoice.
If RowId is not specified on any row, the rows will be mapped and updated in the order in which they are set in the array. All rows that should remain on the invoice needs to be provided.
If RowId is specified on one or more rows the following goes: Corresponding row with that id will be updated. The rows without RowId will be interpreted as new rows. If a row should not be updated but remain on the invoice then specify only RowId like { "RowId": 123 }, otherwise it will be removed. Note that new RowIds are generated for all rows every time an invoice is updated.
Note: The **EuQuarterlyReport** property will become obsolete at 2021-12-01. This property is currently used by the **Quarterly** report as one of the conditions that determine if an invoice should be included in the report or not. A new version of the **Quarterly** report is released at 2021-12-01. In the new report, this property will not be used when determining if an invoice should be included in the report or not, with one exception: if the invoice is created before 2021-12-01, and this property is false, the invoice will be excluded from the report. For invoices created 2021-12-01 and later, this property will have no effect.
##### path Parameters
DocumentNumberrequired| string identifies the invoice  
---|---  
##### Request Body schema: */*
payload
Invoice| object (fortnox_InvoicePayload)   
---|---  
### Responses
**200**
the updated invoice
**default**
Error information if the request did not succeed
put/3/invoices/{DocumentNumber}
Default server
https://api.fortnox.se/3/invoices/{DocumentNumber}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Invoice": {
    * "@url": "string",
    * "@urlTaxReductionList": "string",
    * "AccountingMethod": "ACCRUAL",
    * "Address1": "string",
    * "Address2": "string",
    * "AdministrationFee": 0.1,
    * "AdministrationFeeVAT": 0.1,
    * "Balance": 0.1,
    * "BasisTaxReduction": 0.1,
    * "Booked": true,
    * "Cancelled": true,
    * "City": "string",
    * "Comments": "string",
    * "ContractReference": 0,
    * "ContributionPercent": 0.1,
    * "ContributionValue": 0.1,
    * "CostCenter": "string",
    * "Country": "string",
    * "Credit": "string",
    * "CreditInvoiceReference": "string",
    * "Currency": "string",
    * "CurrencyRate": 0.1,
    * "CurrencyUnit": 0,
    * "CustomerName": "string",
    * "CustomerNumber": "string",
    * "DeliveryAddress1": "string",
    * "DeliveryAddress2": "string",
    * "DeliveryCity": "string",
    * "DeliveryCountry": "string",
    * "DeliveryDate": "2019-08-24",
    * "DeliveryName": "string",
    * "DeliveryZipCode": "string",
    * "DocumentNumber": "string",
    * "DueDate": "2019-08-24",
    * "EDIInformation": {
      * "EDIGlobalLocationNumber": "string",
      * "EDIGlobalLocationNumberDelivery": "string",
      * "EDIInvoiceExtra1": "string",
      * "EDIInvoiceExtra2": "string",
      * "EDIOurElectronicReference": "string",
      * "EDIStatus": "string",
      * "EDIYourElectronicReference": "string"
},
    * "EUQuarterlyReport": true,
    * "EmailInformation": {
      * "EmailAddressBCC": "string",
      * "EmailAddressCC": "string",
      * "EmailAddressFrom": "string",
      * "EmailAddressTo": "string",
      * "EmailBody": "string",
      * "EmailSubject": "string"
},
    * "ExternalInvoiceReference1": "string",
    * "ExternalInvoiceReference2": "string",
    * "FinalPayDate": "2019-08-24",
    * "Freight": 0.1,
    * "FreightVAT": 0.1,
    * "Gross": 0.1,
    * "HouseWork": true,
    * "InvoiceDate": "2019-08-24",
    * "InvoicePeriodEnd": "2019-08-24",
    * "InvoicePeriodReference": "string",
    * "InvoicePeriodStart": "2019-08-24",
    * "InvoiceRows": [
      * {
        * "AccountNumber": 1000,
        * "ArticleNumber": "string",
        * "ContributionPercent": "string",
        * "ContributionValue": "string",
        * "CostCenter": "string",
        * "DeliveredQuantity": "string",
        * "Description": "string",
        * "Discount": 0.1,
        * "DiscountType": "AMOUNT",
        * "HouseWork": true,
        * "HouseWorkHoursToReport": 999,
        * "HouseWorkType": "CONSTRUCTION",
        * "Price": 0.1,
        * "PriceExcludingVAT": 0.1,
        * "Project": "string",
        * "RowId": 0,
        * "StockPointCode": "string",
        * "Total": 0.1,
        * "TotalExcludingVAT": 0.1,
        * "Unit": "string",
        * "VAT": 0,
        * "VATCode": "string"
}
],
    * "InvoiceType": "INVOICE",
    * "Labels": [
      * {
        * "Id": 0
}
],
    * "Language": "SV",
    * "LastRemindDate": "2019-08-24",
    * "Net": 0.1,
    * "NotCompleted": true,
    * "NoxFinans": true,
    * "OCR": "string",
    * "OfferReference": "string",
    * "OrderReference": "string",
    * "OrganisationNumber": "string",
    * "OurReference": "string",
    * "OutboundDate": "2019-08-24",
    * "PaymentWay": "CASH",
    * "Phone1": "string",
    * "Phone2": "string",
    * "PriceList": "string",
    * "PrintTemplate": "string",
    * "Project": "string",
    * "Remarks": "string",
    * "Reminders": 0,
    * "RoundOff": 0.1,
    * "Sent": true,
    * "TaxReduction": 0,
    * "TaxReductionType": "none",
    * "TermsOfDelivery": "string",
    * "TermsOfPayment": "string",
    * "TimeBasisReference": 0,
    * "Total": 0.1,
    * "TotalToPay": 0.1,
    * "TotalVAT": 0.1,
    * "VATIncluded": true,
    * "VoucherNumber": 0,
    * "VoucherSeries": "string",
    * "VoucherYear": 0,
    * "WarehouseReady": true,
    * "WayOfDelivery": "string",
    * "YourOrderNumber": "string",
    * "YourReference": "string",
    * "ZipCode": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Invoices/operation/bookkeep_1)Bookkeep an invoice 
##### path Parameters
DocumentNumberrequired| string identifies the invoice  
---|---  
### Responses
**200**
the updated invoice
**default**
Error information if the request did not succeed
put/3/invoices/{DocumentNumber}/bookkeep
Default server
https://api.fortnox.se/3/invoices/{DocumentNumber}/bookkeep
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Invoice": {
    * "@url": "string",
    * "@urlTaxReductionList": "string",
    * "AccountingMethod": "ACCRUAL",
    * "Address1": "string",
    * "Address2": "string",
    * "AdministrationFee": 0.1,
    * "AdministrationFeeVAT": 0.1,
    * "Balance": 0.1,
    * "BasisTaxReduction": 0.1,
    * "Booked": true,
    * "Cancelled": true,
    * "City": "string",
    * "Comments": "string",
    * "ContractReference": 0,
    * "ContributionPercent": 0.1,
    * "ContributionValue": 0.1,
    * "CostCenter": "string",
    * "Country": "string",
    * "Credit": "string",
    * "CreditInvoiceReference": "string",
    * "Currency": "string",
    * "CurrencyRate": 0.1,
    * "CurrencyUnit": 0,
    * "CustomerName": "string",
    * "CustomerNumber": "string",
    * "DeliveryAddress1": "string",
    * "DeliveryAddress2": "string",
    * "DeliveryCity": "string",
    * "DeliveryCountry": "string",
    * "DeliveryDate": "2019-08-24",
    * "DeliveryName": "string",
    * "DeliveryZipCode": "string",
    * "DocumentNumber": "string",
    * "DueDate": "2019-08-24",
    * "EDIInformation": {
      * "EDIGlobalLocationNumber": "string",
      * "EDIGlobalLocationNumberDelivery": "string",
      * "EDIInvoiceExtra1": "string",
      * "EDIInvoiceExtra2": "string",
      * "EDIOurElectronicReference": "string",
      * "EDIStatus": "string",
      * "EDIYourElectronicReference": "string"
},
    * "EUQuarterlyReport": true,
    * "EmailInformation": {
      * "EmailAddressBCC": "string",
      * "EmailAddressCC": "string",
      * "EmailAddressFrom": "string",
      * "EmailAddressTo": "string",
      * "EmailBody": "string",
      * "EmailSubject": "string"
},
    * "ExternalInvoiceReference1": "string",
    * "ExternalInvoiceReference2": "string",
    * "FinalPayDate": "2019-08-24",
    * "Freight": 0.1,
    * "FreightVAT": 0.1,
    * "Gross": 0.1,
    * "HouseWork": true,
    * "InvoiceDate": "2019-08-24",
    * "InvoicePeriodEnd": "2019-08-24",
    * "InvoicePeriodReference": "string",
    * "InvoicePeriodStart": "2019-08-24",
    * "InvoiceRows": [
      * {
        * "AccountNumber": 1000,
        * "ArticleNumber": "string",
        * "ContributionPercent": "string",
        * "ContributionValue": "string",
        * "CostCenter": "string",
        * "DeliveredQuantity": "string",
        * "Description": "string",
        * "Discount": 0.1,
        * "DiscountType": "AMOUNT",
        * "HouseWork": true,
        * "HouseWorkHoursToReport": 999,
        * "HouseWorkType": "CONSTRUCTION",
        * "Price": 0.1,
        * "PriceExcludingVAT": 0.1,
        * "Project": "string",
        * "RowId": 0,
        * "StockPointCode": "string",
        * "Total": 0.1,
        * "TotalExcludingVAT": 0.1,
        * "Unit": "string",
        * "VAT": 0,
        * "VATCode": "string"
}
],
    * "InvoiceType": "INVOICE",
    * "Labels": [
      * {
        * "Id": 0
}
],
    * "Language": "SV",
    * "LastRemindDate": "2019-08-24",
    * "Net": 0.1,
    * "NotCompleted": true,
    * "NoxFinans": true,
    * "OCR": "string",
    * "OfferReference": "string",
    * "OrderReference": "string",
    * "OrganisationNumber": "string",
    * "OurReference": "string",
    * "OutboundDate": "2019-08-24",
    * "PaymentWay": "CASH",
    * "Phone1": "string",
    * "Phone2": "string",
    * "PriceList": "string",
    * "PrintTemplate": "string",
    * "Project": "string",
    * "Remarks": "string",
    * "Reminders": 0,
    * "RoundOff": 0.1,
    * "Sent": true,
    * "TaxReduction": 0,
    * "TaxReductionType": "none",
    * "TermsOfDelivery": "string",
    * "TermsOfPayment": "string",
    * "TimeBasisReference": 0,
    * "Total": 0.1,
    * "TotalToPay": 0.1,
    * "TotalVAT": 0.1,
    * "VATIncluded": true,
    * "VoucherNumber": 0,
    * "VoucherSeries": "string",
    * "VoucherYear": 0,
    * "WarehouseReady": true,
    * "WayOfDelivery": "string",
    * "YourOrderNumber": "string",
    * "YourReference": "string",
    * "ZipCode": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Invoices/operation/cancel)Cancel an invoice 
##### path Parameters
DocumentNumberrequired| string identifies the invoice  
---|---  
### Responses
**200**
the updated invoice
**default**
Error information if the request did not succeed
put/3/invoices/{DocumentNumber}/cancel
Default server
https://api.fortnox.se/3/invoices/{DocumentNumber}/cancel
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Invoice": {
    * "@url": "string",
    * "@urlTaxReductionList": "string",
    * "AccountingMethod": "ACCRUAL",
    * "Address1": "string",
    * "Address2": "string",
    * "AdministrationFee": 0.1,
    * "AdministrationFeeVAT": 0.1,
    * "Balance": 0.1,
    * "BasisTaxReduction": 0.1,
    * "Booked": true,
    * "Cancelled": true,
    * "City": "string",
    * "Comments": "string",
    * "ContractReference": 0,
    * "ContributionPercent": 0.1,
    * "ContributionValue": 0.1,
    * "CostCenter": "string",
    * "Country": "string",
    * "Credit": "string",
    * "CreditInvoiceReference": "string",
    * "Currency": "string",
    * "CurrencyRate": 0.1,
    * "CurrencyUnit": 0,
    * "CustomerName": "string",
    * "CustomerNumber": "string",
    * "DeliveryAddress1": "string",
    * "DeliveryAddress2": "string",
    * "DeliveryCity": "string",
    * "DeliveryCountry": "string",
    * "DeliveryDate": "2019-08-24",
    * "DeliveryName": "string",
    * "DeliveryZipCode": "string",
    * "DocumentNumber": "string",
    * "DueDate": "2019-08-24",
    * "EDIInformation": {
      * "EDIGlobalLocationNumber": "string",
      * "EDIGlobalLocationNumberDelivery": "string",
      * "EDIInvoiceExtra1": "string",
      * "EDIInvoiceExtra2": "string",
      * "EDIOurElectronicReference": "string",
      * "EDIStatus": "string",
      * "EDIYourElectronicReference": "string"
},
    * "EUQuarterlyReport": true,
    * "EmailInformation": {
      * "EmailAddressBCC": "string",
      * "EmailAddressCC": "string",
      * "EmailAddressFrom": "string",
      * "EmailAddressTo": "string",
      * "EmailBody": "string",
      * "EmailSubject": "string"
},
    * "ExternalInvoiceReference1": "string",
    * "ExternalInvoiceReference2": "string",
    * "FinalPayDate": "2019-08-24",
    * "Freight": 0.1,
    * "FreightVAT": 0.1,
    * "Gross": 0.1,
    * "HouseWork": true,
    * "InvoiceDate": "2019-08-24",
    * "InvoicePeriodEnd": "2019-08-24",
    * "InvoicePeriodReference": "string",
    * "InvoicePeriodStart": "2019-08-24",
    * "InvoiceRows": [
      * {
        * "AccountNumber": 1000,
        * "ArticleNumber": "string",
        * "ContributionPercent": "string",
        * "ContributionValue": "string",
        * "CostCenter": "string",
        * "DeliveredQuantity": "string",
        * "Description": "string",
        * "Discount": 0.1,
        * "DiscountType": "AMOUNT",
        * "HouseWork": true,
        * "HouseWorkHoursToReport": 999,
        * "HouseWorkType": "CONSTRUCTION",
        * "Price": 0.1,
        * "PriceExcludingVAT": 0.1,
        * "Project": "string",
        * "RowId": 0,
        * "StockPointCode": "string",
        * "Total": 0.1,
        * "TotalExcludingVAT": 0.1,
        * "Unit": "string",
        * "VAT": 0,
        * "VATCode": "string"
}
],
    * "InvoiceType": "INVOICE",
    * "Labels": [
      * {
        * "Id": 0
}
],
    * "Language": "SV",
    * "LastRemindDate": "2019-08-24",
    * "Net": 0.1,
    * "NotCompleted": true,
    * "NoxFinans": true,
    * "OCR": "string",
    * "OfferReference": "string",
    * "OrderReference": "string",
    * "OrganisationNumber": "string",
    * "OurReference": "string",
    * "OutboundDate": "2019-08-24",
    * "PaymentWay": "CASH",
    * "Phone1": "string",
    * "Phone2": "string",
    * "PriceList": "string",
    * "PrintTemplate": "string",
    * "Project": "string",
    * "Remarks": "string",
    * "Reminders": 0,
    * "RoundOff": 0.1,
    * "Sent": true,
    * "TaxReduction": 0,
    * "TaxReductionType": "none",
    * "TermsOfDelivery": "string",
    * "TermsOfPayment": "string",
    * "TimeBasisReference": 0,
    * "Total": 0.1,
    * "TotalToPay": 0.1,
    * "TotalVAT": 0.1,
    * "VATIncluded": true,
    * "VoucherNumber": 0,
    * "VoucherSeries": "string",
    * "VoucherYear": 0,
    * "WarehouseReady": true,
    * "WayOfDelivery": "string",
    * "YourOrderNumber": "string",
    * "YourReference": "string",
    * "ZipCode": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Invoices/operation/credit)Credit an invoice 
The created credit invoice will be referenced in the property CreditInvoiceReference.
##### path Parameters
DocumentNumberrequired| string identifies the invoice  
---|---  
### Responses
**200**
the updated invoice
**default**
Error information if the request did not succeed
put/3/invoices/{DocumentNumber}/credit
Default server
https://api.fortnox.se/3/invoices/{DocumentNumber}/credit
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Invoice": {
    * "@url": "string",
    * "@urlTaxReductionList": "string",
    * "AccountingMethod": "ACCRUAL",
    * "Address1": "string",
    * "Address2": "string",
    * "AdministrationFee": 0.1,
    * "AdministrationFeeVAT": 0.1,
    * "Balance": 0.1,
    * "BasisTaxReduction": 0.1,
    * "Booked": true,
    * "Cancelled": true,
    * "City": "string",
    * "Comments": "string",
    * "ContractReference": 0,
    * "ContributionPercent": 0.1,
    * "ContributionValue": 0.1,
    * "CostCenter": "string",
    * "Country": "string",
    * "Credit": "string",
    * "CreditInvoiceReference": "string",
    * "Currency": "string",
    * "CurrencyRate": 0.1,
    * "CurrencyUnit": 0,
    * "CustomerName": "string",
    * "CustomerNumber": "string",
    * "DeliveryAddress1": "string",
    * "DeliveryAddress2": "string",
    * "DeliveryCity": "string",
    * "DeliveryCountry": "string",
    * "DeliveryDate": "2019-08-24",
    * "DeliveryName": "string",
    * "DeliveryZipCode": "string",
    * "DocumentNumber": "string",
    * "DueDate": "2019-08-24",
    * "EDIInformation": {
      * "EDIGlobalLocationNumber": "string",
      * "EDIGlobalLocationNumberDelivery": "string",
      * "EDIInvoiceExtra1": "string",
      * "EDIInvoiceExtra2": "string",
      * "EDIOurElectronicReference": "string",
      * "EDIStatus": "string",
      * "EDIYourElectronicReference": "string"
},
    * "EUQuarterlyReport": true,
    * "EmailInformation": {
      * "EmailAddressBCC": "string",
      * "EmailAddressCC": "string",
      * "EmailAddressFrom": "string",
      * "EmailAddressTo": "string",
      * "EmailBody": "string",
      * "EmailSubject": "string"
},
    * "ExternalInvoiceReference1": "string",
    * "ExternalInvoiceReference2": "string",
    * "FinalPayDate": "2019-08-24",
    * "Freight": 0.1,
    * "FreightVAT": 0.1,
    * "Gross": 0.1,
    * "HouseWork": true,
    * "InvoiceDate": "2019-08-24",
    * "InvoicePeriodEnd": "2019-08-24",
    * "InvoicePeriodReference": "string",
    * "InvoicePeriodStart": "2019-08-24",
    * "InvoiceRows": [
      * {
        * "AccountNumber": 1000,
        * "ArticleNumber": "string",
        * "ContributionPercent": "string",
        * "ContributionValue": "string",
        * "CostCenter": "string",
        * "DeliveredQuantity": "string",
        * "Description": "string",
        * "Discount": 0.1,
        * "DiscountType": "AMOUNT",
        * "HouseWork": true,
        * "HouseWorkHoursToReport": 999,
        * "HouseWorkType": "CONSTRUCTION",
        * "Price": 0.1,
        * "PriceExcludingVAT": 0.1,
        * "Project": "string",
        * "RowId": 0,
        * "StockPointCode": "string",
        * "Total": 0.1,
        * "TotalExcludingVAT": 0.1,
        * "Unit": "string",
        * "VAT": 0,
        * "VATCode": "string"
}
],
    * "InvoiceType": "INVOICE",
    * "Labels": [
      * {
        * "Id": 0
}
],
    * "Language": "SV",
    * "LastRemindDate": "2019-08-24",
    * "Net": 0.1,
    * "NotCompleted": true,
    * "NoxFinans": true,
    * "OCR": "string",
    * "OfferReference": "string",
    * "OrderReference": "string",
    * "OrganisationNumber": "string",
    * "OurReference": "string",
    * "OutboundDate": "2019-08-24",
    * "PaymentWay": "CASH",
    * "Phone1": "string",
    * "Phone2": "string",
    * "PriceList": "string",
    * "PrintTemplate": "string",
    * "Project": "string",
    * "Remarks": "string",
    * "Reminders": 0,
    * "RoundOff": 0.1,
    * "Sent": true,
    * "TaxReduction": 0,
    * "TaxReductionType": "none",
    * "TermsOfDelivery": "string",
    * "TermsOfPayment": "string",
    * "TimeBasisReference": 0,
    * "Total": 0.1,
    * "TotalToPay": 0.1,
    * "TotalVAT": 0.1,
    * "VATIncluded": true,
    * "VoucherNumber": 0,
    * "VoucherSeries": "string",
    * "VoucherYear": 0,
    * "WarehouseReady": true,
    * "WayOfDelivery": "string",
    * "YourOrderNumber": "string",
    * "YourReference": "string",
    * "ZipCode": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Invoices/operation/eInvoice)Send an invoice as e-invoice 
##### path Parameters
DocumentNumberrequired| string identifies the invoice  
---|---  
### Responses
**200**
sent invoice
**default**
Error information if the request did not succeed
get/3/invoices/{DocumentNumber}/einvoice
Default server
https://api.fortnox.se/3/invoices/{DocumentNumber}/einvoice
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Invoice": {
    * "@url": "string",
    * "@urlTaxReductionList": "string",
    * "AccountingMethod": "ACCRUAL",
    * "Address1": "string",
    * "Address2": "string",
    * "AdministrationFee": 0.1,
    * "AdministrationFeeVAT": 0.1,
    * "Balance": 0.1,
    * "BasisTaxReduction": 0.1,
    * "Booked": true,
    * "Cancelled": true,
    * "City": "string",
    * "Comments": "string",
    * "ContractReference": 0,
    * "ContributionPercent": 0.1,
    * "ContributionValue": 0.1,
    * "CostCenter": "string",
    * "Country": "string",
    * "Credit": "string",
    * "CreditInvoiceReference": "string",
    * "Currency": "string",
    * "CurrencyRate": 0.1,
    * "CurrencyUnit": 0,
    * "CustomerName": "string",
    * "CustomerNumber": "string",
    * "DeliveryAddress1": "string",
    * "DeliveryAddress2": "string",
    * "DeliveryCity": "string",
    * "DeliveryCountry": "string",
    * "DeliveryDate": "2019-08-24",
    * "DeliveryName": "string",
    * "DeliveryZipCode": "string",
    * "DocumentNumber": "string",
    * "DueDate": "2019-08-24",
    * "EDIInformation": {
      * "EDIGlobalLocationNumber": "string",
      * "EDIGlobalLocationNumberDelivery": "string",
      * "EDIInvoiceExtra1": "string",
      * "EDIInvoiceExtra2": "string",
      * "EDIOurElectronicReference": "string",
      * "EDIStatus": "string",
      * "EDIYourElectronicReference": "string"
},
    * "EUQuarterlyReport": true,
    * "EmailInformation": {
      * "EmailAddressBCC": "string",
      * "EmailAddressCC": "string",
      * "EmailAddressFrom": "string",
      * "EmailAddressTo": "string",
      * "EmailBody": "string",
      * "EmailSubject": "string"
},
    * "ExternalInvoiceReference1": "string",
    * "ExternalInvoiceReference2": "string",
    * "FinalPayDate": "2019-08-24",
    * "Freight": 0.1,
    * "FreightVAT": 0.1,
    * "Gross": 0.1,
    * "HouseWork": true,
    * "InvoiceDate": "2019-08-24",
    * "InvoicePeriodEnd": "2019-08-24",
    * "InvoicePeriodReference": "string",
    * "InvoicePeriodStart": "2019-08-24",
    * "InvoiceRows": [
      * {
        * "AccountNumber": 1000,
        * "ArticleNumber": "string",
        * "ContributionPercent": "string",
        * "ContributionValue": "string",
        * "CostCenter": "string",
        * "DeliveredQuantity": "string",
        * "Description": "string",
        * "Discount": 0.1,
        * "DiscountType": "AMOUNT",
        * "HouseWork": true,
        * "HouseWorkHoursToReport": 999,
        * "HouseWorkType": "CONSTRUCTION",
        * "Price": 0.1,
        * "PriceExcludingVAT": 0.1,
        * "Project": "string",
        * "RowId": 0,
        * "StockPointCode": "string",
        * "Total": 0.1,
        * "TotalExcludingVAT": 0.1,
        * "Unit": "string",
        * "VAT": 0,
        * "VATCode": "string"
}
],
    * "InvoiceType": "INVOICE",
    * "Labels": [
      * {
        * "Id": 0
}
],
    * "Language": "SV",
    * "LastRemindDate": "2019-08-24",
    * "Net": 0.1,
    * "NotCompleted": true,
    * "NoxFinans": true,
    * "OCR": "string",
    * "OfferReference": "string",
    * "OrderReference": "string",
    * "OrganisationNumber": "string",
    * "OurReference": "string",
    * "OutboundDate": "2019-08-24",
    * "PaymentWay": "CASH",
    * "Phone1": "string",
    * "Phone2": "string",
    * "PriceList": "string",
    * "PrintTemplate": "string",
    * "Project": "string",
    * "Remarks": "string",
    * "Reminders": 0,
    * "RoundOff": 0.1,
    * "Sent": true,
    * "TaxReduction": 0,
    * "TaxReductionType": "none",
    * "TermsOfDelivery": "string",
    * "TermsOfPayment": "string",
    * "TimeBasisReference": 0,
    * "Total": 0.1,
    * "TotalToPay": 0.1,
    * "TotalVAT": 0.1,
    * "VATIncluded": true,
    * "VoucherNumber": 0,
    * "VoucherSeries": "string",
    * "VoucherYear": 0,
    * "WarehouseReady": true,
    * "WayOfDelivery": "string",
    * "YourOrderNumber": "string",
    * "YourReference": "string",
    * "ZipCode": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Invoices/operation/email)Send an invoice as email 
You can use the properties in the EmailInformation to customize the e-mail message on each invoice.
##### path Parameters
DocumentNumberrequired| string identifies the invoice  
---|---  
### Responses
**200**
sent invoice
**default**
Error information if the request did not succeed
get/3/invoices/{DocumentNumber}/email
Default server
https://api.fortnox.se/3/invoices/{DocumentNumber}/email
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Invoice": {
    * "@url": "string",
    * "@urlTaxReductionList": "string",
    * "AccountingMethod": "ACCRUAL",
    * "Address1": "string",
    * "Address2": "string",
    * "AdministrationFee": 0.1,
    * "AdministrationFeeVAT": 0.1,
    * "Balance": 0.1,
    * "BasisTaxReduction": 0.1,
    * "Booked": true,
    * "Cancelled": true,
    * "City": "string",
    * "Comments": "string",
    * "ContractReference": 0,
    * "ContributionPercent": 0.1,
    * "ContributionValue": 0.1,
    * "CostCenter": "string",
    * "Country": "string",
    * "Credit": "string",
    * "CreditInvoiceReference": "string",
    * "Currency": "string",
    * "CurrencyRate": 0.1,
    * "CurrencyUnit": 0,
    * "CustomerName": "string",
    * "CustomerNumber": "string",
    * "DeliveryAddress1": "string",
    * "DeliveryAddress2": "string",
    * "DeliveryCity": "string",
    * "DeliveryCountry": "string",
    * "DeliveryDate": "2019-08-24",
    * "DeliveryName": "string",
    * "DeliveryZipCode": "string",
    * "DocumentNumber": "string",
    * "DueDate": "2019-08-24",
    * "EDIInformation": {
      * "EDIGlobalLocationNumber": "string",
      * "EDIGlobalLocationNumberDelivery": "string",
      * "EDIInvoiceExtra1": "string",
      * "EDIInvoiceExtra2": "string",
      * "EDIOurElectronicReference": "string",
      * "EDIStatus": "string",
      * "EDIYourElectronicReference": "string"
},
    * "EUQuarterlyReport": true,
    * "EmailInformation": {
      * "EmailAddressBCC": "string",
      * "EmailAddressCC": "string",
      * "EmailAddressFrom": "string",
      * "EmailAddressTo": "string",
      * "EmailBody": "string",
      * "EmailSubject": "string"
},
    * "ExternalInvoiceReference1": "string",
    * "ExternalInvoiceReference2": "string",
    * "FinalPayDate": "2019-08-24",
    * "Freight": 0.1,
    * "FreightVAT": 0.1,
    * "Gross": 0.1,
    * "HouseWork": true,
    * "InvoiceDate": "2019-08-24",
    * "InvoicePeriodEnd": "2019-08-24",
    * "InvoicePeriodReference": "string",
    * "InvoicePeriodStart": "2019-08-24",
    * "InvoiceRows": [
      * {
        * "AccountNumber": 1000,
        * "ArticleNumber": "string",
        * "ContributionPercent": "string",
        * "ContributionValue": "string",
        * "CostCenter": "string",
        * "DeliveredQuantity": "string",
        * "Description": "string",
        * "Discount": 0.1,
        * "DiscountType": "AMOUNT",
        * "HouseWork": true,
        * "HouseWorkHoursToReport": 999,
        * "HouseWorkType": "CONSTRUCTION",
        * "Price": 0.1,
        * "PriceExcludingVAT": 0.1,
        * "Project": "string",
        * "RowId": 0,
        * "StockPointCode": "string",
        * "Total": 0.1,
        * "TotalExcludingVAT": 0.1,
        * "Unit": "string",
        * "VAT": 0,
        * "VATCode": "string"
}
],
    * "InvoiceType": "INVOICE",
    * "Labels": [
      * {
        * "Id": 0
}
],
    * "Language": "SV",
    * "LastRemindDate": "2019-08-24",
    * "Net": 0.1,
    * "NotCompleted": true,
    * "NoxFinans": true,
    * "OCR": "string",
    * "OfferReference": "string",
    * "OrderReference": "string",
    * "OrganisationNumber": "string",
    * "OurReference": "string",
    * "OutboundDate": "2019-08-24",
    * "PaymentWay": "CASH",
    * "Phone1": "string",
    * "Phone2": "string",
    * "PriceList": "string",
    * "PrintTemplate": "string",
    * "Project": "string",
    * "Remarks": "string",
    * "Reminders": 0,
    * "RoundOff": 0.1,
    * "Sent": true,
    * "TaxReduction": 0,
    * "TaxReductionType": "none",
    * "TermsOfDelivery": "string",
    * "TermsOfPayment": "string",
    * "TimeBasisReference": 0,
    * "Total": 0.1,
    * "TotalToPay": 0.1,
    * "TotalVAT": 0.1,
    * "VATIncluded": true,
    * "VoucherNumber": 0,
    * "VoucherSeries": "string",
    * "VoucherYear": 0,
    * "WarehouseReady": true,
    * "WayOfDelivery": "string",
    * "YourOrderNumber": "string",
    * "YourReference": "string",
    * "ZipCode": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Invoices/operation/ePrint)Send an invoice as e-print 
##### path Parameters
DocumentNumberrequired| string identifies the invoice  
---|---  
### Responses
**200**
sent invoice
**default**
Error information if the request did not succeed
get/3/invoices/{DocumentNumber}/eprint
Default server
https://api.fortnox.se/3/invoices/{DocumentNumber}/eprint
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Invoice": {
    * "@url": "string",
    * "@urlTaxReductionList": "string",
    * "AccountingMethod": "ACCRUAL",
    * "Address1": "string",
    * "Address2": "string",
    * "AdministrationFee": 0.1,
    * "AdministrationFeeVAT": 0.1,
    * "Balance": 0.1,
    * "BasisTaxReduction": 0.1,
    * "Booked": true,
    * "Cancelled": true,
    * "City": "string",
    * "Comments": "string",
    * "ContractReference": 0,
    * "ContributionPercent": 0.1,
    * "ContributionValue": 0.1,
    * "CostCenter": "string",
    * "Country": "string",
    * "Credit": "string",
    * "CreditInvoiceReference": "string",
    * "Currency": "string",
    * "CurrencyRate": 0.1,
    * "CurrencyUnit": 0,
    * "CustomerName": "string",
    * "CustomerNumber": "string",
    * "DeliveryAddress1": "string",
    * "DeliveryAddress2": "string",
    * "DeliveryCity": "string",
    * "DeliveryCountry": "string",
    * "DeliveryDate": "2019-08-24",
    * "DeliveryName": "string",
    * "DeliveryZipCode": "string",
    * "DocumentNumber": "string",
    * "DueDate": "2019-08-24",
    * "EDIInformation": {
      * "EDIGlobalLocationNumber": "string",
      * "EDIGlobalLocationNumberDelivery": "string",
      * "EDIInvoiceExtra1": "string",
      * "EDIInvoiceExtra2": "string",
      * "EDIOurElectronicReference": "string",
      * "EDIStatus": "string",
      * "EDIYourElectronicReference": "string"
},
    * "EUQuarterlyReport": true,
    * "EmailInformation": {
      * "EmailAddressBCC": "string",
      * "EmailAddressCC": "string",
      * "EmailAddressFrom": "string",
      * "EmailAddressTo": "string",
      * "EmailBody": "string",
      * "EmailSubject": "string"
},
    * "ExternalInvoiceReference1": "string",
    * "ExternalInvoiceReference2": "string",
    * "FinalPayDate": "2019-08-24",
    * "Freight": 0.1,
    * "FreightVAT": 0.1,
    * "Gross": 0.1,
    * "HouseWork": true,
    * "InvoiceDate": "2019-08-24",
    * "InvoicePeriodEnd": "2019-08-24",
    * "InvoicePeriodReference": "string",
    * "InvoicePeriodStart": "2019-08-24",
    * "InvoiceRows": [
      * {
        * "AccountNumber": 1000,
        * "ArticleNumber": "string",
        * "ContributionPercent": "string",
        * "ContributionValue": "string",
        * "CostCenter": "string",
        * "DeliveredQuantity": "string",
        * "Description": "string",
        * "Discount": 0.1,
        * "DiscountType": "AMOUNT",
        * "HouseWork": true,
        * "HouseWorkHoursToReport": 999,
        * "HouseWorkType": "CONSTRUCTION",
        * "Price": 0.1,
        * "PriceExcludingVAT": 0.1,
        * "Project": "string",
        * "RowId": 0,
        * "StockPointCode": "string",
        * "Total": 0.1,
        * "TotalExcludingVAT": 0.1,
        * "Unit": "string",
        * "VAT": 0,
        * "VATCode": "string"
}
],
    * "InvoiceType": "INVOICE",
    * "Labels": [
      * {
        * "Id": 0
}
],
    * "Language": "SV",
    * "LastRemindDate": "2019-08-24",
    * "Net": 0.1,
    * "NotCompleted": true,
    * "NoxFinans": true,
    * "OCR": "string",
    * "OfferReference": "string",
    * "OrderReference": "string",
    * "OrganisationNumber": "string",
    * "OurReference": "string",
    * "OutboundDate": "2019-08-24",
    * "PaymentWay": "CASH",
    * "Phone1": "string",
    * "Phone2": "string",
    * "PriceList": "string",
    * "PrintTemplate": "string",
    * "Project": "string",
    * "Remarks": "string",
    * "Reminders": 0,
    * "RoundOff": 0.1,
    * "Sent": true,
    * "TaxReduction": 0,
    * "TaxReductionType": "none",
    * "TermsOfDelivery": "string",
    * "TermsOfPayment": "string",
    * "TimeBasisReference": 0,
    * "Total": 0.1,
    * "TotalToPay": 0.1,
    * "TotalVAT": 0.1,
    * "VATIncluded": true,
    * "VoucherNumber": 0,
    * "VoucherSeries": "string",
    * "VoucherYear": 0,
    * "WarehouseReady": true,
    * "WayOfDelivery": "string",
    * "YourOrderNumber": "string",
    * "YourReference": "string",
    * "ZipCode": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Invoices/operation/externalPrint)Set an invoice as sent 
Use this endpoint to set invoice as sent, without generating an invoice.
##### path Parameters
DocumentNumberrequired| string identifies the invoice  
---|---  
### Responses
**200**
the updated invoice
**default**
Error information if the request did not succeed
put/3/invoices/{DocumentNumber}/externalprint
Default server
https://api.fortnox.se/3/invoices/{DocumentNumber}/externalprint
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Invoice": {
    * "@url": "string",
    * "@urlTaxReductionList": "string",
    * "AccountingMethod": "ACCRUAL",
    * "Address1": "string",
    * "Address2": "string",
    * "AdministrationFee": 0.1,
    * "AdministrationFeeVAT": 0.1,
    * "Balance": 0.1,
    * "BasisTaxReduction": 0.1,
    * "Booked": true,
    * "Cancelled": true,
    * "City": "string",
    * "Comments": "string",
    * "ContractReference": 0,
    * "ContributionPercent": 0.1,
    * "ContributionValue": 0.1,
    * "CostCenter": "string",
    * "Country": "string",
    * "Credit": "string",
    * "CreditInvoiceReference": "string",
    * "Currency": "string",
    * "CurrencyRate": 0.1,
    * "CurrencyUnit": 0,
    * "CustomerName": "string",
    * "CustomerNumber": "string",
    * "DeliveryAddress1": "string",
    * "DeliveryAddress2": "string",
    * "DeliveryCity": "string",
    * "DeliveryCountry": "string",
    * "DeliveryDate": "2019-08-24",
    * "DeliveryName": "string",
    * "DeliveryZipCode": "string",
    * "DocumentNumber": "string",
    * "DueDate": "2019-08-24",
    * "EDIInformation": {
      * "EDIGlobalLocationNumber": "string",
      * "EDIGlobalLocationNumberDelivery": "string",
      * "EDIInvoiceExtra1": "string",
      * "EDIInvoiceExtra2": "string",
      * "EDIOurElectronicReference": "string",
      * "EDIStatus": "string",
      * "EDIYourElectronicReference": "string"
},
    * "EUQuarterlyReport": true,
    * "EmailInformation": {
      * "EmailAddressBCC": "string",
      * "EmailAddressCC": "string",
      * "EmailAddressFrom": "string",
      * "EmailAddressTo": "string",
      * "EmailBody": "string",
      * "EmailSubject": "string"
},
    * "ExternalInvoiceReference1": "string",
    * "ExternalInvoiceReference2": "string",
    * "FinalPayDate": "2019-08-24",
    * "Freight": 0.1,
    * "FreightVAT": 0.1,
    * "Gross": 0.1,
    * "HouseWork": true,
    * "InvoiceDate": "2019-08-24",
    * "InvoicePeriodEnd": "2019-08-24",
    * "InvoicePeriodReference": "string",
    * "InvoicePeriodStart": "2019-08-24",
    * "InvoiceRows": [
      * {
        * "AccountNumber": 1000,
        * "ArticleNumber": "string",
        * "ContributionPercent": "string",
        * "ContributionValue": "string",
        * "CostCenter": "string",
        * "DeliveredQuantity": "string",
        * "Description": "string",
        * "Discount": 0.1,
        * "DiscountType": "AMOUNT",
        * "HouseWork": true,
        * "HouseWorkHoursToReport": 999,
        * "HouseWorkType": "CONSTRUCTION",
        * "Price": 0.1,
        * "PriceExcludingVAT": 0.1,
        * "Project": "string",
        * "RowId": 0,
        * "StockPointCode": "string",
        * "Total": 0.1,
        * "TotalExcludingVAT": 0.1,
        * "Unit": "string",
        * "VAT": 0,
        * "VATCode": "string"
}
],
    * "InvoiceType": "INVOICE",
    * "Labels": [
      * {
        * "Id": 0
}
],
    * "Language": "SV",
    * "LastRemindDate": "2019-08-24",
    * "Net": 0.1,
    * "NotCompleted": true,
    * "NoxFinans": true,
    * "OCR": "string",
    * "OfferReference": "string",
    * "OrderReference": "string",
    * "OrganisationNumber": "string",
    * "OurReference": "string",
    * "OutboundDate": "2019-08-24",
    * "PaymentWay": "CASH",
    * "Phone1": "string",
    * "Phone2": "string",
    * "PriceList": "string",
    * "PrintTemplate": "string",
    * "Project": "string",
    * "Remarks": "string",
    * "Reminders": 0,
    * "RoundOff": 0.1,
    * "Sent": true,
    * "TaxReduction": 0,
    * "TaxReductionType": "none",
    * "TermsOfDelivery": "string",
    * "TermsOfPayment": "string",
    * "TimeBasisReference": 0,
    * "Total": 0.1,
    * "TotalToPay": 0.1,
    * "TotalVAT": 0.1,
    * "VATIncluded": true,
    * "VoucherNumber": 0,
    * "VoucherSeries": "string",
    * "VoucherYear": 0,
    * "WarehouseReady": true,
    * "WayOfDelivery": "string",
    * "YourOrderNumber": "string",
    * "YourReference": "string",
    * "ZipCode": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Invoices/operation/preview)Preview an invoice 
The difference between this and the print-endpoint is that property Sent is not set to TRUE.
##### path Parameters
DocumentNumberrequired| string identifies the invoice  
---|---  
### Responses
**200**
the invoice as PDF
**default**
Error information if the request did not succeed
get/3/invoices/{DocumentNumber}/preview
Default server
https://api.fortnox.se/3/invoices/{DocumentNumber}/preview
## [](https://api.fortnox.se/apidocs#tag/fortnox_Invoices/operation/print)Print an invoice 
##### path Parameters
DocumentNumberrequired| string identifies the invoice  
---|---  
### Responses
**200**
the invoice as PDF
**default**
Error information if the request did not succeed
get/3/invoices/{DocumentNumber}/print
Default server
https://api.fortnox.se/3/invoices/{DocumentNumber}/print
## [](https://api.fortnox.se/apidocs#tag/fortnox_Invoices/operation/printReminder)Print an invoice as reminder 
##### path Parameters
DocumentNumberrequired| string identifies the invoice  
---|---  
### Responses
**200**
the invoice as PDF
**default**
Error information if the request did not succeed
get/3/invoices/{DocumentNumber}/printreminder
Default server
https://api.fortnox.se/3/invoices/{DocumentNumber}/printreminder
## [](https://api.fortnox.se/apidocs#tag/fortnox_Invoices/operation/warehouseReady)Set an invoice as done 
Used for marking a document as ready in the warehouse module. DeliveryState needs to be set to "delivery".
##### path Parameters
DocumentNumberrequired| string identifies the invoice  
---|---  
### Responses
**200**
the updated invoice
**default**
Error information if the request did not succeed
put/3/invoices/{DocumentNumber}/warehouseready
Default server
https://api.fortnox.se/3/invoices/{DocumentNumber}/warehouseready
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Invoice": {
    * "@url": "string",
    * "@urlTaxReductionList": "string",
    * "AccountingMethod": "ACCRUAL",
    * "Address1": "string",
    * "Address2": "string",
    * "AdministrationFee": 0.1,
    * "AdministrationFeeVAT": 0.1,
    * "Balance": 0.1,
    * "BasisTaxReduction": 0.1,
    * "Booked": true,
    * "Cancelled": true,
    * "City": "string",
    * "Comments": "string",
    * "ContractReference": 0,
    * "ContributionPercent": 0.1,
    * "ContributionValue": 0.1,
    * "CostCenter": "string",
    * "Country": "string",
    * "Credit": "string",
    * "CreditInvoiceReference": "string",
    * "Currency": "string",
    * "CurrencyRate": 0.1,
    * "CurrencyUnit": 0,
    * "CustomerName": "string",
    * "CustomerNumber": "string",
    * "DeliveryAddress1": "string",
    * "DeliveryAddress2": "string",
    * "DeliveryCity": "string",
    * "DeliveryCountry": "string",
    * "DeliveryDate": "2019-08-24",
    * "DeliveryName": "string",
    * "DeliveryZipCode": "string",
    * "DocumentNumber": "string",
    * "DueDate": "2019-08-24",
    * "EDIInformation": {
      * "EDIGlobalLocationNumber": "string",
      * "EDIGlobalLocationNumberDelivery": "string",
      * "EDIInvoiceExtra1": "string",
      * "EDIInvoiceExtra2": "string",
      * "EDIOurElectronicReference": "string",
      * "EDIStatus": "string",
      * "EDIYourElectronicReference": "string"
},
    * "EUQuarterlyReport": true,
    * "EmailInformation": {
      * "EmailAddressBCC": "string",
      * "EmailAddressCC": "string",
      * "EmailAddressFrom": "string",
      * "EmailAddressTo": "string",
      * "EmailBody": "string",
      * "EmailSubject": "string"
},
    * "ExternalInvoiceReference1": "string",
    * "ExternalInvoiceReference2": "string",
    * "FinalPayDate": "2019-08-24",
    * "Freight": 0.1,
    * "FreightVAT": 0.1,
    * "Gross": 0.1,
    * "HouseWork": true,
    * "InvoiceDate": "2019-08-24",
    * "InvoicePeriodEnd": "2019-08-24",
    * "InvoicePeriodReference": "string",
    * "InvoicePeriodStart": "2019-08-24",
    * "InvoiceRows": [
      * {
        * "AccountNumber": 1000,
        * "ArticleNumber": "string",
        * "ContributionPercent": "string",
        * "ContributionValue": "string",
        * "CostCenter": "string",
        * "DeliveredQuantity": "string",
        * "Description": "string",
        * "Discount": 0.1,
        * "DiscountType": "AMOUNT",
        * "HouseWork": true,
        * "HouseWorkHoursToReport": 999,
        * "HouseWorkType": "CONSTRUCTION",
        * "Price": 0.1,
        * "PriceExcludingVAT": 0.1,
        * "Project": "string",
        * "RowId": 0,
        * "StockPointCode": "string",
        * "Total": 0.1,
        * "TotalExcludingVAT": 0.1,
        * "Unit": "string",
        * "VAT": 0,
        * "VATCode": "string"
}
],
    * "InvoiceType": "INVOICE",
    * "Labels": [
      * {
        * "Id": 0
}
],
    * "Language": "SV",
    * "LastRemindDate": "2019-08-24",
    * "Net": 0.1,
    * "NotCompleted": true,
    * "NoxFinans": true,
    * "OCR": "string",
    * "OfferReference": "string",
    * "OrderReference": "string",
    * "OrganisationNumber": "string",
    * "OurReference": "string",
    * "OutboundDate": "2019-08-24",
    * "PaymentWay": "CASH",
    * "Phone1": "string",
    * "Phone2": "string",
    * "PriceList": "string",
    * "PrintTemplate": "string",
    * "Project": "string",
    * "Remarks": "string",
    * "Reminders": 0,
    * "RoundOff": 0.1,
    * "Sent": true,
    * "TaxReduction": 0,
    * "TaxReductionType": "none",
    * "TermsOfDelivery": "string",
    * "TermsOfPayment": "string",
    * "TimeBasisReference": 0,
    * "Total": 0.1,
    * "TotalToPay": 0.1,
    * "TotalVAT": 0.1,
    * "VATIncluded": true,
    * "VoucherNumber": 0,
    * "VoucherSeries": "string",
    * "VoucherYear": 0,
    * "WarehouseReady": true,
    * "WayOfDelivery": "string",
    * "YourOrderNumber": "string",
    * "YourReference": "string",
    * "ZipCode": "string"
}

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_Labels)Labels
Labels resources
## [](https://api.fortnox.se/apidocs#tag/fortnox_Labels/operation/list_22)Retrieve a list of labels 
### Responses
**200**
list of labels
**default**
Error information if the request did not succeed
get/3/labels
Default server
https://api.fortnox.se/3/labels
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Labels": [
    * {
      * "Description": "string",
      * "Id": 0
}
]

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Labels/operation/create_25)Create a label 
The created label will be returned if everything succeeded, if there was any problems an error will be returned.
##### Request Body schema: */*
to create
Labelrequired| object (fortnox_Label)   
---|---  
### Responses
**201**
the created label
**default**
Error information if the request did not succeed
post/3/labels
Default server
https://api.fortnox.se/3/labels
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Label": {
    * "Description": "string",
    * "Id": 0
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Labels/operation/remove_14)Delete a label 
Deletes the label and its connection to documents permanently. You need to supply the unique label id that was returned when the label was created or retrieved from the list of labels.
##### path Parameters
Idrequired| integer <int32> identifies the label  
---|---  
### Responses
**204**
Successfully removed the specified resource.
**default**
Error information if the request did not succeed
delete/3/labels/{Id}
Default server
https://api.fortnox.se/3/labels/{Id}
###  Response samples 
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ErrorInformation": {
    * "Code": 0,
    * "Error": 0,
    * "Message": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Labels/operation/update_20)Update a label 
Updates the specified label with the values provided in the properties. Any property not provided will be left unchanged.
##### path Parameters
Idrequired| integer <int32> identifies the label  
---|---  
##### Request Body schema: */*
to update
Labelrequired| object (fortnox_Label)   
---|---  
### Responses
**200**
the updated label
**default**
Error information if the request did not succeed
put/3/labels/{Id}
Default server
https://api.fortnox.se/3/labels/{Id}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Label": {
    * "Description": "string",
    * "Id": 0
}

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_LockedPeriod)Locked Period
Resource for CRUD operations on locked period
## [](https://api.fortnox.se/apidocs#tag/fortnox_LockedPeriod/operation/get_29)Retrieve the locked period 
If no date is returned, no period is locked.
### Responses
**200**
the locked period
**default**
Error information if the request did not succeed
get/3/settings/lockedperiod
Default server
https://api.fortnox.se/3/settings/lockedperiod
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "LockedPeriod": {
    * "EndDate": "2019-08-24"
}

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_Me)Me
Me resource
## [](https://api.fortnox.se/apidocs#tag/fortnox_Me/operation/get_30)Retrieve user information Use this endpoint to retrieve user information related to the used access token 
### Responses
**200**
user information
**default**
Error information if the request did not succeed
get/3/me
Default server
https://api.fortnox.se/3/me
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "MeInformation": {
    * "Email": "string",
    * "Id": "string",
    * "Locale": "string",
    * "Name": "string",
    * "SysAdmin": true
}

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_ModesOfPayments)Modes Of Payments
Resource for the CRUD operations on modes of payments
## [](https://api.fortnox.se/apidocs#tag/fortnox_ModesOfPayments/operation/list_23)Retrieve a list of modes of payments 
The modes of payments register can return a list of records or a single record. By specifying a Code in the URL, a single record will be returned. Not specifying a Code will return a list of records.
### Responses
**200**
a list of modes of payments.
**default**
Error information if the request did not succeed
get/3/modesofpayments
Default server
https://api.fortnox.se/3/modesofpayments
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ModesOfPayments": [
    * {
      * "@url": "string",
      * "AccountNumber": "stri",
      * "Code": "string",
      * "Description": "string"
}
]

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_ModesOfPayments/operation/create_26)Create a mode of payment 
##### Request Body schema: */*
to create
ModeOfPaymentrequired| object (fortnox_ModeOfPayment)   
---|---  
### Responses
**201**
the created mode of payment
**default**
Error information if the request did not succeed
post/3/modesofpayments
Default server
https://api.fortnox.se/3/modesofpayments
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ModeOfPayment": {
    * "@url": "string",
    * "AccountNumber": "stri",
    * "Code": "string",
    * "Description": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_ModesOfPayments/operation/remove_15)Remove a mode of payment 
##### path Parameters
Coderequired| string identifies the mode of payment  
---|---  
### Responses
**204**
Successfully removed the specified resource.
**default**
Error information if the request did not succeed
delete/3/modesofpayments/{Code}
Default server
https://api.fortnox.se/3/modesofpayments/{Code}
###  Response samples 
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ErrorInformation": {
    * "Code": 0,
    * "Error": 0,
    * "Message": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_ModesOfPayments/operation/get_31)Retrieve a single mode of payment 
##### path Parameters
Coderequired| string identifies the mode of payment  
---|---  
### Responses
**200**
the existing mode of payment
**default**
Error information if the request did not succeed
get/3/modesofpayments/{Code}
Default server
https://api.fortnox.se/3/modesofpayments/{Code}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ModeOfPayment": {
    * "@url": "string",
    * "AccountNumber": "stri",
    * "Code": "string",
    * "Description": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_ModesOfPayments/operation/update_21)Update a mode of payment 
##### path Parameters
Coderequired| string identifies the mode of payment  
---|---  
##### Request Body schema: */*
mode of payment to update
ModeOfPaymentrequired| object (fortnox_ModeOfPayment)   
---|---  
### Responses
**200**
the updated mode of payment
**default**
Error information if the request did not succeed
put/3/modesofpayments/{Code}
Default server
https://api.fortnox.se/3/modesofpayments/{Code}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ModeOfPayment": {
    * "@url": "string",
    * "AccountNumber": "stri",
    * "Code": "string",
    * "Description": "string"
}

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_Offers)Offers
Possible filters on Offers endpoint **Filter** | **Description**  
---|---  
cancelled | Retrieves all offers with the status "cancelled"  
expired | Retrieves all offers that has been expired  
completed | Retrieves all offers where an order or invoice has been created  
notcompleted | Retrieves all offers where an order or invoice has not been created  
ordercreated | Retrieves all offers where an order has been created  
ordernotcreated | Retrieves all offers where an order has not been created  
## [](https://api.fortnox.se/apidocs#tag/fortnox_Offers/operation/list_24)Retrieve a list of offers 
##### query Parameters
filter| string Enum: "cancelled" "expired" "completed" "notcompleted" "ordercreated" "ordernotcreated" possibility to filter offers  
---|---  
customername| string filter by customer name  
customernumber| string filter by customer number  
documentnumber| string filter by document number  
costcenter| string filter by cost center  
label| string filter by label  
fromdate| string filter by from date  
todate| string filter by to date  
project| string filter by project  
sent| boolean filter by sent  
notcompleted| boolean filter by not completed  
ourreference| string filter by our reference  
yourreference| string filter by your reference  
lastmodified| string filter by last modified  
sortby| string Enum: "customerName" "id" "transactionDate" "total" sort returned list of offers  
### Responses
**200**
list of offers
**default**
Error information if the request did not succeed
get/3/offers
Default server
https://api.fortnox.se/3/offers
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Offers": [
    * {
      * "@url": "string",
      * "Cancelled": true,
      * "Currency": "string",
      * "CustomerName": "string",
      * "CustomerNumber": "string",
      * "DocumentNumber": "string",
      * "OfferDate": "2019-08-24",
      * "Project": "string",
      * "Sent": true,
      * "Total": 0.1
}
]

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Offers/operation/create_27)Create an offer 
An endpoint for creating an offer.
Should you have EasyVat enabled, it is mandatory to provide an account in the request should you use a custom VAT rate.
This endpoint can produce errors, some of which may only be relevant for EasyVat. Refer to the table below. 
Errors that can be raised by this endpoint. Error Code | HTTP Code | Description | Solution  
---|---|---|---  
2004167 | 400 | An account must be provided when using a custom VAT rate and EasyVat has been enabled. | Supply each row which has a custom VAT rate with an account.  
##### Request Body schema: */*
to create
Offer| object (fortnox_Offer)   
---|---  
### Responses
**201**
the created offer
**default**
Error information if the request did not succeed
post/3/offers
Default server
https://api.fortnox.se/3/offers
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Offer": {
    * "@url": "string",
    * "@urlTaxReductionList": "string",
    * "Address1": "string",
    * "Address2": "string",
    * "AdministrationFee": 0.1,
    * "AdministrationFeeVAT": 0.1,
    * "BasisTaxReduction": 0.1,
    * "Cancelled": true,
    * "City": "string",
    * "Comments": "string",
    * "ContributionPercent": 0.1,
    * "ContributionValue": 0.1,
    * "CopyRemarks": true,
    * "CostCenter": "string",
    * "Country": "string",
    * "Currency": "string",
    * "CurrencyRate": 0.1,
    * "CurrencyUnit": 0,
    * "CustomerName": "string",
    * "CustomerNumber": "string",
    * "DeliveryAddress1": "string",
    * "DeliveryAddress2": "string",
    * "DeliveryCity": "string",
    * "DeliveryCountry": "string",
    * "DeliveryDate": "2019-08-24",
    * "DeliveryName": "string",
    * "DeliveryZipCode": "string",
    * "DocumentNumber": "string",
    * "EmailInformation": {
      * "EmailAddressBCC": "string",
      * "EmailAddressCC": "string",
      * "EmailAddressFrom": "string",
      * "EmailAddressTo": "string",
      * "EmailBody": "string",
      * "EmailSubject": "string"
},
    * "ExpireDate": "2019-08-24",
    * "Freight": 0.1,
    * "FreightVAT": 0.1,
    * "Gross": 0.1,
    * "HouseWork": true,
    * "InvoiceReference": "string",
    * "Labels": [
      * {
        * "Id": 0
}
],
    * "Language": "string",
    * "Net": 0.1,
    * "NotCompleted": true,
    * "OfferDate": "2019-08-24",
    * "OfferRows": [
      * {
        * "AccountNumber": 0,
        * "ArticleNumber": "string",
        * "ContributionPercent": "string",
        * "ContributionValue": "string",
        * "CostCenter": "string",
        * "Description": "string",
        * "Discount": 0.1,
        * "DiscountType": "AMOUNT",
        * "HouseWork": true,
        * "HouseWorkHoursToReport": 999,
        * "HouseWorkType": "CONSTRUCTION",
        * "Price": 0.1,
        * "Project": "string",
        * "Quantity": "string",
        * "RowId": 0,
        * "Total": 0.1,
        * "Unit": "string",
        * "VAT": 0,
        * "VATCode": "string"
}
],
    * "OrderReference": "string",
    * "OrganisationNumber": "string",
    * "OurReference": "string",
    * "Phone1": "string",
    * "Phone2": "string",
    * "PriceList": "string",
    * "PrintTemplate": "string",
    * "Project": "string",
    * "Remarks": "string",
    * "RoundOff": 0.1,
    * "Sent": true,
    * "TaxReduction": 0,
    * "TaxReductionType": "none",
    * "TermsOfDelivery": "string",
    * "TermsOfPayment": "string",
    * "Total": 0.1,
    * "TotalToPay": 0.1,
    * "TotalVAT": 0.1,
    * "VATIncluded": true,
    * "WayOfDelivery": "string",
    * "YourReference": "string",
    * "YourReferenceNumber": "string",
    * "ZipCode": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Offers/operation/get_32)Retrieve a single offer 
##### path Parameters
DocumentNumberrequired| string identifies the offer  
---|---  
### Responses
**200**
the existing offer
**default**
Error information if the request did not succeed
get/3/offers/{DocumentNumber}
Default server
https://api.fortnox.se/3/offers/{DocumentNumber}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Offer": {
    * "@url": "string",
    * "@urlTaxReductionList": "string",
    * "Address1": "string",
    * "Address2": "string",
    * "AdministrationFee": 0.1,
    * "AdministrationFeeVAT": 0.1,
    * "BasisTaxReduction": 0.1,
    * "Cancelled": true,
    * "City": "string",
    * "Comments": "string",
    * "ContributionPercent": 0.1,
    * "ContributionValue": 0.1,
    * "CopyRemarks": true,
    * "CostCenter": "string",
    * "Country": "string",
    * "Currency": "string",
    * "CurrencyRate": 0.1,
    * "CurrencyUnit": 0,
    * "CustomerName": "string",
    * "CustomerNumber": "string",
    * "DeliveryAddress1": "string",
    * "DeliveryAddress2": "string",
    * "DeliveryCity": "string",
    * "DeliveryCountry": "string",
    * "DeliveryDate": "2019-08-24",
    * "DeliveryName": "string",
    * "DeliveryZipCode": "string",
    * "DocumentNumber": "string",
    * "EmailInformation": {
      * "EmailAddressBCC": "string",
      * "EmailAddressCC": "string",
      * "EmailAddressFrom": "string",
      * "EmailAddressTo": "string",
      * "EmailBody": "string",
      * "EmailSubject": "string"
},
    * "ExpireDate": "2019-08-24",
    * "Freight": 0.1,
    * "FreightVAT": 0.1,
    * "Gross": 0.1,
    * "HouseWork": true,
    * "InvoiceReference": "string",
    * "Labels": [
      * {
        * "Id": 0
}
],
    * "Language": "string",
    * "Net": 0.1,
    * "NotCompleted": true,
    * "OfferDate": "2019-08-24",
    * "OfferRows": [
      * {
        * "AccountNumber": 0,
        * "ArticleNumber": "string",
        * "ContributionPercent": "string",
        * "ContributionValue": "string",
        * "CostCenter": "string",
        * "Description": "string",
        * "Discount": 0.1,
        * "DiscountType": "AMOUNT",
        * "HouseWork": true,
        * "HouseWorkHoursToReport": 999,
        * "HouseWorkType": "CONSTRUCTION",
        * "Price": 0.1,
        * "Project": "string",
        * "Quantity": "string",
        * "RowId": 0,
        * "Total": 0.1,
        * "Unit": "string",
        * "VAT": 0,
        * "VATCode": "string"
}
],
    * "OrderReference": "string",
    * "OrganisationNumber": "string",
    * "OurReference": "string",
    * "Phone1": "string",
    * "Phone2": "string",
    * "PriceList": "string",
    * "PrintTemplate": "string",
    * "Project": "string",
    * "Remarks": "string",
    * "RoundOff": 0.1,
    * "Sent": true,
    * "TaxReduction": 0,
    * "TaxReductionType": "none",
    * "TermsOfDelivery": "string",
    * "TermsOfPayment": "string",
    * "Total": 0.1,
    * "TotalToPay": 0.1,
    * "TotalVAT": 0.1,
    * "VATIncluded": true,
    * "WayOfDelivery": "string",
    * "YourReference": "string",
    * "YourReferenceNumber": "string",
    * "ZipCode": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Offers/operation/update_22)Update an offer 
Note that there are two approaches for updating the rows on an offer.
If RowId is not specified on any row, the rows will be mapped and updated in the order in which they are set in the array. All rows that should remain on the offer needs to be provided.
If RowId is specified on one or more rows the following goes: Corresponding row with that id will be updated. The rows without RowId will be interpreted as new rows. If a row should not be updated but remain on the offer then specify only RowId like { "RowId": 123 }, otherwise it will be removed. Note that new RowIds are generated for all rows every time an offer is updated.
##### path Parameters
DocumentNumberrequired| string identifies the offer  
---|---  
##### Request Body schema: */*
to update
Offer| object (fortnox_Offer)   
---|---  
### Responses
**200**
the updated offer
**default**
Error information if the request did not succeed
put/3/offers/{DocumentNumber}
Default server
https://api.fortnox.se/3/offers/{DocumentNumber}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Offer": {
    * "@url": "string",
    * "@urlTaxReductionList": "string",
    * "Address1": "string",
    * "Address2": "string",
    * "AdministrationFee": 0.1,
    * "AdministrationFeeVAT": 0.1,
    * "BasisTaxReduction": 0.1,
    * "Cancelled": true,
    * "City": "string",
    * "Comments": "string",
    * "ContributionPercent": 0.1,
    * "ContributionValue": 0.1,
    * "CopyRemarks": true,
    * "CostCenter": "string",
    * "Country": "string",
    * "Currency": "string",
    * "CurrencyRate": 0.1,
    * "CurrencyUnit": 0,
    * "CustomerName": "string",
    * "CustomerNumber": "string",
    * "DeliveryAddress1": "string",
    * "DeliveryAddress2": "string",
    * "DeliveryCity": "string",
    * "DeliveryCountry": "string",
    * "DeliveryDate": "2019-08-24",
    * "DeliveryName": "string",
    * "DeliveryZipCode": "string",
    * "DocumentNumber": "string",
    * "EmailInformation": {
      * "EmailAddressBCC": "string",
      * "EmailAddressCC": "string",
      * "EmailAddressFrom": "string",
      * "EmailAddressTo": "string",
      * "EmailBody": "string",
      * "EmailSubject": "string"
},
    * "ExpireDate": "2019-08-24",
    * "Freight": 0.1,
    * "FreightVAT": 0.1,
    * "Gross": 0.1,
    * "HouseWork": true,
    * "InvoiceReference": "string",
    * "Labels": [
      * {
        * "Id": 0
}
],
    * "Language": "string",
    * "Net": 0.1,
    * "NotCompleted": true,
    * "OfferDate": "2019-08-24",
    * "OfferRows": [
      * {
        * "AccountNumber": 0,
        * "ArticleNumber": "string",
        * "ContributionPercent": "string",
        * "ContributionValue": "string",
        * "CostCenter": "string",
        * "Description": "string",
        * "Discount": 0.1,
        * "DiscountType": "AMOUNT",
        * "HouseWork": true,
        * "HouseWorkHoursToReport": 999,
        * "HouseWorkType": "CONSTRUCTION",
        * "Price": 0.1,
        * "Project": "string",
        * "Quantity": "string",
        * "RowId": 0,
        * "Total": 0.1,
        * "Unit": "string",
        * "VAT": 0,
        * "VATCode": "string"
}
],
    * "OrderReference": "string",
    * "OrganisationNumber": "string",
    * "OurReference": "string",
    * "Phone1": "string",
    * "Phone2": "string",
    * "PriceList": "string",
    * "PrintTemplate": "string",
    * "Project": "string",
    * "Remarks": "string",
    * "RoundOff": 0.1,
    * "Sent": true,
    * "TaxReduction": 0,
    * "TaxReductionType": "none",
    * "TermsOfDelivery": "string",
    * "TermsOfPayment": "string",
    * "Total": 0.1,
    * "TotalToPay": 0.1,
    * "TotalVAT": 0.1,
    * "VATIncluded": true,
    * "WayOfDelivery": "string",
    * "YourReference": "string",
    * "YourReferenceNumber": "string",
    * "ZipCode": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Offers/operation/cancel_2)Cancels given offer 
##### path Parameters
DocumentNumberrequired| string identifies the offer  
---|---  
### Responses
**200**
the updated offer
**default**
Error information if the request did not succeed
put/3/offers/{DocumentNumber}/cancel
Default server
https://api.fortnox.se/3/offers/{DocumentNumber}/cancel
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Offer": {
    * "@url": "string",
    * "@urlTaxReductionList": "string",
    * "Address1": "string",
    * "Address2": "string",
    * "AdministrationFee": 0.1,
    * "AdministrationFeeVAT": 0.1,
    * "BasisTaxReduction": 0.1,
    * "Cancelled": true,
    * "City": "string",
    * "Comments": "string",
    * "ContributionPercent": 0.1,
    * "ContributionValue": 0.1,
    * "CopyRemarks": true,
    * "CostCenter": "string",
    * "Country": "string",
    * "Currency": "string",
    * "CurrencyRate": 0.1,
    * "CurrencyUnit": 0,
    * "CustomerName": "string",
    * "CustomerNumber": "string",
    * "DeliveryAddress1": "string",
    * "DeliveryAddress2": "string",
    * "DeliveryCity": "string",
    * "DeliveryCountry": "string",
    * "DeliveryDate": "2019-08-24",
    * "DeliveryName": "string",
    * "DeliveryZipCode": "string",
    * "DocumentNumber": "string",
    * "EmailInformation": {
      * "EmailAddressBCC": "string",
      * "EmailAddressCC": "string",
      * "EmailAddressFrom": "string",
      * "EmailAddressTo": "string",
      * "EmailBody": "string",
      * "EmailSubject": "string"
},
    * "ExpireDate": "2019-08-24",
    * "Freight": 0.1,
    * "FreightVAT": 0.1,
    * "Gross": 0.1,
    * "HouseWork": true,
    * "InvoiceReference": "string",
    * "Labels": [
      * {
        * "Id": 0
}
],
    * "Language": "string",
    * "Net": 0.1,
    * "NotCompleted": true,
    * "OfferDate": "2019-08-24",
    * "OfferRows": [
      * {
        * "AccountNumber": 0,
        * "ArticleNumber": "string",
        * "ContributionPercent": "string",
        * "ContributionValue": "string",
        * "CostCenter": "string",
        * "Description": "string",
        * "Discount": 0.1,
        * "DiscountType": "AMOUNT",
        * "HouseWork": true,
        * "HouseWorkHoursToReport": 999,
        * "HouseWorkType": "CONSTRUCTION",
        * "Price": 0.1,
        * "Project": "string",
        * "Quantity": "string",
        * "RowId": 0,
        * "Total": 0.1,
        * "Unit": "string",
        * "VAT": 0,
        * "VATCode": "string"
}
],
    * "OrderReference": "string",
    * "OrganisationNumber": "string",
    * "OurReference": "string",
    * "Phone1": "string",
    * "Phone2": "string",
    * "PriceList": "string",
    * "PrintTemplate": "string",
    * "Project": "string",
    * "Remarks": "string",
    * "RoundOff": 0.1,
    * "Sent": true,
    * "TaxReduction": 0,
    * "TaxReductionType": "none",
    * "TermsOfDelivery": "string",
    * "TermsOfPayment": "string",
    * "Total": 0.1,
    * "TotalToPay": 0.1,
    * "TotalVAT": 0.1,
    * "VATIncluded": true,
    * "WayOfDelivery": "string",
    * "YourReference": "string",
    * "YourReferenceNumber": "string",
    * "ZipCode": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Offers/operation/createinvoice_1)Create invoice out of given offer 
##### path Parameters
DocumentNumberrequired| string identifies the offer  
---|---  
### Responses
**200**
the created invoice
**default**
Error information if the request did not succeed
put/3/offers/{DocumentNumber}/createinvoice
Default server
https://api.fortnox.se/3/offers/{DocumentNumber}/createinvoice
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Order": {
    * "@url": "string",
    * "@urlTaxReductionList": "string",
    * "Address1": "string",
    * "Address2": "string",
    * "AdministrationFee": 0.1,
    * "AdministrationFeeVAT": 0.1,
    * "BasisTaxReduction": 0.1,
    * "Cancelled": true,
    * "City": "string",
    * "Comments": "string",
    * "ContributionPercent": 0.1,
    * "ContributionValue": 0.1,
    * "CopyRemarks": true,
    * "CostCenter": "string",
    * "Country": "string",
    * "Currency": "str",
    * "CurrencyRate": 0.1,
    * "CurrencyUnit": 0.1,
    * "CustomerName": "string",
    * "CustomerNumber": "string",
    * "DeliveryAddress1": "string",
    * "DeliveryAddress2": "string",
    * "DeliveryCity": "string",
    * "DeliveryCountry": "string",
    * "DeliveryDate": "2019-08-24",
    * "DeliveryName": "string",
    * "DeliveryState": "registration",
    * "DeliveryZipCode": "string",
    * "DocumentNumber": "string",
    * "EmailInformation": {
      * "EmailAddressBCC": "string",
      * "EmailAddressCC": "string",
      * "EmailAddressFrom": "string",
      * "EmailAddressTo": "string",
      * "EmailBody": "string",
      * "EmailSubject": "string"
},
    * "ExternalInvoiceReference1": "string",
    * "ExternalInvoiceReference2": "string",
    * "Freight": 0.1,
    * "FreightVAT": 0.1,
    * "Gross": 0.1,
    * "HouseWork": true,
    * "InvoiceReference": "string",
    * "Labels": [
      * {
        * "Id": 0
}
],
    * "Language": "string",
    * "Net": 0.1,
    * "NotCompleted": true,
    * "OfferReference": "string",
    * "OrderDate": "2019-08-24",
    * "OrderRows": [
      * {
        * "AccountNumber": 0,
        * "ArticleNumber": "string",
        * "ContributionPercent": "string",
        * "ContributionValue": "string",
        * "CostCenter": "string",
        * "DeliveredQuantity": "string",
        * "Description": "string",
        * "Discount": 0.1,
        * "DiscountType": "AMOUNT",
        * "HouseWork": true,
        * "HouseWorkHoursToReport": 0,
        * "HouseWorkType": "CONSTRUCTION",
        * "OrderedQuantity": "string",
        * "Price": 0.1,
        * "Project": "string",
        * "ReservedQuantity": "string",
        * "RowId": 0,
        * "StockPointCode": "string",
        * "StockPointId": "string",
        * "Total": 0.1,
        * "Unit": "string",
        * "VAT": 0.1,
        * "VATCode": "string"
}
],
    * "OrderType": "string",
    * "OrganisationNumber": "string",
    * "OurReference": "string",
    * "OutboundDate": "2019-08-24",
    * "Phone1": "string",
    * "Phone2": "string",
    * "PriceList": "string",
    * "PrintTemplate": "string",
    * "Project": "string",
    * "Remarks": "string",
    * "RoundOff": 0.1,
    * "Sent": true,
    * "StockPointCode": "string",
    * "StockPointId": "string",
    * "TaxReduction": 0.1,
    * "TaxReductionType": "none",
    * "TermsOfDelivery": "string",
    * "TermsOfPayment": "string",
    * "TimeBasisReference": 0,
    * "Total": 0.1,
    * "TotalToPay": 0.1,
    * "TotalVAT": 0.1,
    * "VATIncluded": true,
    * "WarehouseReady": true,
    * "WayOfDelivery": "string",
    * "YourOrderNumber": "string",
    * "YourReference": "string",
    * "ZipCode": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Offers/operation/createorder)Create order out of given offer 
##### path Parameters
DocumentNumberrequired| string identifies the offer  
---|---  
### Responses
**200**
the created order
**default**
Error information if the request did not succeed
put/3/offers/{DocumentNumber}/createorder
Default server
https://api.fortnox.se/3/offers/{DocumentNumber}/createorder
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Order": {
    * "@url": "string",
    * "@urlTaxReductionList": "string",
    * "Address1": "string",
    * "Address2": "string",
    * "AdministrationFee": 0.1,
    * "AdministrationFeeVAT": 0.1,
    * "BasisTaxReduction": 0.1,
    * "Cancelled": true,
    * "City": "string",
    * "Comments": "string",
    * "ContributionPercent": 0.1,
    * "ContributionValue": 0.1,
    * "CopyRemarks": true,
    * "CostCenter": "string",
    * "Country": "string",
    * "Currency": "str",
    * "CurrencyRate": 0.1,
    * "CurrencyUnit": 0.1,
    * "CustomerName": "string",
    * "CustomerNumber": "string",
    * "DeliveryAddress1": "string",
    * "DeliveryAddress2": "string",
    * "DeliveryCity": "string",
    * "DeliveryCountry": "string",
    * "DeliveryDate": "2019-08-24",
    * "DeliveryName": "string",
    * "DeliveryState": "registration",
    * "DeliveryZipCode": "string",
    * "DocumentNumber": "string",
    * "EmailInformation": {
      * "EmailAddressBCC": "string",
      * "EmailAddressCC": "string",
      * "EmailAddressFrom": "string",
      * "EmailAddressTo": "string",
      * "EmailBody": "string",
      * "EmailSubject": "string"
},
    * "ExternalInvoiceReference1": "string",
    * "ExternalInvoiceReference2": "string",
    * "Freight": 0.1,
    * "FreightVAT": 0.1,
    * "Gross": 0.1,
    * "HouseWork": true,
    * "InvoiceReference": "string",
    * "Labels": [
      * {
        * "Id": 0
}
],
    * "Language": "string",
    * "Net": 0.1,
    * "NotCompleted": true,
    * "OfferReference": "string",
    * "OrderDate": "2019-08-24",
    * "OrderRows": [
      * {
        * "AccountNumber": 0,
        * "ArticleNumber": "string",
        * "ContributionPercent": "string",
        * "ContributionValue": "string",
        * "CostCenter": "string",
        * "DeliveredQuantity": "string",
        * "Description": "string",
        * "Discount": 0.1,
        * "DiscountType": "AMOUNT",
        * "HouseWork": true,
        * "HouseWorkHoursToReport": 0,
        * "HouseWorkType": "CONSTRUCTION",
        * "OrderedQuantity": "string",
        * "Price": 0.1,
        * "Project": "string",
        * "ReservedQuantity": "string",
        * "RowId": 0,
        * "StockPointCode": "string",
        * "StockPointId": "string",
        * "Total": 0.1,
        * "Unit": "string",
        * "VAT": 0.1,
        * "VATCode": "string"
}
],
    * "OrderType": "string",
    * "OrganisationNumber": "string",
    * "OurReference": "string",
    * "OutboundDate": "2019-08-24",
    * "Phone1": "string",
    * "Phone2": "string",
    * "PriceList": "string",
    * "PrintTemplate": "string",
    * "Project": "string",
    * "Remarks": "string",
    * "RoundOff": 0.1,
    * "Sent": true,
    * "StockPointCode": "string",
    * "StockPointId": "string",
    * "TaxReduction": 0.1,
    * "TaxReductionType": "none",
    * "TermsOfDelivery": "string",
    * "TermsOfPayment": "string",
    * "TimeBasisReference": 0,
    * "Total": 0.1,
    * "TotalToPay": 0.1,
    * "TotalVAT": 0.1,
    * "VATIncluded": true,
    * "WarehouseReady": true,
    * "WayOfDelivery": "string",
    * "YourOrderNumber": "string",
    * "YourReference": "string",
    * "ZipCode": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Offers/operation/email_2)Send given offer as email 
You can use the properties in the EmailInformation to customize the e-mail message on each offer.
##### path Parameters
DocumentNumberrequired| string identifies the offer  
---|---  
### Responses
**200**
the existing offer
**default**
Error information if the request did not succeed
get/3/offers/{DocumentNumber}/email
Default server
https://api.fortnox.se/3/offers/{DocumentNumber}/email
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Offer": {
    * "@url": "string",
    * "@urlTaxReductionList": "string",
    * "Address1": "string",
    * "Address2": "string",
    * "AdministrationFee": 0.1,
    * "AdministrationFeeVAT": 0.1,
    * "BasisTaxReduction": 0.1,
    * "Cancelled": true,
    * "City": "string",
    * "Comments": "string",
    * "ContributionPercent": 0.1,
    * "ContributionValue": 0.1,
    * "CopyRemarks": true,
    * "CostCenter": "string",
    * "Country": "string",
    * "Currency": "string",
    * "CurrencyRate": 0.1,
    * "CurrencyUnit": 0,
    * "CustomerName": "string",
    * "CustomerNumber": "string",
    * "DeliveryAddress1": "string",
    * "DeliveryAddress2": "string",
    * "DeliveryCity": "string",
    * "DeliveryCountry": "string",
    * "DeliveryDate": "2019-08-24",
    * "DeliveryName": "string",
    * "DeliveryZipCode": "string",
    * "DocumentNumber": "string",
    * "EmailInformation": {
      * "EmailAddressBCC": "string",
      * "EmailAddressCC": "string",
      * "EmailAddressFrom": "string",
      * "EmailAddressTo": "string",
      * "EmailBody": "string",
      * "EmailSubject": "string"
},
    * "ExpireDate": "2019-08-24",
    * "Freight": 0.1,
    * "FreightVAT": 0.1,
    * "Gross": 0.1,
    * "HouseWork": true,
    * "InvoiceReference": "string",
    * "Labels": [
      * {
        * "Id": 0
}
],
    * "Language": "string",
    * "Net": 0.1,
    * "NotCompleted": true,
    * "OfferDate": "2019-08-24",
    * "OfferRows": [
      * {
        * "AccountNumber": 0,
        * "ArticleNumber": "string",
        * "ContributionPercent": "string",
        * "ContributionValue": "string",
        * "CostCenter": "string",
        * "Description": "string",
        * "Discount": 0.1,
        * "DiscountType": "AMOUNT",
        * "HouseWork": true,
        * "HouseWorkHoursToReport": 999,
        * "HouseWorkType": "CONSTRUCTION",
        * "Price": 0.1,
        * "Project": "string",
        * "Quantity": "string",
        * "RowId": 0,
        * "Total": 0.1,
        * "Unit": "string",
        * "VAT": 0,
        * "VATCode": "string"
}
],
    * "OrderReference": "string",
    * "OrganisationNumber": "string",
    * "OurReference": "string",
    * "Phone1": "string",
    * "Phone2": "string",
    * "PriceList": "string",
    * "PrintTemplate": "string",
    * "Project": "string",
    * "Remarks": "string",
    * "RoundOff": 0.1,
    * "Sent": true,
    * "TaxReduction": 0,
    * "TaxReductionType": "none",
    * "TermsOfDelivery": "string",
    * "TermsOfPayment": "string",
    * "Total": 0.1,
    * "TotalToPay": 0.1,
    * "TotalVAT": 0.1,
    * "VATIncluded": true,
    * "WayOfDelivery": "string",
    * "YourReference": "string",
    * "YourReferenceNumber": "string",
    * "ZipCode": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Offers/operation/externalprint)Set given offer as sent 
Use this endpoint to set offer as sent, without generating an offer.
##### path Parameters
DocumentNumberrequired| string identifies the offer  
---|---  
### Responses
**200**
the updated offer
**default**
Error information if the request did not succeed
put/3/offers/{DocumentNumber}/externalprint
Default server
https://api.fortnox.se/3/offers/{DocumentNumber}/externalprint
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Offer": {
    * "@url": "string",
    * "@urlTaxReductionList": "string",
    * "Address1": "string",
    * "Address2": "string",
    * "AdministrationFee": 0.1,
    * "AdministrationFeeVAT": 0.1,
    * "BasisTaxReduction": 0.1,
    * "Cancelled": true,
    * "City": "string",
    * "Comments": "string",
    * "ContributionPercent": 0.1,
    * "ContributionValue": 0.1,
    * "CopyRemarks": true,
    * "CostCenter": "string",
    * "Country": "string",
    * "Currency": "string",
    * "CurrencyRate": 0.1,
    * "CurrencyUnit": 0,
    * "CustomerName": "string",
    * "CustomerNumber": "string",
    * "DeliveryAddress1": "string",
    * "DeliveryAddress2": "string",
    * "DeliveryCity": "string",
    * "DeliveryCountry": "string",
    * "DeliveryDate": "2019-08-24",
    * "DeliveryName": "string",
    * "DeliveryZipCode": "string",
    * "DocumentNumber": "string",
    * "EmailInformation": {
      * "EmailAddressBCC": "string",
      * "EmailAddressCC": "string",
      * "EmailAddressFrom": "string",
      * "EmailAddressTo": "string",
      * "EmailBody": "string",
      * "EmailSubject": "string"
},
    * "ExpireDate": "2019-08-24",
    * "Freight": 0.1,
    * "FreightVAT": 0.1,
    * "Gross": 0.1,
    * "HouseWork": true,
    * "InvoiceReference": "string",
    * "Labels": [
      * {
        * "Id": 0
}
],
    * "Language": "string",
    * "Net": 0.1,
    * "NotCompleted": true,
    * "OfferDate": "2019-08-24",
    * "OfferRows": [
      * {
        * "AccountNumber": 0,
        * "ArticleNumber": "string",
        * "ContributionPercent": "string",
        * "ContributionValue": "string",
        * "CostCenter": "string",
        * "Description": "string",
        * "Discount": 0.1,
        * "DiscountType": "AMOUNT",
        * "HouseWork": true,
        * "HouseWorkHoursToReport": 999,
        * "HouseWorkType": "CONSTRUCTION",
        * "Price": 0.1,
        * "Project": "string",
        * "Quantity": "string",
        * "RowId": 0,
        * "Total": 0.1,
        * "Unit": "string",
        * "VAT": 0,
        * "VATCode": "string"
}
],
    * "OrderReference": "string",
    * "OrganisationNumber": "string",
    * "OurReference": "string",
    * "Phone1": "string",
    * "Phone2": "string",
    * "PriceList": "string",
    * "PrintTemplate": "string",
    * "Project": "string",
    * "Remarks": "string",
    * "RoundOff": 0.1,
    * "Sent": true,
    * "TaxReduction": 0,
    * "TaxReductionType": "none",
    * "TermsOfDelivery": "string",
    * "TermsOfPayment": "string",
    * "Total": 0.1,
    * "TotalToPay": 0.1,
    * "TotalVAT": 0.1,
    * "VATIncluded": true,
    * "WayOfDelivery": "string",
    * "YourReference": "string",
    * "YourReferenceNumber": "string",
    * "ZipCode": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Offers/operation/preview_2)Preview given offer 
The difference between this and the print-endpoint is that property Sent is not set to TRUE.
##### path Parameters
DocumentNumberrequired| string identifies the offer  
---|---  
### Responses
**200**
the existing offer
**default**
Error information if the request did not succeed
get/3/offers/{DocumentNumber}/preview
Default server
https://api.fortnox.se/3/offers/{DocumentNumber}/preview
## [](https://api.fortnox.se/apidocs#tag/fortnox_Offers/operation/print_2)Print given offer 
##### path Parameters
DocumentNumberrequired| string identifies the offer  
---|---  
### Responses
**200**
the existing offer
**default**
Error information if the request did not succeed
get/3/offers/{DocumentNumber}/print
Default server
https://api.fortnox.se/3/offers/{DocumentNumber}/print
# [](https://api.fortnox.se/apidocs#tag/fortnox_Orders)Orders
Possible filters on Orders endpoint **Filter** | **Description**  
---|---  
cancelled | Retrieves all orders with the status "cancelled"  
expired | Retrieves all orders that has been expired  
invoicecreated | Retrieves all offers where an invoice has been created  
invoicenotcreated | Retrieves all orders where an invoice has not been created  
For information about how to use filters, please read this article.
## [](https://api.fortnox.se/apidocs#tag/fortnox_Orders/operation/list_26)Retrieve a list of orders 
##### query Parameters
filter| string Enum: "cancelled" "expired" "invoicecreated" "invoicenotcreated" possibility to filter orders  
---|---  
customername| string filter by customer name  
customernumber| string filter by customer number  
label| string filter by label  
documentnumber| string filter by document number  
externalinvoicereference1| string filter by external invoice reference 1  
externalinvoicereference2| string filter by external invoice reference 2  
fromdate| string filter by from date  
todate| string filter by to date  
costcenter| string filter by cost center  
project| string filter by project  
sent| boolean filter by sent  
notcompleted| boolean filter by not completed  
ourreference| string filter by ourreference  
yourreference| string filter by your reference  
lastmodified| string filter by lastmodified  
ordertype| string filter by order type  
sortby| string Enum: "customername" "customernumber" "orderdate" "documentnumber" "total" field to sort returned list  
### Responses
**200**
list of orders
**default**
Error information if the request did not succeed
get/3/orders
Default server
https://api.fortnox.se/3/orders
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Orders": [
    * {
      * "@url": "string",
      * "Cancelled": true,
      * "Currency": "str",
      * "CustomerName": "string",
      * "CustomerNumber": "string",
      * "DeliveryDate": "2019-08-24",
      * "DocumentNumber": "string",
      * "ExternalInvoiceReference1": "string",
      * "ExternalInvoiceReference2": "string",
      * "OrderDate": "2019-08-24",
      * "OrderType": "string",
      * "Project": "string",
      * "Sent": true,
      * "Total": 0.1
}
]

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Orders/operation/create_29)Create a new order 
An endpoint for creating an order.
Should you have EasyVat enabled, it is mandatory to provide an account in the request should you use a custom VAT rate.
This endpoint can produce errors, some of which may only be relevant for EasyVat. Refer to the table below. 
Errors that can be raised by this endpoint. Error Code | HTTP Code | Description | Solution  
---|---|---|---  
2004167 | 400 | An account must be provided when using a custom VAT rate and EasyVat has been enabled. | Supply each row which has a custom VAT rate with an account.  
##### Request Body schema: */*
order to create
Order| object (fortnox_Order)   
---|---  
### Responses
**201**
the created order
**default**
Error information if the request did not succeed
post/3/orders
Default server
https://api.fortnox.se/3/orders
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Order": {
    * "@url": "string",
    * "@urlTaxReductionList": "string",
    * "Address1": "string",
    * "Address2": "string",
    * "AdministrationFee": 0.1,
    * "AdministrationFeeVAT": 0.1,
    * "BasisTaxReduction": 0.1,
    * "Cancelled": true,
    * "City": "string",
    * "Comments": "string",
    * "ContributionPercent": 0.1,
    * "ContributionValue": 0.1,
    * "CopyRemarks": true,
    * "CostCenter": "string",
    * "Country": "string",
    * "Currency": "str",
    * "CurrencyRate": 0.1,
    * "CurrencyUnit": 0.1,
    * "CustomerName": "string",
    * "CustomerNumber": "string",
    * "DeliveryAddress1": "string",
    * "DeliveryAddress2": "string",
    * "DeliveryCity": "string",
    * "DeliveryCountry": "string",
    * "DeliveryDate": "2019-08-24",
    * "DeliveryName": "string",
    * "DeliveryState": "registration",
    * "DeliveryZipCode": "string",
    * "DocumentNumber": "string",
    * "EmailInformation": {
      * "EmailAddressBCC": "string",
      * "EmailAddressCC": "string",
      * "EmailAddressFrom": "string",
      * "EmailAddressTo": "string",
      * "EmailBody": "string",
      * "EmailSubject": "string"
},
    * "ExternalInvoiceReference1": "string",
    * "ExternalInvoiceReference2": "string",
    * "Freight": 0.1,
    * "FreightVAT": 0.1,
    * "Gross": 0.1,
    * "HouseWork": true,
    * "InvoiceReference": "string",
    * "Labels": [
      * {
        * "Id": 0
}
],
    * "Language": "string",
    * "Net": 0.1,
    * "NotCompleted": true,
    * "OfferReference": "string",
    * "OrderDate": "2019-08-24",
    * "OrderRows": [
      * {
        * "AccountNumber": 0,
        * "ArticleNumber": "string",
        * "ContributionPercent": "string",
        * "ContributionValue": "string",
        * "CostCenter": "string",
        * "DeliveredQuantity": "string",
        * "Description": "string",
        * "Discount": 0.1,
        * "DiscountType": "AMOUNT",
        * "HouseWork": true,
        * "HouseWorkHoursToReport": 0,
        * "HouseWorkType": "CONSTRUCTION",
        * "OrderedQuantity": "string",
        * "Price": 0.1,
        * "Project": "string",
        * "ReservedQuantity": "string",
        * "RowId": 0,
        * "StockPointCode": "string",
        * "StockPointId": "string",
        * "Total": 0.1,
        * "Unit": "string",
        * "VAT": 0.1,
        * "VATCode": "string"
}
],
    * "OrderType": "string",
    * "OrganisationNumber": "string",
    * "OurReference": "string",
    * "OutboundDate": "2019-08-24",
    * "Phone1": "string",
    * "Phone2": "string",
    * "PriceList": "string",
    * "PrintTemplate": "string",
    * "Project": "string",
    * "Remarks": "string",
    * "RoundOff": 0.1,
    * "Sent": true,
    * "StockPointCode": "string",
    * "StockPointId": "string",
    * "TaxReduction": 0.1,
    * "TaxReductionType": "none",
    * "TermsOfDelivery": "string",
    * "TermsOfPayment": "string",
    * "TimeBasisReference": 0,
    * "Total": 0.1,
    * "TotalToPay": 0.1,
    * "TotalVAT": 0.1,
    * "VATIncluded": true,
    * "WarehouseReady": true,
    * "WayOfDelivery": "string",
    * "YourOrderNumber": "string",
    * "YourReference": "string",
    * "ZipCode": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Orders/operation/get_34)Retrieve a single order 
##### path Parameters
DocumentNumberrequired| string identifies the order  
---|---  
### Responses
**200**
the existing order
**default**
Error information if the request did not succeed
get/3/orders/{DocumentNumber}
Default server
https://api.fortnox.se/3/orders/{DocumentNumber}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Order": {
    * "@url": "string",
    * "@urlTaxReductionList": "string",
    * "Address1": "string",
    * "Address2": "string",
    * "AdministrationFee": 0.1,
    * "AdministrationFeeVAT": 0.1,
    * "BasisTaxReduction": 0.1,
    * "Cancelled": true,
    * "City": "string",
    * "Comments": "string",
    * "ContributionPercent": 0.1,
    * "ContributionValue": 0.1,
    * "CopyRemarks": true,
    * "CostCenter": "string",
    * "Country": "string",
    * "Currency": "str",
    * "CurrencyRate": 0.1,
    * "CurrencyUnit": 0.1,
    * "CustomerName": "string",
    * "CustomerNumber": "string",
    * "DeliveryAddress1": "string",
    * "DeliveryAddress2": "string",
    * "DeliveryCity": "string",
    * "DeliveryCountry": "string",
    * "DeliveryDate": "2019-08-24",
    * "DeliveryName": "string",
    * "DeliveryState": "registration",
    * "DeliveryZipCode": "string",
    * "DocumentNumber": "string",
    * "EmailInformation": {
      * "EmailAddressBCC": "string",
      * "EmailAddressCC": "string",
      * "EmailAddressFrom": "string",
      * "EmailAddressTo": "string",
      * "EmailBody": "string",
      * "EmailSubject": "string"
},
    * "ExternalInvoiceReference1": "string",
    * "ExternalInvoiceReference2": "string",
    * "Freight": 0.1,
    * "FreightVAT": 0.1,
    * "Gross": 0.1,
    * "HouseWork": true,
    * "InvoiceReference": "string",
    * "Labels": [
      * {
        * "Id": 0
}
],
    * "Language": "string",
    * "Net": 0.1,
    * "NotCompleted": true,
    * "OfferReference": "string",
    * "OrderDate": "2019-08-24",
    * "OrderRows": [
      * {
        * "AccountNumber": 0,
        * "ArticleNumber": "string",
        * "ContributionPercent": "string",
        * "ContributionValue": "string",
        * "CostCenter": "string",
        * "DeliveredQuantity": "string",
        * "Description": "string",
        * "Discount": 0.1,
        * "DiscountType": "AMOUNT",
        * "HouseWork": true,
        * "HouseWorkHoursToReport": 0,
        * "HouseWorkType": "CONSTRUCTION",
        * "OrderedQuantity": "string",
        * "Price": 0.1,
        * "Project": "string",
        * "ReservedQuantity": "string",
        * "RowId": 0,
        * "StockPointCode": "string",
        * "StockPointId": "string",
        * "Total": 0.1,
        * "Unit": "string",
        * "VAT": 0.1,
        * "VATCode": "string"
}
],
    * "OrderType": "string",
    * "OrganisationNumber": "string",
    * "OurReference": "string",
    * "OutboundDate": "2019-08-24",
    * "Phone1": "string",
    * "Phone2": "string",
    * "PriceList": "string",
    * "PrintTemplate": "string",
    * "Project": "string",
    * "Remarks": "string",
    * "RoundOff": 0.1,
    * "Sent": true,
    * "StockPointCode": "string",
    * "StockPointId": "string",
    * "TaxReduction": 0.1,
    * "TaxReductionType": "none",
    * "TermsOfDelivery": "string",
    * "TermsOfPayment": "string",
    * "TimeBasisReference": 0,
    * "Total": 0.1,
    * "TotalToPay": 0.1,
    * "TotalVAT": 0.1,
    * "VATIncluded": true,
    * "WarehouseReady": true,
    * "WayOfDelivery": "string",
    * "YourOrderNumber": "string",
    * "YourReference": "string",
    * "ZipCode": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Orders/operation/update_24)Update an order 
Note that there are two approaches for updating the rows on an order.
If RowId is not specified on any row, the rows will be mapped and updated in the order in which they are set in the array. All rows that should remain on the order needs to be provided.
If RowId is specified on one or more rows the following goes: Corresponding row with that id will be updated. The rows without RowId will be interpreted as new rows. If a row should not be updated but remain on the order then specify only RowId like { "RowId": 123 }, otherwise it will be removed. Note that new RowIds are generated for all rows every time an order is updated.
##### path Parameters
DocumentNumberrequired| string identifies the order  
---|---  
##### Request Body schema: */*
order to update
Order| object (fortnox_Order)   
---|---  
### Responses
**200**
the updated order
**default**
Error information if the request did not succeed
put/3/orders/{DocumentNumber}
Default server
https://api.fortnox.se/3/orders/{DocumentNumber}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Order": {
    * "@url": "string",
    * "@urlTaxReductionList": "string",
    * "Address1": "string",
    * "Address2": "string",
    * "AdministrationFee": 0.1,
    * "AdministrationFeeVAT": 0.1,
    * "BasisTaxReduction": 0.1,
    * "Cancelled": true,
    * "City": "string",
    * "Comments": "string",
    * "ContributionPercent": 0.1,
    * "ContributionValue": 0.1,
    * "CopyRemarks": true,
    * "CostCenter": "string",
    * "Country": "string",
    * "Currency": "str",
    * "CurrencyRate": 0.1,
    * "CurrencyUnit": 0.1,
    * "CustomerName": "string",
    * "CustomerNumber": "string",
    * "DeliveryAddress1": "string",
    * "DeliveryAddress2": "string",
    * "DeliveryCity": "string",
    * "DeliveryCountry": "string",
    * "DeliveryDate": "2019-08-24",
    * "DeliveryName": "string",
    * "DeliveryState": "registration",
    * "DeliveryZipCode": "string",
    * "DocumentNumber": "string",
    * "EmailInformation": {
      * "EmailAddressBCC": "string",
      * "EmailAddressCC": "string",
      * "EmailAddressFrom": "string",
      * "EmailAddressTo": "string",
      * "EmailBody": "string",
      * "EmailSubject": "string"
},
    * "ExternalInvoiceReference1": "string",
    * "ExternalInvoiceReference2": "string",
    * "Freight": 0.1,
    * "FreightVAT": 0.1,
    * "Gross": 0.1,
    * "HouseWork": true,
    * "InvoiceReference": "string",
    * "Labels": [
      * {
        * "Id": 0
}
],
    * "Language": "string",
    * "Net": 0.1,
    * "NotCompleted": true,
    * "OfferReference": "string",
    * "OrderDate": "2019-08-24",
    * "OrderRows": [
      * {
        * "AccountNumber": 0,
        * "ArticleNumber": "string",
        * "ContributionPercent": "string",
        * "ContributionValue": "string",
        * "CostCenter": "string",
        * "DeliveredQuantity": "string",
        * "Description": "string",
        * "Discount": 0.1,
        * "DiscountType": "AMOUNT",
        * "HouseWork": true,
        * "HouseWorkHoursToReport": 0,
        * "HouseWorkType": "CONSTRUCTION",
        * "OrderedQuantity": "string",
        * "Price": 0.1,
        * "Project": "string",
        * "ReservedQuantity": "string",
        * "RowId": 0,
        * "StockPointCode": "string",
        * "StockPointId": "string",
        * "Total": 0.1,
        * "Unit": "string",
        * "VAT": 0.1,
        * "VATCode": "string"
}
],
    * "OrderType": "string",
    * "OrganisationNumber": "string",
    * "OurReference": "string",
    * "OutboundDate": "2019-08-24",
    * "Phone1": "string",
    * "Phone2": "string",
    * "PriceList": "string",
    * "PrintTemplate": "string",
    * "Project": "string",
    * "Remarks": "string",
    * "RoundOff": 0.1,
    * "Sent": true,
    * "StockPointCode": "string",
    * "StockPointId": "string",
    * "TaxReduction": 0.1,
    * "TaxReductionType": "none",
    * "TermsOfDelivery": "string",
    * "TermsOfPayment": "string",
    * "TimeBasisReference": 0,
    * "Total": 0.1,
    * "TotalToPay": 0.1,
    * "TotalVAT": 0.1,
    * "VATIncluded": true,
    * "WarehouseReady": true,
    * "WayOfDelivery": "string",
    * "YourOrderNumber": "string",
    * "YourReference": "string",
    * "ZipCode": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Orders/operation/cancel_4)Cancels given order 
##### path Parameters
DocumentNumberrequired| string identifies the order  
---|---  
### Responses
**200**
the updated order
**default**
Error information if the request did not succeed
put/3/orders/{DocumentNumber}/cancel
Default server
https://api.fortnox.se/3/orders/{DocumentNumber}/cancel
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Order": {
    * "@url": "string",
    * "@urlTaxReductionList": "string",
    * "Address1": "string",
    * "Address2": "string",
    * "AdministrationFee": 0.1,
    * "AdministrationFeeVAT": 0.1,
    * "BasisTaxReduction": 0.1,
    * "Cancelled": true,
    * "City": "string",
    * "Comments": "string",
    * "ContributionPercent": 0.1,
    * "ContributionValue": 0.1,
    * "CopyRemarks": true,
    * "CostCenter": "string",
    * "Country": "string",
    * "Currency": "str",
    * "CurrencyRate": 0.1,
    * "CurrencyUnit": 0.1,
    * "CustomerName": "string",
    * "CustomerNumber": "string",
    * "DeliveryAddress1": "string",
    * "DeliveryAddress2": "string",
    * "DeliveryCity": "string",
    * "DeliveryCountry": "string",
    * "DeliveryDate": "2019-08-24",
    * "DeliveryName": "string",
    * "DeliveryState": "registration",
    * "DeliveryZipCode": "string",
    * "DocumentNumber": "string",
    * "EmailInformation": {
      * "EmailAddressBCC": "string",
      * "EmailAddressCC": "string",
      * "EmailAddressFrom": "string",
      * "EmailAddressTo": "string",
      * "EmailBody": "string",
      * "EmailSubject": "string"
},
    * "ExternalInvoiceReference1": "string",
    * "ExternalInvoiceReference2": "string",
    * "Freight": 0.1,
    * "FreightVAT": 0.1,
    * "Gross": 0.1,
    * "HouseWork": true,
    * "InvoiceReference": "string",
    * "Labels": [
      * {
        * "Id": 0
}
],
    * "Language": "string",
    * "Net": 0.1,
    * "NotCompleted": true,
    * "OfferReference": "string",
    * "OrderDate": "2019-08-24",
    * "OrderRows": [
      * {
        * "AccountNumber": 0,
        * "ArticleNumber": "string",
        * "ContributionPercent": "string",
        * "ContributionValue": "string",
        * "CostCenter": "string",
        * "DeliveredQuantity": "string",
        * "Description": "string",
        * "Discount": 0.1,
        * "DiscountType": "AMOUNT",
        * "HouseWork": true,
        * "HouseWorkHoursToReport": 0,
        * "HouseWorkType": "CONSTRUCTION",
        * "OrderedQuantity": "string",
        * "Price": 0.1,
        * "Project": "string",
        * "ReservedQuantity": "string",
        * "RowId": 0,
        * "StockPointCode": "string",
        * "StockPointId": "string",
        * "Total": 0.1,
        * "Unit": "string",
        * "VAT": 0.1,
        * "VATCode": "string"
}
],
    * "OrderType": "string",
    * "OrganisationNumber": "string",
    * "OurReference": "string",
    * "OutboundDate": "2019-08-24",
    * "Phone1": "string",
    * "Phone2": "string",
    * "PriceList": "string",
    * "PrintTemplate": "string",
    * "Project": "string",
    * "Remarks": "string",
    * "RoundOff": 0.1,
    * "Sent": true,
    * "StockPointCode": "string",
    * "StockPointId": "string",
    * "TaxReduction": 0.1,
    * "TaxReductionType": "none",
    * "TermsOfDelivery": "string",
    * "TermsOfPayment": "string",
    * "TimeBasisReference": 0,
    * "Total": 0.1,
    * "TotalToPay": 0.1,
    * "TotalVAT": 0.1,
    * "VATIncluded": true,
    * "WarehouseReady": true,
    * "WayOfDelivery": "string",
    * "YourOrderNumber": "string",
    * "YourReference": "string",
    * "ZipCode": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Orders/operation/createinvoice_3)Create invoice out of given order 
##### path Parameters
DocumentNumberrequired| string identifies the order  
---|---  
### Responses
**200**
the created invoice
**default**
Error information if the request did not succeed
put/3/orders/{DocumentNumber}/createinvoice
Default server
https://api.fortnox.se/3/orders/{DocumentNumber}/createinvoice
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Invoice": {
    * "@url": "string",
    * "@urlTaxReductionList": "string",
    * "AccountingMethod": "ACCRUAL",
    * "Address1": "string",
    * "Address2": "string",
    * "AdministrationFee": 0.1,
    * "AdministrationFeeVAT": 0.1,
    * "Balance": 0.1,
    * "BasisTaxReduction": 0.1,
    * "Booked": true,
    * "Cancelled": true,
    * "City": "string",
    * "Comments": "string",
    * "ContractReference": 0,
    * "ContributionPercent": 0.1,
    * "ContributionValue": 0.1,
    * "CostCenter": "string",
    * "Country": "string",
    * "Credit": "string",
    * "CreditInvoiceReference": "string",
    * "Currency": "string",
    * "CurrencyRate": 0.1,
    * "CurrencyUnit": 0,
    * "CustomerName": "string",
    * "CustomerNumber": "string",
    * "DeliveryAddress1": "string",
    * "DeliveryAddress2": "string",
    * "DeliveryCity": "string",
    * "DeliveryCountry": "string",
    * "DeliveryDate": "2019-08-24",
    * "DeliveryName": "string",
    * "DeliveryZipCode": "string",
    * "DocumentNumber": "string",
    * "DueDate": "2019-08-24",
    * "EDIInformation": {
      * "EDIGlobalLocationNumber": "string",
      * "EDIGlobalLocationNumberDelivery": "string",
      * "EDIInvoiceExtra1": "string",
      * "EDIInvoiceExtra2": "string",
      * "EDIOurElectronicReference": "string",
      * "EDIStatus": "string",
      * "EDIYourElectronicReference": "string"
},
    * "EUQuarterlyReport": true,
    * "EmailInformation": {
      * "EmailAddressBCC": "string",
      * "EmailAddressCC": "string",
      * "EmailAddressFrom": "string",
      * "EmailAddressTo": "string",
      * "EmailBody": "string",
      * "EmailSubject": "string"
},
    * "ExternalInvoiceReference1": "string",
    * "ExternalInvoiceReference2": "string",
    * "FinalPayDate": "2019-08-24",
    * "Freight": 0.1,
    * "FreightVAT": 0.1,
    * "Gross": 0.1,
    * "HouseWork": true,
    * "InvoiceDate": "2019-08-24",
    * "InvoicePeriodEnd": "2019-08-24",
    * "InvoicePeriodReference": "string",
    * "InvoicePeriodStart": "2019-08-24",
    * "InvoiceRows": [
      * {
        * "AccountNumber": 1000,
        * "ArticleNumber": "string",
        * "ContributionPercent": "string",
        * "ContributionValue": "string",
        * "CostCenter": "string",
        * "DeliveredQuantity": "string",
        * "Description": "string",
        * "Discount": 0.1,
        * "DiscountType": "AMOUNT",
        * "HouseWork": true,
        * "HouseWorkHoursToReport": 999,
        * "HouseWorkType": "CONSTRUCTION",
        * "Price": 0.1,
        * "PriceExcludingVAT": 0.1,
        * "Project": "string",
        * "RowId": 0,
        * "StockPointCode": "string",
        * "Total": 0.1,
        * "TotalExcludingVAT": 0.1,
        * "Unit": "string",
        * "VAT": 0,
        * "VATCode": "string"
}
],
    * "InvoiceType": "INVOICE",
    * "Labels": [
      * {
        * "Id": 0
}
],
    * "Language": "SV",
    * "LastRemindDate": "2019-08-24",
    * "Net": 0.1,
    * "NotCompleted": true,
    * "NoxFinans": true,
    * "OCR": "string",
    * "OfferReference": "string",
    * "OrderReference": "string",
    * "OrganisationNumber": "string",
    * "OurReference": "string",
    * "OutboundDate": "2019-08-24",
    * "PaymentWay": "CASH",
    * "Phone1": "string",
    * "Phone2": "string",
    * "PriceList": "string",
    * "PrintTemplate": "string",
    * "Project": "string",
    * "Remarks": "string",
    * "Reminders": 0,
    * "RoundOff": 0.1,
    * "Sent": true,
    * "TaxReduction": 0,
    * "TaxReductionType": "none",
    * "TermsOfDelivery": "string",
    * "TermsOfPayment": "string",
    * "TimeBasisReference": 0,
    * "Total": 0.1,
    * "TotalToPay": 0.1,
    * "TotalVAT": 0.1,
    * "VATIncluded": true,
    * "VoucherNumber": 0,
    * "VoucherSeries": "string",
    * "VoucherYear": 0,
    * "WarehouseReady": true,
    * "WayOfDelivery": "string",
    * "YourOrderNumber": "string",
    * "YourReference": "string",
    * "ZipCode": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Orders/operation/email_4)Send given order as email 
You can use the properties in the EmailInformation to customize the e-mail message on each order.
##### path Parameters
DocumentNumberrequired| string identifies the order  
---|---  
### Responses
**200**
the existing order
**default**
Error information if the request did not succeed
get/3/orders/{DocumentNumber}/email
Default server
https://api.fortnox.se/3/orders/{DocumentNumber}/email
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Order": {
    * "@url": "string",
    * "@urlTaxReductionList": "string",
    * "Address1": "string",
    * "Address2": "string",
    * "AdministrationFee": 0.1,
    * "AdministrationFeeVAT": 0.1,
    * "BasisTaxReduction": 0.1,
    * "Cancelled": true,
    * "City": "string",
    * "Comments": "string",
    * "ContributionPercent": 0.1,
    * "ContributionValue": 0.1,
    * "CopyRemarks": true,
    * "CostCenter": "string",
    * "Country": "string",
    * "Currency": "str",
    * "CurrencyRate": 0.1,
    * "CurrencyUnit": 0.1,
    * "CustomerName": "string",
    * "CustomerNumber": "string",
    * "DeliveryAddress1": "string",
    * "DeliveryAddress2": "string",
    * "DeliveryCity": "string",
    * "DeliveryCountry": "string",
    * "DeliveryDate": "2019-08-24",
    * "DeliveryName": "string",
    * "DeliveryState": "registration",
    * "DeliveryZipCode": "string",
    * "DocumentNumber": "string",
    * "EmailInformation": {
      * "EmailAddressBCC": "string",
      * "EmailAddressCC": "string",
      * "EmailAddressFrom": "string",
      * "EmailAddressTo": "string",
      * "EmailBody": "string",
      * "EmailSubject": "string"
},
    * "ExternalInvoiceReference1": "string",
    * "ExternalInvoiceReference2": "string",
    * "Freight": 0.1,
    * "FreightVAT": 0.1,
    * "Gross": 0.1,
    * "HouseWork": true,
    * "InvoiceReference": "string",
    * "Labels": [
      * {
        * "Id": 0
}
],
    * "Language": "string",
    * "Net": 0.1,
    * "NotCompleted": true,
    * "OfferReference": "string",
    * "OrderDate": "2019-08-24",
    * "OrderRows": [
      * {
        * "AccountNumber": 0,
        * "ArticleNumber": "string",
        * "ContributionPercent": "string",
        * "ContributionValue": "string",
        * "CostCenter": "string",
        * "DeliveredQuantity": "string",
        * "Description": "string",
        * "Discount": 0.1,
        * "DiscountType": "AMOUNT",
        * "HouseWork": true,
        * "HouseWorkHoursToReport": 0,
        * "HouseWorkType": "CONSTRUCTION",
        * "OrderedQuantity": "string",
        * "Price": 0.1,
        * "Project": "string",
        * "ReservedQuantity": "string",
        * "RowId": 0,
        * "StockPointCode": "string",
        * "StockPointId": "string",
        * "Total": 0.1,
        * "Unit": "string",
        * "VAT": 0.1,
        * "VATCode": "string"
}
],
    * "OrderType": "string",
    * "OrganisationNumber": "string",
    * "OurReference": "string",
    * "OutboundDate": "2019-08-24",
    * "Phone1": "string",
    * "Phone2": "string",
    * "PriceList": "string",
    * "PrintTemplate": "string",
    * "Project": "string",
    * "Remarks": "string",
    * "RoundOff": 0.1,
    * "Sent": true,
    * "StockPointCode": "string",
    * "StockPointId": "string",
    * "TaxReduction": 0.1,
    * "TaxReductionType": "none",
    * "TermsOfDelivery": "string",
    * "TermsOfPayment": "string",
    * "TimeBasisReference": 0,
    * "Total": 0.1,
    * "TotalToPay": 0.1,
    * "TotalVAT": 0.1,
    * "VATIncluded": true,
    * "WarehouseReady": true,
    * "WayOfDelivery": "string",
    * "YourOrderNumber": "string",
    * "YourReference": "string",
    * "ZipCode": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Orders/operation/externalprint_2)Set given order as sent 
Use this endpoint to set order as sent, without generating an order.
##### path Parameters
DocumentNumberrequired| string identifies the order  
---|---  
### Responses
**200**
the updated order
**default**
Error information if the request did not succeed
put/3/orders/{DocumentNumber}/externalprint
Default server
https://api.fortnox.se/3/orders/{DocumentNumber}/externalprint
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Order": {
    * "@url": "string",
    * "@urlTaxReductionList": "string",
    * "Address1": "string",
    * "Address2": "string",
    * "AdministrationFee": 0.1,
    * "AdministrationFeeVAT": 0.1,
    * "BasisTaxReduction": 0.1,
    * "Cancelled": true,
    * "City": "string",
    * "Comments": "string",
    * "ContributionPercent": 0.1,
    * "ContributionValue": 0.1,
    * "CopyRemarks": true,
    * "CostCenter": "string",
    * "Country": "string",
    * "Currency": "str",
    * "CurrencyRate": 0.1,
    * "CurrencyUnit": 0.1,
    * "CustomerName": "string",
    * "CustomerNumber": "string",
    * "DeliveryAddress1": "string",
    * "DeliveryAddress2": "string",
    * "DeliveryCity": "string",
    * "DeliveryCountry": "string",
    * "DeliveryDate": "2019-08-24",
    * "DeliveryName": "string",
    * "DeliveryState": "registration",
    * "DeliveryZipCode": "string",
    * "DocumentNumber": "string",
    * "EmailInformation": {
      * "EmailAddressBCC": "string",
      * "EmailAddressCC": "string",
      * "EmailAddressFrom": "string",
      * "EmailAddressTo": "string",
      * "EmailBody": "string",
      * "EmailSubject": "string"
},
    * "ExternalInvoiceReference1": "string",
    * "ExternalInvoiceReference2": "string",
    * "Freight": 0.1,
    * "FreightVAT": 0.1,
    * "Gross": 0.1,
    * "HouseWork": true,
    * "InvoiceReference": "string",
    * "Labels": [
      * {
        * "Id": 0
}
],
    * "Language": "string",
    * "Net": 0.1,
    * "NotCompleted": true,
    * "OfferReference": "string",
    * "OrderDate": "2019-08-24",
    * "OrderRows": [
      * {
        * "AccountNumber": 0,
        * "ArticleNumber": "string",
        * "ContributionPercent": "string",
        * "ContributionValue": "string",
        * "CostCenter": "string",
        * "DeliveredQuantity": "string",
        * "Description": "string",
        * "Discount": 0.1,
        * "DiscountType": "AMOUNT",
        * "HouseWork": true,
        * "HouseWorkHoursToReport": 0,
        * "HouseWorkType": "CONSTRUCTION",
        * "OrderedQuantity": "string",
        * "Price": 0.1,
        * "Project": "string",
        * "ReservedQuantity": "string",
        * "RowId": 0,
        * "StockPointCode": "string",
        * "StockPointId": "string",
        * "Total": 0.1,
        * "Unit": "string",
        * "VAT": 0.1,
        * "VATCode": "string"
}
],
    * "OrderType": "string",
    * "OrganisationNumber": "string",
    * "OurReference": "string",
    * "OutboundDate": "2019-08-24",
    * "Phone1": "string",
    * "Phone2": "string",
    * "PriceList": "string",
    * "PrintTemplate": "string",
    * "Project": "string",
    * "Remarks": "string",
    * "RoundOff": 0.1,
    * "Sent": true,
    * "StockPointCode": "string",
    * "StockPointId": "string",
    * "TaxReduction": 0.1,
    * "TaxReductionType": "none",
    * "TermsOfDelivery": "string",
    * "TermsOfPayment": "string",
    * "TimeBasisReference": 0,
    * "Total": 0.1,
    * "TotalToPay": 0.1,
    * "TotalVAT": 0.1,
    * "VATIncluded": true,
    * "WarehouseReady": true,
    * "WayOfDelivery": "string",
    * "YourOrderNumber": "string",
    * "YourReference": "string",
    * "ZipCode": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Orders/operation/preview_4)Preview given offer 
The difference between this and the print-endpoint is that property Sent is not set to TRUE.
##### path Parameters
DocumentNumberrequired| string identifies the offer  
---|---  
### Responses
**200**
the given order as PDF
**default**
Error information if the request did not succeed
get/3/orders/{DocumentNumber}/preview
Default server
https://api.fortnox.se/3/orders/{DocumentNumber}/preview
## [](https://api.fortnox.se/apidocs#tag/fortnox_Orders/operation/print_4)Print given order 
##### path Parameters
DocumentNumberrequired| string identifies the order  
---|---  
### Responses
**200**
the given order as PDF
**default**
Error information if the request did not succeed
get/3/orders/{DocumentNumber}/print
Default server
https://api.fortnox.se/3/orders/{DocumentNumber}/print
# [](https://api.fortnox.se/apidocs#tag/fortnox_PredefinedAccounts)Predefined Accounts
Predefined Accounts resources
## [](https://api.fortnox.se/apidocs#tag/fortnox_PredefinedAccounts/operation/list_28)Retrieve a list of all predefined accounts 
### Responses
**200**
list of predefined accounts
**default**
Error information if the request did not succeed
get/3/predefinedaccounts
Default server
https://api.fortnox.se/3/predefinedaccounts
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "PreDefinedAccounts": [
    * {
      * "@url": "string",
      * "Account": 1000,
      * "Name": "string"
}
]

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_PredefinedAccounts/operation/get_36)Retrieve information for a specific account type 
##### path Parameters
namerequired| string identifies the predefined account  
---|---  
### Responses
**200**
the existing predefined account
**default**
Error information if the request did not succeed
get/3/predefinedaccounts/{name}
Default server
https://api.fortnox.se/3/predefinedaccounts/{name}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "PreDefinedAccount": {
    * "@url": "string",
    * "Account": 1000,
    * "Name": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_PredefinedAccounts/operation/update_26)Update a Predefined Account 
An endpoint for updating a Predefined Account. Predefined Accounts are identified by their _name_ -field, and as such must be unique. Some Predefined Accounts distinguish between Goods and Services. In this case, the former retains the original name whereas the latter ends with a 2. Such as _SALES_ and _SALES2_. Accounts are chosen from the Account Registry, and if you have EasyVat enabled then the new EasyVat Predefined Accounts (_SALES_25_SE_ , etc.) have certain restrictions on the accounts that can be selected. Refer to the table below.
Account restrictions when EasyVat has been enabled. Name | VAT Code | Restrictions  
---|---|---  
SALES_25_SE | MP1 | Must have a compatible VAT Code.  
SALES_12_SE | MP2 | Must have a compatible VAT Code.  
SALES_6_SE | MP3 | Must have a compatible VAT Code.  
SALES_0_SE | MF | Must have a compatible VAT Code.  
This endpoint can produce errors, some of which may only be relevant for EasyVat. Refer to the table below. 
Errors that can be raised by this endpoint. Error Code | HTTP Code | Description | Solution  
---|---|---|---  
2001265 | 400 | The provided account is invalid. It either has not been provided, does not exist, or is inactive. | Verify that an account has been provided and that it exists and is active.  
2002462 | 400 | The account is not in a valid format. | Verify that the format of the account is correct. It has to consist of 4 digits.  
2000729 | 400 | A Predefined Account has not been provided. | Verify that a valid Predefined Account has been provided as a PATH-parameter.  
2004052 | 400 | The provided account has an incompatible VAT Code. Only applies if EasyVat has been enabled. | Verify that the provided account has a VAT Code that is compatible with the selected Predefined Account. Refer to the table above for more information about compatibility.  
If you have activated EasyVat, you can read more about how to use the new Predefined Accounts with your documents in their respective api documentation.
##### path Parameters
namerequired| string identifies the predefined account  
---|---  
##### Request Body schema: */*
predefined account to update
PreDefinedAccountrequired| object (fortnox_PredefinedAccount)   
---|---  
### Responses
**200**
the updated predefined account
**default**
Error information if the request did not succeed
put/3/predefinedaccounts/{name}
Default server
https://api.fortnox.se/3/predefinedaccounts/{name}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "PreDefinedAccount": {
    * "@url": "string",
    * "Account": 1000,
    * "Name": "string"
}

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_PredefinedVoucherSeries)Predefined Voucher Series
Predefined Voucher Series resources
## [](https://api.fortnox.se/apidocs#tag/fortnox_PredefinedVoucherSeries/operation/list_29)Retrieve a list of predefined voucher series 
### Responses
**200**
a list of predefined voucher series
**default**
Error information if the request did not succeed
get/3/predefinedvoucherseries
Default server
https://api.fortnox.se/3/predefinedvoucherseries
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "PreDefinedVoucherSeriesCollection": [
    * {
      * "@url": "string",
      * "Name": "string",
      * "VoucherSeries": "s"
}
]

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_PredefinedVoucherSeries/operation/get_37)Retrieve a specific predefined voucher series 
##### path Parameters
Namerequired| string identifies the predefined voucher series  
---|---  
### Responses
**200**
a list of predefined voucher series
**default**
Error information if the request did not succeed
get/3/predefinedvoucherseries/{Name}
Default server
https://api.fortnox.se/3/predefinedvoucherseries/{Name}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "PreDefinedVoucherSeries": {
    * "@url": "string",
    * "Name": "string",
    * "VoucherSeries": "s"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_PredefinedVoucherSeries/operation/update_27)Update a predefined voucher series 
##### path Parameters
Namerequired| string identifies the predefined voucher series  
---|---  
##### Request Body schema: */*
predefined voucher series to update
PreDefinedVoucherSeries| object (fortnox_PredefinedVoucherSeries)   
---|---  
### Responses
**200**
the updated predefined voucher series
**default**
Error information if the request did not succeed
put/3/predefinedvoucherseries/{Name}
Default server
https://api.fortnox.se/3/predefinedvoucherseries/{Name}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "PreDefinedVoucherSeries": {
    * "@url": "string",
    * "Name": "string",
    * "VoucherSeries": "s"
}

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_PriceLists)Price Lists
Resource for CRUD operations on Pricelists
## [](https://api.fortnox.se/apidocs#tag/fortnox_PriceLists/operation/list_30)Retrieve a list of price lists 
The price lists register can return a list of records or a single record. By specifying a Code in the URL, a single record will be returned. Not specifying a Code will return a list of records.
### Responses
**200**
all price lists
**default**
Error information if the request did not succeed
get/3/pricelists
Default server
https://api.fortnox.se/3/pricelists
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "PriceLists": [
    * {
      * "@url": "string",
      * "Code": "string",
      * "Comments": "string",
      * "Description": "string",
      * "PreSelected": true
}
]

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_PriceLists/operation/create_31)Create a price list 
##### Request Body schema: */*
to create
PriceListrequired| object (fortnox_PriceList)   
---|---  
### Responses
**201**
the created price list
**default**
Error information if the request did not succeed
post/3/pricelists
Default server
https://api.fortnox.se/3/pricelists
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "PriceList": {
    * "@url": "string",
    * "Code": "string",
    * "Comments": "string",
    * "Description": "string",
    * "PreSelected": true
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_PriceLists/operation/get_38)Retrieve a single price list 
##### path Parameters
Coderequired| string identifies the price list  
---|---  
### Responses
**200**
the existing price list
**default**
Error information if the request did not succeed
get/3/pricelists/{Code}
Default server
https://api.fortnox.se/3/pricelists/{Code}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "PriceList": {
    * "@url": "string",
    * "Code": "string",
    * "Comments": "string",
    * "Description": "string",
    * "PreSelected": true
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_PriceLists/operation/update_28)Update a price list 
##### path Parameters
Coderequired| string identifies the price list  
---|---  
##### Request Body schema: */*
price list to update
PriceListrequired| object (fortnox_PriceList)   
---|---  
### Responses
**200**
the updated price list
**default**
Error information if the request did not succeed
put/3/pricelists/{Code}
Default server
https://api.fortnox.se/3/pricelists/{Code}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "PriceList": {
    * "@url": "string",
    * "Code": "string",
    * "Comments": "string",
    * "Description": "string",
    * "PreSelected": true
}

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_Prices)Prices
Resource for CRUD operations on prices
## [](https://api.fortnox.se/apidocs#tag/fortnox_Prices/operation/list_31)Retrieve a list of prices 
### Responses
**200**
a list of prices.
**default**
Error information if the request did not succeed
get/3/prices
Default server
https://api.fortnox.se/3/prices
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Price": {
    * "@url": "string",
    * "ArticleNumber": "string",
    * "Date": "2019-08-24T14:15:22Z",
    * "FromQuantity": 0.1,
    * "Percent": 0.1,
    * "Price": 0.1,
    * "PriceList": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Prices/operation/create_32)Create a price 
##### Request Body schema: */*
price to create
Price| object (fortnox_Price)   
---|---  
### Responses
**201**
the created price
**default**
Error information if the request did not succeed
post/3/prices
Default server
https://api.fortnox.se/3/prices
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Price": {
    * "@url": "string",
    * "ArticleNumber": "string",
    * "Date": "2019-08-24T14:15:22Z",
    * "FromQuantity": 0.1,
    * "Percent": 0.1,
    * "Price": 0.1,
    * "PriceList": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Prices/operation/list_32)Retrieve a list of articles with all their prices in the specified price list 
The list contains a slimmer version of the prices. To get a full entity, use the GET with a price list, article number and from quantity.
##### path Parameters
PriceListrequired| string identifies the price list of the prices  
---|---  
ArticleNumberrequired| string identifies the article number of the prices  
### Responses
**200**
list of prices
**default**
Error information if the request did not succeed
get/3/prices/sublist/{PriceList}/{ArticleNumber}
Default server
https://api.fortnox.se/3/prices/sublist/{PriceList}/{ArticleNumber}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Prices": [
    * {
      * "@url": "string",
      * "ArticleNumber": "string",
      * "FromQuantity": 0.1,
      * "Price": 0.1,
      * "PriceList": "string"
}
]

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Prices/operation/getFirstPrice)Retrieve the first price for the specified article 
##### path Parameters
PriceListrequired| string identifies the price list  
---|---  
ArticleNumberrequired| string identifies the article  
### Responses
**200**
the first price for the specified article
**default**
Error information if the request did not succeed
get/3/prices/{PriceList}/{ArticleNumber}
Default server
https://api.fortnox.se/3/prices/{PriceList}/{ArticleNumber}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Price": {
    * "@url": "string",
    * "ArticleNumber": "string",
    * "Date": "2019-08-24T14:15:22Z",
    * "FromQuantity": 0.1,
    * "Percent": 0.1,
    * "Price": 0.1,
    * "PriceList": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Prices/operation/update_30)Update the first price in the specified article 
##### path Parameters
PriceListrequired| string identifies the price list  
---|---  
ArticleNumberrequired| string identifies the article number  
##### Request Body schema: */*
price to update
Price| object (fortnox_Price)   
---|---  
### Responses
**200**
the updated price
**default**
Error information if the request did not succeed
put/3/prices/{PriceList}/{ArticleNumber}
Default server
https://api.fortnox.se/3/prices/{PriceList}/{ArticleNumber}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Price": {
    * "@url": "string",
    * "ArticleNumber": "string",
    * "Date": "2019-08-24T14:15:22Z",
    * "FromQuantity": 0.1,
    * "Percent": 0.1,
    * "Price": 0.1,
    * "PriceList": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Prices/operation/remove_16)Delete a single price 
##### path Parameters
PriceListrequired| string identifies the price list  
---|---  
ArticleNumberrequired| string identifies the article number  
FromQuantityrequired| number <double> identifies the from quantity  
### Responses
**204**
Successfully removed the specified resource.
**default**
Error information if the request did not succeed
delete/3/prices/{PriceList}/{ArticleNumber}/{FromQuantity}
Default server
https://api.fortnox.se/3/prices/{PriceList}/{ArticleNumber}/{FromQuantity}
###  Response samples 
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ErrorInformation": {
    * "Code": 0,
    * "Error": 0,
    * "Message": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Prices/operation/get_39)Retrieve a price for a specified article 
##### path Parameters
PriceListrequired| string identifies the price list  
---|---  
ArticleNumberrequired| string identifies the article  
FromQuantityrequired| number <double> identifies from quantity  
### Responses
**200**
the price for a specified article
**default**
Error information if the request did not succeed
get/3/prices/{PriceList}/{ArticleNumber}/{FromQuantity}
Default server
https://api.fortnox.se/3/prices/{PriceList}/{ArticleNumber}/{FromQuantity}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Price": {
    * "@url": "string",
    * "ArticleNumber": "string",
    * "Date": "2019-08-24T14:15:22Z",
    * "FromQuantity": 0.1,
    * "Percent": 0.1,
    * "Price": 0.1,
    * "PriceList": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Prices/operation/update_29)Update a price 
##### path Parameters
PriceListrequired| string identifies the price list  
---|---  
ArticleNumberrequired| string identifies the article number  
FromQuantityrequired| number <double> identifies the from quantity  
##### Request Body schema: */*
price to update
Price| object (fortnox_Price)   
---|---  
### Responses
**200**
the updated price
**default**
Error information if the request did not succeed
put/3/prices/{PriceList}/{ArticleNumber}/{FromQuantity}
Default server
https://api.fortnox.se/3/prices/{PriceList}/{ArticleNumber}/{FromQuantity}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Price": {
    * "@url": "string",
    * "ArticleNumber": "string",
    * "Date": "2019-08-24T14:15:22Z",
    * "FromQuantity": 0.1,
    * "Percent": 0.1,
    * "Price": 0.1,
    * "PriceList": "string"
}

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_PrintTemplates)Print Templates
Resource for the CRUD operations on print templates
## [](https://api.fortnox.se/apidocs#tag/fortnox_PrintTemplates/operation/list_33)Retrieve a list of print templates 
### Responses
**200**
a list of print templates.
**default**
Error information if the request did not succeed
get/3/printtemplates
Default server
https://api.fortnox.se/3/printtemplates
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "PrintTemplates": [
    * {
      * "Name": "string",
      * "Template": "string"
}
]

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_Projects)Projects
Resource for the CRUD operations on projects
## [](https://api.fortnox.se/apidocs#tag/fortnox_Projects/operation/list_34)Retrieve a list of projects 
The project register can return a list of records or a single record. By specifying a ProjectNumber in the URL, a single record will be returned. If no ProjectNumber is provided, a list of records will be returned.
### Responses
**200**
list of projects
**default**
Error information if the request did not succeed
get/3/projects
Default server
https://api.fortnox.se/3/projects
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Projects": [
    * {
      * "@url": "string",
      * "Description": "string",
      * "EndDate": "2019-08-24",
      * "ProjectLeader": "string",
      * "ProjectNumber": "string",
      * "StartDate": "2019-08-24",
      * "Status": "NOTSTARTED"
}
]

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Projects/operation/create_33)Create a project 
##### Request Body schema: */*
to create
Project| object (fortnox_Project)   
---|---  
### Responses
**201**
the created project
**default**
Error information if the request did not succeed
post/3/projects
Default server
https://api.fortnox.se/3/projects
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Project": {
    * "@url": "string",
    * "Comments": "string",
    * "ContactPerson": "string",
    * "Description": "string",
    * "EndDate": "2019-08-24",
    * "ProjectLeader": "string",
    * "ProjectNumber": "string",
    * "StartDate": "2019-08-24",
    * "Status": "NOTSTARTED"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Projects/operation/remove_17)Remove a project 
##### path Parameters
ProjectNumberrequired| integer <int32> identifies the project  
---|---  
### Responses
**204**
Successfully removed the specified resource.
**default**
Error information if the request did not succeed
delete/3/projects/{ProjectNumber}
Default server
https://api.fortnox.se/3/projects/{ProjectNumber}
###  Response samples 
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ErrorInformation": {
    * "Code": 0,
    * "Error": 0,
    * "Message": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Projects/operation/get_40)Retrieve a single project 
##### path Parameters
ProjectNumberrequired| integer <int32> identifies the project  
---|---  
### Responses
**200**
the existing project
**default**
Error information if the request did not succeed
get/3/projects/{ProjectNumber}
Default server
https://api.fortnox.se/3/projects/{ProjectNumber}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Project": {
    * "@url": "string",
    * "Comments": "string",
    * "ContactPerson": "string",
    * "Description": "string",
    * "EndDate": "2019-08-24",
    * "ProjectLeader": "string",
    * "ProjectNumber": "string",
    * "StartDate": "2019-08-24",
    * "Status": "NOTSTARTED"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Projects/operation/update_31)Update a project 
##### path Parameters
ProjectNumberrequired| integer <int32> identifies the project  
---|---  
##### Request Body schema: */*
to update
Project| object (fortnox_Project)   
---|---  
### Responses
**200**
the updated project
**default**
Error information if the request did not succeed
put/3/projects/{ProjectNumber}
Default server
https://api.fortnox.se/3/projects/{ProjectNumber}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Project": {
    * "@url": "string",
    * "Comments": "string",
    * "ContactPerson": "string",
    * "Description": "string",
    * "EndDate": "2019-08-24",
    * "ProjectLeader": "string",
    * "ProjectNumber": "string",
    * "StartDate": "2019-08-24",
    * "Status": "NOTSTARTED"
}

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_SalaryTransactions)Salary Transactions
Salary Transaction resources Usable SalaryCodes: You can get a list of usable salary codes in the GUI from Register, Lönearter och koder − Lönearter by choosing one of two tables and pressing print. Depending on which salary code table (löneartstabell) that is set in the settings (Inställningar, Lön, Avtal för arbetare/tjänsteman − Allmänt) you can choose the salary code to use from either salary code table. Make sure to use the correct table that is used for the employee PersonelType you want to sent the salary transaction for. Some salary codes do not exist in every table.
## [](https://api.fortnox.se/apidocs#tag/fortnox_SalaryTransactions/operation/list_35)List all salary transactions for all employees 
Supports query-string parameters **employeeid** and **date** for filtering the result.
##### query Parameters
employeeId| string filter on employeeId  
---|---  
date| string <date> filter on date  
### Responses
**200**
list of salary transactions
**default**
Error information if the request did not succeed
get/3/salarytransactions
Default server
https://api.fortnox.se/3/salarytransactions
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "SalaryTransactions": [
    * {
      * "@url": "string",
      * "Amount": "string",
      * "CostCenter": "string",
      * "Date": "2019-08-24",
      * "EmployeeId": "string",
      * "Expense": "string",
      * "Number": "string",
      * "Project": "string",
      * "SalaryCode": "string",
      * "SalaryRow": 0,
      * "TextRow": "string",
      * "Total": "string",
      * "VAT": "string"
}
]

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_SalaryTransactions/operation/create_34)Create a new salary transaction for an employee 
##### Request Body schema: */*
to create
SalaryTransactionrequired| object (fortnox_SalaryTransaction)   
---|---  
### Responses
**201**
the created salary transaction
**default**
Error information if the request did not succeed
post/3/salarytransactions
Default server
https://api.fortnox.se/3/salarytransactions
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "SalaryTransaction": {
    * "Amount": "string",
    * "CostCenter": "string",
    * "Date": "2019-08-24",
    * "EmployeeId": "string",
    * "Expense": "string",
    * "Number": "string",
    * "Project": "string",
    * "SalaryCode": "string",
    * "SalaryRow": 0,
    * "TextRow": "string",
    * "Total": "string",
    * "VAT": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_SalaryTransactions/operation/delete_3)Delete a single salary transaction 
##### path Parameters
SalaryRowrequired| integer <int32> identifies the salary transaction  
---|---  
### Responses
**200**
the existing salary transaction
**default**
Error information if the request did not succeed
delete/3/salarytransactions/{SalaryRow}
Default server
https://api.fortnox.se/3/salarytransactions/{SalaryRow}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "SalaryTransaction": {
    * "Amount": "string",
    * "CostCenter": "string",
    * "Date": "2019-08-24",
    * "EmployeeId": "string",
    * "Expense": "string",
    * "Number": "string",
    * "Project": "string",
    * "SalaryCode": "string",
    * "SalaryRow": 0,
    * "TextRow": "string",
    * "Total": "string",
    * "VAT": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_SalaryTransactions/operation/get_41)Retrieve a single salary transaction 
##### path Parameters
SalaryRowrequired| integer <int32> identifies the salary transaction  
---|---  
### Responses
**200**
the existing salary transaction
**default**
Error information if the request did not succeed
get/3/salarytransactions/{SalaryRow}
Default server
https://api.fortnox.se/3/salarytransactions/{SalaryRow}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "SalaryTransaction": {
    * "Amount": "string",
    * "CostCenter": "string",
    * "Date": "2019-08-24",
    * "EmployeeId": "string",
    * "Expense": "string",
    * "Number": "string",
    * "Project": "string",
    * "SalaryCode": "string",
    * "SalaryRow": 0,
    * "TextRow": "string",
    * "Total": "string",
    * "VAT": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_SalaryTransactions/operation/update_32)Update a salary transaction 
##### path Parameters
SalaryRowrequired| integer <int32> identifies the salary transaction  
---|---  
##### Request Body schema: */*
to update
SalaryTransactionrequired| object (fortnox_SalaryTransaction)   
---|---  
### Responses
**200**
the updated salary transaction
**default**
Error information if the request did not succeed
put/3/salarytransactions/{SalaryRow}
Default server
https://api.fortnox.se/3/salarytransactions/{SalaryRow}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "SalaryTransaction": {
    * "Amount": "string",
    * "CostCenter": "string",
    * "Date": "2019-08-24",
    * "EmployeeId": "string",
    * "Expense": "string",
    * "Number": "string",
    * "Project": "string",
    * "SalaryCode": "string",
    * "SalaryRow": 0,
    * "TextRow": "string",
    * "Total": "string",
    * "VAT": "string"
}

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_ScheduleTimes)Schedule Times
Schedule times resources
## [](https://api.fortnox.se/apidocs#tag/fortnox_ScheduleTimes/operation/get_42)Retrieve a specific schedule time 
##### path Parameters
EmployeeIdrequired| string identifies the employee  
---|---  
Daterequired| string <date> identifies the date  
### Responses
**200**
the existing schedule time
**default**
Error information if the request did not succeed
get/3/scheduletimes/{EmployeeId}/{Date}
Default server
https://api.fortnox.se/3/scheduletimes/{EmployeeId}/{Date}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ScheduleTime": {
    * "Date": "2019-08-24",
    * "EmployeeId": "string",
    * "Hours": "string",
    * "IWH1": "string",
    * "IWH2": "string",
    * "IWH3": "string",
    * "IWH4": "string",
    * "IWH5": "string",
    * "ScheduleId": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_ScheduleTimes/operation/update_33)Update a schedule time 
##### path Parameters
EmployeeIdrequired| string identifies the employee  
---|---  
Daterequired| string <date> identifies the date  
##### Request Body schema: */*
to update
ScheduleTime| object (fortnox_ScheduleTime)   
---|---  
### Responses
**200**
the updated schedule time
**default**
Error information if the request did not succeed
put/3/scheduletimes/{EmployeeId}/{Date}
Default server
https://api.fortnox.se/3/scheduletimes/{EmployeeId}/{Date}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ScheduleTime": {
    * "Date": "2019-08-24",
    * "EmployeeId": "string",
    * "Hours": "string",
    * "IWH1": "string",
    * "IWH2": "string",
    * "IWH3": "string",
    * "IWH4": "string",
    * "IWH5": "string",
    * "ScheduleId": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_ScheduleTimes/operation/reset)Reset schedule time 
##### path Parameters
EmployeeIdrequired| string identifies the employee  
---|---  
Daterequired| string <date> identifies the date  
### Responses
**200**
the reset schedule time
**default**
Error information if the request did not succeed
put/3/scheduletimes/{EmployeeId}/{Date}/resetday
Default server
https://api.fortnox.se/3/scheduletimes/{EmployeeId}/{Date}/resetday
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ScheduleTime": {
    * "Date": "2019-08-24",
    * "EmployeeId": "string",
    * "Hours": "string",
    * "IWH1": "string",
    * "IWH2": "string",
    * "IWH3": "string",
    * "IWH4": "string",
    * "IWH5": "string",
    * "ScheduleId": "string"
}

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_Sie)Sie
Filters 
Possible filters on SIE endpoint Type | Description  
---|---  
FinancialYear | Retreives the SIE-files for the specific financial year  
Example: | <https://api.fortnox.se/3/sie/4?financialyear=1>  
## [](https://api.fortnox.se/apidocs#tag/fortnox_Sie/operation/get_43)Retrieve a SIE file 
Retrieves a SIE file as streamed content
##### path Parameters
Typerequired| string type  
---|---  
##### query Parameters
financialYear| integer <int32> financialYear  
---|---  
### Responses
**204**
Operation successful but returned no content.
**default**
Error information if the request did not succeed
get/3/sie/{Type}
Default server
https://api.fortnox.se/3/sie/{Type}
###  Response samples 
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ErrorInformation": {
    * "Code": 0,
    * "Error": 0,
    * "Message": "string"
}

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_SupplierInvoiceAccruals)Supplier Invoice Accruals
Resource for the CRUD operations on supplier invoice accruals
## [](https://api.fortnox.se/apidocs#tag/fortnox_SupplierInvoiceAccruals/operation/list_36)Retrieve a list of supplier invoice accruals 
The supplier invoice accruals register can return a list of records or a single record. By specifying a SupplierInvoiceNumber in the URL, a single record will be returned. Not specifying a SupplierInvoiceNumber will return a list of records.
### Responses
**200**
list of supplier invoice accruals
**default**
Error information if the request did not succeed
get/3/supplierinvoiceaccruals
Default server
https://api.fortnox.se/3/supplierinvoiceaccruals
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "SupplierInvoiceAccruals": [
    * {
      * "@url": "string",
      * "Description": "string",
      * "Period": "MONTHLY",
      * "SupplierInvoiceNumber": 0
}
]

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_SupplierInvoiceAccruals/operation/create_35)Create a supplier invoice accrual 
##### Request Body schema: */*
to create
SupplierInvoiceAccrualrequired| object (fortnox_SupplierInvoiceAccrual)   
---|---  
### Responses
**201**
the created supplier invoice accrual
**default**
Error information if the request did not succeed
post/3/supplierinvoiceaccruals
Default server
https://api.fortnox.se/3/supplierinvoiceaccruals
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "SupplierInvoiceAccrual": {
    * "@url": "string",
    * "AccrualAccount": 1000,
    * "CostAccount": 1000,
    * "Description": "string",
    * "EndDate": "2019-08-24",
    * "Period": "MONTHLY",
    * "StartDate": "2019-08-24",
    * "SupplierInvoiceAccrualRows": [
      * {
        * "Account": 0,
        * "CostCenter": "string",
        * "Credit": 0.1,
        * "Debit": 0.1,
        * "Project": "string",
        * "TransactionInformation": "string"
},
      * {
        * "Account": 0,
        * "CostCenter": "string",
        * "Credit": 0.1,
        * "Debit": 0.1,
        * "Project": "string",
        * "TransactionInformation": "string"
}
],
    * "SupplierInvoiceNumber": 0,
    * "Times": 0,
    * "Total": 0.1,
    * "VATIncluded": true
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_SupplierInvoiceAccruals/operation/remove_18)Remove a supplier invoice accrual 
##### path Parameters
SupplierInvoiceNumberrequired| integer <int32> identifies the supplier invoice accrual  
---|---  
### Responses
**204**
Successfully removed the specified resource.
**default**
Error information if the request did not succeed
delete/3/supplierinvoiceaccruals/{SupplierInvoiceNumber}
Default server
https://api.fortnox.se/3/supplierinvoiceaccruals/{SupplierInvoiceNumber}
###  Response samples 
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ErrorInformation": {
    * "Code": 0,
    * "Error": 0,
    * "Message": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_SupplierInvoiceAccruals/operation/get_44)Retrieve a single supplier invoice accrual 
##### path Parameters
SupplierInvoiceNumberrequired| integer <int32> identifies the supplier invoice accrual  
---|---  
### Responses
**200**
the existing supplier invoice accrual
**default**
Error information if the request did not succeed
get/3/supplierinvoiceaccruals/{SupplierInvoiceNumber}
Default server
https://api.fortnox.se/3/supplierinvoiceaccruals/{SupplierInvoiceNumber}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "SupplierInvoiceAccrual": {
    * "@url": "string",
    * "AccrualAccount": 1000,
    * "CostAccount": 1000,
    * "Description": "string",
    * "EndDate": "2019-08-24",
    * "Period": "MONTHLY",
    * "StartDate": "2019-08-24",
    * "SupplierInvoiceAccrualRows": [
      * {
        * "Account": 0,
        * "CostCenter": "string",
        * "Credit": 0.1,
        * "Debit": 0.1,
        * "Project": "string",
        * "TransactionInformation": "string"
},
      * {
        * "Account": 0,
        * "CostCenter": "string",
        * "Credit": 0.1,
        * "Debit": 0.1,
        * "Project": "string",
        * "TransactionInformation": "string"
}
],
    * "SupplierInvoiceNumber": 0,
    * "Times": 0,
    * "Total": 0.1,
    * "VATIncluded": true
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_SupplierInvoiceAccruals/operation/update_34)Update a supplier invoice accrual 
##### path Parameters
SupplierInvoiceNumberrequired| integer <int32> identifies the supplier invoice accrual  
---|---  
##### Request Body schema: */*
to update
SupplierInvoiceAccrualrequired| object (fortnox_SupplierInvoiceAccrual)   
---|---  
### Responses
**200**
the updated supplier invoice accrual
**default**
Error information if the request did not succeed
put/3/supplierinvoiceaccruals/{SupplierInvoiceNumber}
Default server
https://api.fortnox.se/3/supplierinvoiceaccruals/{SupplierInvoiceNumber}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "SupplierInvoiceAccrual": {
    * "@url": "string",
    * "AccrualAccount": 1000,
    * "CostAccount": 1000,
    * "Description": "string",
    * "EndDate": "2019-08-24",
    * "Period": "MONTHLY",
    * "StartDate": "2019-08-24",
    * "SupplierInvoiceAccrualRows": [
      * {
        * "Account": 0,
        * "CostCenter": "string",
        * "Credit": 0.1,
        * "Debit": 0.1,
        * "Project": "string",
        * "TransactionInformation": "string"
},
      * {
        * "Account": 0,
        * "CostCenter": "string",
        * "Credit": 0.1,
        * "Debit": 0.1,
        * "Project": "string",
        * "TransactionInformation": "string"
}
],
    * "SupplierInvoiceNumber": 0,
    * "Times": 0,
    * "Total": 0.1,
    * "VATIncluded": true
}

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_SupplierInvoiceExternalUrlConnections)Supplier Invoice External Url Connections
Supplier Invoice External URL Connections resource Note: Requires a supplier invoice file attachment to be visible in Fortnox GUI.
## [](https://api.fortnox.se/apidocs#tag/fortnox_SupplierInvoiceExternalUrlConnections/operation/create_36)Create a supplier invoice external URL connection 
##### Request Body schema: */*
request
ExternalURLConnection| string  
---|---  
SupplierInvoiceNumber| integer <int32>  
### Responses
**201**
supplier invoice external url connection
**default**
Error information if the request did not succeed
post/3/supplierinvoiceexternalurlconnections
Default server
https://api.fortnox.se/3/supplierinvoiceexternalurlconnections
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "SupplierInvoiceExternalURLConnection": {
    * "ExternalURLConnection": "string",
    * "Id": 0,
    * "SupplierInvoiceNumber": 0,
    * "Url": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_SupplierInvoiceExternalUrlConnections/operation/delete_4)Remove a supplier invoice external URL connection 
##### path Parameters
Idrequired| integer <int32> id  
---|---  
### Responses
**204**
Successfully removed the specified resource.
**default**
Error information if the request did not succeed
delete/3/supplierinvoiceexternalurlconnections/{Id}
Default server
https://api.fortnox.se/3/supplierinvoiceexternalurlconnections/{Id}
###  Response samples 
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ErrorInformation": {
    * "Code": 0,
    * "Error": 0,
    * "Message": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_SupplierInvoiceExternalUrlConnections/operation/get_45)Retrieve a single supplier invoice external URL connection 
##### path Parameters
Idrequired| integer <int32> id  
---|---  
### Responses
**200**
supplier invoice external url connection
**default**
Error information if the request did not succeed
get/3/supplierinvoiceexternalurlconnections/{Id}
Default server
https://api.fortnox.se/3/supplierinvoiceexternalurlconnections/{Id}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "SupplierInvoiceExternalURLConnection": {
    * "ExternalURLConnection": "string",
    * "Id": 0,
    * "SupplierInvoiceNumber": 0,
    * "Url": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_SupplierInvoiceExternalUrlConnections/operation/update_35)Update a supplier invoice external URL connection 
##### path Parameters
Idrequired| integer <int32> id  
---|---  
##### Request Body schema: */*
request
ExternalURLConnection| string  
---|---  
SupplierInvoiceNumber| integer <int32>  
### Responses
**200**
supplier invoice external url connection
**default**
Error information if the request did not succeed
put/3/supplierinvoiceexternalurlconnections/{Id}
Default server
https://api.fortnox.se/3/supplierinvoiceexternalurlconnections/{Id}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "SupplierInvoiceExternalURLConnection": {
    * "ExternalURLConnection": "string",
    * "Id": 0,
    * "SupplierInvoiceNumber": 0,
    * "Url": "string"
}

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_SupplierInvoiceFileConnections)Supplier Invoice File Connections
Resource for CRUD operations on Supplier invoice file connections
## [](https://api.fortnox.se/apidocs#tag/fortnox_SupplierInvoiceFileConnections/operation/list_37)Retrieve a list of supplier invoice file connections 
The supplier invoice file connections register can return a list of records or a single record. By specifying a FileId in the URL, a single record will be returned. Not specifying a FileId will return a list of records.
### Responses
**200**
list of file connections
**default**
Error information if the request did not succeed
get/3/supplierinvoicefileconnections
Default server
https://api.fortnox.se/3/supplierinvoicefileconnections
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "SupplierInvoiceFileConnections": [
    * {
      * "@url": "string",
      * "FileId": "string",
      * "Name": "string",
      * "SupplierInvoiceNumber": "string",
      * "SupplierName": "string"
}
]

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_SupplierInvoiceFileConnections/operation/create_37)Create an supplier invoice file connection 
##### Request Body schema: */*
supplier invoice file connection to create
SupplierInvoiceFileConnection| object (fortnox_SupplierInvoiceFileConnection)   
---|---  
### Responses
**201**
the created supplier invoice file connection
**default**
Error information if the request did not succeed
post/3/supplierinvoicefileconnections
Default server
https://api.fortnox.se/3/supplierinvoicefileconnections
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "SupplierInvoiceFileConnection": {
    * "@url": "string",
    * "FileId": "string",
    * "Name": "string",
    * "SupplierInvoiceNumber": "string",
    * "SupplierName": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_SupplierInvoiceFileConnections/operation/remove_19)Remove an supplier invoice file connection 
##### path Parameters
FileIdrequired| string identifies the supplier invoice file connection  
---|---  
### Responses
**204**
Successfully removed the specified resource.
**default**
Error information if the request did not succeed
delete/3/supplierinvoicefileconnections/{FileId}
Default server
https://api.fortnox.se/3/supplierinvoicefileconnections/{FileId}
###  Response samples 
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ErrorInformation": {
    * "Code": 0,
    * "Error": 0,
    * "Message": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_SupplierInvoiceFileConnections/operation/get_46)Retrieve a single supplier invoice file connection 
##### path Parameters
FileIdrequired| string identifies the file connection  
---|---  
### Responses
**200**
the existing file connection
**default**
Error information if the request did not succeed
get/3/supplierinvoicefileconnections/{FileId}
Default server
https://api.fortnox.se/3/supplierinvoicefileconnections/{FileId}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "SupplierInvoiceFileConnection": {
    * "@url": "string",
    * "FileId": "string",
    * "Name": "string",
    * "SupplierInvoiceNumber": "string",
    * "SupplierName": "string"
}

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_SupplierInvoicePayments)Supplier Invoice Payments
Supplier invoice payments resources 
Possible search params on Supplier Invoice Payments endpoint **Search** | **Description**  
---|---  
invoicenumber | Retrives supplier invoice payments modified by invoicenumber  
lastmodified | Retrives supplier invoice payments modified after provided date and time  
## [](https://api.fortnox.se/apidocs#tag/fortnox_SupplierInvoicePayments/operation/list_38)Retrieve a list of supplier invoice payments 
### Responses
**200**
list of supplier invoice payments
**default**
Error information if the request did not succeed
get/3/supplierinvoicepayments
Default server
https://api.fortnox.se/3/supplierinvoicepayments
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "SupplierInvoicePayments": [
    * {
      * "@url": "string",
      * "Amount": 0.1,
      * "Booked": true,
      * "Currency": "str",
      * "CurrencyRate": 0.1,
      * "CurrencyUnit": 0.1,
      * "InvoiceNumber": "string",
      * "Number": 0,
      * "PaymentDate": "2019-08-24",
      * "Source": "manual",
      * "WriteOffExist": true
}
]

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_SupplierInvoicePayments/operation/create_38)Create a supplier invoice payment 
##### Request Body schema: */*
to create
SupplierInvoicePayment| object (fortnox_SupplierInvoicePayment)   
---|---  
### Responses
**201**
the created supplier invoice payment
**default**
Error information if the request did not succeed
post/3/supplierinvoicepayments
Default server
https://api.fortnox.se/3/supplierinvoicepayments
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "SupplierInvoicePayment": {
    * "@url": "string",
    * "Amount": 0.1,
    * "AmountCurrency": 0.1,
    * "Booked": true,
    * "Currency": "str",
    * "CurrencyRate": 0.1,
    * "CurrencyUnit": 0.1,
    * "Information": "string",
    * "InvoiceDueDate": "2019-08-24",
    * "InvoiceNumber": "string",
    * "InvoiceOCR": "string",
    * "InvoiceSupplierName": "string",
    * "InvoiceSupplierNumber": "string",
    * "InvoiceTotal": "string",
    * "ModeOfPayment": "string",
    * "Number": 0,
    * "PaymentDate": "2019-08-24",
    * "Source": "manual",
    * "VoucherNumber": 0,
    * "VoucherSeries": "string",
    * "VoucherYear": 0,
    * "WriteOffs": [
      * {
        * "AccountNumber": 1000,
        * "Amount": 0.1,
        * "CostCenter": "string",
        * "Currency": "str",
        * "Description": "string",
        * "Project": "string",
        * "TransactionInformation": "string"
}
]
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_SupplierInvoicePayments/operation/remove_20)Remove a supplier invoice payment 
##### path Parameters
Numberrequired| integer <int32> identifies the supplier invoice payment  
---|---  
### Responses
**204**
Successfully removed the specified resource.
**default**
Error information if the request did not succeed
delete/3/supplierinvoicepayments/{Number}
Default server
https://api.fortnox.se/3/supplierinvoicepayments/{Number}
###  Response samples 
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ErrorInformation": {
    * "Code": 0,
    * "Error": 0,
    * "Message": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_SupplierInvoicePayments/operation/get_47)Retrieve a single supplier invoice payment 
##### path Parameters
Numberrequired| integer <int32> identifies the supplier invoice payment  
---|---  
### Responses
**200**
the existing supplier invoice payment
**default**
Error information if the request did not succeed
get/3/supplierinvoicepayments/{Number}
Default server
https://api.fortnox.se/3/supplierinvoicepayments/{Number}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "SupplierInvoicePayment": {
    * "@url": "string",
    * "Amount": 0.1,
    * "AmountCurrency": 0.1,
    * "Booked": true,
    * "Currency": "str",
    * "CurrencyRate": 0.1,
    * "CurrencyUnit": 0.1,
    * "Information": "string",
    * "InvoiceDueDate": "2019-08-24",
    * "InvoiceNumber": "string",
    * "InvoiceOCR": "string",
    * "InvoiceSupplierName": "string",
    * "InvoiceSupplierNumber": "string",
    * "InvoiceTotal": "string",
    * "ModeOfPayment": "string",
    * "Number": 0,
    * "PaymentDate": "2019-08-24",
    * "Source": "manual",
    * "VoucherNumber": 0,
    * "VoucherSeries": "string",
    * "VoucherYear": 0,
    * "WriteOffs": [
      * {
        * "AccountNumber": 1000,
        * "Amount": 0.1,
        * "CostCenter": "string",
        * "Currency": "str",
        * "Description": "string",
        * "Project": "string",
        * "TransactionInformation": "string"
}
]
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_SupplierInvoicePayments/operation/update_36)Update a supplier invoice payment 
##### path Parameters
Numberrequired| integer <int32> identifies the supplier invoice payment  
---|---  
##### Request Body schema: */*
to update
SupplierInvoicePayment| object (fortnox_SupplierInvoicePayment)   
---|---  
### Responses
**200**
the updated supplier invoice payment
**default**
Error information if the request did not succeed
put/3/supplierinvoicepayments/{Number}
Default server
https://api.fortnox.se/3/supplierinvoicepayments/{Number}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "SupplierInvoicePayment": {
    * "@url": "string",
    * "Amount": 0.1,
    * "AmountCurrency": 0.1,
    * "Booked": true,
    * "Currency": "str",
    * "CurrencyRate": 0.1,
    * "CurrencyUnit": 0.1,
    * "Information": "string",
    * "InvoiceDueDate": "2019-08-24",
    * "InvoiceNumber": "string",
    * "InvoiceOCR": "string",
    * "InvoiceSupplierName": "string",
    * "InvoiceSupplierNumber": "string",
    * "InvoiceTotal": "string",
    * "ModeOfPayment": "string",
    * "Number": 0,
    * "PaymentDate": "2019-08-24",
    * "Source": "manual",
    * "VoucherNumber": 0,
    * "VoucherSeries": "string",
    * "VoucherYear": 0,
    * "WriteOffs": [
      * {
        * "AccountNumber": 1000,
        * "Amount": 0.1,
        * "CostCenter": "string",
        * "Currency": "str",
        * "Description": "string",
        * "Project": "string",
        * "TransactionInformation": "string"
}
]
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_SupplierInvoicePayments/operation/bookkeep_3)Bookkeep a supplier invoice payment 
##### path Parameters
Numberrequired| integer <int32> identifies the supplier invoice payment  
---|---  
### Responses
**200**
the updated supplier invoice payment
**default**
Error information if the request did not succeed
put/3/supplierinvoicepayments/{Number}/bookkeep
Default server
https://api.fortnox.se/3/supplierinvoicepayments/{Number}/bookkeep
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "SupplierInvoicePayment": {
    * "@url": "string",
    * "Amount": 0.1,
    * "AmountCurrency": 0.1,
    * "Booked": true,
    * "Currency": "str",
    * "CurrencyRate": 0.1,
    * "CurrencyUnit": 0.1,
    * "Information": "string",
    * "InvoiceDueDate": "2019-08-24",
    * "InvoiceNumber": "string",
    * "InvoiceOCR": "string",
    * "InvoiceSupplierName": "string",
    * "InvoiceSupplierNumber": "string",
    * "InvoiceTotal": "string",
    * "ModeOfPayment": "string",
    * "Number": 0,
    * "PaymentDate": "2019-08-24",
    * "Source": "manual",
    * "VoucherNumber": 0,
    * "VoucherSeries": "string",
    * "VoucherYear": 0,
    * "WriteOffs": [
      * {
        * "AccountNumber": 1000,
        * "Amount": 0.1,
        * "CostCenter": "string",
        * "Currency": "str",
        * "Description": "string",
        * "Project": "string",
        * "TransactionInformation": "string"
}
]
}

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_SupplierInvoices)Supplier Invoices
Possible filters on Supplier Invoice endpoint **Filter** | **Description**  
---|---  
cancelled | Retrieves all invoices with the status "cancelled".  
fullypaid | Retrieves all invoices that has been fully paid.  
unpaid | Retrieves all invoices that is unpaid.  
unpaidoverdue | Retrieves all invoices that is unpaid and overdue.  
unbooked | Retrieves all invoices that is unbooked.  
pendingpayment | Retrieves all invoices that has PaymentPending=true and is booked.  
authorizepending | Retrieves all invoices that has a waiting authorization pending.  
## [](https://api.fortnox.se/apidocs#tag/fortnox_SupplierInvoices/operation/list_39)Retrieve a list of supplier invoices 
##### query Parameters
filter| string Enum: "cancelled" "fullypaid" "unpaid" "unpaidoverdue" "unbooked" "pendingpayment" "authorizepending" possibility to filter supplier invoices  
---|---  
### Responses
**200**
list of supplier invoices
**default**
Error information if the request did not succeed
get/3/supplierinvoices
Default server
https://api.fortnox.se/3/supplierinvoices
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "SupplierInvoices": [
    * {
      * "@url": "string",
      * "AuthorizerName": "string",
      * "Balance": "string",
      * "Booked": true,
      * "Cancel": true,
      * "CostCenter": "string",
      * "Credit": true,
      * "Currency": "string",
      * "CurrencyRate": "string",
      * "CurrencyUnit": 0.1,
      * "DueDate": "2019-08-24",
      * "ExternalInvoiceNumber": "string",
      * "ExternalInvoiceSeries": "string",
      * "FinalPayDate": "2019-08-24",
      * "GivenNumber": "string",
      * "InvoiceDate": "2019-08-24",
      * "InvoiceNumber": "string",
      * "Project": "string",
      * "SupplierName": "string",
      * "SupplierNumber": "string",
      * "Total": "string",
      * "Vouchers": [
        * {
          * "Number": 0,
          * "ReferenceType": "string",
          * "Series": "string",
          * "Year": 0
}
]
}
]

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_SupplierInvoices/operation/create_39)Create a supplier invoice 
##### Request Body schema: */*
supplier invoice to create
SupplierInvoice| object (fortnox_SupplierInvoice)   
---|---  
### Responses
**201**
the created supplier invoice
**default**
Error information if the request did not succeed
post/3/supplierinvoices
Default server
https://api.fortnox.se/3/supplierinvoices
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "SupplierInvoice": {
    * "@url": "string",
    * "AccountingMethod": "ACCRUAL",
    * "AdministrationFee": "string",
    * "Balance": "string",
    * "Booked": true,
    * "Cancelled": true,
    * "Comments": "string",
    * "CostCenter": "string",
    * "Credit": true,
    * "CreditReference": 0,
    * "Currency": "string",
    * "CurrencyRate": "string",
    * "CurrencyUnit": 0.1,
    * "DisablePaymentFile": true,
    * "DueDate": "2019-08-24",
    * "ExternalInvoiceNumber": "string",
    * "ExternalInvoiceSeries": "string",
    * "FinalPayDate": "2019-08-24",
    * "Freight": "string",
    * "GivenNumber": "string",
    * "InvoiceDate": "2019-08-24",
    * "InvoiceNumber": "string",
    * "OCR": "string",
    * "OurReference": "string",
    * "PaymentPending": true,
    * "Project": "string",
    * "RoundOffValue": "string",
    * "SalesType": "STOCK",
    * "SupplierInvoiceRows": [
      * {
        * "Account": 1000,
        * "AccountDescription": "string",
        * "ArticleNumber": "string",
        * "Code": "TOT",
        * "CostCenter": "string",
        * "Credit": 0.1,
        * "CreditCurrency": 0.1,
        * "Debit": 0.1,
        * "DebitCurrency": 0.1,
        * "ItemDescription": "string",
        * "Price": 0.1,
        * "Project": "string",
        * "Quantity": 0,
        * "StockLocationCode": "string",
        * "StockPointCode": "string",
        * "Total": 0.1,
        * "TransactionInformation": "string",
        * "Unit": "string"
}
],
    * "SupplierName": "string",
    * "SupplierNumber": "string",
    * "Total": "string",
    * "VAT": "string",
    * "VATType": "NORMAL",
    * "VoucherNumber": 0,
    * "VoucherSeries": "string",
    * "VoucherYear": 0,
    * "Vouchers": [
      * {
        * "Number": 0,
        * "ReferenceType": "string",
        * "Series": "string",
        * "Year": 0
}
],
    * "YourReference": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_SupplierInvoices/operation/get_48)Retrieve a single supplier invoice 
##### path Parameters
GivenNumberrequired| integer <int32> identifies the invoice  
---|---  
### Responses
**200**
the existing supplier invoice
**default**
Error information if the request did not succeed
get/3/supplierinvoices/{GivenNumber}
Default server
https://api.fortnox.se/3/supplierinvoices/{GivenNumber}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "SupplierInvoice": {
    * "@url": "string",
    * "AccountingMethod": "ACCRUAL",
    * "AdministrationFee": "string",
    * "Balance": "string",
    * "Booked": true,
    * "Cancelled": true,
    * "Comments": "string",
    * "CostCenter": "string",
    * "Credit": true,
    * "CreditReference": 0,
    * "Currency": "string",
    * "CurrencyRate": "string",
    * "CurrencyUnit": 0.1,
    * "DisablePaymentFile": true,
    * "DueDate": "2019-08-24",
    * "ExternalInvoiceNumber": "string",
    * "ExternalInvoiceSeries": "string",
    * "FinalPayDate": "2019-08-24",
    * "Freight": "string",
    * "GivenNumber": "string",
    * "InvoiceDate": "2019-08-24",
    * "InvoiceNumber": "string",
    * "OCR": "string",
    * "OurReference": "string",
    * "PaymentPending": true,
    * "Project": "string",
    * "RoundOffValue": "string",
    * "SalesType": "STOCK",
    * "SupplierInvoiceRows": [
      * {
        * "Account": 1000,
        * "AccountDescription": "string",
        * "ArticleNumber": "string",
        * "Code": "TOT",
        * "CostCenter": "string",
        * "Credit": 0.1,
        * "CreditCurrency": 0.1,
        * "Debit": 0.1,
        * "DebitCurrency": 0.1,
        * "ItemDescription": "string",
        * "Price": 0.1,
        * "Project": "string",
        * "Quantity": 0,
        * "StockLocationCode": "string",
        * "StockPointCode": "string",
        * "Total": 0.1,
        * "TransactionInformation": "string",
        * "Unit": "string"
}
],
    * "SupplierName": "string",
    * "SupplierNumber": "string",
    * "Total": "string",
    * "VAT": "string",
    * "VATType": "NORMAL",
    * "VoucherNumber": 0,
    * "VoucherSeries": "string",
    * "VoucherYear": 0,
    * "Vouchers": [
      * {
        * "Number": 0,
        * "ReferenceType": "string",
        * "Series": "string",
        * "Year": 0
}
],
    * "YourReference": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_SupplierInvoices/operation/update_37)Update a supplier invoice 
##### path Parameters
GivenNumberrequired| integer <int32> identifies the invoice  
---|---  
##### Request Body schema: */*
supplier invoice to update
SupplierInvoice| object (fortnox_SupplierInvoice)   
---|---  
### Responses
**200**
the updated supplier invoice
**default**
Error information if the request did not succeed
put/3/supplierinvoices/{GivenNumber}
Default server
https://api.fortnox.se/3/supplierinvoices/{GivenNumber}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "SupplierInvoice": {
    * "@url": "string",
    * "AccountingMethod": "ACCRUAL",
    * "AdministrationFee": "string",
    * "Balance": "string",
    * "Booked": true,
    * "Cancelled": true,
    * "Comments": "string",
    * "CostCenter": "string",
    * "Credit": true,
    * "CreditReference": 0,
    * "Currency": "string",
    * "CurrencyRate": "string",
    * "CurrencyUnit": 0.1,
    * "DisablePaymentFile": true,
    * "DueDate": "2019-08-24",
    * "ExternalInvoiceNumber": "string",
    * "ExternalInvoiceSeries": "string",
    * "FinalPayDate": "2019-08-24",
    * "Freight": "string",
    * "GivenNumber": "string",
    * "InvoiceDate": "2019-08-24",
    * "InvoiceNumber": "string",
    * "OCR": "string",
    * "OurReference": "string",
    * "PaymentPending": true,
    * "Project": "string",
    * "RoundOffValue": "string",
    * "SalesType": "STOCK",
    * "SupplierInvoiceRows": [
      * {
        * "Account": 1000,
        * "AccountDescription": "string",
        * "ArticleNumber": "string",
        * "Code": "TOT",
        * "CostCenter": "string",
        * "Credit": 0.1,
        * "CreditCurrency": 0.1,
        * "Debit": 0.1,
        * "DebitCurrency": 0.1,
        * "ItemDescription": "string",
        * "Price": 0.1,
        * "Project": "string",
        * "Quantity": 0,
        * "StockLocationCode": "string",
        * "StockPointCode": "string",
        * "Total": 0.1,
        * "TransactionInformation": "string",
        * "Unit": "string"
}
],
    * "SupplierName": "string",
    * "SupplierNumber": "string",
    * "Total": "string",
    * "VAT": "string",
    * "VATType": "NORMAL",
    * "VoucherNumber": 0,
    * "VoucherSeries": "string",
    * "VoucherYear": 0,
    * "Vouchers": [
      * {
        * "Number": 0,
        * "ReferenceType": "string",
        * "Series": "string",
        * "Year": 0
}
],
    * "YourReference": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_SupplierInvoices/operation/approvalbookkeep)Approval of bookkeep of given supplier invoice 
##### path Parameters
GivenNumberrequired| integer <int32> identifies the invoice  
---|---  
### Responses
**200**
the updated supplier invoice
**default**
Error information if the request did not succeed
put/3/supplierinvoices/{GivenNumber}/approvalbookkeep
Default server
https://api.fortnox.se/3/supplierinvoices/{GivenNumber}/approvalbookkeep
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "SupplierInvoice": {
    * "@url": "string",
    * "AccountingMethod": "ACCRUAL",
    * "AdministrationFee": "string",
    * "Balance": "string",
    * "Booked": true,
    * "Cancelled": true,
    * "Comments": "string",
    * "CostCenter": "string",
    * "Credit": true,
    * "CreditReference": 0,
    * "Currency": "string",
    * "CurrencyRate": "string",
    * "CurrencyUnit": 0.1,
    * "DisablePaymentFile": true,
    * "DueDate": "2019-08-24",
    * "ExternalInvoiceNumber": "string",
    * "ExternalInvoiceSeries": "string",
    * "FinalPayDate": "2019-08-24",
    * "Freight": "string",
    * "GivenNumber": "string",
    * "InvoiceDate": "2019-08-24",
    * "InvoiceNumber": "string",
    * "OCR": "string",
    * "OurReference": "string",
    * "PaymentPending": true,
    * "Project": "string",
    * "RoundOffValue": "string",
    * "SalesType": "STOCK",
    * "SupplierInvoiceRows": [
      * {
        * "Account": 1000,
        * "AccountDescription": "string",
        * "ArticleNumber": "string",
        * "Code": "TOT",
        * "CostCenter": "string",
        * "Credit": 0.1,
        * "CreditCurrency": 0.1,
        * "Debit": 0.1,
        * "DebitCurrency": 0.1,
        * "ItemDescription": "string",
        * "Price": 0.1,
        * "Project": "string",
        * "Quantity": 0,
        * "StockLocationCode": "string",
        * "StockPointCode": "string",
        * "Total": 0.1,
        * "TransactionInformation": "string",
        * "Unit": "string"
}
],
    * "SupplierName": "string",
    * "SupplierNumber": "string",
    * "Total": "string",
    * "VAT": "string",
    * "VATType": "NORMAL",
    * "VoucherNumber": 0,
    * "VoucherSeries": "string",
    * "VoucherYear": 0,
    * "Vouchers": [
      * {
        * "Number": 0,
        * "ReferenceType": "string",
        * "Series": "string",
        * "Year": 0
}
],
    * "YourReference": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_SupplierInvoices/operation/approvalpayment)Approval of payment of given supplier invoice 
##### path Parameters
GivenNumberrequired| integer <int32> identifies the invoice  
---|---  
### Responses
**200**
the updated supplier invoice
**default**
Error information if the request did not succeed
put/3/supplierinvoices/{GivenNumber}/approvalpayment
Default server
https://api.fortnox.se/3/supplierinvoices/{GivenNumber}/approvalpayment
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "SupplierInvoice": {
    * "@url": "string",
    * "AccountingMethod": "ACCRUAL",
    * "AdministrationFee": "string",
    * "Balance": "string",
    * "Booked": true,
    * "Cancelled": true,
    * "Comments": "string",
    * "CostCenter": "string",
    * "Credit": true,
    * "CreditReference": 0,
    * "Currency": "string",
    * "CurrencyRate": "string",
    * "CurrencyUnit": 0.1,
    * "DisablePaymentFile": true,
    * "DueDate": "2019-08-24",
    * "ExternalInvoiceNumber": "string",
    * "ExternalInvoiceSeries": "string",
    * "FinalPayDate": "2019-08-24",
    * "Freight": "string",
    * "GivenNumber": "string",
    * "InvoiceDate": "2019-08-24",
    * "InvoiceNumber": "string",
    * "OCR": "string",
    * "OurReference": "string",
    * "PaymentPending": true,
    * "Project": "string",
    * "RoundOffValue": "string",
    * "SalesType": "STOCK",
    * "SupplierInvoiceRows": [
      * {
        * "Account": 1000,
        * "AccountDescription": "string",
        * "ArticleNumber": "string",
        * "Code": "TOT",
        * "CostCenter": "string",
        * "Credit": 0.1,
        * "CreditCurrency": 0.1,
        * "Debit": 0.1,
        * "DebitCurrency": 0.1,
        * "ItemDescription": "string",
        * "Price": 0.1,
        * "Project": "string",
        * "Quantity": 0,
        * "StockLocationCode": "string",
        * "StockPointCode": "string",
        * "Total": 0.1,
        * "TransactionInformation": "string",
        * "Unit": "string"
}
],
    * "SupplierName": "string",
    * "SupplierNumber": "string",
    * "Total": "string",
    * "VAT": "string",
    * "VATType": "NORMAL",
    * "VoucherNumber": 0,
    * "VoucherSeries": "string",
    * "VoucherYear": 0,
    * "Vouchers": [
      * {
        * "Number": 0,
        * "ReferenceType": "string",
        * "Series": "string",
        * "Year": 0
}
],
    * "YourReference": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_SupplierInvoices/operation/bookkeep_4)Bookkeep given supplier invoice 
##### path Parameters
GivenNumberrequired| integer <int32> identifies the invoice  
---|---  
### Responses
**200**
the updated supplier invoice
**default**
Error information if the request did not succeed
put/3/supplierinvoices/{GivenNumber}/bookkeep
Default server
https://api.fortnox.se/3/supplierinvoices/{GivenNumber}/bookkeep
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "SupplierInvoice": {
    * "@url": "string",
    * "AccountingMethod": "ACCRUAL",
    * "AdministrationFee": "string",
    * "Balance": "string",
    * "Booked": true,
    * "Cancelled": true,
    * "Comments": "string",
    * "CostCenter": "string",
    * "Credit": true,
    * "CreditReference": 0,
    * "Currency": "string",
    * "CurrencyRate": "string",
    * "CurrencyUnit": 0.1,
    * "DisablePaymentFile": true,
    * "DueDate": "2019-08-24",
    * "ExternalInvoiceNumber": "string",
    * "ExternalInvoiceSeries": "string",
    * "FinalPayDate": "2019-08-24",
    * "Freight": "string",
    * "GivenNumber": "string",
    * "InvoiceDate": "2019-08-24",
    * "InvoiceNumber": "string",
    * "OCR": "string",
    * "OurReference": "string",
    * "PaymentPending": true,
    * "Project": "string",
    * "RoundOffValue": "string",
    * "SalesType": "STOCK",
    * "SupplierInvoiceRows": [
      * {
        * "Account": 1000,
        * "AccountDescription": "string",
        * "ArticleNumber": "string",
        * "Code": "TOT",
        * "CostCenter": "string",
        * "Credit": 0.1,
        * "CreditCurrency": 0.1,
        * "Debit": 0.1,
        * "DebitCurrency": 0.1,
        * "ItemDescription": "string",
        * "Price": 0.1,
        * "Project": "string",
        * "Quantity": 0,
        * "StockLocationCode": "string",
        * "StockPointCode": "string",
        * "Total": 0.1,
        * "TransactionInformation": "string",
        * "Unit": "string"
}
],
    * "SupplierName": "string",
    * "SupplierNumber": "string",
    * "Total": "string",
    * "VAT": "string",
    * "VATType": "NORMAL",
    * "VoucherNumber": 0,
    * "VoucherSeries": "string",
    * "VoucherYear": 0,
    * "Vouchers": [
      * {
        * "Number": 0,
        * "ReferenceType": "string",
        * "Series": "string",
        * "Year": 0
}
],
    * "YourReference": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_SupplierInvoices/operation/cancel_6)Cancels given supplier invoice 
##### path Parameters
GivenNumberrequired| integer <int32> identifies the invoice  
---|---  
### Responses
**200**
the updated supplier invoice
**default**
Error information if the request did not succeed
put/3/supplierinvoices/{GivenNumber}/cancel
Default server
https://api.fortnox.se/3/supplierinvoices/{GivenNumber}/cancel
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "SupplierInvoice": {
    * "@url": "string",
    * "AccountingMethod": "ACCRUAL",
    * "AdministrationFee": "string",
    * "Balance": "string",
    * "Booked": true,
    * "Cancelled": true,
    * "Comments": "string",
    * "CostCenter": "string",
    * "Credit": true,
    * "CreditReference": 0,
    * "Currency": "string",
    * "CurrencyRate": "string",
    * "CurrencyUnit": 0.1,
    * "DisablePaymentFile": true,
    * "DueDate": "2019-08-24",
    * "ExternalInvoiceNumber": "string",
    * "ExternalInvoiceSeries": "string",
    * "FinalPayDate": "2019-08-24",
    * "Freight": "string",
    * "GivenNumber": "string",
    * "InvoiceDate": "2019-08-24",
    * "InvoiceNumber": "string",
    * "OCR": "string",
    * "OurReference": "string",
    * "PaymentPending": true,
    * "Project": "string",
    * "RoundOffValue": "string",
    * "SalesType": "STOCK",
    * "SupplierInvoiceRows": [
      * {
        * "Account": 1000,
        * "AccountDescription": "string",
        * "ArticleNumber": "string",
        * "Code": "TOT",
        * "CostCenter": "string",
        * "Credit": 0.1,
        * "CreditCurrency": 0.1,
        * "Debit": 0.1,
        * "DebitCurrency": 0.1,
        * "ItemDescription": "string",
        * "Price": 0.1,
        * "Project": "string",
        * "Quantity": 0,
        * "StockLocationCode": "string",
        * "StockPointCode": "string",
        * "Total": 0.1,
        * "TransactionInformation": "string",
        * "Unit": "string"
}
],
    * "SupplierName": "string",
    * "SupplierNumber": "string",
    * "Total": "string",
    * "VAT": "string",
    * "VATType": "NORMAL",
    * "VoucherNumber": 0,
    * "VoucherSeries": "string",
    * "VoucherYear": 0,
    * "Vouchers": [
      * {
        * "Number": 0,
        * "ReferenceType": "string",
        * "Series": "string",
        * "Year": 0
}
],
    * "YourReference": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_SupplierInvoices/operation/credit_2)Credit given supplier invoice 
The created credit invoice will be referenced in the property CreditReference.
##### path Parameters
GivenNumberrequired| integer <int32> identifies the invoice  
---|---  
### Responses
**200**
the updated supplier invoice
**default**
Error information if the request did not succeed
put/3/supplierinvoices/{GivenNumber}/credit
Default server
https://api.fortnox.se/3/supplierinvoices/{GivenNumber}/credit
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "SupplierInvoice": {
    * "@url": "string",
    * "AccountingMethod": "ACCRUAL",
    * "AdministrationFee": "string",
    * "Balance": "string",
    * "Booked": true,
    * "Cancelled": true,
    * "Comments": "string",
    * "CostCenter": "string",
    * "Credit": true,
    * "CreditReference": 0,
    * "Currency": "string",
    * "CurrencyRate": "string",
    * "CurrencyUnit": 0.1,
    * "DisablePaymentFile": true,
    * "DueDate": "2019-08-24",
    * "ExternalInvoiceNumber": "string",
    * "ExternalInvoiceSeries": "string",
    * "FinalPayDate": "2019-08-24",
    * "Freight": "string",
    * "GivenNumber": "string",
    * "InvoiceDate": "2019-08-24",
    * "InvoiceNumber": "string",
    * "OCR": "string",
    * "OurReference": "string",
    * "PaymentPending": true,
    * "Project": "string",
    * "RoundOffValue": "string",
    * "SalesType": "STOCK",
    * "SupplierInvoiceRows": [
      * {
        * "Account": 1000,
        * "AccountDescription": "string",
        * "ArticleNumber": "string",
        * "Code": "TOT",
        * "CostCenter": "string",
        * "Credit": 0.1,
        * "CreditCurrency": 0.1,
        * "Debit": 0.1,
        * "DebitCurrency": 0.1,
        * "ItemDescription": "string",
        * "Price": 0.1,
        * "Project": "string",
        * "Quantity": 0,
        * "StockLocationCode": "string",
        * "StockPointCode": "string",
        * "Total": 0.1,
        * "TransactionInformation": "string",
        * "Unit": "string"
}
],
    * "SupplierName": "string",
    * "SupplierNumber": "string",
    * "Total": "string",
    * "VAT": "string",
    * "VATType": "NORMAL",
    * "VoucherNumber": 0,
    * "VoucherSeries": "string",
    * "VoucherYear": 0,
    * "Vouchers": [
      * {
        * "Number": 0,
        * "ReferenceType": "string",
        * "Series": "string",
        * "Year": 0
}
],
    * "YourReference": "string"
}

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_Suppliers)Suppliers
Resource for the CRUD operations on suppliers
## [](https://api.fortnox.se/apidocs#tag/fortnox_Suppliers/operation/list_40)Retrieve a list of suppliers 
The supplier register can return a list of records or a single record. By specifying a SupplierNumber in the URL, a single record will be returned. Not specifying a SupplierNumber will return a list of records.
### Responses
**200**
list of suppliers
**default**
Error information if the request did not succeed
get/3/suppliers
Default server
https://api.fortnox.se/3/suppliers
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Suppliers": [
    * {
      * "@url": "string",
      * "Active": true,
      * "Address1": "string",
      * "Address2": "string",
      * "BG": "string",
      * "BIC": "string",
      * "BankAccountNumber": "string",
      * "City": "string",
      * "CostCenter": "string",
      * "CountryCode": "st",
      * "Currency": "str",
      * "DisablePaymentFile": true,
      * "Email": "string",
      * "IBAN": "string",
      * "Name": "string",
      * "OrganisationNumber": "string",
      * "PG": "string",
      * "Phone": "string",
      * "PreDefinedAccount": "stri",
      * "Project": "string",
      * "SupplierNumber": "string",
      * "TermsOfPayment": "string",
      * "ZipCode": "string"
}
]

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Suppliers/operation/create_40)Create a supplier 
##### Request Body schema: */*
to create
Supplier| object (fortnox_Supplier)   
---|---  
### Responses
**201**
the created supplier
**default**
Error information if the request did not succeed
post/3/suppliers
Default server
https://api.fortnox.se/3/suppliers
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Supplier": {
    * "@url": "string",
    * "Active": true,
    * "Address1": "string",
    * "Address2": "string",
    * "BG": "string",
    * "BIC": "string",
    * "Bank": "string",
    * "BankAccountNumber": "string",
    * "BranchCode": "string",
    * "City": "string",
    * "ClearingNumber": "string",
    * "Comments": "string",
    * "CostCenter": "string",
    * "Country": "string",
    * "CountryCode": "st",
    * "Currency": "str",
    * "DisablePaymentFile": true,
    * "Email": "string",
    * "Fax": "string",
    * "IBAN": "string",
    * "Name": "string",
    * "OrganisationNumber": "string",
    * "OurCustomerNumber": "string",
    * "OurReference": "string",
    * "PG": "string",
    * "Phone1": "string",
    * "Phone2": "string",
    * "PreDefinedAccount": "stri",
    * "Project": "string",
    * "SupplierNumber": "string",
    * "TermsOfPayment": "string",
    * "VATNumber": "string",
    * "VATType": "string",
    * "VisitingAddress": "string",
    * "VisitingCity": "string",
    * "VisitingCountry": "string",
    * "VisitingCountryCode": "string",
    * "VisitingZipCode": "string",
    * "WWW": "string",
    * "WorkPlace": "string",
    * "YourReference": "string",
    * "ZipCode": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Suppliers/operation/get_49)Retrieve a single supplier 
##### path Parameters
SupplierNumberrequired| string identifies the supplier  
---|---  
### Responses
**200**
the existing supplier
**default**
Error information if the request did not succeed
get/3/suppliers/{SupplierNumber}
Default server
https://api.fortnox.se/3/suppliers/{SupplierNumber}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Supplier": {
    * "@url": "string",
    * "Active": true,
    * "Address1": "string",
    * "Address2": "string",
    * "BG": "string",
    * "BIC": "string",
    * "Bank": "string",
    * "BankAccountNumber": "string",
    * "BranchCode": "string",
    * "City": "string",
    * "ClearingNumber": "string",
    * "Comments": "string",
    * "CostCenter": "string",
    * "Country": "string",
    * "CountryCode": "st",
    * "Currency": "str",
    * "DisablePaymentFile": true,
    * "Email": "string",
    * "Fax": "string",
    * "IBAN": "string",
    * "Name": "string",
    * "OrganisationNumber": "string",
    * "OurCustomerNumber": "string",
    * "OurReference": "string",
    * "PG": "string",
    * "Phone1": "string",
    * "Phone2": "string",
    * "PreDefinedAccount": "stri",
    * "Project": "string",
    * "SupplierNumber": "string",
    * "TermsOfPayment": "string",
    * "VATNumber": "string",
    * "VATType": "string",
    * "VisitingAddress": "string",
    * "VisitingCity": "string",
    * "VisitingCountry": "string",
    * "VisitingCountryCode": "string",
    * "VisitingZipCode": "string",
    * "WWW": "string",
    * "WorkPlace": "string",
    * "YourReference": "string",
    * "ZipCode": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Suppliers/operation/update_38)Update a supplier 
##### path Parameters
SupplierNumberrequired| string identifies the supplier  
---|---  
##### Request Body schema: */*
to update
Supplier| object (fortnox_Supplier)   
---|---  
### Responses
**200**
the updated supplier
**default**
Error information if the request did not succeed
put/3/suppliers/{SupplierNumber}
Default server
https://api.fortnox.se/3/suppliers/{SupplierNumber}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Supplier": {
    * "@url": "string",
    * "Active": true,
    * "Address1": "string",
    * "Address2": "string",
    * "BG": "string",
    * "BIC": "string",
    * "Bank": "string",
    * "BankAccountNumber": "string",
    * "BranchCode": "string",
    * "City": "string",
    * "ClearingNumber": "string",
    * "Comments": "string",
    * "CostCenter": "string",
    * "Country": "string",
    * "CountryCode": "st",
    * "Currency": "str",
    * "DisablePaymentFile": true,
    * "Email": "string",
    * "Fax": "string",
    * "IBAN": "string",
    * "Name": "string",
    * "OrganisationNumber": "string",
    * "OurCustomerNumber": "string",
    * "OurReference": "string",
    * "PG": "string",
    * "Phone1": "string",
    * "Phone2": "string",
    * "PreDefinedAccount": "stri",
    * "Project": "string",
    * "SupplierNumber": "string",
    * "TermsOfPayment": "string",
    * "VATNumber": "string",
    * "VATType": "string",
    * "VisitingAddress": "string",
    * "VisitingCity": "string",
    * "VisitingCountry": "string",
    * "VisitingCountryCode": "string",
    * "VisitingZipCode": "string",
    * "WWW": "string",
    * "WorkPlace": "string",
    * "YourReference": "string",
    * "ZipCode": "string"
}

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_TaxReductions)Tax Reductions
Tax reductions resources 
Possible filters **Filter** | **Description**  
---|---  
invoices | Retrieves all Tax reductions for invoices  
orders | Retrieves all Tax reductions for orders  
offers | Retrieves all Tax reductions for offers  
## [](https://api.fortnox.se/apidocs#tag/fortnox_TaxReductions/operation/list_41)Retrieve a list of tax reductions 
##### query Parameters
filter| string Enum: "invoices" "orders" "offers" possibility to filter tax reductions  
---|---  
### Responses
**200**
a list of tax reductions.
**default**
Error information if the request did not succeed
get/3/taxreductions
Default server
https://api.fortnox.se/3/taxreductions
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "TaxReductions": [
    * {
      * "@url": "string",
      * "ApprovedAmount": 0.1,
      * "CustomerName": "string",
      * "Id": 0,
      * "ReferenceDocumentType": "OFFER",
      * "ReferenceNumber": 0,
      * "SocialSecurityNumber": "stringstri"
}
]

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_TaxReductions/operation/create_41)Create a Tax Reduction 
Note that different types of tax reduction, i.e. ROT, RUT, or Green Technology, applications work differently. When creating an application for Green Technology, the field _TaxReductionAmounts_ becomes mandatory as it is used to determine how much of the asked amount is intended for which type of work. Similarly, the _AskedAmount_ field of the _TaxReduction_ becomes optional, as it will always be considered to be equal to the sum of the _TaxReductionAmounts_.
For the other types, ROT and RUT, this field is not required and should be omitted.
Unlike earlier iterations of this endpoint, specifying the type of reduction for the provided _TaxReduction_ (e.g. ROT, RUT, or Green) is not necessary as this value will always be equal to the type set on the provided document instead.
This endpoint can raise a variety of validation errors, some of which are only relevant for Green Technology applications. Those errors will always return an HTTP Code of 400 and include, but are not limited to, those shown below:
Errors that can be raised by this endpoint. Error Code | Types | Description | Solution  
---|---|---|---  
2000600 | ROT, RUT, GREEN | The provided Social Security Number is already in use for this document. | Verify that the Social Security Number is different from any other applicants already added.  
2004217, 2004218 | ROT, RUT, GREEN | The total asked amount of the application is either in an invalid format or is negative. | Verify that the _AskedAmount_ -field is a positive number (0 is valid for Green Technology) and that it is an integer.  
2004209 | GREEN | The _WorkType_ -field contains a work type that is not valid for the given type of reduction. | Ensure that the _WorkType_ contains a valid type of work for Green Technology.  
2004263 | GREEN | The _TaxReductionAmounts_ -field is missing for a Green Technology application. | Ensure that the field is included, that it is an array, and that each contained object denotes a specific type's asked amount.  
2004262 | GREEN | There are more than one object denoting the asked amount for the same type in the _TaxReductionAmounts_ -field. | Ensure that there is only one object denoting the asked amount per type contained in the array.  
##### Request Body schema: */*
to create
TaxReductionrequired| object (fortnox_TaxReduction)   
---|---  
### Responses
**201**
the created tax reduction
**default**
Error information if the request did not succeed
post/3/taxreductions
Default server
https://api.fortnox.se/3/taxreductions
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "TaxReduction": {
    * "@url": "string",
    * "ApprovedAmount": 0.1,
    * "AskedAmount": 1,
    * "BilledAmount": 0.1,
    * "CustomerName": "string",
    * "Id": 0,
    * "PropertyDesignation": "string",
    * "ReferenceDocumentType": "OFFER",
    * "ReferenceNumber": "string",
    * "RequestSent": true,
    * "ResidenceAssociationOrganisationNumber": "string",
    * "SocialSecurityNumber": "stringstri",
    * "TaxReductionAmounts": [
      * {
        * "AskedAmount": 1,
        * "WorkType": "SOLARCELLS"
}
],
    * "VoucherNumber": 0,
    * "VoucherSeries": "string",
    * "VoucherYear": 0
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_TaxReductions/operation/remove_21)Remove a tax reduction 
##### path Parameters
Idrequired| integer <int32> identifies the tax reduction  
---|---  
### Responses
**204**
Successfully removed the specified resource.
**default**
Error information if the request did not succeed
delete/3/taxreductions/{Id}
Default server
https://api.fortnox.se/3/taxreductions/{Id}
###  Response samples 
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ErrorInformation": {
    * "Code": 0,
    * "Error": 0,
    * "Message": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_TaxReductions/operation/get_50)Retrieve a single tax reduction 
##### path Parameters
Idrequired| integer <int32> identifies the tax reduction  
---|---  
### Responses
**200**
the existing tax reduction
**default**
Error information if the request did not succeed
get/3/taxreductions/{Id}
Default server
https://api.fortnox.se/3/taxreductions/{Id}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "TaxReduction": {
    * "@url": "string",
    * "ApprovedAmount": 0.1,
    * "AskedAmount": 1,
    * "BilledAmount": 0.1,
    * "CustomerName": "string",
    * "Id": 0,
    * "PropertyDesignation": "string",
    * "ReferenceDocumentType": "OFFER",
    * "ReferenceNumber": "string",
    * "RequestSent": true,
    * "ResidenceAssociationOrganisationNumber": "string",
    * "SocialSecurityNumber": "stringstri",
    * "TaxReductionAmounts": [
      * {
        * "AskedAmount": 1,
        * "WorkType": "SOLARCELLS"
}
],
    * "VoucherNumber": 0,
    * "VoucherSeries": "string",
    * "VoucherYear": 0
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_TaxReductions/operation/update_39)Update a tax reduction 
##### path Parameters
Idrequired| integer <int32> identifies the tax reduction  
---|---  
##### Request Body schema: */*
to update
TaxReductionrequired| object (fortnox_TaxReduction)   
---|---  
### Responses
**200**
the updated tax reduction
**default**
Error information if the request did not succeed
put/3/taxreductions/{Id}
Default server
https://api.fortnox.se/3/taxreductions/{Id}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "TaxReduction": {
    * "@url": "string",
    * "ApprovedAmount": 0.1,
    * "AskedAmount": 1,
    * "BilledAmount": 0.1,
    * "CustomerName": "string",
    * "Id": 0,
    * "PropertyDesignation": "string",
    * "ReferenceDocumentType": "OFFER",
    * "ReferenceNumber": "string",
    * "RequestSent": true,
    * "ResidenceAssociationOrganisationNumber": "string",
    * "SocialSecurityNumber": "stringstri",
    * "TaxReductionAmounts": [
      * {
        * "AskedAmount": 1,
        * "WorkType": "SOLARCELLS"
}
],
    * "VoucherNumber": 0,
    * "VoucherSeries": "string",
    * "VoucherYear": 0
}

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_TermsOfDeliveries)Terms Of Deliveries
Resource for the CRUD operations on terms of deliveries
## [](https://api.fortnox.se/apidocs#tag/fortnox_TermsOfDeliveries/operation/list_42)Retrieve a list of terms of deliveries 
The terms of deliveries register can return a list of records or a single record. By specifying a Code in the URL, a single record will be returned. Not specifying a Code will return a list of records.
### Responses
**200**
a list of terms of deliveries
**default**
Error information if the request did not succeed
get/3/termsofdeliveries
Default server
https://api.fortnox.se/3/termsofdeliveries
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "TermsOfDeliveries": [
    * {
      * "@url": "string",
      * "Code": "string",
      * "Description": "string",
      * "DescriptionEnglish": "string"
}
]

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_TermsOfDeliveries/operation/create_42)Create a terms of delivery 
##### Request Body schema: */*
to create
TermsOfDeliveryrequired| object (fortnox_TermsOfDelivery)   
---|---  
### Responses
**201**
the created term of delivery
**default**
Error information if the request did not succeed
post/3/termsofdeliveries
Default server
https://api.fortnox.se/3/termsofdeliveries
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "TermsOfDelivery": {
    * "@url": "string",
    * "Code": "string",
    * "Description": "string",
    * "DescriptionEnglish": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_TermsOfDeliveries/operation/get_51)Retrieve a single terms of delivery 
##### path Parameters
Coderequired| string identifies the terms of delivery  
---|---  
### Responses
**200**
the existing terms of delivery
**default**
Error information if the request did not succeed
get/3/termsofdeliveries/{Code}
Default server
https://api.fortnox.se/3/termsofdeliveries/{Code}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "TermsOfDelivery": {
    * "@url": "string",
    * "Code": "string",
    * "Description": "string",
    * "DescriptionEnglish": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_TermsOfDeliveries/operation/update_40)Update a terms of delivery 
##### path Parameters
Coderequired| string identifies the terms of delivery  
---|---  
##### Request Body schema: */*
to update
TermsOfDeliveryrequired| object (fortnox_TermsOfDelivery)   
---|---  
### Responses
**200**
the updated terms of delivery
**default**
Error information if the request did not succeed
put/3/termsofdeliveries/{Code}
Default server
https://api.fortnox.se/3/termsofdeliveries/{Code}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "TermsOfDelivery": {
    * "@url": "string",
    * "Code": "string",
    * "Description": "string",
    * "DescriptionEnglish": "string"
}

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_TermsOfPayments)Terms Of Payments
Resource for the CRUD operations on terms of payments
## [](https://api.fortnox.se/apidocs#tag/fortnox_TermsOfPayments/operation/list_43)Retrieve a list of all terms of payments 
### Responses
**200**
a list of terms of payments
**default**
Error information if the request did not succeed
get/3/termsofpayments
Default server
https://api.fortnox.se/3/termsofpayments
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "TermsOfPayments": [
    * {
      * "@url": "string",
      * "Code": "string",
      * "Description": "string"
}
]

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_TermsOfPayments/operation/create_43)Create a term of payment 
##### Request Body schema: */*
to create
TermsOfPaymentrequired| object (fortnox_TermsOfPayment)   
---|---  
### Responses
**201**
the created terms of payment
**default**
Error information if the request did not succeed
post/3/termsofpayments
Default server
https://api.fortnox.se/3/termsofpayments
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "TermsOfPayment": {
    * "@url": "string",
    * "Code": "string",
    * "Description": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_TermsOfPayments/operation/remove_22)Remove a term of payment 
##### path Parameters
Coderequired| string identifies the terms of payment  
---|---  
### Responses
**204**
Successfully removed the specified resource.
**default**
Error information if the request did not succeed
delete/3/termsofpayments/{Code}
Default server
https://api.fortnox.se/3/termsofpayments/{Code}
###  Response samples 
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ErrorInformation": {
    * "Code": 0,
    * "Error": 0,
    * "Message": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_TermsOfPayments/operation/get_52)Retrieve a single terms of payment 
##### path Parameters
Coderequired| string identifies the terms of payment  
---|---  
### Responses
**200**
the existing terms of payment
**default**
Error information if the request did not succeed
get/3/termsofpayments/{Code}
Default server
https://api.fortnox.se/3/termsofpayments/{Code}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "TermsOfPayment": {
    * "@url": "string",
    * "Code": "string",
    * "Description": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_TermsOfPayments/operation/update_41)Update a term of payment 
##### path Parameters
Coderequired| string identifies the term of payment  
---|---  
##### Request Body schema: */*
term of payment to update
TermsOfPaymentrequired| object (fortnox_TermsOfPayment)   
---|---  
### Responses
**200**
the updated term of payment
**default**
Error information if the request did not succeed
put/3/termsofpayments/{Code}
Default server
https://api.fortnox.se/3/termsofpayments/{Code}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "TermsOfPayment": {
    * "@url": "string",
    * "Code": "string",
    * "Description": "string"
}

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_TrustedEmailSenders)Trusted Email Senders
Resource for the CRUD operations on trusted email senders
## [](https://api.fortnox.se/apidocs#tag/fortnox_TrustedEmailSenders/operation/get_53)Retrieve a list of all trusted and rejected senders 
### Responses
**200**
all trusted and rejected email senders
**default**
Error information if the request did not succeed
get/3/emailsenders
Default server
https://api.fortnox.se/3/emailsenders
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "EmailSenders": {
    * "RejectedSenders": [
      * {
        * "Email": "string",
        * "Id": 0
}
],
    * "TrustedSenders": [
      * {
        * "Email": "string",
        * "Id": 0
}
]
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_TrustedEmailSenders/operation/create_44)Add a new email address as trusted 
##### Request Body schema: */*
trusted email sender to create
TrustedSender| object (fortnox_TrustedEmailSender_TrustedSender)   
---|---  
### Responses
**201**
the created trusted email sender
**default**
Error information if the request did not succeed
post/3/emailsenders/trusted
Default server
https://api.fortnox.se/3/emailsenders/trusted
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "TrustedSender": {
    * "Email": "string",
    * "Id": 0
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_TrustedEmailSenders/operation/remove_23)Delete an email address from the trusted senders list 
Provide an id matching an email to delete.
##### path Parameters
Idrequired| integer <int32> identifies the trusted email sender to delete  
---|---  
### Responses
**204**
Successfully removed the specified resource.
**default**
Error information if the request did not succeed
delete/3/emailsenders/trusted/{Id}
Default server
https://api.fortnox.se/3/emailsenders/trusted/{Id}
###  Response samples 
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ErrorInformation": {
    * "Code": 0,
    * "Error": 0,
    * "Message": "string"
}

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_Units)Units
Units resources
## [](https://api.fortnox.se/apidocs#tag/fortnox_Units/operation/list_44)Retrieve a list of units 
The units register can return a list of records or a single record. By specifying a Code in the URL, a single record will be returned. Not specifying a Code will return a list of records.
### Responses
**200**
a list of units.
**default**
Error information if the request did not succeed
get/3/units
Default server
https://api.fortnox.se/3/units
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Units": [
    * {
      * "@url": "string",
      * "Code": "string",
      * "CodeEnglish": "string",
      * "Description": "string"
}
]

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Units/operation/create_45)Create a unit 
##### Request Body schema: */*
to create
Unitrequired| object (fortnox_Unit)   
---|---  
### Responses
**201**
the created unit
**default**
Error information if the request did not succeed
post/3/units
Default server
https://api.fortnox.se/3/units
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Unit": {
    * "@url": "string",
    * "Code": "string",
    * "CodeEnglish": "string",
    * "Description": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Units/operation/remove_24)Remove a unit 
##### path Parameters
Coderequired| string identifies the unit  
---|---  
### Responses
**204**
Successfully removed the specified resource.
**default**
Error information if the request did not succeed
delete/3/units/{Code}
Default server
https://api.fortnox.se/3/units/{Code}
###  Response samples 
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ErrorInformation": {
    * "Code": 0,
    * "Error": 0,
    * "Message": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Units/operation/get_54)Retrieve a single unit 
##### path Parameters
Coderequired| string identifies the unit  
---|---  
### Responses
**200**
the existing unit
**default**
Error information if the request did not succeed
get/3/units/{Code}
Default server
https://api.fortnox.se/3/units/{Code}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Unit": {
    * "@url": "string",
    * "Code": "string",
    * "CodeEnglish": "string",
    * "Description": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Units/operation/update_42)Update a unit 
##### path Parameters
Coderequired| string identifies the unit  
---|---  
##### Request Body schema: */*
unit to update
Unitrequired| object (fortnox_Unit)   
---|---  
### Responses
**200**
the updated unit
**default**
Error information if the request did not succeed
put/3/units/{Code}
Default server
https://api.fortnox.se/3/units/{Code}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Unit": {
    * "@url": "string",
    * "Code": "string",
    * "CodeEnglish": "string",
    * "Description": "string"
}

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_VacationDebtBasis)Vacation Debt Basis
Vacation Debt Basis resources
## [](https://api.fortnox.se/apidocs#tag/fortnox_VacationDebtBasis/operation/get_55)Retrieve a specific vacation debt basis for a posted voucher 
##### path Parameters
Yearrequired| integer <int32>  
---|---  
Monthrequired| integer <int32>  
### Responses
**200**
a created and posted vacation debt basis up until last day of month in year
**default**
Error information if the request did not succeed
get/3/vacationdebtbasis/{Year}/{Month}
Default server
https://api.fortnox.se/3/vacationdebtbasis/{Year}/{Month}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "VacationDebtBasis": {
    * "Employees": [
      * {
        * "DaysEarned": 0.1,
        * "DaysSaved": 0.1,
        * "DaysUnused": 0.1,
        * "DebtAdvance": 0.1,
        * "DebtEarned": 0.1,
        * "DebtSaved": 0.1,
        * "DebtUnused": 0.1,
        * "EmployeeId": "string",
        * "EmployeeName": "string",
        * "TotalDebtEmployee": 0.1,
        * "TotalDebtEmployerContribution": 0.1,
        * "VariableEarned": 0.1,
        * "VariableUnused": 0.1,
        * "WageEarned": 0.1,
        * "WageSaved": 0.1,
        * "WageUnused": 0.1
}
],
    * "LastDay": "2019-08-24",
    * "Month": 0,
    * "VoucherNumber": 0,
    * "VoucherSeries": "string",
    * "VoucherYear": 0,
    * "Year": 0
}

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_VoucherFileConnections)Voucher File Connections
Voucher file connections resources 
Possible search params on Voucher file connections endpoint **Search** | **Description**  
---|---  
voucheryear | Retrives voucher file connections by voucher year  
voucherdescription | Retrives voucher file connections by voucher description  
vouchernumber | Retrives voucher file connections by voucher number  
voucherseries | Retrives voucher file connections by voucher series  
## [](https://api.fortnox.se/apidocs#tag/fortnox_VoucherFileConnections/operation/list_45)Retrieve a list of voucher file connections 
The voucher file connections register can return a list of records or a single record. By specifying a FileId in the URL, a single record will be returned. Not specifying a FileId will return a list of records.
### Responses
**200**
a list of voucher file connections.
**default**
Error information if the request did not succeed
get/3/voucherfileconnections
Default server
https://api.fortnox.se/3/voucherfileconnections
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "VoucherFileConnections": [
    * {
      * "@url": "string",
      * "FileId": "string",
      * "VoucherDescription": "string",
      * "VoucherNumber": "string",
      * "VoucherSeries": "string",
      * "VoucherYear": 0
}
]

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_VoucherFileConnections/operation/create_46)Create a voucher file connection 
##### Request Body schema: */*
to create
VoucherFileConnectionrequired| object (fortnox_VoucherFileConnection)   
---|---  
### Responses
**201**
the created voucher file connection
**default**
Error information if the request did not succeed
post/3/voucherfileconnections
Default server
https://api.fortnox.se/3/voucherfileconnections
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "VoucherFileConnection": {
    * "@url": "string",
    * "FileId": "string",
    * "VoucherDescription": "string",
    * "VoucherNumber": "string",
    * "VoucherSeries": "string",
    * "VoucherYear": 0
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_VoucherFileConnections/operation/remove_25)Remove a voucher file connection 
##### path Parameters
FileIdrequired| string identifies the voucher file connection  
---|---  
### Responses
**204**
Successfully removed the specified resource.
**default**
Error information if the request did not succeed
delete/3/voucherfileconnections/{FileId}
Default server
https://api.fortnox.se/3/voucherfileconnections/{FileId}
###  Response samples 
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ErrorInformation": {
    * "Code": 0,
    * "Error": 0,
    * "Message": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_VoucherFileConnections/operation/get_56)Retrieve a single voucher file connection 
##### path Parameters
FileIdrequired| string identifies the voucher file connection  
---|---  
### Responses
**200**
the existing voucher file connection
**default**
Error information if the request did not succeed
get/3/voucherfileconnections/{FileId}
Default server
https://api.fortnox.se/3/voucherfileconnections/{FileId}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "VoucherFileConnection": {
    * "@url": "string",
    * "FileId": "string",
    * "VoucherDescription": "string",
    * "VoucherNumber": "string",
    * "VoucherSeries": "string",
    * "VoucherYear": 0
}

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_VoucherSeries)Voucher Series
Voucher Series resources 
Possible search params on Voucher Series endpoint **Search** | **Description**  
---|---  
lastmodified | Retrives Voucher Series modified after provided date and time  
Possible sort params on Voucher Series endpoint **Sort** | **Description**  
---|---  
code | Sorts Voucher Series according to code  
## [](https://api.fortnox.se/apidocs#tag/fortnox_VoucherSeries/operation/list_47)Retrieve a list of voucher series 
The voucher series register can return a list of records or a single record. By specifying a Code in the URL, a single record will be returned. Not specifying a Code will return a list of records.
### Responses
**200**
a list of voucher series.
**default**
Error information if the request did not succeed
get/3/voucherseries
Default server
https://api.fortnox.se/3/voucherseries
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "VoucherSeriesCollection": [
    * {
      * "@url": "string",
      * "Approver": {
        * "Id": 0,
        * "Name": "string"
},
      * "Code": "string",
      * "Description": "string",
      * "Manual": true,
      * "Year": 0
}
]

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_VoucherSeries/operation/create_48)Create a voucher series 
##### Request Body schema: */*
to create
VoucherSeriesrequired| object (fortnox_VoucherSeries)   
---|---  
### Responses
**201**
the created voucher series
**default**
Error information if the request did not succeed
post/3/voucherseries
Default server
https://api.fortnox.se/3/voucherseries
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "VoucherSeries": {
    * "@url": "string",
    * "Approver": {
      * "Id": 0,
      * "Name": "string"
},
    * "Code": "string",
    * "Description": "string",
    * "Manual": true,
    * "NextVoucherNumber": 0,
    * "Year": 0
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_VoucherSeries/operation/get_58)Retrieve a single voucher series 
##### path Parameters
Coderequired| string identifies the voucher series  
---|---  
### Responses
**200**
the existing voucher series
**default**
Error information if the request did not succeed
get/3/voucherseries/{Code}
Default server
https://api.fortnox.se/3/voucherseries/{Code}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "VoucherSeries": {
    * "@url": "string",
    * "Approver": {
      * "Id": 0,
      * "Name": "string"
},
    * "Code": "string",
    * "Description": "string",
    * "Manual": true,
    * "NextVoucherNumber": 0,
    * "Year": 0
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_VoucherSeries/operation/update_43)Update a voucher series 
##### path Parameters
Coderequired| string identifies the voucher series  
---|---  
##### Request Body schema: */*
to update
VoucherSeriesrequired| object (fortnox_VoucherSeries)   
---|---  
### Responses
**200**
the updated voucher series
**default**
Error information if the request did not succeed
put/3/voucherseries/{Code}
Default server
https://api.fortnox.se/3/voucherseries/{Code}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "VoucherSeries": {
    * "@url": "string",
    * "Approver": {
      * "Id": 0,
      * "Name": "string"
},
    * "Code": "string",
    * "Description": "string",
    * "Manual": true,
    * "NextVoucherNumber": 0,
    * "Year": 0
}

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_Vouchers)Vouchers
Voucher resources 
Possible search params on Vouchers endpoint **Search** | **Description**  
---|---  
lastmodified | Retrives Vouchers modified after provided date and time  
costcenter | Retrives Vouchers by costcenter  
fromdate | Retrives Vouchers starting from provided date  
todate | Retrives Vouchers until provided date todate  
voucherseries | Retrives Vouchers by Voucher Series  
Possible sort params on Vouchers endpoint **Sort** | **Description**  
---|---  
referencenumber | Sorts vouchers according to referencenumber  
referencetype | Sorts vouchers according to referencetype  
vouchernumber | Sorts vouchers according to vouchernumber  
voucherseries | Sorts vouchers according to voucherseries  
## [](https://api.fortnox.se/apidocs#tag/fortnox_Vouchers/operation/list_46)Retrieve all vouchers 
Note that vouchers have two keys, one for voucher series and one for voucher number. The financial year is also specified for each voucher, this is due to the same voucher series and number is used each year. To get a unique voucher you need the voucher series, the voucher number and the financial year. These properties will always be returned where ever vouchers is used.
##### query Parameters
financialyear| integer <int32> filter on financial year  
---|---  
### Responses
**200**
list of vouchers
**default**
Error information if the request did not succeed
get/3/vouchers
Default server
https://api.fortnox.se/3/vouchers
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Vouchers": [
    * {
      * "@url": "string",
      * "ApprovalState": 0,
      * "Comments": "string",
      * "Description": "string",
      * "ReferenceNumber": "string",
      * "ReferenceType": "INVOICE",
      * "TransactionDate": "2019-08-24",
      * "VoucherNumber": 0,
      * "VoucherSeries": "string",
      * "Year": 0
}
]

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Vouchers/operation/create_47)Create a voucher 
The created voucher will be returned if everything succeeded, if there was any problems an error will be returned. If no query param is used the voucher will be created in the preselected financial year. Go to the financialyears endpoint to read on how to retreive the Financial year id.
##### query Parameters
financialyear| integer <int32> Financial year id, used to determine which financial year the voucher is created in  
---|---  
##### Request Body schema: */*
voucher to create
Voucher| object (fortnox_Voucher)   
---|---  
### Responses
**201**
the created voucher
**default**
Error information if the request did not succeed
post/3/vouchers
Default server
https://api.fortnox.se/3/vouchers
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Voucher": {
    * "@url": "string",
    * "ApprovalState": 0,
    * "Comments": "string",
    * "CostCenter": "string",
    * "Description": "string",
    * "Project": "string",
    * "ReferenceNumber": "string",
    * "ReferenceType": "INVOICE",
    * "TransactionDate": "2019-08-24",
    * "VoucherNumber": 0,
    * "VoucherRows": [
      * {
        * "Account": 1000,
        * "CostCenter": "string",
        * "Credit": 0.1,
        * "Debit": 0.1,
        * "Description": "string",
        * "Project": "string",
        * "Quantity": 0.1,
        * "Removed": true,
        * "TransactionInformation": "string"
},
      * {
        * "Account": 1000,
        * "CostCenter": "string",
        * "Credit": 0.1,
        * "Debit": 0.1,
        * "Description": "string",
        * "Project": "string",
        * "Quantity": 0.1,
        * "Removed": true,
        * "TransactionInformation": "string"
}
],
    * "VoucherSeries": "string",
    * "Year": 0
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Vouchers/operation/listVouchers)Retrieve all vouchers for the current financial year 
### Responses
**200**
list of vouchers
**default**
Error information if the request did not succeed
get/3/vouchers/sublist
Default server
https://api.fortnox.se/3/vouchers/sublist
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Vouchers": [
    * {
      * "@url": "string",
      * "ApprovalState": 0,
      * "Comments": "string",
      * "Description": "string",
      * "ReferenceNumber": "string",
      * "ReferenceType": "INVOICE",
      * "TransactionDate": "2019-08-24",
      * "VoucherNumber": 0,
      * "VoucherSeries": "string",
      * "Year": 0
}
]

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Vouchers/operation/listSeries)Retrieve a list of vouchers for a specific series 
##### path Parameters
VoucherSeriesrequired| string identifies the voucher series  
---|---  
##### query Parameters
financialyear| integer <int32> filter on financial year  
---|---  
### Responses
**200**
list of vouchers
**default**
Error information if the request did not succeed
get/3/vouchers/sublist/{VoucherSeries}
Default server
https://api.fortnox.se/3/vouchers/sublist/{VoucherSeries}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Vouchers": [
    * {
      * "@url": "string",
      * "ApprovalState": 0,
      * "Comments": "string",
      * "Description": "string",
      * "ReferenceNumber": "string",
      * "ReferenceType": "INVOICE",
      * "TransactionDate": "2019-08-24",
      * "VoucherNumber": 0,
      * "VoucherSeries": "string",
      * "Year": 0
}
]

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_Vouchers/operation/get_57)Retrieve a specific voucher 
##### path Parameters
VoucherSeriesrequired| string identifies the voucher series  
---|---  
VoucherNumberrequired| integer <int32> identifies the voucher number  
##### query Parameters
financialyear| integer <int32> filter on financial year  
---|---  
### Responses
**200**
a single voucher
**default**
Error information if the request did not succeed
get/3/vouchers/{VoucherSeries}/{VoucherNumber}
Default server
https://api.fortnox.se/3/vouchers/{VoucherSeries}/{VoucherNumber}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "Voucher": {
    * "@url": "string",
    * "ApprovalState": 0,
    * "Comments": "string",
    * "CostCenter": "string",
    * "Description": "string",
    * "Project": "string",
    * "ReferenceNumber": "string",
    * "ReferenceType": "INVOICE",
    * "TransactionDate": "2019-08-24",
    * "VoucherNumber": 0,
    * "VoucherRows": [
      * {
        * "Account": 1000,
        * "CostCenter": "string",
        * "Credit": 0.1,
        * "Debit": 0.1,
        * "Description": "string",
        * "Project": "string",
        * "Quantity": 0.1,
        * "Removed": true,
        * "TransactionInformation": "string"
},
      * {
        * "Account": 1000,
        * "CostCenter": "string",
        * "Credit": 0.1,
        * "Debit": 0.1,
        * "Description": "string",
        * "Project": "string",
        * "Quantity": 0.1,
        * "Removed": true,
        * "TransactionInformation": "string"
}
],
    * "VoucherSeries": "string",
    * "Year": 0
}

}`
# [](https://api.fortnox.se/apidocs#tag/fortnox_WayOfDeliveries)Way Of Deliveries
Resource for CRUD operations on Way of Deliveries
## [](https://api.fortnox.se/apidocs#tag/fortnox_WayOfDeliveries/operation/list_48)Retrieve a list of way of deliveries 
The way of delivery register can return a list of records or a single record. By specifying a Code in the URL, a single record will be returned. Not specifying a Code will return a list of records.
### Responses
**200**
a list of way of deliveries
**default**
Error information if the request did not succeed
get/3/wayofdeliveries
Default server
https://api.fortnox.se/3/wayofdeliveries
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "WayOfDeliveries": [
    * {
      * "@url": "string",
      * "Code": "string",
      * "Description": "string",
      * "DescriptionEnglish": "string"
}
]

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_WayOfDeliveries/operation/create_49)Create a way of delivery 
##### Request Body schema: */*
way of delivery to create
WayOfDelivery| object (fortnox_WayOfDelivery)   
---|---  
### Responses
**201**
the created way of delivery
**default**
Error information if the request did not succeed
post/3/wayofdeliveries
Default server
https://api.fortnox.se/3/wayofdeliveries
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "WayOfDelivery": {
    * "@url": "string",
    * "Code": "string",
    * "Description": "string",
    * "DescriptionEnglish": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_WayOfDeliveries/operation/remove_26)Remove a way of delivery 
##### path Parameters
Coderequired| string identifies the way of delivery  
---|---  
### Responses
**204**
Successfully removed the specified resource.
**default**
Error information if the request did not succeed
delete/3/wayofdeliveries/{Code}
Default server
https://api.fortnox.se/3/wayofdeliveries/{Code}
###  Response samples 
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "ErrorInformation": {
    * "Code": 0,
    * "Error": 0,
    * "Message": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_WayOfDeliveries/operation/get_59)Retrieve a single way of delivery 
##### path Parameters
Coderequired| string identifies the way of delivery  
---|---  
### Responses
**200**
the existing way of delivery
**default**
Error information if the request did not succeed
get/3/wayofdeliveries/{Code}
Default server
https://api.fortnox.se/3/wayofdeliveries/{Code}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "WayOfDelivery": {
    * "@url": "string",
    * "Code": "string",
    * "Description": "string",
    * "DescriptionEnglish": "string"
}

}`
## [](https://api.fortnox.se/apidocs#tag/fortnox_WayOfDeliveries/operation/update_44)Update a way of delivery 
##### path Parameters
Coderequired| string identifies the way of delivery  
---|---  
##### Request Body schema: */*
way of delivery to update
WayOfDelivery| object (fortnox_WayOfDelivery)   
---|---  
### Responses
**200**
the updated way of delivery
**default**
Error information if the request did not succeed
put/3/wayofdeliveries/{Code}
Default server
https://api.fortnox.se/3/wayofdeliveries/{Code}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "WayOfDelivery": {
    * "@url": "string",
    * "Code": "string",
    * "Description": "string",
    * "DescriptionEnglish": "string"
}

}`
# [](https://api.fortnox.se/apidocs#tag/fileattachments_Attachment)Attachment
AttachmentResource
Attach/Detach files to entities.
Possible 400 response error codes: no_attachment_provided, mixed_documents, wrong_file_location, wrong_file_type, could_not_retrieve_document, file_too_big, too_many_attachments_in_one_request, max_total_attachments_exceeded, attachment_files_max_count_exceeded, attachment_files_max_size_exceeded, attachment_files_max_pages_exceeded, field_not_writable, mismatch_attachment_id, missing_mandatory_field
Possible 404 response error codes: file_not_found, document_not_found, attachment_not_found
## [](https://api.fortnox.se/apidocs#tag/fileattachments_Attachment/operation/getAttachments)Get attached files on an entity 
##### query Parameters
entityidrequired| Array of integers <int64> [ items <int64 > ] ids of the entities whose attachments should be fetched  
---|---  
entitytyperequired| string Enum: "OF" "O" "F" "C" "LGR_IO" "LGR_IG" type of the entities whose attachments should be fetched  
### Responses
**200**
A list of attachments
**default**
WebException
get/api/fileattachments/attachments-v1
Default server
https://api.fortnox.se/api/fileattachments/attachments-v1
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
`{
  * "entityId": 0,
  * "entityType": "OF",
  * "fileId": "string",
  * "id": "497f6eca-6276-4993-bfeb-53cbbbba6f08",
  * "includeOnSend": true

}`
## [](https://api.fortnox.se/apidocs#tag/fileattachments_Attachment/operation/attach)Attach files to one or more entities 
##### Request Body schema: */*
A list of attachments
Array 
entityId| integer <int64>  
---|---  
entityType| string Enum: "OF" "O" "F" "C" "LGR_IO" "LGR_IG"  
fileId| string  
id| string <uuid>  
includeOnSend| boolean  
### Responses
**201**
A list of attachments
**default**
WebException
post/api/fileattachments/attachments-v1
Default server
https://api.fortnox.se/api/fileattachments/attachments-v1
###  Response samples 
  * 201
  * default


Content type
application/json
Copy
`{
  * "entityId": 0,
  * "entityType": "OF",
  * "fileId": "string",
  * "id": "497f6eca-6276-4993-bfeb-53cbbbba6f08",
  * "includeOnSend": true

}`
## [](https://api.fortnox.se/apidocs#tag/fileattachments_Attachment/operation/getNumberOfAttachmentsForEntity)List number of attachments 
##### query Parameters
entityidsrequired| Array of integers <int64> [ items <int64 > ] ids of the entities to look for number of attachments on  
---|---  
entitytyperequired| string Enum: "OF" "O" "F" "C" "LGR_IO" "LGR_IG" type of the entities to look for number of attachments on  
### Responses
**200**
A list of the number of attachments on each entity
**default**
WebException
get/api/fileattachments/attachments-v1/numberofattachments
Default server
https://api.fortnox.se/api/fileattachments/attachments-v1/numberofattachments
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
`{
  * "entityId": 0,
  * "numberOfAttachments": 0

}`
## [](https://api.fortnox.se/apidocs#tag/fileattachments_Attachment/operation/validateIncludedOnSend)Validates a list of attachments that will be included on send 
##### Request Body schema: */*
a list of Attachments
Array 
entityId| integer <int64>  
---|---  
entityType| string Enum: "OF" "O" "F" "C" "LGR_IO" "LGR_IG"  
fileId| string  
id| string <uuid>  
includeOnSend| boolean  
### Responses
**204**
Successfully created a new resource.
**default**
WebException
post/api/fileattachments/attachments-v1/validateincludedonsend
Default server
https://api.fortnox.se/api/fileattachments/attachments-v1/validateincludedonsend
###  Response samples 
  * default


Content type
application/json
Copy
`{
  * "error": "string",
  * "id": "string",
  * "message": "string"

}`
## [](https://api.fortnox.se/apidocs#tag/fileattachments_Attachment/operation/detach)Detach file 
##### path Parameters
attachmentIdrequired| string <uuid> id of the attachment to be detached  
---|---  
### Responses
**204**
Successfully removed the specified resource.
**default**
WebException
delete/api/fileattachments/attachments-v1/{attachmentId}
Default server
https://api.fortnox.se/api/fileattachments/attachments-v1/{attachmentId}
###  Response samples 
  * default


Content type
application/json
Copy
`{
  * "error": "string",
  * "id": "string",
  * "message": "string"

}`
## [](https://api.fortnox.se/apidocs#tag/fileattachments_Attachment/operation/updateAttachment)Update attachment 
##### path Parameters
attachmentIdrequired| string <uuid> id of the attachment to be updated  
---|---  
##### Request Body schema: */*
an attachment
entityId| integer <int64>  
---|---  
entityType| string Enum: "OF" "O" "F" "C" "LGR_IO" "LGR_IG"  
fileId| string  
id| string <uuid>  
includeOnSend| boolean  
### Responses
**200**
The updated attachment
**default**
WebException
put/api/fileattachments/attachments-v1/{attachmentId}
Default server
https://api.fortnox.se/api/fileattachments/attachments-v1/{attachmentId}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
`{
  * "entityId": 0,
  * "entityType": "OF",
  * "fileId": "string",
  * "id": "497f6eca-6276-4993-bfeb-53cbbbba6f08",
  * "includeOnSend": true

}`
# [](https://api.fortnox.se/apidocs#tag/integration-developer_Integration-Ratings)Integration Ratings
Get ratings data 
## [](https://api.fortnox.se/apidocs#tag/integration-developer_Integration-Ratings/operation/listRatings)List rating and reviews for integrations that you own 
### Responses
**200**
list of ratings
**default**
WebException
get/api/integration-developer/ratings-v1
Default server
https://api.fortnox.se/api/integration-developer/ratings-v1
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`[
  * {
    * "comment": "string",
    * "companyEmployeeRange": "string",
    * "created": "2019-08-24T14:15:22Z",
    * "integrationId": 0,
    * "isMyRating": true,
    * "rating": 0,
    * "ratingId": 0,
    * "response": {
      * "comment": "string",
      * "created": "2019-08-24T14:15:22Z",
      * "updated": "2019-08-24T14:15:22Z"
},
    * "updated": "2019-08-24T14:15:22Z"
}

]`
# [](https://api.fortnox.se/apidocs#tag/integration-partner_Integration-Sales)Integration Sales
Get sales data from your integrations
## [](https://api.fortnox.se/apidocs#tag/integration-partner_Integration-Sales/operation/getAppSalesForSingleApp)Resolves sales information and active users of an integration 
### Prerequisites
The partner has an active developer account and a published integration that is purchased through Fortnox.
##### path Parameters
appIdrequired| string clientId of the integration to look up sales information for  
---|---  
### Responses
**200**
a `AppSalesResponse`
**default**
WebException
get/api/integration-partner/apps/sales-v1/{appId}
Default server
https://api.fortnox.se/api/integration-partner/apps/sales-v1/{appId}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "appId": "string",
  * "tenants": [
    * {
      * "purchases": [
        * {
          * "amount": 0,
          * "identifier": "string",
          * "purchaseTime": { }
}
],
      * "tenantId": "string",
      * "terminations": [
        * {
          * "amount": 0,
          * "identifier": "string",
          * "onCancellationTime": { }
}
],
      * "users": [
        * {
          * "activationTime": { },
          * "email": "string",
          * "externalSourceId": "string",
          * "name": "string",
          * "userType": "string"
}
]
}
]

}`
## [](https://api.fortnox.se/apidocs#tag/integration-partner_Integration-Sales/operation/getAppSalesForSingleAppAndTenant)Resolves sales information and active users of an integration 
### Prerequisites
The partner has an active developer account and a published integration that is purchased through Fortnox.
##### path Parameters
appIdrequired| string clientId of the integration to look up sales information for  
---|---  
tenantIdrequired| integer <int64> tenantId of the tenant to look up sales information for  
### Responses
**200**
a `AppSalesResponse`
**default**
WebException
get/api/integration-partner/apps/sales-v1/{appId}/{tenantId}
Default server
https://api.fortnox.se/api/integration-partner/apps/sales-v1/{appId}/{tenantId}
###  Response samples 
  * 200
  * default


Content type
application/json
Copy
Expand all  Collapse all 
`{
  * "appId": "string",
  * "tenants": [
    * {
      * "purchases": [
        * {
          * "amount": 0,
          * "identifier": "string",
          * "purchaseTime": { }
}
],
      * "tenantId": "string",
      * "terminations": [
        * {
          * "amount": 0,
          * "identifier": "string",
          * "onCancellationTime": { }
}
],
      * "users": [
        * {
          * "activationTime": { },
          * "email": "string",
          * "externalSourceId": "string",
          * "name": "string",
          * "userType": "string"
}
]
}
]

}`
