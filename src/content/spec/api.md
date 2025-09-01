# API

这里是一些站长免费提供给大家的API

:::note[天气API]
免费无需任何Token即可查询指定目的地信息及其天气信息

信息来源：QWeather
:::

### 获取用户IP信息
:::important[]
- https://weather-api.seave.top/ipInfo
- 请求方式: GET
- 参数: 无
- 返回实例:
```json
{
  "code": 200,
  "data": {
    "ip": "5.34.218.160",
    "info": {
      "country": "US",
      "city": "Los Angeles",
      "latitude": "34.05223",
      "longitude": "-118.24368"
    }
  },
  "message": "获取IP信息成功"
}
```
:::

### 获取地区信息
:::important[]
- https://weather-api.seave.top/lookupGeo
- 请求方式: GET
- 参数: location 地区名（可模糊搜索）
- 返回实例:
```json
{
  "code": 200,
  "data": [
    {
      "name": "北京",
      "id": "101010100",
      "lat": "39.90499",
      "lon": "116.40529",
      "adm2": "北京",
      "adm1": "北京市",
      "country": "中国",
      "tz": "Asia/Shanghai",
      "utcOffset": "+08:00",
      "isDst": "0",
      "type": "city",
      "rank": "10",
      "fxLink": "https://www.qweather.com/weather/beijing-101010100.html"
    },
    // ...
  ],
  "message": "查询地址成功 - 结果由QWeather提供"
}
```
:::