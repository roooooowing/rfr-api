# trigger

### Method description

```
手动触发
```

> URL: http://e-report-domain-feature.test.blacklake.tech/web/v1/analysis/exec/trigger
>
> Origin Url: http://e-report-domain-feature.test.blacklake.tech/web/v1/analysis/exec/trigger
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
  "anaId": 1737353310593557
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
    "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "ZZWL-001-GX-001-10",
          "process_id": 1651819181714076,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "2022-05-06-001",
          "work_order_plan_finish_time": 1651908785000,
          "work_order_id": 1651819181714074,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "工序-001",
          "process_main_output_material_main_unit_display": "张",
          "process_node_num": "10",
          "work_order_plan_start_time": 1651766400000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737435473317097,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "ZZWL-001",
          "process_id": 1651819181714077,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "2022-05-06-001",
          "work_order_plan_finish_time": 1651908785000,
          "work_order_id": 1651819181714074,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "工序-002",
          "process_main_output_material_main_unit_display": "张",
          "process_node_num": "20",
          "work_order_plan_start_time": 1651766400000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737435473317097,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "ZZWL-001-GX-001-10",
          "process_id": 1653455535160113,
          "process_plan_amount": 10.0000000000,
          "work_order_code": "2022-05-25-004",
          "work_order_plan_finish_time": 1653476144000,
          "work_order_id": 1653455535160111,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "工序-001",
          "process_main_output_material_main_unit_display": "张",
          "process_node_num": "10",
          "work_order_plan_start_time": 1653408000000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737435473317097,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "ZZWL-001",
          "process_id": 1653455535160114,
          "process_plan_amount": 10.0000000000,
          "work_order_code": "2022-05-25-004",
          "work_order_plan_finish_time": 1653476144000,
          "work_order_id": 1653455535160111,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "工序-002",
          "process_main_output_material_main_unit_display": "张",
          "process_node_num": "20",
          "work_order_plan_start_time": 1653408000000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737435473317097,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "ZZWL-001-GX-001-10",
          "process_id": 1653462936403025,
          "process_plan_amount": 10.0000000000,
          "work_order_code": "2022-05-25-005",
          "work_order_plan_finish_time": 1653479167000,
          "work_order_id": 1653462936403023,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "工序-001",
          "process_main_output_material_main_unit_display": "张",
          "process_node_num": "10",
          "work_order_plan_start_time": 1653408000000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737435473317097,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "ZZWL-001",
          "process_id": 1653462936403026,
          "process_plan_amount": 10.0000000000,
          "work_order_code": "2022-05-25-005",
          "work_order_plan_finish_time": 1653479167000,
          "work_order_id": 1653462936403023,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "工序-002",
          "process_main_output_material_main_unit_display": "张",
          "process_node_num": "20",
          "work_order_plan_start_time": 1653408000000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737435473317097,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "ZZWL-001-GX-001-10",
          "process_id": 1653462936403070,
          "process_plan_amount": 10.0000000000,
          "work_order_code": "2022-05-25-008",
          "work_order_plan_finish_time": 1653482923000,
          "work_order_id": 1653462936403068,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "工序-001",
          "process_main_output_material_main_unit_display": "张",
          "process_node_num": "10",
          "work_order_plan_start_time": 1653408000000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737435473317097,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "ZZWL-001",
          "process_id": 1653462936403071,
          "process_plan_amount": 10.0000000000,
          "work_order_code": "2022-05-25-008",
          "work_order_plan_finish_time": 1653482923000,
          "work_order_id": 1653462936403068,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "工序-002",
          "process_main_output_material_main_unit_display": "张",
          "process_node_num": "20",
          "work_order_plan_start_time": 1653408000000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737435473317097,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "ZZWL-001-GX-001-10",
          "process_id": 1653463993111028,
          "process_plan_amount": 10.0000000000,
          "work_order_code": "2022-05-25-006",
          "work_order_plan_finish_time": 1653482923000,
          "work_order_id": 1653463993111026,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "工序-001",
          "process_main_output_material_main_unit_display": "张",
          "process_node_num": "10",
          "work_order_plan_start_time": 1653408000000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737435473317097,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "ZZWL-001",
          "process_id": 1653463993111029,
          "process_plan_amount": 10.0000000000,
          "work_order_code": "2022-05-25-006",
          "work_order_plan_finish_time": 1653482923000,
          "work_order_id": 1653463993111026,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "工序-002",
          "process_main_output_material_main_unit_display": "张",
          "process_node_num": "20",
          "work_order_plan_start_time": 1653408000000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737435473317097,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "ZZWL-001-GX-001-10",
          "process_id": 1653463993111408,
          "process_plan_amount": 10.0000000000,
          "work_order_code": "2022-05-26-001",
          "work_order_plan_finish_time": 1653552675000,
          "work_order_id": 1653463993111406,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "工序-001",
          "process_main_output_material_main_unit_display": "张",
          "process_node_num": "10",
          "work_order_plan_start_time": 1653494400000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737435473317097,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "ZZWL-001",
          "process_id": 1653463993111409,
          "process_plan_amount": 10.0000000000,
          "work_order_code": "2022-05-26-001",
          "work_order_plan_finish_time": 1653552675000,
          "work_order_id": 1653463993111406,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "工序-002",
          "process_main_output_material_main_unit_display": "张",
          "process_node_num": "20",
          "work_order_plan_start_time": 1653494400000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737435473317097,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "ZZWL-001-GX-001-10",
          "process_id": 1653463993111485,
          "process_plan_amount": 10.0000000000,
          "work_order_code": "2022-05-26-002",
          "work_order_plan_finish_time": 1653550499000,
          "work_order_id": 1653463993111483,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "工序-001",
          "process_main_output_material_main_unit_display": "张",
          "process_node_num": "10",
          "work_order_plan_start_time": 1653494400000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737435473317097,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "ZZWL-001",
          "process_id": 1653463993111486,
          "process_plan_amount": 10.0000000000,
          "work_order_code": "2022-05-26-002",
          "work_order_plan_finish_time": 1653550499000,
          "work_order_id": 1653463993111483,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "工序-002",
          "process_main_output_material_main_unit_display": "张",
          "process_node_num": "20",
          "work_order_plan_start_time": 1653494400000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737435473317097,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "ZZWL-001-GX-001-10",
          "process_id": 1654049715993002,
          "process_plan_amount": 10.0000000000,
          "work_order_code": "2022-06-01-001",
          "work_order_plan_finish_time": 1654066756000,
          "work_order_id": 1654049715993000,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "工序-001",
          "process_main_output_material_main_unit_display": "张",
          "process_node_num": "10",
          "work_order_plan_start_time": 1654012800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737435473317097,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "ZZWL-001",
          "process_id": 1654049715993003,
          "process_plan_amount": 10.0000000000,
          "work_order_code": "2022-06-01-001",
          "work_order_plan_finish_time": 1654066756000,
          "work_order_id": 1654049715993000,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "工序-002",
          "process_main_output_material_main_unit_display": "张",
          "process_node_num": "20",
          "work_order_plan_start_time": 1654012800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737435473317097,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "ZZWL-001-GX-001-10",
          "process_id": 1654049715993140,
          "process_plan_amount": 10.0000000000,
          "work_order_code": "2022-05-25-100000",
          "work_order_plan_finish_time": 1654071786000,
          "work_order_id": 1654049715993138,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "工序-001",
          "process_main_output_material_main_unit_display": "张",
          "process_node_num": "10",
          "work_order_plan_start_time": 1654012800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737435473317097,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "ZZWL-001",
          "process_id": 1654049715993141,
          "process_plan_amount": 10.0000000000,
          "work_order_code": "2022-05-25-100000",
          "work_order_plan_finish_time": 1654071786000,
          "work_order_id": 1654049715993138,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "工序-002",
          "process_main_output_material_main_unit_display": "张",
          "process_node_num": "20",
          "work_order_plan_start_time": 1654012800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737435473317097,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "ZZWL-001-GX-001-10",
          "process_id": 1654049715993323,
          "process_plan_amount": 5.9999990000,
          "work_order_code": "2022-05-25-100001",
          "work_order_plan_finish_time": 1654072353000,
          "work_order_id": 1654049715993321,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "工序-001",
          "process_main_output_material_main_unit_display": "张",
          "process_node_num": "10",
          "work_order_plan_start_time": 1654012800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737435473317097,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "ZZWL-001",
          "process_id": 1654049715993324,
          "process_plan_amount": 5.9999990000,
          "work_order_code": "2022-05-25-100001",
          "work_order_plan_finish_time": 1654072353000,
          "work_order_id": 1654049715993321,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "工序-002",
          "process_main_output_material_main_unit_display": "张",
          "process_node_num": "20",
          "work_order_plan_start_time": 1654012800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737435473317097,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "ZZWL-001",
          "process_id": 1655391354179110,
          "process_plan_amount": 4.0000000000,
          "work_order_code": "2022-06-17-0050-018",
          "work_order_plan_finish_time": 1655296220000,
          "work_order_id": 1655388383503678,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "工序-002",
          "process_main_output_material_main_unit_display": "张",
          "process_node_num": "20",
          "work_order_plan_start_time": 1655226061000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737435473317097,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "MA00000012-2022_06_07596-10",
          "process_id": 1656330045481516,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "2022-06-28-002",
          "work_order_plan_finish_time": 1656425067000,
          "work_order_id": 1656330045481514,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "汉字2022_06_07418",
          "process_main_output_material_main_unit_display": "测试单位精度1",
          "process_node_num": "10",
          "work_order_plan_start_time": 1656345600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737435473317097,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "MA00000012",
          "process_id": 1656330045481517,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "2022-06-28-002",
          "work_order_plan_finish_time": 1656425067000,
          "work_order_id": 1656330045481514,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "汉字2022_06_07_1654590755368",
          "process_main_output_material_main_unit_display": "测试单位精度1",
          "process_node_num": "20",
          "work_order_plan_start_time": 1656345600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737435473317097,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "MA00000012-2022_06_07code420-10",
          "process_id": 1656330045481631,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "2022-06-28-003",
          "work_order_plan_finish_time": 1656428816000,
          "work_order_id": 1656330045481629,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "汉字2022_06_07name403",
          "process_main_output_material_main_unit_display": "测试单位精度1",
          "process_node_num": "10",
          "work_order_plan_start_time": 1656345600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737435473317097,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "MA00000012-2022_06_07code347-20",
          "process_id": 1656330045481632,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "2022-06-28-003",
          "work_order_plan_finish_time": 1656428816000,
          "work_order_id": 1656330045481629,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "汉字2022_06_07name900",
          "process_main_output_material_main_unit_display": "测试单位精度1",
          "process_node_num": "20",
          "work_order_plan_start_time": 1656345600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737435473317097,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "MA00000012",
          "process_id": 1656330045481633,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "2022-06-28-003",
          "work_order_plan_finish_time": 1656428816000,
          "work_order_id": 1656330045481629,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "汉字2022_06_07_1654590755368",
          "process_main_output_material_main_unit_display": "测试单位精度1",
          "process_node_num": "30",
          "work_order_plan_start_time": 1656345600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737435473317097,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "wlZ",
          "process_id": 1660197404137184,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "2022081100000",
          "work_order_plan_finish_time": 1660291820000,
          "work_order_id": 1660197404137182,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "zzw1pp",
          "process_main_output_material_main_unit_display": "克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1660147200000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737435473317097,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "snr",
          "process_id": 1660285847984155,
          "process_plan_amount": 150.0000000000,
          "work_order_code": "2022081200001",
          "work_order_plan_finish_time": 1660722677000,
          "work_order_id": 1660285847984153,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "zzw1pp",
          "process_main_output_material_main_unit_display": "克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1660233600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737435473317097,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "ZZWL-001-GX-001-10",
          "process_id": 1660883003878046,
          "process_plan_amount": 20.0000000000,
          "work_order_code": "csrz-0012",
          "work_order_plan_finish_time": 1661583477000,
          "work_order_id": 1660883003878044,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "工序-001",
          "process_main_output_material_main_unit_display": "张",
          "process_node_num": "10",
          "work_order_plan_start_time": 1660842061000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737435473317097,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "ZZWL-001",
          "process_id": 1660883003878047,
          "process_plan_amount": 20.0000000000,
          "work_order_code": "csrz-0012",
          "work_order_plan_finish_time": 1661583477000,
          "work_order_id": 1660883003878044,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "工序-002",
          "process_main_output_material_main_unit_display": "张",
          "process_node_num": "20",
          "work_order_plan_start_time": 1660842061000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737435473317097,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "BCP0811-003",
          "process_id": 1660899161453101,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "2022082000006",
          "work_order_plan_finish_time": 1661238696000,
          "work_order_id": 1660899161453099,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "工序_011",
          "process_main_output_material_main_unit_display": "卷",
          "process_node_num": "10",
          "work_order_plan_start_time": 1660924800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737435473317097,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "wl05",
          "process_id": 1661218007722068,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "2022082300001",
          "work_order_plan_finish_time": 1661222773000,
          "work_order_id": 1661218007722066,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "zzw1pp",
          "process_main_output_material_main_unit_display": "克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1661184000000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737435473317097,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "wl07",
          "process_id": 1662709423693153,
          "process_plan_amount": 321.0000000000,
          "work_order_code": "22090062wl07",
          "work_order_plan_finish_time": 1662713153000,
          "work_order_id": 1662709423693151,
          "process_node_work_center_equipment_ids": "\"[1661246786110871]\"",
          "process_name": "zzw1pp",
          "process_main_output_material_main_unit_display": "克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1662652800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737435473317097,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "wl07",
          "process_id": 1663853590049043,
          "process_plan_amount": 321.0000000000,
          "work_order_code": "2209006awl07",
          "work_order_plan_finish_time": 1662713153000,
          "work_order_id": 1663853590049041,
          "process_node_work_center_equipment_ids": "\"[1661246786110871]\"",
          "process_name": "zzw1pp",
          "process_main_output_material_main_unit_display": "克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1662652800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737435473317097,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "wl07",
          "process_id": 1663853590049073,
          "process_plan_amount": 321.0000000000,
          "work_order_code": "2209006bwl07",
          "work_order_plan_finish_time": 1662713153000,
          "work_order_id": 1663853590049071,
          "process_node_work_center_equipment_ids": "\"[1661246786110871]\"",
          "process_name": "zzw1pp",
          "process_main_output_material_main_unit_display": "克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1662652800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737435473317097,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "wl07",
          "process_id": 1663853590049103,
          "process_plan_amount": 321.0000000000,
          "work_order_code": "22090001wl07",
          "work_order_plan_finish_time": 1662713153000,
          "work_order_id": 1663853590049101,
          "process_node_work_center_equipment_ids": "\"[1661246786110871]\"",
          "process_name": "zzw1pp",
          "process_main_output_material_main_unit_display": "克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1662652800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737435473317097,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "wl04",
          "process_id": 1665701477775026,
          "process_plan_amount": 299.0000000000,
          "work_order_code": "2210140028wl04",
          "work_order_plan_finish_time": 1667184835000,
          "work_order_id": 1665701477775024,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "zzw1pp",
          "process_main_output_material_main_unit_display": "克",
          "process_node_num": "10",
          "work_order_plan_start_time": 1665676800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
        "anaExecId": 1737435473317097,
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
		"anaExecId":"No comment,Type =Number",
		"data":[
			{
				"valid":"是否有效",
				"anaExecId":"分析执行记录ID",
				"repeatKey":"重复键",
				"data":{},
				"anaId":"分析告警配置ID"
			}
		],
		"totalCount":"No comment,Type =Number",
		"config":{
			"baseInfo":{
				"createdAt":"创建时间",
				"code":"编号",
				"dataSetId":"数据集ID",
				"anaId":"ID",
				"name":"名称",
				"status":"状态 0-未启用 1-启用",
				"updatedAt":"更新时间"
			},
			"timeJobConfig":{
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
			"action":"触发动作",
			"conditions":[
				{}
			],
			"repeatConfig":{
				"checkTimeNum":"时间范围",
				"checkFields":[
					"检查字段"
				],
				"checkTimeUnit":"时间单位"
			},
			"dataSetMeta":{
				"conditionFields":[
					{
						"controlConfig":{
							"optionalConfig":[
								"可选项配置 - 手动配置"
							],
							"controlType":"控件类型，1-搜索类型， 2-下拉控件",
							"databaseName":"可选项配置-指定数据表",
							"dataTableName":"可选项配置-指定数据表",
							"optionalSource":"可选项来源，1-手动配置， 2-指定数据表",
							"dataFieldCode":"可选项配置-字段"
						},
						"fieldName":"字段名称",
						"fieldCode":"字段编号",
						"fieldType":"字段类型"
					}
				],
				"dataSetId":"数据集id",
				"dataSetName":"名称",
				"displayFields":[
					{
						"controlConfig":{
							"optionalConfig":[
								"可选项配置 - 手动配置"
							],
							"controlType":"控件类型，1-搜索类型， 2-下拉控件",
							"databaseName":"可选项配置-指定数据表",
							"dataTableName":"可选项配置-指定数据表",
							"optionalSource":"可选项来源，1-手动配置， 2-指定数据表",
							"dataFieldCode":"可选项配置-字段"
						},
						"fieldName":"字段名称",
						"fieldCode":"字段编号",
						"fieldType":"字段类型"
					}
				]
			}
		},
		"repeatCount":"No comment,Type =Number"
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


