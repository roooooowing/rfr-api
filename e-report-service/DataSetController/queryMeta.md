# queryMeta

### Method description

```
数据集元数据
```

> URL: http://localhost:8080/web/v1/data_set/dataset/query_meta
>
> Origin Url: http://localhost:8080/web/v1/data_set/dataset/query_meta
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
  "dataSetId": 1736757383996501,
  "genMode": 3
}
```

###### JSON document

```
{
	"dataSetId":"数据集ID",
	"genMode":"数据集生成方式"
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
  "code": 0,
  "data": "default backend - 404",
  "subCode": "E-REPORT-DOMAIN-LOCAL/FEIGN_EX",
  "message": "[404 Not Found] during [POST] to [http://api-adapter-feature.test.blacklake.tech/api/v1/route/_exec] [RouteApi#execRouteIntegrationInterface(ExecRouteCO)]: [default backend - 404]",
  "needCheck": 0
}
```

##### Response document
```
{
	"code":"状态码",
	"data":{
		"dataSetId":"数据集ID",
		"fields":[
			{
				"fieldName":"字段名称",
				"fieldCode":"字段编号",
				"fieldType":"字段类型"
			}
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


