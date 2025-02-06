# listDataset

### Method description

```
可选数据集
```

> URL: http://localhost:8080/web/v1/analysis/config/dataset/optional_list
>
> Origin Url: http://localhost:8080/web/v1/analysis/config/dataset/optional_list
>
> Type: POST


### Request headers

|Header Name| Header Value|
|---------|------|
|x-org-id|10162960|
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
}
```

###### JSON document

```
{
	"quickSearch":"快速搜索"
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
	"data":{},
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


