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
  "anaId": 1,
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
{
  "code": 200,
  "data": {
    "list": [
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736584998229005,
        "repeatKey": null,
        "data": {
          "process_id": 1651819181714076,
          "process_plan_amount": 100.0,
          "work_order_code": "2022-05-06-001",
          "work_order_plan_finish_time": 1651908785000,
          "work_order_id": 1651819181714074,
          "org_id": 10896962,
          "process_name": "工序-001",
          "work_order_shift_name": null,
          "process_node_num": "10",
          "work_order_plan_start_time": 1651766400000
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736584998229005,
        "repeatKey": null,
        "data": {
          "process_id": 1651819181714077,
          "process_plan_amount": 100.0,
          "work_order_code": "2022-05-06-001",
          "work_order_plan_finish_time": 1651908785000,
          "work_order_id": 1651819181714074,
          "org_id": 10896962,
          "process_name": "工序-002",
          "work_order_shift_name": null,
          "process_node_num": "20",
          "work_order_plan_start_time": 1651766400000
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736584998229005,
        "repeatKey": null,
        "data": {
          "process_id": 1653455535160113,
          "process_plan_amount": 10.0,
          "work_order_code": "2022-05-25-004",
          "work_order_plan_finish_time": 1653476144000,
          "work_order_id": 1653455535160111,
          "org_id": 10896962,
          "process_name": "工序-001",
          "work_order_shift_name": null,
          "process_node_num": "10",
          "work_order_plan_start_time": 1653408000000
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736584998229005,
        "repeatKey": null,
        "data": {
          "process_id": 1653455535160114,
          "process_plan_amount": 10.0,
          "work_order_code": "2022-05-25-004",
          "work_order_plan_finish_time": 1653476144000,
          "work_order_id": 1653455535160111,
          "org_id": 10896962,
          "process_name": "工序-002",
          "work_order_shift_name": null,
          "process_node_num": "20",
          "work_order_plan_start_time": 1653408000000
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736584998229005,
        "repeatKey": null,
        "data": {
          "process_id": 1653462936403025,
          "process_plan_amount": 10.0,
          "work_order_code": "2022-05-25-005",
          "work_order_plan_finish_time": 1653479167000,
          "work_order_id": 1653462936403023,
          "org_id": 10896962,
          "process_name": "工序-001",
          "work_order_shift_name": null,
          "process_node_num": "10",
          "work_order_plan_start_time": 1653408000000
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736584998229005,
        "repeatKey": null,
        "data": {
          "process_id": 1653462936403026,
          "process_plan_amount": 10.0,
          "work_order_code": "2022-05-25-005",
          "work_order_plan_finish_time": 1653479167000,
          "work_order_id": 1653462936403023,
          "org_id": 10896962,
          "process_name": "工序-002",
          "work_order_shift_name": null,
          "process_node_num": "20",
          "work_order_plan_start_time": 1653408000000
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736584998229005,
        "repeatKey": null,
        "data": {
          "process_id": 1653462936403070,
          "process_plan_amount": 10.0,
          "work_order_code": "2022-05-25-008",
          "work_order_plan_finish_time": 1653482923000,
          "work_order_id": 1653462936403068,
          "org_id": 10896962,
          "process_name": "工序-001",
          "work_order_shift_name": null,
          "process_node_num": "10",
          "work_order_plan_start_time": 1653408000000
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736584998229005,
        "repeatKey": null,
        "data": {
          "process_id": 1653462936403071,
          "process_plan_amount": 10.0,
          "work_order_code": "2022-05-25-008",
          "work_order_plan_finish_time": 1653482923000,
          "work_order_id": 1653462936403068,
          "org_id": 10896962,
          "process_name": "工序-002",
          "work_order_shift_name": null,
          "process_node_num": "20",
          "work_order_plan_start_time": 1653408000000
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736584998229005,
        "repeatKey": null,
        "data": {
          "process_id": 1653463993111028,
          "process_plan_amount": 10.0,
          "work_order_code": "2022-05-25-006",
          "work_order_plan_finish_time": 1653482923000,
          "work_order_id": 1653463993111026,
          "org_id": 10896962,
          "process_name": "工序-001",
          "work_order_shift_name": null,
          "process_node_num": "10",
          "work_order_plan_start_time": 1653408000000
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736584998229005,
        "repeatKey": null,
        "data": {
          "process_id": 1653463993111029,
          "process_plan_amount": 10.0,
          "work_order_code": "2022-05-25-006",
          "work_order_plan_finish_time": 1653482923000,
          "work_order_id": 1653463993111026,
          "org_id": 10896962,
          "process_name": "工序-002",
          "work_order_shift_name": null,
          "process_node_num": "20",
          "work_order_plan_start_time": 1653408000000
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736584998229005,
        "repeatKey": null,
        "data": {
          "process_id": 1653463993111408,
          "process_plan_amount": 10.0,
          "work_order_code": "2022-05-26-001",
          "work_order_plan_finish_time": 1653552675000,
          "work_order_id": 1653463993111406,
          "org_id": 10896962,
          "process_name": "工序-001",
          "work_order_shift_name": null,
          "process_node_num": "10",
          "work_order_plan_start_time": 1653494400000
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736584998229005,
        "repeatKey": null,
        "data": {
          "process_id": 1653463993111409,
          "process_plan_amount": 10.0,
          "work_order_code": "2022-05-26-001",
          "work_order_plan_finish_time": 1653552675000,
          "work_order_id": 1653463993111406,
          "org_id": 10896962,
          "process_name": "工序-002",
          "work_order_shift_name": null,
          "process_node_num": "20",
          "work_order_plan_start_time": 1653494400000
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736584998229005,
        "repeatKey": null,
        "data": {
          "process_id": 1653463993111485,
          "process_plan_amount": 10.0,
          "work_order_code": "2022-05-26-002",
          "work_order_plan_finish_time": 1653550499000,
          "work_order_id": 1653463993111483,
          "org_id": 10896962,
          "process_name": "工序-001",
          "work_order_shift_name": null,
          "process_node_num": "10",
          "work_order_plan_start_time": 1653494400000
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736584998229005,
        "repeatKey": null,
        "data": {
          "process_id": 1653463993111486,
          "process_plan_amount": 10.0,
          "work_order_code": "2022-05-26-002",
          "work_order_plan_finish_time": 1653550499000,
          "work_order_id": 1653463993111483,
          "org_id": 10896962,
          "process_name": "工序-002",
          "work_order_shift_name": null,
          "process_node_num": "20",
          "work_order_plan_start_time": 1653494400000
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736584998229005,
        "repeatKey": null,
        "data": {
          "process_id": 1654049715993002,
          "process_plan_amount": 10.0,
          "work_order_code": "2022-06-01-001",
          "work_order_plan_finish_time": 1654066756000,
          "work_order_id": 1654049715993000,
          "org_id": 10896962,
          "process_name": "工序-001",
          "work_order_shift_name": null,
          "process_node_num": "10",
          "work_order_plan_start_time": 1654012800000
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736584998229005,
        "repeatKey": null,
        "data": {
          "process_id": 1654049715993003,
          "process_plan_amount": 10.0,
          "work_order_code": "2022-06-01-001",
          "work_order_plan_finish_time": 1654066756000,
          "work_order_id": 1654049715993000,
          "org_id": 10896962,
          "process_name": "工序-002",
          "work_order_shift_name": null,
          "process_node_num": "20",
          "work_order_plan_start_time": 1654012800000
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736584998229005,
        "repeatKey": null,
        "data": {
          "process_id": 1654049715993140,
          "process_plan_amount": 10.0,
          "work_order_code": "2022-05-25-100000",
          "work_order_plan_finish_time": 1654071786000,
          "work_order_id": 1654049715993138,
          "org_id": 10896962,
          "process_name": "工序-001",
          "work_order_shift_name": null,
          "process_node_num": "10",
          "work_order_plan_start_time": 1654012800000
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736584998229005,
        "repeatKey": null,
        "data": {
          "process_id": 1654049715993141,
          "process_plan_amount": 10.0,
          "work_order_code": "2022-05-25-100000",
          "work_order_plan_finish_time": 1654071786000,
          "work_order_id": 1654049715993138,
          "org_id": 10896962,
          "process_name": "工序-002",
          "work_order_shift_name": null,
          "process_node_num": "20",
          "work_order_plan_start_time": 1654012800000
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736584998229005,
        "repeatKey": null,
        "data": {
          "process_id": 1654049715993323,
          "process_plan_amount": 5.999999,
          "work_order_code": "2022-05-25-100001",
          "work_order_plan_finish_time": 1654072353000,
          "work_order_id": 1654049715993321,
          "org_id": 10896962,
          "process_name": "工序-001",
          "work_order_shift_name": null,
          "process_node_num": "10",
          "work_order_plan_start_time": 1654012800000
        }
      },
      {
        "anaId": 1736577089298009,
        "anaExecId": 1736584998229005,
        "repeatKey": null,
        "data": {
          "process_id": 1654049715993324,
          "process_plan_amount": 5.999999,
          "work_order_code": "2022-05-25-100001",
          "work_order_plan_finish_time": 1654072353000,
          "work_order_id": 1654049715993321,
          "org_id": 10896962,
          "process_name": "工序-002",
          "work_order_shift_name": null,
          "process_node_num": "20",
          "work_order_plan_start_time": 1654012800000
        }
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


