#客户端与服务端接口规范
 1.通用接口模板<br>{<br>
    "request_id": "12092061666321",<br>
    "error_code": 0,<br>
    "error_msg": "",<br>
    "data": {}<br>
}<br>
error_code：0请求成功，－1请求失败，其他值待定<br>error_msg: 请求异常提示文案，例如：网络异常。。。<br>data：返回的真正数据都在这里
