# detail

### Method description

```
详情
```

> URL: http://localhost:8080/api/v1/analysis/config/detail
>
> Origin Url: http://localhost:8080/api/v1/analysis/config/detail
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
  "anaId": 1736825194566001
}
```

###### JSON document

```
{
	"anaId":"分析告警ID"
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
    "anaId": 1736825194566001
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
	"data":{
		"baseInfo":{
			"code":"编号",
			"dataSetId":"数据集ID",
			"anaId":"ID",
			"name":"名称",
			"status":"状态 0-未启用 1-启用"
		},
		"actions":[
			"触发动作"
		]
	},
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


