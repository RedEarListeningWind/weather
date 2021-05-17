# C 天气
一个天气查询的 Android 软件

---

# 说明 

1. 为什么不加个 启动页 ?
    > 人们打开天气类软件第一需求是看天气
2. 支持的最低 Android 版本?
    > 8.0
3. 为什么不适配低 Android 版本?
    > ui 中的一些文字需要自适应大小,我尝试写一个类似的功能但发现能力不够,所以用了 Android 8.0 新加入的功能。

# 预期达到的功能

1. 根据 GPS 定位查询 天气
2. 根据 地名 查询 经纬度
3. 根据 经纬度 查询 地名
4. 能添加多个监视页面
5. 正反序列化 json 实现文件读写 (用户设置的保存与读取)
6. 使用多线程加快网络访问

---

# 历史版本

## v0.83 beta

1. 实现 GPS 定位查询 天气    ->    使用 彩云天气 的API
2. 实现 地名 查询 经纬度     ->    使用 百度 的API
3. 实现 经纬度 查询 地名     ->    使用 百度 的API
4. 正反序列化 json          ->    使用 Jackson 框架
5. 网络访问                 ->    使用 OkHttp 框架
6. 使用多线程加快网络访问    ->    使用 JDK 的 java.util.concurrent.ThreadPoolExecutor

注意事项:
1. 权限处理不太完善

![image](https://user-images.githubusercontent.com/58614744/118510363-7a834280-b763-11eb-8b09-b0295af3030d.png)


----
