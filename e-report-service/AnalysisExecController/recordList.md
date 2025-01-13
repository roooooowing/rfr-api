# recordList

### Method description

```
记录-列表
```

> URL: http://localhost:8080/web/v1/analysis/exec/record/list
>
> Origin Url: http://localhost:8080/web/v1/analysis/exec/record/list
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
	"anaId":"分析告警ID",
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

```

##### Response document
```
{
	"code":"状态码",
	"data":{
		"anaId":"分析告警配置ID",
		"totalCount":"总数量",
		"repeatCount":"重复数"
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


