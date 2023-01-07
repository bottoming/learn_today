# Methods

## 传统的methods

> get(获取)/post(提交)，简单网页，就两个操作

## 现在的methods

- get获取数据
- post新建数据
- patch/put 更新数据
- delete 删除数据

## Restful Api

- 一种新的API设计方法
- 传统API设计：把每个url当作一个功能
- Restful Api：把每个url当作一个唯一资源

 请求 | 传统API设计 | Restful Api
-| - | -
post | /api/create-blog | /api/blog
put | /api/update-blog?id=100 | /api/blog/100
get | /api/get-blog?id=100 | /api/blog/100
