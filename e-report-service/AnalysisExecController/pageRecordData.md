# pageRecordData

### Method description

```
分析告警记录-数据
```

> URL: http://localhost:8080/web/v1/analysis/exec/record/page_data
>
> Origin Url: http://localhost:8080/web/v1/analysis/exec/record/page_data
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
  "anaExecId": 1,
  "page": 1,
  "size": 20,
  "selectFlag": 1
}
```

###### JSON document

```
{
	"anaExecId":"执行记录ID",
	"size":"每页大小",
	"sorter":[
		{
			"field":"排序字段",
			"order":"排序规律 默认 asc，asc 升序 desc 降序"
		}
	],
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
    "anaExecId": 1736584998229109,
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
      }
    },
    "data": [
      {
        "org_id": 10896962,
        "process_id": 1651819181714076,
        "work_order_shift_name": null,
        "work_order_id": 1651819181714074,
        "work_order_code": "2022-05-06-001",
        "work_order_plan_start_time": 1651766400000,
        "work_order_plan_finish_time": 1651908785000,
        "process_plan_amount": 100.0000000000,
        "process_node_num": "10",
        "process_name": "工序-001"
      },
      {
        "org_id": 10896962,
        "process_id": 1651819181714077,
        "work_order_shift_name": null,
        "work_order_id": 1651819181714074,
        "work_order_code": "2022-05-06-001",
        "work_order_plan_start_time": 1651766400000,
        "work_order_plan_finish_time": 1651908785000,
        "process_plan_amount": 100.0000000000,
        "process_node_num": "20",
        "process_name": "工序-002"
      },
      {
        "org_id": 10896962,
        "process_id": 1653455535160113,
        "work_order_shift_name": null,
        "work_order_id": 1653455535160111,
        "work_order_code": "2022-05-25-004",
        "work_order_plan_start_time": 1653408000000,
        "work_order_plan_finish_time": 1653476144000,
        "process_plan_amount": 10.0000000000,
        "process_node_num": "10",
        "process_name": "工序-001"
      },
      {
        "org_id": 10896962,
        "process_id": 1653455535160114,
        "work_order_shift_name": null,
        "work_order_id": 1653455535160111,
        "work_order_code": "2022-05-25-004",
        "work_order_plan_start_time": 1653408000000,
        "work_order_plan_finish_time": 1653476144000,
        "process_plan_amount": 10.0000000000,
        "process_node_num": "20",
        "process_name": "工序-002"
      },
      {
        "org_id": 10896962,
        "process_id": 1653462936403025,
        "work_order_shift_name": null,
        "work_order_id": 1653462936403023,
        "work_order_code": "2022-05-25-005",
        "work_order_plan_start_time": 1653408000000,
        "work_order_plan_finish_time": 1653479167000,
        "process_plan_amount": 10.0000000000,
        "process_node_num": "10",
        "process_name": "工序-001"
      },
      {
        "org_id": 10896962,
        "process_id": 1653462936403026,
        "work_order_shift_name": null,
        "work_order_id": 1653462936403023,
        "work_order_code": "2022-05-25-005",
        "work_order_plan_start_time": 1653408000000,
        "work_order_plan_finish_time": 1653479167000,
        "process_plan_amount": 10.0000000000,
        "process_node_num": "20",
        "process_name": "工序-002"
      },
      {
        "org_id": 10896962,
        "process_id": 1653462936403070,
        "work_order_shift_name": null,
        "work_order_id": 1653462936403068,
        "work_order_code": "2022-05-25-008",
        "work_order_plan_start_time": 1653408000000,
        "work_order_plan_finish_time": 1653482923000,
        "process_plan_amount": 10.0000000000,
        "process_node_num": "10",
        "process_name": "工序-001"
      },
      {
        "org_id": 10896962,
        "process_id": 1653462936403071,
        "work_order_shift_name": null,
        "work_order_id": 1653462936403068,
        "work_order_code": "2022-05-25-008",
        "work_order_plan_start_time": 1653408000000,
        "work_order_plan_finish_time": 1653482923000,
        "process_plan_amount": 10.0000000000,
        "process_node_num": "20",
        "process_name": "工序-002"
      },
      {
        "org_id": 10896962,
        "process_id": 1653463993111028,
        "work_order_shift_name": null,
        "work_order_id": 1653463993111026,
        "work_order_code": "2022-05-25-006",
        "work_order_plan_start_time": 1653408000000,
        "work_order_plan_finish_time": 1653482923000,
        "process_plan_amount": 10.0000000000,
        "process_node_num": "10",
        "process_name": "工序-001"
      },
      {
        "org_id": 10896962,
        "process_id": 1653463993111029,
        "work_order_shift_name": null,
        "work_order_id": 1653463993111026,
        "work_order_code": "2022-05-25-006",
        "work_order_plan_start_time": 1653408000000,
        "work_order_plan_finish_time": 1653482923000,
        "process_plan_amount": 10.0000000000,
        "process_node_num": "20",
        "process_name": "工序-002"
      },
      {
        "org_id": 10896962,
        "process_id": 1653463993111408,
        "work_order_shift_name": null,
        "work_order_id": 1653463993111406,
        "work_order_code": "2022-05-26-001",
        "work_order_plan_start_time": 1653494400000,
        "work_order_plan_finish_time": 1653552675000,
        "process_plan_amount": 10.0000000000,
        "process_node_num": "10",
        "process_name": "工序-001"
      },
      {
        "org_id": 10896962,
        "process_id": 1653463993111409,
        "work_order_shift_name": null,
        "work_order_id": 1653463993111406,
        "work_order_code": "2022-05-26-001",
        "work_order_plan_start_time": 1653494400000,
        "work_order_plan_finish_time": 1653552675000,
        "process_plan_amount": 10.0000000000,
        "process_node_num": "20",
        "process_name": "工序-002"
      },
      {
        "org_id": 10896962,
        "process_id": 1653463993111485,
        "work_order_shift_name": null,
        "work_order_id": 1653463993111483,
        "work_order_code": "2022-05-26-002",
        "work_order_plan_start_time": 1653494400000,
        "work_order_plan_finish_time": 1653550499000,
        "process_plan_amount": 10.0000000000,
        "process_node_num": "10",
        "process_name": "工序-001"
      },
      {
        "org_id": 10896962,
        "process_id": 1653463993111486,
        "work_order_shift_name": null,
        "work_order_id": 1653463993111483,
        "work_order_code": "2022-05-26-002",
        "work_order_plan_start_time": 1653494400000,
        "work_order_plan_finish_time": 1653550499000,
        "process_plan_amount": 10.0000000000,
        "process_node_num": "20",
        "process_name": "工序-002"
      },
      {
        "org_id": 10896962,
        "process_id": 1654049715993002,
        "work_order_shift_name": null,
        "work_order_id": 1654049715993000,
        "work_order_code": "2022-06-01-001",
        "work_order_plan_start_time": 1654012800000,
        "work_order_plan_finish_time": 1654066756000,
        "process_plan_amount": 10.0000000000,
        "process_node_num": "10",
        "process_name": "工序-001"
      },
      {
        "org_id": 10896962,
        "process_id": 1654049715993003,
        "work_order_shift_name": null,
        "work_order_id": 1654049715993000,
        "work_order_code": "2022-06-01-001",
        "work_order_plan_start_time": 1654012800000,
        "work_order_plan_finish_time": 1654066756000,
        "process_plan_amount": 10.0000000000,
        "process_node_num": "20",
        "process_name": "工序-002"
      },
      {
        "org_id": 10896962,
        "process_id": 1654049715993140,
        "work_order_shift_name": null,
        "work_order_id": 1654049715993138,
        "work_order_code": "2022-05-25-100000",
        "work_order_plan_start_time": 1654012800000,
        "work_order_plan_finish_time": 1654071786000,
        "process_plan_amount": 10.0000000000,
        "process_node_num": "10",
        "process_name": "工序-001"
      },
      {
        "org_id": 10896962,
        "process_id": 1654049715993141,
        "work_order_shift_name": null,
        "work_order_id": 1654049715993138,
        "work_order_code": "2022-05-25-100000",
        "work_order_plan_start_time": 1654012800000,
        "work_order_plan_finish_time": 1654071786000,
        "process_plan_amount": 10.0000000000,
        "process_node_num": "20",
        "process_name": "工序-002"
      },
      {
        "org_id": 10896962,
        "process_id": 1654049715993323,
        "work_order_shift_name": null,
        "work_order_id": 1654049715993321,
        "work_order_code": "2022-05-25-100001",
        "work_order_plan_start_time": 1654012800000,
        "work_order_plan_finish_time": 1654072353000,
        "process_plan_amount": 5.9999990000,
        "process_node_num": "10",
        "process_name": "工序-001"
      },
      {
        "org_id": 10896962,
        "process_id": 1654049715993324,
        "work_order_shift_name": null,
        "work_order_id": 1654049715993321,
        "work_order_code": "2022-05-25-100001",
        "work_order_plan_start_time": 1654012800000,
        "work_order_plan_finish_time": 1654072353000,
        "process_plan_amount": 5.9999990000,
        "process_node_num": "20",
        "process_name": "工序-002"
      },
      {
        "org_id": 10896962,
        "process_id": 1655391354179110,
        "work_order_shift_name": "06-10-0002",
        "work_order_id": 1655388383503678,
        "work_order_code": "2022-06-17-0050-018",
        "work_order_plan_start_time": 1655226061000,
        "work_order_plan_finish_time": 1655296220000,
        "process_plan_amount": 4.0000000000,
        "process_node_num": "20",
        "process_name": "工序-002"
      },
      {
        "org_id": 10896962,
        "process_id": 1656330045481516,
        "work_order_shift_name": null,
        "work_order_id": 1656330045481514,
        "work_order_code": "2022-06-28-002",
        "work_order_plan_start_time": 1656345600000,
        "work_order_plan_finish_time": 1656425067000,
        "process_plan_amount": 100.0000000000,
        "process_node_num": "10",
        "process_name": "汉字2022_06_07418"
      },
      {
        "org_id": 10896962,
        "process_id": 1656330045481517,
        "work_order_shift_name": null,
        "work_order_id": 1656330045481514,
        "work_order_code": "2022-06-28-002",
        "work_order_plan_start_time": 1656345600000,
        "work_order_plan_finish_time": 1656425067000,
        "process_plan_amount": 100.0000000000,
        "process_node_num": "20",
        "process_name": "汉字2022_06_07_1654590755368"
      },
      {
        "org_id": 10896962,
        "process_id": 1656330045481631,
        "work_order_shift_name": null,
        "work_order_id": 1656330045481629,
        "work_order_code": "2022-06-28-003",
        "work_order_plan_start_time": 1656345600000,
        "work_order_plan_finish_time": 1656428816000,
        "process_plan_amount": 100.0000000000,
        "process_node_num": "10",
        "process_name": "汉字2022_06_07name403"
      },
      {
        "org_id": 10896962,
        "process_id": 1656330045481632,
        "work_order_shift_name": null,
        "work_order_id": 1656330045481629,
        "work_order_code": "2022-06-28-003",
        "work_order_plan_start_time": 1656345600000,
        "work_order_plan_finish_time": 1656428816000,
        "process_plan_amount": 100.0000000000,
        "process_node_num": "20",
        "process_name": "汉字2022_06_07name900"
      },
      {
        "org_id": 10896962,
        "process_id": 1656330045481633,
        "work_order_shift_name": null,
        "work_order_id": 1656330045481629,
        "work_order_code": "2022-06-28-003",
        "work_order_plan_start_time": 1656345600000,
        "work_order_plan_finish_time": 1656428816000,
        "process_plan_amount": 100.0000000000,
        "process_node_num": "30",
        "process_name": "汉字2022_06_07_1654590755368"
      },
      {
        "org_id": 10896962,
        "process_id": 1660197404137184,
        "work_order_shift_name": null,
        "work_order_id": 1660197404137182,
        "work_order_code": "2022081100000",
        "work_order_plan_start_time": 1660147200000,
        "work_order_plan_finish_time": 1660291820000,
        "process_plan_amount": 100.0000000000,
        "process_node_num": "10",
        "process_name": "zzw1pp"
      },
      {
        "org_id": 10896962,
        "process_id": 1660285847984155,
        "work_order_shift_name": "早班",
        "work_order_id": 1660285847984153,
        "work_order_code": "2022081200001",
        "work_order_plan_start_time": 1660233600000,
        "work_order_plan_finish_time": 1660722677000,
        "process_plan_amount": 150.0000000000,
        "process_node_num": "10",
        "process_name": "zzw1pp"
      },
      {
        "org_id": 10896962,
        "process_id": 1660883003878046,
        "work_order_shift_name": "早班",
        "work_order_id": 1660883003878044,
        "work_order_code": "csrz-0012",
        "work_order_plan_start_time": 1660842061000,
        "work_order_plan_finish_time": 1661583477000,
        "process_plan_amount": 20.0000000000,
        "process_node_num": "10",
        "process_name": "工序-001"
      },
      {
        "org_id": 10896962,
        "process_id": 1660883003878047,
        "work_order_shift_name": "早班",
        "work_order_id": 1660883003878044,
        "work_order_code": "csrz-0012",
        "work_order_plan_start_time": 1660842061000,
        "work_order_plan_finish_time": 1661583477000,
        "process_plan_amount": 20.0000000000,
        "process_node_num": "20",
        "process_name": "工序-002"
      },
      {
        "org_id": 10896962,
        "process_id": 1660899161453101,
        "work_order_shift_name": null,
        "work_order_id": 1660899161453099,
        "work_order_code": "2022082000006",
        "work_order_plan_start_time": 1660924800000,
        "work_order_plan_finish_time": 1661238696000,
        "process_plan_amount": 100.0000000000,
        "process_node_num": "10",
        "process_name": "工序_011"
      },
      {
        "org_id": 10896962,
        "process_id": 1661218007722068,
        "work_order_shift_name": null,
        "work_order_id": 1661218007722066,
        "work_order_code": "2022082300001",
        "work_order_plan_start_time": 1661184000000,
        "work_order_plan_finish_time": 1661222773000,
        "process_plan_amount": 100.0000000000,
        "process_node_num": "10",
        "process_name": "zzw1pp"
      },
      {
        "org_id": 10896962,
        "process_id": 1662709423693153,
        "work_order_shift_name": null,
        "work_order_id": 1662709423693151,
        "work_order_code": "22090062wl07",
        "work_order_plan_start_time": 1662652800000,
        "work_order_plan_finish_time": 1662713153000,
        "process_plan_amount": 321.0000000000,
        "process_node_num": "10",
        "process_name": "zzw1pp"
      },
      {
        "org_id": 10896962,
        "process_id": 1663853590049043,
        "work_order_shift_name": null,
        "work_order_id": 1663853590049041,
        "work_order_code": "2209006awl07",
        "work_order_plan_start_time": 1662652800000,
        "work_order_plan_finish_time": 1662713153000,
        "process_plan_amount": 321.0000000000,
        "process_node_num": "10",
        "process_name": "zzw1pp"
      },
      {
        "org_id": 10896962,
        "process_id": 1663853590049073,
        "work_order_shift_name": null,
        "work_order_id": 1663853590049071,
        "work_order_code": "2209006bwl07",
        "work_order_plan_start_time": 1662652800000,
        "work_order_plan_finish_time": 1662713153000,
        "process_plan_amount": 321.0000000000,
        "process_node_num": "10",
        "process_name": "zzw1pp"
      },
      {
        "org_id": 10896962,
        "process_id": 1663853590049103,
        "work_order_shift_name": null,
        "work_order_id": 1663853590049101,
        "work_order_code": "22090001wl07",
        "work_order_plan_start_time": 1662652800000,
        "work_order_plan_finish_time": 1662713153000,
        "process_plan_amount": 321.0000000000,
        "process_node_num": "10",
        "process_name": "zzw1pp"
      },
      {
        "org_id": 10896962,
        "process_id": 1665701477775026,
        "work_order_shift_name": "早班",
        "work_order_id": 1665701477775024,
        "work_order_code": "2210140028wl04",
        "work_order_plan_start_time": 1665676800000,
        "work_order_plan_finish_time": 1667184835000,
        "process_plan_amount": 299.0000000000,
        "process_node_num": "10",
        "process_name": "zzw1pp"
      },
      {
        "org_id": 10162960,
        "process_id": 1648448460429143,
        "work_order_shift_name": null,
        "work_order_id": 1648448460429141,
        "work_order_code": "pxy_0328_zdyl_sop_001",
        "work_order_plan_start_time": 1648396800000,
        "work_order_plan_finish_time": 1648626568000,
        "process_plan_amount": 100.0000000000,
        "process_node_num": "10",
        "process_name": "pxy-工序-0328-001"
      },
      {
        "org_id": 10162960,
        "process_id": 1648448460429144,
        "work_order_shift_name": null,
        "work_order_id": 1648448460429141,
        "work_order_code": "pxy_0328_zdyl_sop_001",
        "work_order_plan_start_time": 1648396800000,
        "work_order_plan_finish_time": 1648626568000,
        "process_plan_amount": 100.0000000000,
        "process_node_num": "20",
        "process_name": "pxy-工序-0328-002"
      },
      {
        "org_id": 10162960,
        "process_id": 1648554580577911,
        "work_order_shift_name": null,
        "work_order_id": 1648554580577909,
        "work_order_code": "pxy_0330_zdyl_sop_001",
        "work_order_plan_start_time": 1648396800000,
        "work_order_plan_finish_time": 1648626568000,
        "process_plan_amount": 100.0000000000,
        "process_node_num": "10",
        "process_name": "pxy-工序-0328-001"
      },
      {
        "org_id": 10162960,
        "process_id": 1648554580577912,
        "work_order_shift_name": null,
        "work_order_id": 1648554580577909,
        "work_order_code": "pxy_0330_zdyl_sop_001",
        "work_order_plan_start_time": 1648396800000,
        "work_order_plan_finish_time": 1648626568000,
        "process_plan_amount": 100.0000000000,
        "process_node_num": "20",
        "process_name": "pxy-工序-0328-002"
      },
      {
        "org_id": 10162960,
        "process_id": 1648606254203404,
        "work_order_shift_name": null,
        "work_order_id": 1648606254203402,
        "work_order_code": "pxy_0330_zdyl_sop_002",
        "work_order_plan_start_time": 1648396800000,
        "work_order_plan_finish_time": 1648626568000,
        "process_plan_amount": 100.0000000000,
        "process_node_num": "10",
        "process_name": "pxy-工序-0328-001"
      },
      {
        "org_id": 10162960,
        "process_id": 1648606254203405,
        "work_order_shift_name": null,
        "work_order_id": 1648606254203402,
        "work_order_code": "pxy_0330_zdyl_sop_002",
        "work_order_plan_start_time": 1648396800000,
        "work_order_plan_finish_time": 1648626568000,
        "process_plan_amount": 100.0000000000,
        "process_node_num": "20",
        "process_name": "pxy-工序-0328-002"
      },
      {
        "org_id": 10162960,
        "process_id": 1648624756085005,
        "work_order_shift_name": null,
        "work_order_id": 1648624756085003,
        "work_order_code": "pxy_0331_wy_001",
        "work_order_plan_start_time": 1648396800000,
        "work_order_plan_finish_time": 1648626568000,
        "process_plan_amount": 100.0000000000,
        "process_node_num": "10",
        "process_name": "pxy-工序-0328-001"
      },
      {
        "org_id": 10162960,
        "process_id": 1648624756085006,
        "work_order_shift_name": null,
        "work_order_id": 1648624756085003,
        "work_order_code": "pxy_0331_wy_001",
        "work_order_plan_start_time": 1648396800000,
        "work_order_plan_finish_time": 1648626568000,
        "process_plan_amount": 100.0000000000,
        "process_node_num": "20",
        "process_name": "pxy-工序-0328-002"
      },
      {
        "org_id": 10162960,
        "process_id": 1648718386189006,
        "work_order_shift_name": null,
        "work_order_id": 1648718386189004,
        "work_order_code": "m0331sc002333",
        "work_order_plan_start_time": 1648656000000,
        "work_order_plan_finish_time": 1649388707000,
        "process_plan_amount": 200.0000000000,
        "process_node_num": "10",
        "process_name": "m工序0331001"
      },
      {
        "org_id": 10162960,
        "process_id": 1648777084274144,
        "work_order_shift_name": null,
        "work_order_id": 1648777084274142,
        "work_order_code": "pxy_zdyl_0402_001",
        "work_order_plan_start_time": 1648396800000,
        "work_order_plan_finish_time": 1648626568000,
        "process_plan_amount": 100.0000000000,
        "process_node_num": "10",
        "process_name": "pxy-工序-0328-001"
      },
      {
        "org_id": 10162960,
        "process_id": 1648777084274145,
        "work_order_shift_name": null,
        "work_order_id": 1648777084274142,
        "work_order_code": "pxy_zdyl_0402_001",
        "work_order_plan_start_time": 1648396800000,
        "work_order_plan_finish_time": 1648626568000,
        "process_plan_amount": 100.0000000000,
        "process_node_num": "20",
        "process_name": "pxy-工序-0328-002"
      },
      {
        "org_id": 10162960,
        "process_id": 1648779665318924,
        "work_order_shift_name": null,
        "work_order_id": 1648779665318922,
        "work_order_code": "m0402sc001",
        "work_order_plan_start_time": 1648828800000,
        "work_order_plan_finish_time": 1649388707000,
        "process_plan_amount": 200.0000000000,
        "process_node_num": "10",
        "process_name": "m工序0331001"
      },
      {
        "org_id": 10162960,
        "process_id": 1648779665318971,
        "work_order_shift_name": null,
        "work_order_id": 1648779665318969,
        "work_order_code": "gmsop0402001",
        "work_order_plan_start_time": 1648828800000,
        "work_order_plan_finish_time": 1651299854000,
        "process_plan_amount": 2000.0000000000,
        "process_node_num": "10",
        "process_name": "0402工序01"
      },
      {
        "org_id": 10162960,
        "process_id": 1648897493156372,
        "work_order_shift_name": null,
        "work_order_id": 1648897493156370,
        "work_order_code": "gm0406001sm",
        "work_order_plan_start_time": 1649174400000,
        "work_order_plan_finish_time": 1650683288000,
        "process_plan_amount": 500.0000000000,
        "process_node_num": "10",
        "process_name": "0402工序01"
      },
      {
        "org_id": 10162960,
        "process_id": 1649921207967148,
        "work_order_shift_name": null,
        "work_order_id": 1649921207967146,
        "work_order_code": "m0414soptlbg-0222",
        "work_order_plan_start_time": 1649924475000,
        "work_order_plan_finish_time": 1650702078000,
        "process_plan_amount": 300.0000000000,
        "process_node_num": "10",
        "process_name": "msop工序-投料报工01"
      },
      {
        "org_id": 10162960,
        "process_id": 1650401600439074,
        "work_order_shift_name": null,
        "work_order_id": 1650401600439072,
        "work_order_code": "gm0420001sm",
        "work_order_plan_start_time": 1650384000000,
        "work_order_plan_finish_time": 1651284304000,
        "process_plan_amount": 200.0000000000,
        "process_node_num": "10",
        "process_name": "0402工序01"
      },
      {
        "org_id": 10162960,
        "process_id": 1650449485326026,
        "work_order_shift_name": null,
        "work_order_id": 1650449485326024,
        "work_order_code": "pxy_zdyl_0402_002",
        "work_order_plan_start_time": 1648396800000,
        "work_order_plan_finish_time": 1648626568000,
        "process_plan_amount": 100.0000000000,
        "process_node_num": "10",
        "process_name": "pxy-工序-0328-001"
      },
      {
        "org_id": 10162960,
        "process_id": 1650449485326027,
        "work_order_shift_name": null,
        "work_order_id": 1650449485326024,
        "work_order_code": "pxy_zdyl_0402_002",
        "work_order_plan_start_time": 1648396800000,
        "work_order_plan_finish_time": 1648626568000,
        "process_plan_amount": 100.0000000000,
        "process_node_num": "20",
        "process_name": "pxy-工序-0328-002"
      },
      {
        "org_id": 10162960,
        "process_id": 1650580139168063,
        "work_order_shift_name": null,
        "work_order_id": 1650580139168061,
        "work_order_code": "pxy_zdyl_0422_001",
        "work_order_plan_start_time": 1648396800000,
        "work_order_plan_finish_time": 1648626568000,
        "process_plan_amount": 100.0000000000,
        "process_node_num": "10",
        "process_name": "pxy-工序-0328-001"
      },
      {
        "org_id": 10162960,
        "process_id": 1650580139168064,
        "work_order_shift_name": null,
        "work_order_id": 1650580139168061,
        "work_order_code": "pxy_zdyl_0422_001",
        "work_order_plan_start_time": 1648396800000,
        "work_order_plan_finish_time": 1648626568000,
        "process_plan_amount": 100.0000000000,
        "process_node_num": "20",
        "process_name": "pxy-工序-0328-002"
      },
      {
        "org_id": 10162960,
        "process_id": 1650875664148039,
        "work_order_shift_name": null,
        "work_order_id": 1650875664148037,
        "work_order_code": "gm0425001sm",
        "work_order_plan_start_time": 1650816000000,
        "work_order_plan_finish_time": 1651308377000,
        "process_plan_amount": 2000.0000000000,
        "process_node_num": "10",
        "process_name": "pxy-工序-0328-001"
      },
      {
        "org_id": 10162960,
        "process_id": 1650924773144026,
        "work_order_shift_name": null,
        "work_order_id": 1650924773144024,
        "work_order_code": "gm0425002nsm",
        "work_order_plan_start_time": 1650902400000,
        "work_order_plan_finish_time": 1651285162000,
        "process_plan_amount": 200.0000000000,
        "process_node_num": "10",
        "process_name": "0402工序01"
      },
      {
        "org_id": 10162960,
        "process_id": 1651199333065144,
        "work_order_shift_name": null,
        "work_order_id": 1651199333065142,
        "work_order_code": "gm0429001tdl",
        "work_order_plan_start_time": 1651161600000,
        "work_order_plan_finish_time": 1651296315000,
        "process_plan_amount": 200.0000000000,
        "process_node_num": "10",
        "process_name": "0402工序01"
      },
      {
        "org_id": 10162960,
        "process_id": 1651241753541119,
        "work_order_shift_name": null,
        "work_order_id": 1651241753541117,
        "work_order_code": "lu000007",
        "work_order_plan_start_time": 1651420800000,
        "work_order_plan_finish_time": 1651574463000,
        "process_plan_amount": 100.0000000000,
        "process_node_num": "10",
        "process_name": "组装"
      },
      {
        "org_id": 10162960,
        "process_id": 1651241753541120,
        "work_order_shift_name": null,
        "work_order_id": 1651241753541117,
        "work_order_code": "lu000007",
        "work_order_plan_start_time": 1651420800000,
        "work_order_plan_finish_time": 1651574463000,
        "process_plan_amount": 100.0000000000,
        "process_node_num": "20",
        "process_name": "打磨"
      },
      {
        "org_id": 10162960,
        "process_id": 1651241753541381,
        "work_order_shift_name": null,
        "work_order_id": 1651241753541379,
        "work_order_code": "gm0505001tdl_M",
        "work_order_plan_start_time": 1651593600000,
        "work_order_plan_finish_time": 1653819203000,
        "process_plan_amount": 2000.0000000000,
        "process_node_num": "10",
        "process_name": "0504gm工序01"
      },
      {
        "org_id": 10162960,
        "process_id": 1651241753541382,
        "work_order_shift_name": null,
        "work_order_id": 1651241753541379,
        "work_order_code": "gm0505001tdl_M",
        "work_order_plan_start_time": 1651593600000,
        "work_order_plan_finish_time": 1653819203000,
        "process_plan_amount": 2000.0000000000,
        "process_node_num": "20",
        "process_name": "0504gm工序02"
      },
      {
        "org_id": 10162960,
        "process_id": 1651241753541546,
        "work_order_shift_name": null,
        "work_order_id": 1651241753541544,
        "work_order_code": "gm0505002tdl_A",
        "work_order_plan_start_time": 1651593600000,
        "work_order_plan_finish_time": 1653820479000,
        "process_plan_amount": 2000.0000000000,
        "process_node_num": "10",
        "process_name": "0504gm工序01"
      },
      {
        "org_id": 10162960,
        "process_id": 1651241753541547,
        "work_order_shift_name": null,
        "work_order_id": 1651241753541544,
        "work_order_code": "gm0505002tdl_A",
        "work_order_plan_start_time": 1651593600000,
        "work_order_plan_finish_time": 1653820479000,
        "process_plan_amount": 2000.0000000000,
        "process_node_num": "20",
        "process_name": "0504gm工序02"
      },
      {
        "org_id": 10162960,
        "process_id": 1651804784831092,
        "work_order_shift_name": null,
        "work_order_id": 1651804784831090,
        "work_order_code": "gmsop0506001tdl_M",
        "work_order_plan_start_time": 1651766400000,
        "work_order_plan_finish_time": 1653975582000,
        "process_plan_amount": 2000.0000000000,
        "process_node_num": "10",
        "process_name": "0504gm工序01"
      },
      {
        "org_id": 10162960,
        "process_id": 1651804784831093,
        "work_order_shift_name": null,
        "work_order_id": 1651804784831090,
        "work_order_code": "gmsop0506001tdl_M",
        "work_order_plan_start_time": 1651766400000,
        "work_order_plan_finish_time": 1653975582000,
        "process_plan_amount": 2000.0000000000,
        "process_node_num": "20",
        "process_name": "0504gm工序02"
      },
      {
        "org_id": 10162960,
        "process_id": 1651819181714180,
        "work_order_shift_name": null,
        "work_order_id": 1651819181714178,
        "work_order_code": "m0506bg-001",
        "work_order_plan_start_time": 1651766400000,
        "work_order_plan_finish_time": 1653725238000,
        "process_plan_amount": 200.0000000000,
        "process_node_num": "10",
        "process_name": "m工序0331001"
      },
      {
        "org_id": 10162960,
        "process_id": 1651819181714181,
        "work_order_shift_name": null,
        "work_order_id": 1651819181714178,
        "work_order_code": "m0506bg-001",
        "work_order_plan_start_time": 1651766400000,
        "work_order_plan_finish_time": 1653725238000,
        "process_plan_amount": 200.0000000000,
        "process_node_num": "20",
        "process_name": "m56测试用工序_1"
      },
      {
        "org_id": 10162960,
        "process_id": 1651841603891034,
        "work_order_shift_name": null,
        "work_order_id": 1651841603891032,
        "work_order_code": "gm0506002tdl_A",
        "work_order_plan_start_time": 1651842085000,
        "work_order_plan_finish_time": 1653820479000,
        "process_plan_amount": 2000.0000000000,
        "process_node_num": "10",
        "process_name": "0504gm工序01"
      },
      {
        "org_id": 10162960,
        "process_id": 1651841603891035,
        "work_order_shift_name": null,
        "work_order_id": 1651841603891032,
        "work_order_code": "gm0506002tdl_A",
        "work_order_plan_start_time": 1651842085000,
        "work_order_plan_finish_time": 1653820479000,
        "process_plan_amount": 2000.0000000000,
        "process_node_num": "20",
        "process_name": "0504gm工序02"
      },
      {
        "org_id": 10162960,
        "process_id": 1651895096603191,
        "work_order_shift_name": null,
        "work_order_id": 1651895096603189,
        "work_order_code": "gm0507001sm",
        "work_order_plan_start_time": 1651852800000,
        "work_order_plan_finish_time": 1653826987000,
        "process_plan_amount": 200.0000000000,
        "process_node_num": "10",
        "process_name": "0504gm工序01"
      },
      {
        "org_id": 10162960,
        "process_id": 1651895096603242,
        "work_order_shift_name": null,
        "work_order_id": 1651895096603240,
        "work_order_code": "gm0508002tdl_A",
        "work_order_plan_start_time": 1651941764000,
        "work_order_plan_finish_time": 1653820479000,
        "process_plan_amount": 2000.0000000000,
        "process_node_num": "10",
        "process_name": "0504gm工序01"
      },
      {
        "org_id": 10162960,
        "process_id": 1651895096603243,
        "work_order_shift_name": null,
        "work_order_id": 1651895096603240,
        "work_order_code": "gm0508002tdl_A",
        "work_order_plan_start_time": 1651941764000,
        "work_order_plan_finish_time": 1653820479000,
        "process_plan_amount": 2000.0000000000,
        "process_node_num": "20",
        "process_name": "0504gm工序02"
      },
      {
        "org_id": 10162960,
        "process_id": 1651895096603292,
        "work_order_shift_name": null,
        "work_order_id": 1651895096603290,
        "work_order_code": "gm0508001tdl_M",
        "work_order_plan_start_time": 1652020526000,
        "work_order_plan_finish_time": 1653819203000,
        "process_plan_amount": 2000.0000000000,
        "process_node_num": "10",
        "process_name": "0504gm工序01"
      },
      {
        "org_id": 10162960,
        "process_id": 1651895096603293,
        "work_order_shift_name": null,
        "work_order_id": 1651895096603290,
        "work_order_code": "gm0508001tdl_M",
        "work_order_plan_start_time": 1652020526000,
        "work_order_plan_finish_time": 1653819203000,
        "process_plan_amount": 2000.0000000000,
        "process_node_num": "20",
        "process_name": "0504gm工序02"
      },
      {
        "org_id": 10162960,
        "process_id": 1651895096603526,
        "work_order_shift_name": null,
        "work_order_id": 1651895096603524,
        "work_order_code": "gm0508003tdl_A",
        "work_order_plan_start_time": 1651941764000,
        "work_order_plan_finish_time": 1653820479000,
        "process_plan_amount": 2000.0000000000,
        "process_node_num": "10",
        "process_name": "0504gm工序01"
      },
      {
        "org_id": 10162960,
        "process_id": 1651895096603527,
        "work_order_shift_name": null,
        "work_order_id": 1651895096603524,
        "work_order_code": "gm0508003tdl_A",
        "work_order_plan_start_time": 1651941764000,
        "work_order_plan_finish_time": 1653820479000,
        "process_plan_amount": 2000.0000000000,
        "process_node_num": "20",
        "process_name": "0504gm工序02"
      },
      {
        "org_id": 10162960,
        "process_id": 1651895096603857,
        "work_order_shift_name": null,
        "work_order_id": 1651895096603855,
        "work_order_code": "pxy_zdyl_0509_001",
        "work_order_plan_start_time": 1648569600000,
        "work_order_plan_finish_time": 1648626568000,
        "process_plan_amount": 100.0000000000,
        "process_node_num": "10",
        "process_name": "pxy-工序-0328-001"
      },
      {
        "org_id": 10162960,
        "process_id": 1651895096603858,
        "work_order_shift_name": null,
        "work_order_id": 1651895096603855,
        "work_order_code": "pxy_zdyl_0509_001",
        "work_order_plan_start_time": 1648569600000,
        "work_order_plan_finish_time": 1648626568000,
        "process_plan_amount": 100.0000000000,
        "process_node_num": "20",
        "process_name": "pxy-工序-0328-002"
      },
      {
        "org_id": 10162960,
        "process_id": 1651895096603926,
        "work_order_shift_name": null,
        "work_order_id": 1651895096603924,
        "work_order_code": "gm0508004tdl_M",
        "work_order_plan_start_time": 1652020526000,
        "work_order_plan_finish_time": 1653819203000,
        "process_plan_amount": 2000.0000000000,
        "process_node_num": "10",
        "process_name": "0504gm工序01"
      },
      {
        "org_id": 10162960,
        "process_id": 1651895096603927,
        "work_order_shift_name": null,
        "work_order_id": 1651895096603924,
        "work_order_code": "gm0508004tdl_M",
        "work_order_plan_start_time": 1652020526000,
        "work_order_plan_finish_time": 1653819203000,
        "process_plan_amount": 2000.0000000000,
        "process_node_num": "20",
        "process_name": "0504gm工序02"
      },
      {
        "org_id": 10162960,
        "process_id": 1652162924776001,
        "work_order_shift_name": null,
        "work_order_id": 1652162924773000,
        "work_order_code": "gm0510002tdl_M",
        "work_order_plan_start_time": 1652112000000,
        "work_order_plan_finish_time": 1653796759000,
        "process_plan_amount": 2000.0000000000,
        "process_node_num": "10",
        "process_name": "0504gm工序01"
      },
      {
        "org_id": 10162960,
        "process_id": 1652167222364125,
        "work_order_shift_name": null,
        "work_order_id": 1652167222364123,
        "work_order_code": "pxy_zdyl_0510_001(hy_bzj=0)",
        "work_order_plan_start_time": 1648569600000,
        "work_order_plan_finish_time": 1648626568000,
        "process_plan_amount": 100.0000000000,
        "process_node_num": "10",
        "process_name": "pxy-工序-0328-001"
      },
      {
        "org_id": 10162960,
        "process_id": 1652167222364126,
        "work_order_shift_name": null,
        "work_order_id": 1652167222364123,
        "work_order_code": "pxy_zdyl_0510_001(hy_bzj=0)",
        "work_order_plan_start_time": 1648569600000,
        "work_order_plan_finish_time": 1648626568000,
        "process_plan_amount": 100.0000000000,
        "process_node_num": "20",
        "process_name": "pxy-工序-0328-002"
      },
      {
        "org_id": 10162960,
        "process_id": 1652172072903048,
        "work_order_shift_name": null,
        "work_order_id": 1652172072903046,
        "work_order_code": "pxy_zdyl_0510_002(hy_bzj=100)",
        "work_order_plan_start_time": 1648569600000,
        "work_order_plan_finish_time": 1648626568000,
        "process_plan_amount": 100.0000000000,
        "process_node_num": "10",
        "process_name": "pxy-工序-0328-001"
      },
      {
        "org_id": 10162960,
        "process_id": 1652172072903049,
        "work_order_shift_name": null,
        "work_order_id": 1652172072903046,
        "work_order_code": "pxy_zdyl_0510_002(hy_bzj=100)",
        "work_order_plan_start_time": 1648569600000,
        "work_order_plan_finish_time": 1648626568000,
        "process_plan_amount": 100.0000000000,
        "process_node_num": "20",
        "process_name": "pxy-工序-0328-002"
      },
      {
        "org_id": 10162960,
        "process_id": 1652184240624014,
        "work_order_shift_name": null,
        "work_order_id": 1652184240624012,
        "work_order_code": "mm0510sop-bg1",
        "work_order_plan_start_time": 1652112000000,
        "work_order_plan_finish_time": 1653444000000,
        "process_plan_amount": 200.0000000000,
        "process_node_num": "10",
        "process_name": "msop工序-投料报工01"
      },
      {
        "org_id": 10162960,
        "process_id": 1652184240624015,
        "work_order_shift_name": null,
        "work_order_id": 1652184240624012,
        "work_order_code": "mm0510sop-bg1",
        "work_order_plan_start_time": 1652112000000,
        "work_order_plan_finish_time": 1653444000000,
        "process_plan_amount": 200.0000000000,
        "process_node_num": "20",
        "process_name": "m56测试用工序_1"
      },
      {
        "org_id": 10162960,
        "process_id": 1652252773194002,
        "work_order_shift_name": null,
        "work_order_id": 1652252773194000,
        "work_order_code": "gm0511001tdl_M",
        "work_order_plan_start_time": 1652198400000,
        "work_order_plan_finish_time": 1653979459000,
        "process_plan_amount": 2000.0000000000,
        "process_node_num": "10",
        "process_name": "0504gm工序01"
      },
      {
        "org_id": 10162960,
        "process_id": 1652252829349017,
        "work_order_shift_name": null,
        "work_order_id": 1652252829349015,
        "work_order_code": "lu000104",
        "work_order_plan_start_time": 1652198400000,
        "work_order_plan_finish_time": 1652350327000,
        "process_plan_amount": 1.0000000000,
        "process_node_num": "10",
        "process_name": "组装"
      },
      {
        "org_id": 10162960,
        "process_id": 1652252829349018,
        "work_order_shift_name": null,
        "work_order_id": 1652252829349015,
        "work_order_code": "lu000104",
        "work_order_plan_start_time": 1652198400000,
        "work_order_plan_finish_time": 1652350327000,
        "process_plan_amount": 1.0000000000,
        "process_node_num": "20",
        "process_name": "打磨"
      },
      {
        "org_id": 10162960,
        "process_id": 1652260223818177,
        "work_order_shift_name": null,
        "work_order_id": 1652260223818175,
        "work_order_code": "gm0511002tdl_M",
        "work_order_plan_start_time": 1652198400000,
        "work_order_plan_finish_time": 1653819174000,
        "process_plan_amount": 2000.0000000000,
        "process_node_num": "10",
        "process_name": "0504gm工序01"
      },
      {
        "org_id": 10162960,
        "process_id": 1652260223818238,
        "work_order_shift_name": null,
        "work_order_id": 1652260223818236,
        "work_order_code": "gmsop0511001tdl_M",
        "work_order_plan_start_time": 1651766400000,
        "work_order_plan_finish_time": 1653975582000,
        "process_plan_amount": 2000.0000000000,
        "process_node_num": "10",
        "process_name": "0504gm工序01"
      },
      {
        "org_id": 10162960,
        "process_id": 1652260223818239,
        "work_order_shift_name": null,
        "work_order_id": 1652260223818236,
        "work_order_code": "gmsop0511001tdl_M",
        "work_order_plan_start_time": 1651766400000,
        "work_order_plan_finish_time": 1653975582000,
        "process_plan_amount": 2000.0000000000,
        "process_node_num": "20",
        "process_name": "0504gm工序02"
      },
      {
        "org_id": 10162960,
        "process_id": 1652284623702002,
        "work_order_shift_name": null,
        "work_order_id": 1652284623702000,
        "work_order_code": "gm0511004tdl_M",
        "work_order_plan_start_time": 1652020526000,
        "work_order_plan_finish_time": 1653819203000,
        "process_plan_amount": 2000.0000000000,
        "process_node_num": "10",
        "process_name": "0504gm工序01"
      },
      {
        "org_id": 10162960,
        "process_id": 1652284623702003,
        "work_order_shift_name": null,
        "work_order_id": 1652284623702000,
        "work_order_code": "gm0511004tdl_M",
        "work_order_plan_start_time": 1652020526000,
        "work_order_plan_finish_time": 1653819203000,
        "process_plan_amount": 2000.0000000000,
        "process_node_num": "20",
        "process_name": "0504gm工序02"
      },
      {
        "org_id": 10162960,
        "process_id": 1652284623702083,
        "work_order_shift_name": null,
        "work_order_id": 1652284623702081,
        "work_order_code": "gm0512001tdl",
        "work_order_plan_start_time": 1652284800000,
        "work_order_plan_finish_time": 1653753895000,
        "process_plan_amount": 2000.0000000000,
        "process_node_num": "10",
        "process_name": "0504gm工序01"
      },
      {
        "org_id": 10162960,
        "process_id": 1652284623702084,
        "work_order_shift_name": null,
        "work_order_id": 1652284623702081,
        "work_order_code": "gm0512001tdl",
        "work_order_plan_start_time": 1652284800000,
        "work_order_plan_finish_time": 1653753895000,
        "process_plan_amount": 2000.0000000000,
        "process_node_num": "20",
        "process_name": "0504gm工序02"
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
		"valid":"是否有效",
		"anaExecId":"分析执行记录ID",
		"repeatKey":"重复键",
		"data":{},
		"anaId":"分析告警配置ID"
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


