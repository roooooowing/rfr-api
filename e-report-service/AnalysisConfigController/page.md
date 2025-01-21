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
    "anaExecId": 1737375644184001,
    "totalCount": 100,
    "repeatCount": 0,
    "config": {
      "baseInfo": {
        "anaId": 1737353310593557,
        "code": "ana_1737373434494",
        "name": "测试_mfg_001",
        "status": 1,
        "dataSetId": 1737353008467251
      },
      "conditions": [],
      "timeJobConfig": {
        "execType": 1,
        "times": [
          "10:00"
        ],
        "days": null,
        "weeks": null,
        "months": null,
        "firstTime": null,
        "fixedRate": null,
        "fixedRateUnit": null,
        "maxExecCount": null,
        "stopTime": null,
        "customs": []
      },
      "action": 1,
      "repeatConfig": null,
      "dataSetMeta": {
        "dataSetId": 1737353008467251,
        "dataSetName": "简单测试_MFG"
      }
    },
    "data": [
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "0328zwl001-0328gx001-10",
          "process_id": 1648258514137302,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "0328gd001",
          "work_order_plan_finish_time": 1648703536000,
          "work_order_id": 1648258514137300,
          "process_node_work_center_equipment_ids": "\"[1648253813099226]\"",
          "process_name": "0328工序001",
          "process_main_output_material_main_unit_display": "kg",
          "process_node_num": "10",
          "work_order_plan_start_time": 1648310400000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "0328zwl001",
          "process_id": 1648258514137303,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "0328gd001",
          "work_order_plan_finish_time": 1648703536000,
          "work_order_id": 1648258514137300,
          "process_node_work_center_equipment_ids": "\"[1648253813099238]\"",
          "process_name": "0328工序002",
          "process_main_output_material_main_unit_display": "kg",
          "process_node_num": "20",
          "work_order_plan_start_time": 1648310400000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "zzw1",
          "process_id": 1648258514137337,
          "process_plan_amount": 200.0000000000,
          "work_order_code": "zzw1",
          "work_order_plan_finish_time": 1648693585000,
          "work_order_id": 1648258514137335,
          "process_node_work_center_equipment_ids": "\"[1648253813099130]\"",
          "process_name": "zzw1",
          "process_main_output_material_main_unit_display": "ml",
          "process_node_num": "10",
          "work_order_plan_start_time": 1648396800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "zzw1",
          "process_id": 1648554580575073,
          "process_plan_amount": 200.0000000000,
          "work_order_code": "swd191424454",
          "work_order_plan_finish_time": 1648693585000,
          "work_order_id": 1648554580575071,
          "process_node_work_center_equipment_ids": "\"[1648253813099130]\"",
          "process_name": "zzw1",
          "process_main_output_material_main_unit_display": "ml",
          "process_node_num": "10",
          "work_order_plan_start_time": 1648396800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "zzw1",
          "process_id": 1648554580575088,
          "process_plan_amount": 200.0000000000,
          "work_order_code": "swd727675838",
          "work_order_plan_finish_time": 1648693585000,
          "work_order_id": 1648554580575086,
          "process_node_work_center_equipment_ids": "\"[1648253813099130]\"",
          "process_name": "zzw1",
          "process_main_output_material_main_unit_display": "ml",
          "process_node_num": "10",
          "work_order_plan_start_time": 1648396800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "zzw1",
          "process_id": 1648554580575103,
          "process_plan_amount": 200.0000000000,
          "work_order_code": "swd1347769125",
          "work_order_plan_finish_time": 1648693585000,
          "work_order_id": 1648554580575101,
          "process_node_work_center_equipment_ids": "\"[1648253813099130]\"",
          "process_name": "zzw1",
          "process_main_output_material_main_unit_display": "ml",
          "process_node_num": "10",
          "work_order_plan_start_time": 1648396800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "zzw1",
          "process_id": 1648554580575118,
          "process_plan_amount": 200.0000000000,
          "work_order_code": "swd1683180931",
          "work_order_plan_finish_time": 1648693585000,
          "work_order_id": 1648554580575116,
          "process_node_work_center_equipment_ids": "\"[1648253813099130]\"",
          "process_name": "zzw1",
          "process_main_output_material_main_unit_display": "ml",
          "process_node_num": "10",
          "work_order_plan_start_time": 1648396800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "zzw1",
          "process_id": 1648554580575133,
          "process_plan_amount": 200.0000000000,
          "work_order_code": "swd695959124",
          "work_order_plan_finish_time": 1648693585000,
          "work_order_id": 1648554580575131,
          "process_node_work_center_equipment_ids": "\"[1648253813099130]\"",
          "process_name": "zzw1",
          "process_main_output_material_main_unit_display": "ml",
          "process_node_num": "10",
          "work_order_plan_start_time": 1648396800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "zzw1",
          "process_id": 1648554580575148,
          "process_plan_amount": 200.0000000000,
          "work_order_code": "swd2073559337",
          "work_order_plan_finish_time": 1648693585000,
          "work_order_id": 1648554580575146,
          "process_node_work_center_equipment_ids": "\"[1648253813099130]\"",
          "process_name": "zzw1",
          "process_main_output_material_main_unit_display": "ml",
          "process_node_num": "10",
          "work_order_plan_start_time": 1648396800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "zzw1",
          "process_id": 1648554580575163,
          "process_plan_amount": 200.0000000000,
          "work_order_code": "swd1315804226",
          "work_order_plan_finish_time": 1648693585000,
          "work_order_id": 1648554580575161,
          "process_node_work_center_equipment_ids": "\"[1648253813099130]\"",
          "process_name": "zzw1",
          "process_main_output_material_main_unit_display": "ml",
          "process_node_num": "10",
          "work_order_plan_start_time": 1648396800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "zzw1",
          "process_id": 1648554580575178,
          "process_plan_amount": 200.0000000000,
          "work_order_code": "swd518618911",
          "work_order_plan_finish_time": 1648693585000,
          "work_order_id": 1648554580575176,
          "process_node_work_center_equipment_ids": "\"[1648253813099130]\"",
          "process_name": "zzw1",
          "process_main_output_material_main_unit_display": "ml",
          "process_node_num": "10",
          "work_order_plan_start_time": 1648396800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "zzw1",
          "process_id": 1648554580575193,
          "process_plan_amount": 200.0000000000,
          "work_order_code": "swd2106748588",
          "work_order_plan_finish_time": 1648693585000,
          "work_order_id": 1648554580575191,
          "process_node_work_center_equipment_ids": "\"[1648253813099130]\"",
          "process_name": "zzw1",
          "process_main_output_material_main_unit_display": "ml",
          "process_node_num": "10",
          "work_order_plan_start_time": 1648396800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "zzw1",
          "process_id": 1648554580575208,
          "process_plan_amount": 200.0000000000,
          "work_order_code": "swd353279400",
          "work_order_plan_finish_time": 1648693585000,
          "work_order_id": 1648554580575206,
          "process_node_work_center_equipment_ids": "\"[1648253813099130]\"",
          "process_name": "zzw1",
          "process_main_output_material_main_unit_display": "ml",
          "process_node_num": "10",
          "work_order_plan_start_time": 1648396800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "zzw1",
          "process_id": 1648554580575223,
          "process_plan_amount": 200.0000000000,
          "work_order_code": "swd1680886495",
          "work_order_plan_finish_time": 1648693585000,
          "work_order_id": 1648554580575221,
          "process_node_work_center_equipment_ids": "\"[1648253813099130]\"",
          "process_name": "zzw1",
          "process_main_output_material_main_unit_display": "ml",
          "process_node_num": "10",
          "work_order_plan_start_time": 1648396800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "zzw1",
          "process_id": 1648554580575238,
          "process_plan_amount": 200.0000000000,
          "work_order_code": "swd1077258756",
          "work_order_plan_finish_time": 1648693585000,
          "work_order_id": 1648554580575236,
          "process_node_work_center_equipment_ids": "\"[1648253813099130]\"",
          "process_name": "zzw1",
          "process_main_output_material_main_unit_display": "ml",
          "process_node_num": "10",
          "work_order_plan_start_time": 1648396800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "zzw1",
          "process_id": 1648554580575253,
          "process_plan_amount": 200.0000000000,
          "work_order_code": "swd2009511428",
          "work_order_plan_finish_time": 1648693585000,
          "work_order_id": 1648554580575251,
          "process_node_work_center_equipment_ids": "\"[1648253813099130]\"",
          "process_name": "zzw1",
          "process_main_output_material_main_unit_display": "ml",
          "process_node_num": "10",
          "work_order_plan_start_time": 1648396800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "zzw1",
          "process_id": 1648554580575268,
          "process_plan_amount": 200.0000000000,
          "work_order_code": "swd1720009066",
          "work_order_plan_finish_time": 1648693585000,
          "work_order_id": 1648554580575266,
          "process_node_work_center_equipment_ids": "\"[1648253813099130]\"",
          "process_name": "zzw1",
          "process_main_output_material_main_unit_display": "ml",
          "process_node_num": "10",
          "work_order_plan_start_time": 1648396800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "zzw1",
          "process_id": 1648554580575283,
          "process_plan_amount": 200.0000000000,
          "work_order_code": "swd578891071",
          "work_order_plan_finish_time": 1648693585000,
          "work_order_id": 1648554580575281,
          "process_node_work_center_equipment_ids": "\"[1648253813099130]\"",
          "process_name": "zzw1",
          "process_main_output_material_main_unit_display": "ml",
          "process_node_num": "10",
          "work_order_plan_start_time": 1648396800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "zzw1",
          "process_id": 1648554580575298,
          "process_plan_amount": 200.0000000000,
          "work_order_code": "swd1302151289",
          "work_order_plan_finish_time": 1648693585000,
          "work_order_id": 1648554580575296,
          "process_node_work_center_equipment_ids": "\"[1648253813099130]\"",
          "process_name": "zzw1",
          "process_main_output_material_main_unit_display": "ml",
          "process_node_num": "10",
          "work_order_plan_start_time": 1648396800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "zzw1",
          "process_id": 1648554580575313,
          "process_plan_amount": 200.0000000000,
          "work_order_code": "swd851599046",
          "work_order_plan_finish_time": 1648693585000,
          "work_order_id": 1648554580575311,
          "process_node_work_center_equipment_ids": "\"[1648253813099130]\"",
          "process_name": "zzw1",
          "process_main_output_material_main_unit_display": "ml",
          "process_node_num": "10",
          "work_order_plan_start_time": 1648396800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "zzw1",
          "process_id": 1648554580575328,
          "process_plan_amount": 200.0000000000,
          "work_order_code": "swd1067535305",
          "work_order_plan_finish_time": 1648693585000,
          "work_order_id": 1648554580575326,
          "process_node_work_center_equipment_ids": "\"[1648253813099130]\"",
          "process_name": "zzw1",
          "process_main_output_material_main_unit_display": "ml",
          "process_node_num": "10",
          "work_order_plan_start_time": 1648396800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "zzw1",
          "process_id": 1648554580575343,
          "process_plan_amount": 200.0000000000,
          "work_order_code": "swd780298871",
          "work_order_plan_finish_time": 1648693585000,
          "work_order_id": 1648554580575341,
          "process_node_work_center_equipment_ids": "\"[1648253813099130]\"",
          "process_name": "zzw1",
          "process_main_output_material_main_unit_display": "ml",
          "process_node_num": "10",
          "work_order_plan_start_time": 1648396800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "zzw1",
          "process_id": 1648554580575358,
          "process_plan_amount": 200.0000000000,
          "work_order_code": "swd1365153145",
          "work_order_plan_finish_time": 1648693585000,
          "work_order_id": 1648554580575356,
          "process_node_work_center_equipment_ids": "\"[1648253813099130]\"",
          "process_name": "zzw1",
          "process_main_output_material_main_unit_display": "ml",
          "process_node_num": "10",
          "work_order_plan_start_time": 1648396800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd003",
          "process_id": 1649855893995053,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "swd414",
          "work_order_plan_finish_time": 1649917994000,
          "work_order_id": 1649855893995051,
          "process_node_work_center_equipment_ids": "\"[1648253813099130]\"",
          "process_name": "zzw1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1649865600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd003",
          "process_id": 1649855893995067,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "swd415",
          "work_order_plan_finish_time": 1649919142000,
          "work_order_id": 1649855893995065,
          "process_node_work_center_equipment_ids": "\"[1648253813099130]\"",
          "process_name": "zzw1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1649865600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "CA00000020",
          "process_id": 1650789256762043,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwade4251",
          "work_order_plan_finish_time": 1650854805000,
          "work_order_id": 1650789256762041,
          "process_node_work_center_equipment_ids": "\"[1648253813099130]\"",
          "process_name": "测试工序420",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1650816000000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "CA00000020",
          "process_id": 1650863012246013,
          "process_plan_amount": 1000.0000000000,
          "work_order_code": "songwade4252",
          "work_order_plan_finish_time": 1650865800000,
          "work_order_id": 1650863012246011,
          "process_node_work_center_equipment_ids": "\"[1648253813099130]\"",
          "process_name": "测试工序420",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1650816000000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "CA00000020",
          "process_id": 1651056723038010,
          "process_plan_amount": 10.0000000000,
          "work_order_code": "songwade4277",
          "work_order_plan_finish_time": 1651058815000,
          "work_order_id": 1651056723038008,
          "process_node_work_center_equipment_ids": "\"[1648253813099130]\"",
          "process_name": "cyrcyr001",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1650988800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "zzw6-gzgx-10",
          "process_id": 1651895096603737,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "zzw6-1",
          "work_order_plan_finish_time": 1653894966000,
          "work_order_id": 1651895096603735,
          "process_node_work_center_equipment_ids": "\"[1648253813099130]\"",
          "process_name": "灌装工序",
          "process_main_output_material_main_unit_display": "CAR",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "13010000004",
          "process_id": 1651895096603738,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "zzw6-1",
          "work_order_plan_finish_time": 1653894966000,
          "work_order_id": 1651895096603735,
          "process_node_work_center_equipment_ids": "\"[1648253813099130]\"",
          "process_name": "组装工序",
          "process_main_output_material_main_unit_display": "CAR",
          "process_node_num": "20",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "zzw6-gzgx-10",
          "process_id": 1651895096603791,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "zzw6-2",
          "work_order_plan_finish_time": 1652081231000,
          "work_order_id": 1651895096603789,
          "process_node_work_center_equipment_ids": "\"[1648253813099130]\"",
          "process_name": "灌装工序",
          "process_main_output_material_main_unit_display": "CAR",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "13010000004",
          "process_id": 1651895096603792,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "zzw6-2",
          "work_order_plan_finish_time": 1652081231000,
          "work_order_id": 1651895096603789,
          "process_node_work_center_equipment_ids": "\"[1648253813099130]\"",
          "process_name": "组装工序",
          "process_main_output_material_main_unit_display": "CAR",
          "process_node_num": "20",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422000,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd1483438691",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576423997,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422011,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd1305755003",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422009,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422022,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd650337949",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422020,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422033,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd427706073",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422031,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422044,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd1756177937",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422042,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422055,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd1942821107",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422053,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422066,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd675519764",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422064,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422077,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd1368759591",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422075,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422088,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd1884875007",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422086,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422099,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd1548251501",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422097,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422110,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd999210832",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422108,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422121,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd639630338",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422119,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422132,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd1319242027",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422130,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422143,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd63526774",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422141,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422154,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd385492878",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422152,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422165,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd1829990394",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422163,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422176,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd1621880858",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422174,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422187,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd1137006106",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422185,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422198,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd689510124",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422196,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422209,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd1724857092",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422207,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422220,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd74135476",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422218,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422231,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd586860472",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422229,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422242,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd726365904",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422240,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422253,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd127193754",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422251,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422264,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd1490315965",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422262,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422275,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd1723753967",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422273,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422286,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd1043304185",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422284,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422297,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd985095679",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422295,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422308,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd626791148",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422306,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422319,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd1025812148",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422317,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422330,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd1869926944",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422328,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422341,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd1509267104",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422339,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422352,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd1093357226",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422350,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422363,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd1080203398",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422361,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422374,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd168201034",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422372,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422385,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd328076438",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422383,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422396,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd589678696",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422394,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422407,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd948637624",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422405,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422418,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd1843910061",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422416,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422429,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd1801187656",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422427,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422440,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd43092381",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422438,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422451,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd352851693",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422449,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422462,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd1762060604",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422460,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422473,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd516598318",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422471,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422484,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd1115603803",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422482,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422495,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd1610462371",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422493,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422506,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd1415865809",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422504,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422517,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd315657648",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422515,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422528,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd664094349",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422526,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422539,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd1648506853",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422537,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422550,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd164357878",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422548,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422561,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd847596589",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422559,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422572,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd1246692815",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422570,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422583,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd401169956",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422581,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422594,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd10865232",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422592,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422605,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd40806167",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422603,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422616,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd176331498",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422614,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422627,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd782418976",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422625,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422638,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd1891545769",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422636,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422649,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd677787707",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422647,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422660,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd1242982891",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422658,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422671,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd1568748545",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422669,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422682,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd1457516953",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422680,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422693,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd606415646",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422691,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422704,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd1801755614",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422702,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422715,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd2017952386",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422713,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422726,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd22847951",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422724,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737375644184001,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "swd001",
          "process_id": 1652077576422737,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "songwd1429138051",
          "work_order_plan_finish_time": 1652077512000,
          "work_order_id": 1652077576422735,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "CP1",
          "process_main_output_material_main_unit_display": "千克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652025600000
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
		"createdAt":"创建时间",
		"code":"编号",
		"dataSetId":"数据集ID",
		"anaId":"ID",
		"dataSetName":"数据集名称",
		"name":"名称",
		"action":"后续动作",
		"execType":"执行频率类型：1每日；2每周；3每月；4每年；5固定周期；6自定义；7每小时",
		"status":"状态 0-未启用 1-启用",
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


