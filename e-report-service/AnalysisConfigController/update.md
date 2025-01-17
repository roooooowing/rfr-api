# update

### Method description

```
编辑
```

> URL: http://localhost:8080/web/v1/analysis/config/update
>
> Origin Url: http://localhost:8080/web/v1/analysis/config/update
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
  "anaId": 1737045480332840,
  "baseInfo": {
    "name": "t4告警",
    "dataSetId": 1705433981406613
  },
  "actions": [
    1
  ],
  "conditions": [
    [
      {
        "conditionType": 0,
        "fieldCode": "work_order_code",
        "rightPart": {
          "valueType": 1,
          "value": "3"
        }
      },
      {
        "conditionType": 0,
        "fieldCode": "work_order_status_display",
        "rightPart": {
          "valueType": 1,
          "value": "2"
        }
      }
    ]
  ],
  "timeJobConfig": {
    "times": [
      "04:00:00"
    ],
    "customs": [],
    "days": [
      5,
      4,
      3
    ],
    "execType": 4,
    "firstTime": null,
    "fixedRate": null,
    "fixedRateUnit": null,
    "maxExecCount": null,
    "stopTime": null,
    "months": [
      1,
      2,
      3
    ],
    "weeks": null
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
		"firstTime":"固定周期类型：首次触发时间",
		"times":[
			"时间列表：每日的几点[\\HH:mm:ss\\]"
		],
		"weeks":[
			"星期列表：每周的星期几"
		],
		"months":[
			"月份列表：每年的几月份"
		],
		"fixedRate":"固定周期类型：执行间隔，前一次开始执行之后多久执行下次",
		"fixedRateUnit":"固定周期类型：执行间隔单位，1：天；2：小时；3：分钟",
		"customs":[
			{
				"date":"日期：yyyy-MM-dd",
				"times":[
					"times_tkk5l"
				]
			}
		],
		"days":[
			"日期列表：每月的几号"
		],
		"maxExecCount":"固定周期类型：最大执行次数",
		"stopTime":"固定周期类型：停止触发时间",
		"execType":"执行频率类型：1每日；2每周；3每月；4每年；5固定周期；6自定义；7每小时"
	},
	"anaId":"分析告警ID",
	"action":"触发动作",
	"conditions":[
		{}
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
    "baseInfo": {
      "anaId": 1737045480332840,
      "code": "ana_1737079894155",
      "name": "t4告警",
      "status": 0,
      "dataSetId": 1705433981406613
    },
    "conditions": [
      [
        {
          "fieldCode": "work_order_code",
          "conditionType": 0,
          "rightPart": {
            "value": "3",
            "valueType": 1,
            "fromValue": null,
            "toValue": null
          }
        }
      ]
    ],
    "timeJobConfig": {
      "execType": 4,
      "times": [
        "04:00"
      ],
      "days": [
        5,
        4,
        3
      ],
      "weeks": null,
      "months": [
        1,
        2,
        3
      ],
      "firstTime": null,
      "fixedRate": null,
      "fixedRateUnit": null,
      "maxExecCount": null,
      "stopTime": null,
      "customs": []
    },
    "action": null,
    "repeatConfig": null,
    "dataSetMeta": {
      "dataSetId": 1705433981406613,
      "dataSetName": "m117预置数据集01"
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


