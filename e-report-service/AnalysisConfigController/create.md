# create

### Method description

```
新建
```

> URL: http://e-report-domain-feature.test.blacklake.tech/web/v1/analysis/config/create
>
> Origin Url: http://e-report-domain-feature.test.blacklake.tech/web/v1/analysis/config/create
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
  "baseInfo": {
    "anaId": 1,
    "name": "t1告警",
    "dataSetId": 1715292670106286
  },
  "actions": [
    1
  ],
  "conditions": [
    [
      {
        "conditionType": 0,
        "fieldCode": "work_order_shift_name",
        "rightPart": {
          "valueType": 1,
          "value": "早班"
        }
      }
    ]
  ],
  "timeJobConfig": {
    "config": {
      "times": [
        "04:00:00"
      ],
      "execType": 4
    }
  }
}
```

###### JSON document

```
{
	"baseInfo":{
		"dataSetId":"数据集ID",
		"anaId":"ID",
		"name":"名称"
	},
	"timeJobConfig":{
		"config":{
			"firstTime":"固定周期类型：首次触发时间",
			"times":"时间列表：每日的几点 hh:mm:ss",
			"weeks":"星期列表：每周的星期几",
			"months":"月份列表：每年的几月份",
			"fixedRate":"固定周期类型：执行间隔，前一次开始执行之后多久执行下次",
			"fixedRateUnit":"固定周期类型：执行间隔单位，1：天；2：小时；3：分钟",
			"customs":"自定义类型：日期时间列表[{ date: 1692759096773, time: [\"hh:mm:ss\"] }]",
			"days":"日期列表：每月的几号",
			"maxExecCount":"固定周期类型：最大执行次数",
			"stopTime":"固定周期类型：停止触发时间",
			"id":"id",
			"execType":"执行频率类型：1每日；2每周；3每月；4每年；5固定周期；6自定义"
		},
		"relatedId":"定时器配置ID"
	},
	"conditions":[
		{}
	],
	"actions":[
		"触发动作"
	],
	"repeatConfig":{
		"checkTimeNum":"时间范围",
		"checkFields":[
			"检查字段"
		],
		"checkTimeUnit":"时间单位"
	}
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
        "dataSetName": "testjt"
      },
      {
        "anaId": 1,
        "code": "ana_1736843818725",
        "name": "t1告警",
        "status": 0,
        "dataSetId": 1715292670106286,
        "dataSetName": "testjt"
      },
      {
        "anaId": 1736825194566001,
        "code": "ana_1736825194738",
        "name": "name_20250114_112634",
        "status": 0,
        "dataSetId": 1709767623185359,
        "dataSetName": "筛选3"
      },
      {
        "anaId": 1736752165634001,
        "code": "ana_1736752165888",
        "name": "name_20250113_150925",
        "status": 0,
        "dataSetId": 1709767623185359,
        "dataSetName": "筛选3"
      },
      {
        "anaId": 1736577089298009,
        "code": "ana_1736577428956",
        "name": "name_20250111_143708",
        "status": 0,
        "dataSetId": 1709767623185359,
        "dataSetName": "筛选3"
      },
      {
        "anaId": 1736577089298005,
        "code": "ana_1736577128138",
        "name": "name_20250111_143208",
        "status": 0,
        "dataSetId": 1705434537871008,
        "dataSetName": "m117预置数据集01"
      },
      {
        "anaId": 1736577089298001,
        "code": "ana_1736577089733",
        "name": "name_20250111_143128",
        "status": 0,
        "dataSetId": 1,
        "dataSetName": null
      },
      {
        "anaId": 1736500767105001,
        "code": "ana_1736500767322",
        "name": "name_20250110_171926",
        "status": 0,
        "dataSetId": 111,
        "dataSetName": null
      },
      {
        "anaId": 1736499670438011,
        "code": null,
        "name": "name_20250110_171806",
        "status": 0,
        "dataSetId": 111,
        "dataSetName": null
      },
      {
        "anaId": 1736499670438006,
        "code": null,
        "name": "name_20250110_171701",
        "status": 0,
        "dataSetId": 111,
        "dataSetName": null
      },
      {
        "anaId": 1736496691049001,
        "code": "999",
        "name": "999",
        "status": 1,
        "dataSetId": 111,
        "dataSetName": null
      },
      {
        "anaId": 1736488504135001,
        "code": "code_20250110_135503",
        "name": "name_20250110_135503",
        "status": null,
        "dataSetId": 111,
        "dataSetName": null
      },
      {
        "anaId": 1736479404878017,
        "code": "code_20250110_135314",
        "name": "name_20250110_135314",
        "status": null,
        "dataSetId": 111,
        "dataSetName": null
      },
      {
        "anaId": 1736479404878014,
        "code": "code_20250110_135248",
        "name": "name_20250110_135248",
        "status": null,
        "dataSetId": 111,
        "dataSetName": null
      },
      {
        "anaId": 1736479404878011,
        "code": "code_20250110_135222",
        "name": "name_20250110_135222",
        "status": null,
        "dataSetId": 111,
        "dataSetName": null
      },
      {
        "anaId": 1736479404878008,
        "code": "code_20250110_135156",
        "name": "name_20250110_135156",
        "status": null,
        "dataSetId": 111,
        "dataSetName": null
      },
      {
        "anaId": 1736422070764036,
        "code": "code",
        "name": "name_20250109_201021",
        "status": null,
        "dataSetId": 111,
        "dataSetName": null
      },
      {
        "anaId": 1736422070764033,
        "code": "code_20250109_200945",
        "name": "name_20250109_200945",
        "status": null,
        "dataSetId": 111,
        "dataSetName": null
      },
      {
        "anaId": 1736422070764030,
        "code": "code_20250109_200923",
        "name": "name_20250109_200923",
        "status": null,
        "dataSetId": 111,
        "dataSetName": null
      },
      {
        "anaId": 1736422070764025,
        "code": "code_{{$currentDateTime}}",
        "name": "name_{{$currentDateTime}}",
        "status": null,
        "dataSetId": 111,
        "dataSetName": null
      }
    ],
    "page": 1,
    "total": 44
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
		"anaId":"分析告警ID"
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


