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
    "anaExecId": 1737604193158811,
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
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "pxy_wl_001-pxy_gx_0328_001-10",
          "process_id": 1648448460429143,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "pxy_0328_zdyl_sop_001",
          "work_order_plan_finish_time": 1648626568000,
          "work_order_id": 1648448460429141,
          "process_node_work_center_equipment_ids": "\"[1648253813099271]\"",
          "process_name": "pxy-工序-0328-001",
          "process_main_output_material_main_unit_display": "Kg",
          "process_node_num": "10",
          "work_order_plan_start_time": 1648396800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "pxy001",
          "process_id": 1648448460429144,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "pxy_0328_zdyl_sop_001",
          "work_order_plan_finish_time": 1648626568000,
          "work_order_id": 1648448460429141,
          "process_node_work_center_equipment_ids": "\"[1648253813099271]\"",
          "process_name": "pxy-工序-0328-002",
          "process_main_output_material_main_unit_display": "精度为0",
          "process_node_num": "20",
          "work_order_plan_start_time": 1648396800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "pxy_wl_001-pxy_gx_0328_001-10",
          "process_id": 1648554580577911,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "pxy_0330_zdyl_sop_001",
          "work_order_plan_finish_time": 1648626568000,
          "work_order_id": 1648554580577909,
          "process_node_work_center_equipment_ids": "\"[1648253813099271]\"",
          "process_name": "pxy-工序-0328-001",
          "process_main_output_material_main_unit_display": "Kg",
          "process_node_num": "10",
          "work_order_plan_start_time": 1648396800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "pxy001",
          "process_id": 1648554580577912,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "pxy_0330_zdyl_sop_001",
          "work_order_plan_finish_time": 1648626568000,
          "work_order_id": 1648554580577909,
          "process_node_work_center_equipment_ids": "\"[1648253813099271]\"",
          "process_name": "pxy-工序-0328-002",
          "process_main_output_material_main_unit_display": "精度为0",
          "process_node_num": "20",
          "work_order_plan_start_time": 1648396800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "pxy_wl_001-pxy_gx_0328_001-10",
          "process_id": 1648606254203404,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "pxy_0330_zdyl_sop_002",
          "work_order_plan_finish_time": 1648626568000,
          "work_order_id": 1648606254203402,
          "process_node_work_center_equipment_ids": "\"[1648253813099271]\"",
          "process_name": "pxy-工序-0328-001",
          "process_main_output_material_main_unit_display": "Kg",
          "process_node_num": "10",
          "work_order_plan_start_time": 1648396800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "pxy001",
          "process_id": 1648606254203405,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "pxy_0330_zdyl_sop_002",
          "work_order_plan_finish_time": 1648626568000,
          "work_order_id": 1648606254203402,
          "process_node_work_center_equipment_ids": "\"[1648253813099271]\"",
          "process_name": "pxy-工序-0328-002",
          "process_main_output_material_main_unit_display": "精度为0",
          "process_node_num": "20",
          "work_order_plan_start_time": 1648396800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "pxy_wl_001-pxy_gx_0328_001-10",
          "process_id": 1648624756085005,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "pxy_0331_wy_001",
          "work_order_plan_finish_time": 1648626568000,
          "work_order_id": 1648624756085003,
          "process_node_work_center_equipment_ids": "\"[1648253813099271]\"",
          "process_name": "pxy-工序-0328-001",
          "process_main_output_material_main_unit_display": "Kg",
          "process_node_num": "10",
          "work_order_plan_start_time": 1648396800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "pxy001",
          "process_id": 1648624756085006,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "pxy_0331_wy_001",
          "work_order_plan_finish_time": 1648626568000,
          "work_order_id": 1648624756085003,
          "process_node_work_center_equipment_ids": "\"[1648253813099271]\"",
          "process_name": "pxy-工序-0328-002",
          "process_main_output_material_main_unit_display": "精度为0",
          "process_node_num": "20",
          "work_order_plan_start_time": 1648396800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "mbgwl-wupici01",
          "process_id": 1648718386189006,
          "process_plan_amount": 200.0000000000,
          "work_order_code": "m0331sc002333",
          "work_order_plan_finish_time": 1649388707000,
          "work_order_id": 1648718386189004,
          "process_node_work_center_equipment_ids": "\"[1648691378496005]\"",
          "process_name": "m工序0331001",
          "process_main_output_material_main_unit_display": "个",
          "process_node_num": "10",
          "work_order_plan_start_time": 1648656000000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "pxy_wl_001-pxy_gx_0328_001-10",
          "process_id": 1648777084274144,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "pxy_zdyl_0402_001",
          "work_order_plan_finish_time": 1648626568000,
          "work_order_id": 1648777084274142,
          "process_node_work_center_equipment_ids": "\"[1648253813099271]\"",
          "process_name": "pxy-工序-0328-001",
          "process_main_output_material_main_unit_display": "Kg",
          "process_node_num": "10",
          "work_order_plan_start_time": 1648396800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "pxy001",
          "process_id": 1648777084274145,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "pxy_zdyl_0402_001",
          "work_order_plan_finish_time": 1648626568000,
          "work_order_id": 1648777084274142,
          "process_node_work_center_equipment_ids": "\"[1648253813099271]\"",
          "process_name": "pxy-工序-0328-002",
          "process_main_output_material_main_unit_display": "精度为0",
          "process_node_num": "20",
          "work_order_plan_start_time": 1648396800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "mbgwl-wupici01",
          "process_id": 1648779665318924,
          "process_plan_amount": 200.0000000000,
          "work_order_code": "m0402sc001",
          "work_order_plan_finish_time": 1649388707000,
          "work_order_id": 1648779665318922,
          "process_node_work_center_equipment_ids": "\"[1648691378496005]\"",
          "process_name": "m工序0331001",
          "process_main_output_material_main_unit_display": "个",
          "process_node_num": "10",
          "work_order_plan_start_time": 1648828800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "mbgwl-wupici01",
          "process_id": 1648779665318971,
          "process_plan_amount": 2000.0000000000,
          "work_order_code": "gmsop0402001",
          "work_order_plan_finish_time": 1651299854000,
          "work_order_id": 1648779665318969,
          "process_node_work_center_equipment_ids": "\"[1648253813099271]\"",
          "process_name": "0402工序01",
          "process_main_output_material_main_unit_display": "个",
          "process_node_num": "10",
          "work_order_plan_start_time": 1648828800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "mbgwl-wupici01",
          "process_id": 1648897493156372,
          "process_plan_amount": 500.0000000000,
          "work_order_code": "gm0406001sm",
          "work_order_plan_finish_time": 1650683288000,
          "work_order_id": 1648897493156370,
          "process_node_work_center_equipment_ids": "\"[1648253813099271]\"",
          "process_name": "0402工序01",
          "process_main_output_material_main_unit_display": "个",
          "process_node_num": "10",
          "work_order_plan_start_time": 1649174400000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "mbgwl-wupici01",
          "process_id": 1649921207967148,
          "process_plan_amount": 300.0000000000,
          "work_order_code": "m0414soptlbg-0222",
          "work_order_plan_finish_time": 1650702078000,
          "work_order_id": 1649921207967146,
          "process_node_work_center_equipment_ids": "\"[1648691378496005]\"",
          "process_name": "msop工序-投料报工01",
          "process_main_output_material_main_unit_display": "个",
          "process_node_num": "10",
          "work_order_plan_start_time": 1649924475000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "mbgwl-wupici01",
          "process_id": 1650401600439074,
          "process_plan_amount": 200.0000000000,
          "work_order_code": "gm0420001sm",
          "work_order_plan_finish_time": 1651284304000,
          "work_order_id": 1650401600439072,
          "process_node_work_center_equipment_ids": "\"[1648253813099271]\"",
          "process_name": "0402工序01",
          "process_main_output_material_main_unit_display": "个",
          "process_node_num": "10",
          "work_order_plan_start_time": 1650384000000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "pxy_wl_001-pxy_gx_0328_001-10",
          "process_id": 1650449485326026,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "pxy_zdyl_0402_002",
          "work_order_plan_finish_time": 1648626568000,
          "work_order_id": 1650449485326024,
          "process_node_work_center_equipment_ids": "\"[1648253813099271]\"",
          "process_name": "pxy-工序-0328-001",
          "process_main_output_material_main_unit_display": "Kg",
          "process_node_num": "10",
          "work_order_plan_start_time": 1648396800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "pxy001",
          "process_id": 1650449485326027,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "pxy_zdyl_0402_002",
          "work_order_plan_finish_time": 1648626568000,
          "work_order_id": 1650449485326024,
          "process_node_work_center_equipment_ids": "\"[1648253813099271]\"",
          "process_name": "pxy-工序-0328-002",
          "process_main_output_material_main_unit_display": "精度为0",
          "process_node_num": "20",
          "work_order_plan_start_time": 1648396800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "pxy_wl_001-pxy_gx_0328_001-10",
          "process_id": 1650580139168063,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "pxy_zdyl_0422_001",
          "work_order_plan_finish_time": 1648626568000,
          "work_order_id": 1650580139168061,
          "process_node_work_center_equipment_ids": "\"[1648253813099271]\"",
          "process_name": "pxy-工序-0328-001",
          "process_main_output_material_main_unit_display": "Kg",
          "process_node_num": "10",
          "work_order_plan_start_time": 1648396800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "pxy001",
          "process_id": 1650580139168064,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "pxy_zdyl_0422_001",
          "work_order_plan_finish_time": 1648626568000,
          "work_order_id": 1650580139168061,
          "process_node_work_center_equipment_ids": "\"[1648253813099271]\"",
          "process_name": "pxy-工序-0328-002",
          "process_main_output_material_main_unit_display": "精度为0",
          "process_node_num": "20",
          "work_order_plan_start_time": 1648396800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "mbgwl-pici01",
          "process_id": 1650875664148039,
          "process_plan_amount": 2000.0000000000,
          "work_order_code": "gm0425001sm",
          "work_order_plan_finish_time": 1651308377000,
          "work_order_id": 1650875664148037,
          "process_node_work_center_equipment_ids": "\"[1648253813099271]\"",
          "process_name": "pxy-工序-0328-001",
          "process_main_output_material_main_unit_display": "g",
          "process_node_num": "10",
          "work_order_plan_start_time": 1650816000000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "mbgwl-pici01",
          "process_id": 1650924773144026,
          "process_plan_amount": 200.0000000000,
          "work_order_code": "gm0425002nsm",
          "work_order_plan_finish_time": 1651285162000,
          "work_order_id": 1650924773144024,
          "process_node_work_center_equipment_ids": "\"[1648253813099271]\"",
          "process_name": "0402工序01",
          "process_main_output_material_main_unit_display": "g",
          "process_node_num": "10",
          "work_order_plan_start_time": 1650902400000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "wl0429001",
          "process_id": 1651199333065144,
          "process_plan_amount": 200.0000000000,
          "work_order_code": "gm0429001tdl",
          "work_order_plan_finish_time": 1651296315000,
          "work_order_id": 1651199333065142,
          "process_node_work_center_equipment_ids": "\"[1648253813099271]\"",
          "process_name": "0402工序01",
          "process_main_output_material_main_unit_display": "包",
          "process_node_num": "10",
          "work_order_plan_start_time": 1651161600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "MA00000006-GX00001-10",
          "process_id": 1651241753541119,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "lu000007",
          "work_order_plan_finish_time": 1651574463000,
          "work_order_id": 1651241753541117,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "组装",
          "process_main_output_material_main_unit_display": "个",
          "process_node_num": "10",
          "work_order_plan_start_time": 1651420800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "MA00000006",
          "process_id": 1651241753541120,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "lu000007",
          "work_order_plan_finish_time": 1651574463000,
          "work_order_id": 1651241753541117,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "打磨",
          "process_main_output_material_main_unit_display": "个",
          "process_node_num": "20",
          "work_order_plan_start_time": 1651420800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "fzzp0505001",
          "process_id": 1651241753541381,
          "process_plan_amount": 2000.0000000000,
          "work_order_code": "gm0505001tdl_M",
          "work_order_plan_finish_time": 1653819203000,
          "work_order_id": 1651241753541379,
          "process_node_work_center_equipment_ids": "\"[1650355713133028,1650849618133047,1650871881315147,1650882284356055,1650882284356059]\"",
          "process_name": "0504gm工序01",
          "process_main_output_material_main_unit_display": "箱",
          "process_node_num": "10",
          "work_order_plan_start_time": 1651593600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "bg0505001",
          "process_id": 1651241753541382,
          "process_plan_amount": 2000.0000000000,
          "work_order_code": "gm0505001tdl_M",
          "work_order_plan_finish_time": 1653819203000,
          "work_order_id": 1651241753541379,
          "process_node_work_center_equipment_ids": "\"[1650355713133028,1650849618133047,1650871881315147,1650882284356055,1650882284356059]\"",
          "process_name": "0504gm工序02",
          "process_main_output_material_main_unit_display": "包",
          "process_node_num": "20",
          "work_order_plan_start_time": 1651593600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "fzzp0505001",
          "process_id": 1651241753541546,
          "process_plan_amount": 2000.0000000000,
          "work_order_code": "gm0505002tdl_A",
          "work_order_plan_finish_time": 1653820479000,
          "work_order_id": 1651241753541544,
          "process_node_work_center_equipment_ids": "\"[1650355713133028,1650849618133047,1650871881315147,1650882284356055,1650882284356059]\"",
          "process_name": "0504gm工序01",
          "process_main_output_material_main_unit_display": "箱",
          "process_node_num": "10",
          "work_order_plan_start_time": 1651593600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "bg0505001",
          "process_id": 1651241753541547,
          "process_plan_amount": 2000.0000000000,
          "work_order_code": "gm0505002tdl_A",
          "work_order_plan_finish_time": 1653820479000,
          "work_order_id": 1651241753541544,
          "process_node_work_center_equipment_ids": "\"[1650355713133028,1650849618133047,1650871881315147,1650882284356055,1650882284356059]\"",
          "process_name": "0504gm工序02",
          "process_main_output_material_main_unit_display": "包",
          "process_node_num": "20",
          "work_order_plan_start_time": 1651593600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "fzzp0505001",
          "process_id": 1651804784831092,
          "process_plan_amount": 2000.0000000000,
          "work_order_code": "gmsop0506001tdl_M",
          "work_order_plan_finish_time": 1653975582000,
          "work_order_id": 1651804784831090,
          "process_node_work_center_equipment_ids": "\"[1650355713133028,1650849618133047,1650871881315147,1650882284356055,1650882284356059]\"",
          "process_name": "0504gm工序01",
          "process_main_output_material_main_unit_display": "箱",
          "process_node_num": "10",
          "work_order_plan_start_time": 1651766400000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "bg0505001",
          "process_id": 1651804784831093,
          "process_plan_amount": 2000.0000000000,
          "work_order_code": "gmsop0506001tdl_M",
          "work_order_plan_finish_time": 1653975582000,
          "work_order_id": 1651804784831090,
          "process_node_work_center_equipment_ids": "\"[1650355713133028,1650849618133047,1650871881315147,1650882284356055,1650882284356059]\"",
          "process_name": "0504gm工序02",
          "process_main_output_material_main_unit_display": "包",
          "process_node_num": "20",
          "work_order_plan_start_time": 1651766400000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "mbgwl-wupici01-m0331gx-1-10",
          "process_id": 1651819181714180,
          "process_plan_amount": 200.0000000000,
          "work_order_code": "m0506bg-001",
          "work_order_plan_finish_time": 1653725238000,
          "work_order_id": 1651819181714178,
          "process_node_work_center_equipment_ids": "\"[1648691378496005]\"",
          "process_name": "m工序0331001",
          "process_main_output_material_main_unit_display": "只",
          "process_node_num": "10",
          "work_order_plan_start_time": 1651766400000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "mbgwl-wupici01",
          "process_id": 1651819181714181,
          "process_plan_amount": 200.0000000000,
          "work_order_code": "m0506bg-001",
          "work_order_plan_finish_time": 1653725238000,
          "work_order_id": 1651819181714178,
          "process_node_work_center_equipment_ids": "\"[1648691378496005]\"",
          "process_name": "m56测试用工序_1",
          "process_main_output_material_main_unit_display": "个",
          "process_node_num": "20",
          "work_order_plan_start_time": 1651766400000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "fzzp0505001",
          "process_id": 1651841603891034,
          "process_plan_amount": 2000.0000000000,
          "work_order_code": "gm0506002tdl_A",
          "work_order_plan_finish_time": 1653820479000,
          "work_order_id": 1651841603891032,
          "process_node_work_center_equipment_ids": "\"[1650355713133028,1650849618133047,1650871881315147,1650882284356055,1650882284356059]\"",
          "process_name": "0504gm工序01",
          "process_main_output_material_main_unit_display": "箱",
          "process_node_num": "10",
          "work_order_plan_start_time": 1651842085000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "bg0505001",
          "process_id": 1651841603891035,
          "process_plan_amount": 2000.0000000000,
          "work_order_code": "gm0506002tdl_A",
          "work_order_plan_finish_time": 1653820479000,
          "work_order_id": 1651841603891032,
          "process_node_work_center_equipment_ids": "\"[1650355713133028,1650849618133047,1650871881315147,1650882284356055,1650882284356059]\"",
          "process_name": "0504gm工序02",
          "process_main_output_material_main_unit_display": "包",
          "process_node_num": "20",
          "work_order_plan_start_time": 1651842085000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "bg0505001",
          "process_id": 1651895096603191,
          "process_plan_amount": 200.0000000000,
          "work_order_code": "gm0507001sm",
          "work_order_plan_finish_time": 1653826987000,
          "work_order_id": 1651895096603189,
          "process_node_work_center_equipment_ids": "\"[1650355713133028,1650849618133047,1650871881315147,1650882284356055,1650882284356059]\"",
          "process_name": "0504gm工序01",
          "process_main_output_material_main_unit_display": "包",
          "process_node_num": "10",
          "work_order_plan_start_time": 1651852800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "fzzp0505001",
          "process_id": 1651895096603242,
          "process_plan_amount": 2000.0000000000,
          "work_order_code": "gm0508002tdl_A",
          "work_order_plan_finish_time": 1653820479000,
          "work_order_id": 1651895096603240,
          "process_node_work_center_equipment_ids": "\"[1650355713133028,1650849618133047,1650871881315147,1650882284356055,1650882284356059]\"",
          "process_name": "0504gm工序01",
          "process_main_output_material_main_unit_display": "箱",
          "process_node_num": "10",
          "work_order_plan_start_time": 1651941764000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "bg0505001",
          "process_id": 1651895096603243,
          "process_plan_amount": 2000.0000000000,
          "work_order_code": "gm0508002tdl_A",
          "work_order_plan_finish_time": 1653820479000,
          "work_order_id": 1651895096603240,
          "process_node_work_center_equipment_ids": "\"[1650355713133028,1650849618133047,1650871881315147,1650882284356055,1650882284356059]\"",
          "process_name": "0504gm工序02",
          "process_main_output_material_main_unit_display": "包",
          "process_node_num": "20",
          "work_order_plan_start_time": 1651941764000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "fzzp0505001",
          "process_id": 1651895096603292,
          "process_plan_amount": 2000.0000000000,
          "work_order_code": "gm0508001tdl_M",
          "work_order_plan_finish_time": 1653819203000,
          "work_order_id": 1651895096603290,
          "process_node_work_center_equipment_ids": "\"[1650355713133028,1650849618133047,1650871881315147,1650882284356055,1650882284356059]\"",
          "process_name": "0504gm工序01",
          "process_main_output_material_main_unit_display": "箱",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652020526000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "bg0505001",
          "process_id": 1651895096603293,
          "process_plan_amount": 2000.0000000000,
          "work_order_code": "gm0508001tdl_M",
          "work_order_plan_finish_time": 1653819203000,
          "work_order_id": 1651895096603290,
          "process_node_work_center_equipment_ids": "\"[1650355713133028,1650849618133047,1650871881315147,1650882284356055,1650882284356059]\"",
          "process_name": "0504gm工序02",
          "process_main_output_material_main_unit_display": "包",
          "process_node_num": "20",
          "work_order_plan_start_time": 1652020526000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "fzzp0505001",
          "process_id": 1651895096603526,
          "process_plan_amount": 2000.0000000000,
          "work_order_code": "gm0508003tdl_A",
          "work_order_plan_finish_time": 1653820479000,
          "work_order_id": 1651895096603524,
          "process_node_work_center_equipment_ids": "\"[1650355713133028,1650849618133047,1650871881315147,1650882284356055,1650882284356059]\"",
          "process_name": "0504gm工序01",
          "process_main_output_material_main_unit_display": "箱",
          "process_node_num": "10",
          "work_order_plan_start_time": 1651941764000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "bg0505001",
          "process_id": 1651895096603527,
          "process_plan_amount": 2000.0000000000,
          "work_order_code": "gm0508003tdl_A",
          "work_order_plan_finish_time": 1653820479000,
          "work_order_id": 1651895096603524,
          "process_node_work_center_equipment_ids": "\"[1650355713133028,1650849618133047,1650871881315147,1650882284356055,1650882284356059]\"",
          "process_name": "0504gm工序02",
          "process_main_output_material_main_unit_display": "包",
          "process_node_num": "20",
          "work_order_plan_start_time": 1651941764000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "pxy_wl_001-pxy_gx_0328_001-10",
          "process_id": 1651895096603857,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "pxy_zdyl_0509_001",
          "work_order_plan_finish_time": 1648626568000,
          "work_order_id": 1651895096603855,
          "process_node_work_center_equipment_ids": "\"[1648253813099271]\"",
          "process_name": "pxy-工序-0328-001",
          "process_main_output_material_main_unit_display": "Kg",
          "process_node_num": "10",
          "work_order_plan_start_time": 1648569600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "pxy001",
          "process_id": 1651895096603858,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "pxy_zdyl_0509_001",
          "work_order_plan_finish_time": 1648626568000,
          "work_order_id": 1651895096603855,
          "process_node_work_center_equipment_ids": "\"[1648253813099271]\"",
          "process_name": "pxy-工序-0328-002",
          "process_main_output_material_main_unit_display": "精度为0",
          "process_node_num": "20",
          "work_order_plan_start_time": 1648569600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "fzzp0505001",
          "process_id": 1651895096603926,
          "process_plan_amount": 2000.0000000000,
          "work_order_code": "gm0508004tdl_M",
          "work_order_plan_finish_time": 1653819203000,
          "work_order_id": 1651895096603924,
          "process_node_work_center_equipment_ids": "\"[1650355713133028,1650849618133047,1650871881315147,1650882284356055,1650882284356059]\"",
          "process_name": "0504gm工序01",
          "process_main_output_material_main_unit_display": "箱",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652020526000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "bg0505001",
          "process_id": 1651895096603927,
          "process_plan_amount": 2000.0000000000,
          "work_order_code": "gm0508004tdl_M",
          "work_order_plan_finish_time": 1653819203000,
          "work_order_id": 1651895096603924,
          "process_node_work_center_equipment_ids": "\"[1650355713133028,1650849618133047,1650871881315147,1650882284356055,1650882284356059]\"",
          "process_name": "0504gm工序02",
          "process_main_output_material_main_unit_display": "包",
          "process_node_num": "20",
          "work_order_plan_start_time": 1652020526000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "bg0505001",
          "process_id": 1652162924776001,
          "process_plan_amount": 2000.0000000000,
          "work_order_code": "gm0510002tdl_M",
          "work_order_plan_finish_time": 1653796759000,
          "work_order_id": 1652162924773000,
          "process_node_work_center_equipment_ids": "\"[1650355713133028,1650849618133047,1650871881315147,1650882284356055,1650882284356059]\"",
          "process_name": "0504gm工序01",
          "process_main_output_material_main_unit_display": "包",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652112000000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "pxy_wl_001-pxy_gx_0328_001-10",
          "process_id": 1652167222364125,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "pxy_zdyl_0510_001(hy_bzj=0)",
          "work_order_plan_finish_time": 1648626568000,
          "work_order_id": 1652167222364123,
          "process_node_work_center_equipment_ids": "\"[1648253813099271]\"",
          "process_name": "pxy-工序-0328-001",
          "process_main_output_material_main_unit_display": "Kg",
          "process_node_num": "10",
          "work_order_plan_start_time": 1648569600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "pxy001",
          "process_id": 1652167222364126,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "pxy_zdyl_0510_001(hy_bzj=0)",
          "work_order_plan_finish_time": 1648626568000,
          "work_order_id": 1652167222364123,
          "process_node_work_center_equipment_ids": "\"[1648253813099271]\"",
          "process_name": "pxy-工序-0328-002",
          "process_main_output_material_main_unit_display": "精度为0",
          "process_node_num": "20",
          "work_order_plan_start_time": 1648569600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "pxy_wl_001-pxy_gx_0328_001-10",
          "process_id": 1652172072903048,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "pxy_zdyl_0510_002(hy_bzj=100)",
          "work_order_plan_finish_time": 1648626568000,
          "work_order_id": 1652172072903046,
          "process_node_work_center_equipment_ids": "\"[1648253813099271]\"",
          "process_name": "pxy-工序-0328-001",
          "process_main_output_material_main_unit_display": "Kg",
          "process_node_num": "10",
          "work_order_plan_start_time": 1648569600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "pxy001",
          "process_id": 1652172072903049,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "pxy_zdyl_0510_002(hy_bzj=100)",
          "work_order_plan_finish_time": 1648626568000,
          "work_order_id": 1652172072903046,
          "process_node_work_center_equipment_ids": "\"[1648253813099271]\"",
          "process_name": "pxy-工序-0328-002",
          "process_main_output_material_main_unit_display": "精度为0",
          "process_node_num": "20",
          "work_order_plan_start_time": 1648569600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "mbgwl-pici01-m0401sopgx-1-10",
          "process_id": 1652184240624014,
          "process_plan_amount": 200.0000000000,
          "work_order_code": "mm0510sop-bg1",
          "work_order_plan_finish_time": 1653444000000,
          "work_order_id": 1652184240624012,
          "process_node_work_center_equipment_ids": "\"[1648691378496005]\"",
          "process_name": "msop工序-投料报工01",
          "process_main_output_material_main_unit_display": "g",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652112000000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "mbgwl-pici01",
          "process_id": 1652184240624015,
          "process_plan_amount": 200.0000000000,
          "work_order_code": "mm0510sop-bg1",
          "work_order_plan_finish_time": 1653444000000,
          "work_order_id": 1652184240624012,
          "process_node_work_center_equipment_ids": "\"[1648691378496005]\"",
          "process_name": "m56测试用工序_1",
          "process_main_output_material_main_unit_display": "g",
          "process_node_num": "20",
          "work_order_plan_start_time": 1652112000000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "bg0505001",
          "process_id": 1652252773194002,
          "process_plan_amount": 2000.0000000000,
          "work_order_code": "gm0511001tdl_M",
          "work_order_plan_finish_time": 1653979459000,
          "work_order_id": 1652252773194000,
          "process_node_work_center_equipment_ids": "\"[1650355713133028,1650849618133047,1650871881315147,1650882284356055,1650882284356059]\"",
          "process_name": "0504gm工序01",
          "process_main_output_material_main_unit_display": "包",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652198400000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "MA00000006-GX00001-10",
          "process_id": 1652252829349017,
          "process_plan_amount": 1.0000000000,
          "work_order_code": "lu000104",
          "work_order_plan_finish_time": 1652350327000,
          "work_order_id": 1652252829349015,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "组装",
          "process_main_output_material_main_unit_display": "个",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652198400000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "MA00000006",
          "process_id": 1652252829349018,
          "process_plan_amount": 1.0000000000,
          "work_order_code": "lu000104",
          "work_order_plan_finish_time": 1652350327000,
          "work_order_id": 1652252829349015,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "打磨",
          "process_main_output_material_main_unit_display": "个",
          "process_node_num": "20",
          "work_order_plan_start_time": 1652198400000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "bg0505001",
          "process_id": 1652260223818177,
          "process_plan_amount": 2000.0000000000,
          "work_order_code": "gm0511002tdl_M",
          "work_order_plan_finish_time": 1653819174000,
          "work_order_id": 1652260223818175,
          "process_node_work_center_equipment_ids": "\"[1650355713133028,1650849618133047,1650871881315147,1650882284356055,1650882284356059]\"",
          "process_name": "0504gm工序01",
          "process_main_output_material_main_unit_display": "包",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652198400000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "fzzp0505001",
          "process_id": 1652260223818238,
          "process_plan_amount": 2000.0000000000,
          "work_order_code": "gmsop0511001tdl_M",
          "work_order_plan_finish_time": 1653975582000,
          "work_order_id": 1652260223818236,
          "process_node_work_center_equipment_ids": "\"[1650355713133028,1650849618133047,1650871881315147,1650882284356055,1650882284356059]\"",
          "process_name": "0504gm工序01",
          "process_main_output_material_main_unit_display": "箱",
          "process_node_num": "10",
          "work_order_plan_start_time": 1651766400000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "bg0505001",
          "process_id": 1652260223818239,
          "process_plan_amount": 2000.0000000000,
          "work_order_code": "gmsop0511001tdl_M",
          "work_order_plan_finish_time": 1653975582000,
          "work_order_id": 1652260223818236,
          "process_node_work_center_equipment_ids": "\"[1650355713133028,1650849618133047,1650871881315147,1650882284356055,1650882284356059]\"",
          "process_name": "0504gm工序02",
          "process_main_output_material_main_unit_display": "包",
          "process_node_num": "20",
          "work_order_plan_start_time": 1651766400000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "fzzp0505001",
          "process_id": 1652284623702002,
          "process_plan_amount": 2000.0000000000,
          "work_order_code": "gm0511004tdl_M",
          "work_order_plan_finish_time": 1653819203000,
          "work_order_id": 1652284623702000,
          "process_node_work_center_equipment_ids": "\"[1650355713133028,1650849618133047,1650871881315147,1650882284356055,1650882284356059]\"",
          "process_name": "0504gm工序01",
          "process_main_output_material_main_unit_display": "箱",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652020526000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "bg0505001",
          "process_id": 1652284623702003,
          "process_plan_amount": 2000.0000000000,
          "work_order_code": "gm0511004tdl_M",
          "work_order_plan_finish_time": 1653819203000,
          "work_order_id": 1652284623702000,
          "process_node_work_center_equipment_ids": "\"[1650355713133028,1650849618133047,1650871881315147,1650882284356055,1650882284356059]\"",
          "process_name": "0504gm工序02",
          "process_main_output_material_main_unit_display": "包",
          "process_node_num": "20",
          "work_order_plan_start_time": 1652020526000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "fzzp0505001",
          "process_id": 1652284623702083,
          "process_plan_amount": 2000.0000000000,
          "work_order_code": "gm0512001tdl",
          "work_order_plan_finish_time": 1653753895000,
          "work_order_id": 1652284623702081,
          "process_node_work_center_equipment_ids": "\"[1650355713133028,1650849618133047,1650871881315147,1650882284356055,1650882284356059]\"",
          "process_name": "0504gm工序01",
          "process_main_output_material_main_unit_display": "箱",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652284800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "bg0505001",
          "process_id": 1652284623702084,
          "process_plan_amount": 2000.0000000000,
          "work_order_code": "gm0512001tdl",
          "work_order_plan_finish_time": 1653753895000,
          "work_order_id": 1652284623702081,
          "process_node_work_center_equipment_ids": "\"[1650355713133028,1650849618133047,1650871881315147,1650882284356055,1650882284356059]\"",
          "process_name": "0504gm工序02",
          "process_main_output_material_main_unit_display": "包",
          "process_node_num": "20",
          "work_order_plan_start_time": 1652284800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "fzzp0505001",
          "process_id": 1652345747930201,
          "process_plan_amount": 2000.0000000000,
          "work_order_code": "gm0512005tdl",
          "work_order_plan_finish_time": 1653753895000,
          "work_order_id": 1652345747930199,
          "process_node_work_center_equipment_ids": "\"[1650355713133028,1650849618133047,1650871881315147,1650882284356055,1650882284356059]\"",
          "process_name": "0504gm工序01",
          "process_main_output_material_main_unit_display": "箱",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652284800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "bg0505001",
          "process_id": 1652345747930202,
          "process_plan_amount": 2000.0000000000,
          "work_order_code": "gm0512005tdl",
          "work_order_plan_finish_time": 1653753895000,
          "work_order_id": 1652345747930199,
          "process_node_work_center_equipment_ids": "\"[1650355713133028,1650849618133047,1650871881315147,1650882284356055,1650882284356059]\"",
          "process_name": "0504gm工序02",
          "process_main_output_material_main_unit_display": "包",
          "process_node_num": "20",
          "work_order_plan_start_time": 1652284800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "fzzp0505001",
          "process_id": 1652361070166799,
          "process_plan_amount": 2000.0000000000,
          "work_order_code": "gm0513001tdl",
          "work_order_plan_finish_time": 1653753895000,
          "work_order_id": 1652361070166797,
          "process_node_work_center_equipment_ids": "\"[1650355713133028,1650849618133047,1650871881315147,1650882284356055,1650882284356059]\"",
          "process_name": "0504gm工序01",
          "process_main_output_material_main_unit_display": "箱",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652284800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "bg0505001",
          "process_id": 1652361070166800,
          "process_plan_amount": 2000.0000000000,
          "work_order_code": "gm0513001tdl",
          "work_order_plan_finish_time": 1653753895000,
          "work_order_id": 1652361070166797,
          "process_node_work_center_equipment_ids": "\"[1650355713133028,1650849618133047,1650871881315147,1650882284356055,1650882284356059]\"",
          "process_name": "0504gm工序02",
          "process_main_output_material_main_unit_display": "包",
          "process_node_num": "20",
          "work_order_plan_start_time": 1652284800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "fzzp0505001",
          "process_id": 1652410209413010,
          "process_plan_amount": 2000.0000000000,
          "work_order_code": "test_for_local_20220513",
          "work_order_plan_finish_time": 1653753895000,
          "work_order_id": 1652410209413008,
          "process_node_work_center_equipment_ids": "\"[1650355713133028,1650849618133047,1650871881315147,1650882284356055,1650882284356059]\"",
          "process_name": "0504gm工序01",
          "process_main_output_material_main_unit_display": "箱",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652284800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "bg0505001",
          "process_id": 1652410209413011,
          "process_plan_amount": 2000.0000000000,
          "work_order_code": "test_for_local_20220513",
          "work_order_plan_finish_time": 1653753895000,
          "work_order_id": 1652410209413008,
          "process_node_work_center_equipment_ids": "\"[1650355713133028,1650849618133047,1650871881315147,1650882284356055,1650882284356059]\"",
          "process_name": "0504gm工序02",
          "process_main_output_material_main_unit_display": "包",
          "process_node_num": "20",
          "work_order_plan_start_time": 1652284800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "pxy_wl_001-pxy_gx_0328_001-10",
          "process_id": 1652425510545002,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "pxy_zdyl_0513_001",
          "work_order_plan_finish_time": 1648626568000,
          "work_order_id": 1652425510545000,
          "process_node_work_center_equipment_ids": "\"[1648253813099271]\"",
          "process_name": "pxy-工序-0328-001",
          "process_main_output_material_main_unit_display": "Kg",
          "process_node_num": "10",
          "work_order_plan_start_time": 1648569600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "pxy001",
          "process_id": 1652425510545003,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "pxy_zdyl_0513_001",
          "work_order_plan_finish_time": 1648626568000,
          "work_order_id": 1652425510545000,
          "process_node_work_center_equipment_ids": "\"[1648253813099271]\"",
          "process_name": "pxy-工序-0328-002",
          "process_main_output_material_main_unit_display": "精度为0",
          "process_node_num": "20",
          "work_order_plan_start_time": 1648569600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "bg0505001",
          "process_id": 1652425510545075,
          "process_plan_amount": 2000.0000000000,
          "work_order_code": "gmsop0513001tdl",
          "work_order_plan_finish_time": 1656574228000,
          "work_order_id": 1652425510545073,
          "process_node_work_center_equipment_ids": "\"[1650355713133028,1650849618133047,1650871881315147,1650882284356055,1650882284356059]\"",
          "process_name": "0504gm工序01",
          "process_main_output_material_main_unit_display": "包",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652371200000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "pxy_wl_001-pxy_gx_0328_001-10",
          "process_id": 1652430849716196,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "pxy_0513_wy_001",
          "work_order_plan_finish_time": 1648626568000,
          "work_order_id": 1652430849716194,
          "process_node_work_center_equipment_ids": "\"[1648253813099271]\"",
          "process_name": "pxy-工序-0328-001",
          "process_main_output_material_main_unit_display": "Kg",
          "process_node_num": "10",
          "work_order_plan_start_time": 1648396800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "pxy001",
          "process_id": 1652430849716197,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "pxy_0513_wy_001",
          "work_order_plan_finish_time": 1648626568000,
          "work_order_id": 1652430849716194,
          "process_node_work_center_equipment_ids": "\"[1648253813099271]\"",
          "process_name": "pxy-工序-0328-002",
          "process_main_output_material_main_unit_display": "精度为0",
          "process_node_num": "20",
          "work_order_plan_start_time": 1648396800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "pxy_wl_001-pxy_gx_0328_001-10",
          "process_id": 1652430849716230,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "pxy_sop_0513_001",
          "work_order_plan_finish_time": 1648626568000,
          "work_order_id": 1652430849716228,
          "process_node_work_center_equipment_ids": "\"[1648253813099271]\"",
          "process_name": "pxy-工序-0328-001",
          "process_main_output_material_main_unit_display": "Kg",
          "process_node_num": "10",
          "work_order_plan_start_time": 1648396800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "pxy001",
          "process_id": 1652430849716231,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "pxy_sop_0513_001",
          "work_order_plan_finish_time": 1648626568000,
          "work_order_id": 1652430849716228,
          "process_node_work_center_equipment_ids": "\"[1648253813099271]\"",
          "process_name": "pxy-工序-0328-002",
          "process_main_output_material_main_unit_display": "精度为0",
          "process_node_num": "20",
          "work_order_plan_start_time": 1648396800000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "fzzp0505001",
          "process_id": 1652439679944220,
          "process_plan_amount": 5000.0000000000,
          "work_order_code": "gm0515001tdl",
          "work_order_plan_finish_time": 1653753895000,
          "work_order_id": 1652439679944218,
          "process_node_work_center_equipment_ids": "\"[1650355713133028,1650849618133047,1650871881315147,1650882284356055,1650882284356059]\"",
          "process_name": "0504gm工序01",
          "process_main_output_material_main_unit_display": "箱",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652513466000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "bg0505001",
          "process_id": 1652439679944221,
          "process_plan_amount": 5000.0000000000,
          "work_order_code": "gm0515001tdl",
          "work_order_plan_finish_time": 1653753895000,
          "work_order_id": 1652439679944218,
          "process_node_work_center_equipment_ids": "\"[1650355713133028,1650849618133047,1650871881315147,1650882284356055,1650882284356059]\"",
          "process_name": "0504gm工序02",
          "process_main_output_material_main_unit_display": "包",
          "process_node_num": "20",
          "work_order_plan_start_time": 1652513466000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "fzzp0505001",
          "process_id": 1652439679944386,
          "process_plan_amount": 5000.0000000000,
          "work_order_code": "gm0515002tdl",
          "work_order_plan_finish_time": 1653753895000,
          "work_order_id": 1652439679944384,
          "process_node_work_center_equipment_ids": "\"[1650355713133028,1650849618133047,1650871881315147,1650882284356055,1650882284356059]\"",
          "process_name": "0504gm工序01",
          "process_main_output_material_main_unit_display": "箱",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652513466000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "bg0505001",
          "process_id": 1652439679944387,
          "process_plan_amount": 5000.0000000000,
          "work_order_code": "gm0515002tdl",
          "work_order_plan_finish_time": 1653753895000,
          "work_order_id": 1652439679944384,
          "process_node_work_center_equipment_ids": "\"[1650355713133028,1650849618133047,1650871881315147,1650882284356055,1650882284356059]\"",
          "process_name": "0504gm工序02",
          "process_main_output_material_main_unit_display": "包",
          "process_node_num": "20",
          "work_order_plan_start_time": 1652513466000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "fzzp0505001",
          "process_id": 1652439679944429,
          "process_plan_amount": 5000.0000000000,
          "work_order_code": "gm0515003tdl",
          "work_order_plan_finish_time": 1653753895000,
          "work_order_id": 1652439679944427,
          "process_node_work_center_equipment_ids": "\"[1650355713133028,1650849618133047,1650871881315147,1650882284356055,1650882284356059]\"",
          "process_name": "0504gm工序01",
          "process_main_output_material_main_unit_display": "箱",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652513466000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "bg0505001",
          "process_id": 1652439679944430,
          "process_plan_amount": 5000.0000000000,
          "work_order_code": "gm0515003tdl",
          "work_order_plan_finish_time": 1653753895000,
          "work_order_id": 1652439679944427,
          "process_node_work_center_equipment_ids": "\"[1650355713133028,1650849618133047,1650871881315147,1650882284356055,1650882284356059]\"",
          "process_name": "0504gm工序02",
          "process_main_output_material_main_unit_display": "包",
          "process_node_num": "20",
          "work_order_plan_start_time": 1652513466000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "fzzp0505001",
          "process_id": 1652439679944457,
          "process_plan_amount": 2000.0000000000,
          "work_order_code": "gm0515004tdl",
          "work_order_plan_finish_time": 1653753895000,
          "work_order_id": 1652439679944455,
          "process_node_work_center_equipment_ids": "\"[1650355713133028,1650849618133047,1650871881315147,1650882284356055,1650882284356059]\"",
          "process_name": "0504gm工序01",
          "process_main_output_material_main_unit_display": "箱",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652513466000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "bg0505001",
          "process_id": 1652439679944458,
          "process_plan_amount": 2000.0000000000,
          "work_order_code": "gm0515004tdl",
          "work_order_plan_finish_time": 1653753895000,
          "work_order_id": 1652439679944455,
          "process_node_work_center_equipment_ids": "\"[1650355713133028,1650849618133047,1650871881315147,1650882284356055,1650882284356059]\"",
          "process_name": "0504gm工序02",
          "process_main_output_material_main_unit_display": "包",
          "process_node_num": "20",
          "work_order_plan_start_time": 1652513466000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "fzzp0505001",
          "process_id": 1652626206896002,
          "process_plan_amount": 2000.0000000000,
          "work_order_code": "gm0515005tdl",
          "work_order_plan_finish_time": 1653819203000,
          "work_order_id": 1652626206896000,
          "process_node_work_center_equipment_ids": "\"[1650355713133028,1650849618133047,1650871881315147,1650882284356055,1650882284356059]\"",
          "process_name": "0504gm工序01",
          "process_main_output_material_main_unit_display": "箱",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652020526000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "bg0505001",
          "process_id": 1652626206896003,
          "process_plan_amount": 2000.0000000000,
          "work_order_code": "gm0515005tdl",
          "work_order_plan_finish_time": 1653819203000,
          "work_order_id": 1652626206896000,
          "process_node_work_center_equipment_ids": "\"[1650355713133028,1650849618133047,1650871881315147,1650882284356055,1650882284356059]\"",
          "process_name": "0504gm工序02",
          "process_main_output_material_main_unit_display": "包",
          "process_node_num": "20",
          "work_order_plan_start_time": 1652020526000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "pxy_wl_001-pxy_gx_0328_001-10",
          "process_id": 1652681394167041,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "pxy_zdyl_0510_002(hy_bzj=10,tdj=90)",
          "work_order_plan_finish_time": 1648626568000,
          "work_order_id": 1652681394167039,
          "process_node_work_center_equipment_ids": "\"[1648253813099271]\"",
          "process_name": "pxy-工序-0328-001",
          "process_main_output_material_main_unit_display": "Kg",
          "process_node_num": "10",
          "work_order_plan_start_time": 1648569600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "pxy001",
          "process_id": 1652681394167042,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "pxy_zdyl_0510_002(hy_bzj=10,tdj=90)",
          "work_order_plan_finish_time": 1648626568000,
          "work_order_id": 1652681394167039,
          "process_node_work_center_equipment_ids": "\"[1648253813099271]\"",
          "process_name": "pxy-工序-0328-002",
          "process_main_output_material_main_unit_display": "精度为0",
          "process_node_num": "20",
          "work_order_plan_start_time": 1648569600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "pxy_wl_001-pxy_gx_0328_001-10",
          "process_id": 1652681394167129,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "pxy_zdyl_0510_002(zp_bzj=100)",
          "work_order_plan_finish_time": 1648626568000,
          "work_order_id": 1652681394167127,
          "process_node_work_center_equipment_ids": "\"[1648253813099271]\"",
          "process_name": "pxy-工序-0328-001",
          "process_main_output_material_main_unit_display": "Kg",
          "process_node_num": "10",
          "work_order_plan_start_time": 1648569600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "pxy001",
          "process_id": 1652681394167130,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "pxy_zdyl_0510_002(zp_bzj=100)",
          "work_order_plan_finish_time": 1648626568000,
          "work_order_id": 1652681394167127,
          "process_node_work_center_equipment_ids": "\"[1648253813099271]\"",
          "process_name": "pxy-工序-0328-002",
          "process_main_output_material_main_unit_display": "精度为0",
          "process_node_num": "20",
          "work_order_plan_start_time": 1648569600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "pxy_wl_001-pxy_gx_0328_001-10",
          "process_id": 1652681394167182,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "pxy_zdyl_0516_003(zp_bzj=0)",
          "work_order_plan_finish_time": 1648626568000,
          "work_order_id": 1652681394167180,
          "process_node_work_center_equipment_ids": "\"[1648253813099271]\"",
          "process_name": "pxy-工序-0328-001",
          "process_main_output_material_main_unit_display": "Kg",
          "process_node_num": "10",
          "work_order_plan_start_time": 1648569600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "pxy001",
          "process_id": 1652681394167183,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "pxy_zdyl_0516_003(zp_bzj=0)",
          "work_order_plan_finish_time": 1648626568000,
          "work_order_id": 1652681394167180,
          "process_node_work_center_equipment_ids": "\"[1648253813099271]\"",
          "process_name": "pxy-工序-0328-002",
          "process_main_output_material_main_unit_display": "精度为0",
          "process_node_num": "20",
          "work_order_plan_start_time": 1648569600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "pxy_wl_001-pxy_gx_0328_001-10",
          "process_id": 1652686194317008,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "pxy_zdyl_0516_004(hy_bzj=10,tdj=90)",
          "work_order_plan_finish_time": 1648626568000,
          "work_order_id": 1652686194317006,
          "process_node_work_center_equipment_ids": "\"[1648253813099271]\"",
          "process_name": "pxy-工序-0328-001",
          "process_main_output_material_main_unit_display": "Kg",
          "process_node_num": "10",
          "work_order_plan_start_time": 1648569600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "pxy001",
          "process_id": 1652686194317009,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "pxy_zdyl_0516_004(hy_bzj=10,tdj=90)",
          "work_order_plan_finish_time": 1648626568000,
          "work_order_id": 1652686194317006,
          "process_node_work_center_equipment_ids": "\"[1648253813099271]\"",
          "process_name": "pxy-工序-0328-002",
          "process_main_output_material_main_unit_display": "精度为0",
          "process_node_num": "20",
          "work_order_plan_start_time": 1648569600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "pxy_wl_001-pxy_gx_0328_001-10",
          "process_id": 1652686194317108,
          "process_plan_amount": 200.0000000000,
          "work_order_code": "pxy_zdyl_0516_005(hy_bzj=10,tdj=90)",
          "work_order_plan_finish_time": 1648626568000,
          "work_order_id": 1652686194317106,
          "process_node_work_center_equipment_ids": "\"[1648253813099271]\"",
          "process_name": "pxy-工序-0328-001",
          "process_main_output_material_main_unit_display": "Kg",
          "process_node_num": "10",
          "work_order_plan_start_time": 1648569600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "pxy_wl_001-pxy_gx_0328_002-20",
          "process_id": 1652686194317109,
          "process_plan_amount": 500.0000000000,
          "work_order_code": "pxy_zdyl_0516_005(hy_bzj=10,tdj=90)",
          "work_order_plan_finish_time": 1648626568000,
          "work_order_id": 1652686194317106,
          "process_node_work_center_equipment_ids": "\"[1648253813099271]\"",
          "process_name": "pxy-工序-0328-002",
          "process_main_output_material_main_unit_display": "Kg",
          "process_node_num": "20",
          "work_order_plan_start_time": 1648569600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "pxy001",
          "process_id": 1652686194317110,
          "process_plan_amount": 100.0000000000,
          "work_order_code": "pxy_zdyl_0516_005(hy_bzj=10,tdj=90)",
          "work_order_plan_finish_time": 1648626568000,
          "work_order_id": 1652686194317106,
          "process_node_work_center_equipment_ids": "\"[1648253813099271]\"",
          "process_name": "0402工序01",
          "process_main_output_material_main_unit_display": "精度为0",
          "process_node_num": "30",
          "work_order_plan_start_time": 1648569600000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "bg0505001",
          "process_id": 1652710706156002,
          "process_plan_amount": 2000.0000000000,
          "work_order_code": "gm0516001tdl",
          "work_order_plan_finish_time": 1654006479000,
          "work_order_id": 1652710706156000,
          "process_node_work_center_equipment_ids": "\"[]\"",
          "process_name": "0504gm工序01",
          "process_main_output_material_main_unit_display": "包",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652630400000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "fzzp0505001",
          "process_id": 1652710706156041,
          "process_plan_amount": 2000.0000000000,
          "work_order_code": "gm0516002t_nsm",
          "work_order_plan_finish_time": 1654008696000,
          "work_order_id": 1652710706156039,
          "process_node_work_center_equipment_ids": "\"[1650355713133028,1650849618133047,1650871881315147,1650882284356055,1650882284356059]\"",
          "process_name": "0504gm工序01",
          "process_main_output_material_main_unit_display": "箱",
          "process_node_num": "10",
          "work_order_plan_start_time": 1652630400000
        }
      },
      {
        "anaId": 1737353310593557,
        "anaExecId": 1737604193158811,
        "repeatKey": null,
        "data": {
          "process_main_output_material_code": "bg0505001",
          "process_id": 1652710706156042,
          "process_plan_amount": 2000.0000000000,
          "work_order_code": "gm0516002t_nsm",
          "work_order_plan_finish_time": 1654008696000,
          "work_order_id": 1652710706156039,
          "process_node_work_center_equipment_ids": "\"[1650355713133028,1650849618133047,1650871881315147,1650882284356055,1650882284356059]\"",
          "process_name": "0504gm工序02",
          "process_main_output_material_main_unit_display": "包",
          "process_node_num": "20",
          "work_order_plan_start_time": 1652630400000
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


