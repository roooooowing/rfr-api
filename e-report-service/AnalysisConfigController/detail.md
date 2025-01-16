# detail

### Method description

```
详情
```

> URL: http://localhost:8080/web/v1/analysis/config/detail
>
> Origin Url: http://localhost:8080/web/v1/analysis/config/detail
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
  "anaId": 1
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
    "baseInfo": {
      "anaId": 1736825194566001,
      "code": "ana_1736825194738",
      "name": "name_20250114_112634",
      "status": 0,
      "dataSetId": 1709767623185359
    },
    "actions": [
      1
    ],
    "dataSetMeta": {
      "dataSetId": 1709767623185359,
      "displayFields": [
        {
          "fieldCode": "org_id",
          "fieldName": "工厂ID",
          "fieldType": 2
        },
        {
          "fieldCode": "process_id",
          "fieldName": "工单工序id",
          "fieldType": 2
        },
        {
          "fieldCode": "work_order_shift_name",
          "fieldName": "工单班次名",
          "fieldType": 1
        },
        {
          "fieldCode": "work_order_id",
          "fieldName": "工单id",
          "fieldType": 2
        },
        {
          "fieldCode": "work_order_code",
          "fieldName": "工单编号",
          "fieldType": 1
        },
        {
          "fieldCode": "work_order_plan_start_time",
          "fieldName": "计划开始时间",
          "fieldType": 8
        },
        {
          "fieldCode": "work_order_plan_finish_time",
          "fieldName": "计划完工时间",
          "fieldType": 8
        },
        {
          "fieldCode": "process_plan_amount",
          "fieldName": "工序计划数",
          "fieldType": 2
        },
        {
          "fieldCode": "process_node_num",
          "fieldName": "工单工序号",
          "fieldType": 1
        },
        {
          "fieldCode": "process_name",
          "fieldName": "工单工序名称",
          "fieldType": 1
        }
      ]
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
		"baseInfo":{
			"code":"编号",
			"dataSetId":"数据集ID",
			"anaId":"ID",
			"name":"名称",
			"status":"状态 0-未启用 1-启用"
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


