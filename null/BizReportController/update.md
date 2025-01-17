# update

### Method description

```
更新
```

> URL: http://localhost:8080/web/v1/biz_report/update
>
> Origin Url: http://localhost:8080/web/v1/biz_report/update
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
  "bizReportName": "赵林的报表",
  "sort": [
  ],
  "condition": [
    [
      {
        "conditionType": 0,
        "fieldCode": "process_node_num",
        "rightPart": {
          "valueType": 1,
          "value": "20"
        }
      }
    ]
  ],
  "fieldConfig": [
    {
      "fieldCode": "process_id",
      "freeze": false,
      "displayType": null,
      "display": false,
      "displayName": null
    },
    {
      "fieldCode": "work_order_id",
      "freeze": false,
      "displayType": null,
      "display": false,
      "displayName": null
    },
    {
      "fieldCode": "work_order_code",
      "freeze": false,
      "displayType": null,
      "display": true,
      "displayName": null
    },
    {
      "fieldCode": "work_order_plan_start_time",
      "freeze": false,
      "displayType": null,
      "display": false,
      "displayName": null
    },
    {
      "fieldCode": "work_order_plan_finish_time",
      "freeze": false,
      "displayType": null,
      "display": false,
      "displayName": null
    },
    {
      "fieldCode": "process_plan_amount",
      "freeze": false,
      "displayType": null,
      "display": true,
      "displayName": null
    },
    {
      "fieldCode": "process_node_num",
      "freeze": false,
      "displayType": null,
      "display": true,
      "displayName": null
    },
    {
      "fieldCode": "process_name",
      "freeze": false,
      "displayType": null,
      "display": true,
      "displayName": null
    }
  ],
  "bizTheme": 1,
  "bizReportId": 1705459283650230
}
```

###### JSON document

```
{
	"dataSetId":"数据集ID",
	"sort":[
		{
			"orderBy":"排序字段编号",
			"sort":"排序 asc 正序 desc 倒序"
		}
	],
	"bizReportId":"业务报表 id",
	"fieldConfig":[
		{
			"displayType":"显示类型",
			"freeze":"是否冻结 默认不冻结",
			"fieldCode":"字段编号（唯一表示）",
			"displayName":"显示名称",
			"display":"是否显示 默认显示"
		}
	],
	"bizReportName":"业务报表名称"
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
		"bizReportId":"业务报表 id"
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


