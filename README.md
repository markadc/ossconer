# 项目说明
- Python交互OSS，更方便地使用一些常用功能
- python3.10+
- 上传、下载、获取key的互联网地址、判断key是否存在、删除key、移动key、遍历目录的所有key、获取key的文件大小等

# 安装
`pip install ossconer`

# 使用教程
## 连接OSS
```python
OSS_CONFIG = {
    'key_id': "<ID>",
    'key_secret': "<secret>",
    'endpoint': "<区域>",
    'bucket': "<桶名>"
}
OSS = OssControler(**OSS_CONFIG)
```
