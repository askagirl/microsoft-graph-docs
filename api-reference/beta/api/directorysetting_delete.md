# Delete a directory setting

Delete a directory setting.
### Prerequisites
The following **scopes** are required to execute this API: *Directory.ReadWrite.All* or *Directory.AccessAsUser.All*
### HTTP request
<!-- { "blockType": "ignored" } -->
Delete a specific tenant-wide or group setting
```http
DELETE /settings/<id>
DELETE /groups/<id>/settings/<id>

```
### Request headers
| Name       | Description|
|:---------------|:----------|
| Authorization  | Bearer <token>. Required.|

### Request body
Do not supply a request body for this method.


### Response
If successful, this method returns `204, No Content` response code. It does not return anything in the response body.

### Example
##### Request
Here is an example of the request.
<!-- {
  "blockType": "request",
  "name": "delete_directorysetting"
}-->
```http
DELETE https://graph.microsoft.com/beta/settings/<id>
```
##### Response
Here is an example of the response. Note: The response object shown here may be truncated for brevity. All of the properties will be returned from an actual call.
<!-- {
  "blockType": "response",
  "truncated": true
} -->
```http
HTTP/1.1 204 No Content
```

<!-- uuid: 8fcb5dbc-d5aa-4681-8e31-b001d5168d79
2015-10-25 14:57:30 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "Delete directorySetting",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->