# API

这里是一些站长免费提供给大家的API

:::tip[目录]
> [天气API](#天气API)
> - [获取用户IP信息](#获取用户ip信息)
> - [获取地区信息](#获取地区信息)
> - [获取实时天气](#获取实时天气)
> - [获取未来24小时天气](#获取未来24小时天气)
> - [获取未来7天天气](#获取未来7天天气)
> - [获取未来生活指数](#获取未来生活指数)
> - [获取未来三天生活指数](#获取未来三天生活指数)
> - [获取天气灾害预警](#获取天气灾害预警)
> - [获取空气质量](#获取空气质量)
> - [获取未来24小时空气质量](#获取未来24小时空气质量)
> - [获取未来三天空气质量](#获取未来三天空气质量)
:::

## 天气API
:::note[]
免费无需任何Token即可查询指定目的地信息及其天气信息

信息来源：QWeather
:::

### 获取用户IP信息
:::important[]
- https://weather-api.seave.top/ipInfo
- 请求方式: GET
- 参数: 无
:::

### 获取地区信息
:::important[]
- https://weather-api.seave.top/lookupGeo
- 请求方式: GET
- 参数: location 地区名（可模糊搜索）
- 返回实例:
:::

### 获取实时天气
:::important[]
- https://weather-api.seave.top/now
- 请求方式: GET
- 参数: lon 经度, lat 纬度
:::

### 获取未来24小时天气
:::important[]
- https://weather-api.seave.top/24h
- 请求方式: GET
- 参数: lon 经度, lat 纬度
:::

### 获取未来7天天气
:::important[]
- https://weather-api.seave.top/7d
- 请求方式: GET
- 参数: lon 经度, lat 纬度
:::

### 获取未来生活指数
:::important[]
- https://weather-api.seave.top/lifeIndex/1d
- 请求方式: GET
- 参数: lon 经度, lat 纬度
:::

### 获取未来三天生活指数
:::important[]
- https://weather-api.seave.top/lifeIndex/3d
- 请求方式: GET
- 参数: lon 经度, lat 纬度
:::

### 获取天气灾害预警
:::important[]
- https://weather-api.seave.top/warning
- 请求方式: GET
- 参数: lon 经度, lat 纬度
:::

### 获取空气质量
:::important[]
- https://weather-api.seave.top/airquality/now
- 请求方式: GET
- 参数: lon 经度, lat 纬度
:::

### 获取未来24小时空气质量
:::important[]
- https://weather-api.seave.top/airquality/24h
- 请求方式: GET
- 参数: lon 经度, lat 纬度
:::

### 获取未来三天空气质量
:::important[]
- https://weather-api.seave.top/airquality/3d
- 请求方式: GET
- 参数: lon 经度, lat 纬度
:::
