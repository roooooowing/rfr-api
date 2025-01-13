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
  "quickSearch": "quickSearch_3b59n"
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
{
  "code": 200,
  "data": {
    "list": [
      {
        "anaId": 1736577089298009,
        "code": "ana_1736577428956",
        "name": "name_20250111_143708",
        "totalCount": 100,
        "repeatCount": 0,
        "id": 1736584998229005,
        "createdAt": 1736585091000,
        "updatedAt": 1736585091000
      },
      {
        "anaId": 1736577089298009,
        "code": "ana_1736577428956",
        "name": "name_20250111_143708",
        "totalCount": 100,
        "repeatCount": 0,
        "id": 1736584998229109,
        "createdAt": 1736585107000,
        "updatedAt": 1736585107000
      }
    ],
    "page": 1,
    "total": 2
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


