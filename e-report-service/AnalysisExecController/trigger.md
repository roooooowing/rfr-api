# trigger

### Method description

```
手动触发
```

> URL: http://e-report-domain-feature.test.blacklake.tech/web/v1/analysis/exec/trigger
>
> Origin Url: http://e-report-domain-feature.test.blacklake.tech/web/v1/analysis/exec/trigger
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
  "anaId": 1737353310593557
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
    "list": [
      {
        "anaId": 1737353310593557,
        "code": "ana_1737373434494",
        "name": "测试_mfg_001",
        "status": 1,
        "dataSetId": 1737353008467251,
        "createdAt": 1737373434000,
        "updatedAt": 1737373499000,
        "action": 1
      },
      {
        "anaId": 1737345649996883,
        "code": "ana_1737365490978",
        "name": "测试_生产主题_001",
        "status": 0,
        "dataSetId": 1704652503876731,
        "createdAt": 1737365491000,
        "updatedAt": 1737373438000
      }
    ],
    "page": 1,
    "total": 2
  },
  "message": "成功"
}
```

##### Response document
```
{
	"code":"状态码",
	"data":{
		"anaExecId":"No comment,Type =Number",
		"data":[
			{
				"valid":"是否有效",
				"anaExecId":"分析执行记录ID",
				"repeatKey":"重复键",
				"data":{},
				"anaId":"分析告警配置ID"
			}
		],
		"totalCount":"No comment,Type =Number",
		"config":{
			"baseInfo":{
				"createdAt":"创建时间",
				"code":"编号",
				"dataSetId":"数据集ID",
				"anaId":"ID",
				"name":"名称",
				"status":"状态 0-未启用 1-启用",
				"updatedAt":"更新时间"
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
							"时间列表：每日的几点[\\HH:mm:ss\\]"
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
			},
			"dataSetMeta":{
				"conditionFields":[
					{
						"controlConfig":{
							"optionalConfig":[
								"可选项配置 - 手动配置"
							],
							"controlType":"控件类型，1-搜索类型， 2-下拉控件",
							"databaseName":"可选项配置-指定数据表",
							"dataTableName":"可选项配置-指定数据表",
							"optionalSource":"可选项来源，1-手动配置， 2-指定数据表",
							"dataFieldCode":"可选项配置-字段"
						},
						"fieldName":"字段名称",
						"fieldCode":"字段编号",
						"fieldType":"字段类型"
					}
				],
				"dataSetId":"数据集id",
				"dataSetName":"名称",
				"displayFields":[
					{
						"controlConfig":{
							"optionalConfig":[
								"可选项配置 - 手动配置"
							],
							"controlType":"控件类型，1-搜索类型， 2-下拉控件",
							"databaseName":"可选项配置-指定数据表",
							"dataTableName":"可选项配置-指定数据表",
							"optionalSource":"可选项来源，1-手动配置， 2-指定数据表",
							"dataFieldCode":"可选项配置-字段"
						},
						"fieldName":"字段名称",
						"fieldCode":"字段编号",
						"fieldType":"字段类型"
					}
				]
			}
		},
		"repeatCount":"No comment,Type =Number"
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


