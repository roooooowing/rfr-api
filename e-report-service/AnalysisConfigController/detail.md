# detail

### Method description

```
详情
```

> URL: http://e-report-domain-feature.test.blacklake.tech/web/v1/analysis/config/detail
>
> Origin Url: http://e-report-domain-feature.test.blacklake.tech/web/v1/analysis/config/detail
>
> Type: POST


### Request headers

|Header Name| Header Value|
|---------|------|
|x-org-id|10855487|
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
  "anaId": 1737045480332840
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
      "anaId": 1737045480332840,
      "code": "ana_1737079894155",
      "name": "t4告警",
      "status": 0,
      "dataSetId": 1705433981406613
    },
    "actions": [
      1
    ],
    "dataSetMeta": {
      "dataSetId": 1705433981406613,
      "displayFields": [
        {
          "fieldCode": "work_order_code",
          "fieldName": "工单编号",
          "fieldType": 1
        },
        {
          "fieldCode": "work_order_type_display",
          "fieldName": "工单类型（目前只有普通）",
          "fieldType": 1
        },
        {
          "fieldCode": "work_order_status_display",
          "fieldName": "业务状态",
          "fieldType": 1
        },
        {
          "fieldCode": "work_order_is_pause_display",
          "fieldName": "工单暂停状态",
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
          "fieldCode": "process_node_work_center_equipment_names",
          "fieldName": "工序工作中心设备列表",
          "fieldType": 1
        },
        {
          "fieldCode": "work_order_shift_name",
          "fieldName": "工单班次名",
          "fieldType": 1
        },
        {
          "fieldCode": "work_order_production_dpt_display",
          "fieldName": "生产部门",
          "fieldType": 1
        },
        {
          "fieldCode": "work_order_production_supervisor_display",
          "fieldName": "生产主管",
          "fieldType": 1
        },
        {
          "fieldCode": "work_order_output_material_code",
          "fieldName": "工单主产出物料编号",
          "fieldType": 1
        },
        {
          "fieldCode": "work_order_output_material_name",
          "fieldName": "工单主产出物料名称",
          "fieldType": 1
        },
        {
          "fieldCode": "work_order_output_material_specification",
          "fieldName": "工单主产出物料规格",
          "fieldType": 1
        },
        {
          "fieldCode": "work_order_output_material_category_name",
          "fieldName": "工单主产出分类名称",
          "fieldType": 1
        },
        {
          "fieldCode": "work_order_output_material_main_unit_display",
          "fieldName": "工单主产出物料主单位",
          "fieldType": 1
        },
        {
          "fieldCode": "work_order_plan_main_unit_amount",
          "fieldName": "工单计划数（主单位）",
          "fieldType": 2
        },
        {
          "fieldCode": "work_order_output_material_process_route_code",
          "fieldName": "工单主产出关联工艺路线编号",
          "fieldType": 1
        },
        {
          "fieldCode": "process_node_seq",
          "fieldName": "工单工序顺序号",
          "fieldType": 2
        },
        {
          "fieldCode": "process_node_num",
          "fieldName": "工单工序号",
          "fieldType": 1
        },
        {
          "fieldCode": "process_code",
          "fieldName": "工序编号",
          "fieldType": 1
        },
        {
          "fieldCode": "process_name",
          "fieldName": "工单工序名称",
          "fieldType": 1
        },
        {
          "fieldCode": "process_is_last_display",
          "fieldName": "是否为最后一道工序",
          "fieldType": 1
        },
        {
          "fieldCode": "process_node_work_center_name",
          "fieldName": "工序工作中心名",
          "fieldType": 1
        },
        {
          "fieldCode": "process_main_output_material_code",
          "fieldName": "工序主产出物料编号",
          "fieldType": 1
        },
        {
          "fieldCode": "process_main_output_material_name",
          "fieldName": "工序主产出物料名称",
          "fieldType": 1
        },
        {
          "fieldCode": "process_main_output_material_specification",
          "fieldName": "工序主产出物料规格",
          "fieldType": 1
        },
        {
          "fieldCode": "process_main_output_material_main_unit_display",
          "fieldName": "工序主产出主单位展示",
          "fieldType": 1
        },
        {
          "fieldCode": "process_plan_amount",
          "fieldName": "工序计划数",
          "fieldType": 2
        },
        {
          "fieldCode": "process_report_amount",
          "fieldName": "工序总报工数",
          "fieldType": 2
        },
        {
          "fieldCode": "process_qualified_report_amount",
          "fieldName": "工序合格报工数",
          "fieldType": 2
        },
        {
          "fieldCode": "process_unqualified_report_amount",
          "fieldName": "工序总报工数",
          "fieldType": 2
        },
        {
          "fieldCode": "process_plan_amount_unit_display",
          "fieldName": "工序单位展示",
          "fieldType": 1
        },
        {
          "fieldCode": "process_jindu",
          "fieldName": "工序报工进度",
          "fieldType": 2
        },
        {
          "fieldCode": "process_hg",
          "fieldName": "工序合格率",
          "fieldType": 2
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


