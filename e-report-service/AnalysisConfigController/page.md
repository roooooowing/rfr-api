# page

### Method description

```
列表筛选
```

> URL: http://localhost:8080/web/v1/analysis/config/page
>
> Origin Url: http://localhost:8080/web/v1/analysis/config/page
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
  "execType": 1,
  "page": 1,
  "size": 20
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
    "list": [
      {
        "anaId": 1737353310593557,
        "code": "ana_1737373434494",
        "name": "测试_mfg_001",
        "status": 1,
        "dataSetId": 1737353008467251,
        "dataSetName": "简单测试_MFG",
        "createdAt": 1737373434000,
        "updatedAt": 1737373499000,
        "action": 1,
        "execType": 1
      },
      {
        "anaId": 1737345649996883,
        "code": "ana_1737365490978",
        "name": "测试_生产主题_001",
        "status": 0,
        "dataSetId": 1704652503876731,
        "dataSetName": "测试生产主题",
        "createdAt": 1737365491000,
        "updatedAt": 1737373438000,
        "execType": 1
      },
      {
        "anaId": 1736831462473803,
        "code": "ana_1736853253043",
        "name": "t3告警",
        "status": 0,
        "dataSetId": 1715292670106286,
        "dataSetName": "testjt",
        "createdAt": 1736853253000,
        "updatedAt": 1736853253000
      },
      {
        "anaId": 1,
        "code": "ana_1736843818725",
        "name": "t1告警",
        "status": 0,
        "dataSetId": 1715292670106286,
        "dataSetName": "testjt",
        "createdAt": 1736843819000,
        "updatedAt": 1736843819000
      },
      {
        "anaId": 1736825194566001,
        "code": "ana_1736825194738",
        "name": "name_20250114_112634",
        "status": 0,
        "dataSetId": 1709767623185359,
        "dataSetName": "筛选3",
        "createdAt": 1736825195000,
        "updatedAt": 1736825195000
      },
      {
        "anaId": 1736577089298009,
        "code": "ana_1736577428956",
        "name": "name_20250111_143708",
        "status": 0,
        "dataSetId": 1709767623185359,
        "dataSetName": "筛选3",
        "createdAt": 1736577429000,
        "updatedAt": 1736577429000
      },
      {
        "anaId": 1736577089298005,
        "code": "ana_1736577128138",
        "name": "name_20250111_143208",
        "status": 0,
        "dataSetId": 1705434537871008,
        "dataSetName": "m117预置数据集01",
        "createdAt": 1736577128000,
        "updatedAt": 1736577128000
      }
    ],
    "page": 1,
    "total": 7
  },
  "message": "成功"
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


