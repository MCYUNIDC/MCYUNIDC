# MC云产品价格中心

## API 调用

### 1. 获取产品列表

```txt
GET https://idc.stay33.cn/cart/all
```
### 2. 获取产品返回

```json
{
  "status": 200,
  "msg": "请求成功",
  "data": {
    "products": [
      {
        "id": 26, //产品组ID
        "name": "代理商", //产品组类型
        "products": [
          {
            "id": 107,
            "type": "other", //产品类型
            "name": "代理 L1", //产品名称
            "description": "香港折扣：9.5 折&lt;/br&gt;\n售前服务：免费提供&lt;/br&gt;\n售后服务：免费提供&lt;/br&gt;\n技术服务：免费提供&lt;/br&gt;\n代理资源：免费提供&lt;/br&gt;\n一键部署：免费提供&lt;/br&gt;\n购买后将自动退回您的账户，余额无法退款和提现！" //产品描述
          },
          {
            "id": 109, //产品ID
            "type": "other", //产品类型
            "name": "代理 L2", //产品名称
            "description": "香港折扣：8.8 折&lt;/br&gt;\n售前服务：免费提供&lt;/br&gt;\n售后服务：免费提供&lt;/br&gt;\n技术服务：免费提供&lt;/br&gt;\n代理资源：免费提供&lt;/br&gt;\n一键部署：免费提供&lt;/br&gt;\n购买后将自动退回您的账户，余额无法退款和提现！" //产品描述
          }
        ]
      },
      {
        "id": 32, //产品组ID
        "name": "短信服务", //产品组类型
        "products": [...], //产品列表
      },
    ]
  }
}
```

### 3. 产品组链接

```txt
https://idc.stay33.cn/cart?gid=产品组ID
```

### 4.购买产品链接

```txt
https://idc.stay33.cn/cart?action=configureproduct&pid=产品ID
```



