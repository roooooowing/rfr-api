# page

### Method description

```
列表筛选
```

> URL: http://e-report-domain-feature.test.blacklake.tech/web/v1/analysis/config/page
>
> Origin Url: http://e-report-domain-feature.test.blacklake.tech/web/v1/analysis/config/page
>
> Type: POST


### Request headers

|Header Name| Header Value|
|---------|------|
|x-org-id|10902217|
|x-user-id|-1|

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
  "dataSetIds": [],
  "page": 1,
  "size": 20,
  "execType": [
    2
  ]
}
```

###### JSON document

```
{
	"size":"每页大小",
	"sorter":[
		{
			"field":"排序字段",
			"order":"排序规律 默认 asc，asc 升序 desc 降序"
		}
	],
	"quickSearch":"快速搜索",
	"name":"分析告警名称",
	"dataSetIds":[
		"数据模型"
	],
	"page":"请求页",
	"execType":"执行频率类型：1每日；2每周；3每月；4每年；5固定周期；6自定义；7每小时",
	"actions":[
		"后续动作"
	],
	"selectFlag":"筛选标识 1 全选 0 不全选 默认为 0",
	"status":"运行状态"
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
    "list": [],
    "page": 1,
    "total": 0
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
		"createdAt":"创建时间",
		"code":"编号",
		"dataSetId":"数据集ID",
		"anaId":"ID",
		"dataSetName":"数据集名称",
		"name":"名称",
		"action":"后续动作",
		"execType":"执行频率类型：1每日；2每周；3每月；4每年；5固定周期；6自定义；7每小时",
		"status":"状态 0-未启用 1-启用",
		"updatedAt":"更新时间"
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


