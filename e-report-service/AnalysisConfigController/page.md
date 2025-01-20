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
  "page":2,
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
	"page":"请求页",
	"selectFlag":"筛选标识 1 全选 0 不全选 默认为 0"
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
        "anaId": 1736831462473803,
        "code": "ana_1736853253043",
        "name": "t3告警",
        "status": 0,
        "dataSetId": 1715292670106286,
        "dataSetName": "testjt",
        "createdAt": 1736853253000,
        "updatedAt": 1736853253000,
        "action": null,
        "execType": null
      },
      {
        "anaId": 1,
        "code": "ana_1736843818725",
        "name": "t1告警",
        "status": 0,
        "dataSetId": 1715292670106286,
        "dataSetName": "testjt",
        "createdAt": 1736843819000,
        "updatedAt": 1736843819000,
        "action": null,
        "execType": null
      },
      {
        "anaId": 1736825194566001,
        "code": "ana_1736825194738",
        "name": "name_20250114_112634",
        "status": 0,
        "dataSetId": 1709767623185359,
        "dataSetName": "筛选3",
        "createdAt": 1736825195000,
        "updatedAt": 1736825195000,
        "action": null,
        "execType": null
      },
      {
        "anaId": 1736577089298009,
        "code": "ana_1736577428956",
        "name": "name_20250111_143708",
        "status": 0,
        "dataSetId": 1709767623185359,
        "dataSetName": "筛选3",
        "createdAt": 1736577429000,
        "updatedAt": 1736577429000,
        "action": null,
        "execType": null
      },
      {
        "anaId": 1736577089298005,
        "code": "ana_1736577128138",
        "name": "name_20250111_143208",
        "status": 0,
        "dataSetId": 1705434537871008,
        "dataSetName": "m117预置数据集01",
        "createdAt": 1736577128000,
        "updatedAt": 1736577128000,
        "action": null,
        "execType": null
      },
      {
        "anaId": 1736577089298001,
        "code": "ana_1736577089733",
        "name": "name_20250111_143128",
        "status": 0,
        "dataSetId": 1,
        "dataSetName": null,
        "createdAt": 1736577099000,
        "updatedAt": 1736577099000,
        "action": null,
        "execType": null
      },
      {
        "anaId": 1736500767105001,
        "code": "ana_1736500767322",
        "name": "name_20250110_171926",
        "status": 0,
        "dataSetId": 111,
        "dataSetName": null,
        "createdAt": 1736500774000,
        "updatedAt": 1736500774000,
        "action": null,
        "execType": null
      },
      {
        "anaId": 1736499670438011,
        "code": null,
        "name": "name_20250110_171806",
        "status": 0,
        "dataSetId": 111,
        "dataSetName": null,
        "createdAt": 1736500686000,
        "updatedAt": 1736500686000,
        "action": null,
        "execType": null
      },
      {
        "anaId": 1736499670438006,
        "code": null,
        "name": "name_20250110_171701",
        "status": 0,
        "dataSetId": 111,
        "dataSetName": null,
        "createdAt": 1736500622000,
        "updatedAt": 1736500622000,
        "action": null,
        "execType": null
      },
      {
        "anaId": 1736496691049001,
        "code": "999",
        "name": "999",
        "status": 1,
        "dataSetId": 111,
        "dataSetName": null,
        "createdAt": 1736496691000,
        "updatedAt": 1736498038000,
        "action": null,
        "execType": null
      },
      {
        "anaId": 1736479404878017,
        "code": "code_20250110_135314",
        "name": "name_20250110_135314",
        "status": null,
        "dataSetId": 111,
        "dataSetName": null,
        "createdAt": 1736488401000,
        "updatedAt": 1736488401000,
        "action": null,
        "execType": null
      },
      {
        "anaId": 1736479404878014,
        "code": "code_20250110_135248",
        "name": "name_20250110_135248",
        "status": null,
        "dataSetId": 111,
        "dataSetName": null,
        "createdAt": 1736488374000,
        "updatedAt": 1736488374000,
        "action": null,
        "execType": null
      },
      {
        "anaId": 1736479404878011,
        "code": "code_20250110_135222",
        "name": "name_20250110_135222",
        "status": null,
        "dataSetId": 111,
        "dataSetName": null,
        "createdAt": 1736488342000,
        "updatedAt": 1736488342000,
        "action": null,
        "execType": null
      },
      {
        "anaId": 1736479404878008,
        "code": "code_20250110_135156",
        "name": "name_20250110_135156",
        "status": null,
        "dataSetId": 111,
        "dataSetName": null,
        "createdAt": 1736488316000,
        "updatedAt": 1736488316000,
        "action": null,
        "execType": null
      },
      {
        "anaId": 1736422070764036,
        "code": "code",
        "name": "name_20250109_201021",
        "status": null,
        "dataSetId": 111,
        "dataSetName": null,
        "createdAt": 1736424628000,
        "updatedAt": 1736424628000,
        "action": null,
        "execType": null
      },
      {
        "anaId": 1736422070764033,
        "code": "code_20250109_200945",
        "name": "name_20250109_200945",
        "status": null,
        "dataSetId": 111,
        "dataSetName": null,
        "createdAt": 1736424595000,
        "updatedAt": 1736424595000,
        "action": null,
        "execType": null
      },
      {
        "anaId": 1736422070764030,
        "code": "code_20250109_200923",
        "name": "name_20250109_200923",
        "status": null,
        "dataSetId": 111,
        "dataSetName": null,
        "createdAt": 1736424572000,
        "updatedAt": 1736424572000,
        "action": null,
        "execType": null
      },
      {
        "anaId": 1736422070764025,
        "code": "code_{{$currentDateTime}}",
        "name": "name_{{$currentDateTime}}",
        "status": null,
        "dataSetId": 111,
        "dataSetName": null,
        "createdAt": 1736422818000,
        "updatedAt": 1736422818000,
        "action": null,
        "execType": null
      },
      {
        "anaId": 1736422070764022,
        "code": "code_20250109_193441",
        "name": "name_20250109_193441",
        "status": null,
        "dataSetId": 111,
        "dataSetName": null,
        "createdAt": 1736422741000,
        "updatedAt": 1736422741000,
        "action": null,
        "execType": null
      },
      {
        "anaId": 1736422070764019,
        "code": "code_20250109_193146",
        "name": "name_20250109_193146",
        "status": null,
        "dataSetId": 111,
        "dataSetName": null,
        "createdAt": 1736422332000,
        "updatedAt": 1736422332000,
        "action": null,
        "execType": null
      }
    ],
    "page": 1,
    "total": 42
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


