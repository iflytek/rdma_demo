# RDMA Demo

这是一个基于 RDMA (Remote Direct Memory Access) 的简单演示项目，展示了如何使用 RDMA 进行远程内存访问。

## 项目结构

- `rdma_server.py`: RDMA 服务器端实现
- `rdma_client.py`: RDMA 客户端实现
- `LICENSE`: 项目许可证文件

## 功能特点

- 支持 RDMA 远程内存访问
- 实现了基本的 RDMA 写入操作
- 包含服务器和客户端的完整实现
- 支持自定义传输数据大小和端口配置

## 使用方法

### 启动服务器

```bash
python rdma_server.py
```

默认参数：
- 数据大小：1024 字节
- 端口：39999

### 启动客户端

```bash
python rdma_client.py
```

默认参数：
- 服务器地址：127.0.0.1
- 服务器端口：29999
- 数据大小：1024 字节

## 注意事项

- 需要 RDMA 硬件支持
- 确保服务器和客户端网络互通
- 根据实际环境调整设备名称和网络参数

## 许可证

本项目采用 Apache License 2.0 许可证，详见 LICENSE 文件。 