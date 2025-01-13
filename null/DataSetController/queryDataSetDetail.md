# queryDataSetDetail

### Method description

```
查询数据集详情
```

> URL: http://localhost:8080/web/v1/data_set/queryDataSetDetail
>
> Origin Url: http://localhost:8080/web/v1/data_set/queryDataSetDetail
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
  "dataSetId": 1696670163204056
}
```

###### JSON document

```
{
	"dataSetId":"数据集Id"
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
  "code": 0,
  "data": "default backend - 404",
  "subCode": "E-REPORT-DOMAIN-LOCAL/FEIGN_EX",
  "message": "[404 Not Found] during [POST] to [http://api-adapter-feature.test.blacklake.tech/api/v1/route/_exec] [RouteApi#execRouteIntegrationInterface(ExecRouteCO)]: [default backend - 404]",
  "needCheck": 0
}
```

##### Response document
```
{
	"code":"状态码",
	"data":{
		"themeDetail":"详细主题,与业务主题联动",
		"creator":{
			"code":"编号",
			"phone":"手机号",
			"name":"用户姓名",
			"id":"用户ID",
			"terminal":"账号类型",
			"orgId":"用户工厂ID",
			"email":"邮箱",
			"username":"用户账号"
		},
		"code":"数据集合编号",
		"objectNodeInfoList":[
			{
				"aliasName":"别名",
				"objectCode":"对象编码",
				"dataSetId":"数据集合编号",
				"displayName":"展示名称",
				"nodeRefFieldInfo":[
					{
						"postNodeUniqueValue":1,
						"refFieldName":"refFieldName_49fgi",
						"refFieldDisplayName":"refFieldDisplayName_i79eb",
						"refObjectId":1,
						"refFieldId":1
					}
				],
				"nodeUniqueValue":"节点对象唯一值",
				"rootObject":"是否是根对象 0是，1不是",
				"id":"节点id",
				"objectId":"对象id"
			}
		],
		"dataSetName":"数据集名称",
		"modifier":{
			"code":"编号",
			"phone":"手机号",
			"name":"用户姓名",
			"id":"用户ID",
			"terminal":"账号类型",
			"orgId":"用户工厂ID",
			"email":"邮箱",
			"username":"用户账号"
		},
		"remark":"备注说明",
		"previewData":[
			{}
		],
		"createdAt":"创建时间",
		"dataSetType":"数据集类型",
		"dataSetGenMode":"数据集生成方式",
		"bizTheme":"业务主题,针对相关业务域",
		"id":"数据集合id",
		"bizSetStatus":"数据集状态：0草稿态,1停用，2启用",
		"previewFieldInfos":[
			{
				"objectCode":"对象code",
				"fieldName":"字段名称",
				"fieldCode":"字段code",
				"fieldInfo":"字段信息",
				"fieldDisplayName":"字段展示名称",
				"fieldScreenConList":[
					"fieldScreenConList_zdmn9"
				],
				"objectNodeId":"节点对象id",
				"objectName":"对象名称",
				"checked":"字段是否被勾选:0 不勾选 1 勾选",
				"fieldType":"字段类型",
				"objectId":"对象id",
				"fieldId":"字段id",
				"order":"字段顺序"
			}
		],
		"objectRelationShipInfoList":[
			{
				"postNodeObjectId":"后节点对象id",
				"refField":[
					{
						"preObjectName":"preObjectName_itgwk",
						"postNodeUniqueValue":"postNodeUniqueValue_zuxva",
						"postRefFieldName":"postRefFieldName_32okm",
						"preRefFieldName":"preRefFieldName_17v67",
						"preNodeUniqueValue":"preNodeUniqueValue_hd0x2",
						"postRefFieldId":1,
						"postObjectName":"postObjectName_n3fa5",
						"preRefFieldDisplayName":"preRefFieldDisplayName_g79w1",
						"postRefFieldDisplayName":"postRefFieldDisplayName_rkgsu",
						"postObjectId":1,
						"preObjectId":1,
						"preRefFieldId":1
					}
				],
				"preNodeObjectId":"前节点对象id",
				"postNodeUniqueValue":"前节点关联唯一值",
				"dataSetId":"数据集合编号",
				"preNodeUniqueValue":"前节点关联唯一值",
				"postNodeName":"后节点名称 存储对象code",
				"joinType":"关联类型：0 左连接，1内连接，2右连接",
				"preNodeName":"前节点名称 存储对象code",
				"id":"关联关系id",
				"joinRelation":"与上游对象的关联关系：0:(1:1),1:(1:n)"
			}
		],
		"updatedAt":"更新时间"
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


