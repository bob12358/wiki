### 1. DELETE /api/tribe/member/:memberId

#### Description
delete user from tribe
#### Resource
 > Please look forward to ☺

#### Authorization
must have user's session info,user must be login

#### Path Parameters
|Name|Type|Description| 
|----|---|---|
| memberId |number| id of user who deleted by tribe manager| 

#### DELETE Parameters
|Name|Type|Description| 
|----|---|---|
| tribeId |number| tribeId.|

#### Response
Status-code: 200 OK

```json

{   
    code:200,
    msg:'ok',
    data:{}
}
```
 