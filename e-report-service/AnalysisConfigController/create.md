# create

### Method description

```
新建
```

> URL: http://localhost:8080/web/v1/analysis/config/create
>
> Origin Url: http://localhost:8080/web/v1/analysis/config/create
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
    "name": "name_20250111_143207",
    "dataSetId": 1705434537871008
  },
  "conditions": [
  ],
  "timeJobConfig": {
  },
  "actions": [
    1
  ],
  "repeatConfig": {
    "checkFields": [
      "test"
    ],
    "checkTimeNum": 1,
    "checkTimeUnit": 1
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
  "data": [
    {
      "dataSetId": 1704873483446296,
      "dataSetName": "ak01",
      "dataSetGenMode": 3,
      "dataSetType": 3,
      "remark": ""
    },
    {
      "dataSetId": 1711318027539885,
      "dataSetName": "copy0011",
      "dataSetGenMode": 3,
      "dataSetType": 3,
      "remark": ""
    },
    {
      "dataSetId": 1709714582943830,
      "dataSetName": "cwpcszy001",
      "dataSetGenMode": 3,
      "dataSetType": 1,
      "remark": ""
    },
    {
      "dataSetId": 1724748738774002,
      "dataSetName": "gm测试222",
      "dataSetGenMode": 3,
      "dataSetType": 1,
      "remark": ""
    },
    {
      "dataSetId": 1705433981406613,
      "dataSetName": "m117预置数据集01",
      "dataSetGenMode": 3,
      "dataSetType": 1,
      "remark": "新建预置数据集，用于测试使用，勿动"
    },
    {
      "dataSetId": 1705434537871008,
      "dataSetName": "m117预置数据集01",
      "dataSetGenMode": 3,
      "dataSetType": 1,
      "remark": ""
    },
    {
      "dataSetId": 1709182479803568,
      "dataSetName": "ypoc021",
      "dataSetGenMode": 3,
      "dataSetType": 1,
      "remark": ""
    },
    {
      "dataSetId": 1709157993325043,
      "dataSetName": "定制筛选3",
      "dataSetGenMode": 3,
      "dataSetType": 3,
      "remark": ""
    },
    {
      "dataSetId": 1709157993325075,
      "dataSetName": "定制筛选3a",
      "dataSetGenMode": 3,
      "dataSetType": 3,
      "remark": ""
    },
    {
      "dataSetId": 1709158430394191,
      "dataSetName": "定制筛选3a",
      "dataSetGenMode": 3,
      "dataSetType": 3,
      "remark": ""
    },
    {
      "dataSetId": 1705985677470304,
      "dataSetName": "工单日报表",
      "dataSetGenMode": 3,
      "dataSetType": 1,
      "remark": ""
    },
    {
      "dataSetId": 1705986552216538,
      "dataSetName": "工单日报表",
      "dataSetGenMode": 3,
      "dataSetType": 1,
      "remark": ""
    },
    {
      "dataSetId": 1705985677470349,
      "dataSetName": "工序进度日报",
      "dataSetGenMode": 3,
      "dataSetType": 1,
      "remark": ""
    },
    {
      "dataSetId": 1704861678160004,
      "dataSetName": "数据集01",
      "dataSetGenMode": 3,
      "dataSetType": 3,
      "remark": ""
    },
    {
      "dataSetId": 1704861678160026,
      "dataSetName": "数据集01",
      "dataSetGenMode": 3,
      "dataSetType": 3,
      "remark": ""
    },
    {
      "dataSetId": 1704860295990004,
      "dataSetName": "数据集01",
      "dataSetGenMode": 3,
      "dataSetType": 3,
      "remark": ""
    },
    {
      "dataSetId": 1704860295990017,
      "dataSetName": "数据集02",
      "dataSetGenMode": 3,
      "dataSetType": 1,
      "remark": ""
    },
    {
      "dataSetId": 1704652503876731,
      "dataSetName": "测试生产主题",
      "dataSetGenMode": 3,
      "dataSetType": 3,
      "remark": ""
    },
    {
      "dataSetId": 1704652503876721,
      "dataSetName": "测试生产主题带limit",
      "dataSetGenMode": 3,
      "dataSetType": 3,
      "remark": ""
    },
    {
      "dataSetId": 1708639215603734,
      "dataSetName": "筛选1",
      "dataSetGenMode": 3,
      "dataSetType": 1,
      "remark": ""
    },
    {
      "dataSetId": 1709767623185359,
      "dataSetName": "筛选3",
      "dataSetGenMode": 3,
      "dataSetType": 1,
      "remark": ""
    },
    {
      "dataSetId": 1710367677341211,
      "dataSetName": "筛选4",
      "dataSetGenMode": 3,
      "dataSetType": 1,
      "remark": ""
    },
    {
      "dataSetId": 1710469703512531,
      "dataSetName": "筛选5",
      "dataSetGenMode": 3,
      "dataSetType": 1,
      "remark": ""
    },
    {
      "dataSetId": 1724116200294170,
      "dataSetName": "预置数据集0820005",
      "dataSetGenMode": 3,
      "dataSetType": 1,
      "remark": ""
    }
  ],
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


