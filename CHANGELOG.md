## Changelog

## 2021-12-13

- 增加店铺名匹配
- 优化captcha代码，抽离正则匹配规则

## 2021-12-01

- 增加远端数据来帮助退出隐藏店铺
- 优化代码，添加店铺名字，品牌名字

## 2021-11-28

- 添加启动检测配置文件
- 添加百度翻译-OCR功能，每个月免费额度为10000次
- 添加启动代码更新检测

## 2021-10-25

- 修改检测jd_wstool连接失败exception处理
- README增加websocket错误说明
- 修复遇到店铺页面失效死循环问题

## 2021-10-24

- 修改`config.yaml`中`shop.phone_tail_number`的配置说明
- 修改`config.yaml`中`shop.skip_shops`的配置说明
- 修复每次获取10条数据的问题，优化刷新缓存策略
- 增加了指定店铺注销，请查看详细配置说明
- 修复了一些bug
