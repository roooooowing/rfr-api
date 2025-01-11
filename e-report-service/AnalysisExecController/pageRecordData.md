# pageRecordData

### Method description

```
分析告警记录-数据
```

> URL: http://localhost:8080/web/v1/analysis/exec/record/page_data
>
> Origin Url: http://localhost:8080/web/v1/analysis/exec/record/page_data
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
  "anaExecId": 1736584998229005,
  "page": 1,
  "size": 20,
  "selectFlag": 1
}
```

###### JSON document

```
{
	"anaExecId":"执行记录ID",
	"size":"每页大小",
	"sorter":[
		{
			"field":"排序字段",
			"order":"排序规律 默认 asc，asc 升序 desc 降序"
		}
	],
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
        "anaId": 1736577089298009,
        "anaExecId": 1736584998229005,
        "repeatKey": null,
        "data": null
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736584998229005,
        "repeatKey": null,
        "data": null
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736584998229005,
        "repeatKey": null,
        "data": null
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736584998229005,
        "repeatKey": null,
        "data": null
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736584998229005,
        "repeatKey": null,
        "data": null
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736584998229005,
        "repeatKey": null,
        "data": null
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736584998229005,
        "repeatKey": null,
        "data": null
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736584998229005,
        "repeatKey": null,
        "data": null
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736584998229005,
        "repeatKey": null,
        "data": null
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736584998229005,
        "repeatKey": null,
        "data": null
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736584998229005,
        "repeatKey": null,
        "data": null
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736584998229005,
        "repeatKey": null,
        "data": null
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736584998229005,
        "repeatKey": null,
        "data": null
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736584998229005,
        "repeatKey": null,
        "data": null
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736584998229005,
        "repeatKey": null,
        "data": null
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736584998229005,
        "repeatKey": null,
        "data": null
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736584998229005,
        "repeatKey": null,
        "data": null
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736584998229005,
        "repeatKey": null,
        "data": null
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736584998229005,
        "repeatKey": null,
        "data": null
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736584998229005,
        "repeatKey": null,
        "data": null
      }
    ],
    "page": 1,
    "total": 100
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
		"valid":"是否有效",
		"anaExecId":"分析执行记录ID",
		"repeatKey":"重复键",
		"data":{},
		"anaId":"分析告警配置ID"
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


