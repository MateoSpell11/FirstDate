<p align="center">
  <a href="https://docsify.js.org">
  </a>
</p>

<p align="center">
    DOCUMENTATION
</p>

<p align="center">
  <a href="https://opencollective.com/docsify/order/3254">
  </a>
</p>

## Get /Clear Cache

>Admin method true
>Auth true 

### response
```shell
    {
      "status": "success",
      "data": {
      }
    }
```
## POST /Change Credentials
>Admin method true
>Auth true 
### Body
```shell
    {
    "userEmail": "logan1@corporatealliance.net.sbx1"
    }
```
### Response
```shell
    {
      "status": "success",
      "data": {
      }
    }
```

## GET /Clear-Cache

>Admin method true
>Auth true 
### response
```shell
    {
      "status": "success",
      "data": {
      }
    }
```

## GET /clear-cache
> Admin auth: true
> Auth: true
### Response 
```shell
{"status":"success","data":{}}
```
## GET /testConnection
> Admin auth: true
> Auth: true
### Response 
```shell
{"status":"success","data":{"status":"SUCCESS OR FAILURE"}}
```
## GET /sfdc/sync/roles
> Admin auth: true
> Auth: true
### Response 
```shell
{"status":"success","data":{"result":"success"}}
```
## GET /sfdc/sync/profiles
> Admin auth: true
> Auth: true
### Response 
```shell
{"status":"success","data":{"result":"success"}}
```
## GET /sfdc/sync/objects
> Admin auth: true
> Auth: true
### Response 
```shell
{"status":"success","data":{}}
```
## POST /sfdc/sync/activate
> Admin auth: true
> Auth: true
### Body 
```shell
{"records":[{"Describe__c":"optional","LastModifiedDate__c":"optional","key__c":"required","IsActive__c":false}]}
```
### Response 
```shell
{"status":"success","data":{"describes":[{}]}}
```
## POST /sfdc/sync/ingest-token
> Admin auth: true
> Auth: true
### Body 
```shell
{"url":"required:: https://ingest.trackland.com"}
```
### Response 
```shell
{"status":"success","data":{}}
```
## POST /sfdc/sync/credential
> Admin auth: true
> Auth: true
### Body 
```shell
{"records":[[{"tlnd__AuthType__c":"required","tlnd__URL__c":"required","tlnd__Token__c":"required","tlnd__Active__c":false,"DevelperName":"required","MasterLabel":"required"}]]}
```
### Response 
```shell
{"status":"success","data":{}}
```
## POST /sfdc/sync/start-sync
> Admin auth: true
> Auth: true
### Body 
```shell
{}
```
### Response 
```shell
{"status":"success","data":{}}
```
## POST /sfdc/sync/records
> Admin auth: true
> Auth: true
### Body 
```shell
{"objectType":"required"}
```
### Response 
```shell
{"status":"success","data":{"TLItem":{}}}
```
## POST /sfdc/sync/changeCredentials
> Admin auth: true
> Auth: true
### Body 
```shell
{"userEmail":"required"}
```
### Response 
```shell
{"status":"success","data":{}}
```
## POST /api/items/post
> Admin auth: false
> Auth: true
### Body 
```shell
{"query":{"type":["required"],"items":[{"atributtes":{"type":"required"}}]}}
```
### Response 
```shell
{"status":"success","data":{}}
```
## POST /api/items/post
> Admin auth: false
> Auth: true
### Body 
```shell
{"query":{"type":["required:: @user"],"items":[{"email":"required","password":"optional","phone":"optional","name":"optional","profile":"required","sfUser":"optional","atributtes":{"type":"required:: @user"}}]}}
```
### Response 
```shell
{"status":"success","data":{}}
```
## POST /api/items/put
> Admin auth: false
> Auth: true
### Body 
```shell
{"query":{"type":["required"],"items":[{"itemId":"required","atributtes":{"type":"required"}}]}}
```
### Response 
```shell
{"status":"success","data":{}}
```
## POST /api/items/put
> Admin auth: false
> Auth: true
### Body 
```shell
{"query":{"type":["required:: @user"],"items":[{"itemId":"required","email":"optional","password":"optional","phone":"optional","name":"optional","profile":"optional","sfUser":"optional","atributtes":{"type":"@user"}}]}}
```
### Response 
```shell
{"status":"success","data":{}}
```
