# list

### Method description

```
列表筛选
```

> URL: http://localhost:8080/web/v1/analysis/list
>
> Origin Url: http://localhost:8080/web/v1/analysis/list
>
> Type: POST


### Request headers

|Header Name| Header Value|
|---------|------|
|x-org-id|10902217|
|x-user-id|1650360262949770|

### Parameters

##### Path parameters

| Parameter | Type | Value | Description |
|---------|------|------|------------|


##### URL parameters

|Required| Parameter | Type | Value | Description |
|---------|---------|------|------|------------|


##### Body parameters

###### JSON

```
{
  "quickSearch": "2025"
}
```

###### JSON document

```
{
	"quickSearch":"No comment,Value =quickSearch_59ykp"
}
```


##### Form URL-Encoded
|Required| Parameter | Type | Value | Description |
|---------|---------|------|------|------------|


##### Multipart
|Required | Parameter | Type | Value | Description |
|---------|---------|------|------|------------|


### Response

##### Response example

```
{
  "code": 200,
  "data": {
    "baseInfo": {
      "anaId": 1736496691049001,
      "code": "999",
      "name": "999",
      "status": null,
      "dataSetId": 111
    },
    "condition": null,
    "timeJobConfig": null,
    "actions": [
      1
    ],
    "repeatConfig": {
      "checkFields": [
        "field_1"
      ],
      "checkTimeNum": 1,
      "checkTimeUnit": 3
    }
  },
  "subCode": null,
  "message": "成功",
  "needCheck": null,
  "fieldPermission": null
}
```

##### Response document
```
{
	"code":"状态码",
	"data":{},
	"subCode":"错误码",
	"needCheck":"是否需要二次确认 0 强管控 不需要确认 1 弱管控 需要用户两次确认",
	"message":"返回信息",
	"fieldPermission":{
		"readonly":[
			"No comment,Type =String"
		],
		"noAccess":[
			"No comment,Type =String"
		],
		"encoding":"No comment,Type =String"
	}
}
```


