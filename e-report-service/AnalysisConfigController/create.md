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
    "anaId": 1,
    "name": "t1告警",
    "dataSetId": 1715292670106286
  },
  "actions": [
    1
  ],
  "conditions": [
    [
      {
        "conditionType": 0,
        "fieldCode": "work_order_shift_name",
        "rightPart": {
          "valueType": 1,
          "value": "早班"
        }
      }
    ]
  ],
  "timeJobConfig": {
    "config": {
      "times": [
        "04:00:00"
      ],
      "execType": 4
    }
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
  "data": {
    "anaExecId": 1736841566695001,
    "config": {
      "baseInfo": {
        "anaId": 1736577089298009,
        "code": "ana_1736577428956",
        "name": "name_20250111_143708",
        "status": 0,
        "dataSetId": 1709767623185359
      },
      "conditions": [],
      "timeJobConfig": null,
      "actions": [
        1
      ],
      "repeatConfig": {
        "checkFields": [
          "test"
        ],
        "checkTimeNum": 1,
        "checkTimeUnit": 1
      },
      "dataSetMeta": {
        "dataSetId": 1709767623185359,
        "displayFields": [
          {
            "fieldCode": "org_id",
            "fieldName": "工厂ID",
            "fieldType": 2,
            "controlConfig": {
              "controlType": null,
              "optionalSource": null,
              "optionalConfig": null,
              "databaseName": null,
              "dataTableName": null,
              "dataFieldCode": null
            }
          },
          {
            "fieldCode": "process_id",
            "fieldName": "工单工序id",
            "fieldType": 2,
            "controlConfig": {
              "controlType": null,
              "optionalSource": null,
              "optionalConfig": null,
              "databaseName": null,
              "dataTableName": null,
              "dataFieldCode": null
            }
          },
          {
            "fieldCode": "work_order_shift_name",
            "fieldName": "工单班次名",
            "fieldType": 1,
            "controlConfig": {
              "controlType": 2,
              "optionalSource": 2,
              "optionalConfig": null,
              "databaseName": "dw_v3_ads",
              "dataTableName": "vw_realtime_data_warehouse_mfg_topic",
              "dataFieldCode": "work_order_shift_name"
            }
          },
          {
            "fieldCode": "work_order_id",
            "fieldName": "工单id",
            "fieldType": 2,
            "controlConfig": {
              "controlType": null,
              "optionalSource": null,
              "optionalConfig": null,
              "databaseName": null,
              "dataTableName": null,
              "dataFieldCode": null
            }
          },
          {
            "fieldCode": "work_order_code",
            "fieldName": "工单编号",
            "fieldType": 1,
            "controlConfig": {
              "controlType": 1,
              "optionalSource": null,
              "optionalConfig": null,
              "databaseName": null,
              "dataTableName": null,
              "dataFieldCode": null
            }
          },
          {
            "fieldCode": "work_order_plan_start_time",
            "fieldName": "计划开始时间",
            "fieldType": 8,
            "controlConfig": {
              "controlType": null,
              "optionalSource": null,
              "optionalConfig": null,
              "databaseName": null,
              "dataTableName": null,
              "dataFieldCode": null
            }
          },
          {
            "fieldCode": "work_order_plan_finish_time",
            "fieldName": "计划完工时间",
            "fieldType": 8,
            "controlConfig": {
              "controlType": null,
              "optionalSource": null,
              "optionalConfig": null,
              "databaseName": null,
              "dataTableName": null,
              "dataFieldCode": null
            }
          },
          {
            "fieldCode": "process_plan_amount",
            "fieldName": "工序计划数",
            "fieldType": 2,
            "controlConfig": {
              "controlType": null,
              "optionalSource": null,
              "optionalConfig": null,
              "databaseName": null,
              "dataTableName": null,
              "dataFieldCode": null
            }
          },
          {
            "fieldCode": "process_node_num",
            "fieldName": "工单工序号",
            "fieldType": 1,
            "controlConfig": {
              "controlType": 2,
              "optionalSource": 1,
              "optionalConfig": [
                "1",
                "2",
                "3",
                "4"
              ],
              "databaseName": null,
              "dataTableName": null,
              "dataFieldCode": null
            }
          },
          {
            "fieldCode": "process_name",
            "fieldName": "工单工序名称",
            "fieldType": 1,
            "controlConfig": {
              "controlType": 1,
              "optionalSource": null,
              "optionalConfig": null,
              "databaseName": null,
              "dataTableName": null,
              "dataFieldCode": null
            }
          }
        ],
        "conditionFields": [
          {
            "fieldCode": "org_id",
            "fieldName": "工厂ID",
            "fieldType": 2,
            "controlConfig": {
              "controlType": null,
              "optionalSource": null,
              "optionalConfig": null,
              "databaseName": null,
              "dataTableName": null,
              "dataFieldCode": null
            }
          },
          {
            "fieldCode": "process_id",
            "fieldName": "工单工序id",
            "fieldType": 2,
            "controlConfig": {
              "controlType": null,
              "optionalSource": null,
              "optionalConfig": null,
              "databaseName": null,
              "dataTableName": null,
              "dataFieldCode": null
            }
          },
          {
            "fieldCode": "work_order_shift_name",
            "fieldName": "工单班次名",
            "fieldType": 1,
            "controlConfig": {
              "controlType": 2,
              "optionalSource": 2,
              "optionalConfig": null,
              "databaseName": "dw_v3_ads",
              "dataTableName": "vw_realtime_data_warehouse_mfg_topic",
              "dataFieldCode": "work_order_shift_name"
            }
          },
          {
            "fieldCode": "work_order_id",
            "fieldName": "工单id",
            "fieldType": 2,
            "controlConfig": {
              "controlType": null,
              "optionalSource": null,
              "optionalConfig": null,
              "databaseName": null,
              "dataTableName": null,
              "dataFieldCode": null
            }
          },
          {
            "fieldCode": "work_order_code",
            "fieldName": "工单编号",
            "fieldType": 1,
            "controlConfig": {
              "controlType": 1,
              "optionalSource": null,
              "optionalConfig": null,
              "databaseName": null,
              "dataTableName": null,
              "dataFieldCode": null
            }
          },
          {
            "fieldCode": "work_order_plan_start_time",
            "fieldName": "计划开始时间",
            "fieldType": 8,
            "controlConfig": {
              "controlType": null,
              "optionalSource": null,
              "optionalConfig": null,
              "databaseName": null,
              "dataTableName": null,
              "dataFieldCode": null
            }
          },
          {
            "fieldCode": "work_order_plan_finish_time",
            "fieldName": "计划完工时间",
            "fieldType": 8,
            "controlConfig": {
              "controlType": null,
              "optionalSource": null,
              "optionalConfig": null,
              "databaseName": null,
              "dataTableName": null,
              "dataFieldCode": null
            }
          },
          {
            "fieldCode": "process_plan_amount",
            "fieldName": "工序计划数",
            "fieldType": 2,
            "controlConfig": {
              "controlType": null,
              "optionalSource": null,
              "optionalConfig": null,
              "databaseName": null,
              "dataTableName": null,
              "dataFieldCode": null
            }
          },
          {
            "fieldCode": "process_node_num",
            "fieldName": "工单工序号",
            "fieldType": 1,
            "controlConfig": {
              "controlType": 2,
              "optionalSource": 1,
              "optionalConfig": [
                "1",
                "2",
                "3",
                "4"
              ],
              "databaseName": null,
              "dataTableName": null,
              "dataFieldCode": null
            }
          },
          {
            "fieldCode": "process_name",
            "fieldName": "工单工序名称",
            "fieldType": 1,
            "controlConfig": {
              "controlType": 1,
              "optionalSource": null,
              "optionalConfig": null,
              "databaseName": null,
              "dataTableName": null,
              "dataFieldCode": null
            }
          }
        ]
      }
    },
    "data": [
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1648258514137302,
          "work_order_shift_name": null,
          "work_order_id": 1648258514137300,
          "work_order_code": "0328gd001",
          "work_order_plan_start_time": 1648310400000,
          "work_order_plan_finish_time": 1648703536000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "0328工序001"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1648258514137303,
          "work_order_shift_name": null,
          "work_order_id": 1648258514137300,
          "work_order_code": "0328gd001",
          "work_order_plan_start_time": 1648310400000,
          "work_order_plan_finish_time": 1648703536000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "20",
          "process_name": "0328工序002"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1648258514137337,
          "work_order_shift_name": null,
          "work_order_id": 1648258514137335,
          "work_order_code": "zzw1",
          "work_order_plan_start_time": 1648396800000,
          "work_order_plan_finish_time": 1648693585000,
          "process_plan_amount": 200.0000000000,
          "process_node_num": "10",
          "process_name": "zzw1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1648554580575073,
          "work_order_shift_name": null,
          "work_order_id": 1648554580575071,
          "work_order_code": "swd191424454",
          "work_order_plan_start_time": 1648396800000,
          "work_order_plan_finish_time": 1648693585000,
          "process_plan_amount": 200.0000000000,
          "process_node_num": "10",
          "process_name": "zzw1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1648554580575088,
          "work_order_shift_name": null,
          "work_order_id": 1648554580575086,
          "work_order_code": "swd727675838",
          "work_order_plan_start_time": 1648396800000,
          "work_order_plan_finish_time": 1648693585000,
          "process_plan_amount": 200.0000000000,
          "process_node_num": "10",
          "process_name": "zzw1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1648554580575103,
          "work_order_shift_name": null,
          "work_order_id": 1648554580575101,
          "work_order_code": "swd1347769125",
          "work_order_plan_start_time": 1648396800000,
          "work_order_plan_finish_time": 1648693585000,
          "process_plan_amount": 200.0000000000,
          "process_node_num": "10",
          "process_name": "zzw1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1648554580575118,
          "work_order_shift_name": null,
          "work_order_id": 1648554580575116,
          "work_order_code": "swd1683180931",
          "work_order_plan_start_time": 1648396800000,
          "work_order_plan_finish_time": 1648693585000,
          "process_plan_amount": 200.0000000000,
          "process_node_num": "10",
          "process_name": "zzw1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1648554580575133,
          "work_order_shift_name": null,
          "work_order_id": 1648554580575131,
          "work_order_code": "swd695959124",
          "work_order_plan_start_time": 1648396800000,
          "work_order_plan_finish_time": 1648693585000,
          "process_plan_amount": 200.0000000000,
          "process_node_num": "10",
          "process_name": "zzw1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1648554580575148,
          "work_order_shift_name": null,
          "work_order_id": 1648554580575146,
          "work_order_code": "swd2073559337",
          "work_order_plan_start_time": 1648396800000,
          "work_order_plan_finish_time": 1648693585000,
          "process_plan_amount": 200.0000000000,
          "process_node_num": "10",
          "process_name": "zzw1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1648554580575163,
          "work_order_shift_name": null,
          "work_order_id": 1648554580575161,
          "work_order_code": "swd1315804226",
          "work_order_plan_start_time": 1648396800000,
          "work_order_plan_finish_time": 1648693585000,
          "process_plan_amount": 200.0000000000,
          "process_node_num": "10",
          "process_name": "zzw1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1648554580575178,
          "work_order_shift_name": null,
          "work_order_id": 1648554580575176,
          "work_order_code": "swd518618911",
          "work_order_plan_start_time": 1648396800000,
          "work_order_plan_finish_time": 1648693585000,
          "process_plan_amount": 200.0000000000,
          "process_node_num": "10",
          "process_name": "zzw1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1648554580575193,
          "work_order_shift_name": null,
          "work_order_id": 1648554580575191,
          "work_order_code": "swd2106748588",
          "work_order_plan_start_time": 1648396800000,
          "work_order_plan_finish_time": 1648693585000,
          "process_plan_amount": 200.0000000000,
          "process_node_num": "10",
          "process_name": "zzw1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1648554580575208,
          "work_order_shift_name": null,
          "work_order_id": 1648554580575206,
          "work_order_code": "swd353279400",
          "work_order_plan_start_time": 1648396800000,
          "work_order_plan_finish_time": 1648693585000,
          "process_plan_amount": 200.0000000000,
          "process_node_num": "10",
          "process_name": "zzw1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1648554580575223,
          "work_order_shift_name": null,
          "work_order_id": 1648554580575221,
          "work_order_code": "swd1680886495",
          "work_order_plan_start_time": 1648396800000,
          "work_order_plan_finish_time": 1648693585000,
          "process_plan_amount": 200.0000000000,
          "process_node_num": "10",
          "process_name": "zzw1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1648554580575238,
          "work_order_shift_name": null,
          "work_order_id": 1648554580575236,
          "work_order_code": "swd1077258756",
          "work_order_plan_start_time": 1648396800000,
          "work_order_plan_finish_time": 1648693585000,
          "process_plan_amount": 200.0000000000,
          "process_node_num": "10",
          "process_name": "zzw1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1648554580575253,
          "work_order_shift_name": null,
          "work_order_id": 1648554580575251,
          "work_order_code": "swd2009511428",
          "work_order_plan_start_time": 1648396800000,
          "work_order_plan_finish_time": 1648693585000,
          "process_plan_amount": 200.0000000000,
          "process_node_num": "10",
          "process_name": "zzw1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1648554580575268,
          "work_order_shift_name": null,
          "work_order_id": 1648554580575266,
          "work_order_code": "swd1720009066",
          "work_order_plan_start_time": 1648396800000,
          "work_order_plan_finish_time": 1648693585000,
          "process_plan_amount": 200.0000000000,
          "process_node_num": "10",
          "process_name": "zzw1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1648554580575283,
          "work_order_shift_name": null,
          "work_order_id": 1648554580575281,
          "work_order_code": "swd578891071",
          "work_order_plan_start_time": 1648396800000,
          "work_order_plan_finish_time": 1648693585000,
          "process_plan_amount": 200.0000000000,
          "process_node_num": "10",
          "process_name": "zzw1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1648554580575298,
          "work_order_shift_name": null,
          "work_order_id": 1648554580575296,
          "work_order_code": "swd1302151289",
          "work_order_plan_start_time": 1648396800000,
          "work_order_plan_finish_time": 1648693585000,
          "process_plan_amount": 200.0000000000,
          "process_node_num": "10",
          "process_name": "zzw1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1648554580575313,
          "work_order_shift_name": null,
          "work_order_id": 1648554580575311,
          "work_order_code": "swd851599046",
          "work_order_plan_start_time": 1648396800000,
          "work_order_plan_finish_time": 1648693585000,
          "process_plan_amount": 200.0000000000,
          "process_node_num": "10",
          "process_name": "zzw1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1648554580575328,
          "work_order_shift_name": null,
          "work_order_id": 1648554580575326,
          "work_order_code": "swd1067535305",
          "work_order_plan_start_time": 1648396800000,
          "work_order_plan_finish_time": 1648693585000,
          "process_plan_amount": 200.0000000000,
          "process_node_num": "10",
          "process_name": "zzw1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1648554580575343,
          "work_order_shift_name": null,
          "work_order_id": 1648554580575341,
          "work_order_code": "swd780298871",
          "work_order_plan_start_time": 1648396800000,
          "work_order_plan_finish_time": 1648693585000,
          "process_plan_amount": 200.0000000000,
          "process_node_num": "10",
          "process_name": "zzw1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1648554580575358,
          "work_order_shift_name": null,
          "work_order_id": 1648554580575356,
          "work_order_code": "swd1365153145",
          "work_order_plan_start_time": 1648396800000,
          "work_order_plan_finish_time": 1648693585000,
          "process_plan_amount": 200.0000000000,
          "process_node_num": "10",
          "process_name": "zzw1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1649855893995053,
          "work_order_shift_name": null,
          "work_order_id": 1649855893995051,
          "work_order_code": "swd414",
          "work_order_plan_start_time": 1649865600000,
          "work_order_plan_finish_time": 1649917994000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "zzw1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1649855893995067,
          "work_order_shift_name": null,
          "work_order_id": 1649855893995065,
          "work_order_code": "swd415",
          "work_order_plan_start_time": 1649865600000,
          "work_order_plan_finish_time": 1649919142000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "zzw1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1650789256762043,
          "work_order_shift_name": null,
          "work_order_id": 1650789256762041,
          "work_order_code": "songwade4251",
          "work_order_plan_start_time": 1650816000000,
          "work_order_plan_finish_time": 1650854805000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "测试工序420"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1650863012246013,
          "work_order_shift_name": null,
          "work_order_id": 1650863012246011,
          "work_order_code": "songwade4252",
          "work_order_plan_start_time": 1650816000000,
          "work_order_plan_finish_time": 1650865800000,
          "process_plan_amount": 1000.0000000000,
          "process_node_num": "10",
          "process_name": "测试工序420"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1651056723038010,
          "work_order_shift_name": null,
          "work_order_id": 1651056723038008,
          "work_order_code": "songwade4277",
          "work_order_plan_start_time": 1650988800000,
          "work_order_plan_finish_time": 1651058815000,
          "process_plan_amount": 10.0000000000,
          "process_node_num": "10",
          "process_name": "cyrcyr001"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1651895096603737,
          "work_order_shift_name": null,
          "work_order_id": 1651895096603735,
          "work_order_code": "zzw6-1",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1653894966000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "灌装工序"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1651895096603738,
          "work_order_shift_name": null,
          "work_order_id": 1651895096603735,
          "work_order_code": "zzw6-1",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1653894966000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "20",
          "process_name": "组装工序"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1651895096603791,
          "work_order_shift_name": null,
          "work_order_id": 1651895096603789,
          "work_order_code": "zzw6-2",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652081231000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "灌装工序"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1651895096603792,
          "work_order_shift_name": null,
          "work_order_id": 1651895096603789,
          "work_order_code": "zzw6-2",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652081231000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "20",
          "process_name": "组装工序"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422000,
          "work_order_shift_name": null,
          "work_order_id": 1652077576423997,
          "work_order_code": "songwd1483438691",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422011,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422009,
          "work_order_code": "songwd1305755003",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422022,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422020,
          "work_order_code": "songwd650337949",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422033,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422031,
          "work_order_code": "songwd427706073",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422044,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422042,
          "work_order_code": "songwd1756177937",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422055,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422053,
          "work_order_code": "songwd1942821107",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422066,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422064,
          "work_order_code": "songwd675519764",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422077,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422075,
          "work_order_code": "songwd1368759591",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422088,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422086,
          "work_order_code": "songwd1884875007",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422099,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422097,
          "work_order_code": "songwd1548251501",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422110,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422108,
          "work_order_code": "songwd999210832",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422121,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422119,
          "work_order_code": "songwd639630338",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422132,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422130,
          "work_order_code": "songwd1319242027",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422143,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422141,
          "work_order_code": "songwd63526774",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422154,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422152,
          "work_order_code": "songwd385492878",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422165,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422163,
          "work_order_code": "songwd1829990394",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422176,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422174,
          "work_order_code": "songwd1621880858",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422187,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422185,
          "work_order_code": "songwd1137006106",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422198,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422196,
          "work_order_code": "songwd689510124",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422209,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422207,
          "work_order_code": "songwd1724857092",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422220,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422218,
          "work_order_code": "songwd74135476",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422231,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422229,
          "work_order_code": "songwd586860472",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422242,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422240,
          "work_order_code": "songwd726365904",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422253,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422251,
          "work_order_code": "songwd127193754",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422264,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422262,
          "work_order_code": "songwd1490315965",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422275,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422273,
          "work_order_code": "songwd1723753967",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422286,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422284,
          "work_order_code": "songwd1043304185",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422297,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422295,
          "work_order_code": "songwd985095679",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422308,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422306,
          "work_order_code": "songwd626791148",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422319,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422317,
          "work_order_code": "songwd1025812148",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422330,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422328,
          "work_order_code": "songwd1869926944",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422341,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422339,
          "work_order_code": "songwd1509267104",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422352,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422350,
          "work_order_code": "songwd1093357226",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422363,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422361,
          "work_order_code": "songwd1080203398",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422374,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422372,
          "work_order_code": "songwd168201034",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422385,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422383,
          "work_order_code": "songwd328076438",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422396,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422394,
          "work_order_code": "songwd589678696",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422407,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422405,
          "work_order_code": "songwd948637624",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422418,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422416,
          "work_order_code": "songwd1843910061",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422429,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422427,
          "work_order_code": "songwd1801187656",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422440,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422438,
          "work_order_code": "songwd43092381",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422451,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422449,
          "work_order_code": "songwd352851693",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422462,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422460,
          "work_order_code": "songwd1762060604",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422473,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422471,
          "work_order_code": "songwd516598318",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422484,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422482,
          "work_order_code": "songwd1115603803",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422495,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422493,
          "work_order_code": "songwd1610462371",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422506,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422504,
          "work_order_code": "songwd1415865809",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422517,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422515,
          "work_order_code": "songwd315657648",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422528,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422526,
          "work_order_code": "songwd664094349",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422539,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422537,
          "work_order_code": "songwd1648506853",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422550,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422548,
          "work_order_code": "songwd164357878",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422561,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422559,
          "work_order_code": "songwd847596589",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422572,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422570,
          "work_order_code": "songwd1246692815",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422583,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422581,
          "work_order_code": "songwd401169956",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422594,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422592,
          "work_order_code": "songwd10865232",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422605,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422603,
          "work_order_code": "songwd40806167",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422616,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422614,
          "work_order_code": "songwd176331498",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422627,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422625,
          "work_order_code": "songwd782418976",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422638,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422636,
          "work_order_code": "songwd1891545769",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422649,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422647,
          "work_order_code": "songwd677787707",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422660,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422658,
          "work_order_code": "songwd1242982891",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422671,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422669,
          "work_order_code": "songwd1568748545",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422682,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422680,
          "work_order_code": "songwd1457516953",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422693,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422691,
          "work_order_code": "songwd606415646",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422704,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422702,
          "work_order_code": "songwd1801755614",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422715,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422713,
          "work_order_code": "songwd2017952386",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422726,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422724,
          "work_order_code": "songwd22847951",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736841566695001,
        "repeatKey": null,
        "data": {
          "org_id": 10375218,
          "process_id": 1652077576422737,
          "work_order_shift_name": null,
          "work_order_id": 1652077576422735,
          "work_order_code": "songwd1429138051",
          "work_order_plan_start_time": 1652025600000,
          "work_order_plan_finish_time": 1652077512000,
          "process_plan_amount": 100.0000000000,
          "process_node_num": "10",
          "process_name": "CP1"
        }
      }
    ]
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


