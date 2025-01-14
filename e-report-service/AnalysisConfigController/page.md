# page

### Method description

```
列表筛选
```

> URL: http://localhost:8080/web/v1/analysis/config/page
>
> Origin Url: http://localhost:8080/web/v1/analysis/config/page
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
  "quickSearch": "",
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
	"quickSearch":"快速搜索",
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
        "baseInfo": {
          "anaId": 1736496691049001,
          "code": "999",
          "name": "999",
          "status": 1,
          "dataSetId": 111
        },
        "condition": null,
        "timeJobConfig": null,
        "actions": [
          1
        ],
        "repeatConfig": {
          "checkFields": [
            "field_1"
          ],
          "checkTimeNum": 1,
          "checkTimeUnit": 3
        }
      },
      {
        "baseInfo": {
          "anaId": 1736388952068044,
          "code": "code_-1",
          "name": "name_-1",
          "status": null,
          "dataSetId": 111
        },
        "condition": null,
        "timeJobConfig": null,
        "actions": [
          1
        ],
        "repeatConfig": {
          "checkFields": [
            "field_1"
          ],
          "checkTimeNum": 1,
          "checkTimeUnit": 3
        }
      },
      {
        "baseInfo": {
          "anaId": 1736388952068051,
          "code": "code_20250109_111224",
          "name": "name_20250109_111224",
          "status": null,
          "dataSetId": 111
        },
        "condition": null,
        "timeJobConfig": null,
        "actions": [
          1
        ],
        "repeatConfig": {
          "checkFields": [
            "field_1"
          ],
          "checkTimeNum": 1,
          "checkTimeUnit": 3
        }
      },
      {
        "baseInfo": {
          "anaId": 1736388952068054,
          "code": "code_20250109_115348",
          "name": "name_20250109_115348",
          "status": null,
          "dataSetId": 111
        },
        "condition": null,
        "timeJobConfig": null,
        "actions": [
          1
        ],
        "repeatConfig": {
          "checkFields": [
            "field_1"
          ],
          "checkTimeNum": 1,
          "checkTimeUnit": 3
        }
      },
      {
        "baseInfo": {
          "anaId": 1736388952068057,
          "code": "code_20250109_115503",
          "name": "name_20250109_115503",
          "status": null,
          "dataSetId": 111
        },
        "condition": null,
        "timeJobConfig": null,
        "actions": [
          1
        ],
        "repeatConfig": {
          "checkFields": [
            "field_1"
          ],
          "checkTimeNum": 1,
          "checkTimeUnit": 3
        }
      },
      {
        "baseInfo": {
          "anaId": 1736388952068060,
          "code": "code_20250109_115534",
          "name": "name_20250109_115534",
          "status": null,
          "dataSetId": 111
        },
        "condition": null,
        "timeJobConfig": null,
        "actions": [
          1
        ],
        "repeatConfig": {
          "checkFields": [
            "field_1"
          ],
          "checkTimeNum": 1,
          "checkTimeUnit": 3
        }
      },
      {
        "baseInfo": {
          "anaId": 1736408621821001,
          "code": "code_20250109_154341",
          "name": "name_20250109_154341",
          "status": null,
          "dataSetId": 111
        },
        "condition": null,
        "timeJobConfig": null,
        "actions": [
          1
        ],
        "repeatConfig": {
          "checkFields": [
            "field_1"
          ],
          "checkTimeNum": 1,
          "checkTimeUnit": 3
        }
      },
      {
        "baseInfo": {
          "anaId": 1736422070764001,
          "code": "code_20250109_192750",
          "name": "name_20250109_192750",
          "status": null,
          "dataSetId": 111
        },
        "condition": null,
        "timeJobConfig": null,
        "actions": [
          1
        ],
        "repeatConfig": {
          "checkFields": [
            "field_1"
          ],
          "checkTimeNum": 1,
          "checkTimeUnit": 3
        }
      },
      {
        "baseInfo": {
          "anaId": 1736422070764004,
          "code": "code_20250109_192803",
          "name": "name_20250109_192803",
          "status": null,
          "dataSetId": 111
        },
        "condition": null,
        "timeJobConfig": null,
        "actions": [
          1
        ],
        "repeatConfig": {
          "checkFields": [
            "field_1"
          ],
          "checkTimeNum": 1,
          "checkTimeUnit": 3
        }
      },
      {
        "baseInfo": {
          "anaId": 1736422070764007,
          "code": "code_20250109_192856",
          "name": "name_20250109_192856",
          "status": null,
          "dataSetId": 111
        },
        "condition": null,
        "timeJobConfig": null,
        "actions": [
          1
        ],
        "repeatConfig": {
          "checkFields": [
            "field_1"
          ],
          "checkTimeNum": 1,
          "checkTimeUnit": 3
        }
      },
      {
        "baseInfo": {
          "anaId": 1736422070764010,
          "code": "code_20250109_192902",
          "name": "name_20250109_192902",
          "status": null,
          "dataSetId": 111
        },
        "condition": null,
        "timeJobConfig": null,
        "actions": [
          1
        ],
        "repeatConfig": {
          "checkFields": [
            "field_1"
          ],
          "checkTimeNum": 1,
          "checkTimeUnit": 3
        }
      },
      {
        "baseInfo": {
          "anaId": 1736422070764013,
          "code": "code_20250109_192955",
          "name": "name_20250109_192955",
          "status": null,
          "dataSetId": 111
        },
        "condition": null,
        "timeJobConfig": null,
        "actions": [
          1
        ],
        "repeatConfig": {
          "checkFields": [
            "field_1"
          ],
          "checkTimeNum": 1,
          "checkTimeUnit": 3
        }
      },
      {
        "baseInfo": {
          "anaId": 1736422070764017,
          "code": "code_20250109_193028",
          "name": "name_20250109_193028",
          "status": null,
          "dataSetId": 111
        },
        "condition": null,
        "timeJobConfig": null,
        "actions": [
          1
        ],
        "repeatConfig": {
          "checkFields": [
            "field_1"
          ],
          "checkTimeNum": 1,
          "checkTimeUnit": 3
        }
      },
      {
        "baseInfo": {
          "anaId": 1736422070764019,
          "code": "code_20250109_193146",
          "name": "name_20250109_193146",
          "status": null,
          "dataSetId": 111
        },
        "condition": null,
        "timeJobConfig": null,
        "actions": [
          1
        ],
        "repeatConfig": {
          "checkFields": [
            "field_1"
          ],
          "checkTimeNum": 1,
          "checkTimeUnit": 3
        }
      },
      {
        "baseInfo": {
          "anaId": 1736422070764022,
          "code": "code_20250109_193441",
          "name": "name_20250109_193441",
          "status": null,
          "dataSetId": 111
        },
        "condition": null,
        "timeJobConfig": null,
        "actions": [
          1
        ],
        "repeatConfig": {
          "checkFields": [
            "field_1"
          ],
          "checkTimeNum": 1,
          "checkTimeUnit": 3
        }
      },
      {
        "baseInfo": {
          "anaId": 1736422070764030,
          "code": "code_20250109_200923",
          "name": "name_20250109_200923",
          "status": null,
          "dataSetId": 111
        },
        "condition": null,
        "timeJobConfig": null,
        "actions": [
          1
        ],
        "repeatConfig": {
          "checkFields": [
            "field_1"
          ],
          "checkTimeNum": 1,
          "checkTimeUnit": 3
        }
      },
      {
        "baseInfo": {
          "anaId": 1736422070764033,
          "code": "code_20250109_200945",
          "name": "name_20250109_200945",
          "status": null,
          "dataSetId": 111
        },
        "condition": null,
        "timeJobConfig": null,
        "actions": [
          1
        ],
        "repeatConfig": {
          "checkFields": [
            "field_1"
          ],
          "checkTimeNum": 1,
          "checkTimeUnit": 3
        }
      },
      {
        "baseInfo": {
          "anaId": 1736422070764036,
          "code": "code",
          "name": "name_20250109_201021",
          "status": null,
          "dataSetId": 111
        },
        "condition": null,
        "timeJobConfig": null,
        "actions": [
          1
        ],
        "repeatConfig": {
          "checkFields": [
            "field_1"
          ],
          "checkTimeNum": 1,
          "checkTimeUnit": 3
        }
      },
      {
        "baseInfo": {
          "anaId": 1736479404878008,
          "code": "code_20250110_135156",
          "name": "name_20250110_135156",
          "status": null,
          "dataSetId": 111
        },
        "condition": null,
        "timeJobConfig": null,
        "actions": [
          1
        ],
        "repeatConfig": {
          "checkFields": [
            "field_1"
          ],
          "checkTimeNum": 1,
          "checkTimeUnit": 3
        }
      },
      {
        "baseInfo": {
          "anaId": 1736479404878011,
          "code": "code_20250110_135222",
          "name": "name_20250110_135222",
          "status": null,
          "dataSetId": 111
        },
        "condition": null,
        "timeJobConfig": null,
        "actions": [
          1
        ],
        "repeatConfig": {
          "checkFields": [
            "field_1"
          ],
          "checkTimeNum": 1,
          "checkTimeUnit": 3
        }
      }
    ],
    "page": 1,
    "total": 44
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
		"condition":[
			{}
		],
		"timeJobConfig":{
			"config":{
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
			"relatedId":"定时器配置ID"
		},
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


